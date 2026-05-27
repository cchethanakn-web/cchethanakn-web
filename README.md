<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>GitHub Dashboard</title>

<!-- Google Font -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<!-- Typing Animation -->
<script src="https://unpkg.com/typed.js@2.1.0/dist/typed.umd.js"></script>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Poppins',sans-serif;
    background:#0f172a;
    color:white;
    min-height:100vh;
}

/* Main Container */

.container{
    width:90%;
    max-width:1100px;
    margin:auto;
    padding:40px 0;
    text-align:center;
}

/* Profile Section */

.profile img{
    width:150px;
    height:150px;
    border-radius:50%;
    border:4px solid #8b5cf6;
    object-fit:cover;
    box-shadow:0 0 25px #8b5cf6;
    animation:float 3s ease-in-out infinite;
}

@keyframes float{
    0%{transform:translateY(0px);}
    50%{transform:translateY(-10px);}
    100%{transform:translateY(0px);}
}

h1{
    margin-top:20px;
    font-size:40px;
}

.typing{
    color:#a855f7;
    font-size:24px;
    font-weight:600;
    margin-top:10px;
}

/* About */

.about{
    margin-top:30px;
    font-size:18px;
    line-height:1.8;
    color:#cbd5e1;
}

/* Skills */

.skills{
    margin-top:50px;
}

.skills h2{
    margin-bottom:20px;
    font-size:32px;
}

.skill-box{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:15px;
}

.skill{
    background:#1e293b;
    padding:12px 20px;
    border-radius:10px;
    transition:0.3s;
    border:1px solid transparent;
}

.skill:hover{
    transform:translateY(-5px);
    border-color:#8b5cf6;
    box-shadow:0 0 15px #8b5cf6;
}

/* GitHub Cards */

.github{
    margin-top:60px;
}

.github img{
    width:100%;
    max-width:500px;
    margin:15px;
    border-radius:15px;
}

/* Social Links */

.social{
    margin-top:50px;
}

.social a{
    text-decoration:none;
    color:white;
    margin:10px;
    padding:12px 20px;
    background:#8b5cf6;
    border-radius:8px;
    display:inline-block;
    transition:0.3s;
}

.social a:hover{
    background:#7c3aed;
    transform:scale(1.05);
}

/* Footer */

footer{
    margin-top:60px;
    color:#94a3b8;
    font-size:14px;
}

</style>
</head>

<body>

<div class="container">

    <!-- Profile -->
    <div class="profile">

        <!-- Change Your Image -->
        <img src="https://avatars.githubusercontent.com/u/9919?v=4" alt="profile">

        <!-- Change Your Name -->
        <h1>Your Name</h1>

        <!-- Typing Animation -->
        <div class="typing">
            <span id="element"></span>
        </div>

    </div>

    <!-- About -->
    <div class="about">
        <p>
            I am a Full Stack Developer passionate about Web Development,
            Blockchain, Open Source and Cybersecurity.
        </p>
    </div>

    <!-- Skills -->
    <div class="skills">

        <h2>Tech Stack</h2>

        <div class="skill-box">

            <div class="skill">HTML</div>
            <div class="skill">CSS</div>
            <div class="skill">JavaScript</div>
            <div class="skill">React</div>
            <div class="skill">Node.js</div>
            <div class="skill">Solidity</div>
            <div class="skill">Python</div>
            <div class="skill">GitHub</div>

        </div>

    </div>

    <!-- GitHub Stats -->
    <div class="github">

        <h2>GitHub Stats</h2>

        <!-- Change username -->
        <img src="https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight">

        <img src="https://github-readme-streak-stats.herokuapp.com/?user=YOUR_USERNAME&theme=tokyonight">

    </div>

    <!-- Social Links -->
    <div class="social">

        <!-- Change Links -->
        <a href="#">GitHub</a>
        <a href="#">LinkedIn</a>
        <a href="#">Twitter</a>
        <a href="#">Portfolio</a>

    </div>

    <footer>
        Made with ❤️ by Your Name
    </footer>

</div>

<!-- Typing Script -->
<script>

var typed = new Typed('#element', {
    strings: [
        'Full Stack Developer',
        'Web3 Developer',
        'Open Source Contributor',
        'Blockchain Enthusiast'
    ],
    typeSpeed: 60,
    backSpeed: 40,
    loop:true
});

</script>

</body>
</html>