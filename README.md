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
        <input type="text" id="ssn" placeholder="Customer SSN ID" required>
        <input type="text" id="firstName" placeholder="First Name" maxlength="50" required>
        <input type="text" id="lastName" placeholder="Last Name" maxlength="50" required>
        <input type="email" id="email" placeholder="Email" required>
        <input type="password" id="password" placeholder="Password" maxlength="30" required>
        <input type="password" id="confirmPassword" placeholder="Confirm Password" maxlength="30" required>
        <textarea id="address" placeholder="Address" maxlength="100"></textarea>
        <input type="text" id="contactNumber" placeholder="Contact Number" maxlength="10" required>
        <button type="button" onclick="register()">Register</button>
    </form>
    <div id="acknowledgment" style="display:none;"></div>
    <script src="script.js"></script>
</body>
</html>

