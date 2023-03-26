<!DOCTYPE html>
<html>
<head>
	<title>My Personal Website</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<link href="https://fonts.googleapis.com/css?family=Lato:400,700&display=swap" rel="stylesheet">
	<style>
		body {
			font-family: 'Lato', sans-serif;
			margin: 0;
			padding: 0;
			background-color: #f1f1f1;
		}
		header {
			background-color: #333;
			color: #fff;
			padding: 20px;
			text-align: center;
		}
		h1 {
			margin: 0;
			font-size: 36px;
			font-weight: 700;
			text-transform: uppercase;
		}
		nav {
			background-color: #fff;
			padding: 10px;
			text-align: center;
			box-shadow: 0 2px 5px rgba(0,0,0,0.3);
		}
		nav a {
			color: #333;
			text-decoration: none;
			padding: 10px 20px;
			font-weight: 700;
			font-size: 18px;
			text-transform: uppercase;
		}
		nav a:hover {
			background-color: #333;
			color: #fff;
		}
		.container {
			margin: 20px auto;
			padding: 20px;
			background-color: #fff;
			box-shadow: 0 2px 5px rgba(0,0,0,0.3);
			max-width: 800px;
			text-align: justify;
			line-height: 1.5;
		}
		.container img {
			max-width: 100%;
		}
	</style>
</head>
<body>
	<header>
		<h1>My Personal Website</h1>
	</header>
	<nav>
		<a href="#about">About</a>
		<a href="#experience">Experience</a>
		<a href="#education">Education</a>
		<a href="#skills">Skills</a>
		<a href="#contact">Contact</a>
	</nav>
	<div class="container">
		<h2 id="about">About Me</h2>
		<p>Insert your brief bio here.</p>
		<h2 id="experience">Experience</h2>
		<ul>
			<li><strong>Company Name</strong> - Position Title (Start date - End date)</li>
			<li><strong>Company Name</strong> - Position Title (Start date - End date)</li>
			<li><strong>Company Name</strong> - Position Title (Start date - End date)</li>
		</ul>
		<h2 id="education">Education</h2>
		<ul>
			<li><strong>University Name</strong> - Degree Title (Start date - End date)</li>
			<li><strong>University Name</strong> - Degree Title (Start date - End date)</li>
		</ul>
		<h2 id="skills">Skills</h2>
		<ul>
			<li>Skill 1</li>
			<li>Skill 2</li>
			<li>S
