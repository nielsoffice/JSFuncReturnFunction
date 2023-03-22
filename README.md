# JSFuncReturnFunction
JavaScript Function returning function 

```JS
 const celebrate = function(celebrate) {
   return function (name) {
    console.log(`${celebrate} ${name}`);
   }
 } 

// USAGE:
 const celebratingBirthday = celebrate('Happy Bornday!');
 celebratingBirthday('nielsoffice');

 // OR 
 celebrate('Happy Bornday!')('Ginro');
 ```
 
 ```JS
 // console.log | Result
 Happy Bornday! nielsoffice
 Happy Bornday! Ginro
 ```

```JS
// JS Closure 

let y;

const x = function() {
  const z = 9;

  y = function() {
    console.log(z);
  }
}

// x function
x();
// Call y function will be avaialble once you call x function 
// This is Closure
y(); 

```

 ```JS
 // console.log | Result
 9
 ```
