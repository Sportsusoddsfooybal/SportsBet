<!DOCTYPE html>
<html lang="en" class="h-full">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Sports & Games Dashboard</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800;900&display=swap" rel="stylesheet">
    <script>
        tailwind.config = {
            darkMode: 'class',
            theme: {
                extend: {
                    colors: {
                        primaryRed: '#e60012',
                        darkBg: '#121212',
                        cardBg: '#1e1e1e',
                        accentGreen: '#00b050',
                        accentGold: '#ffcc00'
                    },
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    }
                }
            }
        }
    </script>
    <style>
        body { font-family: 'Inter', sans-serif; background-color: #0a0a0a; color: #fff; user-select: none; }
        .no-scrollbar::-webkit-scrollbar { display: none; }
        .no-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
    </style>
</head>
<body class="h-full flex justify-center items-center bg-[#0a0a0a] text-white">

    <div class="w-full max-w-md h-full md:h-[92vh] md:rounded-3xl bg-darkBg flex flex-col relative overflow-hidden shadow-2xl border border-gray-800">
        
        <!-- Header -->
        <header class="bg-primaryRed px-4 py-3 flex items-center justify-between border-b border-red-700 shrink-0">
            <div class="flex items-center space-x-2">
                <div class="flex items-center bg-black/30 border border-white/20 rounded-full px-3 py-1">
                    <span class="text-[10px] text-accentGold font-bold mr-1">GHS</span>
                    <span id="user-balance" class="text-xs font-black text-white">500.00</span>
                </div>
            </div>
            <h1 class="font-black italic text-lg tracking-wider text-white">SPORTS ARENA</h1>
            <button onclick="switchTab('profile')" class="bg-white text-primaryRed font-black px-2.5 py-1 rounded-md text-xs uppercase shadow">
                Wallet
            </button>
        </header>

        <!-- Main Workspace -->
        <main class="flex-1 flex flex-col overflow-y-auto relative bg-darkBg pb-16">
            
            <!-- HOME TAB: Sports Fixtures -->
            <div id="tab-home" class="p-4 space-y-4">
                <div class="flex space-x-2 overflow-x-auto no-scrollbar pb-1">
                    <button class="bg-primaryRed text-white px-4 py-1.5 rounded-lg text-xs font-bold shrink-0">Football</button>
                    <button class="bg-cardBg text-gray-300 px-4 py-1.5 rounded-lg text-xs font-bold shrink-0 border border-gray-800">Live (12)</button>
                    <button class="bg-cardBg text-gray-300 px-4 py-1.5 rounded-lg text-xs font-bold shrink-0 border border-gray-800">Basketball</button>
                </div>

                <div class="space-y-3" id="fixtures-container">
                    <div class="bg-cardBg p-3.5 rounded-2xl border border-gray-800 space-y-2">
                        <div class="flex justify-between text-[11px] text-gray-400">
                            <span>UEFA Champions League</span>
                            <span>Live 75'</span>
                        </div>
                        <div class="flex justify-between items-center text-sm font-bold">
                            <span>Real Madrid vs Bayern Munich</span>
                            <span class="text-accentGold">2 - 1</span>
                        </div>
                        <div class="grid grid-cols-3 gap-2 pt-2">
                            <button onclick="placeBet('Real Madrid', 1.75)" class="bg-black/40 hover:bg-cardBg p-2 rounded-xl text-center border border-gray-700">
                                <span class="block text-[10px] text-gray-400">1</span>
                                <span class="text-xs font-bold text-accentGreen">1.75</span>
                            </button>
                            <button onclick="placeBet('Draw', 3.40)" class="bg-black/40 hover:bg-cardBg p-2 rounded-xl text-center border border-gray-700">
                                <span class="block text-[10px] text-gray-400">X</span>
                                <span class="text-xs font-bold text-gray-300">3.40</span>
                            </button>
                            <button onclick="placeBet('Bayern Munich', 4.20)" class="bg-black/40 hover:bg-cardBg p-2 rounded-xl text-center border border-gray-700">
                                <span class="block text-[10px] text-gray-400">2</span>
                                <span class="text-xs font-bold text-gray-300">4.20</span>
                            </button>
                        </div>
                    </div>
                </div>
            </div>

            <!-- GAMES TAB: Standard Multiplier Simulation -->
            <div id="tab-games" class="flex flex-col flex-1 hidden">
                <div class="relative w-full h-56 bg-gradient-to-b from-[#090d16] via-[#111936] to-[#121212] flex flex-col items-center justify-center border-b border-gray-800">
                    <div id="game-status" class="text-xs uppercase tracking-widest text-accentGold font-bold mb-1">Ready</div>
                    <div id="multiplier-display" class="text-5xl font-black tracking-wider text-white">1.00x</div>
                </div>
                <div class="p-4 space-y-4">
                    <div class="bg-cardBg p-4 rounded-2xl border border-gray-800 space-y-3">
                        <div class="flex justify-between text-xs text-gray-400">
                            <span>Stake Amount (GHS)</span>
                            <span>Min: 1.00</span>
                        </div>
                        <div class="flex items-center space-x-2">
                            <input type="number" id="game-stake" value="10.00" class="flex-1 bg-black/50 border border-gray-700 rounded-xl p-3 text-center font-bold text-white focus:outline-none">
                            <button id="game-btn" onclick="startMultiplierGame()" class="w-36 bg-accentGreen hover:bg-green-600 text-white font-extrabold py-3.5 rounded-xl text-sm uppercase tracking-wider">
                                Place Bet
                            </button>
                        </div>
                    </div>
                </div>
            </div>

            <!-- PROFILE & WALLET TAB -->
            <div id="tab-profile" class="p-4 space-y-4 hidden">
                <div class="bg-cardBg p-4 rounded-2xl border border-gray-800 space-y-3">
                    <h3 class="text-sm font-bold text-gray-300">Wallet Management</h3>
                    <div class="flex justify-between text-xs text-gray-400">
                        <span>Available Balance</span>
                        <span id="wallet-balance" class="text-accentGold font-bold text-sm">GHS 500.00</span>
                    </div>
                    <div class="flex space-x-2 pt-2">
                        <button onclick="depositFunds(100)" class="flex-1 bg-accentGreen/20 hover:bg-accentGreen text-accentGreen hover:text-white py-2.5 rounded-xl text-xs font-bold border border-accentGreen/40">+ GHS 100</button>
                        <button onclick="depositFunds(500)" class="flex-1 bg-accentGreen/20 hover:bg-accentGreen text-accentGreen hover:text-white py-2.5 rounded-xl text-xs font-bold border border-accentGreen/40">+ GHS 500</button>
                    </div>
                </div>
            </div>

        </main>

        <!-- Bottom Navigation -->
        <nav class="bg-[#181818] border-t border-gray-800 px-4 py-2.5 flex justify-around items-center shrink-0 z-30">
            <button onclick="switchTab('home')" id="nav-home" class="flex flex-col items-center text-primaryRed space-y-0.5">
                <i class="fa-solid fa-house text-lg"></i>
                <span class="text-[10px] font-semibold">Home</span>
            </button>
            <button onclick="switchTab('games')" id="nav-games" class="flex flex-col items-center text-gray-400 hover:text-white space-y-0.5">
                <i class="fa-solid fa-gamepad text-lg"></i>
                <span class="text-[10px] font-semibold">Games</span>
            </button>
            <button onclick="switchTab('profile')" id="nav-profile" class="flex flex-col items-center text-gray-400 hover:text-white space-y-0.5">
                <i class="fa-solid fa-user text-lg"></i>
                <span class="text-[10px] font-semibold">Me</span>
            </button>
        </nav>

        <!-- Toast notification -->
        <div id="toast" class="absolute top-16 left-1/2 transform -translate-x-1/2 bg-[#222] border border-accentGold text-white px-4 py-2 rounded-xl shadow-xl opacity-0 pointer-events-none transition-opacity duration-300 text-xs font-semibold z-50"></div>
    </div>

    <script>
        let balance = 500.00;
        let gameActive = false;
        let currentMult = 1.00;
        let gameInterval = null;

        function showToast(msg) {
            const t = document.getElementById('toast');
            t.innerText = msg;
            t.classList.remove('opacity-0');
            setTimeout(() => t.classList.add('opacity-0'), 2500);
        }

        function updateBalanceUI() {
            document.getElementById('user-balance').innerText = balance.toFixed(2);
            document.getElementById('wallet-balance').innerText = 'GHS ' + balance.toFixed(2);
        }

        function depositFunds(amt) {
            balance += amt;
            updateBalanceUI();
            showToast(`Successfully deposited GHS ${amt.toFixed(2)}`);
        }

        function switchTab(tab) {
            ['home', 'games', 'profile'].forEach(t => {
                document.getElementById('tab-' + t).classList.add('hidden');
                const nav = document.getElementById('nav-' + t);
                if(nav) { nav.classList.remove('text-primaryRed'); nav.classList.add('text-gray-400'); }
            });
            document.getElementById('tab-' + tab).classList.remove('hidden');
            const activeNav = document.getElementById('nav-' + tab);
            if(activeNav) { activeNav.classList.remove('text-gray-400'); activeNav.classList.add('text-primaryRed'); }
        }

        function placeBet(selection, odds) {
            const stake = 10.00;
            if (balance < stake) {
                showToast("Insufficient balance");
                return;
            }
            balance -= stake;
            updateBalanceUI();
            showToast(`Placed GHS ${stake} on ${selection} (@${odds})`);
        }

        function startMultiplierGame() {
            const stake = parseFloat(document.getElementById('game-stake').value) || 10;
            const btn = document.getElementById('game-btn');

            if (!gameActive) {
                if (balance < stake) {
                    showToast("Insufficient balance");
                    return;
                }
                balance -= stake;
                updateBalanceUI();
                gameActive = true;
                currentMult = 1.00;
                
                const targetCrash = 1.20 + Math.random() * 3.5;
                document.getElementById('game-status').innerText = "In Flight...";
                btn.className = "w-36 bg-accentGold text-black font-extrabold py-3.5 rounded-xl text-sm uppercase tracking-wider";
                btn.innerText = "Cash Out";

                const startT = Date.now();
                gameInterval = setInterval(() => {
                    const elapsed = (Date.now() - startT) / 1000;
                    currentMult = 1.00 + Math.pow(elapsed, 1.4) * 0.3;

                    if (currentMult >= targetCrash) {
                        clearInterval(gameInterval);
                        gameActive = false;
                        document.getElementById('multiplier-display').innerText = targetCrash.toFixed(2) + "x";
                        document.getElementById('game-status').innerText = "Crashed";
                        btn.className = "w-36 bg-accentGreen text-white font-extrabold py-3.5 rounded-xl text-sm uppercase tracking-wider";
                        btn.innerText = "Place Bet";
                        showToast("Round crashed!");
                    } else {
                        document.getElementById('multiplier-display').innerText = currentMult.toFixed(2) + "x";
                    }
                }, 50);
            } else {
                clearInterval(gameInterval);
                const win = stake * currentMult;
                balance += win;
                updateBalanceUI();
                gameActive = false;
                showToast(`Cashed out GHS ${win.toFixed(2)} at ${currentMult.toFixed(2)}x!`);
                btn.className = "w-36 bg-accentGreen text-white font-extrabold py-3.5 rounded-xl text-sm uppercase tracking-wider";
                btn.innerText = "Place Bet";
                document.getElementById('game-status').innerText = "Ready";
            }
        }
    </script>
</body>
</html>
