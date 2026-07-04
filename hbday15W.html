<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>HAPPY BDAY KELLY KELLY 👑</title>
    <!-- Tailwind CSS for rapid styling -->
    <script src="https://cdn.jsdelivr.net/npm/@tailwindcss/browser@4"></script>
    <!-- Canvas Confetti for particle effects -->
    <script src="https://cdn.jsdelivr.net/npm/canvas-confetti@1.9.3/dist/confetti.browser.min.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Fredoka+One&family=Space+Grotesk:wght=700&display=swap');
        
        body {
            font-family: 'Fredoka One', cursive;
            background: linear-gradient(135deg, #ff007f, #7f00ff, #00f0ff);
            background-size: 400% 400%;
            animation: gradientBG 10s ease infinite;
            overflow-x: hidden;
            touch-action: manipulation; /* Prevents zooming on double tap for the game */
        }

        @keyframes gradientBG {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }

        .y2k-text {
            font-family: 'Space Grotesk', sans-serif;
            text-shadow: 4px 4px 0px #000, -2px -2px 0px #000, 2px -2px 0px #000, -2px 2px 0px #000;
        }

        .floating {
            animation: float 3s ease-in-out infinite;
        }

        @keyframes float {
            0%, 100% { transform: translateY(0px) rotate(0deg); }
            50% { transform: translateY(-15px) rotate(3deg); }
        }

        @keyframes rocketLaunch {
            0% { bottom: -15vh; transform: translateX(-50%) scale(0.6); opacity: 1; }
            80% { bottom: 55vh; transform: translateX(-50%) scale(1.4); opacity: 1; }
            100% { bottom: 60vh; transform: translateX(-50%) scale(0); opacity: 0; }
        }
        .rocket-fly {
            position: absolute;
            left: 50%;
            animation: rocketLaunch 0.8s cubic-bezier(0.25, 1, 0.5, 1) forwards;
        }

        /* Slither minigame container */
        #game-overlay {
            display: none; /* Hidden by default */
        }
        #game-overlay.active {
            display: flex;
        }
    </style>
