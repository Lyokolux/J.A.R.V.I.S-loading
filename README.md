J.A.R.V.I.S-loading
===================
<!DOCTYPE html>
<html>

<head>

  <meta charset="UTF-8">

  <title>J.A.R.V.I.S Loding</title>

    <link rel="stylesheet" href="css/style.css" media="screen" type="text/css" />
    <style>
             body {
                background-image: url(http://i.imgur.com/ct8IVXk.jpg);            
                background-size: 100%;
                background-origin: content;
                background-repeat: no-repeat;
             }
          </style>

</head>


<body>
<font face="After Disaster" size="+5" color="#35afc3"><center>J &nbsp;  . &nbsp;  A &nbsp;  . &nbsp;  R &nbsp;  . &nbsp;  V &nbsp;  . &nbsp;  I &nbsp;  . &nbsp;  S</center>
<center>loading </center></font>
  <div class="cf-loader">
  
	<div class="loading-spinner"></div>
	<div class="go-rounder"></div>
	<div class="go-rounder another"></div>
	<div class="loader-text">
	
	</div>
</div>

  

</body>

</html>

 /*----------------------------------
 *
 * 	Loding Style with CSS3 animation transform (cross browser) 
 * 
 * 
 *----------------------------------*/

.cf-loader {
	position: fixed;
	margin: 0 auto;
	top: 78.5%;
	left: 45.8%;
}

.loading-spinner {
	position: absolute;
	top: 0;
	width: 80px;
	height: 80px;
	border-radius: 50%;
	border: 15px solid #d1fdf1;
	 -webkit-animation: rotation 3s infinite linear;
	  -moz-animation: rotation 3s infinite linear;
	   -o-animation: rotation 3s infinite linear;
	animation: rotation 3s infinite linear;
	 -webkit-animation: rotation 3s infinite linear;
	  -moz-animation: rotation 3s infinite linear;
	   -o-animation: rotation 3s infinite linear;
}

.loading-spinner:before {
	content: " ";
	display: block;
	position: absolute;
	left: -15px;
	top: -15px;
	height: 100%;
	width: 100%;
	border-top: 15px solid #35afc3;
	opacity: 0.8;
	border-left: 15px solid transparent;
	border-bottom: 15px solid transparent;
	border-right: 15px solid transparent;
	border-radius: 100%;
}

@-webkit-keyframes rotation {
	from {-webkit-transform: rotate(0deg);}
	to {-webkit-transform: rotate(359deg);}
}
@-moz-keyframes rotation {
	from {-moz-transform: rotate(0deg);}
	to {-moz-transform: rotate(359deg);}
}
@-o-keyframes rotation {
	from {-o-transform: rotate(0deg);}
	to {-o-transform: rotate(359deg);}
}
@keyframes rotation {
	from {transform: rotate(0deg);}
	to {transform: rotate(359deg);}
}

.go-rounder {
	position: absolute;
	top: -15px;
	left: -15px;
	width: 70px;
	height: 70px;
	border: 20px solid;
	border-radius: 100%;
	border-top-color: #35afc3 ;
	border-left-color: #7ffad8;
	border-bottom-color: #35afc3 ;
	border-right-color: #7ffad8;
	opacity: 0.2;
	animation: goor 5s infinite;
	 -webkit-animation: goor 5s infinite;
	  -moz-animation: goor 5s infinite;
	   -o-animation: goor 5s infinite;
}

@keyframes goor {
	0% {transform: scale(1,1) rotate(0deg); opacity: 0.2;}
	50% {transform: scale(4,4) rotate(360deg); opacity: 0;}
}
@-webkit-keyframes goor {
	0% {-webkit-transform: scale(1,1) rotate(0deg); opacity: 0.2;}
	50% {-webkit-transform: scale(4,4) rotate(360deg); opacity: 0;}
}
@-moz-keyframes goor {
	0% {-moz-transform: scale(1,1) rotate(0deg); opacity: 0.2;}
	50% {-moz-transform: scale(4,4) rotate(360deg); opacity: 0;}
}
@-o-keyframes goor {
	0% {-o-transform: scale(1,1) rotate(0deg); opacity: 0.2;}
	50% {-o-transform: scale(4,4) rotate(360deg); opacity: 0;}
}

.another {
	opacity: 0.1;
	transform: rotate(90deg);
	 -webkit-transform: rotate(90deg);
	  -moz-transform: rotate(90deg);
	   -o-transform: rotate(90deg);
	
	animation: gooraty 5s infinite;
	 -webkit-animation: gooraty 5s infinite;
	  -moz-animation: gooraty 5s infinite;
	   -o-animation: gooraty 5s infinite;
	animation-delay: 1s;
	 -webkit-animation-delay: 1s;
	  -moz-animation-delay: 1s;
	   -o-animation-delay: 1s;
}

@keyframes gooraty {
	0% {transform: scale(1,1) rotate(90deg); opacity: 0.1;}
	50% {transform: scale(4,4) rotate(-360deg); opacity: 0;}
}
@-webkit-keyframes gooraty {
	0% {-webkit-transform: scale(1,1) rotate(90deg); opacity: 0.1;}
	50% {-webkit-transform: scale(4,4) rotate(-360deg); opacity: 0;}
}
@-moz-keyframes gooraty {
	0% {-moz-transform: scale(1,1) rotate(90deg); opacity: 0.1;}
	50% {-moz-transform: scale(4,4) rotate(-360deg); opacity: 0;}
}
@-o-keyframes gooraty {
	0% {-o-transform: scale(1,1) rotate(90deg); opacity: 0.1;}
	50% {-o-transform: scale(4,4) rotate(-360deg); opacity: 0;}
}

.loader-text {
	position: absolute;
	top: 95px;
	left: -38px;
	font-family: Arial;
	color: #999999;
	text-transform: lowercase;
	letter-spacing: 3px;
	min-width: 160px;
	text-align: center;
	
	 -webkit-animation: opaa 5s infinite; /* Chrome, Safari 5+ */
     -moz-animation: opaa 5s infinite; /* Firefox 5-15 */
       -o-animation: opaa 5s infinite; /* Opera 12.00 */
          animation: opaa 5s infinite; /* Chrome, Firefox 16+, IE 10+, Opera 12.10+ */
}

@-webkit-keyframes opaa {
	0% {opacity: 1;}
	10% {opacity: 0.5}
	15% {opacity: 1;}
	30% {opacity: 1;}
	65% {opacity: 0.3;}
	90% {opacity: 0.8;}
}

@-moz-keyframes opaa {
	0% {opacity: 1;}
	10% {opacity: 0.5}
	15% {opacity: 1;}
	30% {opacity: 1;}
	65% {opacity: 0.3;}
	90% {opacity: 0.8;}
}

@-o-keyframes opaa {
	0% {opacity: 1;}
	10% {opacity: 0.5}
	15% {opacity: 1;}
	30% {opacity: 1;}
	65% {opacity: 0.3;}
	90% {opacity: 0.8;}
}

@keyframes opaa {
	0% {opacity: 1;}
	10% {opacity: 0.5}
	15% {opacity: 1;}
	30% {opacity: 1;}
	65% {opacity: 0.3;}
	90% {opacity: 0.8;}
}
