<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CBT Administrasi Perkantoran</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="quiz-container">
        <div id="quiz">
            <div class="header">
                <h2>Tes Kemampuan Akademik</h2>
                <span id="question-progress">Soal 1 dari 3</span>
            </div>
            <h3 id="question">Teks Pertanyaan Disini</h3>
            <div id="options" class="options-container">
                <!-- Tombol pilihan akan muncul di sini -->
            </div>
            <button id="next-btn" class="hide">Selanjutnya</button>
        </div>
        <div id="result" class="hide">
            <h2>Tes Selesai!</h2>
            <p>Nilai Anda: <span id="score">0</span> / 100</p>
            <button onclick="location.reload()">Ulangi Tes</button>
        </div>
    </div>
    <script src="script.js"></script>
</body>
</html># test-tugas
