<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<meta name="description" content="AutoMaster Tamil - Learn Automobile Engineering, Engine Systems, NVQ Level 3 Study Materials and MCQ Quizzes">
<meta name="keywords" content="Automobile, Tamil, Engine Systems, NVQ Level 3, Auto Learning">
<meta name="author" content="AutoMaster Tamil">
<title>AutoMaster Tamil</title>

<style>
:root{
    --bg:#f5f7fa;
    --card:#ffffff;
    --text:#222;
    --primary:#0066ff;
    --shadow:0 5px 15px rgba(0,0,0,0.1);
}

.dark{
    --bg:#121212;
    --card:#1e1e1e;
    --text:#ffffff;
}

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:Arial, sans-serif;
}

body{
    background:var(--bg);
    color:var(--text);
    transition:.3s;
}

header{
    background:linear-gradient(135deg,#0066ff,#00c6ff);
    color:white;
    padding:20px;
    position:sticky;
    top:0;
    z-index:1000;
}

nav{
    display:flex;
    justify-content:space-between;
    align-items:center;
    flex-wrap:wrap;
}

.logo{
    font-size:28px;
    font-weight:bold;
}

nav ul{
    list-style:none;
    display:flex;
    gap:20px;
}

nav ul li a{
    color:white;
    text-decoration:none;
    font-weight:bold;
}

.toggle-btn{
    background:white;
    color:black;
    border:none;
    padding:8px 15px;
    border-radius:20px;
    cursor:pointer;
}

.hero{
    text-align:center;
    padding:100px 20px;
}

.hero h1{
    font-size:50px;
    margin-bottom:20px;
}

.hero p{
    font-size:20px;
    margin-bottom:20px;
}

.btn{
    background:var(--primary);
    color:white;
    padding:12px 25px;
    text-decoration:none;
    border-radius:30px;
}

section{
    padding:60px 20px;
    max-width:1200px;
    margin:auto;
}

.section-title{
    text-align:center;
    margin-bottom:40px;
    font-size:35px;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
    gap:20px;
}

.card{
    background:var(--card);
    padding:25px;
    border-radius:15px;
    box-shadow:var(--shadow);
}

.card h3{
    margin-bottom:15px;
}

.quiz-box{
    background:var(--card);
    padding:25px;
    border-radius:15px;
    box-shadow:var(--shadow);
    text-align:center;
}

.quiz-box button{
    margin-top:15px;
    padding:10px 20px;
    border:none;
    background:var(--primary);
    color:white;
    border-radius:10px;
    cursor:pointer;
}

.contact-form{
    display:flex;
    flex-direction:column;
    gap:15px;
}

.contact-form input,
.contact-form textarea{
    padding:12px;
    border:1px solid #ccc;
    border-radius:10px;
}

.contact-form button{
    padding:12px;
    border:none;
    background:var(--primary);
    color:white;
    border-radius:10px;
    cursor:pointer;
}

footer{
    background:#111;
    color:white;
    text-align:center;
    padding:20px;
}

@media(max-width:768px){
    nav{
        flex-direction:column;
        gap:15px;
    }

    nav ul{
        flex-wrap:wrap;
        justify-content:center;
    }

    .hero h1{
        font-size:35px;
    }
}
</style>
</head>

<body>

<header>
<nav>
<div class="logo">🚗 AutoMaster Tamil</div>

<ul>
<li><a href="#home">Home</a></li>
<li><a href="#learning">Learning</a></li>
<li><a href="#engine">Engine Notes</a></li>
<li><a href="#nvq">NVQ Level 3</a></li>
<li><a href="#quiz">Quiz</a></li>
<li><a href="#contact">Contact</a></li>
</ul>

<button class="toggle-btn" onclick="toggleDarkMode()">🌙 Dark Mode</button>
</nav>
</header>

<section class="hero" id="home">
<h1>AutoMaster Tamil</h1>
<p>Learn Automobile Engineering in Tamil from Basic to Advanced Level</p>
<a href="#learning" class="btn">Start Learning</a>
</section>

<section id="learning">
<h2 class="section-title">Automobile Learning</h2>

<div class="grid">

<div class="card">
<h3>Engine Fundamentals</h3>
<p>Learn petrol engines, diesel engines, engine cycles and working principles.</p>
</div>

<div class="card">
<h3>Transmission Systems</h3>
<p>Study clutch, gearbox, differential and power transmission systems.</p>
</div>

<div class="card">
<h3>Electrical Systems</h3>
<p>Understand batteries, alternators, starters and vehicle electronics.</p>
</div>

</div>
</section>

<section id="engine">
<h2 class="section-title">Engine Systems Notes</h2>

<div class="grid">

<div class="card">
<h3>Fuel System</h3>
<p>Petrol & Diesel fuel supply systems and maintenance procedures.</p>
</div>

<div class="card">
<h3>Cooling System</h3>
<p>Radiator, thermostat, coolant circulation and troubleshooting.</p>
</div>

<div class="card">
<h3>Lubrication System</h3>
<p>Oil pump, filters and engine lubrication functions.</p>
</div>

</div>
</section>

<section id="nvq">
<h2 class="section-title">NVQ Level 3 Study Materials</h2>

<div class="grid">

<div class="card">
<h3>Advanced Engine Technology</h3>
<p>Modern engine control systems and EFI technology.</p>
</div>

<div class="card">
<h3>Automotive Calculations</h3>
<p>Horsepower, torque, compression ratio and efficiency formulas.</p>
</div>

<div class="card">
<h3>Exam Preparation</h3>
<p>Important questions and revision notes for NVQ exams.</p>
</div>

</div>
</section>

<section id="quiz">
<h2 class="section-title">MCQ Quiz</h2>

<div class="quiz-box">
<h3 id="question">What does EFI stand for?</h3>

<button onclick="checkAnswer('a')">Electronic Fuel Injection</button>
<button onclick="checkAnswer('b')">Engine Fuel Indicator</button>

<p id="result"></p>
</div>
</section>

<section id="contact">
<h2 class="section-title">Contact Us</h2>

<form class="contact-form">
<input type="text" placeholder="Your Name" required>
<input type="email" placeholder="Your Email" required>
<textarea rows="5" placeholder="Your Message"></textarea>
<button type="submit">Send Message</button>
</form>

</section>

<footer>
<p>© 2026 AutoMaster Tamil | Automobile Learning Platform</p>
</footer>

<script>
function toggleDarkMode(){
    document.body.classList.toggle("dark");
}

function checkAnswer(answer){
    const result=document.getElementById("result");

    if(answer==="a"){
        result.innerHTML="✅ Correct Answer!";
        result.style.color="green";
    }else{
        result.innerHTML="❌ Wrong Answer!";
        result.style.color="red";
    }
}

document.querySelector(".contact-form").addEventListener("submit",function(e){
    e.preventDefault();
    alert("Message Sent Successfully!");
});
</script>

</body>
</html>
