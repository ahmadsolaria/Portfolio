<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Coming Soon</title>
    <style>
        @import url('https://fonts.cdnfonts.com/css/sf-pro-display');
        
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }
        
        body {
            font-family: 'SF Pro Display', -apple-system, BlinkMacSystemFont, sans-serif;
            background-color: white;
            color: black;
            height: 100vh;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding: 20px;
        }
        
        .container {
            max-width: 800px;
        }
        
        h1 {
            font-size: 3.5rem;
            font-weight: 700;
            letter-spacing: -0.05em;
            margin-bottom: 1.5rem;
            opacity: 0;
            animation: fadeIn 1s ease-in forwards;
        }
        
        p {
            font-size: 1.5rem;
            font-weight: 400;
            letter-spacing: -0.02em;
            line-height: 1.5;
            margin-bottom: 2.5rem;
            opacity: 0;
            animation: fadeIn 1s ease-in forwards 0.3s;
        }
        
        .divider {
            width: 40px;
            height: 4px;
            background-color: black;
            margin: 0 auto 2.5rem;
            opacity: 0;
            animation: fadeIn 1s ease-in forwards 0.6s;
        }
        
        @keyframes fadeIn {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }
        
        @media (max-width: 768px) {
            h1 {
                font-size: 2.5rem;
            }
            
            p {
                font-size: 1.2rem;
            }
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Site Under Development</h1>
        <div class="divider"></div>
        <p>We're currently working on something exciting. <br>Please check back soon.</p>
    </div>
</body>
</html>