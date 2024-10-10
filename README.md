* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}

body {
    font-family: Arial, sans-serif;
    background-image: url('image1.png');
    background-size: cover;
    background-position: center;
    color: white;
}

.container {
    text-align: center;
    height: 100vh;
    display: flex;
    flex-direction: column;
    justify-content: center;
}

header {
    position: relative;
    margin-bottom: 40px;
    padding-top: 150px; 
}

.auth-buttons {
    position: absolute;
    top: 70px;
    right: 20px;
}

.button {
    background-color: #007bff;
    color: white;
    padding: 10px 20px;
    text-decoration: none;
    border-radius: 5px;
    margin: 0 10px;
    transition: background-color 0.3s;
}

.button:hover {
    background-color: #0056b3;
}

h1 {
    font-size: 100px;
    margin: 40px 0;
    color: #000000; 
}



.account-cards {
    display: flex;
    justify-content: center;
    gap: 20px;
}

.card {
    background: rgba(0, 0, 0, 0.7);
    border-radius: 10px;
    padding: 20px;
    width: 300px;
    cursor: pointer;
    transition: transform 0.3s;
}

.card img {
    width: 100%;
    border-radius: 10px 10px 0 0;
}

.card:hover {
    transform: scale(1.05);
}

h2 {
    margin: 15px 0;
}

p {
    font-size: 16px;
}
