<!DOCTYPE html>
<html>
	<head>
		<title>RANDOM BRICKS</title>
		<meta charset="UTF-8"/>
		<link rel="stylesheet" type="text/css" href="css/style.css">
		
	</head>
	<body onload="drawIt()">
			<nav>
				<div class="whiteWrap">
					<h1>RANDOM BRICKS by Matej Rupnik</h1>
				</div>
			</nav>

			<main>
				<div class="whiteWrap">
					<canvas id="canvas" width="450" height="450"  tabindex="1">
						Tvoj brskalnik ne podpira HTML5 canvas značke.
					</canvas>
				</div>
				<script charset="UTF-8" src="javas/main.js" ></script>
			</main>

			</div>

			<footer><div class="whiteWrap">pritisni SPACE za začetek in ponovni zagon igre</div></footer>
			<footer><p class="whiteWrap">Točke: <mark id="tocke">0</mark>Čas: <mark id="cas">00:00</mark></p></footer>
	</body>
	<script src="javas/jQuery.js"></script>
	<!--<script type="text/javascript" src="../javas/main.js"></script>-->
</html>
