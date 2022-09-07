Question--1
/****************************************************************************
<!-- 1)1)Find the culprit ...fix.html -->
//****************************************************************************

<!DOCTYPE html>
<html>
<body>
 <script>
 alert( "I'm JavaScript!");
 </script>
 Whats the error in this ?
</body>
</html>

//***************************************************************************
<!-- 1)2)Find the culprit and invoke the alert ...fix.html -->
//****************************************************************************

<!DOCTYPE html>
<html>
    <body>
        <script src="script.js"></script>
    </body>
</html>
<!--  script.js -->
alert("I'm invoked!");

//****************************************************************************
<!-- 1)3)Explain the below how it works....explain.html -->
//****************************************************************************
<!DOCTYPE html>
<html>
    <body>
        <script src="script.js"></script>
    </body>
</html>

<!--  script.js -->

alert("I'm JavaScript!");// output of Alert shows I'm JavaScript! 
alert('Hello') /* this line is not having semicolon but output of Alert shows
                   Hello and then for good practice we can use semicolon.*/
alert(`Wor
 ld`)// output of alert shows Wor is in oneline Id is in anotherline.
alert(3 +
1
+ 2); /* this is multiple line code and its working .yes, output of alert shows 6. 
         alert();in between the alert bracket it done everyline action perfectly 
         and show the output.*/

//****************************************************************************
<!-- 1)4)Fix the below to alert Guvi geek....fix.html-->
//****************************************************************************

<!DOCTYPE html>
<html>
    <body>
        <script src="script.js"></script>
    </body>
</html>

<!--  script.js -->

let admin=9, fname=10.5; 
fname = "Guvi";
lname = "geek"
admin =  fname +" "+lname;
alert( admin ); // "Guvi geek"

//****************************************************************************
<!-- 1)5)Fix the below to alert hello Guvi geek....fix.html-->
//****************************************************************************

<!DOCTYPE html>
<html>
    <body>
        <script src="script.js"></script>
    </body>
</html>

<!--  script.js -->
let fname=10.5; 
fname = "Guvi";
lname = "geek"
let name = fname+" "+lname;
alert( `hello ${name}` );

//****************************************************************************
<!-- 1)6)Fix the below to alert sum of two numbers....fix.html-->
//****************************************************************************

<!DOCTYPE html>
<html>
    <body>
        <script src="script.js"></script>
    </body>
</html>

<!--  script.js -->
let a = Number(prompt("First number?",''));
let b = Number(prompt("Second number?",''));
alert(a + b);

//****************************************************************************
<!-- 1)7)Explain Why the Code is blasted and how to diffuse it and get “Diffused”-->
//****************************************************************************

var a = "2" > "12";// 
//Don't touch below this
if (a) {
  console.log("Code is Blasted");
}
else
{
  console.log("Diffused"); 
}

The above code considers the values of var a is  “2” and “12” as strings and 
compares them with their decimal ASCII value by using the  operator > that gives 
output  Code is blasted.

Andthen you can use operator < output  get “Diffused”
var a = "2" < "12";// 
//Don't touch below this
if (a) {
  console.log("Code is Blasted");
}
else
{
  console.log("Diffused"); 
}

//****************************************************************************
<!-- 1)8)How to get the success in console -->
//****************************************************************************
let a = Number(prompt("Enter a number?"));//if the input is not a number you will get output success.
//Don't modify any code below this
if (a) {
 console.log( 'OMG it works for any number inc 0' );
}
else
{
 console.log( "Success" );
}

//****************************************************************************
<!-- 1)9)How to get the correct score in console. -->
//****************************************************************************
let value = Number(prompt('How many runs you scored in this ball'));
if (value === 4) {
      console.log("You hit a Four");
} else if (value === 6) {
      console.log("You hit a Six");
} else {
      console.log("I couldn't figure out");
}

//****************************************************************************
<!-- 1)10)Fix the code to welcome the Employee -->
//****************************************************************************

let login = 'Employee';
let message = (login == 'Employee') ?'Welcome Employee':/* we used multiple conditional operator and 
                                                         the output statement of this condition added 
                                                          (login == 'Employee') ?'Welcome Employee':*/
  (login == 'Director') ? 'Greetings' :
  (login == '') ? 'No login' :
  '';
