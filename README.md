/* LESS Document */

/* Summary 
   0. General
	   Fonts 
	   Colors 
	   Containers & Sections 
	   Boutons 
   I. Navbar 
   II. Slider
   III. Icones
   IV. Les Offres OtheatrO
   V. Comment
   VI. Spectacles
   VII. Newsletter
   IX. Footer */

/* 0. General */

/* Fonts */
@font-face { font-family: AvantGarde; src: url('../fonts/ITCAvantGardeStd-Md.otf'); } 
@font-face { font-family: AvantGarde; font-weight: 300; src: url('../fonts/ITCAvantGardeStd-Bk.otf');}
@font-face { font-family: AvantGarde; font-weight: 800; src: url('../fonts/ITCAvantGardeStd-Bold.otf');}
@font-face { font-family: Demi; src: url('../fonts/ITCAvantGardeStd-Demi.otf'); }


h1, h2, h3, h4, .itc, a {font-family: AvantGarde, sans-serif;}

.itc-bk {
	font-family: AvantGarde, sans-serif;
	font-weight: 300;
}

.itc-bold {
	font-family: AvantGarde, sans-serif;
	font-weight: 800;
}

.demi {font-family: Demi, sans-serif;}

h1 {font-size: 40px;}
h2 {font-size: 35px;}
h3 {font-size: 15px;}
h4 {font-size: 14px;	}

h3, h4 {text-transform: uppercase;}

.sous-titre {
	font-size:16px;	
}

p {
	font-size: 14px;	
	font-weight: 300;
}

.text-justify {
  text-align: justify;
}

.mt-5 {margin-top:5px;}
.mt-10 {margin-top:10px;}
.mt-20 {margin-top:20px;}
.mt-30 {margin-top:30px;}
.mt-40 {margin-top:40px;}
.mt-50 {margin-top:50px;}
.mt-70 {margin-top:70px;}
.mb-0 {margin-bottom: 0px;}
.mb-5 {margin-bottom: 5px;}
.mb-10 {margin-bottom: 10px;	}
.mb-20 {margin-bottom: 20px;	}
.mb-30 {margin-bottom: 30px;	}
.mb-40 {margin-bottom: 40px;	}
.mb-50 {margin-bottom: 50px;	}
.pl-0{padding-left: 0px;}
.pl-20{padding-left: 20px;}
.pl-30{padding-left: 30px;}
.pl-40{padding-left: 40px;}
.pr-10{padding-right: 10px;}
.pr-20{padding-right: 20px;}
.pr-40{padding-right: 40px;}
.pt-20{padding-top: 20px;}
.pt-30{padding-top: 30px;}
.pt-40{padding-top: 40px;}
.pt-50{padding-top: 50px;}
.pb-30{padding-bottom: 30px;}
.pb-40{padding-bottom: 40px;}
.pb-50{padding-bottom: 50px;}

/* Colors */

@accent: #34d0d3;
@backgray:#ebeae9;
@backlightgray:#f7f7f7;
@blue : #5387b3;
@bordeaux: #d95c5b;
@dark : #181818;
@darkblue : #3b3d63;
@darkgray: #616161;
@gold: #efc762;
@green : #89c5c2;
@lightgray: #ececec;
@lightpurple : #b1a5cc;
@purple : #6e61a0;
@red : #f04f52;
@salmon : #ecb192;

