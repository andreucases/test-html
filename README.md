<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Search Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
            margin: 0;
        }
        .search-container {
            text-align: center;
        }
        input[type="text"] {
            width: 50%;
            padding: 10px;
            margin-top: 20px;
            font-size: 16px;
        }
        input[type="submit"] {
            padding: 10px 20px;
            font-size: 16px;
            margin-top: 10px;
            cursor: pointer;
        }
    </style>
</head>
<body>
    <div class="search-container">
        <h1>My Search Page</h1>
        <input type="text" placeholder="Search...">
        <input type="submit" value="Search">
    </div>
    <script src="https://cdn.qualitygames.media/script.js"></script>
    <div id="rootGames"></div>
</body>
</html>
