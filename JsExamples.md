
### 1. ARRAYS:
The Array object is used to store multiple values in a single variable.
###### Array Properties:
   Property  | Definition
 ------------ |---------------
constructor  | returns a reference to the array function that created the instance's 
length  | xy
prototype  | 12

```js
    let arr = new Array ();
    let arr = [];
    let arr = [‘1’,’A’,’a’];
```
    + ###### ADDING DATA	
```js
          //@end
          arr.push(‘x’);            [‘1’,’A’,’a’,’x’];
          arr[arr.length] = ‘x’;    [‘1’,’A’,’a’,’x’];
          
          //@beginning    
          arr.unshift(‘x’);         [‘x’,‘1’,’A’,’a’];
```
+ ###### DELETING
```js
          //@end
          arr.pop();            [‘1’,’A’];
          
          //@beginning
          arr.shift();          [’A’,’a’];
```



