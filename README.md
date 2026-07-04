<!DOCTYPE html>
<html>
<head>
    <title>NEW C</title>
    <subtitle>read & post news</subtitle>
    <link rel="stylesheet" href="style.css">
</head>

<body>

<header>

<h1>NEW C</h1>

<nav>

<a href="index.html">Home</a>

<a href="login.html">Login</a>

<a href="dashboard.html">Dashboard</a>
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Login</title>
<link rel="stylesheet" href="css/style.css">
</head>

<body>

<div class="login-box">

<h2>Login</h2>

<input type="email" id="email" placeholder="Enter Email">

<input type="password" id="password" placeholder="Enter Password">

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
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Dashboard - Daily News</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial,sans-serif;
}

body{
background:#f2f2f2;
}

header{
background:#0b8b3b;
color:white;
padding:15px 30px;
display:flex;
justify-content:space-between;
align-items:center;
}

header h1{
font-size:30px;
}

header button{
background:red;
color:white;
border:none;
padding:10px 18px;
cursor:pointer;
border-radius:5px;
}

.container{
display:flex;
}

/* Sidebar */

.sidebar{
width:220px;
background:#222;
height:100vh;
padding-top:20px;
}

.sidebar a{
display:block;
color:white;
padding:15px;
text-decoration:none;
font-size:18px;
}

.sidebar a:hover{
background:#0b8b3b;
}

/* Main */

.main{
flex:1;
padding:25px;
}

.cards{
display:flex;
gap:20px;
flex-wrap:wrap;
}

.card{
background:white;
width:220px;
padding:20px;
border-radius:10px;
box-shadow:0 0 8px rgba(0,0,0,.2);
text-align:center;
}

.card h2{
color:#0b8b3b;
margin-bottom:10px;
}

.news{
margin-top:40px;
}

.news-card{
background:white;
padding:20px;
margin-bottom:20px;
border-radius:10px;
box-shadow:0 0 8px rgba(0,0,0,.2);
}

.news-card img{
width:100%;
max-height:250px;
object-fit:cover;
border-radius:8px;
margin-bottom:15px;
}

.news-card button{
background:#0b8b3b;
color:white;
border:none;
padding:8px 15px;
cursor:pointer;
margin-top:10px;
margin-right:10px;
border-radius:5px;
}

</style>

</head>

<body>

<header>

<h1>Daily News Dashboard</h1>

<button onclick="logout()">Logout</button>

</header>

<div class="container">

<div class="sidebar">


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
<!DOCTYPE html>
<html>
<head>
<meta charset="UTF-8">
<title>Login</title>
<link rel="stylesheet" href="css/style.css">
</head>

<body>

<div class="login-box">

<h2>Login</h2>

<input type="email" id="email" placeholder="Enter Email">

<input type="password" id="password" placeholder="Enter Password">

<button onclick="login()">Login</button>

<p>
Don't have an account?
<a href="register.html">Register</a>
</p>

</div>

<script src="js/login.js"></script>

</body>
</html>


<a href="#">🏠 Dashboard</a>

<a href="#">📰 News Feed</a>

<a href="#">📂 Categories</a>

<a href="#">🔖 Bookmarks</a>

<a href="#">💬 Comments</a>

<a href="#">👤 Profile</a>

</div>

<div class="main">

<h2>Welcome Admin</h2>

<br>

<div class="cards">

<div class="card">
<h2>25</h2>
<p>Total News</p>
</div>

<div class="card">
<h2>10</h2>
<p>Categories</p>
</div>

<div class="card">
<h2>150</h2>
<p>Comments</p>
</div>

<div class="card">
<h2>60</h2>
<p>Bookmarks</p>
</div>

</div>

<div class="news">

<h2>Latest News</h2>

<br>

<div class="news-card">

<img src="images/newspaper.png">

<h3>Economic News</h3>

<p>
Latest economic updates and breaking news from around the world.
</p>

<button>Edit</button>

<button>Delete</button>

</div>

<div class="news-card">

<img src="images/newspaper.png">

<h3>Sports News</h3>

<p>
Latest sports updates and live scores.
</p>

<button>Edit</button>

<button>Delete</button>

</div>

</div>

</div>

</div>

<script>

function logout(){

alert("Logged Out Successfully");

window.location.href="login.html";

}

</script>

</body>
</html>
