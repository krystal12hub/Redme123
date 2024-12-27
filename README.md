<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Scholarship Information</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Scholarship Information</h1>
        <nav>
            <ul>
                <li><a href="#home">Home</a></li>
                <li><a href="#about">About</a></li>
                <li><a href="#scholarships">Scholarships</a></li>
                <li><a href="#contact">Contact</a></li>
            </ul>
        </nav>
    </header>

    <section id="home">
        <h2>Welcome to the Scholarship Information Website</h2>
        <p>Your one-stop destination for finding scholarships that suit your needs.</p>
    </section>

    <section id="about">
        <h2>About Us</h2>
        <p>We provide up-to-date information about various scholarships available for students.</p>
    </section>

    <section id="scholarships">
        <h2>Available Scholarships</h2>
        <ul>
            <li>Scholarship 1: <a href="#">Details</a></li>
            <li>Scholarship 2: <a href="#">Details</a></li>
            <li>Scholarship 3: <a href="#">Details</a></li>
        </ul>
    </section>

    <section id="contact">
        <h2>Contact Us</h2>
        <form action="#" method="post">
            <label for="name">Name:</label>
            <input type="text" id="name" name="name" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="message">Message:</label>
            <textarea id="message" name="message" required></textarea>
            <button type="submit">Submit</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2024 Scholarship Information. All rights reserved.</p>
    </footer>
    <script src="scripts.js"></script>
</body>
</html> 
body {
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    background-color: #f4f4f4;
}

header {
    background-color: #333;
    color: #fff;
    padding: 1em 0;
    text-align: center;
}

header nav ul {
    list-style: none;
    padding: 0;
}

header nav ul li {
    display: inline;
    margin: 0 15px;
}

header nav ul li a {
    color: #fff;
    text-decoration: none;
}

section {
    padding: 2em;
    margin: 10px;
    background-color: #fff;
    border-radius: 5px;
}

footer {
    background-color: #333;
    color: #fff;
    text-align: center;
    padding: 1em 0;
    position: fixed;
    width: 100%;
    bottom: 0;
}

input, textarea {
    width: 100%;
    padding: 10px;
    margin: 5px 0 20px 0;
    border: 1px solid #ccc;
    border-radius: 5px;
}

button {
    padding: 10px 20px;
    background-color: #333;
    color: #fff;
    border: none;
    border-radius: 5px;
    cursor: pointer;
}

button:hover {
    background-color: #555;
} 

// For now, we will keep this file empty.
// You can add JavaScript code here to handle form submission, dynamic content loading, etc.
