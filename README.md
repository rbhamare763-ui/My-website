<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Sorry Siddhi ❤️</title>

<style>
    body {
        margin: 0;
        padding: 0;
        font-family: 'Segoe UI', sans-serif;
        background: linear-gradient(135deg, #ff9a9e, #fad0c4);
        display: flex;
        justify-content: center;
        align-items: center;
        height: 100vh;
    }

    .card {
        background: white;
        padding: 40px;
        border-radius: 20px;
        box-shadow: 0 15px 35px rgba(0,0,0,0.2);
        text-align: center;
        max-width: 400px;
        animation: float 3s ease-in-out infinite;
    }

    h1 {
        color: #ff4d6d;
        margin-bottom: 15px;
    }

    p {
        color: #555;
        font-size: 18px;
        line-height: 1.6;
    }

    .heart {
        font-size: 40px;
        animation: beat 1s infinite;
    }

    button {
        margin-top: 20px;
        padding: 10px 20px;
        border: none;
        border-radius: 25px;
        background: #ff4d6d;
        color: white;
        font-size: 16px;
        cursor: pointer;
        transition: 0.3s;
    }

    button:hover {
        background: #e63950;
        transform: scale(1.05);
    }

    @keyframes beat {
        0%, 100% { transform: scale(1); }
        50% { transform: scale(1.2); }
    }

    @keyframes float {
        0%, 100% { transform: translateY(0px); }
        50% { transform: translateY(-10px); }
    }
</style>
</head>

<body>

<div class="card">
    <div class="heart">❤️</div>
    <h1>Sorry Siddhi</h1>
    <p>
        I am really sorry if I hurt you.<br><br>
        You mean so much to me, and I never want to lose you.<br><br>
        Please forgive me ❤️
    </p>
    <button onclick="alert('Thank you for forgiving me ❤️')">Forgive Me?</button>
</div>

</body>
</html>
