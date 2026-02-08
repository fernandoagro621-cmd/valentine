# valentine
Will you be my valentine Nimisha??
<!DOCTYPE html>
<html>
<head>
<title>Valentine 💖</title>

<style>
body{
  background: linear-gradient(45deg,#ff9a9e,#fecfef);
  text-align:center;
  font-family: Arial;
  margin-top:80px;
  overflow:hidden;
}

h1{
  font-size:40px;
  color:white;
}

button{
  padding:12px 25px;
  font-size:18px;
  border:none;
  border-radius:25px;
  cursor:pointer;
  margin:10px;
}

#yes{
  background:red;
  color:white;
}

#no{
  background:black;
  color:white;
  position:relative;
}

#msg{
  font-size:28px;
  color:white;
  margin-top:20px;
}
</style>
</head>

<body>

<h1>Nitesh asks… 💌<br>Will you be my Valentine? ❤️</h1>

<button id="yes" onclick="love()">YES 😍</button>
<button id="no" onmouseover="run()">NO 😜</button>

<div id="msg"></div>

<script>
function love(){
 document.getElementById("msg").innerHTML =
 "Yayyy ❤️ Best decision ever 😍💖";
}

function run(){
 let btn=document.getElementById("no");
 btn.style.position="absolute";
 btn.style.top=Math.random()*400+"px";
 btn.style.left=Math.random()*400+"px";
}
</script>

</body>
</html>
