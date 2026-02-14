# For-mine
Your smile is a gentle sunrise that warms the coldest corners of my heart, and your kindness flows like a quiet river, nurturing every dream we share together—truly, you are the poetry my soul has always longed to write." 💖
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, user-scalable=no">
    <title>Eternal Love Proposal</title>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;700&family=Inter:wght@300;500;700&display=swap" rel="stylesheet">
    <style>
        * { box-sizing: border-box; margin: 0; padding: 0; }
        body {
            font-family: 'Inter', sans-serif;
            background: linear-gradient(135deg, #fce4ec 0%, #f8bbd9 50%, #e91e63 100%);
            color: #333;
            overflow-x: hidden;
            min-height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            position: relative;
            -webkit-touch-callout: none;
            -webkit-user-select: none;
            user-select: none;
        }
        .container {
            max-width: 1000px;
            width: 95%;
            padding: 30px;
            background: rgba(255, 255, 255, 0.95);
            border-radius: 25px;
            box-shadow: 0 20px 60px rgba(0, 0, 0, 0.15);
            backdrop-filter: blur(15px);
            position: relative;
            z-index: 1;
        }
        h1, h2 { font-family: 'Playfair Display', serif; color: #c2185b; text-align: center; margin-bottom: 20px; }
        .hidden { display: none; opacity: 0; transform: translateY(20px); transition: all 0.8s cubic-bezier(0.25, 0.46, 0.45, 0.94); }
        .visible { opacity: 1; transform: translateY(0); }
        .fade-in { animation: elegantFade 1.5s cubic-bezier(0.25, 0.46, 0.45, 0.94); }
        @keyframes elegantFade { from { opacity: 0; transform: translateY(30px) scale(0.95); } to { opacity: 1; transform: translateY(0) scale(1); } }
        .typewriter { overflow: hidden; border-right: 4px solid #c2185b; white-space: nowrap; animation: typing 5s steps(60, end), blink 1.2s infinite; font-size: 1.3em; line-height: 1.6; }
        @keyframes typing { from { width: 0; } to { width: 100%; } }
        @keyframes blink { from, to { border-color: transparent; } }
        .particle { position: absolute; font-size: 1.5em; animation: drift 8s infinite linear; pointer-events: none; }
        @keyframes drift { 0% { transform: translateY(100vh) rotate(0deg); } 100% { transform: translateY(-10vh) rotate(360deg); } }
        .cartoon { cursor: pointer; transition: all 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94); }
        .cartoon:hover { transform: scale(1.15) rotate(5deg); filter: drop-shadow(0 5px 10px rgba(0, 0, 0, 0.2)); }
        #game { position: relative; height: 550px; background: linear-gradient(45deg, #fce4ec, #f8bbd9); border-radius: 20px; border: 4px solid #c2185b; margin: 30px 0; overflow: hidden; display: flex; flex-direction: column; justify-content: space-between; align-items: center; padding: 20px; }
        .game-element { position: absolute; font-size: 2.8em; transition: all 0.3s ease; user-select: none; }
        .obstacle { animation: glide 5s infinite linear; }
        @keyframes glide { 0% { left: -15%; } 100% { left: 115%; } }
        #proposal { background: radial-gradient(circle, #0d0d0d 0%, #1a1a2e 100%); color: white; padding: 60px; border-radius: 25px; text-align: center; box-shadow: inset 0 0 100px rgba(233, 30, 99, 0.3); position: relative; overflow: hidden; }
        .confetti { position: absolute; font-size: 1.8em; animation: cascade 6s infinite ease-in-out; }
        @keyframes cascade { 0% { top: -20px; transform: rotate(0deg) scale(1); } 50% { transform: rotate(180deg) scale(1.2); } 100% { top: 100vh; transform: rotate(360deg) scale(0.8); } }
        button { background: linear-gradient(45deg, #fce4ec, #e91e63); border: none; padding: 15px 30px; color: white; font-size: 1.2em; font-weight: 600; cursor: pointer; border-radius: 30px; margin: 15px; transition: all 0.4s cubic-bezier(0.25, 0.46, 0.45, 0.94); box-shadow: 0 8px 25px rgba(0, 0, 0, 0.2); -webkit-tap-highlight-color: transparent; }
        button:hover { transform: translateY(-3px); box-shadow: 0 12px 35px rgba(0, 0, 0, 0.3); }
        button:active { transform: translateY(0); }
        input { padding: 15px; border-radius: 15px; border: 3px solid #c2185b; width: 100%; max-width: 350px; font-size: 1.1em; transition: all 0.3s; outline: none; background: white; color: #333; -webkit-appearance: none; appearance: none; }
        input:focus { border-color: #e91e63; box-shadow: 0 0 10px rgba(233, 30, 99, 0.5); }
        .modal { position: fixed; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0, 0, 0, 0.8); display: flex; justify-content: center; align-items: center; z-index: 1000; backdrop-filter: blur(10px); }
        .modal-content { background: white; padding: 40px; border-radius: 20px; text-align: center; max-width: 450px; box-shadow: 0 15px 40px rgba(0, 0, 0, 0.3); animation: modalPop 0.5s cubic-bezier(0.25, 0.46, 0.45, 0.94); }
        @keyframes modalPop { from { transform: scale(0.8); opacity: 0; } to { transform: scale(1); opacity: 1; } }
        .progress-bar { width: 100%; height: 12px; background: #eee; border-radius: 6px; overflow: hidden; margin: 20px 0; }
        .progress-fill { height: 100%; background: linear-gradient(90deg, #fce4ec, #e91e63); transition: width 0.6s cubic-bezier(0.25, 0.46, 0.45, 0.94); }
        .description { font-style: italic; color: #666; margin-top: 10px; }
    </style>
</head>
<body>
    <div class="container">
        <div id="intro" class="fade-in">
            <h1>💕 Eternal Love Awaits 💕</h1>
            <input type="text" id="nameInput" placeholder="Whisper your beloved's name..." maxlength="20" aria-label="Enter name" ontouchstart="handleInputFocus(event)">
            <button onclick="startJourney()" ontouchstart="startJourney()">Embark on Romance</button>
        </div>
        
        <div id="loading" class="hidden">
            <h2>Weaving Enchantment...</h2>
            <div class="progress-bar"><div class="progress-fill" id="progressFill"></div></div>
        </div>
        
        <div id="texts" class="hidden">
            <p id="text1" class="typewriter"></p>
            <p id="text2" class="typewriter hidden"></p>
            <p id="text3" class="typewriter hidden"></p>
            <button onclick="initiateQuest()" ontouchstart="initiateQuest()" class="hidden">Begin the Heart Quest</button>
        </div>
        
        <div id="game" class="hidden">
            <h2>Whimsical Heart Odyssey 🏹</h2>
            <p>Gather 10 hearts in this enchanted realm! Evade mischief and invoke Cupid's grace.</p>
            <div id="heartsCollected">Hearts Collected: 0/10</div>
            <div id="cupid" class="cartoon game-element" onclick="activatePower()" ontouchstart="activatePower()" aria-label="Cupid's Arrow">🏹</div>
        </div>
        
        <div id="proposal" class="hidden">
            <div id="confettiContainer"></div>
            <h1 id="proposalText"></h1>
            <p class="description">In this moment of pure magic, [Name], your beauty and grace have captivated my soul eternally.</p>
            <button onclick="affirmLove('yes')" ontouchstart="affirmLove('yes')">Yes, My Forever 💍</button>
            <button onclick="affirmLove('maybe')" ontouchstart="affirmLove('maybe')">Cherish the Wait 😊</button>
        </div>
        
        <footer class="hidden" id="footer">
            <button onclick="spreadLove()" ontouchstart="spreadLove()">Share This Enchantment ❤️</button>
        </footer>
    </div>

    <div id="modal" class="modal hidden">
        <div class="modal-content">
            <p id="modalText"></p>
            <button onclick="dismissModal()" ontouchstart="dismissModal()">Continue</button>
        </div>
    </div>

    <script>
        // Global variables for game state
        let belovedName = '';
        let heartCount = 0;
        let powerActivated = false;
        const romanticTexts = [
            "In the tapestry of stars, [Name], your radiance outshines the cosmos, drawing me into a dance of eternal affection...",
            "Like a petal kissed by dawn, [Name], your tenderness blooms in my heart, a symphony of love's sweetest melody...",
            "Together, we shall traverse the realms of joy, [Name], where every heartbeat echoes our unbreakable bond..."
        ];

        // Handle input focus on mobile touch
        function handleInputFocus(event) {
            event.preventDefault();
            document.getElementById('nameInput').focus();
        }

        // Start the journey with name input
        function startJourney() {
            belovedName = document.getElementById('nameInput').value.trim() || 'My Love';
            document.getElementById('intro').classList.add('hidden');
            document.getElementById('loading').classList.remove('hidden');
            simulateEnchantment(() => {
                document.getElementById('loading').classList.add('hidden');
                document.getElementById('texts').classList.remove('hidden');
                unveilTexts();
                scatterHearts();
            });
        }

        // Simulate loading progress
        function simulateEnchantment(callback) {
            let enchantment = 0;
            const ritual = setInterval(() => {
                enchantment += 8;
                document.getElementById('progressFill').style.width = enchantment + '%';
                if (enchantment >= 100) {
                    clearInterval(ritual);
                    callback();
                }
            }, 250);
        }

        // Display sequential romantic texts
        function unveilTexts() {
            const textElements = [document.getElementById('text1'), document.getElementById('text2'), document.getElementById('text3')];
            textElements.forEach((el, index) => {
                el.textContent = romanticTexts[index].replace('[Name]', belovedName);
                setTimeout(() => el.classList.add('visible'), index * 6000);
            });
            setTimeout(() => document.querySelector('#texts button').classList.remove('hidden'), 18000);
        }

        // Transition to game
        function initiateQuest() {
            document.getElementById('texts').classList.add('hidden');
            document.getElementById('game').classList.remove('hidden');
            setupQuest();
        }

        // Initialize game elements
        function setupQuest() {
            const realm = document.getElementById('game');
            // Add hearts
            for (let i = 0; i < 10; i++) {
                const heart = document.createElement('div');
                heart.textContent = '❤️';
                heart.className = 'cartoon game-element';
                heart.style.left = Math.random() * 75 + '%';
                heart.style.top = Math.random() * 75 + '%';
                const handleInteraction = (e) => {
                    e.preventDefault();
                    harvestHeart(heart);
                };
                heart.addEventListener('click', handleInteraction);
                heart.addEventListener('touchstart', handleInteraction, { passive: false });
                realm.appendChild(heart);
            }
            // Add obstacles
            for (let i = 0; i < 6; i++) {
                const mischief = document.createElement('div');
                mischief.textContent = i % 2 === 0 ? '👹' : '🍫';
                mischief.className = 'obstacle game-element';
                mischief.style.top = Math.random() * 75 + '%';
                const handleInteraction = (e) => {
                    e.preventDefault();
                    diminishHeart();
                };
                mischief.addEventListener('click', handleInteraction);
                mischief.addEventListener('touchstart', handleInteraction, { passive: false });
                realm.appendChild(mischief);
            }
            // Add Easter egg creatures
            const creatures = ['🐰', '🐱', '🐦'];
            creatures.forEach(creature => {
                const sprite = document.createElement('div');
                sprite.textContent = creature;
                sprite.className = 'cartoon game-element';
                sprite.style.left = Math.random() * 75 + '%';
                sprite.style.top = Math.random() * 75 + '%';
                const handleInteraction = (e) => {
                    e.preventDefault();
                    revealBonus();
                };
                sprite.addEventListener('click', handleInteraction);
                sprite.addEventListener('touchstart', handleInteraction, { passive: false });
                realm.appendChild(sprite);
            });
        }

        // Collect heart
        function harvestHeart(heart) {
            heart.remove();
            heartCount++;
            document.getElementById('heartsCollected').textContent = `Hearts Collected: ${heartCount}/10`;
            if (heartCount >= 10) concludeQuest();
        }

        // Lose heart on obstacle
        function diminishHeart() {
            heartCount = Math.max(0, heartCount - 1);
            document.getElementById('heartsCollected').textContent = `Hearts Collected: ${heartCount}/10`;
        }

        // Activate power-up
        function activatePower() {
            if (!powerActivated) {
                powerActivated = true;
                displayModal("Cupid's Arrow awakens! Fortune and swiftness are bestowed upon you!");
                setTimeout(() => powerActivated = false, 6000);
            }
        }

        // Reveal bonus
        function revealBonus() {
            displayModal(`A hidden treasure: ${belovedName}, your allure is beyond compare! 😘`);
        }

        // End game and show proposal
        function concludeQuest() {
            document.getElementById('game').classList.add('hidden');
            document.getElementById('proposal').classList.remove('hidden');
            document.getElementById('proposalText').textContent = `${belovedName}, will you be my eternal companion?`;
            unleashConfetti();
        }

        // Handle love affirmation
        function affirmLove(response) {
            const affirmation = response === 'yes' ? `Eternal bliss, ${belovedName}! Our love story begins anew. 🎉` :
