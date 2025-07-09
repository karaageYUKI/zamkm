# zamkm
<!DOCTYPE html>
<html lang="ja">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Googleへ移動</title>
    <style>
        body {
            font-family: sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            min-height: 100vh;
            margin: 0;
            background-color: #f0f0f0;
        }
        .google-button {
            padding: 15px 30px;
            font-size: 20px;
            color: #ffffff;
            background-color: #4285F4; /* Googleのブランドカラー */
            border: none;
            border-radius: 5px;
            cursor: pointer;
            text-decoration: none; /* aタグの装飾を解除 */
            display: inline-block; /* ボタンのように見せるため */
            transition: background-color 0.3s ease;
        }
        .google-button:hover {
            background-color: #357ae8; /* ホバー時の色 */
        }
    </style>
</head>
<body>
    <a href="https://www.google.com" class="google-button">Googleへ移動</a>
</body>
</html>
