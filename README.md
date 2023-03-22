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
