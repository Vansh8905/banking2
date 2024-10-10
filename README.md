<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>TATA BANK</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <header>
            <div class="auth-buttons">
                <a href="login.html" class="button">Login</a>
                <a href="register.html" class="button">Register</a>
            </div>
            <h1>TATA BANK</h1>
            
        </header>
        
        <main>
            <section class="account-cards">
                <div class="card" onclick="showDetails('savings')">
                    <img src="image.png" alt="Savings Account">
                    <h2>Savings Account</h2>
                    <p>Grow your savings with competitive interest rates.</p>
                </div>
                <div class="card" onclick="showDetails('current')">
                    <img src="image.png" alt="Current Account">
                    <h2>Current Account</h2>
                    <p>Manage your business transactions with ease.</p>
                </div>
                <div class="card" onclick="showDetails('salary')">
                    <img src="image.png" alt="Salary Account">
                    <h2>Salary Account</h2>
                    <p>Specialized accounts for employees with exclusive benefits.</p>
                </div>
            </section>
        </main>
    </div>

    <script>
        function showDetails(accountType) {
            let message = "";
            if (accountType === 'savings') {
                message = "Savings Account: Enjoy higher interest rates and flexible access to your funds.";
            } else if (accountType === 'current') {
                message = "Current Account: Ideal for businesses, offering overdraft and checkbook facilities.";
            } else if (accountType === 'salary') {
                message = "Salary Account: Exclusive benefits for employees, including lower fees and more.";
            }
            alert(message);
        }
    </script>
</body>
</html>
