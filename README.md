// Initialize balance variable
let balance = 10000; // Initial balance

// Function for user registration
function register() {
    const password = document.getElementById('password').value;
    const confirmPassword = document.getElementById('confirmPassword').value;

    // Validate password
    if (password !== confirmPassword) {
        alert("Passwords do not match.");
        return;
    }

    const customerId = 'US001' + Math.floor(Math.random() * 10000);
    const name = document.getElementById('firstName').value + ' ' + document.getElementById('lastName').value;

    // Display acknowledgment
    document.getElementById('acknowledgment').innerHTML = `
        <h3 style="color: green;">Customer Registration successful.</h3>
        <p>Customer Account ID: ${customerId}</p>
        <p>Customer Name: ${name}</p>
    `;
    document.getElementById('acknowledgment').style.display = 'block';

    // Redirect to login after 3 seconds
    setTimeout(() => {
        location.href = 'login.html';
    }, 3000);
}

// Function for user login
function login() {
    // Mock login validation (implement actual validation as needed)
    alert("Customer login successful.");
    location.href = 'home.html'; // Redirect to Home Page
}

// Function to create account (not implemented)
function createAccount() {
    alert("Account creation functionality not implemented.");
}

// Function for depositing amount
function deposit() {
    const amount = prompt("Enter amount to deposit:");
    if (amount && !isNaN(amount) && parseInt(amount) > 0) {
        balance += parseInt(amount);
        alert(`Deposited: ${amount}. New Balance: ${balance}`);
    } else {
        alert("Please enter a valid amount.");
    }
}

// Function for withdrawing money
function withdraw() {
    const amount = prompt("Enter amount to withdraw:");
    if (amount && !isNaN(amount) && parseInt(amount) >= 1000) {
        const withdrawalAmount = parseInt(amount);
        if (balance - withdrawalAmount < 500) {
            alert("Minimum balance should be 500 after withdrawal.");
        } else {
            balance -= withdrawalAmount;
            alert(`Withdrawn: ${withdrawalAmount}. New Balance: ${balance}`);
        }
    } else {
        alert("Minimum amount that can be withdrawn is 1000.");
    }
}

// Function to check balance
function checkBalance() {
    alert(`Current Balance: ${balance}`);
}
