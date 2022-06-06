<!DOCTYPE html>
<html>

	<head>
		<meta charset="UTF-8" />
		<title>Lorde Wiki - Adique</title>
		<link rel="shortcut icon" type="images/lordefavicon.jpg" href="images/lordefavicon.jpg"/>
		<meta name="author" content="John Vic A. Adique">
		<meta name="keywords" content="HTML, CSS, CSProject, Lorde">
		<meta name="revised" content="07-11-2021">
		<link rel="stylesheet" href="css/styles.css" type="text/css" />	
	</head>
	
	<style>
	
	body {                         /* This is what the base of the website will look like */
	background-image: url(images/lordeback.jpg);  
	background-size: cover;
	background-position: center;
    background-repeat: no-repeat;
    background-attachment: fixed;
	padding-top: 100px;
	padding-bottom: 50px;
	}
	
	.infobox {                     /* The main content and information */
	height: 1300px;
    width: 700px;
	background-color: #F4D37A;
    border: 1px solid black;
	border-radius: 10px;
    margin-right: 300px;
	margin-left: 200px;
	margin-top: 20px;
	margin-bottom: 20px;
	padding: 50px;
    font-family: "Times New Roman", Times, serif;
	}
	
	.fixedheader{                  /* Buttons for the main page, the subpage, and Lorde's Spotify */
    width: 100%;
    position: fixed;        
    background: #EBE1C8;
    padding: 20px 0;
    color: #fff;
	top: 0;
	left: 0;
	display: flex;
	justify-content: left;
    align-items: center;
	}
	 
	.box{                           /* A quick summary of the wiki in a box */
    background-color: white;
    width: 270px;
    border: 2px solid black;
    margin: 30px;
	float: right;
	}
	
	.titleinfo{                     /* The text block below the image */
    display: block;
    width: 270px;
    height: 50px;
    border-bottom: 1px solid black;    
    background-color: yellow;
    float: right;	
	}
	
	.infoboxtext1{                  /* The first text in the infobox */
	padding-left: 15px;
	padding-right: 15px;
	margin-top: 70px;
	}
	
	.infoboxtext2{                  /* The remaining text in the infobox */
	padding-left: 15px;
	padding-right: 15px;
	margin-top: 20px;
	}
	
	.navigation {                   /* A column on the right where you can click on an album and it directly leads you to Spotify */
    float: right;
    width: 200px;
    background: #eee;
	position: fixed;
	top: 94px;
	right: 0;
	bottom: 0;
	display: flex;
	justify-content: center;
	align-items: center;
	background: #F6DB97;
	}
	
	.fixedfooter{                   /*  The footer */
    width: 100%;
    position: fixed;        
    background: #EBE1C8;
    padding: 20px 0;
    color: black;
	bottom: 0;
	left: -10px;
	}
	
	</style>
	
	<body>
	<div class="fixedheader">
		<span style="margin-left: 50px"><img src="images/lordefavicon.jpg" height="50px" width="50px"></span>
		<span style="margin-left: 20px"><img src="images/lordename.jpg" height="25px" width="100px"></span>
	    <nav>
            <a href="file:///C:/Users/Yam/Desktop/CS3%20Q1%20Project_Adique/CS3_Q1%20Project_Adique.html"><span style="margin-left: 20px; margin-right: 20px; vertical-align:middle"><img src="images/homeicon.jpg" height="20px" width="20px"></span></a>
            <a href="file:///C:/Users/Yam/Desktop/CS3%20Q1%20Project_Adique/CS3_Q1%20Project_Adique_Subpage.html"><span style="margin-right: 20px; vertical-align:middle"><img src="images/albumicon.jpg" height="20px" width="20px"></span></a>
            <a href="https://open.spotify.com/artist/163tK9Wjr9P9DmM0AVK7lm?si=sgCMpcN1RLKym4iAn_t1Xg"><span style="margin-right: 20px; vertical-align:middle"><img src="images/spotifyicon.jpg" height="20px" width="20px"></span></a>
        </nav>
	</div>
	
	<div class="navigation">
	    <nav>
			<p>
			    <span style="font-weight:600">Lorde's Discography</span>
			</p>
			
            <p>
			    <a href="https://open.spotify.com/album/6rnzvZhe3PA57xKcKLRtJ6?si=0kqtUybAQjeZoK8kj-HTEQ">
				    <span style="margin-left: 20px; margin-right: 20px">
				        <img src="images/ph.jpg" height="100px" width="100px">
				    </span>
				</a>
			</p>
			
			<p>
			    <span style="display: flex; justify-content: center; align-items: center; font-weight:600">Pure Heroine</span>
			</p>
			
			<p>
			    <a href="https://open.spotify.com/album/2B87zXm9bOWvAJdkJBTpzF?si=YOzVlKCOReeexbmfPZc45g">
				    <span style="margin-left: 20px; margin-right: 20px">
					    <img src="images/melo.jpg" height="100px" width="100px">
					</span>
				</a>
			</p>
			
			<p>
			    <span style="display: flex; justify-content: center; align-items: center; font-weight:600">Melodrama</span>
			</p>
			
            <p>
			    <a href="https://open.spotify.com/album/3lK2JRwfIOn2NaYtgEGTmZ?si=zib7Lrp6Temc_3G0BSNctQ">
			        <span style="margin-left: 20px; margin-right: 20px; vertical-align:middle">
					    <img src="images/sp.jpg" height="100px" width="100px">
					</span>
				</a>
			</p>
			
			<p>
			    <span style="display: flex; justify-content: center; align-items: center; font-weight:600">Solar Power</span>
			</p>
	    </nav>
	</div>
	
	<div class="infobox">
	    <div class="box">
	        <span style="display: flex; justify-content: center; font-family: Verdana; align-items: center; font-weight:600; font-size: 20px; padding-top:20px; padding-bottom:10px">Lorde</span><img style="display: block" src="images/lorde.jpg" height="350px" width="270px">
	        <span class="titleinfo" style="display: flex; justify-content: center; align-items: center; font-family: Verdana; font-weight:600; font-size: 15px">General Information</span>
	            <p class="infoboxtext1">
			        <span style="font-family: Times New Roman; font-weight:600; font-size: 15px">Full Name</span>
			        <span style=" font-family: Times New Roman; font-size: 12px; padding-left: 30px"> Ella Marija Lani Yelich-</span><span style=" font-family: Times New Roman; font-size: 12px; padding-left: 130px">O Connor</span>
			    </p> 
	        <hr>
			
	            <p class="infoboxtext2">
			        <span style="font-family: Times New Roman; font-weight:600; font-size: 12px">Birthdate</span>
			        <span style=" font-family: Times New Roman; font-size: 12px; padding-left: 65px">November 7 1996</span>
			    </p>
	        <hr>
			
	            <p class="infoboxtext2">
			        <span style="font-family: Times New Roman; font-weight:600; font-size: 12px">Hometown</span>
			        <span style=" font-family: Times New Roman; font-size: 12px; padding-left: 45px">Takapuna, New Zealand</span>
			    </p>
            <hr>
			
	            <p class="infoboxtext2">
			        <span style="font-family: Times New Roman; font-weight:600; font-size: 12px">Years Active</span>
			        <span style=" font-family: Times New Roman; font-size: 12px; padding-left: 60px">2012 - Present</span>
			    </p>
		</div>
	
	    <p style="font-family: Arial; font-size: 50px">Lorde</p>  <!-- The main text -->
	
	    <p style="font-family: Times New Roman; font-size: 20px">Ella Marija Lani Yelich O'Connor, more famously known as <span style="font-weight: 600">Lorde</span>, was born in Takapuna, New Zealand on November 7th, 1996. The daughter of Sonja Yelich and Vic O'Connor, was already showing her talent in writing when she won 2nd place, along with her teammates, in a global literature contest when she was 13 </p>
	    <p style="font-family: Times New Roman; font-size: 20px">After several years, she was signed with Universal Music Group and then in 2013, she released her first EP called The Love Club EP. After they saw the success it has sprung, Lorde then released her first album called <span style="font-weight: 600"> Pure Heroine. </span>
	    This album has produced a number-one single called Royals, that helped here boost her prominence. Her debut album won several awards, including Song of the Year at the GRAMMYs Award and was named Album of the Year in New Zealand Music Awards. It was regarded as an influential alobum and a "game-changer" that changed the landscape of pop music.</p>
	    <p style="font-family: Times New Roman; font-size: 20px">After her world tour for her debut album, she went on hiatus for several years. She went back on 2017 to tease her new single, called Green Light for her 2nd studio album, called <span style="font-weight: 600"> Melodrama</span>. This single peaked at number 20 in Billboard Hot 100. After that she then released her 2nd single, called Perfect Places 3 months after.
	    15 days later, she released her most anticipated album, Melodrama. It went number one on Billboard 200 and was critically acclaimed by various critics and reviwers. It received a 91 in the website Metacritic and was given an 8.8 over 10 score by Pitchfork. It also went number 460 on Rolling Stone's 500 Best Albums of All-Time.</p>
	    <p style="font-family: Times New Roman; font-size: 20px">After this, she went on a 4-year hiatus. This June, she teased an image in her website featuring herself and a beach in her background. On June 20, she released the title track for her 3rd studio album, <span style="font-weight: 600"> Solar Power </span> . It went number 6 on the Billboard 100. 2 days before the release of the album, she released the 2nd single called Mood Ring.
	    On August 20, she released Solar Power and it went number 5 on Billboard 200. It also went number on on New Zealand and Australia Album Charts. Her Solar Power tour will embark early next year.</p>
		
		<p style="font-family: Arial; font-size: 30px">Sources</p> <!-- The sources -->
		<hr>
		<p style="font-family: Times New Roman; font-size: 15px">Ray, Michael. "Lorde" Britannica: Biography, edited by Amy Tikannen. <a href="https://www.britannica.com/biography/Lorde" style="text-decoration: none; color: black" >https://www.britannica.com/biography/Lorde</a></p>
	    
		</div>
        </div>
	
	<div class="fixedfooter" ></div>
	
	</body>
	
</html>
