<!DOCTYPE html>  
<html lang="en">  
<head>  
<meta charset="UTF-8">  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
  
<title>CropBoostIndia | Premium Agricultural Solutions</title>  
<meta name="description" content="CropBoostIndia provides high-quality micronutrients, biofertilizers, seaweed extract and advanced agricultural solutions for higher crop yield.">  
  
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">  
  
<style>  
*{margin:0;padding:0;box-sizing:border-box;font-family:'Poppins',sans-serif;}  
body{background:#f5f9f5;color:#333;}  
header{  
    background:#145a32;  
    padding:15px 8%;  
    display:flex;  
    justify-content:space-between;  
    align-items:center;  
    position:sticky;  
    top:0;  
    z-index:1000;  
}  
header h1{color:#fff;}  
nav a{  
    color:white;  
    margin-left:20px;  
    text-decoration:none;  
    font-weight:500;  
}  
.hero{  
    background:linear-gradient(rgba(0,0,0,.6),rgba(0,0,0,.6)),  
    url('https://images.unsplash.com/photo-1501004318641-b39e6451bec6');  
    background-size:cover;  
    background-position:center;  
    padding:120px 20px;  
    text-align:center;  
    color:white;  
}  
.hero h2{font-size:42px;margin-bottom:20px;}  
.hero p{font-size:18px;margin-bottom:30px;}  
.btn{  
    background:#2ecc71;  
    color:white;  
    padding:12px 25px;  
    border-radius:5px;  
    text-decoration:none;  
    font-weight:600;  
}  
section{padding:80px 8%;}  
.section-title{text-align:center;font-size:30px;margin-bottom:40px;color:#145a32;}  
  
.products{  
    display:grid;  
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));  
    gap:25px;  
}  
.product-card{  
    background:white;  
    padding:20px;  
    border-radius:10px;  
    box-shadow:0 5px 15px rgba(0,0,0,0.1);  
    text-align:center;  
}  
.product-card h3{margin-bottom:10px;color:#1e8449;}  
.product-card button{  
    background:#27ae60;  
    color:white;  
    border:none;  
    padding:8px 15px;  
    border-radius:4px;  
    cursor:pointer;  
}  
.about{background:#eafaf1;text-align:center;}  
  
.testimonials{  
    display:grid;  
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));  
    gap:20px;  
}  
.testimonial{  
    background:white;  
    padding:20px;  
    border-radius:10px;  
    box-shadow:0 4px 12px rgba(0,0,0,0.1);  
}  
  
.faq-item{margin-bottom:15px;}  
.faq-item h4{color:#145a32;}  
  
form{  
    max-width:500px;  
    margin:auto;  
    display:flex;  
    flex-direction:column;  
}  
form input, form textarea{  
    margin-bottom:15px;  
    padding:12px;  
    border:1px solid #ccc;  
    border-radius:5px;  
}  
form button{  
    background:#145a32;  
    color:white;  
    padding:12px;  
    border:none;  
    border-radius:5px;  
    cursor:pointer;  
}  
  
footer{  
    background:#145a32;  
    color:white;  
    padding:40px 8%;  
}  
.footer-grid{  
    display:grid;  
    grid-template-columns:repeat(auto-fit,minmax(200px,1fr));  
    gap:30px;  
}  
footer a{color:white;text-decoration:none;display:block;margin-bottom:8px;}  
  
.whatsapp{  
    position:fixed;  
    bottom:20px;  
    right:20px;  
    background:#25D366;  
    color:white;  
    padding:15px;  
    border-radius:50%;  
    font-size:22px;  
    text-decoration:none;  
}  
</style>  
</head>  
  
<body>  
  
<header>  
<h1>CropBoostIndia</h1>  
<nav>  
<a href="#about">About</a>  
<a href="#products">Products</a>  
<a href="#distributor">Distributor</a>  
<a href="#faq">FAQ</a>  
<a href="#contact">Contact</a>  
</nav>  
</header>  
  
<section class="hero">  
<h2>Boosting Crops. Empowering Farmers.</h2>  
<p>Premium Micronutrients • Biofertilizers • Growth Enhancers</p>  
<a href="#products" class="btn">Shop Now</a>  
</section>  
  
<section id="about" class="about">  
<h2 class="section-title">About Us</h2>  
<p>CropBoostIndia delivers scientifically formulated agricultural inputs to maximize crop productivity and improve soil health. We focus on innovation, quality, and farmer success.</p>  
</section>  
  
<section id="products">  
<h2 class="section-title">Our Products</h2>  
<div class="products">  
  
<div class="product-card">  
<h3>Seaweed Extract</h3>  
<p>Improves plant vigor and yield.</p>  
<button onclick="addToCart()">Add to Cart</button>  
</div>  
  
<div class="product-card">  
<h3>Micronutrient Mixture</h3>  
<p>Corrects soil nutrient deficiency.</p>  
<button onclick="addToCart()">Add to Cart</button>  
</div>  
  
<div class="product-card">  
<h3>Liquid Biofertilizer</h3>  
<p>Enhances soil fertility naturally.</p>  
<button onclick="addToCart()">Add to Cart</button>  
</div>  
  
<div class="product-card">  
<h3>Humic Acid</h3>  
<p>Boosts root growth & nutrient uptake.</p>  
<button onclick="addToCart()">Add to Cart</button>  
</div>  
  
</div>  
</section>  
  
<section>  
<h2 class="section-title">What Farmers Say</h2>  
<div class="testimonials">  
<div class="testimonial">“Excellent results in wheat crop. Yield increased significantly.”</div>  
<div class="testimonial">“Best micronutrient product in my district.”</div>  
<div class="testimonial">“Fast response and good quality.”</div>  
</div>  
</section>  
  
<section id="distributor">  
<h2 class="section-title">Become a Distributor</h2>  
<form>  
<input type="text" placeholder="Full Name" required>  
<input type="email" placeholder="Email Address" required>  
<input type="text" placeholder="Phone Number" required>  
<textarea rows="4" placeholder="Your Message"></textarea>  
<button type="submit">Submit Inquiry</button>  
</form>  
</section>  
  
<section id="faq">  
<h2 class="section-title">Frequently Asked Questions</h2>  
<div class="faq-item">  
<h4>Are your products certified?</h4>  
<p>Yes, our products comply with government agricultural regulations.</p>  
</div>  
<div class="faq-item">  
<h4>Do you offer bulk supply?</h4>  
<p>Yes, distributor and bulk purchase options are available.</p>  
</div>  
<div class="faq-item">  
<h4>Do you provide field support?</h4>  
<p>Yes, we provide agronomic guidance and demo support.</p>  
</div>  
</section>  
  
<section id="contact" class="about">  
<h2 class="section-title">Contact Us</h2>  
<p>Email: info@cropboostindia.com</p>  
<p>Phone: +91-XXXXXXXXXX</p>  
<p>Location: India</p>  
</section>  
  
<footer>  
<div class="footer-grid">  
<div>  
<h3>CropBoostIndia</h3>  
<p>Advanced Agricultural Solutions</p>  
</div>  
<div>  
<h4>Quick Links</h4>  
<a href="#about">About</a>  
<a href="#products">Products</a>  
<a href="#contact">Contact</a>  
</div>  
<div>  
<h4>Business</h4>  
<a href="#distributor">Become Distributor</a>  
<a href="#">Privacy Policy</a>  
<a href="#">Terms & Conditions</a>  
</div>  
</div>  
<p style="margin-top:30px;text-align:center;">© 2026 CropBoostIndia. All Rights Reserved.</p>  
</footer>  
  
<a href="https://wa.me/91XXXXXXXXXX" class="whatsapp">💬</a>  
  
<script>  
function addToCart(){  
    alert("Product added to cart (Demo Version)");  
}  
</script>  
  
</body>  
</html>  