.accent {color: @accent;	}
.bordeaux{color: @bordeaux;}
.blue{color: @blue;}
.purple {color: @purple;}
.white { color: #fff; }
.gold {color: @gold;}
.gray {color: #b1b1b1;}
.green{color: @green;}
.red { color: @red; }
.salmon { color: @salmon;}

.bc-accent { background-color: #73b9b6;}
.bc-bordeaux { background-color: @bordeaux;}
.bc-dark { background-color: @dark;}
.bc-darkblue { background-color: @darkblue;}
.bc-gold { background-color: #ecad4b;}
.bc-gray { background-color: @backgray;}
.bc-lightpurple { background-color: @lightpurple;}
.bc-darkpurple { background-color: #70618a;}
.bc-red { background-color: @red;}
.bc-salmon { background-color: #e79c77;}
.bc-white { background-color: #fff;}

/* Containers & Sections */

/* .container-fluid {
	padding: 0;	
} */

.section {
	margin-top: 40px;	
}

.section-title h2 {
	font-size: 40px;
	margin-top: 30px;
	margin-bottom: 25px;
}

.section-content {
	padding-top: 30px;	
}

.section-gray {
	background-color: @backlightgray;	
}

.section-red {
	background-color: @red;	
}

/* Boutons */

.btn-decouverte {
	.white;
	text-transform: uppercase;
	height: 80px;
	width: 290px;
	margin-top: 60px;
	margin-bottom: 60px;
	padding: 30px 20px;
	background :url('../assets/images/btn-decouverte-fond.png');	
}

.btn-decouverte:hover{
	color: @accent;	
	background :url('../assets/images/btn-decouverte-fond-hover.png');
}

.btn-spectacle {
	.white;
	text-transform: uppercase;
	font-size: 13px;
	height: 80px;
	width: 290px;
	margin-top: 60px;
	margin-bottom: 60px;
	padding: 30px 20px;
	background :url('../assets/images/btn-decouverte-fond.png');	
}

.btn-spectacle:hover{
	color: @accent;	
	background :url('../assets/images/btn-decouverte-fond-hover.png');
}

.btn-temoignage {
	.white;
	text-transform: uppercase;
	font-size: 13px;
	height: 62px;
	width: 308px;
	margin-top: 60px;
	margin-bottom: 60px;
	padding: 20px 20px;
	background :url('../assets/images/btn-temoignage-fond.png');	
}

.btn-temoignage:hover{
	color: @accent;	
	background :url('../assets/images/btn-temoignage-fond-hover.png');
}

.btn-slider {
	.white;
	text-transform: uppercase;
	font-size: 13px;
	height: 62px;
	width: 157px;
	padding: 20px 15px;
	background :url('../assets/images/btn-slider-fond.png');	
}

.btn-slider:hover{
	color: @accent;	
	background :url('../assets/images/btn-slider-fond-hover.png');
}

.btn-achat {
	.white;
	text-transform: uppercase;
	font-size: 20px;
	height: 80px;
	width: 290px;
	padding: 25px 20px;
	background :url('../assets/images/btn-decouverte-fond.png');	
	margin-top: -30px;
}

.btn-achat:hover{
	color: @accent;	
	background :url('../assets/images/btn-decouverte-fond-hover.png');
}

.btn-cadeau {
	.white;
	text-transform: uppercase;
	font-size: 15px;
	height: 58px;
	width: 294px;
	padding: 20px 20px;
	background :url('../assets/images/btn-cadeau.png');	
	margin-top: -30px;
}

.btn-cadeau:hover{
	color: @red;	
	background :url('../assets/images/btn-cadeau-hover.png');
}

.btn-acheter {
	.white;
	text-transform: uppercase;
	height: 80px;
	width: 150px;
	margin-top: -35px;
	margin-left: -30px;
	padding: 30px 20px;
	background :url('../assets/images/btn-acheter.png');	
}

.btn-acheter:hover{
	color: @accent;	
	background :url('../assets/images/btn-acheter-hover.png');
}

.btn-acheter-gold {
	.white;
	text-transform: uppercase;
	height: 80px;
	width: 150px;
	margin-top: -35px;
	padding: 30px 20px;
	background :url('../assets/images/btn-acheter-gold.png');	
}

.btn-acheter-gold:hover{
	color: @accent;	
	background :url('../assets/images/btn-acheter-gold-hover.png');
}


.btn-offrir {
	color: @accent;	
	text-transform: uppercase;
	height: 80px;
	width: 150px;
	margin-top: -35px;
	margin-left: -44px;
	padding: 30px 20px;
	background :url('../assets/images/btn-offrir.png');	
}

.btn-offrir:hover{
	color: #fff;	
	background :url('../assets/images/btn-offrir-hover.png');
}

.btn-acheter-2 {
	.white;
	text-transform: uppercase;
	height: 80px;
	width: 150px;
	margin-top: -35px;
	padding: 30px 20px;
	background :url('../assets/images/btn-acheter-2.png');	
}

.btn-acheter-2:hover{
	color: @accent;	
	background :url('../assets/images/btn-acheter-2-hover.png');
}

.btn-offrir-2 {
	color: @accent;	
	text-transform: uppercase;
	height: 80px;
	width: 150px;
	margin-top: -35px;
	margin-left: -62px;
	padding: 30px 20px;
	background :url('../assets/images/btn-offrir-2.png');	
}

.btn-offrir-2:hover{
	color: #fff;	
	background :url('../assets/images/btn-offrir-2-hover.png');
}

.btn-filtre {
	.white;
	text-transform: uppercase;
	font-size: 14px;
	height: 62px;
	width: 157px;
	padding: 20px 10px;
	background :url('../assets/images/btn-filtre.png');	
}

.btn-filtre:hover{
	color: @red;	
	background :url('../assets/images/btn-filtre-hover.png');
}

.btn-savoir-plus {
	.white;
	text-transform: uppercase;
	height: 78px;
	width: 191px;
	padding: 30px 10px;
	background :url('../assets/images/btn-savoir-plus.png');	
	margin-top: 0px;
	margin-bottom: 0px;
	display: block;
	position: absolute;
	bottom: -5%;
	left:50%;	
	transform: translateX(-50%);
}

.btn-savoir-plus:hover{
	color: @accent;	
	background :url('../assets/images/btn-savoir-plus-hover.png');
}

/* I. Header */

.navbar-default {
    background-color: #fff;
    border-color: #fff;
	margin-bottom: 0px;
}

.navbar .container-fluid {
	padding: 0 0px;	
}

.navbar-header {
	width: 100%;	
	border-bottom: 1px solid @lightgray;
}

.logo-container {
	padding-left: 50px;	
}

.navbar-toggle {
	border: 0px solid #FFF;	
	margin-top: 20px;
	border-radius: 0px;
}

.navbar-toggle:hover {
	border: 0px solid #FFF;	
	background-color: @accent !important;
}

.navbar-toggle .icon-bar {
	background-color: #1e1f1f !important;
	height: 3px !important;
	width: 30px !important;
}

.navbar-toggle:hover .icon-bar {
	background-color: #fff !important;
}

.navbar-nav > li > a {
    padding-bottom: 0px;
}

/* Phones (up to 768px) */
@media (max-width: 767px) { 

#navbar-otheatro {
	position: absolute;
	top : 0px;
	left:0px;
	width: 104%;	
	z-index:100;
	background-color: #fff;
	-webkit-box-shadow: 5px 0px 5px 0px rgba(0,0,0,0.1);
	-moz-box-shadow: 5px 0px 5px 0px rgba(0,0,0,0.1);
	box-shadow: 5px 0px 5px 0px rgba(0,0,0,0.1);
	margin-right: 0px;
	padding-left: 10px;
}

#navbar-otheatro .nav-menu{
	text-align: center;
}

#logo-item {
	position: absolute;
	top: 0px;
	left: 10px;	
}

#logo-item img{
	width: 150px;
	height: auto;	
}

#close-btn {
	position: absolute;
	top: 10px;
	right: 10px;	
	z-index:1000;	
}

#close-btn img{
	height: 20px;
	width: auto;	
}

.mobile-separator {
	width: 50px;
	margin-top: 0px;
	margin-bottom: 0px;
	border-color: #a9a9a9;	
}

#navbar-otheatro .menu-item {
	margin-top: 0px;	
}

.social-btn {
	float: left;	
}

.social-btn {
	width: 50%;	
}

#navbar-otheatro .nav-menu {
	padding-top: 50px;	
}

