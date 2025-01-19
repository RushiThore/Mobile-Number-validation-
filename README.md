 Mobile-Number-validation-
<html>

<body>

Enter Mobile No:<input type="text" id="tf

1">

<input type="button" name="b1" value="C heck Mobile No" onclick="Display()">

<script language="javascript" type="text /javascript">

function Display()

{

var text=document.getElementById("tf1 ").value;

var pattern=/^[0-9]{10}$/gmi;

var result=pattern.test(text);

if (result)

{

alert("Valid Mobile No");

}

else

{

alert("Invalid Mobile No");

}

}
</script>

</body>

</html>
