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
<html>
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
<hr color="red">
<p> 
Enter option for doing the corresponding operation
</p>
</body>
</html>


## OUTPUT
![Screenshot 2023-05-27 093732](https://github.com/JosephselwinJ/Ex07_Web-Design/assets/127816444/3d9e2b0e-879e-4a92-8c7e-5c10f078b1db)
![Screenshot 2023-05-27 093611](https://github.com/JosephselwinJ/Ex07_Web-Design/assets/127816444/d6adf2a7-d5a8-4a3c-aa89-987b673b4fd6)
![Screenshot 2023-05-27 093624](https://github.com/JosephselwinJ/Ex07_Web-Design/assets/127816444/c457d6ef-4cd7-49ff-ae97-addf991e5bf6)
![Screenshot 2023-05-27 093708](https://github.com/JosephselwinJ/Ex07_Web-Design/assets/127816444/a32f520e-6a8d-445c-b0e8-2f7fdfcf0be9)
![Screenshot 2023-05-27 093724](https://github.com/JosephselwinJ/Ex07_Web-Design/assets/127816444/0775de38-01a7-486d-be9e-91e4bc3e2432)


## RESULT
  Implementation of a Simple Calculator using JavaScript is done successfully.
