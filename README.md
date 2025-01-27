# Gerominator.ai
The official website for Gerominator
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Gerominator - Chaos Unleashed</title>
    <style>
        body {
            font-family: 'Comic Sans MS', Arial, sans-serif;
            margin: 0;
            padding: 0;
            background: linear-gradient(to bottom right, #2c3e50, #34495e);
            color: #ffffff;
            text-align: center;
            overflow: hidden;
        }

        header {
            position: relative;
            background: rgba(0, 0, 0, 0.8);
            color: #f1c40f;
            padding: 40px;
            font-size: 3rem;
            font-weight: bold;
            text-transform: uppercase;
            text-shadow: 4px 4px 0px #e74c3c;
            z-index: 2;
        }

        header::after {
            content: '';
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: url('https://via.placeholder.com/1920x1080.png?text=Gerominator+Burning+Printer') no-repeat center/cover;
            opacity: 0.2;
            z-index: -1;
        }

        .hero {
            margin: 50px auto;
            max-width: 800px;
            background: rgba(255, 255, 255, 0.1);
            border-radius: 20px;
            padding: 30px;
            box-shadow: 0px 8px 20px rgba(0, 0, 0, 0.7);
        }

        .hero h1 {
            font-size: 4rem;
            margin-bottom: 20px;
            color: #f1c40f;
            text-shadow: 3px 3px 0px #e74c3c;
        }

        .hero p {
            font-size: 1.5rem;
            color: #ecf0f1;
            text-shadow: 2px 2px 0px #000000;
        }

        .btn {
            display: inline-block;
            margin-top: 20px;
            padding: 15px 30px;
            background: linear-gradient(to right, #e84393, #6c5ce7);
            color: white;
            font-size: 1.5rem;
            font-weight: bold;
            text-decoration: none;
            border-radius: 10px;
            transition: transform 0.3s ease;
        }

        .btn:hover {
            transform: scale(1.1);
        }

        .floating-items {
            position: absolute;
            width: 50px;
            height: 50px;
            background: url('https://via.placeholder.com/100.png?text=🔥') no-repeat center/cover;
            animation: float 5s infinite ease-in-out;
        }

        @keyframes float {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-30px);
            }
        }

        .floating-items:nth-child(2) {
            left: 10%;
            animation-duration: 6s;
        }

        .floating-items:nth-child(3) {
            left: 30%;
            animation-duration: 7s;
        }

        .floating-items:nth-child(4) {
            left: 60%;
            animation-duration: 4.5s;
        }

        .floating-items:nth-child(5) {
            left: 80%;
            animation-duration: 5.5s;
        }

        footer {
            margin-top: 50px;
            padding: 20px;
            background: #2c3e50;
            color: #bdc3c7;
            font-size: 1rem;
            box-shadow: 0px -4px 10px rgba(0, 0, 0, 0.5);
        }

        footer a {
            color: #f1c40f;
            text-decoration: none;
            font-weight: bold;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <header>
        Chaos is Here: Welcome to Gerominator
    </header>

    <div class="hero">
        <h1>The Printer Burns Forever</h1>
        <p>Gerominator is here to wreak havoc, crush your alt-season dreams, and make you laugh hysterically at the absurdity of it all. Sarcasm is the only currency accepted here.</p>
        <a class="btn" href="https://twitter.com/Gerominator_AI" target="_blank">Follow Gerominator on Twitter</a>
    </div>

    <!-- Floating fire items -->
    <div class="floating-items" style="left: 10%; top: 20%;"></div>
    <div class="floating-items" style="left: 30%; top: 40%;"></div>
    <div class="floating-items" style="left: 60%; top: 30%;"></div>
    <div class="floating-items" style="left: 80%; top: 10%;"></div>

    <footer>
        <p>&copy; 2025 Gerominator. Built to Burn Alt Seasons and Printers. Find us on <a href="https://twitter.com/Gerominator_AI" target="_blank">Twitter</a>.</p>
    </footer>
</body>
</html>