.city-selector {
	pointer:selector;
	margin-bottom: 10px;	
	font-size: 18px;
}

.city-selector .active{
	.demi;
	color: @red;
}

}

/* Small devices to large (tablets, 768px and up) */
@media (min-width: 768px) { 
.nav-menu {
	padding-left: 20px;
	height: 55px;
	margin-top: -10px;
	z-index:10;
}

#navbar-otheatro .menu-item a {
	text-transform: uppercase;	
}

.social-container {
	padding-top: 3px;
	padding-right: 20px;	
}

.city-selector {
	pointer:selector;
	font-size: 18px;
	position: absolute;
	top:25px;
	left: 250px;
}

.city-selector .active{
	.demi;
	color: @red;
}

}

.navbar-brand {	
	padding: 15px 10px;
	height: auto;
}

.navbar-brand img {
	width: 180px;
	height: auto;	
}

.account-container .account {
	text-align: right;
	color: #585959;
}

.account-container .account a{
	color: #585959;
}

.account-container .account a:hover{
	color: @accent;
	text-decoration: none;
}

.account-container .account a img{
	margin-top: -3px;
}

.info-container {
	padding: 5px 40px 0px 0px;	
	width: 50%;
}

.search-container {
	margin-top: -10px;
}

.search-container, .search-container .navbar-form {
	width: 100%;
}

