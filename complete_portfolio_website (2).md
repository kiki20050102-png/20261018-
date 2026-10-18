<!DOCTYPE html>
<html lang="zh-TW" class="scroll-smooth">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>李鈺琦 (KIKI) | 個人作品集</title>
    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <style>
        /* 套用標楷體 (BiauKai / 標楷體) 搭配通用襯線字體與系統字體 */
        body {
            font-family: "BiauKai", "DFKai-SB", "KaiTi", "STKaiti", serif;
            letter-spacing: 0.05em;
        }
    </style>
</head>
<body class="bg-slate-50 text-slate-800 antialiased selection:bg-slate-900 selection:text-white">

    <!-- 導覽列 (Navbar) -->
    <nav class="sticky top-0 z-50 bg-slate-900/95 backdrop-blur-md shadow-md border-b border-slate-800 text-white">
        <div class="max-w-6xl mx-auto px-6 py-4 flex justify-between items-center">
            <a href="#" class="font-bold text-xl tracking-wider flex items-center gap-3">
                <i class="fa-solid fa-graduation-cap text-slate-400"></i> 李鈺琦 KIKI
            </a>
            <div class="hidden md:flex space-x-8 text-base font-medium text-slate-300">
                <a href="#about" class="hover:text-white transition">關於我</a>
                <a href="#education" class="hover:text-white transition">學經歷</a>
                <a href="#credentials" class="hover:text-white transition">證照與榮譽</a>
                <a href="#project" class="hover:text-white transition">H5P教材專案</a>
            </div>
        </div>
    </nav>

    <!-- 封面與自我介紹 (Hero Section) -->
    <header id="about" class="relative overflow-hidden py-24 lg:py-36 bg-slate-900 text-white">
        <!-- 簡約背景裝飾網格 -->
        <div class="absolute inset-0 opacity-10 pointer-events-none bg-[radial-gradient(#cbd5e1_1px,transparent_1px)] [background-size:16px_16px]"></div>
        
        <div class="max-w-5xl mx-auto px-6 text-center relative z-10">
            <div class="inline-block py-1.5 px-5 rounded-full bg-slate-800 border border-slate-700 text-slate-300 text-sm mb-6 shadow-inner">
                Healthcare Education & Digital Learning Practitioner
            </div>
            <h1 class="text-4xl lg:text-6xl font-bold mb-6 tracking-wide leading-tight">
                嗨，我是 <span class="text-slate-200 underline decoration-slate-500 underline-offset-8">李鈺琦 (KIKI)</span>
            </h1>
            <p class="text-lg lg:text-xl text-slate-300 max-w-3xl mx-auto mb-10 leading-relaxed">
                「以護理為本，以數位科技與教育創新為翼，致力於打造溫暖且具啟發性的專業互動學習體驗。」
            </p>
            <div class="flex justify-center gap-5">
                <a href="#project" class="bg-white text-slate-900 font-bold px-8 py-3.5 rounded-lg shadow-lg hover:bg-slate-200 transition flex items-center gap-2">
                    <i class="fa-solid fa-laptop-code"></i> 查看精選專案
                </a>
                <a href="#credentials" class="bg-slate-800 text-slate-200 border border-slate-700 font-bold px-8 py-3.5 rounded-lg shadow-sm hover:bg-slate-700 transition">
                    核心資歷
                </a>
            </div>
        </div>
    </header>

    <!-- 教育背景與學經歷 (Education Section) -->
    <section id="education" class="py-20 max-w-5xl mx-auto px-6">
        <div class="text-center mb-16">
            <h2 class="text-3xl lg:text-4xl font-bold text-slate-900">教育背景與學經歷</h2>
            <p class="text-slate-600 mt-3 text-lg">扎實的醫護專業基底，拓展至數位學習與教育科技領域</p>
            <div class="w-16 h-1 bg-slate-900 mx-auto mt-4"></div>
        </div>
        <div class="grid md:grid-cols-2 gap-8">
            <!-- 北護大 -->
            <div class="bg-white p-8 rounded-xl shadow-md border border-slate-200 hover:shadow-lg transition">
                <div class="w-12 h-12 rounded-lg bg-slate-900 text-white flex items-center justify-center text-xl mb-6 shadow">
                    <i class="fa-solid fa-graduation-cap"></i>
                </div>
                <span class="text-xs font-bold uppercase tracking-wider text-white bg-slate-900 px-3 py-1 rounded">就讀中</span>
                <h3 class="text-2xl font-bold text-slate-900 mt-4">國立臺北護理健康大學</h3>
                <p class="text-slate-700 mt-1 font-bold text-lg">醫護教育暨數位學習系</p>
                <p class="text-slate-600 mt-4 leading-relaxed">
                    深入鑽研數位學習理論、互動網頁開發與數位教材設計，將醫療專業結合現代科技，全面提升衛生教育與培訓成效。
                </p>
            </div>
            <!-- 聖母專校 -->
            <div class="bg-white p-8 rounded-xl shadow-md border border-slate-200 hover:shadow-lg transition">
                <div class="w-12 h-12 rounded-lg bg-slate-900 text-white flex items-center justify-center text-xl mb-6 shadow">
                    <i class="fa-solid fa-hospital-user"></i>
                </div>
                <span class="text-xs font-bold uppercase tracking-wider text-slate-700 bg-slate-200 px-3 py-1 rounded">已畢業</span>
                <h3 class="text-2xl font-bold text-slate-900 mt-4">聖母醫護管理專科學校</h3>
                <p class="text-slate-700 mt-1 font-bold text-lg">護理科</p>
                <p class="text-slate-600 mt-4 leading-relaxed">
                    扎根嚴謹的臨床護理訓練，培養出高度的同理心、敏銳的臨床觀察力與無懈可擊的醫療安全思維。
                </p>
            </div>
        </div>
    </section>

    <!-- 專業證照與競賽榮譽 (Certificates & Honors) -->
    <section id="credentials" class="py-20 bg-slate-900 text-white">
        <div class="max-w-5xl mx-auto px-6">
            <div class="text-center mb-16">
                <h2 class="text-3xl lg:text-4xl font-bold text-white">專業證照與競賽榮譽</h2>
                <p class="text-slate-400 mt-3 text-lg">兼具醫療急救、行銷企劃與 AI 科技應用的多元實力</p>
                <div class="w-16 h-1 bg-white mx-auto mt-4"></div>
            </div>
            <div class="grid md:grid-cols-2 gap-8">
                <!-- Honors -->
                <div class="bg-slate-800 p-8 rounded-xl border border-slate-700 shadow-md">
                    <div class="flex items-center gap-4 mb-6">
                        <div class="w-10 h-10 rounded-lg bg-slate-700 text-white flex items-center justify-center text-lg">
                            <i class="fa-solid fa-trophy"></i>
                        </div>
                        <h3 class="text-xl font-bold text-white">競賽肯定</h3>
                    </div>
                    <ul class="space-y-4">
                        <li class="flex items-start gap-4 bg-slate-900 p-5 rounded-lg border border-slate-700">
                            <span class="text-xl mt-0.5">🏆</span>
                            <div>
                                <h4 class="font-bold text-white text-lg">TAECT 2026 教案與媒體競賽</h4>
                                <p class="text-slate-300 font-medium mt-1">入圍肯定</p>
                            </div>
                        </li>
                    </ul>
                </div>
                <!-- Certificates -->
                <div class="bg-slate-800 p-8 rounded-xl border border-slate-700 shadow-md">
                    <div class="flex items-center gap-4 mb-6">
                        <div class="w-10 h-10 rounded-lg bg-slate-700 text-white flex items-center justify-center text-lg">
                            <i class="fa-solid fa-certificate"></i>
                        </div>
                        <h3 class="text-xl font-bold text-white">專業證照</h3>
                    </div>
                    <ul class="space-y-3.5">
                        <li class="flex items-center justify-between bg-slate-900 px-5 py-3.5 rounded-lg border border-slate-700 text-base">
                            <span class="font-bold text-white">ACLS 高階心臟救命術</span>
                            <span class="text-xs bg-slate-800 text-slate-300 px-3 py-1 rounded font-bold border border-slate-700">醫療專業</span>
                        </li>
                        <li class="flex items-center justify-between bg-slate-900 px-5 py-3.5 rounded-lg border border-slate-700 text-base">
                            <span class="font-bold text-white">TIMS 行銷企劃證照</span>
                            <span class="text-xs bg-slate-800 text-slate-300 px-3 py-1 rounded font-bold border border-slate-700">傑出合格</span>
                        </li>
                        <li class="flex items-center justify-between bg-slate-900 px-5 py-3.5 rounded-lg border border-slate-700 text-base">
                            <span class="font-bold text-white">TQC 生成式 AI 應用與技術</span>
                            <span class="text-xs bg-slate-800 text-slate-300 px-3 py-1 rounded font-bold border border-slate-700">AI 科技</span>
                        </li>
                    </ul>
                </div>
            </div>
        </div>
    </section>

    <!-- H5P 專案展示 (Project Showcase) -->
    <section id="project" class="py-24 max-w-5xl mx-auto px-6">
        <div class="text-center mb-16">
            <span class="text-xs font-bold uppercase tracking-wider text-white bg-slate-900 px-4 py-1.5 rounded-full shadow">精選專案展示</span>
            <h2 class="text-3xl lg:text-4xl font-bold text-slate-900 mt-4">情緒識別教育數位教材 (SEL 學習模組)</h2>
            <p class="text-slate-600 mt-3 text-lg max-w-2xl mx-auto">運用 H5P 互動工具與同理心設計，打造兼具美學與教育意義的社交情緒學習體驗。</p>
            <div class="w-16 h-1 bg-slate-900 mx-auto mt-4"></div>
        </div>

        <div class="bg-white rounded-2xl shadow-xl border border-slate-200 overflow-hidden">
            <div class="p-8 lg:p-12">
                <div class="grid lg:grid-cols-2 gap-10 items-center">
                    <div>
                        <h3 class="text-2xl font-bold text-slate-900 mb-6 flex items-center gap-3">
                            <i class="fa-solid fa-paintbrush text-slate-700"></i> 視覺美學與設計理念
                        </h3>
                        <ul class="space-y-5 text-slate-700 text-base leading-relaxed">
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-check text-slate-900 mt-1.5 font-bold"></i>
                                <div>
                                    <strong class="text-slate-900 font-bold">色彩計畫與舒適排版：</strong>以米白色為背景營造溫暖閱讀環境，有效減少視覺疲勞；版面保持簡潔清晰，大幅提升內容易讀性與專注度。
                                </div>
                            </li>
                            <li class="flex items-start gap-3">
                                <i class="fa-solid fa-check text-slate-900 mt-1.5 font-bold"></i>
                                <div>
                                    <strong class="text-slate-900 font-bold">契合 SEL 核心主題：</strong>字體選擇圓潤柔和風格降低壓迫感，搭配多元色彩與情緒插圖，協助學習者精準辨識不同情緒。
                                </div>
                            </li>
                        </ul>
                    </div>
                    <div class="bg-slate-900 p-8 rounded-xl text-white shadow-md">
                        <h4 class="font-bold text-white text-lg mb-4 flex items-center gap-2">
                            <i class="fa-solid fa-puzzle-piece text-slate-400"></i> 核心 H5P 互動模組應用
                        </h4>
                        <div class="space-y-3.5 text-sm text-slate-200">
                            <div class="bg-slate-800 p-3.5 rounded-lg border border-slate-700 flex items-center justify-between">
                                <span class="font-bold">Drag the Words / Drag and Drop</span>
                                <span class="text-xs text-slate-400">文字與表情圖片配對</span>
                            </div>
                            <div class="bg-slate-800 p-3.5 rounded-lg border border-slate-700 flex items-center justify-between">
                                <span class="font-bold">Image Hotspots</span>
                                <span class="text-xs text-slate-400">情緒細節與心理支持解析</span>
                            </div>
                            <div class="bg-slate-800 p-3.5 rounded-lg border border-slate-700 flex items-center justify-between">
                                <span class="font-bold">Documentation Tool & Audio</span>
                                <span class="text-xs text-slate-400">反思紀錄與語音輔助</span>
                            </div>
                        </div>
                    </div>
                </div>

                <div class="mt-12 pt-8 border-t border-slate-200 flex justify-end">
                    <a href="https://ahedl01.jonstudy.net/mod/h5pactivity/view.php?id=373" target="_blank" class="bg-slate-900 text-white font-bold px-8 py-3.5 rounded-lg shadow-md hover:bg-slate-800 transition flex items-center gap-3 text-base">
                        <i class="fa-solid fa-external-link-alt"></i> 前往體驗 H5P 教材成品
                    </a>
                </div>
            </div>
        </div>
    </section>

    <!-- 頁尾 (Footer) -->
    <footer class="bg-slate-900 text-slate-400 border-t border-slate-800 py-10 text-center text-sm">
        <div class="max-w-5xl mx-auto px-6">
            <p>&copy; 2026 李鈺琦 (KIKI) · 跨域數位學習與醫護教育作品集. All Rights Reserved.</p>
        </div>
    </footer>

</body>
</html>