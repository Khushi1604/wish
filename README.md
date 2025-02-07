
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Hug Day</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: #f0e68c;
            text-align: center;
            padding: 50px;
        }

        .container {
            background-color: #fff;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            padding: 20px;
            max-width: 400px;
            margin: auto;
        }

        h1 {
            color: #ff69b4;
        }

        button {
            background-color: #ff69b4;
            color: white;
            border: none;
            padding: 10px 20px;
            font-size: 16px;
            cursor: pointer;
            border-radius: 5px;
        }

        button:hover {
            background-color: #ff1493;
        }

        #bearHug {
            margin-top: 20px;
        }

        .hidden {
            display: none;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Happy Hug Day!</h1>
        <button id="hugButton">Get a Hug</button>
        <div id="bearHug" class="hidden">
            <img src="hug.gif" alt="Bear Hug">
            <p>Love Love Love!</p>
        </div>
    </div>
    <script>
        document.getElementById('hugButton').addEventListener('click', function() {
            document.getElementById('bearHug').classList.toggle('hidden');
        });
    </script>
</body>
</html>
