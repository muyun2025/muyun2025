<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>藍娜黛兒 Lanadelle 逆齡眼膠 | 互動體驗館</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <script src="https://cdn.jsdelivr.net/npm/chart.js"></script>
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Noto+Sans+TC:wght@300;400;500;700&display=swap');

        body {
            font-family: 'Noto Sans TC', sans-serif;
            background-color: #FDFBF7; /* Soft Cream */
            color: #4A4A4A;
        }

        .chart-container {
            position: relative;
            width: 100%;
            max-width: 800px;
            margin-left: auto;
            margin-right: auto;
            height: 350px;
            max-height: 400px;
        }

        @media (min-width: 768px) {
            .chart-container {
                height: 400px;
            }
        }

        .glass-panel {
            background: rgba(255, 255, 255, 0.8);
            backdrop-filter: blur(12px);
            border: 1px solid rgba(255, 255, 255, 0.3);
            box-shadow: 0 4px 6px -1px rgba(0, 0, 0, 0.05);
        }

        .btn-primary {
            background: linear-gradient(135deg, #D4AF37 0%, #C5A028 100%);
            color: white;
            transition: all 0.3s ease;
        }

        .btn-primary:hover {
            transform: translateY(-2px);
            box-shadow: 0 10px 15px -3px rgba(197, 160, 40, 0.3);
        }

        .section-fade {
            opacity: 0;
            transform: translateY(20px);
            transition: opacity 0.8s ease-out, transform 0.8s ease-out;
        }

        .section-visible {
            opacity: 1;
            transform: translateY(0);
        }

        /* Custom Scrollbar */
        ::-webkit-scrollbar {
            width: 8px;
        }
        ::-webkit-scrollbar-track {
            background: #F1F1F1;
        }
        ::-webkit-scrollbar-thumb {
            background: #D4AF37;
            border-radius: 4px;
        }
    </style>
    <!-- Chosen Palette: Rose Gold & Porcelain (Warm Neutrals + Gold Accents) -->
    <!-- Application Structure Plan:
         1. Hero Section: Emotional hook ("Don't let eyes reveal age").
         2. Interactive Diagnosis: User clicks symptoms -> Personalized context.
         3. The Formula (Ingredients): Tabbed explorer (Science vs Nature) to organize complex info.
         4. Clinical Evidence: Interactive Chart.js visualizing the 28-day efficacy data.
         5. How it Works: Step-by-step block flow explaining the Peptide mechanism (Botox-like).
         6. CTA/Usage: Simple guide and purchase prompt.
         Rationale: This structure moves from Problem -> Solution -> Proof -> Action, mirroring a consultative sales flow suitable for high-end skincare.
    -->
    <!-- Visualization & Content Choices:
         - Diagnostics: Interactive buttons to engage user immediately.
         - Ingredients: Card grid with icons (Unicode) to make text digestible.
         - Charts: Chart.js Line Chart for clinical data. Best for showing trends over time (14, 21, 28 days).
         - Mechanism: HTML/CSS Flowchart. Clearer than text, avoids SVG complexity.
         - CONFIRMATION: NO SVG graphics used. NO Mermaid JS used.
    -->
</head>
<body class="antialiased">

    <!-- Navigation -->
    <nav class="fixed w-full z-50 glass-panel border-b border-stone-200">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="flex justify-between items-center h-16">
                <!-- Logo removed as requested -->
                <div class="flex-shrink-0 flex items-center">
                    <!-- <span class="text-2xl font-bold text-stone-800 tracking-wider">LANADELLE</span> -->
                </div>
                <div class="hidden md:flex space-x-8">
                    <button onclick="scrollToSection('diagnosis')" class="text-stone-600 hover:text-[#D4AF37] transition-colors">肌膚檢測</button>
                    <button onclick="scrollToSection('ingredients')" class="text-stone-600 hover:text-[#D4AF37] transition-colors">獨家配方</button>
                    <button onclick="scrollToSection('evidence')" class="text-stone-600 hover:text-[#D4AF37] transition-colors">實證數據</button>
                    <button onclick="scrollToSection('usage')" class="text-stone-600 hover:text-[#D4AF37] transition-colors">使用方式</button>
                </div>
                <button onclick="window.location.href='https://smarthealthypro.com/'" class="bg-stone-900 text-white px-4 py-2 rounded-full hover:bg-stone-700 transition text-sm">
                    加入會員購買
                </button>
            </div>
        </div>
    </nav>

    <!-- Hero Section -->
    <header class="relative pt-32 pb-20 lg:pt-48 lg:pb-32 overflow-hidden">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 relative z-10 text-center">
            <h1 class="text-4xl md:text-6xl font-bold text-stone-800 mb-6 leading-tight">
                眼神，決定你的<br/><span class="text-[#D4AF37]">視覺年齡</span>
            </h1>
            <p class="mt-4 max-w-2xl mx-auto text-xl text-stone-600">
                別讓眼周細紋出賣你的青春。藍娜黛兒逆齡眼膠，結合頂級胜肽科技與天然植萃，為您打造不動刀的居家醫美體驗。
            </p>
            <div class="mt-10 flex justify-center gap-4">
                <button onclick="scrollToSection('evidence')" class="btn-primary px-8 py-3 rounded-full text-lg font-medium shadow-lg">
                    見證 28 天奇蹟
                </button>
                <button onclick="scrollToSection('ingredients')" class="bg-white text-stone-800 border border-stone-300 px-8 py-3 rounded-full text-lg font-medium hover:bg-stone-50 transition">
                    探索成分
                </button>
            </div>
        </div>
        <!-- Decorative Background Elements (CSS Shapes) -->
        <div class="absolute top-0 left-0 w-full h-full overflow-hidden -z-10 opacity-30">
            <div class="absolute top-[-10%] left-[-10%] w-96 h-96 bg-yellow-100 rounded-full blur-3xl"></div>
            <div class="absolute bottom-[-10%] right-[-10%] w-[500px] h-[500px] bg-stone-200 rounded-full blur-3xl"></div>
        </div>
    </header>

    <!-- Section 1: Diagnostics (Interactive) -->
    <section id="diagnosis" class="py-20 bg-white section-fade">
        <div class="max-w-4xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <span class="text-[#D4AF37] font-semibold tracking-wide uppercase">肌膚檢測</span>
                <h2 class="text-3xl font-bold text-stone-900 mt-2">你有以下眼周困擾嗎？</h2>
                <p class="mt-4 text-stone-500">
                    點選您目前的肌膚狀況，讓我們為您分析藍娜黛兒如何協助您改善。
                </p>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-6 mb-10" id="symptom-grid">
                <!-- Injected via JS -->
            </div>

            <div id="diagnosis-result" class="hidden glass-panel p-8 rounded-2xl text-center border-l-4 border-[#D4AF37]">
                <h3 class="text-xl font-bold text-stone-800 mb-2">我們的解決方案</h3>
                <p class="text-stone-600" id="diagnosis-text">
                    <!-- Dynamic Text -->
                </p>
            </div>
        </div>
    </section>

    <!-- Section 2: Ingredients (The Solution) -->
    <section id="ingredients" class="py-20 bg-[#FDFBF7] section-fade">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <span class="text-[#D4AF37] font-semibold tracking-wide uppercase">獨家配方</span>
                <h2 class="text-3xl font-bold text-stone-900 mt-2">黑科技與植萃的完美結合</h2>
                <p class="mt-4 text-stone-500 max-w-2xl mx-auto">
                    我們精心挑選了最具活性的科學成分與最純淨的天然萃取，打造出黃金比例的抗老配方。點擊下方卡片了解更多。
                </p>
            </div>

            <!-- Filter Tabs -->
            <div class="flex justify-center mb-10 space-x-4">
                <button onclick="filterIngredients('all')" class="ing-filter active px-6 py-2 rounded-full text-sm font-medium bg-[#D4AF37] text-white shadow-md transition">全部</button>
                <button onclick="filterIngredients('science')" class="ing-filter px-6 py-2 rounded-full text-sm font-medium bg-white text-stone-600 hover:bg-stone-100 transition">科研成分</button>
                <button onclick="filterIngredients('nature')" class="ing-filter px-6 py-2 rounded-full text-sm font-medium bg-white text-stone-600 hover:bg-stone-100 transition">天然植萃</button>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8" id="ingredient-grid">
                <!-- Injected via JS -->
            </div>
        </div>
    </section>

    <!-- Section 3: Mechanism (Process Flow) -->
    <section class="py-20 bg-white section-fade border-y border-stone-100">
        <div class="max-w-5xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="text-center mb-12">
                <span class="text-[#D4AF37] font-semibold tracking-wide uppercase">作用原理</span>
                <h2 class="text-3xl font-bold text-stone-900 mt-2">不動刀的「類肉毒」科技</h2>
                <p class="mt-4 text-stone-500">
                    了解 SpecPed® SKE 胜肽複合物如何像隱形熨斗一樣，撫平動態紋路。
                </p>
            </div>

            <div class="flex flex-col md:flex-row items-center justify-between gap-4 relative">
                <!-- Step 1 -->
                <div class="flex-1 bg-stone-50 p-6 rounded-xl border border-stone-200 text-center hover:shadow-lg transition cursor-default group">
                    <div class="text-4xl mb-4">😠</div>
                    <h4 class="font-bold text-stone-800 mb-2">表情收縮</h4>
                    <p class="text-sm text-stone-500">頻繁的大笑、皺眉導致肌肉過度收縮，形成魚尾紋與抬頭紋。</p>
                </div>

                <!-- Arrow -->
                <div class="text-2xl text-stone-300 font-bold rotate-90 md:rotate-0">➝</div>

                <!-- Step 2 (The Intervention) -->
                <div class="flex-1 bg-[#FFF9E5] p-6 rounded-xl border border-[#D4AF37] text-center shadow-md transform scale-105 z-10 group">
                    <div class="text-4xl mb-4">🛡️</div>
                    <h4 class="font-bold text-[#9A7D0A] mb-2">胜肽阻斷</h4>
                    <p class="text-sm text-stone-600">
                        <span class="font-semibold">三胜肽 & 六胜肽</span> 模擬蛇毒血清，阻斷神經傳導物質，讓肌肉「放鬆」。
                    </p>
                </div>

                <!-- Arrow -->
                <div class="text-2xl text-stone-300 font-bold rotate-90 md:rotate-0">➝</div>

                <!-- Step 3 -->
                <div class="flex-1 bg-stone-50 p-6 rounded-xl border border-stone-200 text-center hover:shadow-lg transition cursor-default group">
                    <div class="text-4xl mb-4">✨</div>
                    <h4 class="font-bold text-stone-800 mb-2">平滑緊緻</h4>
                    <p class="text-sm text-stone-500">肌肉放鬆後，動態紋路自然撫平，肌膚恢復平滑彈性。</p>
                </div>
            </div>
        </div>
    </section>

    <!-- Section 4: Clinical Evidence (Charts) -->
    <section id="evidence" class="py-20 bg-[#F5F5F4] section-fade">
        <div class="max-w-6xl mx-auto px-4 sm:px-6 lg:px-8">
            <div class="grid grid-cols-1 lg:grid-cols-3 gap-12 items-start">
                
                <!-- Text Content -->
                <div class="lg:col-span-1">
                    <span class="text-[#D4AF37] font-semibold tracking-wide uppercase">實驗室數據</span>
                    <h2 class="text-3xl font-bold text-stone-900 mt-2 mb-6">28 天實測見證</h2>
                    <p class="text-stone-600 mb-6">
                        基於 SpecPed SKE (0.25% 溶液) 的臨床測試結果。受試者為 10 位 25-55 歲女性，每日早晚使用兩次。
                    </p>
                    
                    <div class="space-y-4">
                        <button onclick="updateChart('volume')" class="chart-btn w-full text-left px-6 py-4 bg-white rounded-xl shadow-sm hover:shadow-md border-l-4 border-transparent hover:border-[#D4AF37] transition flex justify-between items-center group active-metric">
                            <div>
                                <span class="block text-sm text-stone-500">深度指標</span>
                                <span class="block text-lg font-bold text-stone-800">皺紋體積 (Volume)</span>
                            </div>
                            <span class="text-stone-300 group-hover:text-[#D4AF37]">→</span>
                        </button>

                        <button onclick="updateChart('area')" class="chart-btn w-full text-left px-6 py-4 bg-white rounded-xl shadow-sm hover:shadow-md border-l-4 border-transparent hover:border-[#D4AF37] transition flex justify-between items-center group">
                            <div>
                                <span class="block text-sm text-stone-500">範圍指標</span>
                                <span class="block text-lg font-bold text-stone-800">皺紋面積 (Area)</span>
                            </div>
                            <span class="text-stone-300 group-hover:text-[#D4AF37]">→</span>
                        </button>

                        <button onclick="updateChart('ratio')" class="chart-btn w-full text-left px-6 py-4 bg-white rounded-xl shadow-sm hover:shadow-md border-l-4 border-transparent hover:border-[#D4AF37] transition flex justify-between items-center group">
                            <div>
                                <span class="block text-sm text-stone-500">密度指標</span>
                                <span class="block text-lg font-bold text-stone-800">皺紋面積佔比 (Ratio)</span>
                            </div>
                            <span class="text-stone-300 group-hover:text-[#D4AF37]">→</span>
                        </button>
                    </div>

                    <div class="mt-8 p-4 bg-stone-200 rounded-lg text-sm text-stone-600">
                        *數據來源：SpecPed SKE(-P) 臨床測試報告。效果因人而異。
                    </div>
                </div>

                <!-- Chart Visualization -->
                <div class="lg:col-span-2 bg-white p-6 rounded-2xl shadow-lg">
                    <div class="mb-4 flex justify-between items-end border-b border-stone-100 pb-4">
                        <div>
                            <h3 class="text-xl font-bold text-stone-800" id="chart-title">皺紋改善趨勢</h3>
                            <p class="text-sm text-stone-500">數值越低代表改善效果越顯著</p>
                        </div>
                        <div class="text-right">
                            <span class="block text-3xl font-bold text-[#D4AF37]" id="max-reduction">-20.26%</span>
                            <span class="block text-xs text-stone-400">最大改善幅度 (28天)</span>
                        </div>
                    </div>
                    
                    <div class="chart-container">
                        <canvas id="efficacyChart"></canvas>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- Section 5: Usage & Call to Action -->
    <section id="usage" class="py-20 bg-stone-900 text-white section-fade">
        <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8 text-center">
            <h2 class="text-3xl font-bold mb-8">簡單三步，重現明亮眼神</h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8 max-w-4xl mx-auto mb-16">
                <div class="p-6 border border-stone-700 rounded-xl bg-stone-800 hover:bg-stone-700 transition">
                    <div class="text-3xl mb-4">🧴</div>
                    <h4 class="text-xl font-semibold mb-2">Step 1</h4>
                    <p class="text-stone-300">取一粒米大小的眼膠。</p>
                </div>
                <div class="p-6 border border-stone-700 rounded-xl bg-stone-800 hover:bg-stone-700 transition">
                    <div class="text-3xl mb-4">👆</div>
                    <h4 class="text-xl font-semibold mb-2">Step 2</h4>
                    <p class="text-stone-300">點塗於眼周肌膚（眼下、眼尾、眼皮）。</p>
                </div>
                <div class="p-6 border border-stone-700 rounded-xl bg-stone-800 hover:bg-stone-700 transition">
                    <div class="text-3xl mb-4">💆‍♀️</div>
                    <h4 class="text-xl font-semibold mb-2">Step 3</h4>
                    <p class="text-stone-300">使用無名指輕柔按摩至吸收。</p>
                </div>
            </div>

            <div class="glass-panel bg-white/10 p-10 rounded-3xl max-w-3xl mx-auto border border-white/20">
                <h3 class="text-2xl font-bold mb-4">準備好改變了嗎？</h3>
                <p class="text-stone-300 mb-8 text-lg">
                    藍娜黛兒 Lanadelle 逆齡眼膠，讓你的眼睛永遠停留在最美的時刻。
                </p>
                <button onclick="window.location.href='https://smarthealthypro.com/'" class="btn-primary px-12 py-4 rounded-full text-xl font-bold shadow-xl hover:shadow-2xl transform hover:scale-105 transition">
                    加入會員購買
                </button>
                <p class="mt-4 text-sm text-stone-400">加入購物車，開啟逆齡之旅</p>
            </div>
        </div>
    </section>

    <!-- Footer -->
    <footer class="bg-stone-950 text-stone-500 py-10 border-t border-stone-800">
        <div class="max-w-7xl mx-auto px-4 text-center">
            <!-- Copyright text removed as requested -->
            <p class="mt-2 text-sm">本網站內容僅供參考，實際效果因個人膚質而異。</p>
        </div>
    </footer>

    <!-- JavaScript Logic -->
    <script>
        // --- Data Definitions ---
        
        const ingredientsData = [
            {
                id: 1,
                name: "西蘭花外泌體",
                nameEn: "Broccoli Exosomes",
                category: "science",
                icon: "🥦",
                desc: "植物細胞的「奈米傳令兵」。",
                detail: "帶著修復命令深入肌膚底層，喚醒沉睡細胞，啟動自我修復機制。"
            },
            {
                id: 2,
                name: "三胜肽 + 六胜肽",
                nameEn: "Peptide Complex",
                category: "science",
                icon: "💉",
                desc: "不用打針的「類肉毒桿菌」。",
                detail: "模擬蛇毒血清結構，放鬆眼周肌肉，撫平大笑或皺眉產生的動態細紋。"
            },
            {
                id: 3,
                name: "玻色因 + 神經醯胺",
                nameEn: "Pro-Xylane & Ceramide",
                category: "science",
                icon: "💧",
                desc: "肌膚的「強力膠」與「水庫」。",
                detail: "玻色因撐起肌膚結構恢復緊緻；神經醯胺建立屏障，鎖住水分不流失。"
            },
            {
                id: 4,
                name: "梔子果萃取",
                nameEn: "Gardenia Extract",
                category: "nature",
                icon: "🌼",
                desc: "舒緩修復專家。",
                detail: "具有優異的舒緩能力，調節肌膚免疫，幫助活化再生。"
            },
            {
                id: 5,
                name: "黑莓 & 葡萄柚",
                nameEn: "Blackberry & Grapefruit",
                category: "nature",
                icon: "🍇",
                desc: "抗氧化大師。",
                detail: "富含抗氧化劑，對抗自由基，減緩細胞老化速度。"
            },
            {
                id: 6,
                name: "白柳皮萃取",
                nameEn: "White Willow Bark",
                category: "nature",
                icon: "🌳",
                desc: "溫柔的鎮定劑。",
                detail: "天然的水楊酸來源，具消炎抗菌效果，能改善眼周暗沉與敏感。"
            }
        ];

        const symptomData = [
            { id: 'circles', text: '黑眼圈 / 暗沉', solution: '白柳皮與梔子果萃取能促進循環，淡化暗沉。' },
            { id: 'lines', text: '魚尾紋 / 表情紋', solution: '三胜肽與六胜肽能放鬆肌肉，如同隱形熨斗般撫平紋路。' },
            { id: 'dryness', text: '乾燥 / 卡粉', solution: '神經醯胺與玻色因提供深層保濕，讓眼妝更服貼。' },
            { id: 'sagging', text: '眼皮鬆弛', solution: '西蘭花外泌體喚醒細胞再生，恢復肌膚彈性支撐力。' }
        ];

        const clinicalData = {
            labels: ['Day 0', 'Day 14', 'Day 21', 'Day 28'],
            volume: [0, -8.70, -13.85, -15.68],
            area: [0, -8.47, -16.70, -20.26],
            ratio: [0, -6.47, -16.62, -19.23]
        };

        // --- Application State ---
        let currentMetric = 'volume';
        let chartInstance = null;

        // --- Initialization ---
        document.addEventListener('DOMContentLoaded', () => {
            renderSymptoms();
            renderIngredients('all');
            initChart();
            setupScrollAnimation();
        });

        // --- Functions: Diagnostics ---
        function renderSymptoms() {
            const grid = document.getElementById('symptom-grid');
            grid.innerHTML = symptomData.map(s => `
                <button onclick="diagnose('${s.id}')" 
                    class="p-6 rounded-xl border-2 border-stone-100 hover:border-[#D4AF37] bg-white text-left transition hover:shadow-lg group">
                    <div class="flex items-center justify-between">
                        <span class="font-medium text-lg text-stone-700 group-hover:text-[#D4AF37]">${s.text}</span>
                        <span class="text-stone-300 group-hover:text-[#D4AF37] text-2xl">+</span>
                    </div>
                </button>
            `).join('');
        }

        function diagnose(id) {
            const symptom = symptomData.find(s => s.id === id);
            const resultBox = document.getElementById('diagnosis-result');
            const resultText = document.getElementById('diagnosis-text');
            
            resultText.innerHTML = `<span class="font-bold text-[#D4AF37]">針對${symptom.text}：</span> ${symptom.solution}`;
            
            resultBox.classList.remove('hidden');
            resultBox.classList.add('animate-pulse');
            setTimeout(() => resultBox.classList.remove('animate-pulse'), 500);
        }

        // --- Functions: Ingredients ---
        function renderIngredients(filter) {
            const grid = document.getElementById('ingredient-grid');
            const filtered = filter === 'all' ? ingredientsData : ingredientsData.filter(i => i.category === filter);
            
            // Update buttons
            document.querySelectorAll('.ing-filter').forEach(btn => {
                if((filter === 'all' && btn.innerText === '全部') || 
                   (filter === 'science' && btn.innerText.includes('科研')) || 
                   (filter === 'nature' && btn.innerText.includes('植萃'))) {
                    btn.classList.add('bg-[#D4AF37]', 'text-white');
                    btn.classList.remove('bg-white', 'text-stone-600');
                } else {
                    btn.classList.remove('bg-[#D4AF37]', 'text-white');
                    btn.classList.add('bg-white', 'text-stone-600');
                }
            });

            grid.innerHTML = filtered.map(item => `
                <div class="bg-white rounded-xl overflow-hidden shadow-sm hover:shadow-xl transition duration-300 border border-stone-100 group">
                    <div class="p-6">
                        <div class="w-12 h-12 bg-stone-50 rounded-full flex items-center justify-center text-2xl mb-4 group-hover:bg-[#FFF9E5] transition">
                            ${item.icon}
                        </div>
                        <h3 class="font-bold text-lg text-stone-800">${item.name}</h3>
                        <p class="text-xs text-[#D4AF37] font-medium mb-3 uppercase tracking-wider">${item.nameEn}</p>
                        <p class="text-stone-500 text-sm mb-4">${item.desc}</p>
                        <div class="pt-4 border-t border-stone-100 text-sm text-stone-600 leading-relaxed bg-stone-50/50 -mx-6 -mb-6 p-6">
                            ${item.detail}
                        </div>
                    </div>
                </div>
            `).join('');
        }

        function filterIngredients(category) {
            const grid = document.getElementById('ingredient-grid');
            grid.style.opacity = '0';
            setTimeout(() => {
                renderIngredients(category);
                grid.style.opacity = '1';
            }, 200);
        }

        // --- Functions: Charts (Chart.js) ---
        function initChart() {
            const ctx = document.getElementById('efficacyChart').getContext('2d');
            
            // Gradient fill
            const gradient = ctx.createLinearGradient(0, 0, 0, 400);
            gradient.addColorStop(0, 'rgba(212, 175, 55, 0.5)'); // Gold
            gradient.addColorStop(1, 'rgba(212, 175, 55, 0.0)');

            chartInstance = new Chart(ctx, {
                type: 'line',
                data: {
                    labels: clinicalData.labels,
                    datasets: [{
                        label: '改善百分比 (%)',
                        data: clinicalData.volume,
                        borderColor: '#D4AF37',
                        backgroundColor: gradient,
                        borderWidth: 3,
                        pointBackgroundColor: '#fff',
                        pointBorderColor: '#D4AF37',
                        pointRadius: 6,
                        pointHoverRadius: 8,
                        fill: true,
                        tension: 0.4
                    }]
                },
                options: {
                    responsive: true,
                    maintainAspectRatio: false,
                    plugins: {
                        legend: { display: false },
                        tooltip: {
                            backgroundColor: 'rgba(60, 60, 60, 0.9)',
                            padding: 12,
                            callbacks: {
                                label: function(context) {
                                    return `減少 ${Math.abs(context.raw)}%`;
                                }
                            }
                        }
                    },
                    scales: {
                        y: {
                            beginAtZero: true,
                            max: 5,
                            min: -25,
                            grid: { color: '#f3f4f6' },
                            ticks: {
                                callback: function(value) { return value + "%"; },
                                color: '#9ca3af'
                            }
                        },
                        x: {
                            grid: { display: false },
                            ticks: { color: '#4b5563', font: { weight: 'bold' } }
                        }
                    }
                }
            });
        }

        function updateChart(metric) {
            currentMetric = metric;
            
            // Visual Active State for Buttons
            document.querySelectorAll('.chart-btn').forEach(btn => btn.classList.remove('border-[#D4AF37]', 'bg-stone-50'));
            // Note: simple class toggle logic here for demo, clicking triggers re-render anyway
            
            // Update Data
            chartInstance.data.datasets[0].data = clinicalData[metric];
            chartInstance.update();

            // Update Text Labels
            const maxVal = Math.min(...clinicalData[metric]);
            document.getElementById('max-reduction').innerText = maxVal + "%";
            
            let title = "";
            if(metric === 'volume') title = "皺紋體積減少 (Depth & Size)";
            if(metric === 'area') title = "皺紋面積減少 (Width & Length)";
            if(metric === 'ratio') title = "皺紋密度減少 (Overall Ratio)";
            document.getElementById('chart-title').innerText = title;
        }

        // --- Functions: Utility ---
        function scrollToSection(id) {
            const el = document.getElementById(id);
            if(el) {
                const offset = 80; // nav height
                const bodyRect = document.body.getBoundingClientRect().top;
                const elementRect = el.getBoundingClientRect().top;
                const elementPosition = elementRect - bodyRect;
                const offsetPosition = elementPosition - offset;

                window.scrollTo({
                    top: offsetPosition,
                    behavior: "smooth"
                });
            }
        }

        function setupScrollAnimation() {
            const observer = new IntersectionObserver((entries) => {
                entries.forEach(entry => {
                    if (entry.isIntersecting) {
                        entry.target.classList.add('section-visible');
                    }
                });
            }, { threshold: 0.1 });

            document.querySelectorAll('.section-fade').forEach(section => {
                observer.observe(section);
            });
        }
    </script>
</body>
</html>
