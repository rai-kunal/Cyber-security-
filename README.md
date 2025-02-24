# Cyber-security-
This is a simple webpage of cuber security providing company
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Knock Out - Cyber Security</title>
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            font-family: 'Arial', sans-serif;
        }
        body {
            background-color: #0a192f;
            color: #ccd6f6;
        }
        header {
            background-color: #112240;
            padding: 20px;
            text-align: center;
        }
        nav {
            display: flex;
            justify-content: center;
            gap: 30px;
            padding: 15px 0;
        }
        nav a {
            color: #64ffda;
            text-decoration: none;
            font-size: 18px;
            padding: 10px 15px;
            transition: 0.3s;
        }
        nav a:hover {
            color: #8892b0;
            border-bottom: 2px solid #64ffda;
        }
        .container {
            padding: 50px 20px;
            text-align: center;
        }
        footer {
            background-color: #112240;
            padding: 20px;
            text-align: center;
            margin-top: 30px;
        }
        @media (max-width: 768px) {
            nav {
                flex-direction: column;
            }
        }
    </style>
</head>
<body>
    <header>
        <h1>Knock Out - Cyber Security</h1>
        <nav>
            <a href="#home">Home</a>
            <a href="#about">About</a>
            <a href="#contact">Contact Us</a>
        </nav>
    </header>
    <div class="container" id="home">
        <h2>Welcome to Knock Out</h2>
        <p>Advanced Cyber Security Solutions to Keep You Safe</p>
    </div>
    <div class="container" id="about">
        <h2>About Us</h2>
        <p>We are dedicated to protecting businesses and individuals from cyber threats through innovative solutions.</p>
    </div>
    <div class="container" id="contact">
        <h2>Contact Us</h2>
        <p>Email: support@knockout.com</p>
        <p>Phone: +91 8262902899</p>
    </div>
    <footer>
        <p>&copy; 2025 Knock Out - All Rights Reserved</p>
    </footer>
</body>
</html>
