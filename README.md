# Vgd<!DOCTYPE html>
<html lang="sv">
<head>
<meta charset="UTF-8">
<title>VGD</title>

<link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;500;700&display=swap" rel="stylesheet">

<style>

body{
margin:0;
font-family:Inter, sans-serif;
background:#0a0a0a;
color:white;
}

header{
padding:30px;
display:flex;
justify-content:space-between;
align-items:center;
border-bottom:1px solid #222;
}

.logo{
font-size:28px;
letter-spacing:6px;
}

.hero{
height:60vh;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
}

.hero h1{
font-size:64px;
letter-spacing:10px;
}

.products{
max-width:1100px;
margin:auto;
padding:40px 20px;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:30px;
}

.product{
background:#111;
padding:20px;
border:1px solid #222;
}

.product img{
width:100%;
}

button{
width:100%;
padding:12px;
margin-top:10px;
background:white;
border:none;
cursor:pointer;
font-weight:600;
}

select,input{
width:100%;
padding:10px;
margin-top:10px;
background:#0a0a0a;
border:1px solid #333;
color:white;
}

footer{
text-align:center;
padding:40px;
color:#777;
}

</style>
</head>

<body>

<header>
<div class="logo">VGD</div>
<div>Modern Underground Clothing</div>
</header>

<section class="hero">
<h1>VGD</h1>
</section>

<section class="products">

<div class="product">
<img src="https://picsum.photos/500/600" alt="">
<h3>VGD Distressed Hoodie</h3>
<p>1200 SEK</p>

<form action="https://formspree.io/f/yourcode" method="POST">

<input type="hidden" name="Produkt" value="Distressed Hoodie">

<label>Storlek</label>
<select name="Storlek">
<option>S</option>
<option>M</option>
<option>L</option>
</select>

<label>Ditt namn</label>
<input type="text" name="Namn" required>

<label>Email</label>
<input type="email" name="Email" required>

<button type="submit">Beställ</button>

</form>
</div>

</section>

<footer>
© VGD
</footer>

</body>
</html>
