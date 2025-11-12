<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Example Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f5f7fa;
            color: #333;
            margin: 0;
            padding: 0;
            text-align: center;
        }

        header {
            background-color: #4a90e2;
            color: white;
            padding: 20px;
        }

        main {
            padding: 40px;
        }

        button {
            background-color: #4a90e2;
            border: none;
            color: white;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
        }

        button:hover {
            background-color: #357ABD;
        }

        footer {
            background-color: #222;
            color: #aaa;
            padding: 15px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>

    <header>
        <h1>Welcome to My Example Page</h1>
    </header>

    <main>
        <h2>Hello, World!</h2>
        <p>This is a simple HTML page created for demonstration.</p>
        <button onclick="sayHello()">Click Me!</button>
    </main>

    <footer>
        &copy; 2025 My Example Page
    </footer>

    <script>
        function sayHello() {
            alert('Hello there! Thanks for clicking the button 😄');
        }
    </script>

</body>
</html>
