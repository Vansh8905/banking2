<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Register</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <form id="registrationForm">
        <h2>Create Account</h2>
        <label for="ssn">Customer SSN ID</label>
        <input type="text" id="ssn" required>
        
        <label for="firstName">First Name</label>
        <input type="text" id="firstName" maxlength="50" required>
        
        <label for="lastName">Last Name</label>
        <input type="text" id="lastName" maxlength="50" required>
        
        <label for="email">Email</label>
        <input type="email" id="email" required>
        
        <label for="password">Password</label>
        <input type="password" id="password" maxlength="30" required>
        
        <label for="confirmPassword">Confirm Password</label>
        <input type="password" id="confirmPassword" maxlength="30" required>
        
        <label for="address">Address</label>
        <textarea id="address" maxlength="100"></textarea>
        
        <label for="contactNumber">Contact Number</label>
        <input type="text" id="contactNumber" maxlength="10" required>
        
        <button type="button" onclick="register()">Register</button>
    </form>
    <div id="acknowledgment" style="display:none;"></div>
    <script src="script.js"></script>
</body>
</html>


