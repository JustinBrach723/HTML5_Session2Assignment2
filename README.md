<!DOCTYPE html>
<html>
<head>
	<title>HTML Basic Tags</title>
</head>
<body>
	<fieldset>
		<legend>Contact Information:</legend>
			Name: <input type="text" name=""><br>
			Email: <input type="text" name="">
	</fieldset>
	<fieldset>
		<legend>What are you interested in?</legend><br>
		<select name="options">
			<option value="opt_development">Development</option>
			<option value="opt_training" selected>Training</option>
			<option value="opt_other">Other</option>
		</select><br><br>
		Comments:<br>
		<textarea cols="45" rows="15"></textarea><br><br>
		<input type="checkbox" name=""> Have someone give me a call </input><br><br>
		<input type="submit" name="" value="Submit Request"></input>
	</fieldset>
</body>
</html>
