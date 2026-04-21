# cityend-trucking-website
<!DOCTYPE html><html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>CityEnd Trucking</title><link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;600;700&display=swap" rel="stylesheet"><style>
*{
  margin:0;
  padding:0;
  box-sizing:border-box;
  font-family:'Montserrat', sans-serif;
}

body{
  background:#0f172a;
  color:#fff;
}

/* HERO SECTION */
.hero{
  height:100vh;
  background:url('images/truck1.jpg') center/cover no-repeat;
  position:relative;
  display:flex;
  align-items:center;
  justify-content:center;
  text-align:center;
}

.hero::after{
  content:"";
  position:absolute;
  top:0;
  left:0;
  width:100%;
  height:100%;
  background:rgba(0,0,0,0.65);
}

.hero-content{
  position:relative;
  z-index:1;
  max-width:800px;
  padding:20px;
}

.hero h1{
  font-size:50px;
  font-weight:700;
  letter-spacing:1px;
}

.hero p{
  margin-top:15px;
  font-size:18px;
  color:#cbd5e1;
}

.btn{
  display:inline-block;
  margin-top:20px;
  padding:12px 25px;
  background:#f97316;
  color:white;
  text-decoration:none;
  border-radius:6px;
  font-weight:600;
  transition:0.3s;
}

.btn:hover{
  background:#ea580c;
}

.btn-secondary{
  background:#1d4ed8;
}

/* SECTIONS */
section{
  padding:60px 20px;
  text-align:center;
}

.section-title{
  font-size:32px;
  margin-bottom:20px;
  font-weight:700;
}

.about p{
  max-width:700px;
  margin:auto;
  color:#cbd5e1;
  line-height:1.6;
}

/* SERVICES */
.cards{
  display:grid;
  grid-template-columns:repeat(auto-fit, minmax(250px,1fr));
  gap:20px;
  margin-top:30px;
}

.card{
  background:#1e293b;
  padding:20px;
  border-radius:10px;
  box-shadow:0 10px 20px rgba(0,0,0,0.3);
}

.card h3{
  margin-bottom:10px;
  color:#f97316;
}

/* GALLERY */
.gallery{
  display:grid;
  grid-template-columns:repeat(auto-fit, minmax(250px,1fr));
  gap:15px;
  margin-top:30px;
}

.gallery img{
  width:100%;
  border-radius:10px;
  transition:0.3s;
}

.gallery img:hover{
  transform:scale(1.05);
}

/* CONTACT BAR */
.contact-bar{
  background:#0b1220;
  padding:40px 20px;
  text-align:center;
}

.phone{
  font-size:20px;
  margin:10px 0;
  color:#38bdf8;
}

footer{
  background:#020617;
  padding:20px;
  text-align:center;
  font-size:14px;
  color:#94a3b8;
}

/* FLOAT BUTTON */
.float-call{
  position:fixed;
  bottom:20px;
  right:20px;
  background:#22c55e;
  color:white;
  padding:15px 18px;
  border-radius:50px;
  text-decoration:none;
  font-weight:700;
  box-shadow:0 10px 20px rgba(0,0,0,0.4);
}
</style></head>
<body><!-- HERO --><header class="hero">
  <div class="hero-content">
    <h1>CityEnd Trucking</h1>
    <p>Reliable Transport Solutions up to 3 Tons Across Zimbabwe</p>
    <a class="btn" href="tel:+263777616273">Call Now</a>
    <a class="btn btn-secondary" href="tel:+263714033978">Backup Call</a>
  </div>
</header><!-- ABOUT --><section class="about">
  <h2 class="section-title">About Us</h2>
  <p>
    CityEnd Trucking provides fast, safe, and affordable transportation services for small loads up to 3 tons. 
    We operate across highways and local routes with a rate of $1.50 per kilometer.
  </p>
</section><!-- SERVICES --><section>
  <h2 class="section-title">Our Services</h2>
  <div class="cards">
    <div class="card">
      <h3>Local Transport</h3>
      <p>Quick deliveries within city and surrounding areas.</p>
    </div>
    <div class="card">
      <h3>Long Distance</h3>
      <p>Reliable highway transport across Zimbabwe.</p>
    </div>
    <div class="card">
      <h3>Small Loads</h3>
      <p>Perfect for furniture, goods, and small cargo up to 3 tons.</p>
    </div>
  </div>
</section><!-- GALLERY --><section>
  <h2 class="section-title">Our Trucks</h2>
  <div class="gallery">
    <img src="images/truck1.jpg" />
    <img src="images/truck2.jpg" />
    <img src="images/truck3.jpg" />
  </div>
</section><!-- CONTACT --><section class="contact-bar">
  <h2 class="section-title">Contact Us</h2>
  <p class="phone">📞 +263777616273</p>
  <p class="phone">📞 +263714033978</p>
  <p>Rate: $1.50 per kilometer</p>
</section><footer>
  © 2026 CityEnd Trucking. All rights reserved.
</footer><a class="float-call" href="tel:+263777616273">Call Now</a>

</body>
</html>
