# webpageUI.github.io<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Login Page</title>
    <link rel="stylesheet" href="styles.css">
    <style>
        /* styles.css */
        body {
            background-image: url('C:\Users\harsh\OneDrive\Pictures\ganesh.jpg'); /* Set your background image here */
            background-size: cover;
            background-repeat: no-repeat;
            background-attachment: fixed; /* Keeps the image fixed while scrolling */
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;

            background-color: aquamarine;
        }

        .login-container {
    background-color: #007BFF; /* Updated background color to a vibrant blue */
    padding: 30px;
    border-radius: 10px; /* Increased border-radius for a rounded appearance */
    box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1); /* A slightly lifted box shadow */
    text-align: center;
    width: 300px;
    margin: 0 auto; /* Center the container horizontally */
    color: #fff; /* Text color */
}

.login-container h2 {
    color: #333; /* Heading color */
}

.login-form {
    margin-top: 20px;
}

.login-form label {
    display: block;
    text-align: left;
    margin-bottom: 5px;
}

.login-form input[type="text"],
.login-form input[type="password"] {
    width: 100%;
    padding: 10px;
    margin-bottom: 10px;
    border: 1px solid #ccc;
    border-radius: 3px;
}

.login-form button {
    background-color: #ff6600;
    color: #fff;
    padding: 12px 20px; /* Increased padding for the button */
    border: none;
    border-radius: 5px;
    cursor: pointer;
    font-weight: bold; /* Added font weight for emphasis */
    transition: background-color 0.3s; /* Smooth color transition on hover */
}

.login-form button:hover {
    background-color: #ff4500; /* Change the button color on hover */
}

/* Adjusted link styles for better visibility */
.login-container a {
    color: #007BFF;
    text-decoration: none;
    font-weight: bold;
}

.login-container a:hover {
    text-decoration: underline;
}
/* Add this CSS to style the "Create Account" link */
.login-container p a {
    color: #007BFF; /* Link text color */
    text-decoration: none; /* Remove underlines */
    font-weight: bold; /* Make the link text bold */
    transition: color 0.3s; /* Smooth color transition on hover */
}

.login-container p a:hover {
    color: #0056b3; /* Change the link color on hover */
    text-decoration: underline; /* Add underlines on hover */
}




 </style>
</head>
<body>
    <div class="login-container">
        <h2>Login</h2>
        <form class="login-form" id="login-form">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required>
            <br>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
            <br>
            <button type="submit">Login</button>
        </form>
        <p>Don't have an account? <a href="Create accont.html">Create Account</a></p>
    </div>

    <script>
        document.getElementById("login-form").addEventListener("submit", function (e) {
            e.preventDefault();

            const username = document.getElementById("username").value;
            const password = document.getElementById("password").value;

            // Replace with your actual login logic
            if (username === "darshan" && password === "7338541530") {
                window.location.href = "house desgn.html"; // Adjust the URL as needed
            } else {
                alert("Invalid username or password. Please try again.");
            }
        });
    </script>
</body>
</html>


