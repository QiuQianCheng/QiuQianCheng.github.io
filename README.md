# 新年快乐蕊蕊子
<html>
<head lang="en">
    <meta charset="UTF-8">
    <title>新年快乐蕊蕊子</title>
    <style type="text/css">
        *{padding: 0;
        margin: 0;}
        body,html{height:100%;}
    
        body{background-image: url("images/beijing.jpg");background-size: 100% 100%;}
        #box{width: 400px;
            height: 400px;
            position: fixed;
            left: 0;
            right: 0;
            top:0;
            bottom: 0;
            margin: auto;
            transform-style: preserve-3d;
            transform: rotateX(0deg) rotateY(0deg);
            animation: go 45s linear infinite;
           }
        #box img{width: 260px;
                 height: 560px;
                 position: absolute;
                 left: 0;
                 top: 0;
        }
        #box:hover{
            animation-play-state: paused;}
        #box img:nth-child(1):hover{transform: scale(2,2);}
        #box img:nth-child(2):hover{ transform: scale(2,2);}
        #box img:nth-child(3):hover{ transform: scale(2,2);}
        #box img:nth-child(4):hover{ transform: scale(2,2);}
        #box img:nth-child(5):hover{ transform: scale(2,2);}
        #box img:nth-child(6):hover{ transform: scale(2,2);}
        #box img:nth-child(7):hover{ transform: scale(2,2);}
        #box img:nth-child(8):hover{ transform: scale(2,2);}
        #box img:nth-child(9):hover{ transform: scale(2,2);}
        #box img:nth-child(10):hover{ transform: scale(2,2);}
        #box img:nth-child(1){
            transform: rotateY(0deg) translateZ(650px);}
        #box img:nth-child(2){
            transform: rotateY(36deg) translateZ(650px);}
        #box img:nth-child(3){
            transform: rotateY(72deg) translateZ(650px);}
        #box img:nth-child(4){
            transform: rotateY(108deg) translateZ(650px);}
        #box img:nth-child(5){
            transform: rotateY(144deg) translateZ(650px);}
        #box img:nth-child(6){
            transform: rotateY(180deg) translateZ(650px);}
        #box img:nth-child(7){
            transform: rotateY(216deg) translateZ(650px);}
        #box img:nth-child(8){
            transform: rotateY(252deg) translateZ(650px);}
        #box img:nth-child(9){
            transform: rotateY(288deg) translateZ(650px);}
        #box img:nth-child(10){
            transform: rotateY(324deg) translateZ(650px);}
		@keyframes go {
		    0%{transform: rotateX(0deg) rotateY(0deg);}
		    25%{transform: rotateX(20deg) rotateY(180deg);}
		    50%{transform: rotateX(0deg) rotateY(360deg);}
		    75%{transform: rotateX(-20deg) rotateY(540deg);}
		    100%{transform: rotateX(0deg) rotateY(720deg);}
		}
    </style>
</head>
	<body>
		<div id="box">
		    <img src="images/1.jpg">
		    <img src="images/2.jpg">
		    <img src="images/3.jpg">
		    <img src="images/4.jpg">
		    <img src="images/5.jpg">
		    <img src="images/6.jpg">
		    <img src="images/7.jpg">
		    <img src="images/8.jpg">
		    <img src="images/9.jpg">
		    <img src="images/10.jpg">
		</div>
    <audio controls>
          <source src="music/123.ogg" type="audio/ogg">
          <source src="music/123.mp3" type="audio/mpeg">
    </audio>
	</body>
</html>
