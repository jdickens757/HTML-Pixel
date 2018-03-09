# HTML-Pixel
<!DOCTYPE html>
<html>

	<head>
		<style>
			#cellphone{
			width:270px;
			height:510px;
			background-color:black;
			border-radius: 15px;
			background-image: linear-gradient(to right top, #00ff00, #a0d600, #d7a700, #f66d00, #ff0000);
			text-align: center
		}
		#goo{
		font-family: Impact,Charcoal,san-serif;
		}
		#iframeContainer{
			width: 250px;
			height:400px;
			background-color: white;
			margin:auto;
			overflow: hidden;
		}
		#iframeContainer iframe{
			height: 103%;
			width: 106%;
		}
		#homeBtn{
			width: 50px;
			height: 10px;
			border: 2px solid white;
			margin: auto;
		}
		</style>
	</head>

	<body>
		<div id="cellphone">
			<br>
			<div id="Goo">Google</div>
			<br>
			<div id="iframeContainer">
				<iframe src="http://bbc.com">
			</div>
			<br>
			<div id="homeBtn"></div>
		</div>
	</body>

</html>
