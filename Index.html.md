<!DOCTYPE html>  
<html>  
<head>  
<meta charset="UTF-8">  
<title>Regalo</title>  
<style>  
body{  
  margin:0;  
  display:flex;  
  justify-content:center;  
  align-items:center;  
  height:100vh;  
  background:#ffe6f0;  
  font-family:Arial, sans-serif;  
}  
.corazon{  
  position:relative;  
  width:300px;  
  height:270px;  
}  
.corazon:before,  
.corazon:after{  
  content:"";  
  position:absolute;  
  left:150px;  
  top:0;  
  width:150px;  
  height:240px;  
  background:red;  
  border-radius:150px 150px 0 0;  
  transform:rotate(-45deg);  
  transform-origin:0 100%;  
}  
.corazon:after{  
  left:0;  
  transform:rotate(45deg);  
  transform-origin:100% 100%;  
}  
.texto{  
  position:absolute;  
  width:100%;  
  top:50%;  
  transform:translateY(-50%);  
  text-align:center;  
  color:white;  
  font-size:28px;  
  font-weight:bold;  
}  
</style>  
</head>  
<body>  
<div class="corazon">  
  <div class="texto">te quiero cojer</div>  
</div>  
</body>  
</html>  
