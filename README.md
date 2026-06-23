# inamigos task1
<!DOCTYPE html>

<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>InAmigos Foundation | NGO Awareness</title>

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
background:#f8fafc;
color:#333;
}

/* Navbar */

nav{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 8%;
background:white;
box-shadow:0 2px 10px rgba(0,0,0,.1);
position:sticky;
top:0;
z-index:1000;
}

.logo{
font-size:28px;
font-weight:700;
color:#0d9488;
}

.logo span{
color:#f97316;
}

nav ul{
display:flex;
gap:25px;
list-style:none;
}

nav ul li a{
text-decoration:none;
color:#333;
font-weight:500;
transition:.3s;
}

nav ul li a:hover{
color:#0a988d;
}

/* Hero */

.hero{
height:90vh;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
background:linear-gradient(rgba(156, 157, 160, 0.733),rgba(0,0,0,.55)),
url('https://images.unsplash.com/photo-1488521787991-ed7bbaae773c');
background-size:cover;
<img src="c:\Users\Admin\Downloads\looogo.jpg" alt="InAmigos logo" class="hero-logo">
<h1>InAmigos Foundation</h1>
<p>Uniting Minds For Change</p>
background-position:center;
color:white;
padding:20px;
}
.hero-logo{
    width:120px;
    margin-bottom:20px;
}
.hero-content h1{
font-size:55px;
margin-bottom:15px;
}

.hero-content p{
font-size:20px;
margin-bottom:30px;
}

.btn{
padding:14px 28px;
border:none;
border-radius:30px;
cursor:pointer;
font-size:16px;
margin:10px;
transition:.3s;
}

.join{
background:#0d9488;
color:white;
}

.volunteer{
background:#f97316;
color:white;
}

.btn:hover{
transform:translateY(-3px);
}

/* Section */

section{
padding:80px 10%;
}

.heading{
text-align:center;
font-size:38px;
color:#0d9488;
margin-bottom:40px;
}

/* About */

.about{
text-align:center;
max-width:900px;
margin:auto;
line-height:1.8;
}

/* Projects */

.projects-grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
gap:25px;
}

.card{
background:white;
padding:25px;
border-radius:15px;
box-shadow:0 5px 15px rgba(0,0,0,.08);
transition:.4s;
}

.card:hover{
transform:translateY(-10px);
}

.card h3{
color:#0d9488;
margin-bottom:10px;
}

/* Impact */

.impact{
background:#0d9488;
color:white;
}

.stats{
display:flex;
justify-content:center;
flex-wrap:wrap;
gap:40px;
text-align:center;
}

.stat h2{
font-size:45px;
}

/* CTA */

.cta{
text-align:center;
background:#ffffff;
color:#0d9488;
}

.cta h2{
margin-bottom:20px;
}

/* Footer */

footer{
background:#0d9488;
color:white;
text-align:center;
padding:25px;
}

/* Popup */

.popup{
display:none;
position:fixed;
top:0;
left:0;
width:100%;
height:100%;
background:rgba(0,0,0,.7);
justify-content:center;
align-items:center;
z-index:2000;
}

.popup-content{
background:white;
padding:30px;
border-radius:15px;
width:90%;
max-width:450px;
}

.popup-content h2{
margin-bottom:20px;
color:#07decc;
}

.popup-content input,
.popup-content textarea{
width:100%;
padding:12px;
margin:10px 0;
border:1px solid #ccc;
border-radius:8px;
}

.submit-btn{
background:#07d1c0;
color:white;
border:none;
padding:12px;
width:100%;
border-radius:8px;
cursor:pointer;
}

.close{
float:right;
font-size:24px;
cursor:pointer;
}

@media(max-width:768px){

.hero-content h1{
font-size:36px;
}

.stats{
flex-direction:column;
}

nav ul{
display:none;
}

}

</style>

</head>

<body>

<nav>
<div class="logo">
    <img src="c:\Users\Admin\Downloads\looogo.jpg" alt="InAmigos Logo" height="60">
</div>

