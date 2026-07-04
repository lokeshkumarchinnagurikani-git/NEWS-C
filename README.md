<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>NES C</title>
<link rel="stylesheet" href="css/style.css">
</head>

<body>

<header>

<div class="logo">

<h1>NES <span>C</span></h1>

<p>Post & Share News</p>

</div>

<nav>

<a href="index.html">Home</a>

<a href="login.html">Login</a>

<a href="dashboard.html">Dashboard</a>

</nav>

</header>

<section class="headline">

<h2>WORLD NEWS TODAY</h2>

<img src="images/newspaper.jpg">

<p>

Read and share the latest news from around the world.

</p>

</section>

<section class="cards">

<div class="card">

<img src="images/news1.jpg">

<h3>Politics</h3>

<p>Latest political news.</p>

</div>

<div class="card">

<img src="images/news2.jpg">

<h3>Sports</h3>

<p>Latest sports updates.</p>

</div>

<div class="card">

<img src="images/news3.jpg">

<h3>Technology</h3>

<p>Latest technology news.</p>

</div>

</section>

<footer>

© 2026 NES C

</footer>

</body>

</html>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:white;
}

header{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px;
background:white;
box-shadow:0 2px 10px lightgray;
}

.logo h1{
font-size:42px;
}

.logo span{
color:red;
}

.logo p{
color:gray;
}

nav a{
text-decoration:none;
margin-left:20px;
color:black;
font-size:18px;
font-weight:bold;
}

nav a:hover{
color:red;
}

.headline{
text-align:center;
padding:40px;
}

.headline h2{
font-size:40px;
margin-bottom:20px;
}

.headline img{
width:80%;
max-width:900px;
border-radius:10px;
}

.headline p{
margin-top:20px;
font-size:20px;
}

.cards{
display:flex;
justify-content:center;
gap:20px;
padding:30px;
}

.card{
width:300px;
box-shadow:0 0 10px gray;
border-radius:10px;
padding:15px;
}

.card img{
width:100%;
height:180px;
object-fit:cover;
}

.card h3{
margin:10px 0;
}

footer{
background:black;
color:white;
text-align:center;
padding:20px;
margin-top:40px;
}
<!DOCTYPE html>
<html>
<head>

<title>Login</title>

<link rel="stylesheet" href="css/style.css">

</head>

<body>

<div class="login-box">

<h1>NES C</h1>

<p>Post & Share News</p>

<input type="email" id="email" placeholder="Email">

<input type="password" id="password" placeholder="Password">

<button onclick="login()">Login</button>

</div>

<script src="js/login.js"></script>

</body>

</html>
function login(){

let email=document.getElementById("email").value;

let password=document.getElementById("password").value;

if(email=="admin@nesc.com" && password=="123456"){

window.location.href="dashboard.html";

}

else{

alert("Invalid Login");

}

}
