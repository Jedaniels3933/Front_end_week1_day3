# HTML Forms

## use form element 

```<!DOCTYPE html>
<html>
<body>

<h2>HTML Forms</h2>

##<form> and <input>

<form action="/action_page.php">
  <label for="fname">First name:</label><br> 
  <input type="text" id="fname" name="fname" value="John"><br>
  <label for="lname">Last name:</label><br>
  <input type="text" id="lname" name="lname" value="Doe"><br><br>
  <input type="submit" value="Submit">
</form> 

<p>If you click the "Submit" button, the form-data will be sent to a page called "/action_page.php".</p>

</body>
</html> ```

###HTML Class
-an attribute you assign 
- goes right after <style>

#Auto Complete 
- An HTML form where the username and password does NOT get autocompleted:
  
  <form action="/action_page.php">
  <label for="username">Username:</label>
  <input type="text" id="username" name="username"><br><br>
  <label for="password">Password:</label>
  <input type="password" id="password" name="password" autocomplete="new-password"><br><br>
  <input type="submit">
</form> 

##Example
An HTML form with an input field that can contain only three letters (no numbers or special characters):

<form action="/action_page.php">
  <label for="country_code">Country code:</label>
  <input type="text" id="country_code" name="country_code"
  pattern="[A-Za-z]{3}" title="Three letter country code"><br><br>
  <input type="submit">
</form>