.search-container .navbar-form {
	padding-right: 0px;	
	text-align: right;
}

.search-container .navbar-form .form-group{
	width: 300px;
}

.search-container .navbar-form .form-group input{
	width: 100%;	
	border-radius: 0px;
	.itc-bk;
	margin-top: 4px;
	padding-top: 8px;
	height: 40px;
}

.navbar-form .btn{
	color: @red;
	border:0px solid @red;
	background :url('../assets/images/btn-recherche-fond.png');	
	width: 57px;
	height: 62px;
	margin-left: -10px;
}

#home-item a {
	padding: 0;
	margin-top: -15px;	
}

.menu-item {
	font-family: AvantGarde, sans-serif;
	font-weight: 300;
	margin-top: 10px;
}

.navbar-default .navbar-nav > .active > a, .navbar-default .navbar-nav > .active > a:hover, .navbar-default .navbar-nav > .active > a:focus {
	background-color: #fff;
	color: @red;
	.demi;
}

.navbar .social-btn a{
	padding: 5px 5px !important;	
}

#navbar-otheatro {
background-color: #FFF;	
		border-bottom: 1px solid @lightgray;
	-webkit-box-shadow: 0px 8px 10px 0px rgba(0,0,0,0.03);
	-moz-box-shadow: 0px 8px 10px 0px rgba(0,0,0,0.03);
	box-shadow: 0px 8px 10px 0px rgba(0,0,0,0.03);
}
/* II. Slider */

.slider-container {
	z-index: 1;	
}

.carousel-inner .item img {
	margin: auto;
	width: 100%;	
	-webkit-transition: 1s ease-in-out left;
    -moz-transition: 1s ease-in-out left;
    -o-transition: 1s ease-in-out left;
    transition: 1s ease-in-out left;
}

#carousel-otheatro .btn-container {
    bottom: 2%;
    left: 10%;
    padding-left: 0;
    position: absolute;
    text-align: left;
    width: 30%;
    z-index: 15;
}



/* Phones (up to 768px) */
@media (max-width: 767px) { 

#carousel-otheatro .btn-container {
    bottom: -20%;
    left: 20%;
	height: 100px;
}

.btn-slider {
	.white;
	text-transform: uppercase;
	font-size: 13px;
	height: 40px;
	width: 105px;
	padding: 10px 5px;
	background :url('../assets/images/btn-slider-fond-phone.png');	
}


.btn-slider:hover{
	color: @accent;	
	background :url('../assets/images/btn-slider-fond-hover-phone.png');
}

}



/* Small devices to large (tablets, 768px and up) */
@media (min-width: 768px) { 

#carousel-otheatro .btn-container {
    bottom: 15%;
    left: 4%;
}

}

/* III. Icones  */

.icone-presentation {
	height: 50px;
	width: auto;	
}

/* IV. Les Offres OtheatrO */

.col-carte {
	position: relative;
	height: 536px;
	z-index: 10;	
}

.carte-focus {
	display: none;	
}

.col-carte:hover .carte-focus {
	display: inline;
}

.col-carte:hover .carte-initial {
	display: none;
}

.carte-fond {
	position: absolute;
	top:50%;
	transform:translateY(-50%);	
	z-index: 1;	
}

.carte-fond-left {
	right:0%;
}

