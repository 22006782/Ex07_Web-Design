# Ex.07 JavaScript - Simple Calculator
## AIM
  To write a program in JavaScript for implementing a simple calculator.

## ALGORITHM
### STEP-1
  Open notepad and type the HTML code.

### STEP-2
  Define a function to implement the simple calculator.

### STEP-3
  Using branching statements to find the corresponding operation.

### STEP-4
  Open the file in a browser and verify the output.
  
## CODE
```<html>
<head>
<script type="text/javascript">
function calc()
{
var a=prompt("Enter 1st Value");
var b=prompt("Enter 2st Value");
var op=prompt("Enter Operation to Perform 1.Addition 2.Subtraction 3.Multiplication 4.Division");
var d;
if(op==1)
{
d=a+b;
alert(d);
}
else if(op==2)
{
d=a-b;
alert(d);
}
else if(op==3)
{
d=a*b;
alert(d);
}
else if(op==4)
{
d=a/b;
alert(d);
}
else
{
alert("Invalid Operation");
}
}
</script>
</head>
<body onload="calc()">
<h1>
Simple Calculator
</h1>
<hr color="pink">
<p> 
Enter option for doing the corresponding operation
</p>
</body>
</html>
```


## OUTPUT
![assignment71](https://github.com/22006782/Ex07_Web-Design/assets/128878369/136e6978-5e81-46b5-bfc5-4c6729ccdc25)
![assignment72](https://github.com/22006782/Ex07_Web-Design/assets/128878369/dd5d2ec9-89ec-4a41-864e-bb0faf046efc)
![assignment73](https://github.com/22006782/Ex07_Web-Design/assets/128878369/051fb4da-002f-4d5a-b5dd-2c73098d7177)
![assignment74](https://github.com/22006782/Ex07_Web-Design/assets/128878369/369e10b7-12ff-48fd-9fe9-e4913787b2b7)
![assignment75](https://github.com/22006782/Ex07_Web-Design/assets/128878369/a34face0-80ab-4b16-9ede-e19bc2126ad3)



## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
