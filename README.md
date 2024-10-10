<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <form id="loginForm">
        <h2>Login</h2>
        <label for="accountNumber">Customer Account Number</label>
        <input type="text" id="accountNumber" required>
        
        <label for="loginPassword">Password</label>
        <input type="password" id="loginPassword" maxlength="30" required>
        
        <button type="button" onclick="login()">Login</button>
    </form>
    <script src="script.js"></script>
</body>
</html>



