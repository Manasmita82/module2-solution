<!DOCTYPE html>
<html lang="en">
<head>
	<meta charset="utf-8">
	<meta http-equiv="X-UA-Compatiable" content="IE=edge">
	<meta name="viewport" content="width=device-width, initial-scale=1">
<title>Bootstrap Grid</title>
<style>
  
.row {
	margin-bottom: 15px;
	width: 100%;
}
.row > div {
	border: 2px solid red;
	background-color: gray;
}

h1 {
	text-align: center;
}
.col-md-4 {
	background-color: gray;
			padding: 30px 30px 30px 30px;
			border: 10px solid blue;
			margin: 20px;
			width: 400px;
			height: 150px;
			box-sizing:border-box;
			overflow: scroll;
}

p{
			width: 100px;
			height: 20px;
			border: 2px solid black;

		}
			
		#Chicken {
			background-color: pink;
			text-align: center;
			position: absolute;
			float: right;
			margin-top: -30px;
			margin-left: 260px;

			
		}
		#Beef {
			background-color:crimson;
			text-align: center;
			color: ghostwhite;
			position: absolute;
			float: right;
			margin-top: -30px;
			margin-left: 260px;


		}
		#Sushi {
			background-color: lightgoldenrodyellow;
			text-align: center;
			float: right;
			position: absolute;
			margin-top: -30px;
			margin-left: 260px;
		}
</style>
</head>
<body>
	<h1>Our Menu</h1>
<div class="container-fluid">
	<div class="row">
		<div class="col-md-4 col-sm-6"><p id="Chicken">Chicken</p>
			<div>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</div></div>
		<div class="col-md-4 col-sm-6"><p id="Beef">Beef</p>	
			<div>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</div></div>
		<div class="col-md-4 col-sm-6"><p id="Sushi">Sushi</p>	
			<div>"Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur. Excepteur sint occaecat cupidatat non proident, sunt in culpa qui officia deserunt mollit anim id est laborum."</div></div>
	</div>

</div>
<script src="js/jquery-3.7.1.min.js"></script>
<script src="js/bootstrap.min.js"></script>
<script src="js/script.js"></script>
</body>
</html>
