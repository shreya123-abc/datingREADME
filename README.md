<!DOCTYPE html>
<html>
	<head>
		<title>Dating Site</title>
		<style type="text/css" rel="stylesheet">
			fieldset {
				background-color: #FBE8F7 ;
				border: 10px  #FFEFFE;
				margin-bottom: 10px;
				width:720px;
			}
			label {
				width: 180px;
				display: inline-block;
				text-align: right;
				vertical-align: top;
				margin-bottom: 10px;
			}
			.options {
				width:auto;
			}
			.range-low, .range-high {
				text-align: center;
				color: white;
				display: inline-block;
				width:60px;
				vertical-align: top;
			}
			.range-low {
				background-color: #CAE5FD ;
			}
			.range-high {
				background-color: #E8F3FC ;
			}
			textarea {
				width: 360px;
				height:	50px;
			}
			label:hover, input:hover {
				font-size: 20px;
			}
		</style>				<legend>Your Face</legend>
					<label for="your-image">Your Image:</label><input type="file" required><br />
					<label for="image-preview">Image Preview:</label><img src="" id="preview"><br />
			</fieldset>
	</head>
	<body>
		<h1>MEET YOUR SOULMATE</h1>
		<form action="https://ihome.ust.hk/~rossiter/cgi-bin/show_everything.php" enctype="multipart/form-data" method="post">
			<fieldset>
			</fieldset>
 <TITLE>Activity - Insert animated GIF to HTML</TITLE> </HEAD>
<BODY>
  <IMG SRC="https://media.tenor.com/yPsM6zNRfpcAAAAM/srk-heroes.gif" ;CENTER>
</BODY>
</TITLE>


			<fieldset>
				<legend>Your General Details</legend>
				<label for="name">Name:</label>			<input type="text" name="name" placeholder="Your full name" required><br />
				<label for="gender">Gender:</label>		<input type="radio" name="gender" value="male" required><label for="gender-male" class="options">Male</label><input type="radio" name="gender" value="female"><label for="gender-female" class="options">Female</label><br />
				<label for="age">Age:</label>			<input type="number" name="age" required><br />
				<label for="dob">Date of birth:</label>		<input type="date" name="dob"><br />
				<label for="fav-color">Favorite color:</label>	<input type="color" name="fav-color" value="#000000"><br />
				<label for="country">Which country:</label>
					<select name="country">
						<option value="no-selection">no selection</option>
						<option value="ID">Indonesia</option>
						<option value="IN">India</option>
						<option value="MY">Malaysia</option>
						<option value="UK">United Kingdom</option>
						<option value="US">United States</option>
					</select>
			</fieldset>
			<fieldset>
				<legend>Your Indicators</legend>
				<label for="height">Height:</label>
					<div class="range-low" >Short</div><input type="range" name="height" min="0" max="100"><div class="range-high">Tall</div><br />
				<label for="salary">Salary:</label>
					<div class="range-low">Poor</div><input type="range" name="height" min="0" max="100"><div class="range-high">Rich</div>
			</fieldset>
			<fieldset>
				<legend>Your Contact Information</legend>
				<label for="email">Email:</label><input type="email" name="email" required><br />
				<label for="mobile">Mobile:</label><input type="tel" name="mobile"><br />
				<label for="address">Address:</label><textarea name="address"></textarea><br />
				<label for="method-to-contact">Method to contact you:</label>
					<input type="checkbox">
						<label class="options" for="contact-email">Email</label>
					<input type="checkbox">
						<label class="options" for="contact-whatsapp">WhatsApp</label>
					<input type="checkbox">
						<label  class="options"for="contact-in-app-chat">In-app chat</label>
			</fieldset>
			<input type="submit">
		</form>

	</body>
</html>
