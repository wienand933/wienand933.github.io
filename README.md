<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Valentine's Proposal</title>
    <style>
        body {
            text-align: center;
            font-family: Arial, sans-serif;
            margin-top: 100px;
            background-color: #ffe6e6;
        }
        h1 {
            color: #ff3366;
        }
        .btn {
            font-size: 20px;
            padding: 10px 20px;
            margin: 10px;
            border: none;
            cursor: pointer;
            border-radius: 10px;
            transition: 0.3s;
        }
        #yes {
            background-color: #ff4d4d;
            color: white;
        }
        #no {
            background-color: #cccccc;
            color: black;
        }
    </style>
</head>
<body>

    <h1>Will you be my Valentine? ❤️</h1>
    <button id="yes" class="btn" onclick="alert('Yay! I knew you’d say yes! ❤️')">Yes</button>
    <button id="no" class="btn" onmouseover="growYes()">No</button>

    <script>
        let yesButton = document.getElementById("yes");
        let size = 20; // Initial font size

        function growYes() {
            size += 10; // Increase size
            yesButton.style.fontSize = size + "px";
        }
    </script>

</body>
</html>
