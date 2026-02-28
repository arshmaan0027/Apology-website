<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>I'm Truly Sorry</title>
    <!-- Importing Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Dancing+Script:wght@600&family=Lato:wght@300;400&display=swap" rel="stylesheet">
    
    <style>
        /* --- CSS Styles --- */
        
        /* Reset & Base */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            height: 100vh;
            width: 100%;
            overflow: hidden; /* Prevents scrollbars from floating elements */
            /* Soft Pastel Gradient: Light Pink to Sky Blue */
            background: linear-gradient(to top, #fad0c4 0%, #ffd1ff 100%);
            font-family: 'Lato', sans-serif;
            display: flex;
            justify-content: center;
            align-items: center;
            color: #555;
        }

        /* Floating Hearts Animation Container */
        #particle-container {
            position: absolute;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            pointer-events: none;
            z-index: 1;
        }

        .heart {
            position: absolute;
            color: rgba(255, 105, 180, 0.6);
            font-size: 20px;
            animation: floatUp 6s linear infinite;
            bottom: -20px; /* Start below screen */
        }

        @keyframes floatUp {
            0% { transform: translateY(0) rotate(0deg); opacity: 1; }
            100% { transform: translateY(-110vh) rotate(360deg); opacity: 0; }
        }

        /* Main Content Card */
        .card {
            position: relative;
            z-index: 10;
            background: rgba(255, 255, 255, 0.85);
            backdrop-filter: blur(10px);
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05);
            text-align: center;
            max-width: 500px;
            width: 90%;
            border: 1px solid rgba(255,255,255,0.5);
            
            /* Fade In Animation */
            animation: fadeInUp 1.5s ease-out forwards;
            opacity: 0;
            transform: translateY(20px);
        }

        @keyframes fadeInUp {
            to { opacity: 1; transform: translateY(0); }
        }

        /* Typography */
        h1 {
            font-family: 'Dancing Script', cursive;
            font-size: 3.5rem;
            color: #d6336c;
            margin-bottom: 20px;
            line-height: 1.2;
        }

        p {
            font-size: 1.1rem;
            line-height: 1.6;
            color: #666;
            margin-bottom: 30px;
        }

        /* Buttons */
        button {
            padding: 12px 30px;
            font-size: 1rem;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s ease;
            font-family: 'Lato', sans-serif;
            font-weight: 400;
            letter-spacing: 1px;
        }

        #forgive-btn {
            background-color: #ff6b6b;
            color: white;
            box-shadow: 0 4px 15px rgba(255, 107, 107, 0.4);
        }

        #forgive-btn:hover {
            background-color: #fa5252;
            transform: scale(1.05);
        }

        /* Hidden Message Area */
        #response-message {
            margin-top: 20px;
            display: none;
            color: #d6336c;
            font-weight: bold;
            font-size: 1.2rem;
            animation: popIn 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275);
        }

        @keyframes popIn {
            from { opacity: 0; transform: scale(0.8); }
            to { opacity: 1; transform: scale(1); }
        }

        /* Music Control (Top Right) */
        .music-control {
            position: absolute;
            top: 20px;
            right: 20px;
            z-index: 20;
            background: rgba(255,255,255,0.6);
            border: none;
            border-radius: 50%;
            width: 40px;
            height: 40px;
            cursor: pointer;
            font-size: 18px;
            display: flex;
            align-items: center;
            justify-content: center;
            transition: background 0.3s;
        }

        .music-control:hover {
            background: rgba(255,255,255,0.9);
        }

        /* Mobile Responsiveness */
        @media (max-width: 600px) {
            h1 { font-size: 2.5rem; }
            .card { padding: 30px 20px; width: 95%; }
            p { font-size: 1rem; }
        }

    </style>
</head>
<body>

    <!-- Floating Hearts Background -->
    <div id="particle-container"></div>

    <!-- Background Music Element -->
    <!-- Replace 'your-music-file.mp3' with your actual file name -->
    <audio id="bg-music" loop>
        <source src="your-music-file.mp3" type="audio/mpeg">
        Your browser does not support the audio element.
    </audio>

    <!-- Music Mute/Play Button -->
    <button class="music-control" id="music-btn" title="Toggle Music">🔊</button>

    <!-- Main Apology Card -->
    <div class="card">
        <h1>I’m Truly Sorry ❤️</h1>
        
        <p>
            I know words alone can’t fix what happened, and I take full responsibility for my mistakes. 
            I hurt you, and that is the last thing I ever wanted to do. You deserve so much better, 
            and I am committed to proving that I can be better. <br><br>
            I miss you more than words can say, and I hope you can find it in your heart to forgive me.
        </p>

        <button id="forgive-btn">Will You Forgive Me?</button>

        <div id="response-message">
            <p>❤️ Thank you. I promise to make it right. ❤️</p>
        </div>
    </div>

    <script>
        // --- JavaScript Logic ---

        // 1. Floating Hearts Logic
        const particleContainer = document.getElementById('particle-container');
        
        function createHeart() {
            const heart = document.createElement('div');
            heart.classList.add('heart');
            heart.innerHTML = '❤';
            
            // Random positioning and timing
            heart.style.left = Math.random() * 100 + 'vw';
            heart.style.animationDuration = (Math.random() * 3 + 4) + 's'; // Between 4s and 7s
            heart.style.opacity = Math.random();
            heart.style.fontSize = (Math.random() * 20 + 10) + 'px'; // Size 10px to 30px
            
            particleContainer.appendChild(heart);

            // Remove heart after animation ends to keep DOM clean
            setTimeout(() => {
                heart.remove();
            }, 7000);
        }

        // Spawn a heart every 400ms
        setInterval(createHeart, 400);

        // 2. Button Interaction
        const forgiveBtn = document.getElementById('forgive-btn');
        const responseMsg = document.getElementById('response-message');

        forgiveBtn.addEventListener('click', () => {
            // Hide the button
            forgiveBtn.style.display = 'none';
            
            // Show the sweet message
            responseMsg.style.display = 'block';
            
            // Trigger a confetti burst (simple version using hearts)
            for(let i=0; i<20; i++) {
                createHeart();
            }
        });

        // 3. Music Control Logic
        const music = document.getElementById('bg-music');
        const musicBtn = document.getElementById('music-btn');
        let isMuted = false;

        // Note: Modern browsers block autoplay unless the user has interacted with the page.
        // We attempt to play immediately, but the user might need to click something first.
        window.onload = () => {
            const playPromise = music.play();
            if (playPromise !== undefined) {
                playPromise.catch(error => {
                    console.log("Auto-play prevented. User interaction required to play music.");
                    // Icon indicates sound is off if autoplay fails
                    musicBtn.innerHTML = "🔇"; 
                    isMuted = true;
                });
            }
        };

        musicBtn.addEventListener('click', () => {
            if (isMuted) {
                music.play();
                musicBtn.innerHTML = "🔊";
                isMuted = false;
            } else {
                music.pause();
                musicBtn.innerHTML = "🔇";
                isMuted = true;
            }
        });
    </script>
</body>
</html>