.carte-fond-middle {
	left:50%;
	transform:translate(-50%,-50%);	
}

.carte-fond-right {
	left:0%;	
}

.carte-content {
	position: absolute;
	top:50%;
	transform:translateY(-50%);	
	z-index: 10;	
}

.carte-content-left {
	right:8%;
}

.carte-content-middle {
	left:50%;
	transform:translate(-50%,-50%);
}

.carte-content-right {
	left:2.5%;	
}

.prix {
	margin-top: 30px;
	width: 100%;	
}

.prix span {
	font-size: 36px;	
}

/* Phones (up to 768px) */
@media (max-width: 767px) { 

.carte-fond-left, .carte-fond-right {
	left:50%;
	transform:translate(-50%,-50%);	
}

.carte-content-left, .carte-content-right {
	left:50%;
	transform:translate(-50%,-50%);
}

.carte-illimite {
	margin-left: -30px;	
}

}

/* V. Comment */

.step {
	font-size: 19px;	
}

/* VI. Salles */

/* Phones up to 767px */
@media (max-width: 767px) { 
	.salle {
		text-align: center;	
		margin-bottom: 30px;
	}
}

/* Small devices to large (tablets, 768px and up) */
@media (min-width: 768px) { 
	.salle {
		text-align: left;	
	}
}

/* VI. Spectacles */

.spectacle-title img,  .spectacle-title h3{
	float: left;
	padding-left: 20px;
}

.col-spectacle-focus {
	background-color: #fff;	
	-webkit-box-shadow: 0px 0px 30px 0px rgba(0,0,0,0.26);
	-moz-box-shadow: 0px 0px 30px 0px rgba(0,0,0,0.26);
	box-shadow: 0px 0px 30px 0px rgba(0,0,0,0.26);
}

.col-spectacle .spectacle-title {
	margin-bottom: 20px;
}

.col-spectacle .break {
	clear: both;
}

.col-spectacle h4{
	margin-bottom: 5px;
}

.col-spectacle .ranking{
	margin-bottom: 5px;
}
.spectacle-img {
	height: 183px;
	width: auto;	
}

/* VII. Newsletter */
.section-arrow {
	position: relative;
	background: #f04f52;
	border: 4px solid #f04f52;
}
.section-arrow:after, .section-arrow:before {
	bottom: 100%;
	left: 50%;
	border: solid transparent;
	content: " ";
	height: 0;
	width: 0;
	position: absolute;
	pointer-events: none;
}

.section-arrow:after {
	border-color: rgba(240, 79, 82, 0);
	border-bottom-color: #f04f52;
	border-width: 30px;
	margin-left: -30px;
}

.section-arrow:before {
	border-color: rgba(240, 79, 82, 0);
	border-bottom-color: #f04f52;
	border-width: 36px;
	margin-left: -36px;
}

.newsletter-form .form-control{
	display: inline;
	width: 80%;
	float: left;
	border-radius: 0px;
	background-color: @red;
	border: 1px solid #fff;
	color: #fff;
	margin-top: 4px;
	height: 40px;
}

.newsletter-form .form-control::-moz-placeholder {
    color: #fff;
}

.newsletter-form .btn{
	display: inline;
	width: 10%;
	float: left;
	border-radius: 0px;
	color: @red;
	border:0px solid @red;
	background :url('../assets/images/btn-newsletter-fond.png');	
	width: 137px;
	height: 49px;
	margin-left: -3px;
}

/* Phones (up to 768px) */
@media (max-width: 767px) { 

.newsletter-form {
	margin: auto;
}

.newsletter-form .form-control{
	width: 65%;
}

}


/* IX. Footer */

#top-footer {
	background-color: #FFF;	
	padding-top: 20px;
	padding-bottom: 20px;
	border-top: 1px solid @lightgray;
	-webkit-box-shadow: 0px -8px 10px 0px rgba(0,0,0,0.03);
	-moz-box-shadow: 0px -8px 10px 0px rgba(0,0,0,0.03);
	box-shadow: 0px -8px 10px 0px rgba(0,0,0,0.03);
}

#top-footer a{
	color: #333333;
}

#top-footer .container {
	margin: auto;	
}

