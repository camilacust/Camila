# Camila


<!DOCTYPE html>
<html>

<head>
		<meta charset= "UTF-8" />
		
	<title>Validando com Javascript</title>
</head>

<body>

<div id="msgEmail"></div>
Nome:<input type="text" id="name"/> 
Email:<input type="text" id="email"/> 
<button id="validar" onclick="validar()">validar</button><br/>


<script language="Javascript">

function validar(){
e=document.getElementById("email").value;
if(email.value.indexOf("@") == -1 ||
    email.valueOf.indexOf(".") == -1 ||
    email.value == "" ||
    email.value == null) {
    alert("Indique um e-mail válido.");
	email.focus();
        return false;
}
else
return true;
}




</script>

</body>
</form>
</script>
</body>

</html>
