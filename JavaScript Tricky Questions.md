
1) What would be the output of below code: 

var salary = "1000$";

 (function () {
     console.log("Original salary was " + salary);

     var salary = "5000$";

     console.log("My New Salary " + salary);
})();

Ans:- Undefined
      5000$
   
  
2) What would be the output of below code: 
var testVar = "I'm a global";

function example( )
{
  console.log(testVar);  
  
  var testVar = "I'm a local var";
  console.log(testVar);  
}

example();

Ans:- undefined
       I'm a local var
