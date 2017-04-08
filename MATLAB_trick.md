# matlab

### linear vector

  ```matlab
  v = 1:2:10
  ans = 1 3 5 7 9
  ```
  ```matlab
  v = linspace(1,5,5)
  ans = 1 2 3 4 5
  ```
 ### mapping in matlab
 
  ```matlab
  x = [1,2,3]
  fx = arrayfun(@(i) i+1,x) %f(x) = x+1
  ```
 ### cell
 
 ```matlab
 x = cell{3,3}  %initialize
 
 cell{1,end+1} = [1,2,3]  %attach new element to cell
 
 cell{1,:} = [] %delete the first row
 ```
  
 
  
  
