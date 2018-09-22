## CRUD Operations:
###### 1. ARRAYS:

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



