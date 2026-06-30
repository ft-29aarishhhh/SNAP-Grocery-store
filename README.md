# SNAP-Grocery-store
we sell fresh fruits and vegetables at the cheapest price available.
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>SNAP Fresh Grocery | Ramamurthy Nagar</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#f8fdff;
color:#333;
}

section{
padding:80px 8%;
}

.container{
max-width:1200px;
margin:auto;
}

h2{
font-size:38px;
text-align:center;
margin-bottom:20px;
color:#2196F3;
}

p{
line-height:1.8;
}

img{
max-width:100%;
display:block;
}

a{
text-decoration:none;
}

/* NAVBAR */

nav{
position:fixed;
top:0;
left:0;
width:100%;
background:#2196F3;
display:flex;
justify-content:space-between;
align-items:center;
padding:15px 8%;
z-index:999;
box-shadow:0 3px 12px rgba(0,0,0,.15);
}

.logo{
font-size:30px;
font-weight:700;
color:#fff;
}

nav ul{
display:flex;
list-style:none;
gap:30px;
}

nav ul li a{
color:white;
font-weight:500;
transition:.3s;
}

nav ul li a:hover{
color:#c8f7c5;
}

/* HERO */

.hero{
height:100vh;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
background:linear-gradient(rgba(0,0,0,.45),rgba(0,0,0,.45)),
url('https://images.unsplash.com/photo-1542838132-92c53300491e?auto=format&fit=crop&w=1600&q=80');
background-size:cover;
background-position:center;
color:white;
}

.hero h1{
font-size:60px;
margin-bottom:20px;
}

.hero p{
font-size:22px;
margin-bottom:30px;
}

.btn{
display:inline-block;
padding:15px 35px;
border-radius:40px;
background:#4CAF50;
color:white;
font-weight:600;
margin:8px;
transition:.3s;
}

.btn:hover{
background:#388E3C;
transform:translateY(-3px);
}

.whatsapp{
background:#25D366;
}

.whatsapp:hover{
background:#1db954;
}

/* FEATURES */

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(230px,1fr));
gap:25px;
margin-top:40px;
}

.card{
background:white;
padding:25px;
border-radius:15px;
box-shadow:0 8px 20px rgba(0,0,0,.08);
transition:.3s;
text-align:center;
}

.card:hover{
transform:translateY(-8px);
}

.card h3{
margin:15px 0;
color:#2196F3;
}

/* OFFERS */

.offers{
background:#E8F5E9;
}

.offer-box{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
margin-top:40px;
}

.offer{
background:white;
padding:30px;
border-radius:15px;
box-shadow:0 5px 20px rgba(0,0,0,.08);
text-align:center;
border-left:6px solid #4CAF50;
}

.offer h3{
color:#2196F3;
margin-bottom:10px;
}

.discount{
font-size:28px;
font-weight:bold;
color:#e53935;
margin-top:10px;
}

/* GALLERY */

.gallery{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
margin-top:40px;
}

.gallery img{
height:240px;
object-fit:cover;
border-radius:15px;
transition:.3s;
}

.gallery img:hover{
transform:scale(1.05);
}

/* REVIEWS */

.reviews{
background:#f7fcff;
}

.review-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
margin-top:40px;
}

.review{
background:white;
padding:25px;
border-radius:15px;
box-shadow:0 5px 15px rgba(0,0,0,.08);
}

.stars{
color:#FFD700;
font-size:20px;
margin-bottom:10px;
}

/* CONTACT */

.contact-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(320px,1fr));
gap:40px;
margin-top:40px;
}

iframe{
width:100%;
height:350px;
border:none;
border-radius:15px;
}

form{
display:flex;
flex-direction:column;
gap:15px;
}

input,textarea{
padding:15px;
border:1px solid #ddd;
border-radius:10px;
font-size:16px;
}

textarea{
height:150px;
resize:none;
}

button{
padding:15px;
border:none;
background:#2196F3;
color:white;
font-size:17px;
border-radius:10px;
cursor:pointer;
}

button:hover{
background:#1976D2;
}

.phone{
font-size:20px;
font-weight:600;
margin:15px 0;
}

/* FOOTER */

footer{
background:#2196F3;
color:white;
text-align:center;
padding:30px;
}

.float{
position:fixed;
right:20px;
bottom:20px;
width:65px;
height:65px;
background:#25D366;
border-radius:50%;
display:flex;
justify-content:center;
align-items:center;
font-size:32px;
color:white;
box-shadow:0 10px 20px rgba(0,0,0,.3);
}

/* MOBILE */

@media(max-width:768px){

.hero h1{
font-size:40px;
}

.hero p{
font-size:18px;
}

nav{
flex-direction:column;
padding:15px;
}

nav ul{
margin-top:12px;
gap:15px;
flex-wrap:wrap;
justify-content:center;
}

section{
padding:70px 5%;
}

}
</style>

