<!DOCTYPE html>
 
<html lang="en">
 
<head>
 
    <meta charset="UTF-8">
 
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
 
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
 
    <title>HTML Bucin</title>
 
    <link rel="stylesheet" href="style.css">
 
</head>
 
<body>
 
    <h1>Hai Sayangku! ❤️</h1>
 
    <p>Kamu adalah alasan kenapa aku bisa senyum setiap hari 😊</p>
 
    <p class="heart">💖</p>
 
    <button class="button-love" onclick="showLove()">Klik untuk tahu rahasiaku</button>
 
 
 
 
    <script src="script.js"></script>
 
</body>
 
</html>
body {
 
    background-color: #ffe6e6;
 
    color: #ff66b2;
 
    font-family: 'Comic Sans MS', cursive, sans-serif;
 
    text-align: center;
 
    margin: 0;
 
    padding: 0;
 
}
 
h1 {
 
    margin-top: 50px;
 
    font-size: 48px;
 
    color: #ff4081;
 
}
 
p {
 
    font-size: 24px;
 
}
 
.heart {
 
    font-size: 100px;
 
    color: #ff1744;
 
    animation: beat 1s infinite;
 
}
 
@keyframes beat {
 
    0%, 20%, 50%, 80%, 100% {transform: scale(1);}
 
    40% {transform: scale(1.2);}
 
    60% {transform: scale(0.9);}
 
}
 
.button-love {
 
    margin-top: 30px;
 
    padding: 10px 20px;
 
    font-size: 18px;
 
    color: white;
 
    background-color: #ff66b2;
 
    border: none;
 
    border-radius: 5px;
 
    cursor: pointer;
 
}
 
.button-love:hover {
 
    background-color: #ff4081;
 
}
function showLove() {
 
    alert('Aku cinta kamu selamanya! ❤️');
 
}
