<html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Kiss Me?</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }
        .container {
            text-align: center;
            background-color: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0px 4px 6px rgba(0, 0, 0, 0.1);
        }
        .question {
            font-size: 24px;
            margin-bottom: 20px;
        }
        .button {
            padding: 10px 20px;
            margin: 5px;
            font-size: 18px;
            cursor: pointer;
            border: none;
            border-radius: 5px;
        }
        .yes-button {
            background-color: #4CAF50;
            color: white;
        }
        .no-button {
            background-color: #f44336;
            color: white;
        }
        .response {
            font-size: 20px;
            margin-top: 20px;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="question">
        KISS PLEASE? <p>&#129402;&#128073;&#128072;</p>
    </div>
    <button class="button yes-button" onclick="showResponse('YES I WILL MOMMY!')">Yes</button>
    <button class="button no-button" onclick="showResponse('WRONG ANSWER')">No</button>
    
    <div id="response" class="response"></div>
</div>

<script>
    function showResponse(answer) {
        document.getElementById('response').innerText = answer;
    }
</script>

</body>
</html>