</head>

<body>

<nav>

<div class="logo">🥬 SNAP</div>

<ul>
<li><a href="#home">Home</a></li>
<li><a href="#highlights">Highlights</a></li>
<li><a href="#offers">Offers</a></li>
<li><a href="#gallery">Gallery</a></li>
<li><a href="#reviews">Reviews</a></li>
<li><a href="#contact">Contact</a></li>
</ul>

</nav>

<section class="hero" id="home">

<div>

<h1>Fresh Groceries Delivered Daily</h1>

<p>Welcome to <strong>SNAP Fresh Grocery</strong><br>
Ramamurthy Nagar's trusted neighborhood grocery store.</p>

<a href="https://wa.me/919999999999" class="btn whatsapp">
📲 Order on WhatsApp
</a>

<a href="#offers" class="btn">
View Today's Offers
</a>

</div>

</section>

<section id="highlights">

<h2>Fresh Grocery Highlights</h2>

<div class="cards">

<div class="card">
<h3>🥦 Fresh Vegetables</h3>
<p>Farm fresh vegetables delivered every morning.</p>
</div>

<div class="card">
<h3>🍎 Seasonal Fruits</h3>
<p>Premium quality fruits at affordable prices.</p>
</div>

<div class="card">
<h3>🥛 Dairy Products</h3>
<p>Milk, butter, paneer, curd and more.</p>
</div>

<div class="card">
<h3>🛒 Daily Essentials</h3>
<p>Rice, flour, oil, pulses, spices and household products.</p>
</div>

</div>

</section>

<section class="offers" id="offers">

<h2>Today's Special Offers</h2>

<div class="offer-box">

<div class="offer">
<h3>🥬 Sunday Vegetable Sale</h3>
<p>Every Sunday enjoy fresh vegetables at</p>
<div class="discount">25% OFF</div>
</div>

<div class="offer">
<h3>🍉 Fresh Fruits</h3>
<p>Buy any 2kg of fruits and get an extra 10% OFF.</p>
</div>

<div class="offer">
<h3>🛍️ Family Savings</h3>
<p>Free home delivery on orders above ₹999.</p>
</div>

</div>

</section>

<section id="gallery">

<h2>Inside SNAP Grocery</h2>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1542838132-92c53300491e?auto=format&fit=crop&w=900&q=80">

<img src="https://images.unsplash.com/photo-1518843875459-f738682238a6?auto=format&fit=crop&w=900&q=80">

<img src="https://images.unsplash.com/photo-1573246123716-6b1782bfc499?auto=format&fit=crop&w=900&q=80">

<img src="https://images.unsplash.com/photo-1543168256-418811576931?auto=format&fit=crop&w=900&q=80">

</div>

</section>

<section class="reviews" id="reviews">

<h2>Customer Reviews</h2>

<div class="review-grid">

<div class="review">
<div class="stars">★★★★★</div>
<p>"Excellent quality vegetables and very friendly staff. Highly recommended!"</p>
<b>– Suresh</b>
</div>

<div class="review">
<div class="stars">★★★★★</div>
<p>"Affordable prices and quick WhatsApp ordering. Love shopping here."</p>
<b>– Lakshmi</b>
</div>

<div class="review">
<div class="stars">★★★★★</div>
<p>"Fresh fruits every day and free home delivery is a big plus."</p>
<b>– Praveen</b>
</div>

</div>

</section>

<section id="contact">

<h2>Visit SNAP Grocery</h2>

<div class="contact-grid">

<div>

<iframe
src="https://maps.google.com/maps?q=Ramamurthy%20Nagar%20Bangalore&t=&z=15&ie=UTF8&iwloc=&output=embed">
</iframe>

<p class="phone">📞 +91 98765 43210</p>

<p class="phone">☎ +91 91234 56789</p>

<a href="https://wa.me/919999999999" class="btn whatsapp">
Order on WhatsApp
</a>

</div>

<div>

<form>

<input type="text" placeholder="Your Name" required>

<input type="email" placeholder="Email Address" required>

<input type="tel" placeholder="Phone Number">

<textarea placeholder="Write your message..."></textarea>

<button type="submit">
Send Message
</button>

</form>

</div>

</div>

</section>

<footer>

<h2 style="color:white;">SNAP Fresh Grocery</h2>

<p>Your Neighborhood Grocery Store in Ramamurthy Nagar</p>

<p style="margin-top:10px;">Fresh Produce • Best Prices • Home Delivery</p>

<p style="margin-top:15px;">© 2026 SNAP Grocery. All Rights Reserved.</p>

</footer>

<a class="float" href="https://wa.me/919999999999">
💬
</a>

</body>
</html>
