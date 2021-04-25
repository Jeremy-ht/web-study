# JavaScript



- typeof

- instanceof





## Object





## Array

- **push()**	
- **pop()**

- **shift()**
- **unshift()**



- **reverse()**
- **sort()**



- **concat()**
- **slice()**	



- ##### splice()

  ```js
  # 删除	可以删除任意数量的项		需要2个参数
  splice(索引，要删除的项数)
  	const arr = [1,2,3,4]
  	arr.splice(1,2)		// arr = [1,4]
  
  
  # 插入	可以在指定位置插入任意数量的项		需要3个参数	
  splice(起始位置，0 （要删除的项数）, 要插入的项)	// 插入时第二个参数为0
  	const arr = [1,2,3,4]
  	arr.splice(1,0,5,6,7)		// arr = [1,5,6,2,3,4]
  
  
  # 替换	可以在指定位置替换任意数量的项，且同时删除任意数量的项		需要3个参数
  splice(起始位置，要删除的项数, 要插入的项)	// 删除项和插入项数目不需要相等
  	const arr = [1,2,3,4]
  	arr.splice(1,2,5,6,7)		// arr = [1,5,6,7,4]
  
  ```



- **indexOf()**

- **lastIndexOf()**

  ```js
  # indexOf() 从头开始查找  lastIndexOf() 从末尾开始查找
  
  const numbers = [1,2,3,4,5,4,3,2,1]
      
  # indexOf(查找的项)
  	numbers.indexOf(3)	// 2
  # indexOf(查找的项, 查找的起点索引位置)
  	numbers.indexOf(3, 4)	// 6
  ```


- **迭代**

  ```js
  # filter()
  
  # forEach()
  
  # map()
  
  # some()
  
  # every()
  
  
  
  
  ```




- **reudce()**
- **reduceRight()**





## Date



## Math

![1618920775880](assets/1618920775880.png)

![1618921563296](assets/1618921563296.png)

```js
# min()
# max()

# ceil()	向上取整
	Math.ceil(25.9)	// 26
	Math.ceil(25.1)	// 26
# floor()	向下取整
	Math.floor(25.9)	// 25
	Math.floor(25.1)	// 25
# round()	四舍五入
    Math.round(25.9)	// 26
    Math.round(25.1)	// 25

# random()	返回0到1之间的随机数，不包括0和1
	值 = Math.floor(Math.random() * 可能值的总数 + 第一个可能出现的值)
    1-10	Math.floor(Math.random() * 10 + 1)
	3-10	Math.floor(Math.random() * 10 + 3)
```





## String

```js
# charAt()		charCodeAt()
	const str = 'hello'
    str.charAt(1)	// 'e'
	str.charCodeAt(1)	// '101'
	str[1]	//  'e' (注：浏览器版本)

# concat()

# slice()	substr()	substring()

# indexOf()		lastIndexOf()

# trim()	trimLeft()	trimRight()

# toLowerCase()		toUpperCase()
```



## Global

![1618920597667](assets/1618920597667.png)






















