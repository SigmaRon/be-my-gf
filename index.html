<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Will You Be My Girlfriend?</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@700&family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
            user-select: none;
            -webkit-user-select: none;
        }

        html, body {
            width: 100%;
            height: 100%;
            overflow: hidden;
            font-family: 'Poppins', sans-serif;
        }

        body {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            position: relative;
        }

        /* Animated background particles */
        .particle {
            position: absolute;
            border-radius: 50%;
            background: rgba(255, 255, 255, 0.1);
            animation: float 20s infinite;
            pointer-events: none;
        }

        @keyframes float {
            0%, 100% { transform: translateY(100vh) scale(0); opacity: 0; }
            10% { opacity: 1; }
            90% { opacity: 1; }
            100% { transform: translateY(-100vh) scale(1); opacity: 0; }
        }

        /* Main container */
        #mainContainer {
            position: absolute;
            top: 50%;
            left: 50%;
            transform: translate(-50%, -50%);
            text-align: center;
            z-index: 10;
            width: 90%;
            max-width: 600px;
        }

        /* Card design */
        .card {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            border-radius: 30px;
            padding: 60px 40px;
            box-shadow: 0 25px 50px rgba(0,0,0,0.15);
            border: 1px solid rgba(255,255,255,0.2);
        }

        /* Header */
        .heart-icon {
            font-size: 60px;
            margin-bottom: 20px;
            animation: heartbeat 1.5s ease-in-out infinite;
            display: inline-block;
        }

        @keyframes heartbeat {
            0%, 100% { transform: scale(1); }
            50% { transform: scale(1.1); }
        }

        h1 {
            font-family: 'Playfair Display', serif;
            font-size: 2.5em;
            color: #2d3748;
            margin-bottom: 15px;
            line-height: 1.2;
        }

        .subtitle {
            font-size: 1.1em;
            color: #718096;
            margin-bottom: 40px;
            font-weight: 300;
        }

        /* Progress indicator */
        .progress-container {
            margin-bottom: 30px;
        }

        .progress-bar {
            width: 100%;
            height: 8px;
            background: #e2e8f0;
            border-radius: 10px;
            overflow: hidden;
            margin-bottom: 10px;
        }

        .progress-fill {
            height: 100%;
            background: linear-gradient(90deg, #f093fb 0%, #f5576c 100%);
            width: 0%;
            transition: width 0.3s ease;
            border-radius: 10px;
        }

        .attempt-text {
            font-size: 0.9em;
            color: #a0aec0;
            font-weight: 600;
        }

        /* Buttons */
        .button-container {
            display: flex;
            gap: 20px;
            justify-content: center;
            flex-wrap: wrap;
            margin-top: 20px;
        }

        button {
            padding: 18px 50px;
            font-size: 1.2em;
            font-weight: 600;
            border: none;
            border-radius: 50px;
            cursor: pointer;
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
            font-family: 'Poppins', sans-serif;
            position: relative;
            overflow: hidden;
        }

        button::before {
            content: '';
            position: absolute;
            top: 50%;
            left: 50%;
            width: 0;
            height: 0;
            border-radius: 50%;
            background: rgba(255,255,255,0.3);
            transform: translate(-50%, -50%);
            transition: width 0.6s, height 0.6s;
        }

        button:active::before {
            width: 300px;
            height: 300px;
        }

        #yesBtn {
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            color: white;
            box-shadow: 0 4px 15px rgba(102, 126, 234, 0.4);
        }

        #yesBtn:hover {
            transform: translateY(-2px);
            box-shadow: 0 8px 25px rgba(102, 126, 234, 0.5);
        }

        #noBtn {
            background: #e2e8f0;
            color: #718096;
            box-shadow: 0 4px 15px rgba(0,0,0,0.1);
            position: fixed;
            z-index: 100;
        }

        #noBtn:hover {
            background: #cbd5e0;
        }

        /* Message area */
        #messageArea {
            margin-top: 25px;
            min-height: 30px;
        }

        .message {
            font-size: 1em;
            color: #e53e3e;
            font-weight: 500;
            opacity: 0;
            transform: translateY(-10px);
            animation: fadeInDown 0.3s forwards;
        }

        @keyframes fadeInDown {
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* Floating emoji */
        .floating-emoji {
            position: absolute;
            font-size: 24px;
            pointer-events: none;
            animation: floatUp 2s ease-out forwards;
            z-index: 5;
        }

        @keyframes floatUp {
            0% { transform: translateY(0) scale(1); opacity: 1; }
            100% { transform: translateY(-100px) scale(1.5); opacity: 0; }
        }

        /* Celebration Screen */
        #celebration {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
            z-index: 1000;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            overflow: hidden;
        }

        .celebration-content {
            text-align: center;
            z-index: 10;
            padding: 20px;
        }

        .celebration-content h1 {
            font-family: 'Playfair Display', serif;
            font-size: 3.5em;
            color: white;
            margin-bottom: 20px;
            animation: bounce 1s infinite alternate;
            text-shadow: 2px 2px 4px rgba(0,0,0,0.2);
        }

        @keyframes bounce {
            from { transform: translateY(0); }
            to { transform: translateY(-20px); }
        }

        .celebration-subtitle {
            font-size: 1.5em;
            color: rgba(255,255,255,0.9);
            margin-bottom: 40px;
            font-weight: 300;
        }

        /* Meme grid */
        .meme-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(150px, 1fr));
            gap: 20px;
            max-width: 800px;
            width: 90%;
            margin: 0 auto;
            padding: 20px;
        }

        .meme-item {
            position: relative;
            border-radius: 20px;
            overflow: hidden;
            box-shadow: 0 10px 30px rgba(0,0,0,0.3);
            animation: popIn 0.5s ease-out backwards;
            background: white;
        }

        .meme-item img {
            width: 100%;
            height: 150px;
            object-fit: cover;
            display: block;
        }

        @keyframes popIn {
            0% { transform: scale(0) rotate(-10deg); opacity: 0; }
            100% { transform: scale(1) rotate(0deg); opacity: 1; }
        }

        /* Confetti */
        .confetti {
            position: absolute;
            width: 10px;
            height: 10px;
            top: -10px;
            animation: confetti-fall linear forwards;
        }

        @keyframes confetti-fall {
            0% { transform: translateY(0) rotate(0deg); opacity: 1; }
            100% { transform: translateY(100vh) rotate(720deg); opacity: 0; }
        }

        /* Responsive */
        @media (max-width: 600px) {
            .card { padding: 40px 25px; }
            h1 { font-size: 2em; }
            .celebration-content h1 { font-size: 2.5em; }
            button { padding: 15px 35px; font-size: 1em; }
            .meme-item img { height: 120px; }
        }
    </style>
