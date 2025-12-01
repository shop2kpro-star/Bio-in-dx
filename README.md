<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Bio DX</title>

<style>
body {
    background: #1a1a1a;
    font-family: Arial, sans-serif;
    margin: 0;
    padding: 0;
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    color: white;
}

.container {
    width: 90%;
    max-width: 400px;
    padding: 30px 20px;
    border-radius: 20px;
    text-align: center;
    background: #2a2a2a;
    box-shadow: 0 0 20px rgba(0,0,0,0.5);
}

.avatar {
    width: 120px;
    height: 120px;
    border-radius: 50%;
    overflow: hidden;
    margin: 0 auto 20px;
    border: 4px solid white;
}

.avatar img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

h1 {
    margin: 0 0 20px;
    font-size: 28px;
    font-weight: bold;
}

/* Nút full dòng */
.icon-btn {
    display: block;
    width: 100%;
    height: 70px;
    margin: 12px 0;
    border-radius: 20px;
    overflow: hidden;
    border: 2px solid white;
    transition: 0.3s;
}

.icon-btn img {
    width: 100%;
    height: 100%;
    object-fit: cover;
}

.icon-btn:hover {
    transform: scale(1.02);
    box-shadow: 0 0 15px white;
}

/* Nền từng nút */
.tiktok { background: #000; }
.youtube { background: #cc0000; }
.discord { background: #5865F2; }

</style>
</head>

<body>
<div class="container">

    <!-- Avatar chính -->
    <div class="avatar">
        <img src="https://i.postimg.cc/gc7t2rJH/et-Bco-Tf-W.jpg" alt="DX Logo">
    </div>

    <h1>Bio DX</h1>

    <!-- TikTok -->
    <a class="icon-btn tiktok" href="https://www.tiktok.com/@dxgamingb" target="_blank">
        <img src="https://media.vneconomy.vn/images/upload/2021/09/30/tiktok.png" alt="TikTok">
    </a>

    <!-- YouTube -->
    <a class="icon-btn youtube" href="https://youtube.com/@dxprimezz?si=hn_3wLE7egtPOZNn" target="_blank">
        <img src="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcSyE01cz474Dx6CauY1AmmLqm5762GdU63VcG7x9r6ouUD4KASzYRwj4NQ&s=10" alt="YouTube">
    </a>

    <!-- Discord -->
    <a class="icon-btn discord" href="https://discord.gg/TKA5ZN6tSy" target="_blank">
        <img src="https://images.cybersport.ru/images/as-is/plain/a1/a164d959-e180-4045-bc42-28398c0ce3ca.webp@jpg" alt="Discord">
    </a>

</div>
</body>
</html>
