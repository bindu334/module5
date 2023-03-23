<!DOCTYPE html>
<html>
<head>
	<title>Login Page</title>
	<meta charset="UTF-8">
	<meta name="viewport" content="width=device-width, initial-scale=1.0">
	<style>
		body {
			font-family: Arial, sans-serif;
			background-color: #f2f2f2;
		}
		form {
			background-color: white;
			padding: 20px;
			border-radius: 5px;
			box-shadow: 0px 0px 10px grey;
			max-width: 500px;
			margin: 0 auto;
			margin-top: 50px;
		}
		input[type=text], input[type=password] {
			padding: 10px;
			margin: 5px 0 20px 0;
			display: block;
			width: 100%;
			border: none;
			border-radius: 5px;
			box-shadow: 0px 0px 5px grey;
		}
		button {
			background-color: #4CAF50;
			color: white;
			padding: 10px 20px;
			border: none;
			border-radius: 5px;
			cursor: pointer;
			margin-bottom: 10px;
		}
		button:hover {
			background-color: #45a049;
		}
	</style>
</head>
<body>
	<form>
		<h2>Login</h2>
		<label for="username"><b>Username</b></label>
		<input type="text" placeholder="Enter Username" name="username" required>

		<label for="password"><b>Password</b></label>
		<input type="password" placeholder="Enter Password" name="password" required>

		<button type="submit">Login</button>
		<label>
			<input type="checkbox" checked="checked" name="remember"> Remember me
		</label>
	</form>
</body>
</html>