#logo-footer {
	width: 80px;
	height: auto;	
	margin-top: -40px;
	margin-left: -30px;
	margin-bottom: 10px;
}

.newsletter-footer-form .form-control{
	display: inline;
	width: 80%;
	float: left;
	border-radius: 0px;
	border: 1px solid @lightgray;
	margin-top: 13px;
	height: 40px;
}


.newsletter-footer-form .btn{
	display: inline;
	width: 10%;
	float: left;
	border-radius: 0px;
	border:0px solid @lightgray;
	background :url('../assets/images/btn-footer-fond.png');	
	width: 57px;
	height: 62px;
	margin-left: -5px;
}

#top-footer .break {
	clear: both;
}

#top-footer .social-container{
	padding-top: 0px;	
}

#top-footer .social-container .social-btn a {
	padding: 0px 5px;	
}

#top-footer .btn-vente {
	margin-top: 20px;
	background :url('../assets/images/btn-vente-fond.png');	
	width: 202px;
	height: 62px;
	padding-top: 22px;
}

.question-separator{
	width: 40%;	
	margin-left: 0px;
}

/* Phones (up to 768px) */
@media (max-width: 767px) { 
	#top-footer .btn-vente {
		margin: auto;
		display: block;
		margin-top: 20px;
	}
	
	#top-footer .social-btn-facebook {
		text-align: right;	
	}
	
}

#bottom-footer {
	background-color: @accent;	
	color: #FFF;
	padding: 20px 20px 10px 20px;
	margin-top: 0px;
}

#bottom-footer a{
	color: #FFF;
	padding-right: 40px;
}















/* Tunnel d'achat */

#product .section-content {
	padding-top: 70px;
}

.info-achat {
	margin-top: -5px;	
}

.achat-parcours, .achat-parcours-2 {
	padding-left: 0px;
	margin-bottom: 0px;
}

.achat-parcours li{
	font-size: 25px;
	line-height: 35px;
	padding:25px 30px 35px 30px;
	list-style-type: none;
	color: @darkgray;
	display: inline-block;
}

.achat-parcours-2 li{
	font-size: 25px;
	line-height: 35px;
	padding:25px 30px 35px 30px;
	list-style-type: none;
	color: @darkgray;
	display: inline-block;
}

.achat-parcours span, .achat-parcours-2 span {
    width: 35px;
    height: 35px;
	display: inline-block;
    font-size: 20px;
    text-align: center;
    color: @darkgray;
 	margin-right: 5px;
    border: 1px solid @darkgray;
    border-radius: 50%;
	line-height: 33px;
}

.achat-parcours li.active, .achat-parcours-2 li.active{
	color: #fff;
}

.achat-parcours .active span, .achat-parcours-2 .active span {
    color: #fff;
    border: 1px solid #fff;
}

#product-img {
	margin-top: -30px;	
}

.prix-tunnel span {
	font-size: 36px;	
}

.img-center {margin:0 auto;}

.quantite-container .btn-quantite{
	float: left;	
	display: block;
	width: 24px;
}

.quantite-container .quantite{
	float: left;	
	display: block;
	width: 20px;
	line-height: 24px;
}

/* Base for label styling */
[type="checkbox"]:not(:checked),
[type="checkbox"]:checked {
  position: absolute;
  left: -9999px;
}
[type="checkbox"]:not(:checked) + label,
[type="checkbox"]:checked + label {
  position: relative;
  padding-left: 25px;
  cursor: pointer;
}

