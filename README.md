- 👋 Hi, I’m @0shubhzzz0
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
0shubhzzz0/0shubhzzz0 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
<!doctype html>
<html>
<head>
<script>
var numOne, numTwo, res, temp;
function fun()
{
  numOne = parseInt(document.getElementById("one").value);
  numTwo = parseInt(document.getElementById("two").value);
  if(numOne && numTwo)
  {
    temp = document.getElementById("res");
    temp.style.display = "block";
    res = numOne + numTwo;
    document.getElementById("add").value = res;
    res = numOne - numTwo;
    document.getElementById("subtract").value = res;
    res = numOne * numTwo;
    document.getElementById("multiply").value = res;
    res = numOne / numTwo;
    document.getElementById("divide").value = res;
  }
}
</script>
</head>
<body>

<p id="input">Enter First Number: <input id="one">
<br/><br/>
Enter Second Number: <input id="two"></p>
<p><button onclick="fun()">Add, Subtract, Multiply, Divide</button></p>
<p id="res" style="display:none;">
Addition Result = <input id="add"><br/><br/>
Subtraction Result = <input id="subtract"><br/><br/>
Multiplication Result = <input id="multiply"><br/><br/>
Division Result = <input id="divide"></p>

</body>
</html>
