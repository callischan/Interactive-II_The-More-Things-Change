# Interactive-II_The-More-Things-Change

<html lang="en">

<head>

	<meta charset="utf-8" />
	<meta http-equiv="Content-Type" content="text/html; charset=UTF-8" />
	<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1"/>

	<style>
	.half {
		position: relative;
		display: inline-block;
		width: 30%;
		height: 500px;
	}
	.video-box {
		position: absolute;
		height: 100%;
		width: 100%;
		overflow: hidden;
	}
	video {
		width: 100%;
		height: 100%;
	}
	</style>
	
	
	
<html>
	<body>

		<div class="half">
			<div class="video-box">
				<video onclick="this.paused ? this.play() : this.pause();"
				poster="vidsrc/img1.jpg"><source src="vidsrc/1.mov">
				</video>
			</div>
		</div>

		<div class="half">
			<div class="video-box">
				<video onclick="this.paused ? this.play() : this.pause();"
				poster="vidsrc/img2.jpg"><source src="vidsrc/2.mov">
				</video>
			</div>
		</div>

		<div class="half">
			<div class="video-box">
				<video onclick="this.paused ? this.play() : this.pause();"
				poster="vidsrc/img3.jpg"><source src="vidsrc/3.mov">
				</video>
			</div>
		</div>
		
	</body>
</html>
