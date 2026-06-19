<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>About Me - Atueyi Zel</title>

<style>
*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family: Arial, sans-serif;
    background-image: linear-gradient(rgba(0,0,0,0.4),
    rgba(0,0,0,0.4)),
    url('https://images.unsplash.com/photo-1576091160399-112ba8d25d1f');
    background-size: cover;
    background-position: center;
    min-height: 100vh;

    display:flex;
    justify-content:center;
    align-items:center;
    padding:20px;
}

.container{
    width:90%;
    max-width:1000px;
    background:white;
    border:3px solid #00509e;
    border-radius:15px;
    padding:30px;
    box-shadow:0 8px 20px rgba(0,0,0,0.3);
}

h1{
    text-align:center;
    color:#003366;
    margin-bottom:20px;
}

.content{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:20px;
}

.section{
    background:#f4f7fc;
    padding:20px;
    border-radius:10px;
    border:1px solid #d9e6f2;
    box-shadow:0 4px 8px rgba(0,0,0,0.1);
}

h2{
    color:#00509e;
    margin-bottom:10px;
    border-bottom:2px solid #00509e;
    padding-bottom:5px;
}

p, li{
    font-size:16px;
    line-height:1.7;
    color:#333;
}

ul{
    padding-left:20px;
}

.footer{
    margin-top:25px;
    display:flex;
    justify-content:center;
    align-items:center;
    color:#666;
    font-weight:bold;
}

@media (max-width:768px){
    .content{
        grid-template-columns:1fr;
    }
}
</style>
</head>

<body>

<div class="container">

    <h1>About Me</h1>

    <div class="content">

        <div class="section">
            <h2>Personal Information</h2>
            <p>
                My name is <strong>Atueyi Zel</strong>. I am a 300-level
                medical student at <strong>Madonna University, Elele</strong>.
                I am passionate about learning, personal development,
                and making a positive impact in society through medicine.
            </p>
        </div>

        <div class="section">
            <h2>My Interests</h2>
            <ul>
                <li>Medicine and Healthcare</li>
                <li>Human Anatomy and Physiology</li>
                <li>Medical Research</li>
                <li>Leadership and Community Service</li>
                <li>Reading and Continuous Learning</li>
            </ul>
        </div>

        <div class="section">
            <h2>My Goals</h2>
            <ul>
                <li>Successfully complete my medical education.</li>
                <li>Become a skilled and compassionate doctor.</li>
                <li>Improve healthcare in my community.</li>
                <li>Contribute to medical research.</li>
                <li>Develop strong leadership skills.</li>
            </ul>
        </div>

        <div class="section">
            <h2>Skills</h2>
            <ul>
                <li>Communication Skills</li>
                <li>Teamwork</li>
                <li>Critical Thinking</li>
                <li>Problem Solving</li>
                <li>Computer Literacy</li>
            </ul>
        </div>

    </div>

    <div class="footer">
        © 2026 Atueyi Zel | Medical Student
    </div>

</div>

</body>
</html>