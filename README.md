<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Prince Kumar | Future IAS Officer</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;500;700&display=swap" rel="stylesheet">

<style>
*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:linear-gradient(135deg,#0f2027,#203a43,#2c5364);
color:white;
overflow-x:hidden;
}

/* WELCOME SCREEN */
#welcome{
height:100vh;
display:flex;
flex-direction:column;
justify-content:center;
align-items:center;
text-align:center;
background:url('https://images.unsplash.com/photo-1588072432836-e10032774350') no-repeat center/cover;
animation:fadeIn 2s ease-in-out;
}

#welcome h1{
font-size:50px;
background:linear-gradient(45deg,#FFD700,#fff);
-webkit-background-clip:text;
color:transparent;
animation:glow 2s infinite alternate;
}

#welcome button{
margin-top:30px;
padding:12px 30px;
border:none;
border-radius:30px;
background:#FFD700;
color:black;
font-weight:bold;
cursor:pointer;
transition:0.3s;
}

#welcome button:hover{
background:white;
transform:scale(1.1);
}

@keyframes glow{
from{text-shadow:0 0 10px gold;}
to{text-shadow:0 0 25px white;}
}

@keyframes fadeIn{
from{opacity:0;}
to{opacity:1;}
}

/* NAVBAR */
nav{
position:fixed;
top:0;
width:100%;
background:rgba(0,0,0,0.7);
display:flex;
justify-content:center;
padding:10px;
z-index:1000;
}

nav a{
color:white;
text-decoration:none;
margin:0 15px;
font-weight:500;
transition:0.3s;
}

nav a:hover{
color:#FFD700;
}

/* SECTIONS */
.section{
min-height:100vh;
padding:120px 40px;
display:none;
background-size:cover;
background-position:center;
}

.section h2{
text-align:center;
margin-bottom:40px;
font-size:35px;
color:#FFD700;
}

/* GRID BOXES */
.grid{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
}

.box{
background:rgba(0,0,0,0.7);
padding:20px;
border-radius:15px;
cursor:pointer;
transition:0.4s;
box-shadow:0 0 10px #FFD700;
}

.box:hover{
transform:translateY(-10px);
box-shadow:0 0 25px gold;
}

.content{
display:none;
margin-top:10px;
font-size:14px;
color:#ddd;
}

footer{
text-align:center;
padding:20px;
background:black;
}
</style>
</head>

<body>

<!-- WELCOME SCREEN -->
<div id="welcome">
<h1>Welcome to The Journey of IAS Officer</h1>
<p>Discipline • Dedication • Determination</p>
<button onclick="enterSite()">Enter Mission UPSC</button>
</div>

<!-- NAVBAR -->
<nav id="navbar" style="display:none;">
<a href="#home" onclick="showSection('home')">Home</a>
<a href="#guidance" onclick="showSection('guidance')">UPSC Guidance</a>
<a href="#syllabus" onclick="showSection('syllabus')">Syllabus</a>
<a href="#about" onclick="showSection('about')">About Me</a>
<a href="#contact" onclick="showSection('contact')">Contact</a>
</nav>

<!-- HOME -->
<section id="home" class="section"
style="background-image:url('https://images.unsplash.com/photo-1524995997946-a1c2e315a42f')">
<h2>Home - Vision & Mission</h2>
<div class="grid">
<div class="box" onclick="toggle(this)">
<h3>My Dream</h3>
<div class="content">
My dream is to crack UPSC and become an honest IAS officer to serve India with integrity.
</div></div>

<div class="box" onclick="toggle(this)">
<h3>Why UPSC?</h3>
<div class="content">
UPSC gives opportunity to work for nation development and help people at district and national level.
</div></div>

<div class="box" onclick="toggle(this)">
<h3>Discipline</h3>
<div class="content">
Daily study routine, newspaper reading and answer writing practice.
</div></div>

<div class="box" onclick="toggle(this)">
<h3>Hard Work</h3>
<div class="content">
Consistent preparation for 2-3 years with full focus.
</div></div>

<div class="box" onclick="toggle(this)">
<h3>Leadership</h3>
<div class="content">
IAS officer leads district administration and ensures law and development.
</div></div>

<div class="box" onclick="toggle(this)">
<h3>Nation First</h3>
<div class="content">
My goal is service before self and honesty before power.
</div></div>
</div>
</section>

<!-- ABOUT -->
<section id="about" class="section"
style="background-image:url('https://images.unsplash.com/photo-1521737604893-d14cc237f11d')">
<h2>About Me</h2>
<div class="grid">

<div class="box" onclick="toggle(this)">
<h3>Name</h3>
<div class="content">
Prince Kumar
</div></div>

<div class="box" onclick="toggle(this)">
<h3>School</h3>
<div class="content">
I study at Pride International School, located approximately 1 km from my home. 
It is a modern educational institution focused on quality education and overall personality development. 
The school provides smart classrooms, disciplined environment, and well-qualified teachers. 

Features of my school:
• Modern teaching methods  
• Computer and coding classes  
• Spoken English improvement  
• Co-curricular activities  
• Moral and value education  

Coding is also taught in our school which helps students learn technology and develop future-ready skills. 
Our school prepares students not only for exams but also for real life and global opportunities.
</div></div>

<div class="box" onclick="toggle(this)">
<h3>Goal</h3>
<div class="content">
To crack UPSC and become IAS officer.
</div></div>

<div class="box" onclick="toggle(this)">
<h3>Hobbies</h3>
<div class="content">
Reading books, learning coding, watching news.
</div></div>

</div>
</section>

<!-- CONTACT -->
<section id="contact" class="section"
style="background-image:url('https://images.unsplash.com/photo-1519389950473-47ba0277781c')">
<h2>Contact Me</h2>
<div class="grid">

<div class="box" onclick="toggle(this)">
<h3>Email</h3>
<div class="content">
princeguptaui@gmail.com
</div></div>

<div class="box" onclick="toggle(this)">
<h3>Instagram</h3>
<div class="content">
@The_alone
</div></div>

<div class="box" onclick="toggle(this)">
<h3>Location</h3>
<div class="content">
Narkatiaganj, Bihar, India
</div></div>

<div class="box">
<h3>My Portfolio</h3>
<div class="content" style="display:block;">
<a href="https://princeguptaui-ui.github.io/Now/" target="_blank" style="color:#FFD700; text-decoration:none;">
Click Here To Visit My Portfolio
</a>
</div>
</div>

</div>
</section>

<footer>
© 2026 Prince Kumar | Future IAS Officer
</footer>

<script>
function enterSite(){
document.getElementById("welcome").style.display="none";
document.getElementById("navbar").style.display="flex";
showSection('home');
}

function showSection(id){
let sections=document.querySelectorAll('.section');
sections.forEach(sec=>sec.style.display="none");
document.getElementById(id).style.display="block";
}

function toggle(box){
let content=box.querySelector('.content');
content.style.display = content.style.display === "block" ? "none" : "block";
}
</script>

</body>
</html>
