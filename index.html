<!DOCTYPE html>
<html lang="id">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Petualangan Aturan Ceria - Kelas 1B SDIT Az-zahra</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Fredoka:wght@400;500;600;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/animate.css/4.1.1/animate.min.css"/>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <style>
        body {
            font-family: 'Fredoka', sans-serif;
            background-color: #f0fdf4; /* Soft green background */
            background-image: radial-gradient(#dcfce7 20%, transparent 20%),
                              radial-gradient(#dcfce7 20%, transparent 20%);
            background-position: 0 0, 25px 25px;
            background-size: 50px 50px;
            overflow: hidden; /* Prevent scrolling, act like an app */
            touch-action: manipulation;
        }

        .screen {
            display: none;
            height: 100vh;
            width: 100vw;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            padding: 1rem;
        }

        .screen.active {
            display: flex;
            animation: fadeIn 0.5s ease-in-out;
        }

        .btn-option {
            transition: all 0.2s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }

        .btn-option:active {
            transform: scale(0.95);
        }

        .btn-option.correct {
            background-color: #22c55e !important; /* Tailwind Green 500 */
            color: white !important;
            border-color: #16a34a !important;
            box-shadow: 0 10px 0 #16a34a, 0 15px 20px rgba(0,0,0,0.2) !important;
            animation: pulse 0.5s;
        }

        .btn-option.wrong {
            background-color: #ef4444 !important; /* Tailwind Red 500 */
            color: white !important;
            border-color: #dc2626 !important;
            box-shadow: 0 10px 0 #dc2626, 0 15px 20px rgba(0,0,0,0.2) !important;
            animation: headShake 0.5s;
        }

        /* 3D Button Effect */
        .btn-3d {
            position: relative;
            top: 0;
            box-shadow: 0 8px 0 var(--shadow-color), 0 15px 20px rgba(0,0,0,0.1);
            transition: all 0.1s;
        }
        
        .btn-3d:active, .btn-3d.pressed {
            top: 8px;
            box-shadow: 0 0 0 var(--shadow-color), 0 5px 10px rgba(0,0,0,0.1);
        }

        /* Confetti Canvas */
        #confetti-canvas {
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 100;
        }

        .floating-cloud {
            animation: float 6s ease-in-out infinite;
        }

        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-20px); }
            100% { transform: translateY(0px); }
        }

        /* Input field styling */
        .name-input {
            width: 100%;
            padding: 1rem;
            font-size: 1.25rem;
            border: 4px solid #14b8a6; /* teal-500 */
            border-radius: 1rem;
            text-align: center;
            outline: none;
            transition: border-color 0.3s, box-shadow 0.3s;
            font-family: 'Fredoka', sans-serif;
            color: #0f766e; /* teal-700 */
        }

        .name-input:focus {
            border-color: #0d9488; /* teal-600 */
            box-shadow: 0 0 0 4px rgba(20, 184, 166, 0.2);
        }

        .name-input::placeholder {
            color: #99f6e4; /* teal-200 */
        }

        .avatar-img {
            width: 80px;
            height: 80px;
            object-fit: contain;
            border-radius: 50%;
            background-color: #f1f5f9;
            border: 3px solid #cbd5e1;
            padding: 5px;
        }
    </style>
