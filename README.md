<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
	<title>Alex Shelley</title>
	<style>
		* {
			font-family: Times New Roman, serif;
		}
		body {
			margin: 0;
			font-size: 11px;
			line-height: 13px;
		}
		a, a:visited {
			color: black;
			font-style: italic;
			text-decoration: none;
		}
		.information {
			z-index: 1000;
			margin: 1.2em;
			position: absolute;
		}
		.container {
			z-index: 1;
			width: 100vw;
			height: 100vh;
			margin: auto;
			position: relative;
		}
		.image_container {
			width: 800px;
			height: 500px;
			display: flex;
			flex-direction: row;
			margin: 0;
			position: absolute;
			top: 50%;
			left: 50%;
			-ms-transform: translate(-50%, -50%);
			transform: translate(-50%, -50%);
		}
		.image_1 {
			width: 50%;
			height: 100%;
			margin-right: 0.5em;
			background-image: none;
			background-size: cover;
		}
		.image_2 {
			width: 50%;
			height: 100%;
			margin-left: 0.5em;
			background-image: none;
			background-size: cover;
		}
		@media (max-width: 840px) {
			.image_container {
				width: 400px;
				height: 250px;
			}
		}
		@media (max-width: 480px) {
			.image_container {
				width: 320px;
				height: 200px;
			}
		}
	</style>
</head>
<body style="pointer-events: auto;">
	<div class="information">
		Alex Shelley<br>
		ashell.info@gmail.com<br>
		Portland, OR.<br>
		<br>
		Portrait World, 2024<br>
		Visual identity, web design, merch and photography<br>
		<br>
		No Pressure, 2024<br>
		Design, layout and copy<br>
		<br>
		Specialized Rockhopper<br>
		Design, layout and copy<br>
	</div>
	<div class="container" style="pointer-events: auto;">
		<div class="image_container">
			<div class="image_1"></div>
			<div class="image_2"></div>
		</div>
	</div>
</body>
</html>
