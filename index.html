<!DOCTYPE html>
<html lang="ha">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DIGITAL_INGINIYA - Domains App</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap');
        body {
            font-family: 'Inter', system-ui, sans-serif;
        }
        .pi-gradient {
            background: linear-gradient(135deg, #4F46E5, #7C3AED);
        }
        .domain-card {
            transition: all 0.3s cubic-bezier(0.4, 0, 0.2, 1);
        }
        .domain-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 25px -5px rgb(0 0 0 / 0.1), 0 8px 10px -6px rgb(0 0 0 / 0.1);
        }
        .nav-active {
            border-bottom: 3px solid #6366F1;
        }
        .pi-logo {
            animation: pulse 2s infinite;
        }
    </style>
</head>
<body class="bg-zinc-950 text-white min-h-screen">

    <!-- TOP NAV -->
    <nav class="fixed top-0 left-0 right-0 z-50 bg-zinc-900 border-b border-zinc-800">
        <div class="max-w-screen-xl mx-auto px-4">
            <div class="flex justify-between items-center h-16">
                <div class="flex items-center gap-3">
                    <div class="w-9 h-9 bg-indigo-600 rounded-2xl flex items-center justify-center text-xl font-bold">DI</div>
                    <div>
                        <span class="text-2xl font-bold tracking-tighter">DIGITAL</span>
                        <span class="text-2xl font-bold text-indigo-400 tracking-tighter">INGINIYA</span>
                    </div>
                </div>
                
                <div class="hidden md:flex items-center gap-8 text-sm font-medium">
                    <a href="#" onclick="showSection('home')" class="hover:text-indigo-400 nav-active" id="nav-home">Gida</a>
                    <a href="#" onclick="showSection('marketplace')" class="hover:text-indigo-400" id="nav-market">Kasuwa</a>
                    <a href="#" onclick="showSection('my-domains')" class="hover:text-indigo-400" id="nav-mydomains">Domains Na</a>
                    <a href="#" onclick="showSection('admin')" class="hover:text-indigo-400" id="nav-admin">Admin</a>
                </div>

                <div class="flex items-center gap-4">
                    <div onclick="togglePiWallet()" class="flex items-center gap-2 bg-zinc-800 hover:bg-zinc-700 px-4 py-2 rounded-3xl cursor-pointer text-sm">
                        <i class="fa-brands fa-bitcoin text-amber-400"></i>
                        <span id="pi-balance" class="font-mono">1,245.78 π</span>
                    </div>
                    <div class="w-9 h-9 bg-zinc-700 rounded-2xl flex items-center justify-center cursor-pointer" onclick="showProfile()">
                        👤
                    </div>
                </div>
            </div>
        </div>
    </nav>

    <div class="pt-20 pb-24 max-w-screen-xl mx-auto px-4">

        <!-- HOME / HERO -->
        <section id="home-section" class="section">
            <div class="py-16 text-center">
                <div class="inline-flex items-center gap-2 bg-zinc-900 px-6 py-3 rounded-3xl mb-6 border border-zinc-700">
                    <div class="pi-logo w-6 h-6 bg-gradient-to-br from-amber-400 to-yellow-500 rounded-full flex items-center justify-center text-xs font-bold text-black">π</div>
                    <span class="text-sm font-medium">Pi Network Ecosystem</span>
                </div>
                <h1 class="text-6xl md:text-7xl font-bold tracking-tighter mb-6 leading-none">
                    Sayar da <span class="text-transparent bg-clip-text bg-gradient-to-r from-indigo-400 to-purple-400">Domains</span><br>
                    a cikin Pi Ecosystem
                </h1>
                <p class="max-w-lg mx-auto text-zinc-400 text-lg mb-10">
                    Kasuwar Domains mafi kyau a Pi Network. Saka hannun jari, sayarwa, da kula da sunayen yanar gizo masu daraja.
                </p>
                <div class="flex flex-col sm:flex-row gap-4 justify-center">
                    <button onclick="showSection('marketplace')" 
                            class="px-10 py-4 bg-indigo-600 hover:bg-indigo-500 rounded-3xl font-semibold text-lg flex items-center justify-center gap-3">
                        <i class="fas fa-search"></i>
                        Bincika Domains
                    </button>
                    <button onclick="togglePiWallet()" 
                            class="px-10 py-4 border border-zinc-700 hover:border-zinc-400 rounded-3xl font-semibold text-lg flex items-center justify-center gap-3">
                        <i class="fa-brands fa-bitcoin"></i>
                        Haɗa Wallet
                    </button>
                </div>
            </div>

            <!-- Featured Domains -->
            <div class="mt-12">
                <h2 class="text-2xl font-semibold mb-6 flex items-center gap-3">
                    <span>⭐ Featured Domains</span>
                </h2>
                <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-6" id="featured-domains">
                    <!-- Populated by JS -->
                </div>
            </div>
        </section>

        <!-- MARKETPLACE -->
        <section id="marketplace-section" class="section hidden">
            <div class="mb-8">
                <div class="relative">
                    <input id="search-input" type="text" placeholder="Bincika domain (misali: example.pi)" 
                           class="w-full bg-zinc-900 border border-zinc-700 rounded-3xl py-6 px-8 text-lg focus:outline-none focus:border-indigo-500">
                    <button onclick="searchDomains()" 
                            class="absolute right-4 top-1/2 -translate-y-1/2 bg-indigo-600 hover:bg-indigo-500 px-10 py-4 rounded-3xl font-medium">
                        Bincika
                    </button>
                </div>
            </div>

            <div class="flex gap-4 mb-8 overflow-x-auto pb-4">
                <button onclick="filterCategory('all')" class="category-btn active px-6 py-3 bg-zinc-800 hover:bg-zinc-700 rounded-3xl text-sm font-medium whitespace-nowrap">Duk</button>
                <button onclick="filterCategory('premium')" class="category-btn px-6 py-3 bg-zinc-800 hover:bg-zinc-700 rounded-3xl text-sm font-medium whitespace-nowrap">Premium</button>
                <button onclick="filterCategory('tech')" class="category-btn px-6 py-3 bg-zinc-800 hover:bg-zinc-700 rounded-3xl text-sm font-medium whitespace-nowrap">Tech</button>
                <button onclick="filterCategory('finance')" class="category-btn px-6 py-3 bg-zinc-800 hover:bg-zinc-700 rounded-3xl text-sm font-medium whitespace-nowrap">Finance</button>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6" id="domain-list">
                <!-- Populated by JS -->
            </div>
        </section>

        <!-- MY DOMAINS -->
        <section id="my-domains-section" class="section hidden">
            <h2 class="text-3xl font-bold mb-8">Domains Na</h2>
            <div id="my-domains-list" class="space-y-6">
                <!-- Populated by JS -->
            </div>
        </section>

        <!-- ADMIN DASHBOARD -->
        <section id="admin-section" class="section hidden">
            <div class="flex justify-between items-center mb-8">
                <h2 class="text-3xl font-bold">Admin Dashboard</h2>
                <div class="flex gap-4">
                    <button onclick="refreshAdmin()" class="px-6 py-3 bg-zinc-800 rounded-3xl text-sm flex items-center gap-2 hover:bg-zinc-700">
                        <i class="fas fa-sync"></i> Refresh
                    </button>
                    <button onclick="addNewDomain()" class="px-6 py-3 bg-emerald-600 hover:bg-emerald-500 rounded-3xl text-sm flex items-center gap-2">
                        <i class="fas fa-plus"></i> Ƙara Domain
                    </button>
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-4 gap-6 mb-10">
                <div class="bg-zinc-900 rounded-3xl p-6 border border-zinc-700">
                    <div class="text-zinc-400 text-sm">Total Domains</div>
                    <div id="stat-total" class="text-5xl font-bold mt-2">248</div>
                </div>
                <div class="bg-zinc-900 rounded-3xl p-6 border border-zinc-700">
                    <div class="text-zinc-400 text-sm">Sold Today</div>
                    <div id="stat-sold" class="text-5xl font-bold mt-2 text-emerald-400">12</div>
                </div>
                <div class="bg-zinc-900 rounded-3xl p-6 border border-zinc-700">
                    <div class="text-zinc-400 text-sm">Pi Volume</div>
                    <div id="stat-volume" class="text-5xl font-bold mt-2">18.4K π</div>
                </div>
                <div class="bg-zinc-900 rounded-3xl p-6 border border-zinc-700">
                    <div class="text-zinc-400 text-sm">Active Users</div>
                    <div id="stat-users" class="text-5xl font-bold mt-2">1,892</div>
                </div>
            </div>

            <div class="bg-zinc-900 rounded-3xl p-6">
                <h3 class="font-semibold mb-4 text-lg">Recent Transactions</h3>
                <table class="w-full">
                    <thead>
                        <tr class="border-b border-zinc-700 text-zinc-400 text-sm">
                            <th class="py-4 text-left">Domain</th>
                            <th class="py-4 text-left">Buyer</th>
                            <th class="py-4 text-left">Amount</th>
                            <th class="py-4 text-left">Date</th>
                        </tr>
                    </thead>
                    <tbody id="transactions-body" class="text-sm">
                        <!-- Populated by JS -->
                    </tbody>
                </table>
            </div>
        </section>
    </div>

    <!-- BOTTOM NAV (Mobile) -->
    <nav class="fixed bottom-0 left-0 right-0 bg-zinc-900 border-t border-zinc-800 md:hidden z-50">
        <div class="flex justify-around py-3">
            <button onclick="showSection('home')" class="flex flex-col items-center text-xs gap-1 text-indigo-400">
                <i class="fas fa-home text-xl"></i>
                <span>Gida</span>
            </button>
            <button onclick="showSection('marketplace')" class="flex flex-col items-center text-xs gap-1">
                <i class="fas fa-store text-xl"></i>
                <span>Kasuwa</span>
            </button>
            <button onclick="showSection('my-domains')" class="flex flex-col items-center text-xs gap-1">
                <i class="fas fa-folder text-xl"></i>
                <span>Na</span>
            </button>
            <button onclick="showSection('admin')" class="flex flex-col items-center text-xs gap-1">
                <i class="fas fa-crown text-xl"></i>
                <span>Admin</span>
            </button>
        </div>
    </nav>

    <!-- PI WALLET MODAL -->
    <div id="wallet-modal" class="hidden fixed inset-0 bg-black/80 flex items-center justify-center z-[100]">
        <div class="bg-zinc-900 rounded-3xl max-w-md w-full mx-4 overflow-hidden">
            <div class="p-8">
                <div class="flex justify-between items-center mb-8">
                    <div class="flex items-center gap-3">
                        <div class="text-4xl">π</div>
                        <div>
                            <div class="font-bold text-2xl">Pi Testnet Wallet</div>
                            <div class="text-emerald-400 text-sm">Connected • Testnet</div>
                        </div>
                    </div>
                    <button onclick="togglePiWallet()" class="text-3xl text-zinc-400">×</button>
                </div>
                
                <div class="bg-zinc-800 rounded-2xl p-6 mb-8">
                    <div class="text-sm text-zinc-400 mb-2">Balance</div>
                    <div class="text-6xl font-mono font-bold" id="modal-balance">1,245.78 π</div>
                </div>

                <div class="space-y-6">
                    <button onclick="simulatePayment()" 
                            class="w-full py-6 bg-gradient-to-r from-amber-500 to-yellow-500 text-black font-bold text-xl rounded-3xl flex items-center justify-center gap-3 hover:brightness-110">
                        <i class="fas fa-paper-plane"></i>
                        Yi Payment (Test)
                    </button>
                    
                    <div class="grid grid-cols-2 gap-4 text-sm">
                        <div onclick="copyAddress()" class="bg-zinc-800 hover:bg-zinc-700 p-5 rounded-3xl cursor-pointer text-center">
                            <i class="fas fa-copy mb-2"></i><br>
                            Copy Address
                        </div>
                        <div onclick="showQR()" class="bg-zinc-800 hover:bg-zinc-700 p-5 rounded-3xl cursor-pointer text-center">
                            <i class="fas fa-qrcode mb-2"></i><br>
                            Show QR
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- DOMAIN DETAIL MODAL -->
    <div id="domain-modal" class="hidden fixed inset-0 bg-black/80 flex items-center justify-center z-[100]">
        <div class="bg-zinc-900 rounded-3xl max-w-lg w-full mx-4">
            <div class="p-8" id="modal-content">
                <!-- JS injected -->
            </div>
        </div>
    </div>

    <script>
        // Tailwind script already included via CDN
        function initTailwind() {
            // Already configured via CDN
        }

        // Mock Domains Data
        let domains = [
            {
                id: 1,
                name: "blockchain.pi",
                price: 1250,
                category: "premium",
                owner: "You",
                status: "available",
                description: "Premium domain for blockchain projects in Pi ecosystem."
            },
            {
                id: 2,
                name: "inginiya.ng",
                price: 450,
                category: "tech",
                owner: "Aliyu",
                status: "available",
                description: "Perfect for tech startups and engineering firms."
            },
            {
                id: 3,
                name: "paypi.ng",
                price: 890,
                category: "finance",
                owner: "Fatima",
                status: "sold",
                description: "Ideal for payment solutions using Pi Network."
            },
            {
                id: 4,
                name: "crypto.ng",
                price: 2100,
                category: "premium",
                owner: "You",
                status: "available",
                description: "High value crypto related domain."
            },
            {
                id: 5,
                name: "digital.ng",
                price: 320,
                category: "tech",
                owner: "Ibrahim",
                status: "available",
                description: "Great for digital services."
            }
        ];

        let myDomains = [
            {
                name: "blockchain.pi",
                expiry: "2027-06-15",
                value: 1250
            },
            {
                name: "myproject.pi",
                expiry: "2026-11-03",
                value: 680
            }
        ];

        let transactions = [
            { domain: "finance.pi", buyer: "0xA1b2...C3d4", amount: "890 π", date: "Yau" },
            { domain: "shop.ng", buyer: "0xF9e8...7d6c", amount: "420 π", date: "Jiya" },
            { domain: "ai.ng", buyer: "0x12ab...34ef", amount: "1340 π", date: "2 days ago" }
        ];

        // Render Functions
        function renderFeatured() {
            const container = document.getElementById('featured-domains');
            container.innerHTML = '';
            domains.slice(0, 3).forEach(domain => {
                const card = document.createElement('div');
                card.className = `domain-card bg-zinc-900 rounded-3xl overflow-hidden border border-zinc-700 cursor-pointer`;
                card.innerHTML = `
                    <div class="p-6">
                        <div class="flex justify-between items-start">
                            <div>
                                <div class="text-2xl font-bold">${domain.name}</div>
                                <div class="text-emerald-400 text-sm mt-1">${domain.category.toUpperCase()}</div>
                            </div>
                            <div class="text-right">
                                <div class="text-3xl font-mono">${domain.price} <span class="text-amber-400">π</span></div>
                            </div>
                        </div>
                        <p class="text-zinc-400 text-sm mt-6 line-clamp-2">${domain.description}</p>
                    </div>
                    <div onclick="viewDomain(${domain.id}); event.stopImmediatePropagation()" class="border-t border-zinc-700 py-4 px-6 text-indigo-400 hover:bg-zinc-800 text-center text-sm font-medium">
                        Duba Cikakken Bayani →
                    </div>
                `;
                container.appendChild(card);
            });
        }

        function renderAllDomains(filteredDomains = domains) {
            const container = document.getElementById('domain-list');
            container.innerHTML = '';
            filteredDomains.forEach(domain => {
                const card = document.createElement('div');
                card.className = `domain-card bg-zinc-900 rounded-3xl overflow-hidden border border-zinc-700`;
                card.innerHTML = `
                    <div class="p-6">
                        <div class="font-mono text-xl font-semibold">${domain.name}</div>
                        <div class="flex justify-between items-end mt-8">
                            <div>
                                <div class="text-xs text-zinc-400">PRICE</div>
                                <div class="text-4xl font-bold">${domain.price}π</div>
                            </div>
                            <button onclick="viewDomain(${domain.id}); event.stopImmediatePropagation()" 
                                    class="bg-indigo-600 hover:bg-indigo-500 px-8 py-4 rounded-2xl text-sm font-medium">
                                Sayi
                            </button>
                        </div>
                    </div>
                `;
                container.appendChild(card);
            });
        }

        function renderMyDomains() {
            const container = document.getElementById('my-domains-list');
            container.innerHTML = '';
            myDomains.forEach((domain, index) => {
                const card = document.createElement('div');
                card.className = "bg-zinc-900 rounded-3xl p-6 flex justify-between items-center border border-zinc-700";
                card.innerHTML = `
                    <div>
                        <div class="text-2xl font-bold">${domain.name}</div>
                        <div class="text-zinc-400 text-sm">Expires: ${domain.expiry}</div>
                    </div>
                    <div class="text-right">
                        <div class="text-emerald-400 font-mono">${domain.value} π</div>
                        <button onclick="renewDomain(${index})" class="mt-4 text-xs bg-zinc-800 hover:bg-zinc-700 px-5 py-2 rounded-2xl">Renew</button>
                    </div>
                `;
                container.appendChild(card);
            });
        }

        function renderTransactions() {
            const tbody = document.getElementById('transactions-body');
            tbody.innerHTML = '';
            transactions.forEach(tx => {
                const row = document.createElement('tr');
                row.className = "border-b border-zinc-800 last:border-none hover:bg-zinc-800/50";
                row.innerHTML = `
                    <td class="py-5 font-medium">${tx.domain}</td>
                    <td class="py-5 text-zinc-400 font-mono text-sm">${tx.buyer}</td>
                    <td class="py-5 font-semibold text-emerald-400">${tx.amount}</td>
                    <td class="py-5 text-zinc-400">${tx.date}</td>
                `;
                tbody.appendChild(row);
            });
        }

        // View single domain
        function viewDomain(id) {
            const domain = domains.find(d => d.id === id);
            if (!domain) return;
            
            const modal = document.getElementById('domain-modal');
            const content = document.getElementById('modal-content');
            
            content.innerHTML = `
                <div class="flex justify-between items-center">
                    <h2 class="text-3xl font-bold">${domain.name}</h2>
                    <button onclick="closeModal()" class="text-4xl text-zinc-400">×</button>
                </div>
                <div class="my-8 bg-zinc-800 rounded-2xl p-8 text-center">
                    <div class="text-7xl font-mono font-bold mb-2">${domain.price} <span class="text-3xl">π</span></div>
                    <div class="text-emerald-400">Available Now</div>
                </div>
                <p class="text-zinc-300 mb-8">${domain.description}</p>
                <div class="flex gap-4">
                    <button onclick="buyDomain(${domain.id}); closeModal()" 
                            class="flex-1 py-6 bg-gradient-to-r from-indigo-500 to-purple-500 rounded-3xl font-bold text-xl">
                        BUY NOW
                    </button>
                    <button onclick="closeModal()" 
                            class="flex-1 py-6 border border-zinc-600 rounded-3xl font-medium">
                        Close
                    </button>
                </div>
            `;
            modal.classList.remove('hidden');
        }

        function closeModal() {
            document.getElementById('domain-modal').classList.add('hidden');
        }

        // Buy simulation
        function buyDomain(id) {
            alert(`✅ Purchase of domain successful!\n\nYou paid via Pi Testnet Wallet.\nTransaction ID: PI_${Math.floor(Math.random()*100000000)}`);
            // Move to my domains
            const domain = domains.find(d => d.id === id);
            if (domain) {
                myDomains.unshift({
                    name: domain.name,
                    expiry: "2028-06-27",
                    value: domain.price
                });
                renderMyDomains();
            }
        }

        // Simulate payment
        function simulatePayment() {
            const balanceEl = document.getElementById('modal-balance');
            let balance = parseFloat(balanceEl.textContent);
            balance -= 450;
            balanceEl.textContent = balance.toFixed(2) + " π";
            document.getElementById('pi-balance').textContent = balance.toFixed(2) + " π";
            
            alert("✅ Test Payment Successful on Pi Testnet!\n\nAmount: 450 π\nStatus: Confirmed");
        }

        function togglePiWallet() {
            const modal = document.getElementById('wallet-modal');
            modal.classList.toggle('hidden');
        }

        function copyAddress() {
            alert("📋 Wallet address copied:\nG4k9...X7pQ (Testnet)");
        }

        function showQR() {
            alert("📱 QR Code for Pi Wallet displayed (demo)");
        }

        // Section switching
        function showSection(section) {
            document.querySelectorAll('.section').forEach(sec => {
                sec.classList.add('hidden');
            });
            
            if (section === 'home') {
                document.getElementById('home-section').classList.remove('hidden');
            } else if (section === 'marketplace') {
                document.getElementById('marketplace-section').classList.remove('hidden');
            } else if (section === 'my-domains') {
                document.getElementById('my-domains-section').classList.remove('hidden');
            } else if (section === 'admin') {
                document.getElementById('admin-section').classList.remove('hidden');
            }
            
            // Update active nav
            document.querySelectorAll('.nav-active').forEach(el => el.classList.remove('nav-active'));
        }

        function searchDomains() {
            const query = document.getElementById('search-input').value.toLowerCase().trim();
            if (!query) {
                renderAllDomains();
                return;
            }
            const filtered = domains.filter(d => d.name.toLowerCase().includes(query));
            renderAllDomains(filtered);
        }

        function filterCategory(cat) {
            document.querySelectorAll('.category-btn').forEach(btn => btn.classList.remove('active', 'bg-indigo-600'));
            
            const activeBtn = Array.from(document.querySelectorAll('.category-btn')).find(btn => {
                if (cat === 'all') return btn.textContent === 'Duk';
                return btn.getAttribute('onclick').includes(cat);
            });
            if (activeBtn) activeBtn.classList.add('active', 'bg-indigo-600');
            
            if (cat === 'all') {
                renderAllDomains();
            } else {
                const filtered = domains.filter(d => d.category === cat);
                renderAllDomains(filtered);
            }
        }

        function renewDomain(index) {
            alert(`✅ Domain ${myDomains[index].name} renewed successfully for another year!`);
        }

        function addNewDomain() {
            const name = prompt("Enter new domain name (e.g. newproject.pi):");
            if (name) {
                domains.unshift({
                    id: Date.now(),
                    name: name,
                    price: Math.floor(Math.random() * 2000) + 200,
                    category: "tech",
                    owner: "Admin",
                    status: "available",
                    description: "Newly listed domain."
                });
                renderAllDomains();
                alert("✅ New domain added successfully!");
            }
        }

        function refreshAdmin() {
            document.getElementById('stat-sold').textContent = Math.floor(Math.random() * 20) + 8;
            document.getElementById('stat-volume').textContent = (Math.random() * 15 + 10).toFixed(1) + "K π";
            alert("Dashboard refreshed ✓");
        }

        function showProfile() {
            alert("👤 Profile\n\nUsername: @digital_inginiya\nPi Rank: Pioneer Level 4\nJoined: March 2025");
        }

        // Initialize everything
        function initializeApp() {
            renderFeatured();
            renderAllDomains();
            renderMyDomains();
            renderTransactions();
            
            // Keyboard support for search
            document.getElementById('search-input').addEventListener('keypress', function(e) {
                if (e.key === 'Enter') searchDomains();
            });
            
            // Show home by default
            showSection('home');
            
            console.log("%cDIGITAL_INGINIYA App Loaded Successfully ✓\nPi Testnet Ready", "color:#6366f1; font-family:monospace");
        }

        // Boot the app
        window.onload = initializeApp;
    </script>
</body>
</html>
