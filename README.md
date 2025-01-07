<html lang="en"><head>
		<meta charset="UTF-8">
		<meta name="viewport" content="width=device-width, initial-scale=1.0">
	    <meta http-equiv="X-UA-Compatible" content="ie=edge">
		<title>Lucas Reif</title>
		<style>
			*{
				font-family: Times New Roman, serif;
			}
			body{
				margin: 0;
				font-size: 1em;
				line-height: 1.2;
			}
			a, a:visited{
				color: black;
				font-style: italic;
				text-decoration: none;
			}
			a:hover{
			}
			.information{
				z-index: 1000;
				margin: 1.2em;
				position: absolute;
			}
			.container{
				z-index: 1;
				width: 100vw;
				height: 100vh;
				margin: auto;
				position: relative;
			}
			.image_container{
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
			.image_1{
				width: 50%;
				height: 100%;
				margin-right: 0.5em;
				background-image: url('image_1.jpg');
				background-size: cover;
			}
			.image_2{
				width: 50%;
				height: 100%;
				margin-left: 0.5em;
				background-image: url('image_2.jpg');
				background-size: cover;
			}
			@media(max-width: 840px){
				.image_container{
					width: 400px;
					height: 250px;
				}
			}
			@media(max-width: 480px){
				.image_container{
					width: 320px;
					height: 200px;
				}
			}
		</style>
	</head>
	<body style="pointer-events: auto;">
		<div class="information">
			Lucas Reif<br>
			info@lucasreif.com<br>
			New York<br>
			<br>
			<a href="https://shelfshelf.store/">Shelf Shelf</a><br>
			<a href="https://thenormalstudio.com/">Normal</a><br>
			<a href="https://music-arts.art/">Music Arts</a>
		</div>
		<div class="container" style="pointer-events: auto;">
			<div class="image_container">
				<div class="image_1"></div>
				<div class="image_2"></div>
			</div>
		</div>
	
</body></html>