/* checkbox aspect */
[type="checkbox"]:not(:checked) + label:before,
[type="checkbox"]:checked + label:before {
  content: '';
  position: absolute;
  left:0; top: 0px;
  width: 17px; height: 17px;
  border: 1px solid @purple;
  background: #fff;
  border-radius: 0px;
}
/* checked mark aspect */
[type="checkbox"]:not(:checked) + label:after,
[type="checkbox"]:checked + label:after {
  content:url('../assets/icones/check.png');
  position: absolute;
  top: -2px; left: 5px;
  transition: all .2s;
}
/* checked mark aspect changes */
[type="checkbox"]:not(:checked) + label:after {
  opacity: 0;
  transform: scale(0);
}
[type="checkbox"]:checked + label:after {
  opacity: 1;
  transform: scale(1);
}
/* disabled checkbox */
[type="checkbox"]:disabled:not(:checked) + label:before,
[type="checkbox"]:disabled:checked + label:before {
  box-shadow: none;
  border-color: #bbb;
  background-color: #ddd;
}
[type="checkbox"]:disabled:checked + label:after {
  color: #999;
}
[type="checkbox"]:disabled + label {
  color: #aaa;
}
/* accessibility */
[type="checkbox"]:checked:focus + label:before,
[type="checkbox"]:not(:checked):focus + label:before {
  border: 1px dotted blue;
}

/* hover style just for information */
label:hover:before {
  border: 2px solid @purple!important;
}

.form-container {
	text-align: center;
}

.promo-form .form-group {
	width: 100%;
}

.promo-form .form-control {
	width: 80%;
	border-radius:0px;	
	float: left;	
	height: 40px;
	margin:13px 0 0 5%;
}

.promo-form .btn{
	display: inline;
	float: left;
	border-radius: 0px;
	border:0px solid @lightgray;
	background :url('../assets/images/btn-footer-fond.png');	
	width: 57px;
	height: 62px;
	margin-left: -7px;
	color: #FFF;
	padding-top: 10px;
}

/* Phones (up to 768px) */
@media (max-width: 767px) { 
	
.promo-form .form-control {
	width: 80%;
}

}

/* @media (min-width: 992px) and (max-width: 1199px){ 
	
.promo-form .form-control {
	width: 75%;
}

} */

/* Livraison */

.info-form .form-control {
	border-radius:0px;	
}

.info-form .form-group {
	margin-bottom: 10px;
}

.info-form .detail {
	height: 30px;
}

.info-form .detail label {
	display: inline;
	width: 45%;
	color: @darkgray;
	padding-bottom: 10px;
	margin-left: 0;
	line-height: 35px;
}

.info-form .detail .form-control {
	float: right;
	display: inline;
	width: 55%;
}

.info-form .detail #crypto {
	width: 30%;	
}

.shipping-form .form-control {
	border-radius:0px;	
}

.shipping-form .form-group {
	margin-bottom: 10px;
}

textarea#complementary-info-form{
	width: 100%;
	border: 1px solid #ccc;
	color: #555555;
	padding: 6px 12px;	
}


.date-form .form-control {
	border-radius:0px;	
}

.date-form .form-group {
	margin-bottom: 10px;
}

.date-form label {
	padding-right: 30px;
}




/* Récapitulatif */
.recap-quantity {
	padding-left: 10px;	
}







/* Page Produit */

#page-title-section .page-title{
	font-size: 35px;
	padding: 10px;	
}

.produit-h2 {
	font-size: 20px;
	text-transform: none;
}	

.product-feature {
	font-size: 18px;	
}

.section-white {
	position: relative;
	background: #fff;
	border: 4px solid #fff;
}


.section-arrow-white {
	position: relative;
	background: #fff;
	border: 4px solid #fff;
}
.section-arrow-white:after, .section-arrow-white:before {
	top: 100%;
	left: 50%;
	border: solid transparent;
	content: " ";
	height: 0;
	width: 0;
	position: absolute;
	pointer-events: none;
}

.section-arrow-white:after {
	border-color: rgba(255, 255, 255, 0);
	border-top-color: #fff;
	border-width: 15px;
	margin-left: -15px;
}
.section-arrow-white:before {
	border-color: rgba(255, 255, 255, 0);
	border-top-color: #fff;
	border-width: 21px;
	margin-left: -21px;
}

.text-underline {
	text-decoration: underline;
}	

.product-sidebar .product-img {
	margin-top: -40px;
}

.achat-cadeau-container {
	position:absolute;		
	top:100%;	
}	

#produit-v {
	float: left;	
}

#purchase-information .liste-salles {
	list-style: none;
}

#offres .carte-content-left {
	right:3%;
}

.product-related {
	font-size: 20px;	
}

#related-products .produit-h2 {
	text-transform: uppercase;	
}

