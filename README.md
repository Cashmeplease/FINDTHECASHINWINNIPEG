<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>FIND THE CASH WINNIPEG</title>
    <style>
        body {
            background-color: #ffffff;
            color: #000000;
            font-family: Arial, sans-serif;
            text-align: center;
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            padding: 20px;
            background: #f8f8f8;
            display: inline-block;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
            width: 90%;
            max-width: 400px;
        }
        h1 {
            color: #000000;
            font-size: 24px;
        }
        #randomNumbers {
            font-size: 32px;
            font-weight: bold;
            margin-top: 20px;
            color: #000000;
        }
        button {
            background: #000000;
            color: #ffffff;
            padding: 10px 20px;
            border: none;
            border-radius: 5px;
            font-size: 18px;
            cursor: pointer;
            margin-top: 15px;
            width: 100%;
        }
        button:hover {
            background: #333333;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>FIND THE CASH WINNIPEG</h1>
        <p>Tap the button to get two random numbers!</p>
        <div id="randomNumbers">Tap the button</div>
        <button onclick="generateNumbers()">Generate Numbers</button>
    </div>
    <script>
        function generateNumbers() {
            let num1 = Math.floor(Math.random() * 10);
            let num2 = Math.floor(Math.random() * 10);
            document.getElementById("randomNumbers").textContent = `${num1} ${num2}`;
        }
    </script>
</body>
</html>
