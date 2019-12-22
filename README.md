<html>
<head>
<style>
body
	width 100%
	height 100%
	min-height 100vh
	margin 0
	font-family 'Work Sans', sans-serif
	font-weight 400

.background
	width 100%
	height 100%
	min-height 100vh
	position fixed
	top 0
	left 0
	z-index -1
	background rgb(167,65,255)
	background -moz-linear-gradient(top, rgba(167,65,255,1) 0%, rgba(84,128,253,1) 100%)
	background -webkit-linear-gradient(top, rgba(167,65,255,1) 0%,rgba(84,128,253,1) 100%)
	background linear-gradient(to bottom, rgba(167,65,255,1) 0%,rgba(84,128,253,1) 100%)

.wrapper
	width 80%
	height 100%
	min-height 800px
	background #FFF
	position absolute
	left 50%
	top 0
	margin 60px 0
	transform translate(-50%,0)
	-webkit-transform translate(-50%,0)
	-moz-transform translate(-50%,0)
	-webkit-box-shadow 0px 0px 30px 5px rgba(0,0,0,0.15)
	-moz-box-shadow 0px 0px 30px 5px rgba(0,0,0,0.15)
	box-shadow 0px 0px 30px 5px rgba(0,0,0,0.15)
	.header
		width 100%
		height 100%
		position absolute
		top 0
		left 0
		background rgb(129,162,255)
		background -moz-linear-gradient(top, rgba(129,162,255,1) 0%, rgba(193,225,255,1) 100%)
		background -webkit-linear-gradient(top, rgba(129,162,255,1) 0%,rgba(193,225,255,1) 100%)
		background linear-gradient(to bottom, rgba(129,162,255,1) 0%,rgba(193,225,255,1) 100%)
		overflow hidden
		.logo
			width 50px
			height auto
			position absolute
			top 50px
			left 100px
		.menu
			list-style none
			margin 0
			padding 0
			line-height 33px
			position absolute
			top 50px
			right 100px
			text-align right
			width auto
			li
				display inline-block
				margin 0 10px
				color #FFF
		.content
			position absolute
			width 100%
			height auto
			max-width 800px
			top 50%
			left 50%
			transform translate(-50%,-85%)
			h2
				color #FFF
				margin 0
				font-size 2.3em
				line-height 1.2em
				width 100%
				text-align center
			.buttons
				width 100%
				text-align center
				margin 0
				padding 0
			.button
				display inline-block
				width 150px
				height 50px
				padding-left 20px
				background #000
				color #FFF
				font-size 1.2em
				text-decoration none
				text-align center
				line-height 50px
				margin 40px 5px 0
				-moz-border-radius 5px
				-webkit-border-radius 5px
				border-radius 5px
				-webkit-box-shadow 0px 12px 20px -10px rgba(0,0,0,0.65)
				-moz-box-shadow 0px 12px 20px -10px rgba(0,0,0,0.65)
				box-shadow 0px 12px 20px -10px rgba(0,0,0,0.65)
				transition box-shadow 0.5s
				&:hover
					-webkit-box-shadow 0px 0px 20px -10px rgba(0,0,0,0.65)
					-moz-box-shadow 0px 0px 20px -10px rgba(0,0,0,0.65)
					box-shadow 0px 0px 20px -10px rgba(0,0,0,0.65)
					transition box-shadow 0.5s
				&.apple
					background-image url('http://vignette2.wikia.nocookie.net/respawnables/images/2/2f/Apple-logo-white-md.png/revision/latest?cb=20160224124036')
					background-size 20px auto
					background-repeat no-repeat
					background-position 20px center
				&.google
					background-image url('http://vignette3.wikia.nocookie.net/starwars/images/e/ee/Google_Play_logo.png/revision/latest?cb=20141119230612')
					background-size 20px auto
					background-repeat no-repeat
					background-position 20px center
		.waves
			width calc(100% + 10px)
			height auto
			position absolute
			bottom -3px
			left 50%
			transform translate(-50%,0)
			-webkit-transform translate(-50%,0)
			-moz-transform translate(-50%,0)
			z-index 0
		.curve
			display none
			width calc(100% + 10px)
			height auto
			position absolute
			bottom -1px
			left 50%
			transform translate(-50%,0)
			-webkit-transform translate(-50%,0)
			-moz-transform translate(-50%,0)
			z-index 1
      </style>
      </head>
      <body>
      
<div class="wrapper">
	<div class="header">
		<ul class="menu">
			<li>News</li>
			<li>Features</li>
			<li>How it works</li>
			<li>Blog</li>
		</ul>
		<div class="content">
			<h2>Combine your Spotify, Soundcloud. iTunes, Deezer and YouTube into one giant music library</h2>
			<div class="buttons">
				<a class="button apple" href="#">App Store</a>
				<a class="button google" href="#">Google play</a>
			</div>
		</div>
		<img class="logo" src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/626071/line-logo.svg">
		<img class="curve" src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/626071/bottom-curve_copy.svg">
		<img class="waves" src="https://s3-us-west-2.amazonaws.com/s.cdpn.io/626071/waves_copy.svg">
	</div>
</div>
<div class="background"></div>
</body>
</html>
