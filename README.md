<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be My Girlfriend?</title>
    <style>
        body {
            font-family: 'Arial', sans-serif;
            text-align: center;
            background-color: #ffe6e6;
            margin: 0;
            padding: 0;
            overflow: hidden;
        }
        .container {
            margin: 50px auto;
            width: 80%;
        }
        h1 {
            color: #d63384;
            animation: fadeIn 2s ease-in-out;
        }
        .message {
            font-size: 18px;
            color: #333;
            margin-bottom: 20px;
            animation: fadeIn 3s ease-in-out;
        }
        .teddy-container {
            margin: 20px auto;
            animation: bounce 2s infinite;
        }
        .teddy-container img {
            width: 250px;
            height: auto;
        }
        .yes-btn {
            font-size: 20px;
            padding: 10px 20px;
            background-color: #ff4081;
            color: white;
            border: none;
            border-radius: 10px;
            cursor: pointer;
            margin-top: 20px;
            transition: transform 0.3s, background-color 0.3s;
        }
        .yes-btn:hover {
            background-color: #d63384;
            transform: scale(1.1);
        }
        .hidden-message {
            display: none;
            font-size: 24px;
            color: #28a745;
            margin-top: 20px;
            animation: fadeIn 2s ease-in-out;
        }
        
        @keyframes bounce {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-10px);
            }
        }
        
        @keyframes fadeIn {
            from {
                opacity: 0;
            }
            to {
                opacity: 1;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>I Have One Question To Ask You?</h1>
        <p class="message">From the moment our souls intertwined, my heart recognised its home in you. You are my refuge and my wildest journey, the love story I never anticipated yet can no longer imagine life without. 💖</p>
        
        <div class="teddy-container">
            <img src="https://i.imgur.com/vbPsgBG.jpeg" alt="Teddy Bear Holding a Sign">
        </div>
        
        <button class="yes-btn" onclick="showMessage()">Yes! 💕</button>
        <p class="hidden-message" id="responseMessage">Excellent Chomza! I can’t wait to continue this journey with you! 🎉🥰</p>
    </div>
    
    <script>
        function showMessage() {
            document.getElementById('responseMessage').style.display = 'block';
        }
    </script>
</body>
</html>
