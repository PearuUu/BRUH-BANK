# BRUH-BANK
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>BRUH. BANK S.A.</title>
	<style>

		body {
			background-color: #121212;
			font-family: impact;
			margin-bottom: 50px;
		}

		header {
			background-color: #1E1E1E;
			margin: 10px;
			padding: 15px;
			color: #545454;
			font-size: 55px;
			border-radius: 12px;
		}

		.header_buttons {
			border-color: #545454;
			background-color: #1E1E1E;
			color: #545454;
			border-radius: 12px;
			font-size: 35px;
			border-width: 4px;
			border-style: solid;
			padding: 5px;
			font-family: impact;
			float: right;
			margin: 3px 0px 0px 20px;
			transition-duration: 0.3s;
		}

		.header_buttons:hover {
			background-color: #717171;
		}

		.option_buttons {
			border-color: #545454;
			background-color: #1E1E1E;
			color: #545454;
			border-radius: 12px;
			font-size: 35px;
			border-width: 4px;
			border-style: solid;
			padding: 5px;
			font-family: impact;
			transition-duration: 0.3s;
			width: 95%;
		}

		.option_buttons:hover {
			background-color: #717171;
		}

		img {
			border-color: #545454;
			border-radius: 12px;
			border-width: 4px;
			border-style: solid;
			width: 45%;
			height: auto;
		}

		a {
			text-decoration: none;
			color: inherit;
		}

		article {
			background-color: #1E1E1E;
			margin: 10px;
			padding: 15px;
			color: #545454;
			font-size: 35px;
			border-radius: 12px;
			display: flex;
		}

		footer, #news {
			background-color: #1E1E1E;
			margin: 10px;
			padding: 15px;
			color: #545454;
			font-size: 35px;
			border-radius: 12px;
		}

		.logo {
			border-color: #545454;
			border-radius: 12px;
			border-width: 4px;
			border-style: solid;
			margin-left: 20px;
			width: 40px;
			height: 40px;
			float: right;
			background-color: #545454;
		}

		p {
			margin-left: 35px;
		}

		.oferta {
			border-color: #545454;
			background-color: #1E1E1E;
			color: #545454;
			border-radius: 12px;
			font-size: 35px;
			border-width: 4px;
			border-style: solid;
			padding: 5px;
			font-family: impact;
			margin-left: 20px;
			width: 30%;
			padding: 15px;
		}

		ul, ol, li, dl, dd {
			font-size: 20px;
			font-family: impact;
		}

		dt {
			font-size: 25px;
			font-family: impact;
		}

		marquee {
			direction: left;
			height: auto;
		}

		.credit_cards {
			border-color: #545454;
			border-radius: 12px;
			border-width: 4px;
			border-style: solid;
			width: 20%;
		}

		#ubezpieczenie, #rates {
			background-color: #1E1E1E;
			margin: 10px;
			padding: 15px;
			color: #545454;
			font-size: 35px;
			border-radius: 12px;
		}

		#cards {
			border-color: #545454;
			border-radius: 12px;
			border-width: 4px;
			border-style: solid;
			background-color: #1E1E1E;
			padding: 15px;
			color: #545454;
			font-size: 35px;
			width: 50%;
			margin-left: 15px;
		}

		.center {
			margin-top: 10px;
			display: flex;
			justify-content: space-around;
		}

		.insurance {
			border-color: #545454;
			background-color: #1E1E1E;
			color: #545454;
			border-radius: 12px;
			font-size: 30px;
			border-width: 4px;
			border-style: solid;
			padding: 5px;
			font-family: impact;
			width: 17%;
			padding: 15px;
		}

		.insurance_desc {
			color: #545454;
			font-size: 20px;
			font-family: impact;
		}

		.registration {
			border-color: #545454;
			background-color: #1E1E1E;
			color: #545454;
			border-radius: 12px;
			font-size: 35px;
			border-width: 4px;
			border-style: solid;
			padding: 15px;
			font-family: impact;
			width: 30%;
		}

		::-webkit-scrollbar {
		  width: 10px;
		}

		::-webkit-scrollbar-track {
		  background: #121212; 
		}

		::-webkit-scrollbar-thumb {
		  background: #545454; 
		}

		::-webkit-scrollbar-thumb:hover {
		  background: #717171; 
		}

		input::-webkit-outer-spin-button,
		input::-webkit-inner-spin-button {
		  -webkit-appearance: none;
		  margin: 0;
		}

		input[type=number] {
		  -moz-appearance: textfield;
		}

		input:focus{
		   outline: none;
		}

		*focus {
			outline: none;
		}

		#article2 {
			background-color: #1E1E1E;
			margin: 10px;
			padding: 15px;
			color: #545454;
			font-size: 35px;
			border-radius: 12px;
			display: flex;
			justify-content: space-around;
		}

		#article3 {
			background-color: #1E1E1E;
			margin: 10px;
			padding: 15px;
			color: #545454;
			font-size: 35px;
			border-radius: 12px;
			align-items: center;
			height: 500px;
			position: relative;
			justify-content: space-around;
		}

		#article4 {
			background-color: #1E1E1E;
			margin: 10px;
			padding: 15px;
			color: #545454;
			font-size: 35px;
			border-radius: 12px;
		}

		#article5 {
			background-color: #1E1E1E;
			margin: 10px;
			padding: 15px;
			color: #545454;
			font-size: 35px;
			border-radius: 12px;
		}



		input[type=text], input[type=password], input[type=number], input[type=email] {
			border-radius: 12px;
			border-width: 4px;
			border-style: solid;
			border-color: #545454;
			background-color: #1E1E1E;
			font-size: 35px;
			font-family: impact;
			color: #545454;
			padding: 5px;
			width: 96.5%;
		}

		input:focus {
			background-color: #717171;
		}


		.hr {
			border: 4px solid #545454;
		}

		input[type=submit] {
			border-color: #545454;
			background-color: #1E1E1E;
			color: #545454;
			border-radius: 12px;
			font-size: 35px;
			border-width: 4px;
			border-style: solid;
			font-family: impact;
			margin: 3px 0px 0px 20px;
			transition-duration: 0.3s;
			padding: 5px;
			float: right;
		}

		input:hover[type=submit] {
			background-color: #717171;
		}

		#login {
			border-color: #545454;
			background-color: #1E1E1E;
			color: #545454;
			border-radius: 12px;
			font-size: 35px;
			border-width: 4px;
			border-style: solid;
			padding: 15px;
			font-family: impact;
			width: 30%;
			height: 45%;
			position: absolute;
			left: 34%;
		}

		#post_register {
			border-color: #1E1E1E;
			background-color: #1E1E1E;
			color: #545454;
			border-radius: 12px;
			font-size: 35px;
			border-width: 4px;
			border-style: solid;
			font-family: impact;
			width: auto;
		}

		#stan_konta {
			border-color: #545454;
			background-color: #1E1E1E;
			color: #545454;
			border-radius: 12px;
			font-size: 35px;
			border-width: 4px;
			border-style: solid;
			font-family: impact;
			width: 23%;
			padding: 15px;
		}

		#history {
			border-color: #545454;
			background-color: #1E1E1E;
			color: #545454;
			border-radius: 12px;
			font-size: 35px;
			border-width: 4px;
			border-style: solid;
			padding: 15px;
			font-family: impact;
			width: 23%;
			float: right;
		}

		.staty {
			border-color: #545454;
			background-color: #1E1E1E;
			color: #545454;
			border-radius: 12px;
			font-size: 35px;
			border-width: 4px;
			border-style: solid;
			padding: 15px;
			font-family: impact;
			width: auto;
		}

		.stats {
			width: 23%;
			padding: 15px;
		}

		.options {
			border-color: #545454;
			background-color: #1E1E1E;
			color: #545454;
			border-radius: 12px;
			font-size: 35px;
			border-width: 4px;
			border-style: solid;
			font-family: impact;
			width: auto;
		}

		.opcje {
			width: 23%;
			padding: 15px;
			display: flex;
		  justify-content: space-around;
		  flex-direction: column;
		}

		.container {
			display: block;
			position: relative;
			padding-left: 35px;
			cursor: pointer;
			font-size: 35px;
			-webkit-user-select: none;
		  -moz-user-select: none;
		  -ms-user-select: none;
		  user-select: none;
		}

		.container input {
		  position: absolute;
		  opacity: 0;
		  cursor: pointer;
		}

		.checkmark {
			position: absolute;
			top:  7px;
			left: 0;
			height: 25px;
			width: 25px;
			background-color: #545454;
			border-radius: 12px;
		}

		.container:hover input ~ .checkmark {
		  background-color: #121212;
		}

		.container input:checked ~ .checkmark {
		  background-color: #545454;
		}

		.checkmark:after {
		  content: "";
		  position: absolute;
		  display: none;
		}

		.container input:checked ~ .checkmark:after {
		  display: block;
		}

		.container .checkmark:after {
			top: 9px;
			left: 9px;
			width: 8px;
			height: 8px;
			border-radius: 50%;
			background: #1E1E1E;
		}

		#article5, #article6 {
			padding: 15px;
			display: flex;
			justify-content: center;
		}

		#center {
			font-size: 40px;
			font-family: impact;
			margin: 20%;
			background-color: #121212;
			color: #545454;
		}

		#order_card, #send_money {
			border-color: #545454;
			background-color: #1E1E1E;
			color: #545454;
			border-radius: 12px;
			font-size: 35px;
			border-width: 4px;
			border-style: solid;
			font-family: impact;
			width: auto;
			padding: 15px;
		}

		.custom-select {
			position: relative;
			font-family: impact;
			font-size: 35px;
		}

		.custom-select select {
			display: none;
		}

		.select-selected {
			background-color: #1E1E1E;
		}

		.select-selected:after {
		  position: absolute;
		  content: "";
		  top: 15px;
		  right: 15px;
		  width: 5;
		  height: 5;
		  border: 4px;
		  border-style: solid;
		  border-color: #545454;
		}

		.select-selected.select-arrow-active:after {
		  border-color: #545454;
		  top: 15px;
		}

		.select-items div,.select-selected {
		  color: #545454;
		  padding: 5px;
		  border: 4px;
		  border-style: solid;
		  border-color: #545454;
		  border-radius: 12px;
		  cursor: pointer;
		  user-select: none;
		}

		.select-items {
		  position: absolute;
		  background-color: #1E1E1E;
		  top: 100%;
		  left: 0;
		  right: 0;
		  z-index: 99;
		  transition-duration: 0.3s;
		}

		.select-hide {
		  display: none;
		}

		.select-items div:hover, .same-as-selected {
		  background-color: #717171;
		}

	</style>
	<link rel="icon" href="logo_icons/bank_logo.png">
</head>
<body>
	<footer>
		&copy; 2021 BRUH. BANK S.A. Wszelkie prawa zastrzeżone.
		<a href="https://youtu.be/dQw4w9WgXcQ" target="_blank"><img class="logo" src="logo_icons/yt_logo.png" alt="yt_logo"></a>
		<a href="https://www.reddit.com/" target="_blank"><img class="logo" src="logo_icons/reddit_logo.png" alt="reddit_logo"></a>
		<a href="https://pl.linkedin.com/" target="_blank"><img class="logo" src="logo_icons/linkedin_logo.png" alt="linkedin_logo"></a>
		<a href="https://twitter.com/?lang=pl" target="_blank"><img class="logo" src="logo_icons/twitter_logo.png" alt="twitter_logo"></a>
		<a href="https://www.instagram.com/bruh.bank.official/" target="_blank"><img class="logo" src="logo_icons/instagram_logo.png" alt="ig_logo"></a>
		<a href="https://pl-pl.facebook.com/" target="_blank"><img class="logo" src="logo_icons/fb_logo.png" alt="fb_logo"></a>
	</footer>
</body>
</html>
