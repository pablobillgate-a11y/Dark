# Dark<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>My Professional Portfolio</title>

<style>
body{
    font-family: Arial, sans-serif;
    margin:0;
    background:#0f172a;
    color:white;
    text-align:center;
}

.container{
    padding:60px 20px;
}

h1{
    font-size:50px;
}

.highlight{
    color:#38bdf8;
}

.skills{
    display:flex;
    justify-content:center;
    flex-wrap:wrap;
    gap:15px;
    margin-top:40px;
}

.skill{
    background:#1e293b;
    padding:15px 25px;
    border-radius:12px;
}

button{
    margin-top:40px;
    padding:15px 30px;
    font-size:18px;
    border:none;
    border-radius:10px;
    background:#38bdf8;
    cursor:pointer;
}

button:hover{
    background:#0ea5e9;
}
</style>

</head>

<body>

<div class="container">
    <h1>Hi 👋 I'm <span class="highlight">Your Name</span></h1>
    <p>I build modern web experiences.</p>

    <h2>My Skills</h2>

    <div class="skills">
        <div class="skill">HTML</div>
        <div class="skill">CSS</div>
        <div class="skill">JavaScript</div>
        <div class="skill">Design</div>
    </div>

    <button onclick="alert('Contact coming soon!')">
        Contact Me
    </button>
</div>

</body>
</html>
