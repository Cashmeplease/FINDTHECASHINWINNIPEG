<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FIND THE CASH WINNIPEG</title>
    <style>
        body {
            background-color: #121212;
            color: #fff;
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 50px;
        }
        .container {
            padding: 20px;
            background: #1e1e1e;
            display: inline-block;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 255, 100, 0.8);
            transition: 0.3s;
        }
        h1 {
            color: #00ff64;
            text-shadow: 0 0 10px #00ff64;
        }
        #randomNumbers {
            font-size: 24px;
            font-weight: bold;
            margin-top: 20px;
            color: #00ff64;
        }
        .container:hover {
            box-shadow: 0 6px 20px rgba(0, 255, 100, 1);
        }
        button {
            background: #00ff64;
            color: black;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
            margin-top: 15px;
            transition: 0.3s;
        }
        button:hover {
            background: #00cc50;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>FIND THE CASH WINNIPEG</h1>
        <p>Click the button to get two random numbers!</p>
        <div id="randomNumbers">Click the button</div>
        <button onclick="generateNumbers()">Generate Numbers</button>
    </div>
    <script>
        function generateNumbers() {
            let num1 = Math.floor(Math.random() * 10);
            let num2 = Math.floor(Math.random() * 10);
            document.getElementById("randomNumbers").textContent = `Numbers: ${num1}, ${num2}`;
        }
    </script>
</body>
</html>
