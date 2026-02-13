<!DOCTYPE html>  
<html>  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
<title>Omer ♡ Bahriiii</title>  
<style>  
body{  
margin:0;  
font-family:Arial;  
background:linear-gradient(135deg,#1a1a2e,#16213e);  
color:white;  
text-align:center;  
padding:20px;  
}  
  
img{  
width:90%;  
max-width:300px;  
border-radius:20px;  
margin:10px 0;  
}  
  
button{  
background:#ff9a9e;  
border:none;  
padding:15px 30px;  
border-radius:50px;  
font-size:20px;  
margin:15px;  
cursor:pointer;  
}  
  
.counter{  
font-size:40px;  
margin:20px 0;  
color:#ffb6c1;  
}  
</style>  
</head>  
<body>  
  
<h2>Bahriiii 🤍</h2>  
  
<img src="photo1.jpg">  
<img src="photo2.jpg">  
<img src="photo3.jpg">  
  
<div class="counter" id="counter">225</div>  
  
<p>225 days of choosing you 💕</p>  
  
<button onclick="nextPage()">💘 YES</button>  
<button onclick="nextPage()">💝 YEAH</button>  
  
<script>  
let days = 225;  
setInterval(()=>{  
days++;  
document.getElementById("counter").innerHTML = days;  
},86400000);  
  
function nextPage(){  
window.location.href="success.html";  
}  
</script>  
  
</body>  
</html>  
