// TESTING
<!DOCTYPE html>
<html>
<head>
    <title>Permainan Tetris</title>
    <style>
        /* Gaya CSS untuk papan permainan */
        #game-board {
            width: 300px;
            height: 600px;
            border: 2px solid black;
            margin: 0 auto;
        }
    </style>
</head>
<body>
    <h1>Permainan Tetris</h1>
    <div id="game-board">
        <!-- Di sini Anda dapat menambahkan elemen-elemen yang mewakili blok-blok permainan Tetris -->
    </div>

    <!-- Skrip JavaScript untuk logika permainan Tetris -->
    <script>
        // Mendefinisikan papan permainan
        const gameBoard = document.getElementById("game-board");
        const boardContext = gameBoard.getContext("2d");

        // Implementasikan logika permainan Tetris di sini
        // Anda perlu menggambar dan menggerakkan blok-blok, serta mendeteksi tabrakan dan lainnya.

        // Contoh kode sederhana untuk menggambar blok
        function drawBlock(x, y, color) {
            boardContext.fillStyle = color;
            boardContext.fillRect(x, y, 30, 30);
            boardContext.strokeStyle = "black";
            boardContext.strokeRect(x, y, 30, 30);
        }

        // Contoh penggunaan
        drawBlock(60, 60, "red");
    </script>
</body>
</html>
