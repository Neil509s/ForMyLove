
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Happy 27th Monthsary!</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            background: linear-gradient(135deg, #ff9a9e, #fad0c4);
            font-family: Arial, sans-serif;
            color: #fff;
            text-align: center;
            overflow: hidden;
        }
        .container {
            animation: fadeIn 2s ease-in-out;
        }
        h1 {
            font-size: 3rem;
            margin: 0;
            display: none;
        }
        p {
            font-size: 1.5rem;
            display: none;
        }
        button {
            padding: 10px 20px;
            font-size: 1.2rem;
            background-color: #ff6f61;
            border: none;
            border-radius: 5px;
            color: white;
            cursor: pointer;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }
        button:hover {
            background-color: #ff856e;
        }
        @keyframes fadeIn {
            from { opacity: 0; transform: scale(0.8); }
            to { opacity: 1; transform: scale(1); }
        }
    </style>
</head>
<body>
    <div class="container">
        <button onclick="showGreeting()">Click Me!</button>
        <h1>Happy 27th Monthsary! ❤️</h1>
        <p>"By," you make my every day brighter.<br>Thank you for being my partner in this journey.<br>Here's to many more months together! 💖</p>
    </div>

    <script>
        function showGreeting() {
            document.querySelector('h1').style.display = 'block';
            document.querySelector('p').style.display = 'block';
            document.querySelector('button').style.display = 'none';
        }
    </script>
</body>
</html>

