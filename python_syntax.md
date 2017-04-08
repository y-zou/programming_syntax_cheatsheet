# Python Syntax Cheatsheet
For the purpose of refreshing your knowledge before competitive coding.

## Read the file
	```python
	data_path = r'C:\Desktop\sample.txt'
  	data = open(data_file, 'rb')
  	result = [ ]
  	for line in data:
    	result.append([int(line.split(' '))])
	```
  
**or**:		
	`result = [int(i) for i in data.readlines().split(' ')]`
 
	`data.readline()  #read one line`
	`next(data)       #skip one line`
	 
**write to file**

	```python
	result_path = r'V:\Desktop\result.txt'
	result = open(result_path,'w')
	for i in result:
	result.write("%d\n" % i)
	```

## misc about list

**format**

	```python
	myList = [1,3,5]
	map(str,myList)
	# >>> ['1','3','5']
	'-'.join(map(str,myList))
	# >>> '1-2-4'
	```
	
## misc about dict
	
	```python
	#count for dupulication in a list
	myDict = {}
	for i in myList:
		if i not in myDict:
			myDict.update({i:1})
		else:
			myDict[i] += 1	#value +1
	```			
