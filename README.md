<!DOCTYPE html>
<html lang="en">
<head>

<meta charset="UTF-8">

<meta name="viewport"
content="width=device-width, initial-scale=1.0">

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

<div class="news-layout">

<div class="left">

<img src="images/newspaper.jpg">

<p>

Latest world news updates from across the globe.

</p>

</div>

<div class="right">

<h3>Economic News</h3>

<p>

Share breaking news with everyone using NES C.

</p>

</div>

</div>

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

<p>Sports updates.</p>

</div>

<div class="card">

<img src="images/news3.jpg">

<h3>Technology</h3>

<p>Technology news.</p>

</div>

</section>

<footer>

<p>

©2026 NES C

</p>

</footer>

</body>

</html>
*{

margin:0;

padding:0;

box-sizing:border-box;

font-family:Arial;

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

box-shadow:0 2px 8px gray;

}

.logo h1{

font-size:40px;

}

.logo span{

color:red;

}

.logo p{

font-size:18px;

color:gray;

}

nav a{

text-decoration:none;

margin:15px;

color:black;

font-size:18px;

}

.headline{

padding:40px;

}

.headline h2{

font-size:45px;

margin-bottom:20px;

}

.news-layout{

display:flex;

gap:30px;

}

.left{

width:60%;

}

.left img{

width:100%;

border-radius:10px;

}

.right{

width:40%;

font-size:22px;

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

padding:15px;

border-radius:10px;

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

margin-top:30px;

}
