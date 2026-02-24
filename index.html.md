# index.html  
  
<!DOCTYPE html>  
<html lang="en">  
<head>  
<meta charset="UTF-8">  
<title>Grupo Constructor Leuris</title>  
<meta name="viewport" content="width=device-width, initial-scale=1.0">  
  
<style>  
body {  
    margin:0;  
    font-family: "Segoe UI", Arial, sans-serif;  
    background:#f4f6f9;  
    color:#222;  
}  
  
header {  
    background:#0b2c4a;  
    padding:15px 40px;  
    display:flex;  
    align-items:center;  
    justify-content:space-between;  
}  
  
header img {  
    height:60px;  
}  
  
nav a {  
    color:white;  
    margin-left:25px;  
    text-decoration:none;  
    font-weight:600;  
}  
  
.hero {  
    background:linear-gradient(rgba(11,44,74,.75),rgba(11,44,74,.75)),  
    url("https://images.unsplash.com/photo-1581091870622-1e7e58c71c1d");  
    background-size:cover;  
    background-position:center;  
    color:white;  
    padding:120px 40px;  
    text-align:center;  
}  
  
.hero h1 {  
    font-size:48px;  
    margin-bottom:20px;  
}  
  
.hero p {  
    font-size:20px;  
    max-width:800px;  
    margin:auto;  
}  
  
.buttons a {  
    display:inline-block;  
    margin:15px;  
    padding:14px 30px;  
    background:#1fa67a;  
    color:white;  
    text-decoration:none;  
    border-radius:6px;  
    font-weight:bold;  
}  
  
section {  
    padding:70px 50px;  
}  
  
h2 {  
    text-align:center;  
    margin-bottom:40px;  
    color:#0b2c4a;  
}  
  
.grid {  
    display:grid;  
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));  
    gap:25px;  
}  
  
.card {  
    background:white;  
    padding:30px;  
    border-radius:10px;  
    box-shadow:0 4px 10px rgba(0,0,0,.1);  
}  
  
footer {  
    background:#0b2c4a;  
    color:white;  
    text-align:center;  
    padding:25px;  
}  
  
input, textarea {  
    width:100%;  
    padding:12px;  
    margin-bottom:15px;  
    border-radius:5px;  
    border:1px solid #ccc;  
}  
  
button {  
    background:#1fa67a;  
    color:white;  
    border:none;  
    padding:14px 25px;  
    border-radius:5px;  
    font-size:16px;  
    cursor:pointer;  
}  
  
.lang {  
    font-size:14px;  
    color:#ddd;  
}  
</style>  
</head>  
  
<body>  
  
<header>  
<img src="logo.png" alt="Grupo Constructor Leuris Logo">  
<nav>  
<a href="#home">Home</a>  
<a href="#about">About</a>  
<a href="#services">Services</a>  
<a href="#contact">Contact</a>  
</nav>  
</header>  
  
<section class="hero" id="home">  
<h1>Engineering, Construction, and Material Supply Solutions</h1>  
<p>Professional services and high-quality materials for construction, solar installations, and industrial projects.</p>  
  
<br>  
  
<h3>Soluciones en ingeniería, construcción y suministro de materiales</h3>  
<p>Servicios profesionales y materiales de alta calidad para proyectos de construcción, instalaciones solares e industriales.</p>  
  
<div class="buttons">  
<a href="#contact">Request a Quote</a>  
<a href="#contact">Solicitar Cotización</a>  
</div>  
</section>  
  
<section id="about">  
<h2>About Us / Sobre Nosotros</h2>  
<div class="grid">  
<div class="card">  
<p>  
Grupo Constructor Leuris is a professional company specialized in engineering, construction, and material supply.  
We provide integrated solutions for commercial, industrial, and renewable energy projects, ensuring quality, safety, and reliability at every stage.  
</p>  
</div>  
  
<div class="card">  
<p>  
Grupo Constructor Leuris es una empresa especializada en ingeniería, construcción y suministro de materiales.  
Ofrecemos soluciones integrales para proyectos comerciales, industriales y de energía renovable, garantizando calidad, seguridad y confiabilidad en cada etapa.  
</p>  
</div>  
</div>  
</section>  
  
<section id="services">  
<h2>Our Services / Nuestros Servicios</h2>  
<div class="grid">  
  
<div class="card">  
<h3>Construction Services</h3>  
<ul>  
<li>Industrial and commercial construction</li>  
<li>Infrastructure projects</li>  
<li>Structural systems</li>  
<li>Project execution and supervision</li>  
</ul>  
</div>  
  
<div class="card">  
<h3>Material Supply</h3>  
<ul>  
<li>Construction materials</li>  
<li>Roofing systems</li>  
<li>Solar installation components</li>  
<li>Electrical and structural supplies</li>  
</ul>  
</div>  
  
<div class="card">  
<h3>Engineering & Project Management</h3>  
<ul>  
<li>Planning and design</li>  
<li>Technical supervision</li>  
<li>Quality control</li>  
<li>Project management</li>  
</ul>  
</div>  
  
</div>  
</section>  
  
<section id="contact">  
<h2>Contact Us / Contáctanos</h2>  
  
<div class="grid">  
<div class="card">  
<form>  
<input type="text" placeholder="Name / Nombre">  
<input type="text" placeholder="Company / Empresa">  
<input type="email" placeholder="Email">  
<input type="text" placeholder="Phone / Teléfono">  
<textarea rows="5" placeholder="Message / Mensaje"></textarea>  
<button>Send Message</button>  
</form>  
</div>  
  
<div class="card">  
<h3>Company Information</h3>  
<p><strong>Grupo Constructor Leuris</strong></p>  
<p>Engineering, Construction and Material Supply</p>  
<p>Email: info@grupoconstructorleuris.com</p>  
<p>Phone: +52 XXX XXX XXXX</p>  
<p>Location: Mexico / USA</p>  
</div>  
</div>  
</section>  
  
<footer>  
<p>© 2026 Grupo Constructor Leuris. All Rights Reserved.</p>  
<p class="lang">Engineering • Construction • Material Supply</p>  
</footer>  
  
</body>  
</html>  
