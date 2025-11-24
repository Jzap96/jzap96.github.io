<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>My VR Portfolio</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 40px;
            background: #f4f4f4;
        }

        h1, h2, h3 {
            font-weight: bold;
        }

        .section {
            margin-bottom: 60px;
        }

        .game-block {
            margin-bottom: 40px;
        }

        .image-grid {
            display: grid;
            grid-template-columns: repeat(4, 1fr);
            gap: 10px;
            margin: 20px 0;
        }

        .image-grid img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            background: #ccc; /* placeholder background */
        }

        .side-title {
            font-size: 32px;
            font-weight: bold;
        }
    </style>
</head>

<body>

    <!-- ABOUT ME SECTION -->
    <div class="section">
        <h1>About Me</h1>
        <p><!-- Write about yourself here --> 
            Hi, I’m [Your Name]. This portfolio showcases my VR games, level designs, and development work.
        </p>
    </div>

    <!-- VR GAMES MAIN TITLE -->
    <div class="section">
        <h1 class="side-title">VR Games</h1>

        <!-- GAME SET 1 -->
        <div class="game-block">
            <h2>Game Title 1</h2>
            <div class="image-grid">
                <img src="" alt="Image 1">
                <img src="" alt="Image 2">
                <img src="" alt="Image 3">
                <img src="" alt="Image 4">
            </div>
        </div>

        <!-- LEVELS -->
        <h1 class="side-title">Levels</h1>

        <!-- LEVEL SET 1 -->
        <div class="game-block">
            <h2>Level Title 1</h2>
            <div class="image-grid">
                <img src="" alt="Level Image 1">
                <img src="" alt="Level Image 2">
                <img src="" alt="Level Image 3">
                <img src="" alt="Level Image 4">
            </div>
        </div>

        <!-- REPEAT PATTERN 3 MORE TIMES -->

        <!-- LEVEL SET 2 -->
        <div class="game-block">
            <h2>Level Title 2</h2>
            <div class="image-grid">
                <img src="" alt="Level Image 1">
                <img src="" alt="Level Image 2">
                <img src="" alt="Level Image 3">
                <img src="" alt="Level Image 4">
            </div>
        </div>

        <!-- LEVEL SET 3 -->
        <div class="game-block">
            <h2>Level Title 3</h2>
            <div class="image-grid">
                <img src="" alt="Level Image 1">
                <img src="" alt="Level Image 2">
                <img src="" alt="Level Image 3">
                <img src="" alt="Level Image 4">
            </div>
        </div>

        <!-- LEVEL SET 4 -->
        <div class="game-block">
            <h2>Level Title 4</h2>
            <div class="image-grid">
                <img src="" alt="Level Image 1">
                <img src="" alt="Level Image 2">
                <img src="" alt="Level Image 3">
                <img src="" alt="Level Image 4">
            </div>
        </div>

    </div>

</body>
</html>
