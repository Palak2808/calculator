# calculator
<html>
<head>
<title> buttons </title>
<style>
#p{height:540px;
width:275px;
border: 2px solid black;
margin:auto;
padding:10px;
}
#calc{
width: 250px;
margin-top:10px;
margin-left:10px;
border: 1px solid gray;
	border-radius: 3px;
	padding: 20px;
	margin: auto;
}
input
{
width: 10px;
background-color:black;
color: white;
border: 1px solid gray;
	border-radius: 5px;
	padding: 26px;
	margin: 5px;
	font-size: 15px;
}
#clear{
width: 270px;
border: 3px solid gray;
	border-radius: 1px;
	padding: 20px;
	background-color: black;
color:white;
}

</style>
</head>
<body>
<div id="p">
<form name="myform">
<input id="calc" type="text" name="answer" placeholder="write here"><br><br>
<input type="button" value="1" onclick="myform.answer.value +='1' ">
<input type="button" value="2" onclick="myform.answer.value +='2' ">
<input type="button" value="3" onclick="myform.answer.value +='3' ">
<input type="button" value="+" onclick="myform.answer.value +='+' "><br><br>

<input type="button" value="4" onclick="myform.answer.value +='4' ">
<input type="button" value="5" onclick="myform.answer.value +='5' ">
<input type="button" value="6" onclick="myform.answer.value +='6' ">
<input type="button" value="-" onclick="myform.answer.value +='-' "><br><br>

<input type="button" value="7" onclick="myform.answer.value +='7' ">
<input type="button" value="8" onclick="myform.answer.value +='8' ">
<input type="button" value="9" onclick="myform.answer.value +='9' ">
<input type="button" value="*" onclick="myform.answer.value +='*' "><br><br>

<input type="button" value="/" onclick="myform.answer.value +='/' ">
<input type="button" value="0" onclick="myform.answer.value +='0' ">
<input type="button" value="%" onclick="myform.answer.value +='%' ">
<input type="button"  value="=" onclick="myform.answer.value =eval(myform.answer.value) "><br><br>

<input type="button" value="AC" onclick="myform.answer.value =' '" id="clear">


</form>
</div>
</body>
</html>