<ul>
<li><a href="#about">About</a></li>
<li><a href="#projects">Projects</a></li>
<li><a href="#impact">Impact</a></li>
<li><a href="#contact">Contact</a></li>
</ul>
</nav>

<section class="hero">

<div class="hero-content">

<h1>InAmigos Foundation</h1>

<p>Uniting Minds For Change</p>

<button class="btn join" onclick="openJoin()">Join Now</button>

<button class="btn volunteer" onclick="openVolunteer()('Submitted Successfully!')">Become a Volunteer</button>

</div>

</section>

<section id="about">

<h2 class="heading">About Us</h2>

<div class="about">

<p>
InAmigos Foundation is a non-profit organization dedicated to creating positive social impact through education, environmental sustainability, women empowerment, animal welfare, hunger relief, and skill development initiatives. We believe collective action can transform communities and create a brighter future for everyone.
</p>

</div>

</section>

<section id="projects">

<h2 class="heading">Our Projects</h2>

<div class="projects-grid">

<div class="card">
<h3>SEVA</h3>
<p>Providing food, clothing, and support to underprivileged communities.</p>
</div>

<div class="card">
<h3>BACHPANSHALA</h3>
<p>Promoting education and learning opportunities for children.</p>
</div>

<div class="card">
<h3>UDAAN</h3>
<p>Empowering women through education and skill development.</p>
</div>

<div class="card">
<h3>PRAKRITI</h3>
<p>Supporting environmental sustainability and tree plantation drives.</p>
</div>

<div class="card">
<h3>JEEV</h3>
<p>Animal welfare initiatives including rescue and care programs.</p>
</div>

<div class="card">
<h3>VIKAS</h3>
<p>Skill development and internship opportunities for youth.</p>
</div>

</div>

</section>

<section id="impact" class="impact">

<h2 class="heading" style="color:white;">Our Impact</h2>

<div class="stats">

<div class="stat">
<h2>500+</h2>
<p>Volunteers</p>
</div>

<div class="stat">
<h2>10K+</h2>
<p>Lives Impacted</p>
</div>

<div class="stat">
<h2>50+</h2>
<p>Campaigns</p>
</div>

</div>

</section>

<section class="cta" id="contact">

<h2>Be The Change You Wish To See</h2>

<p>Join us in creating a better future.</p>

<br>

<button class="btn join" onclick="openJoin()">Support Us</button>

</section>

<footer>
    
    <img src="c:\Users\Admin\Downloads\looogo.jpg" width="80">
    <h3>#InAmigos</h3>


<h3>#InAmigos</h3>

<p>Uniting Minds For Change © 2026</p>

</footer>

<!-- Volunteer Popup -->

<div class="popup" id="volunteerPopup">

<div class="popup-content">

<span class="close" onclick="closeVolunteer()">×</span>

<h2>Volunteer Registration</h2>

<input type="text" placeholder="Full Name">

<input type="email" placeholder="Email">

<input type="tel" placeholder="Phone Number">

<textarea placeholder="Why do you want to volunteer?"></textarea>

<button class="submit-btn" onclick="alert('Submitted Successfully!'); closeVolunteer();">
    Submit
</button>

</div>

</div>


<!-- Join Popup -->

<div class="popup" id="joinPopup">

<div class="popup-content">

<span class="close" onclick="closeJoin()">×</span>

<h2>Join InAmigos</h2>

<input type="text" placeholder="Full Name">

<input type="email" placeholder="Email">

<input type="tel" placeholder="Phone Number">

<input type="button" value="Join Now" onclick="alert('Submitted Successfully!')">


</div>

</div>

<script>


function openVolunteer(){
document.getElementById("volunteerPopup").style.display="flex";
}

function closeVolunteer(){
document.getElementById("volunteerPopup").style.display="none";
}

function openJoin(){
document.getElementById("joinPopup").style.display="flex";
}

function closeJoin(){
document.getElementById("joinPopup").style.display="none";
}

window.onclick=function(e){

if(e.target==document.getElementById("volunteerPopup")){
closeVolunteer();
}

if(e.target==document.getElementById("joinPopup")){
closeJoin();
}

}

</script>

</body>
</html>

