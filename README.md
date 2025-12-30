<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>CHIDI AGU ENTERPRISE | Building & Home Solutions</title>

<style>
*{
margin:0;padding:0;box-sizing:border-box;
font-family:Segoe UI, Tahoma, sans-serif;
}

body{background:#f4f6f8;color:#222}

/* HEADER */
header{
background:#111827;color:#fff;
padding:20px 8%;
display:flex;justify-content:space-between;align-items:center;
flex-wrap:wrap;
}

.logo{display:flex;align-items:center;gap:10px}
.logo-icon{
width:42px;height:42px;border-radius:50%;
background:#fbbf24;color:#111827;
display:flex;align-items:center;justify-content:center;
font-weight:800;
}

nav a{
color:#e5e7eb;margin-left:20px;
text-decoration:none;font-size:15px;
}
nav a:hover{color:#fbbf24}

/* HERO */
.hero{
height:85vh;
background:
linear-gradient(rgba(0,0,0,.7),rgba(0,0,0,.7)),
url("https://picsum.photos/1920/1080?home") center/cover;
display:flex;align-items:center;
padding:0 8%;color:white;
}

.hero span{
color:#fbbf24;letter-spacing:2px;font-size:14px;
}

.hero h2{
font-size:48px;margin:15px 0;
}

.hero p{
font-size:18px;margin-bottom:25px;color:#e5e7eb;
}

/* SECTIONS */
section{padding:80px 8%}

.section-title{text-align:center;margin-bottom:50px}
.section-title h3{font-size:34px}

/* PRODUCTS */
.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(260px,1fr));
gap:30px;
}

.product-card{
background:white;border-radius:12px;
box-shadow:0 10px 25px rgba(0,0,0,.1);
overflow:hidden;
}

.product-card img{
width:100%;height:220px;
object-fit:cover;display:block;
}

.product-card div{padding:22px}

/* WHY */
.why{
background:#111827;color:white;
border-radius:12px;
}

.why ul{
list-style:none;
display:grid;
grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
gap:20px;
}

.why li{
background:#1f2933;
padding:25px;border-radius:8px;
}

/* ABOUT */
.about{
background:white;
padding:40px;border-radius:12px;
box-shadow:0 10px 25px rgba(0,0,0,.1);
max-width:900px;margin:auto;
}

/* CONTACT */
.contact{
background:#111827;color:white;
border-radius:12px;
padding:50px;text-align:center;
}

.contact p{margin:10px 0}

/* SOCIAL LINKS */
.social-links{
margin-top:25px;
display:flex;
justify-content:center;
gap:15px;
flex-wrap:wrap;
}

.social-links a{
text-decoration:none;
padding:12px 18px;
border-radius:30px;
color:white;
font-size:14px;
font-weight:600;
transition:.3s;
}

.fb{background:#1877f2}
.ig{background:#e1306c}
.tw{background:#000}
.mail{background:#f59e0b}

.social-links a:hover{opacity:.85}

/* WHATSAPP FLOAT */
.whatsapp{
position:fixed;
bottom:20px;right:20px;
background:#25D366;color:white;
padding:15px 22px;
border-radius:50px;
text-decoration:none;font-weight:600;
box-shadow:0 10px 25px rgba(0,0,0,.4);
z-index:1000;
}

/* FOOTER */
footer{
background:#020617;color:#9ca3af;
text-align:center;padding:20px;
font-size:14px;
}

@media(max-width:768px){
.hero h2{font-size:34px}
nav{margin-top:10px}
}
</style>
</head>

<body>

<header>
<div class="logo">
<div class="logo-icon">CA</div>
<h2>CHIDI AGU ENTERPRISE</h2>
</div>

<nav>
<a href="#">Home</a>
<a href="#products">Products</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</nav>
</header>

<section class="hero">
<div>
<span>PREMIUM BUILDING & HOME SOLUTIONS</span>
<h2>Building Dreams,<br>One Brick at a Time</h2>
<p>Quality materials, luxury fittings and trusted service.</p>
</div>
</section>

<section id="products">
<div class="section-title">
<h3>Our Products</h3>
</div>

<div class="products">

<div class="product-card">
<img src="https://picsum.photos/600/400?heater" loading="eager">
<div>
<h4>Water Heaters</h4>
<p>Reliable and efficient water heating systems.</p>
</div>
</div>

<div class="product-card">
<img src="https://picsum.photos/600/400?tank" loading="eager">
<div>
<h4>GeePee Tanks</h4>
<p>Strong and durable water storage tanks.</p>
</div>
</div>

<div class="product-card">
<img src="https://picsum.photos/600/400?tiles" loading="eager">
<div>
<h4>Exotic Tiles</h4>
<p>Luxury tiles for modern floors and walls.</p>
</div>
</div>

<div class="product-card">
<img src="https://picsum.photos/600/400?bathroom" loading="eager">
<div>
<h4>Bathroom Sets</h4>
<p>Modern and elegant bathroom accessories.</p>
</div>
</div>

<div class="product-card">
<img src="https://picsum.photos/600/400?plumbing" loading="eager">
<div>
<h4>Plumbing Fittings</h4>
<p>High-quality plumbing materials.</p>
</div>
</div>

<div class="product-card">
<img src="https://picsum.photos/600/400?shower" loading="eager">
<div>
<h4>Shower Curtains</h4>
<p>Stylish and durable shower solutions.</p>
</div>
</div>

</div>
</section>

<section class="why">
<div class="section-title">
<h3>Why Choose Us</h3>
</div>
<ul>
<li>✔ Competitive Pricing</li>
<li>✔ High Standards & Quality Materials</li>
<li>✔ Safety First</li>
<li>✔ Customer Satisfaction</li>
</ul>
</section>

<section id="about">
<div class="section-title">
<h3>About Us</h3>
</div>
<div class="about">
<p>
CHIDI AGU ENTERPRISE is a trusted supplier of building materials,
plumbing fittings and luxury home solutions.
We focus on quality, reliability and long-lasting customer relationships.
</p>
</div>
</section>

<section id="contact">
<div class="contact">
<h3>Contact Us</h3>
<p>📍 Nigeria</p>
<p>📞 09044785578</p>
<p>✉️ chidiaguenterprise@gmail.com</p>

<div class="social-links">
<a href="https://facebook.com/" target="_blank" class="fb">Facebook</a>
<a href="https://instagram.com/" target="_blank" class="ig">Instagram</a>
<a href="https://x.com/" target="_blank" class="tw">X (Twitter)</a>
<a href="mailto:chidiaguenterprise@gmail.com" class="mail">Email Us</a>
</div>
</div>
</section>

<footer>
© 2025 CHIDI AGU ENTERPRISE. All Rights Reserved.
</footer>

<!-- WHATSAPP CHAT WITH AUTO MESSAGE -->
<a class="whatsapp"
href="https://wa.me/2349044785578?text=Hello%20CHIDI%20AGU%20ENTERPRISE,%20I%20am%20interested%20in%20your%20products."
target="_blank">
💬 Chat on WhatsApp
</a>

</body>
</html># CHIDI-AGU-ENTERPRISE
A PROFESSIONAL WEBSITE FOR BUILDING MATERIALS AND CONTRAINDICATIONS TOOLS 
