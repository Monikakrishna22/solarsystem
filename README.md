<!DOCTYPE html>
<html>
<head>
	<title>Learn Solar System</title>
	<style type="text/css">
       
		body {
			
            background-image: url(images/bgi.jpg);
            background-repeat: no-repeat;
            background-attachment: fixed;
            background-size: cover;

			color: white;
			font-family: Copperplate, Papyrus, fantasy;
		}
		h1 {
			text-align: center;
			margin-top: 50px;
			font-size: 48px;
		}
		h2 {
			text-align: center;
			margin-top: 20px;
			font-size: 24px;
		}
		#solar-system {
			display: flex;
			flex-wrap: wrap;
			justify-content: center;
			align-items: center;
			margin-top: 50px;
		}
		button {
			background-color: rgba(0, 0, 0, 0);
			color: rgba(0, 0, 0, 0.197);
			border-radius: 50%;
			border: none;
			width: 100px;
			height: 100px;
			margin-right: 20px;
			margin-bottom: 20px;
			font-size: 24px;
			font-weight: bold;
			cursor: pointer;
		}
		button:hover {
			background-color: rgb(239, 238, 238);
			color: rgb(255, 254, 254);
		}
		
	</style>
</head>
<body>
<h1>Learn Solar System</h1>
<h2>Click on a planet to learn more!</h2>
<div id="solar-system">
    <button><a href="http://127.0.0.1:5500/ssmain.html" target="_blank"><img src="images/solarsystem.png" style="width: 100px;height: 100px;"></a></button>
    <button id="sun"><a href="images/su.png" target="_blank"><img src="images/sun.png" style="width: 100px;height: 100px;"></a></button>
    <button id="mercury"><a href="images/me.png" target="_blank"><img src="images/Mercury-PNG.png" style="width: 100px;height: 100px;"></a></button>
    <button id="venus"><a href="images/ve.png" target="_blank"><img src="images/Venus-PNG.png" style="width: 100px;height: 100px;"></a></button>
    <button id="earth"><a href="images/ea.png" target="_blank"><img src="images/earth.png" style="width: 100px;height: 100px;"></a></button>
    <button id="mars"><a href="images/ma.png" target="_blank"><img src="images/Mars-PNG.png" style="width: 100px;height: 100px;"></a></button>
    <button id="jupiter"><a href="images/jupi.png" target="_blank"><img src="images/Jupitar-PNG.png" style="width: 11s0px;height: 100px;"></a></button>
    <button id="saturn"><a href="images/sa.png" target="_blank"><img src="images/Saturn-PNG.png" style="width: 100px;height: 100px;"></a></button>
    <button id="uranus"><a href="images/ur.png" target="_blank"><img src="images/Uranus-PNG.png" style="width: 110px;height: 80px;"></a></button>
    <button id="neptune"><a href="images/ne.png" target="_blank"><img src="images/Neptune-PNG.png" style="width: 100px;height: 100px;"></a></button>
</div>

        </body>
        </html>
