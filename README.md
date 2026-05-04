<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My Profile</title>
    <style>
        body {
            background: linear-gradient(to right, #6a11cb, #2575fc);
            color: white;
            font-family: Arial, sans-serif;
            text-align: center;
            animation: backgroundAnimation 10s infinite alternate;
        }
        @keyframes backgroundAnimation {
            0% { background: linear-gradient(to right, #6a11cb, #2575fc); }
            50% { background: linear-gradient(to right, #f9d423, #ff4e50); }
            100% { background: linear-gradient(to right, #6a11cb, #2575fc); }
        }
        .profile {
            padding: 50px;
            background-color: rgba(0, 0, 0, 0.5);
            border-radius: 15px;
            box-shadow: 0 4px 20px rgba(0, 0, 0, 0.3);
        }
        h1 {
            font-size: 3em;
            margin-bottom: 0.5em;
        }
        .stats {
            display: flex;
            justify-content: center;
            gap: 20px;
            margin-top: 20px;
        }
        .badge {
            background: #ff4e50;
            padding: 10px 15px;
            border-radius: 5px;
            transition: background 0.3s;
        }
        .badge:hover {
            background: #f9d423;
        }
    </style>
</head>
<body>
    <div class="profile">
        <h1>Welcome to My Profile</h1>
        <h2>Stats</h2>
        <div class="stats">
            <div class="badge">🌟 Stars: 150</div>
            <div class="badge">🍴 Forks: 75</div>
            <div class="badge">🖥️ Repositories: 20</div>
        </div>
    </div>
</body>
</html>
