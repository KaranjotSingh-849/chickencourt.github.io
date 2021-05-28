<html>
    <head>
        <meta charset="utf-8">
	<title>Chicken Court</title>
	<link rel = "icon" href = 
"Icon Logo.jpg" 
        type = "image/x-icon">
	<link rel="preconnect" href="https://fonts.gstatic.com">
	<link href="https://fonts.googleapis.com/css2?family=Girassol:wght@400&display=swap" rel="stylesheet">
	<link href="https://fonts.googleapis.com/css2?family=Karla:wght@500&display=swap" rel="stylesheet">
	<link href="https://fonts.googleapis.com/css2?family=Goblin+One&display=swap" rel="stylesheet">
        <style>
                   *{
                             margin: 0px;
	        padding: 0px;
                    }
                     body{
        	      background : rgb(100, 200, 255, 0.3);
	      overflow-x: hidden;
	}
	#navBar{
	      display: flex;
	      flex-direction: row;
	      padding-left: 10%;
	      
	}
	#HeadingLogo{
	width: 30%;
	
	}
	#HeadingLogo img{
	width: 100%;
	max-width: 200px;
	}
	#navOptions{
	margin-left: auto;
	padding: 5px;
	margin-right: 15%;
	display: flex;
	justify-content: space-around;
	}
	.NavTools{
	align-self: center;
	text-align: center;
	white-space: nowrap;
	margin: 5%;
	padding-bottom: 20%;
	font-size: 30px;
	color: Black;
	font-family: Girassol;
	font-weight: bold;
	}
	a {
	text-decoration: none;
	}
	.NavTools:hover{
	text-decoration: underline;
	animation-name: texty;
	animation-duration: 2s;
	}

	@keyframes texty{
	from{
	           font-size: 30px;
	}
	to{
	          font-size: 32px;
	}
	}
	
	.content{
	     background: rgb(0, 0, 0, 0.1);
	     display: flex;
	     padding: 5%;
	
	}

	.content p{
	font-size: 42px;
	align-self: center;
	color: black;
	font-family: Karla;
	}
	.content img{
	width: 40%;
	border: gray 5px inset;
	}
	.content img:hover, .itemImg:hover{
	animation-name: grow;
	animation-duration: 2s;
	}
	
	@keyframes grow{
	  from {
	            transform: scale(1.0);
	      }
	  to {
	            transform: scale(1.1);
	      }
	}
	#oneText, #threeText{
	margin-right: 10%;
	}
	#twoText{
	margin-left: 10%;
	text-align: right;
	}
	
	#theProducts{
	     margin-top: 20px;
	      width: 100%;
	      background: rgb(0, 100, 200, 0.3);
	      padding: 5px 5%;
	      text-align: center;
	}
	#theProducts h1{
	text-align: center;
	font-size: 50px;
	font-family: 'Goblin One';
	text-decoration: underline;
	}
	#flexProducts{
	display: flex;
	margin: 5px 0px ;
	flex-wrap: wrap;
	justify-content: center;
	padding: 0 5%;
	}
	.flexItem{
	background: rgb(0, 0, 0, 0.1);
	width: 40%;
	margin: 10px 5%;
	text-align: center;
	}
	.itemH{
	padding-top: 10px;
	font-family: 'Goblin One';
	font-size: 27px;
	color: rgb(0, 0, 0, 0.95);
	}
	.itemImg{
	margin-top: 10px;
	width: 80%;
	height: 70%;
	}
	.itemP{
	margin-top: 5%;
	font-family: Karla;
	font-size: 24px;
	color: black;
	}
	#footer{
	background: black;
	margin: 0px;
	padding-top: 20px;
	padding-bottom: 20px;
	font-family: Arial;
	font-size: 20px;
	text-decoration: underline;
	}
	#footer a{
	margin: 20%;
	color: rgb(0, 120, 150);
	}
	@media (max-width: 750px){
                           #HeadingLogo{
	       margin-left: 0px;
	       width: 150px;
	          }
	#navBar{
	      padding-left: 0px;
	     
	}
	#navOptions{
	 justify-content: right;
	margin-right: 2.5%;
	}
	#oneText, #twoText, #threeText{
	margin: 1% 5%;
	padding: 0px;
	font-size: 32px;
	text-align: justify;
	}
	.NavTools{
	white-space: normal;
	margin: 2.5%;
	padding-bottom: 0%;
	}
	.content{
	flex-direction:column;
	align-items: center;
	}
	.content img{
	width: 80%;
	margin: 5%;
	order: -1;
	}
	#flexProducts{
	flex-direction: column;
	align-items: center;
	}
	.flexItem{
	width: 80%;
	}
	#theProducts{
	padding: 5px;
	}
	#footer a {
	margin: 15%;
	}
            }
        </style>
    </head>
    <body>
	<div id = "navBar"> 
	<a href = "homepage.html" id = "HeadingLogo">
	<img src = "Heading Logo.jpg" ></a>
		<div id = "navOptions">
		           <a href = "Portfolio.html" id = "Portfolio" class = "NavTools" target = "_blank"> Portfolio </a>
		            <a href = "homepage.html#theProducts" id = "Products" class = "NavTools" target = "_blank">Our products</a>
		           <a href = "AboutUs.html" id = "AboutUs" class = "NavTools" target = "_blank">About Us</a>
		</div>
	</div>
	<div id = "firstText" class = "content"> 
	              <p id = "oneText">
		We provide the best types of chicken and meat dishes.
	                </p>
	                <img src = "bkg1.jpg" id = "bkg1">
	</div>
	<div id = "secondText" class = "content"> 
	                <img src = "bkg2.jpg" id = "bkg2">
	              <p id = "twoText">
		We have strict environmental policies and the best corporate social responsibility policies.
	                </p>
	</div>
	<div id = "thirdText" class = "content"> 
	                
	              <p id = "threeText">
		Since our starting in the 2015, we have been provoding the best experiences to all our customers.
	                </p>
	                <img src = "bkg3.jpg" id = "bkg3">
	</div>
	<div id = "theProducts"> 
	             <h1>Our Products</h1>
	            <div id = "flexProducts">
		<div id = "item1" class = "flexItem">
		     <h2  id = "hdo1" class = "itemH">Chicken Dishes</h2>
		<a href = "chickenPage.html" target = "_blank">
		     <img src = "fpg1.jpg" class = "itemImg">
		     <p id = "pro1" class = "itemP">We provide all kinds of chicken dishes.</p>
		</a>
		</div>

		<div id = "item2" class = "flexItem">
		     <h2  id = "hdo2" class = "itemH">Mutton Dishes</h2>
		<a href = "muttonPage.html" target = "_blank">
		     <img src = "fpg2.jpg" class = "itemImg">
		     <p id = "pro2" class = "itemP">All varieties of mutton dishes can be found on our site.</p>
		</a>
		</div>

		<div id = "item3" class = "flexItem">
		     <h2  id = "hdo3" class = "itemH">Rice dishes</h2>
		<a href = "ricePage.html" target = "_blank">
		     <img src = "fpg3.jpg" class = "itemImg">
		     <p id = "pro3" class = "itemP">Delivering rice in delicious ways is our skill.</p>
		</a>
		</div>

		<div id = "item4" class = "flexItem">
		     <h2  id = "hdo4" class = "itemH">Other Dishes</h2>
		<a href = "beveragePage.html" target = "_blank">
		     <img src = "fpg4.jpg" class = "itemImg">
		     <p id = "pro4" class = "itemP">Many other dishes are also sold by us.</p>
		</a>
		</div>
	             </div>
	</div>
	<div id = "footer">
	          <a href = "Portfolio.html" target = "_blank">Portfolio</a>
	          <a href = "AboutUs.html" target = "_blank">About Us</a>
	</div>
    </body>
</html>
