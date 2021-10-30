<!DOCTYPE html>
<html lang="pt-br">
<head>
<title> home </title>
<meta charset="utf-8" />
<style type="text/css">
* {
font-size:20px;
}
body {
background:black;
width:auto;
font-weight:bold;
font-size:20px;
color:white;
}
main#main1 {
background:white;
height:1490px;
padding:10px;
border-radius:9px;
}
main#doh1 {
background:black;
color:white;
padding:15px;
margin-top:25px;
border-radius:9px;
font-size:20px;
text-align:center;
width:auto;
}
main#form {
height:800px;
width:auto;
text-align:center;
background:black;
padding:15px;
color:white;
font-size:20px;
border-radius:9px;
}
input {
font-size:20px;
height:40px;
width:500px;
}
li#uma {
text-align:left;
}
li#umo {
text-align:left;
}
button#btn {
padding:10px;
padding-left:30px;
padding-right:30px;
border-radius:4px;
}
</style>
</head>
<body>
<?php
echo "<br>";
echo "<p> user == admin <br> senha == admin <br></p>";
$logs=$_POST['btn3'];
if(isset($_POST['btn3'])):
$logs="";
$user=$_POST['user1'];
$user2=$_POST['senha2'];
if ($user == "admin"):
if ($user2 == "admin"):
$logado="muinto bom vc esta logado";
echo '<script> alert(" ' . $logado . '")</script>';
endif;
endif;
endif;
?>
<main id="main1">
<main id="doh1">
<h1 name="principal">  SEU BITI AQUI.. </h1>
</main>
<br><br>
<main id="form" >
<h2> seu site favorito </h2>
<br><br>
<form method="post" >
<fieldset>
<ul>
<ul>
<fieldset>
    <li id="uma" >nome.:</li>    
    <li><input type="text" placeholder="digite um nome valido" name="user1"></li>
</fieldset>
<br>
</ul>
<ul>
<br>
<fieldset>
    <li id="umo">senha: </li>
    <li> <input type="text" placeholder="digite uma senha valida" name="senha2" ></li>
</fieldset>
</ul>
</ul>
<br><br>
<button id="btn" name="btn3" > CRIAR LOGUIN </button>
<br><br>
</fieldset>
</form>
</main>
</main>
</body>
</html>