console.log(message);
//****************************************************************************
<!-- 1)11)Fix the code to welcome the boss -->
//****************************************************************************

let message;
if (null || 2 || undefined )
{
 message = "welcome boss";
}
else
{
 message = "Go away";
}
  console.log(message);

//****************************************************************************
<!-- 1)12)Fix the code to welcome -->
//****************************************************************************

let message;
let lock ="";
//Dont change any code below this 
if (null || lock || undefined )
{
  message = "Go away";
}
else
{
 message = "welcome";
}
  console.log(message);
//****************************************************************************
<!-- 1)13)Fix the code to welcome -->
//****************************************************************************

let message;
let lock = "";
//Dont change any code below this
if (lock && " " || undefined )
{
  message = "Go away";
}
else
{
 message = "welcome";
}
console.log(message);

//****************************************************************************
<!-- 1)14)Change the code to print -->
//****************************************************************************
let i=3;
while ( i ) {
  console.log(i);
  --i; 
}
//****************************************************************************
<!-- 1)15)Change the code to print 1 to 10 in 4 lines -->
//****************************************************************************
let num =10;
let k="";
for(let i=1;i<=num;i++)
{
k = k+i+" ";

}
console.log(k);
console.log(k);
console.log(k);
console.log(k);
//****************************************************************************
<!-- 1)16)Change the code to print even numbers -->
//****************************************************************************

//You are allowed to modify only one character 
for (let num = 2; num <= 20; num += 2) {
    
    console.log(num);
  }
//****************************************************************************
<!-- 1)17)Change the code to print all the gifts -->
//****************************************************************************

let gifts = ["teddy bear", "drone", "doll"];
for (let i = 0; i < 3; i++) {
  console.log('Wrapped ${'gifts[i]'} and added a bow!');
}



Question--2

