# javascript
JavaScript Simple Step by Step Course

<!DOCTYPE html>
<html>
<body>

<h2>JavaScript Statements</h2>
<input type="text" id="aaa">
<input type="text" id="bbb">
<input type="button" value="Click here to run function" onClick="ttt()">
<script>
function ttt(){
	var a=document.getElementById("aaa").value;
	var b=document.getElementById("bbb").value;
	var c=a+b;
	var d=a-b;
	document.getElementById("hhh").innerHTML=d;
}

</script>

<h3 id="hhh"></h3>
</body>
</html>
