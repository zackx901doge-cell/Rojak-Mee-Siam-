# Rojak-Mee-Siam-<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Rojak & Mee Siam</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
<style>
* { margin:0; padding:0; box-sizing:border-box; font-family:'Poppins', sans-serif; scroll-behavior:smooth;}
body { line-height:1.6; background:#FFF8E1; color:#333; }

header {
  display:flex; justify-content:space-between; align-items:center; padding:20px 40px; 
  background:#6B8E23; color:#fff; position:sticky; top:0; z-index:1000;
  box-shadow:0 4px 6px rgba(0,0,0,0.2);
}
header .logo { font-weight:700; font-size:1.8em; letter-spacing:1px;}
nav a { margin-left:25px; text-decoration:none; color:#fff; font-weight:500; transition:0.3s;}
nav a:hover { color:#FFD700; }
nav { display:flex; }

.hamburger { display:none; font-size:2em; cursor:pointer; color:#fff; }

.hero { text-align:center; padding:100px 20px; background: linear-gradient(135deg,#FFFBCC,#FFE4B5);}
.hero h1 { font-size:3em; color:#6B8E23; margin-bottom:15px; opacity:0; transform:translateY(-20px); animation:slideDown 1s forwards;}
.hero p { font-size:1.3em; color:#556B2F; opacity:0; transform:translateY(-20px); animation:slideDown 1.2s forwards; }

@keyframes slideDown {
  to { opacity:1; transform:translateY(0);}
}

section { padding:60px 20px; text-align:center; opacity:0; transform:translateY(20px); transition:0.8s ease-out;}
section.active { opacity:1; transform:translateY(0); }

#menu h2, #info h2, #location h2 { color:#6B8E23; margin-bottom:20px; letter-spacing:1px;}
.cards { display:flex; justify-content:center; flex-wrap:wrap; gap:20px; margin-top:30px;}
.card { background:#FFFACD; padding:20px; border-radius:10px; box-shadow:0 4px 8px rgba(0,0,0,0.2); width:200px; transition:transform 0.3s, background 0.3s; cursor:pointer;}
.card:hover { transform:translateY(-7px); background:#FAFAD2;}

.highlight { color:#228B22; font-weight:bold; }

footer { background:#6B8E23; color:#fff; text-align:center; padding:20px; }

@media(max-width:768px){
  nav { display:none; flex-direction:column; background:#6B8E23; padding:10px; }
  nav.show { display:flex; }
  .hamburger { display:block; }
}
</style>
</head>
<body>

<header>
  <div class="logo">Rojak & Mee Siam</div>
  <div class="hamburger" id="hamburger">&#9776;</div>
  <nav id="nav-menu">
    <a href="#menu">Menu</a>
    <a href="#info">Information</a>
    <a href="#location">Location</a>
  </nav>
</header>

<section class="hero">
  <h1>Old-School Rojak & Mee Siam</h1>
  <p>Taste the classics, made fresh daily!</p>
</section>

<section id="menu">
  <h2>Our Menu</h2>
  <p class="highlight">*Mee Siam: Morning only & limited!* </p>
  <div class="cards">
    <div class="card"><h3>Tepung Kosong</h3><p>$1.00</p></div>
    <div class="card"><h3>Tepung Kelapa</h3><p>$1.20</p></div>
    <div class="card"><h3>Tee Sian</h3><p>$1.00</p></div>
    <div class="card"><h3>Fish Ball</h3><p>$1.00</p></div>
    <div class="card"><h3>Sotong Kering</h3><p>$2.00</p></div>
    <div class="card"><h3>Telur Rebus</h3><p>$1.00</p></div>
    <div class="card"><h3>Ubi Kentang</h3><p>$0.80/$1.00</p></div>
    <div class="card"><h3>Paru Lembu</h3><p>$2.00</p></div>
    <div class="card"><h3>Fish Cake</h3><p>$1.60</p></div>
    <div class="card"><h3>Tempeh</h3><p>$2.00</p></div>
    <div class="card"><h3>Udang Cake</h3><p>$1.60</p></div>
    <div class="card"><h3>Tahu</h3><p>$1.20</p></div>
    <div class="card"><h3>Limpah Lembu</h3><p>$2.00</p></div>
    <div class="card"><h3>Ayam Cake</h3><p>$1.60</p></div>
    <div class="card"><h3>Hot Dog</h3><p>$0.80</p></div>
    <div class="card"><h3>Tepong Sayur</h3><p>$1.20</p></div>
    <div class="card"><h3>Hati Lembu</h3><p>$1.20</p></div>
    <div class="card"><h3>Udang Tepong</h3><p>$2.00</p></div>
    <div class="card"><h3>Fish Fillet</h3><p>$1.60</p></div>
    <div class="card"><h3>Tepong Telor</h3><p>$1.60</p></div>
  </div>
</section>

<section id="info">
  <h2>Information</h2>
  <ul style="list-style:none; padding:0; line-height:1.8;">
    <li>🕑 <span class="highlight">Closed every Friday 12:30 PM – 2:00 PM for prayer</span></li>
    <li>🏨 Featured at the Fullerton Hotel</li>
    <li>🍴 Previous Prime Minister Halimah Yacob's husband enjoyed our Rojak</li>
    <li>🥔 <span class="highlight">Sweet Potato Gravy: Unlimited refills!</span></li>
  </ul>
</section>

<section id="location">
  <h2>Location</h2>
  <p>📍 Geylang Serai Market, Stall 02-126</p>
  <iframe 
    src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d3978.123456!2d103.918765!3d1.317890!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x31da1234567890ab%3A0xabcdef1234567890!2sGeylang%20Serai%20Market!5e0!3m2!1sen!2ssg!4v1699999999999!5m2!1sen!2ssg" 
    width="100%" height="300" style="border:0;" allowfullscreen="" loading="lazy">
  </iframe>
</section>

<footer>
  <p>© 2026 Rojak & Mee Siam | All Rights Reserved</p>
</footer>

<script>
  // Hamburger menu
  const hamburger = document.getElementById('hamburger');
  const navMenu = document.getElementById('nav-menu');
  hamburger.addEventListener('click', () => { navMenu.classList.toggle('show'); });

  // Scroll animation for sections
  const sections = document.querySelectorAll('section');
  const observer = new IntersectionObserver(entries => {
    entries.forEach(entry => {
      if(entry.isIntersecting){ entry.target.classList.add('active'); }
    });
  }, { threshold:0.2 });
  sections.forEach(section => observer.observe(section));
</script>

</body>
</html>