.product-sidebar hr {
	width: 30%;	
}

#related-products .carte-content-left {
	right:3.5%;
}

#related-products .carte-content-right {
	left:3.5%;
}

/* Phones (up to 768px) */
@media (max-width: 767px) { 
.product-sidebar .product-img {
	display: none;
}

.carte-content-produit-left {
	left:50%;
	transform:translate(-45%,-50%);	
}

#purchase-information .liste-salles {
	padding-left: 40px !important;
}

}


/* Small devices to large (tablets, 768px and up) */
@media (min-width: 768px) { 
.product-sidebar {
	width: 33%;
	margin-left: 0.3333%;	
}

#purchase-information .content-container, #purchase-information .content-title {
	padding-left: 5%;
	padding-right: 5%;	
}

.separator-right {
	border-right: 1px solid @lightgray;	
}

.product-show, .product-sidebar {
	min-height:600px;	
}
}





/* Page Cartes  */

.info-offer {
	padding-top: 50px;	
}

.card-offers {
	margin-top: 80px;	
	margin-bottom: 100px;
}

.filtre-form .form-control {
	border-radius: 0;	
	margin-right: 40px;
	padding-right: 30px;
	width: 200px;
	background: url('../assets/icones/filtre-fleche.png') right center no-repeat #fff;
}

select.filtre {
	color: #bebebe;
}
/* Hidden placeholder */
select option[disabled]:first-child {
	display: none;
}

select {
  background: transparent;
  width: 300px;
  padding: 5px 35px 5px 5px;
  font-size: 16px;
  border: 1px solid #ccc;
  height: 34px;
  -webkit-appearance: none;
  -moz-appearance: none;
  appearance: none;
  background: url(http://www.stackoverflow.com/favicon.ico) 96% / 15% no-repeat #eee;
}
/*target Internet Explorer 9 and Internet Explorer 10:*/

@media screen and (min-width: 0) {
  select {
    background: none;
    padding: 5px;
  }
}

.section-arrow-white-col {
	position: relative;
	background: #fff;
}
.section-arrow-white-col:after {
	top: 100%;
	left: 50%;
	border: solid transparent;
	content: " ";
	height: 0;
	width: 0;
	position: absolute;
	pointer-events: none;
	border-color: rgba(255, 255, 255, 0);
	border-top-color: #fff;
	border-width: 30px;
	margin-left: -30px;
}

.info-text {
	font-size: 10px !important;	
}

.card-offers .carte-content-left {
	right:2%;
}


.card-offers .carte-content-right {
	left:2%;	
}


/* Phones (up to 768px) */
@media (max-width: 767px) { 

.card-offers .carte-content-left {
	right:0%;
}

.card-offers .carte-content-right {
	left:50%;	
}

.col-card-right {
	margin-top: 180px;	
}

} 

.place-list {
	list-style: none;
}	

.place-list li {
	.itc-bk;	
}

.popover {
	border-radius:0px;	
	width:500px !important;
	border: #fff;
	text-align: center;
}

.popover-title {
	background-color: #fff;	
	border-bottom: 0px solid #fff;
}

button {
	border: 0px solid #fff;
	background-color: rgba(0,0,0,0);	
}

.modal-dialog {
    margin: 30px auto;
    width: 80%;
}

.modal-content {
    background-color: #fff;
    border: 0px solid rgba(0, 0, 0, 0);
    border-radius: 0px;
	.itc;
}

.modal-content .p {
	font-size: 15px;	
	margin-bottom: 20px;
}

.modal-content .purple {
	font-size: 17px;	
}

.modal-header {
    background-color: #000;
	border-bottom: 0px solid #FFF;
    padding: 15px;
	color: #FFF;
	text-align: center;
	text-transform: none;
}

.modal-header h2{
	font-size: 24px;
}

.modal-body {
	padding: 60px;
}

.modal-footer {
	border-top: 0px solid #fff;	
	padding: 0px;
}

#salles {
	margin-bottom: -50px;	
}

/* Small devices to large (tablets, 768px and up) */
@media (min-width: 768px) { 

#salles .last-col .place-list {
	margin-top: 70px;	
}

}
