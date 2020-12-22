<html lang="en">


    <head>
        <meta charset="utf-8"/>
        <style>
html {
	background-color: #f3e0e0;
	font-family: "Segoe UI";
    color: #f3e8ec;
} 

body { 
    margin: 0;
    width: 100%; 
    padding: 0px;
    height: 100%;
}

div.header {
    padding-top: 5px;
    padding-bottom: 5px;
    height: 60px;
	width: 100%;
	background-color: #151515;
    position: fixed;
    border-bottom: 0px solid #f3e8ec;
    box-shadow: 0px 0px 12px #000; 
    z-index: 1;
}

div.dividing {
    height: 35px
}

h1 {
    text-align: center;
	font-family: "Segoe UI";
    margin-top: 10%;
    margin-bottom: 10%;
    font-size:400%;
    text-shadow: 1px 1px 5px #000;
}

h2 {
    text-align: center;
	font-family: "Segoe UI";
    margin-top: 10px;
    margin-bottom: 3%;
    font-size:3em;

}

code {
    font-weight: bold;
    color:#151515;
    background-color: #d0f0d0;
}

header {
    font-size: 200%;
    font-weight: bold;
    text-align: center;
    padding-bottom: 10px;
}

ul{
	list-style-position: inside;
    font-weight: bold;
    
}

ol{
	list-style-position: inside;
    font-weight: bold;
}

li {
    font-weight: normal;
}

div.left {
   text-align: left; 
}

img {
	height: 100%;
 	padding: 0px;
    float: left;
}

#logo {
    height: 66px;
    padding-left: 5px;
}

img.fLeft {
	float: left;
    position: fixed;
}

div.black {
	float: left;
	background-color: #000;
    color: #f3e8ec;
	text-align: left; 
	font-size: 120%;	
    width:100%;
	height: 70%;
    box-shadow: 0px 0px 12px #000;
}

div.pic {
	float: right;
    background-image: url('CoolPaint.jpg');
    background-size: cover;
    width:100%;
	height: 100%;
    box-shadow: 0px 0px 12px #000; 
    background-attachment: fixed;
    padding: 40px;
}

.coolpic {
    box-shadow: 0px 0px 12px #000;
    display: block;
    margin-left: auto;
    margin-right: auto;
    width: 500px;
    float:inherit;
}


div.blogpost{
	background-color: #fefefe;
	text-align: center; 
	font-size: 120%;
    font-family: "Segoe UI";
    width:900px;
    box-shadow: 0px 0px 8px #000; 
    color: #151515;
    margin: auto;
    padding: 10px;
    padding-top: 25px;
    padding-bottom: 25px;    
}

div.picpost{
	background-image: url('dots.png');
    background-attachment: fixed;
	text-align: center; 
	font-size: 150%;
    font-family: "Segoe UI";
    width:900px;
    box-shadow: 0px 0px 8px #000; 
    color: #11255e;
    margin: auto;
    padding: 10px;
    padding-top: 50px;
    padding-bottom: 50px;    
}



div.invisibletextbox {
    padding-left: 10px;
    padding-right: 10px;
    text-align: left;
}

div.button p:hover {
    box-shadow: 1px 1px 2px #000;
    background-color: #f3e8ec;
    color: #d8272c;
    text-shadow: 0px 0px 0px #000;
}

a {
    text-decoration: none;
    color:inherit;
}


table, th, td {
	border: 2px solid black;
	text-align: center;
	border-collapse: collapse;
	height: 30px;
	width: 600px;
    
	background-color:#f97d7d;
}

#navcontainer {
    width:100%;
    margin: 0;
    position: absolute;
    top: 50%;
    transform: translateY(-50%);
}

#navcontainer ul {
    margin: 0;
    padding: 10px;
    list-style-type: none;
    text-align: center;
    float: right;
}

#navcontainer ul li { 
    display: inline; }

#navcontainer ul li a{
    font-family: "Segoe UI Semibold";
    text-decoration: none;
    padding: .2em 1.2em;
    padding-top: .7em;
    padding-bottom: .7em;
    font-size: 100%;
    color: #ffffff;
    margin-right: 10px;
    text-shadow: 1px 1px 3px #000;
    border: 1px solid #151515;
}

#coolbutton {
    background-color: #333;
    box-shadow: 1px 1px 3px #000;

}

#navcontainer ul li a:hover {
    background-image: linear-gradient(#353535, #000);
    border: 1px solid #333;
}


@media screen and (max-width: 1000px){
    div.blogpost{
        width:90%;
}
    div.picpost{
        width: 90%
    }
    .coolpic {
        width: 90%;}
}

/*@media screen and (max-height: 580px){
    div.pic {
        height: 640px
    }
}*/
@media screen and (max-width: 660px){
    div.button {
        visibility: visible;
        font-size: 3vw;
    }
    div.button p {
        width: 70%;
    }
}

</style>
        <title>SampleSite - Home</title>
        <link rel="icon" href="small_logo.png">
    </head>
    
    <body>
        <div class=header>
            <div>
		<img src=nikkilogo2.png alt="Logo" id="logo">
		</div>
            <div id="navcontainer">
                <ul>
                        <li><a href="tips.html">Tech Tips</a></li>
                <li><a href="about.html" id="coolbutton">About Me</a></li>
                </ul>
            </div>
        </div>

        <div style="height: 60px;"></div>


        <div class=pic>
            <h1>Ensley Exeter - Just another white chick</h1>
        </div>
        .
        <div class=dividing></div>
        
        <div class=blogpost><div class=invisibletextbox>September 3, 2020
            <p>Laying on the floor and staring at the ceiling is the equivalent to therapy for me</p></div></div>
        
        
        <div class=dividing></div>
        
                <div class=blogpost><div class=invisibletextbox>July 25, 2020
                    <p>For anyone wanting an update: my resurrection plant/Rose of Jericho! He's been chilling in water for a couple of days now and look how he's flourished! These guys just roll around in the desert until they find water to root themselves in. Very nomadic plants that adjust to their circumstances, and take advantage of opportunities to grow. I love the symbolism of these plants. They inspire me</p>
                    </div></div>
    
             <div class=dividing></div>
        
        <div class=blogpost><div class=invisibletextbox>August 13, 2020
            <p>5 years ago I moved out for the first time, and I’m getting ready to do it again. It’s wild to think of all the life I’ve been able to live in those 5 years</p>
            </div></div>

        
        <div class=dividing></div>
        
        
        
        <div class=black>
            <br><br>
        </div>


    </body>

</html>