<!DOCTYPE html>
<html>
<head>
    <title>NEW C</title>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<header>

<h1>NEW C</h1>

<nav>

<a href="index.html">Home</a>

<a href="login.html">Login</a>

<a href="dashboard.html">Dashboard</a>

</nav>

</header>

<section>

<h2>Welcome to NEW C</h2>

<p>Read and publish the latest news.</p>

</section>

<script src="script.js"></script>

</body>
</html>
body{
margin:0;
font-family:Arial;
background:#ccffcc;
}

header{
background:#006400;
color:white;
padding:20px;
text-align:center;
}

nav a{
color:white;
text-decoration:none;
margin:15px;
}

section{
padding:30px;
text-align:center;
}
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Login</title>
<link rel="stylesheet" href="css/style.css">
</head>

<body>

<div class="container">

<h1>News Platform</h1>

<h2>Login</h2>

<input type="email" id="email" placeholder="Email">

<input type="password" id="password" placeholder="Password">

<button onclick="login()">Login</button>

<p>
Don't have an account?
<a href="register.html">Register</a>
</p>

</div>

<script src="js/login.js"></script>

</body>
</html>
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Register</title>
<link rel="stylesheet" href="css/style.css">
</head>

<body>

<div class="container">

<h1>Create Account</h1>

<input type="text" id="name" placeholder="Full Name">

<input type="email" id="email" placeholder="Email">

<input type="password" id="password" placeholder="Password">

<button onclick="register()">Register</button>

<p>

Already have an account?

<a href="login.html">Login</a>

</p>

</div>

<script src="js/register.js"></script>

</body>
</html>
body{
font-family:Arial;
background:#d9ffe0;
display:flex;
justify-content:center;
align-items:center;
height:100vh;
margin:0;
}

.container{
background:white;
padding:30px;
width:320px;
border-radius:10px;
box-shadow:0 0 15px gray;
text-align:center;
}

input{
width:90%;
padding:10px;
margin:10px;
}

button{
padding:10px;
width:95%;
background:green;
color:white;
border:none;
cursor:pointer;
}
function login(){

let email=document.getElementById("email").value;

let password=document.getElementById("password").value;

if(email=="" || password==""){

alert("Enter Email and Password");

return;

}

alert("Login Successful");

window.location="home.html";

}
function register(){

let name=document.getElementById("name").value;

let email=document.getElementById("email").value;

let password=document.getElementById("password").value;

if(name=="" || email=="" || password==""){

alert("Fill all fields");

return;

}

alert("Registration Successful");

window.location="login.html";

}