/****************************************************************************
<!-- 2)1)Write a code to print the numbers in the array -->
//****************************************************************************
//Output: 1234567891011
var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
var new_string = "";
 
for (var i = 0; i <numsArr.length; i++) {
 new_string =new_string + numsArr[i]+"";
}
console.log(new_string);
//****************************************************************************
<!-- 2)2)Write a code to print the numbers in the array -->
//****************************************************************************
//Output: 1,2,3,4,5,6,7,8,9,10,11
let numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
let new_string = "";
 
for (let i = 0; i < 11; i++) {
 new_string += numsArr[i]+ ",";
}
let b = new_string.slice(0,-1);
console.log(b);
//****************************************************************************
<!-- 2)3)Write a code to print from last to first with spaces (Make sure there is no space after the last element 1) -->
//****************************************************************************
//Output: 11 10 9 8 7 6 5 4 3 2 1
let new_string = "";
for (var i = 11; i > 0; i -- ) {
 new_string += i + " ";
}
console.log(new_string.trimEnd());
//****************************************************************************
<!-- 2)4)Write a code to replace the array value — If the number is even, replace it with ‘even’. -->
//****************************************************************************
//Output:[ 1, “even”, 3, “even”, 5, “even”, 7, “even”, 9, “even”, … ]
var numsArr = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
for (var i = 0; i <= 10; i++) {
  if (numsArr[i] % 2 === 0) {
    numsArr[i] = "even";
  }
}
console.log(numsArr);
//****************************************************************************
<!-- 2)5)Write a code to replace the array value — If the index is even, replace it with ‘even’. -->
//****************************************************************************
//Output: [ “even”, 2, “even”, 4, “even”, 6, “even”, 8, “even”, 10, … ]
var numsArr = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
for (var i = 0; i <= 10; i++) {
  if (i % 2 === 0) {
    numsArr[i] = "even";
  }
}
console.log(numsArr);
//****************************************************************************
<!-- 2)6)Write a code to add all the numbers in the array-->
//****************************************************************************
//Output: 66
//way 1:
var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
var sum=0;
for (let i = 0; i <=10; i++) {
 sum = sum+numsArr[i];
}
console.log(sum);
//way 2:
let numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
let sum = numsArr.reduce((acc,cur)=>{
    return acc+cur;
});
console.log(sum);
//****************************************************************************
<!-- 2)7)Write a code to add the even numbers only-->
//****************************************************************************
//Output: 30
var numsArr = [ 1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
var sum=0;
for (let i = 0; i <=10; i++) {
 if(numsArr[i]%2==0){
 sum = sum+numsArr[i];
}
}
console.log(sum);
//****************************************************************************
<!-- 2)8)Write a code to add the even numbers and subract the odd numbers-->
//****************************************************************************
//Output: 94
var numsArr = [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, 11];
var sum = 100;
for (var i = 0; i <= 10; i++) {
  if (numsArr[i] % 2 === 0) {
    sum += numsArr[i];
  } else {
    sum -= numsArr[i];
  }
}
console.log(sum);
//****************************************************************************
<!-- 2)9)Write a code to print inner arrays-->
//****************************************************************************
//Output:
 [ 1, 2, 3, 4, 5 ]
 [ 6, 7, 8, 9, 10, 11 ]
var numsArr = [
    [1, 2, 3, 4, 5],
    [6, 7, 8, 9, 10, 11],
  ];
  for (var i = 0; i < numsArr.length; i++) {
    console.log(numsArr[i]);
  }
//****************************************************************************
<!-- 2)10) Write a code to print elements in the inner arrays-->
//****************************************************************************
// Output: 1234567891011
var numsArr = [
    [1, 2, 3, 4, 5],
    [6, 7, 8, 9, 10, 11],
  ];
  var str_all = "";
  for (var i = 0; i < numsArr.length; i++) {
    var inner_array = numsArr[i];
    for (var j = 0; j < inner_array.length; j++) str_all += inner_array[j];
  }
  console.log(str_all);
//****************************************************************************
<!-- 2)11) Fixed code to replace the array value — If the index is even, replace it with ‘even’.-->
//****************************************************************************
// Output: [ [“even”, 2, “even”, 4, “even”], [6, “even”, 8, “even”, 10, …] ]
var numsArr = [
    [1, 2, 3, 4, 5],
    [6, 7, 8, 9, 10, 11],
  ];
  var str_all = "";
  var count = 0;
  for (var i = 0; i < numsArr.length; i++) {
    var inner_array = numsArr[i];
    for (var j = 0; j < inner_array.length; j++) {
      if (count % 2 === 0) {
        numsArr[i][j] = "even";
      }
      count++;
    }
  }
  console.log(numsArr);
//****************************************************************************
<!-- 2)12) Fixed code to print elements in the inner arrays in reverse-->
//****************************************************************************
// Output: 11 10 9 8 7 6 5 4 3 2 1
var numsArr = [
    [1, 2, 3, 4, 5],
    [6, 7, 8, 9, 10, 11],
  ];
  var str_all = "";
  for (var i = numsArr.length - 1; i >= 0; i--) {
    var inner_array = numsArr[i];
    for (var j = inner_array.length - 1; j >= 0; j--)
 {
      if (i === 0 && j === 0)
{
 str_all += inner_array[j];
}
      else {
str_all += inner_array[j] + " ";
}
    }
  }
  console.log(str_all);
//****************************************************************************
<!-- 2)13) Fixed code to add elements in the inner arrays based on odd or even values-->
//****************************************************************************
/*Output:
36
30*/

var numsArr = [
    [1, 2, 3, 4, 5],
    [6, 7, 8, 9, 10, 11],
  ];
  var sum_odd = 0;
  var sum_even = 0;
  for (var i = 0; i < numsArr.length; i++) {
    var inner_array = numsArr[i];
    for (var j = 0; j < inner_array.length; j++) {
      if (inner_array[j] % 2 !== 0) {
        sum_odd += inner_array[j];
      } else {
        sum_even += inner_array[j];
      }
    }
  }
  console.log(sum_odd);
  console.log(sum_even);
  
  Question--3
  
  //*************************************************************************
