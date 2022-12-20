<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8" />
		<meta http-equiv="X-UA-Compatible" content="IE=edge" />
		<meta name="viewport" content="width=device-width, initial-scale=1.0" />
		<title>Developer Landing Page</title>
		<link rel="stylesheet" href="style.css" />
	</head>
	<body>
		<section class="pimg1">
			<div class="ptext">
				<span class="textbg"
					><h2>Hi,</h2>
					I am Chaitanya</span
				>
				<h1>FRONTEND DEVELOPER</h1>
			</div>
		</section>
		<section class="section section-light">
			<h2>What Can I Do For <span>You</span>...</h2>
		</section>
		<section class="work">
			<div class="grid-item">
				<div class="card">
					<div class="image-container">
						<img
							src="./Web.jpg"
							alt="Websites"
							width="320"
							height="200"
							style="border-radius: 10px;"
						/>
					</div>
					<div class="cardcontent">
						<h3>Web Development</h3>
						<p>
							Web development is the work involved in developing a website for the Internet (World
							Wide Web) or an intranet <br />(a private network). Web development can range from
							developing a simple <br />single static page of plain text to complex web
							applications, electronic businesses, and social network services.
						</p>
					</div>
				</div>
			</div>
			<div class="grid-item">
				<div class="card">
					<div class="image-container">
						<img src="./App.jpg" alt="App" width="320" height="200" style="border-radius: 10px;" />
					</div>
					<div class="cardcontent">
						<h3>App Development</h3>
						<p>
							Mobile application development is the process of creating software applications that
							run on a mobile device, and a <br />typical mobile application utilizes a network
							connection to work with remote <br />computing resources.
						</p>
					</div>
				</div>
			</div>
		</section>
		<section class="bottom-section">
			<div class="contact">
				<h2>Contact Me</h2>
				<p>Feel Free to Contact me...</p>
				<p>Contact No.:+91 9014722037</p>
				<p>Chaitanyadwarapudi123@gmail.com</p>
			</div>
			<div class="about">
				<h2>About Me</h2>
				<p>
					As a web developer, I have many years of experience with CSS, JavaScript, and HTML.<br />
					On top of that, my software development skills allowed me to build up my object-oriented programming
					abilities.<br /> In the wrong example, you simply state front end responsibilities.
				</p>
			</div>
		</section>
		<footer>Project By Chaitanya..</footer>
	</body>
</html>

<style>
	html,
	body {
		height: 100%;
		margin: 0;
		font-size: 16px;
		font-family: 'lato', sans-serif;
		font-weight: 300;
		line-height: 1.8em;
		color: black;
	}
	.pimg1 {
		background-image: linear-gradient(to right, #5433ff , #20bdff, #a5fecb);
		min-height: 100vh;
		position: relative;
		background-position: center;
		background-size: cover;
		background-repeat: no-repeat;
	}
	.ptext {
		color: black;
		max-width: 900px;
		margin: 0 auto;
		font-size: 90px;
		padding-top: 70px;
		padding-left: 16px;
	}
	.ptext h2 {
		display: block;
		font-size: 1.5em;
		margin-block-start: 0.83em;
		margin-block-end: 0.83em;
		margin-inline-start: 0px;
		margin-inline-end: 0px;
		font-weight: bold;
	}
	.ptext h1 {
		font-size: 60px;
		margin-top: 6%;
		font-weight: bold;
	}
	.section {
		padding: 50px 80px;
		text-align: center;
	}
	.section-light {
		background-color: rgb(7, 7, 7);
		color: white;
	}
	.section h2 {
		font-size: 40px;
	}
	.section span {
		font-size: 90px;
	}
	.work {
		display: grid;
		grid-template-columns: repeat(auto-fit, minmax(320px, 1fr));
		gap: 20px;
		margin: 20px 0;
		max-width: 900px;
		margin: 50px auto;
	}
	.grid-item {
		display: flex;
		justify-content: center;
		align-items: center;
	}
	.card {
		max-width: 320px;
		height: 550px;
		border-radius: 10px;
		box-shadow: 3px 5px 5px hsl(0, 3%, 28%);
		transition: 0.3s ease-in-out;
	}
	.card:hover {
		transform: scale(1.04);
		box-shadow: 3px 5px 5px rgba(1, 1, 1, 0.2);
		transition: 0.3s ease-in-out;
	}
	.cardcontent {
		padding-left: 20px;
	}
	.cardcontent h3 {
		font-weight: bold;
	}
	.cardcontent p {
		margin-top: 5%;
	}
	.bottom-section {
		display: flex;
	}
	.contact {
		background-color: rgb(137, 137, 137);
		width: 100%;
	}
	.contact h2 {
		font-weight: bold;
	}
	.contact p {
		margin-top: 5%;
	}
	.about {
		background-color: rgb(0, 0, 0);
		color: white;
		width: 100%;
	}
	.about h2 {
		font-weight: bold;
	}
	.about p {
		margin-top: 5%;
	}
	.contact,
	.about {
		min-height: 300px;
		padding: 35px;
	}
	.contact p,
	.about p {
		margin-bottom: 10px;
	}
	.contact h2,
	.about h2 {
		font-size: 64px;
		font-weight: 300px;
	}
	footer {
		text-align: center;
		text-transform: uppercase;
		background-color: rgb(12, 12, 12);
		padding: 20px;
		color: white;
		font-size: 19px;
		width: 100%;
	}
	@media (max-width: 786px) {
		.pimg1 {
			min-height: 50vh;
		}
		.ptext {
			padding: 10px 0;
			text-align: center;
			font-size: 50px;
		}
		.ptext h1 {
			font-size: 30px;
		}
		.textbg h1 {
			font-size: 32px;
		}
		.section-light h2 {
			font-size: 24px;
		}
		.section-light h2 span {
			font-weight: 400;
			font-size: 32px;
		}
		.bottom-section {
			flex-direction: column;
		}
		.about h2,
		.contact h2 {
			font-size: 32px;
		}
	}
</style>
