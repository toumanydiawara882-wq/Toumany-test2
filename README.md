<!DOCTYPE html>
<html>
<head>
    <title>Toumany's Website</title>

    <style>
        body {
            background-color: #0f172a;
            color: white;
            font-family: Arial;
            text-align: center;
            padding: 50px;
        }

        h1 {
            color: #38bdf8;
        }

        button {
            background-color: #22c55e;
            border: none;
            padding: 10px 20px;
            color: white;
            font-size: 16px;
            border-radius: 5px;
            cursor: pointer;
        }

        button:hover {
            background-color: #16a34a;
        }
    </style>
</head>

<body>

    <h1>👋 Welcome to my website</h1>
    <h2>Toumany Diawara</h2>

    <p>I am learning coding and building my future 🚀</p>

    <button onclick="sayHello()">Click Me</button>

    <script>
        function sayHello() {
            alert("Welcome to my website!");
        }
    </script>

</body>
</html>
