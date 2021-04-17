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








