</head>
<body>
    <!-- Background particles -->
    <div id="particles"></div>

    <!-- Main Container -->
    <div id="mainContainer">
        <div class="card">
            <div class="heart-icon">💝</div>
            <h1>Will You Be My Girlfriend?</h1>
            <p class="subtitle">I've been wanting to ask you this for a while...</p>

            <div class="progress-container">
                <div class="progress-bar">
                    <div class="progress-fill" id="progressFill"></div>
                </div>
                <div class="attempt-text">Attempts: <span id="attemptCount">0</span> / 10</div>
            </div>

            <div class="button-container">
                <button id="yesBtn" onclick="sayYes()">Yes, I will! 💕</button>
            </div>

            <div id="messageArea"></div>
        </div>
    </div>

    <!-- NO Button (teleports anywhere on screen) -->
    <button id="noBtn" onclick="teleportNo(event)">Not yet</button>

    <!-- Celebration Screen -->
    <div id="celebration">
        <div class="celebration-content">
            <h1>She Said Yes! 🎉</h1>
            <p class="celebration-subtitle">Best day ever! I love you! ❤️</p>
        </div>
        <div class="meme-grid" id="memeGrid"></div>
    </div>

    <script>
        let attempts = 0;
        const maxAttempts = 10;

        const messages = [
            "Are you sure? 🤔",
            "Think about it! 💭",
            "Please? 🥺",
            "I'll be good! 😇",
            "Don't break my heart 💔",
            "Pretty please? 🌹",
            "You're so mean! 😢",
            "Give me a chance! 🎲",
            "I'm begging! 🙏",
            "Okay, you win... 😏"
        ];

        const emojis = ['💕', '💖', '💗', '💓', '💝', '🌸', '✨', '😢', '🥺', '🌹'];

        const celebrationMemes = [
            "https://media.tenor.com/YcjMpOSyz2AAAAAM/marin-kitagawa-blush.gif",
            "https://media.tenor.com/28LwTmfU58cAAAAe/anime-happy.png",
            "https://media.tenor.com/XpOVHJWYrckAAAAM/celebration-tuvigif.gif",
            "https://media.tenor.com/mMdISEZLmKUAAAAM/jumping-yay.gif",
            "https://media.tenor.com/1WljoHHuIeoAAAAM/cute.gif",
            "https://images.stockcake.com/public/9/e/3/9e344496-5b7f-45f7-8bac-aeed43927caf_large/victorious-anime-celebration-stockcake.jpg",
            "https://images.stockcake.com/public/4/a/3/4a3b90b6-5056-4fca-b168-74523f7308b7_large/joyful-anime-celebration-stockcake.jpg",
            "https://images.stockcake.com/public/7/5/4/754591cf-9be7-43d5-9d94-8a77db8a4358_large/victory-jump-celebration-stockcake.jpg"
        ];

        // Create background particles
        function createParticles() {
            const container = document.getElementById('particles');
            for (let i = 0; i < 20; i++) {
                const particle = document.createElement('div');
                particle.className = 'particle';
                particle.style.width = Math.random() * 100 + 50 + 'px';
                particle.style.height = particle.style.width;
                particle.style.left = Math.random() * 100 + 'vw';
                particle.style.animationDelay = Math.random() * 20 + 's';
                particle.style.animationDuration = (Math.random() * 10 + 15) + 's';
                container.appendChild(particle);
            }
        }

        createParticles();

        // Position NO button initially (to the right of YES)
        function positionNoButton() {
            const yesBtn = document.getElementById('yesBtn');
            const noBtn = document.getElementById('noBtn');
            const yesRect = yesBtn.getBoundingClientRect();

            noBtn.style.left = (yesRect.right + 20) + 'px';
            noBtn.style.top = yesRect.top + 'px';
        }

        // Call after page loads
        window.onload = positionNoButton;
        window.onresize = positionNoButton;

        function teleportNo(event) {
            event.stopPropagation();

            if (attempts >= maxAttempts) {
                // Transform to YES
                const noBtn = document.getElementById('noBtn');
                noBtn.textContent = "Okay, YES! 💕";
                noBtn.style.background = "linear-gradient(135deg, #667eea 0%, #764ba2 100%)";
                noBtn.style.color = "white";
                noBtn.style.transform = "scale(1.1)";
                noBtn.onclick = sayYes;
                showMessage("You got me! Click now! 😘");
                return;
            }

            attempts++;
            document.getElementById('attemptCount').textContent = attempts;
            document.getElementById('progressFill').style.width = (attempts / maxAttempts * 100) + '%';

            // Teleport to random position anywhere on screen
            const noBtn = document.getElementById('noBtn');
            const btnWidth = noBtn.offsetWidth;
            const btnHeight = noBtn.offsetHeight;

            // Keep within viewport bounds
            const maxX = window.innerWidth - btnWidth - 20;
            const maxY = window.innerHeight - btnHeight - 20;

            const randomX = Math.random() * maxX + 10;
            const randomY = Math.random() * maxY + 10;

            noBtn.style.left = randomX + 'px';
            noBtn.style.top = randomY + 'px';

            // Show message
            showMessage(messages[attempts - 1] || "Click YES! 💕");

            // Create floating emoji at click position
            createFloatingEmoji(event.clientX, event.clientY);

            // Make button slightly smaller each time
            const scale = Math.max(0.7, 1 - (attempts * 0.03));
            noBtn.style.transform = `scale(${scale})`;
        }

        function showMessage(text) {
            const area = document.getElementById('messageArea');
            area.innerHTML = '<div class="message">' + text + '</div>';
        }

        function createFloatingEmoji(x, y) {
            const emoji = document.createElement('div');
            emoji.className = 'floating-emoji';
            emoji.textContent = emojis[attempts - 1] || '💕';
            emoji.style.left = x + 'px';
            emoji.style.top = y + 'px';
            document.body.appendChild(emoji);

            setTimeout(() => emoji.remove(), 2000);
        }

        function sayYes() {
            const celebration = document.getElementById('celebration');
            const memeGrid = document.getElementById('memeGrid');

            celebration.style.display = 'flex';

            // Add memes with stagger
            celebrationMemes.forEach((url, index) => {
                setTimeout(() => {
                    const item = document.createElement('div');
                    item.className = 'meme-item';
                    item.style.animationDelay = index * 0.1 + 's';

                    const img = document.createElement('img');
                    img.src = url;
                    img.alt = 'Celebration!';
                    img.onerror = function() {
                        // Fallback if image fails
                        this.src = 'data:image/svg+xml,<svg xmlns="http://www.w3.org/2000/svg" width="150" height="150"><rect fill="%23ff6b9d" width="150" height="150"/><text fill="white" x="50%" y="50%" text-anchor="middle" dy=".3em" font-size="60">🎉</text></svg>';
                    };

                    item.appendChild(img);
                    memeGrid.appendChild(item);
                }, index * 150);
            });

            // Start confetti
            createConfetti();
        }

        function createConfetti() {
            const colors = ['#f093fb', '#f5576c', '#ffd700', '#00ff88', '#00ccff', '#ff6b9d', '#ffffff'];

            // Initial burst
            for (let i = 0; i < 150; i++) {
                setTimeout(() => {
                    const confetti = document.createElement('div');
                    confetti.className = 'confetti';
                    confetti.style.left = Math.random() * 100 + 'vw';
                    confetti.style.background = colors[Math.floor(Math.random() * colors.length)];
                    confetti.style.animationDuration = (Math.random() * 3 + 2) + 's';
                    confetti.style.borderRadius = Math.random() > 0.5 ? '50%' : '0';
                    confetti.style.width = (Math.random() * 10 + 5) + 'px';
                    confetti.style.height = confetti.style.width;
                    document.getElementById('celebration').appendChild(confetti);

                    setTimeout(() => confetti.remove(), 5000);
                }, i * 20);
            }

            // Continuous confetti
            setInterval(() => {
                const confetti = document.createElement('div');
                confetti.className = 'confetti';
                confetti.style.left = Math.random() * 100 + 'vw';
                confetti.style.background = colors[Math.floor(Math.random() * colors.length)];
                confetti.style.animationDuration = (Math.random() * 2 + 2) + 's';
                document.getElementById('celebration').appendChild(confetti);
                setTimeout(() => confetti.remove(), 4000);
            }, 100);
        }

        // Prevent context menu
        document.addEventListener('contextmenu', e => e.preventDefault());
    </script>
</body>
</html>
