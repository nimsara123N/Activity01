# Register Page and Login Page

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Cyber Hacking Website</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Welcome to the Cyber Hacking Website</h1>
    </header>

    <section id="register">
        <h2>Register</h2>
        <form action="/register" method="POST">
            <label for="username">Username:</label>
            <input type="text" id="username" name="username" required>
            <label for="email">Email:</label>
            <input type="email" id="email" name="email" required>
            <label for="password">Password:</label>
            <input type="password" id="password" name="password" required>
            <button type="submit">Register</button>
        </form>
    </section>

    <section id="login">
        <h2>Login</h2>
        <form action="/login" method="POST">
            <label for="login-username">Username:</label>
            <input type="text" id="login-username" name="username" required>
            <label for="login-password">Password:</label>
            <input type="password" id="login-password" name="password" required>
            <button type="submit">Login</button>
        </form>
    </section>

    <footer>
        <p>&copy; 2023 Cyber Hacking Website. All rights reserved.</p>
    </footer>
</body>
</html>

