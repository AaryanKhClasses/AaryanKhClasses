<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
            background-color: #1A1B27;
            text-align: center;
            color: #fff;
            font-family: 'Quicksand', sans-serif
        }
        hr { opacity: 0.2; }
        .text { font-size: 20px; }
        .stat { margin-bottom: 10px; }
        .avatar {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin: 0 auto;
            margin-top: 50px;
        }
        .name {
            font-size: 30px;
            margin-top: 20px;
        }
        .nick {
            font-size: 20px !important;
            margin-top: 10px;
        }
        .about {
            margin-top: 20px;
            margin-bottom: 20px;
        }
        .tooltip {
            position: relative;
            display: inline-block;
        }
        .tooltip .tooltiptext {
            visibility: hidden;
            width: auto;
            background-color: #555;
            color: #fff;
            text-align: center;
            border-radius: 6px;
            padding: 5px;
            position: absolute;
            z-index: 1;
            bottom: 110%;
            left: 50%;
            margin-left: -60px;
            opacity: 0;
            transition: opacity 0.3s;
        }
        .tooltip .tooltiptext::after {
            content: "";
            position: absolute;
            top: 100%;
            left: 50%;
            margin-left: -5px;
            border-width: 5px;
            border-style: solid;
            border-color: #555 transparent transparent transparent;
        }
        .tooltip:hover .tooltiptext {
            visibility: visible;
            opacity: 1;
        }
        .card-container {
            display: flex;
            flex-wrap: wrap;
            justify-content: center;
            margin-top: 50px;
        }
        .card {
            width: 300px;
            height: 300px;
            background-color: #2A2B37;
            border-radius: 10px;
            margin: 10px;
            padding: 20px;
            box-sizing: border-box;
            display: flex;
            flex-direction: column;
            justify-content: space-between;
        }
        .card:hover {
            transform: scale(1.05);
            transition: 0.3s;
        }
        .card .head {
            font-size: 20px;
            margin-bottom: 10px;
        }
        .card .desc {
            font-size: 15px;
        }
        .card .foot {
            font-size: 15px;
            margin-top: 10px;
        }
        .btn{
            background-color: #2A2B37;
            border: 1px solid #fff;
            color: #fff;
            padding: 10px 20px;
            border-radius: 5px;
            text-decoration: none;
            margin-top: 20px;
            margin-bottom: 20px;
            cursor: pointer;
        }
        .btn:hover {
            background-color: #fff;
            color: #2A2B37;
            transition: 0.3s;
        }
        .tdot {
            height: 10px;
            width: 10px;
            background-color: #3178C6;
            border-radius: 50%;
            display: inline-block;
        }
        .ts { color: #3178C6; }
        .jdot {
            height: 10px;
            width: 10px;
            background-color: #F1E05A;
            border-radius: 50%;
            display: inline-block;
        }
        .js { color: #F1E05A; }
    </style>
</head>
<body>
    <div class="avatarDiv">
        <img class="avatar" src="https://avatars.githubusercontent.com/u/66236478?v=4">
        <p class="name"><b>AaryanKhClasses</b> <span class="nick">(AaryanKh)</span></p>
    </div>
    <hr>
    <div class="about">
        <p class="text">Hello and Welcome to my GitHub Profile!<br>
            I'm AaryanKh, a 15 year old Programmer and Application Developer.<br>
            I have 2 years of experience in programming Web and Desktop Applications.<br>
            My main languages are Javascript/Typescript, Python and C#.
        </p>
    </div>
    <hr>
    <div class="projects">
        <p class="text">Here are some of my Projects:</p>
        <div class="card-container">
            <div class="card">
                <div class="card-head">Sayout-Clone</div>
                <div class="card-desc">A "prototype clone" of the popular anonymous messaging service, Sayout.me</div>
                <div class="card-foot"><span class="tdot"></span><span class="ts"><b>Typescript</b></span><br><a class="link" href="https://github.com/AaryanKhClasses/Sayout-Clone"><button class="btn">Check Out!</button></a></div>
            </div>
            <div class="card">
                <div class="card-head">DatabaseApp</div>
                <div class="card-desc">A Local JSON-Based Database Application.</div>
                <div class="card-foot"><span class="tdot"></span><span class="ts"><b>Typescript</b></span><br><a class="link" href="https://github.com/AaryanKhClasses/DatabaseApp"><button class="btn">Check Out!</button></a></div>
            </div>
            <div class="card">
                <div class="card-head">Scrap Miner</div>
                <div class="card-desc">An Economy-Based RPG Discord Bot.</div>
                <div class="card-foot"><span class="jdot"></span><span class="js"><b>Javascript</b></span><br><a class="link" href="https://github.com/AaryanKhClasses/Scrap-Miner"><button class="btn">Check Out!</button></a></div>
            </div>
        </div>
    </div>
    <hr>
    <div class="stats">
        <p class="text">Here are my GitHub Stats:</p>
        <div class="tooltip stat">
            <img src="https://github-readme-stats.vercel.app/api?username=AaryanKhClasses&theme=tokyonight&show_icons=true">
            <span class="tooltiptext">My GitHub Statistics</span>
        </div><br>
        <div class="tooltip stat">
            <img src="https://github-profile-trophy.vercel.app/?username=AaryanKhClasses&theme=onedark&column=4">
            <span class="tooltiptext">My GitHub Trophies</span>
        </div><br>
        <div class="tooltip stat">
            <img src="https://github-readme-streak-stats.herokuapp.com/?user=AaryanKhClasses&theme=slateorange">
            <span class="tooltiptext">My GitHub Contributions</span>
        </div><br>
        <div class="tooltip stat">
            <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=AaryanKhClasses&langs_count=10&theme=tokyonight&layout=compact">
            <span class="tooltiptext">My Most Used Languages</span>
        </div><br>
    </div>
    <hr>
</body>
</html>
