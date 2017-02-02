<!DOCTYPE html>
<html>
<head>
	<title>Css Style</title>
	<style>
body{
	background-color: lightblue;
}	
</style>
</head>

<body>
<form action="http://www.example.com/review.php" method="get">
			<fieldset>
				<h6>Step 1: Your Details<h6>
				<label>Name: <input type="text" name="name" size="30" maxlength="100" placeholder="First And Last Name"></label><br />
				<label>Email: <input type="email" name="email" size="30" maxlength="100" placeholder="example@domain.com"></label><br />
				<label>Phone Number: <input type="Number" name="Number" size="30" maxlength="100" placeholder="e.g.+04499999"></label><br />
				<br />
				<h6>Step 1: Delivery Address<h6>
				<p>
					<label for="comments">Addrss:</label><br />
					<textarea rows="4" cols="40" id="comments"></textarea>
				</p>
				<label>Pin Code: <input type="Number" name="Number" size="30" maxlength="100"></label><br />
				<label>Contry: <input type="text" name="text" size="30" maxlength="100"></label><br />
				<br />
				<h6>Step 1: Card Details<h6>
				<p>
					Card Type <br />
					<label><input type="radio" name="Card" value="Visa" /> Visa</label>
					<label><input type="radio" name="Card" value="Master" /> Master</label>
					<label><input type="radio" name="Card" value="Mastro" /> Mastro</label>
				</p>
				<label>Card Name: <input type="text" name="name" size="30" maxlength="100"></label><br />
				<label>Security Code: <input type="Number" name="Number" size="30" maxlength="100"></label><br />
				<label>Name On Card: <input type="text" name="name" size="30" maxlength="100"></label><br />
				<button onclick="myFunction()">BUY!</button>
			</fieldset>

		</form>


</body>
</html>
