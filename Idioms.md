
## swap variables x and y
```
tmp = x;
x = y;
y = tmp;

```

## Traverse an array
``` java
  for (i=0;i<a.size();i++){
      // do something
  }
  
  
```

## Find the smallest 
``` java
  
  smallest = a[0];
  for (i=0;i<a.size();i++){
      if (a[i] < smallest){
          smallest = a[i];
          }
  }
  
```

## Calculate the sum
``` java
  
  sum = 0;
  for (i=0;i<a.size();i++){
      sum = sum + a[i]
  }
  
```

## Traverse a linked list

``` java
  currentNode = L;
  while (currentNode != null){
      // do something
      currentNode = currentNode.getNext();
  }
  
```


## Find the smallest
``` java
  currentNode = L;
  smallest = currentNode.getData();
  while (currentNode != null){
      if (currentNode.getData() < smallest){
          smallest = currentNode.getData();
          }
      currentNode = currentNode.getNext();
  }
  
```

## Calculate the sum

``` java
  currentNode = L;
  sum = 0;
  while (currentNode != null){
      sum = sum + currentNode.getData();
      currentNode = currentNode.getNext();
  }
  
```

## process a 2D array
Notice that the inner 3 lines is the traverse a 1D array idiom and the
outer loop is also a traverse a 1D array idiom.

``` java
  for (row = 0; row < a.size(); row++){
  
      for (col = 0; col < a[row].size(); col++){
          // do stuff
          }
  
  
  }
  
  
  
  
```