</head>
<body class="text-slate-800 antialiased selection:bg-teal-200">

    <canvas id="confetti-canvas"></canvas>

    <!-- Screen 1: Welcome & Name Input -->
    <div id="welcome-screen" class="screen active relative">
        <div class="absolute top-10 left-10 text-6xl floating-cloud opacity-70">☁️</div>
        <div class="absolute top-20 right-10 text-5xl floating-cloud opacity-80" style="animation-delay: 1s;">⛅</div>
        <div class="absolute bottom-20 left-20 text-4xl floating-cloud opacity-60" style="animation-delay: 2s;">🎈</div>

        <div class="bg-white/95 backdrop-blur-sm p-8 rounded-[2rem] shadow-2xl border-4 border-teal-400 max-w-md w-full text-center relative z-10">
            <h3 class="text-xl font-bold text-teal-600 mb-2 uppercase tracking-wider">Selamat Datang di</h3>
            <h1 class="text-3xl md:text-4xl font-extrabold text-indigo-600 mb-6 drop-shadow-sm leading-tight">
                SDIT Az-zahra
            </h1>
            
            <div class="flex justify-center mb-6 space-x-6">
                <!-- Using FontAwesome for Islamic Avatars -->
                <div class="flex flex-col items-center animate__animated animate__bounceIn">
                     <div class="bg-pink-100 p-3 rounded-full border-4 border-pink-300">
                        <i class="fa-solid fa-child-dress text-5xl text-pink-500"></i>
                     </div>
                     <span class="mt-2 font-semibold text-pink-600">Siswi</span>
                </div>
                <div class="flex flex-col items-center animate__animated animate__bounceIn animate__delay-1s">
                     <div class="bg-blue-100 p-3 rounded-full border-4 border-blue-300">
                        <i class="fa-solid fa-child text-5xl text-blue-500"></i>
                     </div>
                     <span class="mt-2 font-semibold text-blue-600">Siswa</span>
                </div>
            </div>

            <div class="mb-6">
                <label for="student-name" class="block text-lg font-semibold text-slate-600 mb-2">Siapa namamu?</label>
                <input type="text" id="student-name" class="name-input" placeholder="Ketik nama di sini..." autocomplete="off">
                <p id="name-error" class="text-red-500 font-medium text-sm mt-2 hidden animate__animated animate__shakeX">Jangan lupa isi namamu ya! 😉</p>
            </div>
            
            <button onclick="goToStartScreen()" style="--shadow-color: #0d9488;" class="btn-3d w-full bg-teal-500 hover:bg-teal-400 text-white font-bold text-xl py-3 px-6 rounded-2xl border-4 border-teal-600 flex items-center justify-center gap-2">
                <span>Lanjut</span>
                <span class="text-2xl"><i class="fa-solid fa-arrow-right"></i></span>
            </button>
        </div>
    </div>

    <!-- Screen 2: Game Start Info -->
    <div id="start-screen" class="screen relative">
        <div class="absolute top-10 left-10 text-6xl floating-cloud opacity-70">☁️</div>
        <div class="absolute top-20 right-10 text-5xl floating-cloud opacity-80" style="animation-delay: 1s;">⛅</div>
        <div class="absolute bottom-20 left-20 text-4xl floating-cloud opacity-60" style="animation-delay: 2s;">🎈</div>

        <div class="bg-white/90 backdrop-blur-sm p-8 rounded-[2rem] shadow-2xl border-4 border-indigo-400 max-w-lg w-full text-center relative z-10">
            <div class="flex justify-center mb-4">
                 <i class="fa-solid fa-school text-6xl text-indigo-500"></i>
            </div>
            <h2 class="text-2xl font-bold text-slate-700 mb-2">Ahlan Wa Sahlan, <span id="display-student-name" class="text-indigo-600 font-extrabold text-3xl">Siswa</span>! 👋</h2>
            
            <h1 class="text-4xl md:text-5xl font-extrabold text-indigo-600 mb-4 drop-shadow-md leading-tight mt-4">
                Petualangan<br>Aturan Ceria
            </h1>
            <p class="text-lg text-slate-600 mb-8 font-medium bg-indigo-50 p-4 rounded-xl border border-indigo-100">
                Belajar Pendidikan Pancasila Kelas 1B.<br>Yuk kita belajar aturan di rumah dan di sekolah sesuai syariat Islam!
            </p>
            
            <button onclick="startGame()" style="--shadow-color: #4338ca;" class="btn-3d w-full bg-indigo-500 hover:bg-indigo-400 text-white font-bold text-2xl py-4 px-8 rounded-2xl border-4 border-indigo-700 flex items-center justify-center gap-3">
                <span>Mulai Bermain!</span>
                <span class="text-3xl">🚀</span>
            </button>
        </div>
    </div>

    <div id="level-intro-screen" class="screen">
        <div class="bg-white p-10 rounded-[3rem] shadow-2xl border-8 border-indigo-400 max-w-md w-full text-center text-white bg-gradient-to-br from-indigo-500 to-purple-600">
            <div id="level-icon" class="text-8xl mb-6 animate__animated animate__tada">🌟</div>
            <h2 id="level-title" class="text-5xl font-extrabold mb-4 drop-shadow-lg">Level 1</h2>
            <p id="level-desc" class="text-2xl font-medium mb-8">Aturan Dasar Sehari-hari</p>
            
            <button onclick="startLevel()" style="--shadow-color: #c2410c;" class="btn-3d w-full bg-orange-500 hover:bg-orange-400 text-white font-bold text-2xl py-4 px-8 rounded-2xl border-4 border-orange-600">
                Lanjut <i class="fa-solid fa-arrow-right ml-2"></i>
            </button>
        </div>
    </div>

    <div id="game-screen" class="screen">
        <!-- Header: Progress & Score -->
        <div class="w-full max-w-2xl flex justify-between items-center mb-6 px-4">
            <div class="bg-white py-2 px-4 rounded-full font-bold text-lg text-indigo-600 shadow-md border-2 border-indigo-200 flex items-center gap-2">
                <i class="fa-solid fa-layer-group"></i> Level <span id="current-level-display">1</span>
            </div>
            <div class="bg-white py-2 px-4 rounded-full font-bold text-lg text-rose-500 shadow-md border-2 border-rose-200 flex items-center gap-2">
                <i class="fa-solid fa-star text-amber-400"></i> <span id="score-display">0</span>
            </div>
        </div>

        <!-- Question Card -->
        <div class="bg-white p-6 md:p-8 rounded-[2rem] shadow-xl border-4 border-amber-300 max-w-2xl w-full text-center relative mb-8">
            <div class="absolute -top-4 left-1/2 transform -translate-x-1/2 bg-amber-400 text-white font-bold py-1 px-4 rounded-full text-sm shadow-md border-2 border-white">
                Soal <span id="question-number">1</span> / 5
            </div>

            <div id="question-image-container" class="mb-4 mt-2 flex justify-center">
                <!-- Using SVGs/Emojis for colorful visuals -->
                <div id="question-emoji" class="text-7xl bg-amber-100 p-4 rounded-full border-4 border-amber-200 w-32 h-32 flex items-center justify-center">🏠</div>
            </div>
            <h2 id="question-text" class="text-2xl md:text-3xl font-bold text-slate-700 leading-snug mb-2">
                Pertanyaan akan muncul di sini.
            </h2>
        </div>

        <!-- Options Container -->
        <div id="options-container" class="w-full max-w-2xl flex flex-col gap-4 px-4 pb-6 overflow-y-auto">
            <!-- Buttons injected via JS -->
        </div>
    </div>

    <div id="result-screen" class="screen">
        <div class="bg-white p-8 rounded-[3rem] shadow-2xl border-8 border-pink-400 max-w-md w-full text-center">
            <div class="text-6xl mb-2"><i class="fa-solid fa-medal text-yellow-400"></i></div>
            <h2 class="text-3xl font-extrabold text-pink-500 mb-2">Alhamdulillah!</h2>
            <p class="text-xl text-slate-700 font-bold mb-4">Kerja Bagus, <span id="final-student-name" class="text-indigo-600">Siswa</span>!</p>
            <div class="text-8xl mb-4 animate__animated animate__heartBeat animate__infinite">🏆</div>
            
            <p class="text-lg text-slate-600 font-medium mb-4">Kamu telah menjadi anak yang mengerti aturan!</p>
            
            <div class="bg-slate-100 rounded-2xl p-6 mb-8 border-2 border-slate-200">
                <p class="text-lg text-slate-500 mb-1">Total Bintang Kebaikanmu:</p>
                <div class="text-5xl font-black text-amber-400 drop-shadow-md flex justify-center items-center gap-2">
                    <span id="final-score">0</span> <i class="fa-solid fa-star"></i>
                </div>
            </div>
            
            <button onclick="sendToWhatsApp()" style="--shadow-color: #15803d;" class="btn-3d w-full bg-green-500 hover:bg-green-400 text-white font-bold text-xl py-4 px-8 rounded-2xl border-4 border-green-700 flex items-center justify-center gap-2 mb-4">
                <span>Lapor Bu Guru via WA</span>
                <span class="text-3xl"><i class="fa-brands fa-whatsapp"></i></span>
            </button>

            <button onclick="resetGame()" style="--shadow-color: #0369a1;" class="btn-3d w-full bg-sky-500 hover:bg-sky-400 text-white font-bold text-xl py-4 px-8 rounded-2xl border-4 border-sky-600 flex items-center justify-center gap-2">
                <span>Main Lagi</span>
                <span class="text-3xl"><i class="fa-solid fa-rotate-right"></i></span>
            </button>
        </div>
    </div>

    <script>
        // Game Data organized by Levels
        const gameData = [
            {
                level: 1,
                title: "Level 1",
                desc: "Aturan di Rumah (Mudah)",
                icon: "🏡",
                themeColor: "indigo",
                questions: [
                    {
                        emoji: "🛏️",
                        text: "Saat bangun tidur di pagi hari, sebagai anak shalih/shalihah, Ali sebaiknya...",
                        options: [
                            { text: "Membaca doa bangun tidur, merapikan tempat tidur, lalu bersiap shalat shubuh", correct: true },
                            { text: "Bermalas-malasan, tidak shalat shubuh, dan langsung bermain HP", correct: false }
                        ]
                    },
                    {
                        emoji: "🧸",
                        text: "Setelah Aisyah selesai bermain balok susun di ruang keluarga, yang harus dilakukan adalah...",
                        options: [
                            { text: "Membiarkannya berantakan agar Ibu yang membersihkan", correct: false },
                            { text: "Merapikannya kembali ke dalam kotak mainan dengan ikhlas", correct: true }
                        ]
                    },
                    {
                        emoji: "🤝",
                        text: "Sebelum Ali berangkat ke sekolah SDIT, ia wajib...",
                        options: [
                            { text: "Berpamitan, cium tangan kedua orang tua, dan mengucapkan salam", correct: true },
                            { text: "Langsung lari keluar rumah tanpa pamit karena takut terlambat", correct: false }
                        ]
                    },
                    {
                        emoji: "🚪",
                        text: "Aisyah mau masuk ke kamar Kakak untuk meminjam pensil. Sebelum membuka pintu, Aisyah harus...",
                        options: [
                            { text: "Mengetuk pintu dan mengucapkan salam", correct: true },
                            { text: "Langsung menerobos masuk tanpa permisi", correct: false }
                        ]
                    },
                    {
                        emoji: "🧹",
                        text: "Ibu sedang sibuk membersihkan meja makan. Sebagai anak yang berbakti, Ali sebaiknya...",
                        options: [
                            { text: "Membantu Ibu membersihkan meja bersama-sama", correct: true },
                            { text: "Pergi menonton televisi dan membiarkan Ibu kelelahan", correct: false }
                        ]
                    }
                ]
            },
            {
                level: 2,
                title: "Level 2",
                desc: "Aturan di Sekolah (Sedang)",
                icon: "🏫",
                themeColor: "orange",
                questions: [
                    {
                        emoji: "👩‍🏫",
                        text: "Saat Bu Guru sedang menerangkan pelajaran tentang Rukun Iman di kelas, Aisyah harus...",
                        options: [
                            { text: "Mengobrol dan bercanda dengan teman sebangku", correct: false },
                            { text: "Mendengarkan dengan tenang, fokus, dan memperhatikan penjelasan", correct: true }
                        ]
                    },
                    {
                        emoji: "🙋‍♀️",
                        text: "Ali ingin bertanya kepada Bu Guru karena belum paham. Apa yang harus Ali lakukan?",
                        options: [
                            { text: "Mengangkat tangan kanan terlebih dahulu dan menunggu dipersilakan", correct: true },
                            { text: "Langsung berteriak dari tempat duduknya memotong pembicaraan", correct: false }
                        ]
                    },
                    {
                        emoji: "👕",
                        text: "Seragam sekolah SDIT yang dipakai setiap hari ke sekolah harus terlihat...",
                        options: [
                            { text: "Kotor, kusut, dan baju dikeluarkan", correct: false },
                            { text: "Bersih, rapi, menutup aurat, dan dimasukkan ke dalam celana/rok", correct: true }
                        ]
                    },
                    {
                        emoji: "🍱",
                        text: "Saat jam istirahat, banyak siswa ingin membeli makan di kantin kejujuran. Aturan yang benar adalah...",
                        options: [
                            { text: "Mengantre dengan tertib menunggu giliran dengan sabar", correct: true },
                            { text: "Menyerobot antrean teman agar lebih cepat dapat makanan", correct: false }
                        ]
                    },
                    {
                        emoji: "🗑️",
                        text: "Aisyah melihat ada bungkus plastik camilan jatuh di halaman sekolah. Sesuai hadits kebersihan, Aisyah sebaiknya...",
                        options: [
                            { text: "Memungutnya dan membuang ke tempat sampah untuk menjaga kebersihan", correct: true },
                            { text: "Pura-pura tidak melihat dan membiarkan petugas kebersihan yang mengambil", correct: false }
                        ]
                    }
                ]
            }
        ];

        // Game State Variables
        let currentLevelIndex = 0;
        let currentQuestionIndex = 0;
        let score = 0;
        let isAnswering = false;
        let playerName = "";

        function showScreen(screenId) {
            document.querySelectorAll('.screen').forEach(screen => {
                screen.classList.remove('active');
            });
            document.getElementById(screenId).classList.add('active');
        }

        function goToStartScreen() {
            const nameInput = document.getElementById('student-name');
            const errorMsg = document.getElementById('name-error');
            
            if(nameInput.value.trim() === "") {
                errorMsg.classList.remove('hidden');
                // Retrigger animation
                errorMsg.classList.remove('animate__shakeX');
                void errorMsg.offsetWidth; // trigger reflow
                errorMsg.classList.add('animate__shakeX');
                nameInput.focus();
                return;
            }
            
            errorMsg.classList.add('hidden');
            playerName = nameInput.value.trim();
            document.getElementById('display-student-name').innerText = playerName;
            showScreen('start-screen');
        }

        // Allow pressing Enter in name input
        document.getElementById('student-name').addEventListener('keypress', function (e) {
            if (e.key === 'Enter') {
                goToStartScreen();
            }
        });

        function startGame() {
            currentLevelIndex = 0;
            currentQuestionIndex = 0;
            score = 0;
            updateScore();
            prepareLevelIntro();
        }

        function prepareLevelIntro() {
            const levelData = gameData[currentLevelIndex];
            document.getElementById('level-title').innerText = levelData.title;
            document.getElementById('level-desc').innerText = levelData.desc;
            document.getElementById('level-icon').innerText = levelData.icon;
            
            const introCard = document.getElementById('level-intro-screen').querySelector('div');
            if(levelData.themeColor === 'indigo') {
                introCard.className = "bg-white p-10 rounded-[3rem] shadow-2xl border-8 border-indigo-400 max-w-md w-full text-center text-white bg-gradient-to-br from-indigo-500 to-purple-600";
            } else {
                introCard.className = "bg-white p-10 rounded-[3rem] shadow-2xl border-8 border-orange-400 max-w-md w-full text-center text-white bg-gradient-to-br from-orange-400 to-rose-500";
            }

            showScreen('level-intro-screen');
        }

        function startLevel() {
            currentQuestionIndex = 0;
            document.getElementById('current-level-display').innerText = gameData[currentLevelIndex].level;
            loadQuestion();
            showScreen('game-screen');
        }

        function loadQuestion() {
            isAnswering = false;
            const currentLevelData = gameData[currentLevelIndex];
            const qData = currentLevelData.questions[currentQuestionIndex];

            document.getElementById('question-number').innerText = currentQuestionIndex + 1;
            document.getElementById('question-emoji').innerText = qData.emoji;
            document.getElementById('question-text').innerText = qData.text;

            const optionsContainer = document.getElementById('options-container');
            optionsContainer.innerHTML = ''; 

            const shuffledOptions = shuffleArray([...qData.options]);

            // Fun colorful options
            const colors = [
                { bg: 'bg-blue-50', border: 'border-blue-400', text: 'text-blue-800', hover: 'hover:bg-blue-100', shadow: '#60a5fa' },
                { bg: 'bg-purple-50', border: 'border-purple-400', text: 'text-purple-800', hover: 'hover:bg-purple-100', shadow: '#c084fc' }
            ];

            shuffledOptions.forEach((option, index) => {
                const btnColor = colors[index % colors.length];
                const btn = document.createElement('button');
                
                btn.className = `btn-option btn-3d w-full ${btnColor.bg} ${btnColor.border} ${btnColor.text} ${btnColor.hover} border-4 rounded-2xl p-4 md:p-6 text-left text-lg md:text-xl font-semibold flex items-center justify-between gap-4`;
                btn.style.setProperty('--shadow-color', btnColor.shadow);
                
                btn.innerHTML = `
                    <span class="flex-1 leading-snug">${option.text}</span>
                    <div class="icon-container w-10 h-10 rounded-full border-2 border-current flex items-center justify-center shrink-0 bg-white text-xl"></div>
                `;
                
                // Add touch support explicitly for mobile
                btn.addEventListener('click', () => handleAnswer(option.correct, btn));
                optionsContainer.appendChild(btn);
            });
        }

        function shuffleArray(array) {
            for (let i = array.length - 1; i > 0; i--) {
                const j = Math.floor(Math.random() * (i + 1));
                [array[i], array[j]] = [array[j], array[i]];
            }
            return array;
        }

        function handleAnswer(isCorrect, buttonElement) {
            if (isAnswering) return;
            isAnswering = true;

            const iconContainer = buttonElement.querySelector('.icon-container');

            if (isCorrect) {
                buttonElement.classList.add('correct');
                iconContainer.innerHTML = '<i class="fa-solid fa-check"></i>';
                iconContainer.classList.add('text-green-600', 'border-transparent');
                score += 10;
                updateScore();
            } else {
                buttonElement.classList.add('wrong');
                iconContainer.innerHTML = '<i class="fa-solid fa-xmark"></i>';
                iconContainer.classList.add('text-red-600', 'border-transparent');
                
                // Show which one was correct (optional, but good for learning)
                const allButtons = document.querySelectorAll('.btn-option');
                const currentOptions = gameData[currentLevelIndex].questions[currentQuestionIndex].options;
                
                // Find correct text to highlight the right button
                let correctText = "";
                currentOptions.forEach(opt => { if(opt.correct) correctText = opt.text; });
                
                allButtons.forEach(btn => {
                    if(btn.innerText.includes(correctText)) {
                         setTimeout(() => {
                             btn.classList.add('border-green-500', 'bg-green-100');
                         }, 500);
                    }
                });
            }

            setTimeout(() => {
                currentQuestionIndex++;
                if (currentQuestionIndex < gameData[currentLevelIndex].questions.length) {
                    loadQuestion();
                } else {
                    endLevel();
                }
            }, 2000); // Slightly longer delay so kids can read the correct answer
        }

        function updateScore() {
            document.getElementById('score-display').innerText = score;
        }

        function endLevel() {
            currentLevelIndex++;
            if (currentLevelIndex < gameData.length) {
                prepareLevelIntro();
            } else {
                showResultScreen();
            }
        }

        function showResultScreen() {
            document.getElementById('final-student-name').innerText = playerName;
            document.getElementById('final-score').innerText = score;
            showScreen('result-screen');
            startConfetti();
        }

        function sendToWhatsApp() {
            const phoneNumber = "6281349582525";
            let predikat = "";
            if(score === 100) predikat = "Luar Biasa (Sempurna)";
            else if(score >= 80) predikat = "Sangat Baik";
            else if(score >= 60) predikat = "Baik";
            else predikat = "Perlu Belajar Lagi";

            const message = `Assalamu'alaikum Bu Guru.\n\nSaya *${playerName}* dari kelas *1B SDIT Az-zahra* telah selesai bermain game edukasi 'Petualangan Aturan Ceria'.\n\nTotal Bintang (Nilai) saya adalah: *${score}* ⭐\nPredikat: *${predikat}*\n\nTerima kasih Bu Guru! 🙏`;
            const encodedMessage = encodeURIComponent(message);
            const waUrl = `https://wa.me/${phoneNumber}?text=${encodedMessage}`;
            
            // Membuka tab baru menuju WhatsApp
            window.open(waUrl, '_blank');
        }

        function resetGame() {
            stopConfetti();
            // Go back to start screen so they don't have to re-enter name
            showScreen('start-screen');
        }

        // Simple Canvas Confetti System
        const canvas = document.getElementById('confetti-canvas');
        const ctx = canvas.getContext('2d');
        let confettis = [];
        let confettiActive = false;

        function resizeCanvas() {
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
        }
        window.addEventListener('resize', resizeCanvas);
        resizeCanvas();

        function startConfetti() {
            confettiActive = true;
            confettis = [];
            for (let i = 0; i < 150; i++) {
                confettis.push({
                    x: Math.random() * canvas.width,
                    y: Math.random() * canvas.height - canvas.height,
                    w: Math.random() * 10 + 5,
                    h: Math.random() * 10 + 5,
                    color: `hsl(${Math.random() * 360}, 100%, 50%)`,
                    speedY: Math.random() * 3 + 2,
                    speedX: Math.random() * 2 - 1,
                    rot: Math.random() * 360,
                    rotSpeed: Math.random() * 10 - 5
                });
            }
            animateConfetti();
        }

        function stopConfetti() {
            confettiActive = false;
            ctx.clearRect(0, 0, canvas.width, canvas.height);
        }

        function animateConfetti() {
            if (!confettiActive) return;
            ctx.clearRect(0, 0, canvas.width, canvas.height);
            
            confettis.forEach(c => {
                c.y += c.speedY;
                c.x += c.speedX;
                c.rot += c.rotSpeed;

                if (c.y > canvas.height) {
                    c.y = -10;
                    c.x = Math.random() * canvas.width;
                }

                ctx.save();
                ctx.translate(c.x, c.y);
                ctx.rotate(c.rot * Math.PI / 180);
                ctx.fillStyle = c.color;
                ctx.fillRect(-c.w / 2, -c.h / 2, c.w, c.h);
                ctx.restore();
            });

            requestAnimationFrame(animateConfetti);
        }
    </script>
</body>
</html>
