<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Özgür 💕 Melisa</title>
    <style>
        body {
            margin: 0;
            padding: 0;
            font-family: 'Dancing Script', cursive;
            background: url('el-ele-tutasma.png') no-repeat center center fixed;
            background-size: cover;
            color: #fff;
            text-align: center;
            overflow: hidden;
        }
        h1 {
            font-size: 4rem;
            margin-top: 20px;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.3);
        }
        p {
            font-size: 2rem;
            margin: 20px;
            text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.3);
        }
        .content {
            position: relative;
            z-index: 1;
        }
        .gallery {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 10px;
            padding: 20px;
        }
        .gallery img {
            width: 100%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2);
        }
    </style>
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@700&display=swap" rel="stylesheet">
</head>
<body>
    <div class="content">
        <h1>ÖZGÜR 💕 MELİSA</h1>
        <p>Sevgilimmm,<br> İyi ki Benimlesin. İyi ki varsın seni çok seviyorum.<br> Seninle olan günlerimiz hiç bitmesin istiyorum.<br> Unutma bize her gün 14 Şubat.<br> Birtanemmm.</p>
        
        <!-- Resim Galerisi -->
        <div class="gallery">
            <img src="resim1.jpg" alt="Resim 1">
            <img src="resim2.jpg" alt="Resim 2">
            <img src="resim3.jpg" alt="Resim 3">
            <!-- Daha fazla resim ekleyebilirsin -->
        </div>
    </div>

    <!-- Arka Plan Müziği -->
    <audio autoplay loop>
        <source src="ta-uzak-yollardan.mp3" type="audio/mpeg">
        Tarayıcınız audio öğesini desteklemiyor.
    </audio>
</body>
</html>
