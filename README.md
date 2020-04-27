# My Portfolio
<!DOCTYPE html>
<html>

<!-- Head -->
	<head>
		<meta charset="UTF-8">
		<title>Your name here </title>
		<link rel="stylesheet" type="text/css" href="Stylesheet/sample_Portfolio.css">
	</head>

<!-- Body -->
<body class="Background"> 

<!-- Navbar -->
	<div class="Navbar">
		<a class="active" href="#Home">Home</a> 
		<a href="#About">About</a>
		<a href="#GitHub">GitHub</a>
		<a href="#Contact">Contact</a>
	</div>

<!-- Home -->
		<br> <!-- Breaks inserted to add space between navbar and first heading -->
		<br>

<!-- Video -->
	<div id="Home">
		<video autoplay muted loop id="Typing_Video"> <!-- Makes the video play automatically, on a loop and with no sound -->
			<source src="Stylesheet/Video/Typing.mp4" type="video/mp4">
			Your browser does not support HTML5 video. <!-- Display message if video fails to run -->
		</video>
	</div>

<!-- Video text --> 
	<div class="Video_Text"> 
		<h1 style="color:white;">PEACE PANZA's Portfolio</h1>
			<p> 
				<strong>
					<center>
						<q>The computer programmer is a creator of universes for which he alone is the lawgiver.
						<br>No playwright, no stage director, no emperor, however powerful, has ever exercised such absolute authority to arrange a stage or
						<br>field of battle and to command such unswervingly dutiful actors or troops.
						</q>	
						<br>-Joseph Weizenbaum<br>
						<br>
						Welcome to my portfolio website. On it, I will tell you about my background and experience.<br>
						<br>Thank you for stopping by and enjoy! 
					</center>	
				</strong>
			</p> 
	</div>

<!-- About section -->
	<div class="Row" id="About"> 
		<div class="Column_2"> <!-- Left column -->
			<img src="Stylesheet/Images/Development.jpg" alt="Laptop">
		</div>
  
		<div class="Column_1"> <!-- Right column -->
			<h1>About</h2>
				<p>I am a very new in this industry and I am learning to code! As a young adult, I enjoy time with my family, friends and traveling. <br><br>I am a graduate of <a href="https://www.learncodinganywhere.com" target="_blank">The Tech Academy</a>’s Software Developer Boot Camp, and trained and experienced in the following web and programming languages: HTML, CSS, JavaScript, SQL, C# and more. <br><br>I am a full-stack developer and would love to work with you on your project. <a href="#Contact">Contact</a> me below!</p>
		</div>
	</div>

<!-- GitHub section -->
	<div class="Row" id="GitHub">
		<div class="Column_1"> <!-- Left column -->
			<h1>GitHub</h1>
				<p>You can view my coding projects on my GitHub profile here:<br>
				<center><a href="https://github.com/ppanza" target="_blank">The Tech Academy GitHub</a></center></p>
		</div>
		
		<div class="Column_2"> <!-- Right column -->
			<a href="https://github.com/ppanza" target="_blank"><img src="Stylesheet/Images/GitHub.png" alt="GitHub"></a>
		</div>
	</div>

<!-- Contact section -->
	<div class="Row" id="Contact"> 
		<div class="Column_3"> <!-- Contact image, left column -->
			<img src="Stylesheet/Images/Contact.jpg" alt="Contact_Image">
		</div>
	
		<div class="Column_1"> <!-- Contact form, right "column" -->
			<h1>Contact</h2> 
				<form action="" method="get"> <!-- This specifies where to send the form data and how; it is left blank -->
					<label>Name:</label>
						<input type="text" placeholder="Please enter your name here">
					<label>Email:</label>
						<input type="text" id="Email" name="Email" placeholder="Please enter your email here">
					<label>Message:</label>
						<input type="text" id="Message" name="Message" placeholder="Please write your message here">
						<input type="submit" value="Submit">
				</form>
		</div>
	</div>
	
<!-- Footer section -->
	<footer>
		<p>
			<center>&copy Prosper Consulting Inc.,  <a href="https://learncodinganywhere.com/">The Tech Academy</a></center><br>
		</p>
	</footer>

		</body>

</html>
