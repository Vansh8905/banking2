/* General Styles */
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #e9ecef; /* Light background color */
    color: #333;
}

h1, h2, h3 {
    text-align: center;
}

/* Navigation Styles */
nav {
    background-color: #0044cc;
    padding: 15px;
    color: white;
    text-align: center;
}

nav button {
    background-color: #007bff;
    border: none;
    color: white;
    padding: 10px 20px;
    margin: 5px;
    cursor: pointer;
    border-radius: 5px;
    transition: background-color 0.3s;
}

nav button:hover {
    background-color: #0056b3;
}

/* Content Styles */
.content {
    text-align: center;
    padding: 20px;
    margin: 20px;
}

.content img {
    max-width: 100%;
    height: auto;
    margin: 20px 0;
}

/* Form Styles */
form {
    background-color: white;
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
    max-width: 400px;
    margin: 20px auto;
}

label {
    display: block;
    margin: 10px 0 5px;
    font-weight: bold;
    color: #333;
}

input, textarea {
    display: block;
    margin: 10px auto;
    padding: 10px;
    width: calc(100% - 22px); /* Adjust for padding */
    border: 1px solid #ccc;
    border-radius: 5px;
    font-size: 16px;
    background-color: #f8f9fa; /* Light background for inputs */
}

input:focus, textarea:focus {
    border-color: #007bff;
    outline: none;
    background-color: #ffffff; /* White background on focus */
}

/* Acknowledgment Styles */
#acknowledgment {
    background-color: #d4edda;
    color: #155724;
    border: 1px solid #c3e6cb;
    padding: 15px;
    border-radius: 5px;
    margin: 20px auto;
    max-width: 400px;
    display: none; /* Hidden by default */
}

/* Button Styles */
button[type="button"] {
    background-color: #28a745; /* Green for main actions */
    border: none;
    color: white;
    padding: 10px 20px;
    margin: 10px auto;
    cursor: pointer;
    border-radius: 5px;
    transition: background-color 0.3s;
    width: 100%;
}

button[type="button"]:hover {
    background-color: #218838;
}

/* Home Page Styles */
h2 {
    margin-top: 20px;
}

button {
    width: 100%;
}