// 1.Fixed code to get the largest of three.
//*************************************************************************
let aa = (f, s, t) => {
    console.log(f, s, t);
    if (f > s && f > t) {
      console.log(f);
    } else if (s > f && s > t) {
      console.log(s);
    } else {
      console.log(t);
    }
  };
  aa(1, 2, 3);
  
  
  //*************************************************************************
  // 2.Fixed code to Sum of the digits present in the number
  //*************************************************************************
  
  let n = 123;
  console.log(add(n));
  function add(n) {
    let sum = 0;
    while (n !== 0) {
      sum += n % 10;
      n = parseInt(n / 10);
    }
    return sum;
  }
  
  //*************************************************************************
  // 3.Fixed code to Sum of all numbers using IIFE function
  //*************************************************************************
  
  const arr = [9, 8, 5, 6, 4, 3, 2, 1];
  (function addition(arr) {
    let sum = 0;
    for (var i = 0; i < arr.length; i++) sum += arr[i];
    console.log(sum);
  })(arr);
  
  //*************************************************************************
  // 4.Fixed code to gen Title caps.
  //*************************************************************************
  
  var arr = ["guvi", "geek", "zen", "fullstack"];
  var ano = function (arro) {
    for (var i = 0; i <= arro.length; i++) {
      console.log(arro[i][0].toUpperCase() + arro[i].substr(1));
    }
  };
  ano(arr);
  
  //*************************************************************************
  // 5.Fixed code to return the Prime numbers
  //*************************************************************************
  
  const newArray = [1, 3, 2, 5, 10];
  const myPrime = newArray.filter((num) => {
    if (num === 1 || num === 0) return false;
    for (let i = 2; i <= Math.sqrt(num); i++) {
      if (num % i === 0) {
        return false;
      }
    }
    return num;
  });
  console.log(myPrime);
  
  
  //*************************************************************************
  // 6.Fixed code to sum the number in that array
  //*************************************************************************
  
  const num = [10, 20, 30, 40, 50, 60, 70, 80, 90, 100];
  const sum = num.reduce((a, b) => a + b);
  console.log(sum);
  
  
  //*************************************************************************
  // 7.Fixed code to gen Title caps.
  //*************************************************************************
  var arr = ["guvi", "geek", "zen", "fullstack"];
  (function (arr) {
    for (var i = 0; i <= arr.length; i++) {
      console.log(arr[i][0].toUpperCase() + arr[i].substr(1));
    }
  })(arr);
  
  //*************************************************************************
  // 8.print all odd numbers in an array using IIFE function
  //*************************************************************************
  
  var arr = [1, 2, 3, 5, 7, 79, 7, 2, 6, 9, 4];
  (function (arr) {
    for (var i = 0; i < arr.length; i++) {
      if (arr[i] % 2 === 1) {
        console.log(arr[i]);
      }
    }
  })(arr);
  
  //*************************************************************************
  // 9.Fixed code to reverse.
  //*************************************************************************
  
  (function (str) {
    str1 = str.split("").reverse().join("");
    console.log(str1);
  })("abcd");
  
  //*************************************************************************
  // 10.Fixed code to remove duplicates.
  //*************************************************************************
  
  var res = function (arr) {
    let newArr = [];
    for (var i = 0; i < arr.length; i++) {
      if (newArr.indexOf(arr[i]) === -1) {
        newArr.push(arr[i]);
      }
    }
    console.log(newArr);
  };
  res(["guvi", "geek", "guvi", "duplicate", "geek"]);
  
  //*************************************************************************
  // 11.Fixed code to give the below output:
  //*************************************************************************
  /*Expected Output:
  [   {firstName: “Vasanth”, lastName: “Raja”, age: 24, role: “JSWizard”},
      {firstName: “Sri”, lastName: “Devi”, age: 28, role: “Coder”}         ]
  */
  var array = [
    [
      ["firstname", "vasanth"],
      ["lastname", "Raje"],
      ["age", 24],
      ["role", "JSWizard"],
    ],
    [
      ["firstname", "Sri"],
      ["lastname", "Devi"],
      ["age", 28],
      ["role", "Coder"],
    ],
  ];
  var final = [];
  while (array.length !== 0) {
    var outer_remove = array.shift();
    let new_object = {};
    while (outer_remove.length !== 0) {
      var inner_remove = outer_remove.shift();
      var key = inner_remove[0];
      var value = inner_remove[1];
      new_object[key] = value;
    }
    final.push(new_object);
  }
  console.log(final);
  
  //*************************************************************************
  // 12.Fixed code to give the Sum of odd numbers in an array
  //*************************************************************************
  
  var as = [12, 34, 5, 6, 2, 56, 6, 2, 1];
  var s = as.reduce(function (a, c) {
    if (c % 2 !== 0) {
      return a + c;
    } else return a;
  }, 0);
  console.log(s);
