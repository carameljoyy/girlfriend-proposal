<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be My Girlfriend?</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f0f0f0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
        }
        .container {
            background-color: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            text-align: center;
        }
        h1 {
            color: #333;
        }
        p {
            color: #666;
        }
        button {
            background-color: #007bff;
            color: #fff;
            border: none;
            padding: 10px 20px;
            border-radius: 5px;
            cursor: pointer;
            font-size: 16px;
            margin-top: 20px;
            transition: background-color 0.3s;
        }
        button:hover {
            background-color: #0056b3;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Will You Be My Girlfriend?</h1>
        <p>My [Sade],</p>
        <p>I do not know how i feel but i know yo are always on my mind. You've brought so much joy and happiness into my life, and I cherish every moment we spend together. I've come to realize that you mean more to me.</p>
        <p>I guess you have been waiting long for this day to come..and I believe we have something truly special.</p>
        <p>So, [Sade baby], would you do me the honor of being your girlfriend?</p>
        <button onclick="sendResponse('yes')">Yes, I'd love to!</button>
        <button onclick="sendResponse('no')">I'm sorry, I can't</button>
    </div>

    <script>
        function sendResponse(response) {
            if (response === 'yes') {
                alert("Yaaaaay, i'm so happy rn.");
            } else {
                alert("You de whine me shey?.");
            }
        }
    </script>
</body>
</html>
