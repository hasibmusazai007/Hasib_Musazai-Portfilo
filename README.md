# Hasib_Musazai
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Professional Portfolio</title>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.0/css/all.min.css">
<style>
:root{
--bg:#081226;
--card:#15233f;
--primary:#33b5ff;
--text:#cbd5e1;
--white:#fff;
}
*{margin:0;padding:0;box-sizing:border-box;font-family:Segoe UI,sans-serif;scroll-behavior:smooth}
body{background:linear-gradient(90deg,#0a1630,#07142d);color:var(--white)}
nav{position:fixed;top:0;width:100%;display:flex;justify-content:space-between;align-items:center;padding:18px 8%;background:rgba(5,10,25,.9);backdrop-filter:blur(10px);z-index:999;border-bottom:1px solid #233}
.logo{display:flex;align-items:center;gap:10px}
.logo img{width:40px;height:40px;border-radius:50%;border:2px solid var(--primary)}
nav ul{display:flex;list-style:none;gap:25px}
nav a{text-decoration:none;color:#ddd}
nav a:hover{color:var(--primary)}
section{padding:100px 8%}
.hero{min-height:100vh;display:flex;align-items:center;justify-content:space-between;gap:40px}
.hero h4{color:var(--primary)}
.hero h1{font-size:60px}
.hero h3{font-size:30px;color:#9fb7d8}
.hero p{max-width:600px;color:var(--text);margin:20px 0}
.btn{display:inline-block;padding:12px 22px;background:var(--primary);color:#000;text-decoration:none;border-radius:8px;margin-right:10px}
.btn2{background:transparent;border:1px solid var(--primary);color:var(--primary)}
.hero img{width:320px;height:320px;border-radius:50%;object-fit:cover;border:3px solid var(--primary);box-shadow:0 0 25px var(--primary),0 0 70px rgba(51,181,255,.4)}
.title{text-align:center;margin-bottom:50px}
.title p{color:var(--primary);letter-spacing:2px}
.title h2{font-size:42px}
.about-wrap{display:grid;grid-template-columns:1fr 1fr;gap:40px;align-items:center}
.about-wrap img{width:100%;max-width:350px;border-radius:20px;border:2px solid var(--primary);box-shadow:0 0 20px var(--primary)}
.stats{display:flex;gap:15px;margin:20px 0}
.stat{background:var(--card);padding:25px;border-radius:15px;text-align:center;flex:1}
.stat h3{color:var(--primary);font-size:30px}
.grid{display:grid;grid-template-columns:repeat(auto-fit,minmax(250px,1fr));gap:20px}
.card,.project,.contact-box{background:var(--card);padding:25px;border-radius:15px;border:1px solid #29405d}
.card:hover,.project:hover{transform:translateY(-8px);transition:.3s}
.card i{font-size:40px;color:var(--primary);margin-bottom:15px}
.project img{width:100%;height:180px;object-fit:cover;border-radius:10px;margin-bottom:15px}
.tags span{background:#0d3c66;padding:4px 8px;border-radius:20px;font-size:12px;margin-right:5px}
.contact-wrap{display:grid;grid-template-columns:300px 1fr;gap:20px}
form input,form textarea{width:100%;padding:14px;margin-bottom:12px;background:#09172f;border:1px solid #29405d;color:#fff;border-radius:8px}
form button{width:100%;padding:14px;border:none;background:var(--primary);border-radius:8px;font-weight:bold}
footer{text-align:center;padding:30px;color:#aaa}
.reveal{opacity:0;transform:translateY(30px);transition:.6s}
.reveal.active{opacity:1;transform:none}
@media(max-width:900px){
.hero,.about-wrap,.contact-wrap{grid-template-columns:1fr;display:grid}
.hero{text-align:center}
.hero h1{font-size:42px}
nav ul{display:none}
.hero img{margin:auto}
}
</style>
</head>
<body>

<nav>
<div class="logo">
<img src="https://via.placeholder.com/100">
<b>Your Name</b>
</div>
<ul>
<li><a href="#home">Home</a></li>
<li><a href="#about">About</a></li>
<li><a href="#skills">Skills</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>

<section class="hero" id="home">
<div>
<h4>Hello, I'm</h4>
<h1>Your Name</h1>
<h3><span id="typing"></span></h3>
<p>I build modern responsive websites and web applications using HTML, CSS, JavaScript, PHP, Laravel and MySQL.</p>
<a href="#contact" class="btn">Hire Me</a>
<a href="#" class="btn btn2">Download CV</a>
</div>
<img src="https://via.placeholder.com/500x500.png?text=Profile" alt="profile">
</section>

<section id="about" class="reveal">
<div class="title"><p>ABOUT ME</p><h2>Passionate Web Developer</h2></div>
<div class="about-wrap">
<div><img src="https://via.placeholder.com/500x600.png?text=About+Image"></div>
<div>
<p>I create clean and modern websites with a focus on performance, usability and responsive design.</p>
<div class="stats">
<div class="stat"><h3>2+</h3><p>Years</p></div>
<div class="stat"><h3>10+</h3><p>Projects</p></div>
<div class="stat"><h3>7+</h3><p>Clients</p></div>
</div>
<a href="#contact" class="btn">Contact Me</a>
</div>
</div>
</section>

<section id="skills" class="reveal">
<div class="title"><p>MY EXPERTISE</p><h2>Technologies & Tools</h2></div>
<div class="grid">
<div class="card"><i class="fab fa-html5"></i><h3>HTML5</h3><p>Semantic and SEO-friendly markup.</p></div>
<div class="card"><i class="fab fa-css3-alt"></i><h3>CSS3</h3><p>Responsive layouts and animations.</p></div>
<div class="card"><i class="fab fa-js"></i><h3>JavaScript</h3><p>Interactive web applications.</p></div>
<div class="card"><i class="fab fa-bootstrap"></i><h3>Bootstrap</h3><p>Fast responsive UI development.</p></div>
<div class="card"><i class="fab fa-react"></i><h3>React</h3><p>Reusable components and SPA.</p></div>
<div class="card"><i class="fas fa-database"></i><h3>MySQL</h3><p>Database design and management.</p></div>
</div>
</section>

<section id="projects" class="reveal">
<div class="title"><p>MY WORK</p><h2>Featured Projects</h2></div>
<div class="grid">
<div class="project"><img src="https://via.placeholder.com/600x400"><h3>Student Management System</h3><p>PHP & MySQL project.</p><div class="tags"><span>PHP</span><span>MySQL</span></div></div>
<div class="project"><img src="https://via.placeholder.com/600x400"><h3>E-Commerce Website</h3><p>Laravel online store.</p><div class="tags"><span>Laravel</span><span>Blade</span></div></div>
<div class="project"><img src="https://via.placeholder.com/600x400"><h3>Chat Application</h3><p>Realtime messaging platform.</p><div class="tags"><span>AJAX</span><span>JS</span></div></div>
</div>
</section>

<section id="contact" class="reveal">
<div class="title"><p>GET IN TOUCH</p><h2>Contact Me</h2></div>
<div class="contact-wrap">
<div>
<div class="contact-box"><h3>Email</h3><p>h47816mz@gmail.com</p></div><br>
<div class="contact-box"><h3>Phone</h3><p>+93 787-088-141</p></div><br>
<div class="contact-box"><h3>Location</h3><p>Kabul, Afghanistan</p></div>
</div>
<form>
<input placeholder="Name">
<input placeholder="Email">
<input placeholder="Subject">
<textarea rows="7" placeholder="Message"></textarea>
<button>Send Message</button>
</form>
</div>
</section>

<footer>© 2026 Hasibullah Musazai. All Rights Reserved.</footer>

<script>
const texts=["Full Stack Developer","Frontend Developer","PHP Laravel Developer"];
let i=0,j=0,current="",erase=false;
function type(){
if(!erase && j<=texts[i].length){current=texts[i].substring(0,j++);}
if(erase && j>=0){current=texts[i].substring(0,j--);}
document.getElementById("typing").textContent=current;
if(j===texts[i].length+1){erase=true;setTimeout(type,1000);return;}
if(erase && j<0){erase=false;i=(i+1)%texts.length;}
setTimeout(type,erase?50:100);
}
type();

const reveals=document.querySelectorAll('.reveal');
window.addEventListener('scroll',()=>{
reveals.forEach(el=>{
if(el.getBoundingClientRect().top<window.innerHeight-100){
el.classList.add('active');
}
});
});
</script>

</body>
</html>