</head>
<body class="min-h-screen flex flex-col items-center justify-center p-4 text-white">

    <div id="meme-zone" class="fixed inset-0 pointer-events-none z-[9999]"></div>

    <!-- Slither Game Overlay -->
    <div id="game-overlay" class="fixed inset-0 z-[10000] bg-black/90 flex-col items-center justify-center">
        <div class="absolute top-4 left-4 z-[10001] text-pink-300 font-bold text-xl y2k-text">
            SCORE: <span id="game-score">0</span>
        </div>
        <button onclick="stopGame()" class="absolute top-4 right-4 z-[10001] bg-red-600 hover:bg-red-500 text-white px-4 py-2 rounded-xl font-bold border-b-4 border-red-900 active:border-b-0 uppercase text-sm">
            ❌ Exit Game
        </button>
        <canvas id="gameCanvas" class="w-full h-full cursor-crosshair"></canvas>
    </div>

    <main class="relative z-10 bg-black/40 backdrop-blur-md p-6 rounded-3xl border-4 border-pink-400 max-w-lg w-full text-center shadow-2xl space-y-6">
        
        <header class="space-y-2">
            <h1 class="text-4xl md:text-5xl font-black text-pink-300 y2k-text tracking-wider uppercase animate-bounce">
                KELLY KELLY !
            </h1>
            <p class="text-yellow-300 tracking-wide text-xl y2k-text">⚡ 15 & SLAYING SINCE JULY 4, 2011 ⚡</p>
        </header>

        <section class="flex flex-col items-center justify-center relative my-4">
            <div id="cake-emoji" class="text-8xl cursor-pointer select-none transition-transform duration-150 hover:scale-125 floating" onclick="triggerCakeRocket()">
                🎂
            </div>
            <p class="text-xs text-cyan-200 mt-2 animate-pulse">👇 CLICK THE CAKE FOR THE CHAD LAUNCH 👇</p>
        </section>

        <!-- NEW MINIGAME BUTTON -->
        <section class="w-full">
            <button onclick="startGame()" class="w-full bg-gradient-to-r from-green-400 to-emerald-600 hover:from-green-500 hover:to-emerald-700 font-bold py-3 px-4 rounded-xl border-b-4 border-green-900 active:border-b-0 transition-all text-lg uppercase y2k-text tracking-widest shadow-lg">
                🐍 Play Slither Kelly 🐍
            </button>
        </section>

        <section class="grid grid-cols-2 gap-4 text-sm">
            <div class="bg-purple-900/60 p-3 rounded-xl border border-purple-400">
                <span class="block text-gray-300">Total Rizz Count</span>
                <span id="rizz-stat" class="text-2xl font-bold text-green-400">10,000+</span>
            </div>
            <div class="bg-purple-900/60 p-3 rounded-xl border border-purple-400">
                <span class="block text-gray-300">Aura Tier</span>
                <span class="text-2xl font-bold text-amber-400">INFINITE</span>
            </div>
        </section>

        <!-- SOUNDBOARD -->
        <section class="space-y-3">
            <h3 class="text-left text-pink-300 text-sm tracking-widest uppercase">🔊 Brainrot Audio Loops</h3>
            <div class="grid grid-cols-2 gap-2">
                <button onclick="playBrainrotTune('tiki')" class="bg-gradient-to-r from-pink-500 to-purple-600 hover:from-pink-600 hover:to-purple-700 font-bold py-2 px-4 rounded-xl border-b-4 border-purple-900 active:border-b-0 transition-all text-sm uppercase">
                    🎵 tiki tiki
                </button>
                <button onclick="playBrainrotTune('sixseven')" class="bg-gradient-to-r from-cyan-500 to-blue-600 hover:from-cyan-600 hover:to-blue-700 font-bold py-2 px-4 rounded-xl border-b-4 border-blue-900 active:border-b-0 transition-all text-sm uppercase">
                    🎵 677777
                </button>
                <button onclick="playBrainrotTune('hbday')" class="bg-gradient-to-r from-yellow-500 to-amber-600 hover:from-yellow-600 hover:to-amber-700 font-bold py-2 px-4 rounded-xl border-b-4 border-amber-900 active:border-b-0 transition-all text-sm uppercase">
                    🎵 hbday 15
                </button>
                <button onclick="playBrainrotTune('yara')" class="bg-gradient-to-r from-emerald-500 to-green-600 hover:from-emerald-600 hover:to-green-700 font-bold py-2 px-4 rounded-xl border-b-4 border-green-900 active:border-b-0 transition-all text-sm uppercase">
                    🎵 Yara Yara
                </button>
            </div>
            <p class="text-[10px] text-purple-300">Tap a button to play! Tap it again to turn off.</p>
        </section>

        <section class="bg-white/10 p-4 rounded-2xl border border-white/20 space-y-2">
            <h4 class="text-sm text-cyan-300">Generate Hype Message:</h4>
            <div id="hype-box" class="text-md font-mono bg-black/30 p-3 rounded-lg text-white min-h-12 flex items-center justify-center text-center font-bold px-2">
                Click below to cook...
            </div>
            <button onclick="generateHype()" class="w-full bg-white text-purple-900 hover:bg-gray-200 font-black py-2 rounded-xl transition-colors text-xs uppercase tracking-widest">
                🔥 Cook dynamic text 🔥
            </button>
        </section>

    </main>

    <footer class="mt-4 text-xs text-white/50 z-10">
        Made for the literal legend Kelly Kelly
    </footer>

    <script>
        // --- EXISTING LOGIC ---
        let rizzCounter = 10000;
        let audioCtx = null;
        let activeAudio = null;
        let activeTrack = null;

        const trackFiles = {
            'tiki': 'https://cdn.jsdelivr.net/gh/loquiiiiiiiiii/Bdaytracks/QMIIR_-_TIKI_TIKI_(SkySound.cc).mp3',
            'sixseven': 'https://cdn.jsdelivr.net/gh/loquiiiiiiiiii/Bdaytracks/Laurinha%20Costa%20-%20Six%20Seven.mp3',
            'hbday': 'https://cdn.jsdelivr.net/gh/loquiiiiiiiiii/Bdaytracks/nesrality-happy-birthday-jazz-band-style-117435.mp3',
            'yara': 'https://cdn.jsdelivr.net/gh/loquiiiiiiiiii/Bdaytracks/Yara%20Yara%20Ya%20Phonk%20(Ultra%20Slowed).mp3'
        };

        function initAudioCtx() {
            if (!audioCtx) {
                audioCtx = new (window.AudioContext || window.webkitAudioContext)();
            }
        }

        function stopCurrentAudio() {
            if (activeAudio) {
                activeAudio.pause();
                activeAudio.currentTime = 0;
            }
            activeTrack = null;
            activeAudio = null;
        }

        function playBrainrotTune(track) {
            const isSameTrack = (activeTrack === track);
            stopCurrentAudio();
            if (isSameTrack) return;
            activeTrack = track;
            activeAudio = new Audio(trackFiles[track]);
            activeAudio.loop = true; 
            activeAudio.play().catch(e => {
                console.log("Audio load error:", e);
                alert("LOADING ERROR:\n" + e.message + "\n\nTarget URL:\n" + trackFiles[track]);
            });
            spawnFloatingElement(`🎵 NOW PLAYING: ${track.toUpperCase()}`);
        }

        document.addEventListener('visibilitychange', () => {
            if (document.hidden) stopCurrentAudio();
        });
        window.addEventListener('pagehide', () => stopCurrentAudio());

        function triggerCakeRocket() {
            rizzCounter += 1000;
            document.getElementById('rizz-stat').innerText = rizzCounter.toLocaleString() + "+";
            initAudioCtx();

            const container = document.getElementById('meme-zone');
            const rocket = document.createElement('div');
            rocket.className = 'rocket-fly text-5xl z-[9999]';
            rocket.innerHTML = '🚀';
            container.appendChild(rocket);

            try {
                const osc = audioCtx.createOscillator();
                const gain = audioCtx.createGain();
                osc.type = 'sawtooth';
                osc.frequency.setValueAtTime(100, audioCtx.currentTime);
                osc.frequency.exponentialRampToValueAtTime(1200, audioCtx.currentTime + 0.8);
                gain.gain.setValueAtTime(0.1, audioCtx.currentTime);
                gain.gain.linearRampToValueAtTime(0, audioCtx.currentTime + 0.8);
                osc.connect(gain);
                gain.connect(audioCtx.destination);
                osc.start();
                osc.stop(audioCtx.currentTime + 0.8);
            } catch(e){}

            setTimeout(() => {
                rocket.remove();
                try {
                    const boomSound = new Audio('https://cdn.jsdelivr.net/gh/loquiiiiiiiiii/Bdaytracks/defecation-sound.mp3');
                    boomSound.play().catch(err => console.log("SFX playback blocked or delayed:", err));
                } catch(e){
                    console.log("Audio setup failed:", e);
                }

                confetti({ particleCount: 200, spread: 100, origin: { y: 0.4 } });

                const textBoom = document.createElement('div');
                textBoom.className = 'absolute text-7xl md:text-9xl font-black text-yellow-300 y2k-text font-sans z-[9999] select-none pointer-events-none transition-all duration-1000 ease-out opacity-100 whitespace-nowrap';
                textBoom.innerText = 'W 15';
                textBoom.style.left = '50%';
                textBoom.style.top = '40%';
                textBoom.style.transform = 'translate(-50%, -50%) scale(0.5)';
                container.appendChild(textBoom);

                setTimeout(() => {
                    textBoom.style.transform = 'translate(-50%, -50%) scale(1.4)';
                    textBoom.style.opacity = '0';
                }, 50);

                setTimeout(() => textBoom.remove(), 1050);

            }, 750);
        }

        function spawnFloatingElement(content) {
            const container = document.getElementById('meme-zone');
            const el = document.createElement('div');
            el.className = 'absolute text-2xl md:text-3xl font-extrabold text-cyan-300 y2k-text transition-all duration-1000 ease-out opacity-100 select-none pointer-events-none z-[9999] whitespace-nowrap';
            el.innerText = content;
            el.style.left = Math.random() * 50 + 25 + '%';
            el.style.top = '55%';
            el.style.transform = 'translateX(-50%)';
            container.appendChild(el);

            setTimeout(() => {
                el.style.transform = 'translate(-50%, -120px) scale(1.2)';
                el.style.opacity = '0';
            }, 50);

            setTimeout(() => el.remove(), 1050);
        }

        const hypes = [
            "W 15 bro", 
            "brigor ayieeee", 
            "hbday Kelly Kelly", 
            "#notababyanymore", 
            "officiallyavoter", 
            "so sigma", 
            "tiki tiki phonk?"
        ];

        function generateHype() {
            const randomHype = hypes[Math.floor(Math.random() * hypes.length)];
            document.getElementById('hype-box').innerText = randomHype;
            spawnFloatingElement(randomHype);
        }


        // --- SLITHER MINIGAME LOGIC ---
        const canvas = document.getElementById('gameCanvas');
        const ctx = canvas.getContext('2d');
        
        let gameActive = false;
        let animFrame;
        
        // Load Assets
        const kellyHead = new Image();
        kellyHead.src = 'https://cdn.jsdelivr.net/gh/loquiiiiiiiiii/Bdaytracks/FB_IMG_1783136211394.jpg';
        
        const laurenceOrb = new Image();
        laurenceOrb.src = 'https://cdn.jsdelivr.net/gh/loquiiiiiiiiii/Bdaytracks/Screenshot_2026-07-04-11-37-23-330_com.facebook.katana.png';

        // Game State
        let snake = { x: 0, y: 0, speed: 4, radius: 25 };
        let mouse = { x: window.innerWidth / 2, y: window.innerHeight / 2 };
        let history = []; 
        let score = 0;
        let snakeLength = 10; 
        const historySpacing = 6; // Space between trailing segments
        let foods = [];

        function resizeCanvas() {
            canvas.width = window.innerWidth;
            canvas.height = window.innerHeight;
            if (!gameActive) {
                snake.x = canvas.width / 2;
                snake.y = canvas.height / 2;
            }
        }
        window.addEventListener('resize', resizeCanvas);
        resizeCanvas();

        // Input Listeners
        canvas.addEventListener('mousemove', (e) => { mouse.x = e.clientX; mouse.y = e.clientY; });
        canvas.addEventListener('touchmove', (e) => { 
            mouse.x = e.touches[0].clientX; 
            mouse.y = e.touches[0].clientY; 
            e.preventDefault(); 
        }, { passive: false });

        function spawnFood() {
            foods.push({
                x: Math.random() * (canvas.width - 100) + 50,
                y: Math.random() * (canvas.height - 100) + 50,
                radius: 20
            });
        }

        function startGame() {
            document.getElementById('game-overlay').classList.add('active');
            gameActive = true;
            score = 0;
            snakeLength = 10;
            history = [];
            foods = [];
            snake.x = canvas.width / 2;
            snake.y = canvas.height / 2;
            mouse.x = snake.x; 
            mouse.y = snake.y;
            document.getElementById('game-score').innerText = score;
            
            for(let i=0; i<3; i++) spawnFood(); // Start with 3 Laurence orbs
            
            gameLoop();
        }

        function stopGame() {
            document.getElementById('game-overlay').classList.remove('active');
            gameActive = false;
            cancelAnimationFrame(animFrame);
        }

        function drawCircularImage(img, x, y, radius) {
            if (!img.complete) return;
            ctx.save();
            ctx.beginPath();
            ctx.arc(x, y, radius, 0, Math.PI * 2);
            ctx.closePath();
            ctx.clip();
            // Draw image scaled to fit the circle
            ctx.drawImage(img, x - radius, y - radius, radius * 2, radius * 2);
            ctx.restore();
            
            // Draw a cute neon border around images
            ctx.beginPath();
            ctx.arc(x, y, radius, 0, Math.PI * 2);
            ctx.strokeStyle = '#ff007f';
            ctx.lineWidth = 3;
            ctx.stroke();
        }

        function gameLoop() {
            if (!gameActive) return;

            // Clear Screen
            ctx.clearRect(0, 0, canvas.width, canvas.height);

            // Movement logic
            const dx = mouse.x - snake.x;
            const dy = mouse.y - snake.y;
            const distance = Math.hypot(dx, dy);

            if (distance > snake.speed) {
                snake.x += (dx / distance) * snake.speed;
                snake.y += (dy / distance) * snake.speed;
            }

            // Record history for the tail
            history.unshift({ x: snake.x, y: snake.y });
            if (history.length > snakeLength * historySpacing) {
                history.pop();
            }

            // Draw Tail (Back to front)
            for (let i = history.length - 1; i >= 0; i -= historySpacing) {
                const segment = history[i];
                if (segment) {
                    ctx.beginPath();
                    ctx.arc(segment.x, segment.y, snake.radius * 0.8, 0, Math.PI * 2);
                    ctx.fillStyle = i % (historySpacing*2) === 0 ? '#ff007f' : '#00f0ff'; // Alternating colors
                    ctx.fill();
                    ctx.strokeStyle = '#fff';
                    ctx.lineWidth = 1;
                    ctx.stroke();
                }
            }

            // Draw Foods
            for (let i = foods.length - 1; i >= 0; i--) {
                let f = foods[i];
                drawCircularImage(laurenceOrb, f.x, f.y, f.radius);

                // Collision Detection with Head
                const distToFood = Math.hypot(snake.x - f.x, snake.y - f.y);
                if (distToFood < snake.radius + f.radius) {
                    foods.splice(i, 1);
                    score += 1;
                    snakeLength += 2; // Grow snake
                    document.getElementById('game-score').innerText = score;
                    spawnFood();
                    // Occasionally spawn an extra food
                    if (Math.random() > 0.5) spawnFood(); 
                }
            }

            // Draw Head (Kelly)
            drawCircularImage(kellyHead, snake.x, snake.y, snake.radius);

            animFrame = requestAnimationFrame(gameLoop);
        }
    </script>
</body>
</html>
