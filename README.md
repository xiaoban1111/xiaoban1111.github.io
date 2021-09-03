# xiaoban1111.github.io
欢迎来到小班的专属空间
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>family</title>
    <link rel="icon" href="./06_family/family.ico">
    <style>
        html {
            perspective: 2000px;
            height: 100%;
            width: 100%;
            background-image: url("./06_family/bg.gif");
        }

        body {
            height: 100%;
            width: 100%;
        }

        audio {
            display: none;
        }

        .cube2:hover .box7 {
            transform: rotateY(90deg) translateZ(400px);
        }

        .cube2:hover .box8 {
            transform: rotateY(-90deg) translateZ(400px);
        }

        .cube2:hover .box9 {
            transform: rotateX(90deg) translateZ(400px);
        }

        .cube2:hover .box10 {
            transform: rotateX(-90deg) translateZ(400px);
        }

        .cube2:hover .box11 {
            transform: rotateY(180deg) translateZ(400px);
        }

        .cube2:hover .box12 {
            transform: translateZ(400px);
        }

        .wrapper {
            height: 100%;
            width: 100%;
            transform-style: preserve-3d;
            float: left;
            animation: rotate 9.9s linear infinite;
        }

        html:hover .cube {
            transform: inherit;
        }

        .cube {
            width: 200px;
            height: 200px;
            position: absolute;
            top: 0;
            bottom: 0;
            left: 0;
            right: 0;
            margin: auto;
            transform-style: preserve-3d;
            transition: all 3.5s;
        }

        .wrapper .cube div {
            width: 200px;
            height: 200px;
            opacity: 0.8;
            position: absolute;
        }

        .cube2 {
            width: 250px;
            height: 250px;
            position: absolute;
            top: 0;
            bottom: 0;
            left: 0;
            right: 0;
            margin: auto;
            transform-style: preserve-3d;
        }

        .cube2 div {
            width: 250px;
            height: 250px;
            opacity: 0.6;
            position: absolute;
        }

        img {
            vertical-align: top;
        }

        .box1 {
            transform: rotateY(90deg) translateZ(100px);
        }

        .box2 {
            transform: rotateY(-90deg) translateZ(100px);
        }

        .box3 {
            transform: rotateX(90deg) translateZ(100px);
        }

        .box4 {
            transform: rotateX(-90deg) translateZ(100px);
        }

        .box5 {
            transform: rotateY(180deg) translateZ(100px);
        }

        .box6 {
            transform: translateZ(100px);
        }

        .box7 {
            transform: rotateY(90deg) translateZ(125px);
            transition: all 3.5s;
        }

        .box8 {
            transform: rotateY(-90deg) translateZ(125px);
            transition: all 3.5s;
        }

        .box9 {
            transform: rotateX(90deg) translateZ(125px);
            transition: all 3.5s;
        }

        .box10 {
            transform: rotateX(-90deg) translateZ(125px);
            transition: all 3.5s;
        }

        .box11 {
            transform: rotateY(180deg) translateZ(125px);
            transition: all 3.5s;
        }

        .box12 {
            transform: translateZ(125px);
            transition: all 3.5s;
        }

        @keyframes rotate {
            from {
                transform: rotateX(0) rotateZ(0);
            }

            to {
                transform: rotateX(1turn) rotateZ(1turn);
            }
        }
    </style>
</head>

<body>
    <audio src="./06_family/星空.mp3" autoplay="autoplay" controls="controls" loop="loop">
    </audio>
    <div class="wrapper">
        <div class="cube">
            <div class="box1">
                <img src="./06_family/6.jpg">
            </div>

            <div class="box2">
                <img src="./06_family/5.jpg">
            </div>

            <div class="box3">
                <img src="./06_family/4.jpg">
            </div>

            <div class="box4">
                <img src="./06_family/3.jpg">
            </div>

            <div class="box5">
                <img src="./06_family/2.jpg">
            </div>

            <div class="box6">
                <img src="./06_family/1.jpg">
            </div>
        </div>

        <div class="cube2">
            <div class="box7">
                <img src="./06_family/12.jpg">
            </div>

            <div class="box8">
                <img src="./06_family/11.jpg">
            </div>

            <div class="box9">
                <img src="./06_family/10.jpg">
            </div>

            <div class="box10">
                <img src="./06_family/9.jpg">
            </div>

            <div class="box11">
                <img src="./06_family/8.jpg">
            </div>

            <div class="box12">
                <img src="./06_family/7.jpg">
            </div>
        </div>
    </div>
</body>
</html>
