<!DOCTYPE html>
<html lang="zh-TW">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>中越峴港風華5日 - 樹林區永慶不動產</title>
    <!-- 引入 Tailwind CSS 進行排版 -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- 引入 Lucide 圖示庫 -->
    <script src="https://unpkg.com/lucide@latest"></script>
    <style>
        /* 隱藏滾動條但保留滾動功能 */
        .hide-scrollbar::-webkit-scrollbar { display: none; }
        .hide-scrollbar { -ms-overflow-style: none; scrollbar-width: none; }
        html { scroll-behavior: smooth; }
    </style>
</head>
<body class="bg-slate-50 font-sans text-slate-800 pb-20">

    <!-- 頂部主視覺 Header -->
    <header class="relative h-[60vh] min-h-[400px] flex items-center justify-center overflow-hidden">
        <div class="absolute inset-0 z-0 bg-slate-900">
            <img 
                src="https://images.unsplash.com/photo-1583417319070-4a69db38a482?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80" 
                alt="峴港佛手金橋" 
                class="w-full h-full object-cover opacity-50"
                onerror="this.onerror=null;this.src='https://images.unsplash.com/photo-1528181304800-259b08848526?ixlib=rb-4.0.3&auto=format&fit=crop&w=1920&q=80';"
            />
        </div>
        <div class="relative z-10 text-center px-4 max-w-4xl mx-auto">
            <span class="inline-block py-1 px-3 rounded-full bg-teal-500/80 text-white text-sm font-medium mb-4 backdrop-blur-sm">
                樹林區永慶不動產 專屬行程
            </span>
            <h1 class="text-4xl md:text-5xl lg:text-6xl font-bold text-white mb-4 leading-tight tracking-wide">
                中越峴港風華5日
            </h1>
            <p class="text-xl md:text-2xl text-teal-50 mb-8 font-light">
                全程五星酒店・無購物・簽證快速通關
            </p>
            <div class="flex flex-wrap justify-center gap-3">
                <span class="bg-white/20 backdrop-blur-md border border-white/30 text-white px-4 py-2 rounded-full text-sm flex items-center gap-2">
                    <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-300"></i> 90分鐘越式洗頭按摩
                </span>
                <span class="bg-white/20 backdrop-blur-md border border-white/30 text-white px-4 py-2 rounded-full text-sm flex items-center gap-2">
                    <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-300"></i> 世界遺產會安古鎮
                </span>
                <span class="bg-white/20 backdrop-blur-md border border-white/30 text-white px-4 py-2 rounded-full text-sm flex items-center gap-2">
                    <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-300"></i> 巴拿山佛手金橋
                </span>
                <span class="bg-white/20 backdrop-blur-md border border-white/30 text-white px-4 py-2 rounded-full text-sm flex items-center gap-2">
                    <i data-lucide="check-circle-2" class="w-4 h-4 text-teal-300"></i> 迦南島竹籃船捕蟹
                </span>
            </div>
        </div>
    </header>

    <!-- 航班資訊 -->
    <section class="max-w-5xl mx-auto px-4 -mt-12 relative z-20">
        <div class="bg-white rounded-2xl shadow-xl p-6 md:p-8 flex flex-col md:flex-row gap-6 justify-between items-center border border-gray-100">
            <div class="w-full md:w-1/2 flex items-center gap-4 p-4 rounded-xl bg-slate-50">
                <div class="bg-teal-100 p-3 rounded-full text-teal-600 shrink-0">
                    <i data-lucide="plane-takeoff" class="w-6 h-6"></i>
                </div>
                <div>
                    <p class="text-sm text-gray-500 font-medium">第1天出發 | 華航 CI789</p>
                    <p class="text-lg font-bold text-slate-800">14:40 桃園 <span class="text-teal-500 mx-2">➔</span> 16:30 峴港</p>
                </div>
            </div>
            <div class="w-full md:w-1/2 flex items-center gap-4 p-4 rounded-xl bg-slate-50">
                <div class="bg-teal-100 p-3 rounded-full text-teal-600 shrink-0">
                    <i data-lucide="plane-landing" class="w-6 h-6"></i>
                </div>
                <div>
                    <p class="text-sm text-gray-500 font-medium">第5天回程 | 華航 CI1790</p>
                    <p class="text-lg font-bold text-slate-800">17:30 峴港 <span class="text-teal-500 mx-2">➔</span> 21:30 桃園</p>
                </div>
            </div>
        </div>
    </section>

    <main class="max-w-5xl mx-auto px-4 py-12">
        
        <!-- 旅程簡介 -->
        <section class="mb-16 text-center max-w-3xl mx-auto">
            <h2 class="text-3xl font-bold mb-6 text-slate-800 flex items-center justify-center gap-2">
                <i data-lucide="sparkles" class="w-6 h-6 text-amber-500"></i>
                旅程簡介
                <i data-lucide="sparkles" class="w-6 h-6 text-amber-500"></i>
            </h2>
            <p class="text-lg text-slate-600 leading-relaxed">
                探索世界文化遺產會安古鎮、漫步巴拿山佛手金橋、體驗迦南島傳統桶船。品味私房海鮮料理，享受90分鐘越式洗頭，給您最尊榮的越南風華之旅。
            </p>
        </section>

        <!-- 行程區塊 -->
        <section id="itinerary" class="mb-16">
            <h2 class="text-3xl font-bold mb-8 text-center text-slate-800">每日行程總覽</h2>
            
            <!-- 天數切換按鈕 -->
            <div class="flex overflow-x-auto hide-scrollbar gap-2 mb-8 pb-2 snap-x justify-start md:justify-center" id="day-tabs-container">
                <button onclick="setActiveDay(1)" data-day="1" class="day-tab snap-center shrink-0 px-6 py-4 rounded-xl font-bold text-lg transition-all duration-300 flex flex-col items-center gap-1 min-w-[120px] bg-teal-600 text-white shadow-lg shadow-teal-600/30 scale-105 cursor-pointer">
                    <span class="text-sm font-medium opacity-80">Day 1</span>
                </button>
                <button onclick="setActiveDay(2)" data-day="2" class="day-tab snap-center shrink-0 px-6 py-4 rounded-xl font-bold text-lg transition-all duration-300 flex flex-col items-center gap-1 min-w-[120px] bg-white text-slate-500 hover:bg-teal-50 border border-slate-200 cursor-pointer">
                    <span class="text-sm font-medium opacity-80">Day 2</span>
                </button>
                <button onclick="setActiveDay(3)" data-day="3" class="day-tab snap-center shrink-0 px-6 py-4 rounded-xl font-bold text-lg transition-all duration-300 flex flex-col items-center gap-1 min-w-[120px] bg-white text-slate-500 hover:bg-teal-50 border border-slate-200 cursor-pointer">
                    <span class="text-sm font-medium opacity-80">Day 3</span>
                </button>
                <button onclick="setActiveDay(4)" data-day="4" class="day-tab snap-center shrink-0 px-6 py-4 rounded-xl font-bold text-lg transition-all duration-300 flex flex-col items-center gap-1 min-w-[120px] bg-white text-slate-500 hover:bg-teal-50 border border-slate-200 cursor-pointer">
                    <span class="text-sm font-medium opacity-80">Day 4</span>
                </button>
                <button onclick="setActiveDay(5)" data-day="5" class="day-tab snap-center shrink-0 px-6 py-4 rounded-xl font-bold text-lg transition-all duration-300 flex flex-col items-center gap-1 min-w-[120px] bg-white text-slate-500 hover:bg-teal-50 border border-slate-200 cursor-pointer">
                    <span class="text-sm font-medium opacity-80">Day 5</span>
                </button>
            </div>

            <!-- 動態行程內容容器 -->
            <div id="day-content-container"></div>
        </section>

        <!-- 行程注意事項 -->
        <section class="mb-16">
            <div class="bg-orange-50 rounded-2xl p-6 md:p-8 border border-orange-100 shadow-sm">
                <h2 class="text-2xl font-bold mb-6 text-orange-900 flex items-center gap-2">
                    <i data-lucide="alert-circle" class="w-6 h-6 text-orange-500"></i>
                    行程注意事項
                </h2>
                <div class="space-y-4">
                    <div class="flex gap-3">
                        <span class="text-orange-500 font-bold mt-0.5">•</span>
                        <p class="text-slate-700 leading-relaxed">【越式洗頭提醒】洗頭按摩結束後，請記得給予服務人員每人 10 萬越盾（約新台幣 90 元）的小費。如不參加此活動，請於報名時通知，每人可退費 NT$500（不含附贈之奶蓋咖啡）。</p>
                    </div>
                    <div class="flex gap-3">
                        <span class="text-orange-500 font-bold mt-0.5">•</span>
                        <p class="text-slate-700 leading-relaxed">【巴拿山自費說明】巴拿山行程一票到底，但「法國百年酒窖」不含入內門票，若需品酒一杯需另加 NT$180；遊樂園的高山過山車不包含「LUGE 室外滑車」。</p>
                    </div>
                    <div class="flex gap-3">
                        <span class="text-orange-500 font-bold mt-0.5">•</span>
                        <p class="text-slate-700 leading-relaxed">【餐食異動說明】第2天晚上的「會安古宅庭院自助餐」，若當天餐廳用餐客人不足 20 位，餐廳將改為合菜形式供應。</p>
                    </div>
                </div>
            </div>
        </section>

        <!-- 精選五星級住宿 -->
        <section>
            <h2 class="text-3xl font-bold mb-8 text-center text-slate-800">精選五星級住宿</h2>
            <div class="grid md:grid-cols-2 gap-6">
                
                <!-- 飯店 1 -->
                <a href="https://www.marriott.com/en-us/hotels/dadfp-four-points-by-sheraton-danang/overview/" target="_blank" rel="noopener noreferrer" class="bg-white rounded-2xl overflow-hidden shadow-md border border-slate-100 hover:shadow-xl transition-all group block cursor-pointer">
                    <div class="h-48 overflow-hidden relative bg-slate-200">
                        <img src="https://images.unsplash.com/photo-1566073771259-6a8506099945?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="峴港福朋喜來登" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700">
                        <div class="absolute top-4 left-4 flex gap-2">
                            <span class="bg-black/60 backdrop-blur-sm text-white text-xs px-2 py-1 rounded">五星級</span>
                            <span class="bg-black/60 backdrop-blur-sm text-white text-xs px-2 py-1 rounded">海景</span>
                            <span class="bg-black/60 backdrop-blur-sm text-white text-xs px-2 py-1 rounded">無邊際泳池</span>
                        </div>
                    </div>
                    <div class="p-6 relative">
                        <h3 class="text-xl font-bold text-slate-800 mb-3 group-hover:text-teal-600 transition-colors pr-8">
                            峴港福朋喜來登 Four Points by Sheraton
                            <i data-lucide="external-link" class="w-5 h-5 absolute top-6 right-6 text-slate-300 group-hover:text-teal-500 transition-colors"></i>
                        </h3>
                        <p class="text-slate-600 text-sm leading-relaxed">【萬豪集團旗下】展現現代設計與細膩品味，窗外可眺望迷人海景或城市風光。</p>
                    </div>
                </a>

                <!-- 飯店 2 -->
                <a href="https://peninsulahotel.vn/" target="_blank" rel="noopener noreferrer" class="bg-white rounded-2xl overflow-hidden shadow-md border border-slate-100 hover:shadow-xl transition-all group block cursor-pointer">
                    <div class="h-48 overflow-hidden relative bg-slate-200">
                        <img src="https://images.unsplash.com/photo-1582719478250-c89cae4dc85b?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="峴港半島酒店" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700">
                        <div class="absolute top-4 left-4 flex gap-2">
                            <span class="bg-black/60 backdrop-blur-sm text-white text-xs px-2 py-1 rounded">五星級</span>
                            <span class="bg-black/60 backdrop-blur-sm text-white text-xs px-2 py-1 rounded">美溪沙灘</span>
                            <span class="bg-black/60 backdrop-blur-sm text-white text-xs px-2 py-1 rounded">無邊際泳池</span>
                        </div>
                    </div>
                    <div class="p-6 relative">
                        <h3 class="text-xl font-bold text-slate-800 mb-3 group-hover:text-teal-600 transition-colors pr-8">
                            峴港半島酒店 Peninsula Hotel
                            <i data-lucide="external-link" class="w-5 h-5 absolute top-6 right-6 text-slate-300 group-hover:text-teal-500 transition-colors"></i>
                        </h3>
                        <p class="text-slate-600 text-sm leading-relaxed">坐落於美麗的峴港海岸，擁有現代簡約風格設計，設有無邊際泳池，鄰近美溪沙灘與市中心。</p>
                    </div>
                </a>

                <!-- 飯店 3 -->
                <a href="https://bellerivehoian.com/" target="_blank" rel="noopener noreferrer" class="bg-white rounded-2xl overflow-hidden shadow-md border border-slate-100 hover:shadow-xl transition-all group block cursor-pointer">
                    <div class="h-48 overflow-hidden relative bg-slate-200">
                        <img src="https://images.unsplash.com/photo-1540541338287-41700207dee6?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="會安貝勒里夫水療渡假飯店" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700">
                        <div class="absolute top-4 left-4 flex gap-2">
                            <span class="bg-black/60 backdrop-blur-sm text-white text-xs px-2 py-1 rounded">五星級</span>
                            <span class="bg-black/60 backdrop-blur-sm text-white text-xs px-2 py-1 rounded">渡假村</span>
                            <span class="bg-black/60 backdrop-blur-sm text-white text-xs px-2 py-1 rounded">免費自行車</span>
                        </div>
                    </div>
                    <div class="p-6 relative">
                        <h3 class="text-xl font-bold text-slate-800 mb-3 group-hover:text-teal-600 transition-colors pr-8">
                            會安貝勒里夫水療渡假飯店 Bellerive Hoi An
                            <i data-lucide="external-link" class="w-5 h-5 absolute top-6 right-6 text-slate-300 group-hover:text-teal-500 transition-colors"></i>
                        </h3>
                        <p class="text-slate-600 text-sm leading-relaxed">2022年開幕，距離古鎮約5公里，有免費自行車租借服務，提供絕佳休閒空間與高質素住宿體驗。</p>
                    </div>
                </a>

                <!-- 飯店 4 -->
                <a href="https://grandsunrisepalace.com/" target="_blank" rel="noopener noreferrer" class="bg-white rounded-2xl overflow-hidden shadow-md border border-slate-100 hover:shadow-xl transition-all group block cursor-pointer">
                    <div class="h-48 overflow-hidden relative bg-slate-200">
                        <img src="https://images.unsplash.com/photo-1571896349842-33c89424de2d?ixlib=rb-4.0.3&auto=format&fit=crop&w=800&q=80" alt="會安日出宮大飯店" class="w-full h-full object-cover group-hover:scale-105 transition-transform duration-700">
                        <div class="absolute top-4 left-4 flex gap-2">
                            <span class="bg-black/60 backdrop-blur-sm text-white text-xs px-2 py-1 rounded">五星級</span>
                            <span class="bg-black/60 backdrop-blur-sm text-white text-xs px-2 py-1 rounded">新開幕</span>
                            <span class="bg-black/60 backdrop-blur-sm text-white text-xs px-2 py-1 rounded">近古鎮</span>
                        </div>
                    </div>
                    <div class="p-6 relative">
                        <h3 class="text-xl font-bold text-slate-800 mb-3 group-hover:text-teal-600 transition-colors pr-8">
                            會安日出宮大飯店 Grand Sunrise Palace
                            <i data-lucide="external-link" class="w-5 h-5 absolute top-6 right-6 text-slate-300 group-hover:text-teal-500 transition-colors"></i>
                        </h3>
                        <p class="text-slate-600 text-sm leading-relaxed">2023年新開幕，85間精緻客房提供周到的服務和一流的設施，絕佳的地理位置能領略會安古鎮風情。</p>
                    </div>
                </a>
            </div>
        </section>
    </main>

    <!-- 頁尾 -->
    <footer class="bg-slate-900 text-slate-400 py-8 text-center px-4">
        <p class="mb-2">中越峴港風華5日全程五星酒店 &copy; 2026 樹林區永慶不動產專屬行程</p>
        <p class="text-sm">行程內容及順序依當地旅行社及導遊安排為主</p>
    </footer>

    <!-- 行程資料與動態渲染腳本 -->
    <script>
        const itinerary = [
            {
                day: 1,
                title: "抵達峴港，前往會安",
                route: "桃園國際機場 ✈ 峴港國際機場 - 會安市",
                activities: [
                    { time: "下午", title: "抵達峴港與快速通關", desc: "專人為我們辦理落地簽證和快速通關，免去排隊煩惱。峴港曾是占婆王國首都，現為越南中部最大城市。" },
                    { time: "傍晚", title: "前往會安與海鮮大餐", desc: "前往充滿歷史風情的會安市，享用道地的豐盛海鮮大餐，為接下來的旅程補充電力，隨後前往五星酒店辦理入住與休息。" }
                ],
                meals: { breakfast: "溫暖的家", lunch: "機上精緻簡餐", dinner: "尚青ㄟ~豐盛海鮮大拼盤 (加贈啤酒/可樂)" },
                hotel: "會安貝勒里夫水療渡假飯店 或 會安日出宮大飯店"
            },
            {
                day: 2,
                title: "水上人家與古鎮風華",
                route: "迦南島水上人家 - 會安古鎮 - 祈福水燈",
                activities: [
                    { time: "上午", title: "迦南島傳統竹桶船", desc: "搭乘傳統竹籃船體驗樂釣螃蟹趣，欣賞水椰林生態。船夫還會表演精彩的竹籃船旋轉舞！" },
                    { time: "下午", title: "會安古鎮漫遊 (含5景點門票)", desc: "參觀福建會館、廣東會館、日本橋、馮興古宅、沙黃博物館。並品嚐中越著名奶蓋咖啡。" },
                    { time: "夜晚", title: "會安祈福水燈", desc: "體驗越南秋盆河放水燈祈願習俗，在張燈結綵的古鎮享受浪漫之夜。" }
                ],
                meals: { breakfast: "飯店內自助式早餐", lunch: "秘製私房菜~奶油螃蟹胡椒蝦+清蒸海上鮮", dinner: "會安古宅庭院自助餐" },
                hotel: "會安貝勒里夫水療渡假飯店 或 會安日出宮大飯店"
            },
            {
                day: 3,
                title: "越式療癒與峴港夜景",
                route: "越式洗頭按摩 - 粉紅大教堂 - APEC廣場 - 龍橋夜景",
                activities: [
                    { time: "上午", title: "越式洗頭+按摩90分鐘", desc: "偷得浮生半日閒！包含小黃瓜敷面、全套洗頭、挖耳、洗腳等服務。(不參加可退費)" },
                    { time: "下午", title: "粉紅大教堂 & APEC廣場", desc: "參觀法國殖民時期哥德式建築「耶穌聖心主教座堂」，浪漫粉紅打卡聖地。接著車遊韓江畔的APEC公園。" },
                    { time: "夜晚", title: "龍橋百萬夜景", desc: "車遊韓江，欣賞峴港第一地標「龍橋」，長長龍身橫掛韓江上，吉祥寓意滿滿。" }
                ],
                meals: { breakfast: "飯店內自助式早餐", lunch: "正宗港式風味~東林粵式烤鴨餐", dinner: "正宗韓式石板烤肉BBQ自助 (升等生啤酒+軟飲無限暢飲)" },
                hotel: "【萬豪集團】峴港福朋喜來登 或 峴港半島酒店"
            },
            {
                day: 4,
                title: "巴拿山雲端奇幻之旅",
                route: "巴拿山法國山城 - 高空纜車 - 佛手金橋 - 夢想樂園",
                activities: [
                    { time: "全天", title: "巴拿山主題景區 (一票到底)", desc: "搭乘兩項金氏世界紀錄的高空纜車，前往海拔1,414公尺的法國山城。" },
                    { time: "亮點", title: "佛手金橋、小火車與大佛", desc: "漫步於被《TIME》評為世界最佳旅遊地的「佛手金橋」，並搭乘靜心園小火車沿途欣賞風景，參拜靈應寺大佛。" },
                    { time: "遊樂", title: "夢想樂園 & 法國村", desc: "在世界三大室內娛樂公園暢玩，漫步於浪漫歐風的百年法國村與愛情花園。" }
                ],
                meals: { breakfast: "飯店內自助式早餐", lunch: "巴拿山高山自助餐廳", dinner: "峴港創意海鮮饗宴~加碼肥美螃蟹及生猛海鮮塔無限暢吃" },
                hotel: "【萬豪集團】峴港福朋喜來登 或 峴港半島酒店"
            },
            {
                day: 5,
                title: "山茶半島祈福，滿載而歸",
                route: "山茶半島/靈應寺 - 五行山(電梯) - 峴港機場 ✈ 桃園國際機場",
                activities: [
                    { time: "上午", title: "山茶半島 & 靈應寺", desc: "前往峴港自然的屏風山茶半島，遠眺美溪沙灘。參拜高68公尺的望海觀音像，祈求平安。" },
                    { time: "近午", title: "五行山 (含電梯上下)", desc: "特別安排搭乘電梯登上代表金、木、水、火、土的五行山，探索融合鐘乳石洞和寺廟的神仙寶地。" },
                    { time: "下午", title: "告別峴港", desc: "帶著滿滿的美好回憶，搭機返回溫暖的家，結束中越峴港五日風華之旅。" }
                ],
                meals: { breakfast: "飯店內自助式早餐", lunch: "秘製乳豬龍蝦餐 (加贈啤酒/可樂)", dinner: "機上精緻簡餐" },
                hotel: "溫暖的家"
            }
        ];

        function setActiveDay(day) {
            // 更新按鈕樣式
            const tabs = document.querySelectorAll('.day-tab');
            tabs.forEach(tab => {
                if (parseInt(tab.dataset.day) === day) {
                    tab.className = "day-tab snap-center shrink-0 px-6 py-4 rounded-xl font-bold text-lg transition-all duration-300 flex flex-col items-center gap-1 min-w-[120px] bg-teal-600 text-white shadow-lg shadow-teal-600/30 scale-105 cursor-pointer";
                } else {
                    tab.className = "day-tab snap-center shrink-0 px-6 py-4 rounded-xl font-bold text-lg transition-all duration-300 flex flex-col items-center gap-1 min-w-[120px] bg-white text-slate-500 hover:bg-teal-50 border border-slate-200 cursor-pointer";
                }
            });

            // 取得當天資料
            const dayData = itinerary.find(d => d.day === day);
            const container = document.getElementById('day-content-container');

            // 建立時間軸 HTML
            const activitiesHtml = dayData.activities.map(activity => {
                const searchQuery = encodeURIComponent('越南 ' + activity.title);
                const searchUrl = `https://www.google.com/search?q=${searchQuery}`;
                return `
                    <div class="relative flex items-start gap-6 md:gap-8 group">
                        <div class="sticky top-0 z-10 flex items-center justify-center bg-teal-100 w-10 h-10 rounded-full border-4 border-white shadow-sm shrink-0 mt-1 text-teal-600 group-hover:bg-teal-500 group-hover:text-white transition-colors duration-300">
                            <i data-lucide="clock" class="w-4 h-4"></i>
                        </div>
                        <a href="${searchUrl}" target="_blank" rel="noopener noreferrer" class="bg-slate-50 p-5 rounded-2xl border border-slate-100 flex-1 hover:shadow-lg hover:shadow-teal-100 hover:border-teal-200 hover:-translate-y-1 hover:bg-white transition-all duration-300 cursor-pointer block relative" title="在 Google 搜尋「${activity.title}」">
                            <span class="text-xs font-bold text-teal-600 uppercase tracking-wider mb-1 block">${activity.time}</span>
                            <div class="flex justify-between items-start gap-4">
                                <h4 class="text-xl font-bold text-slate-800 mb-2 group-hover:text-teal-700 transition-colors">${activity.title}</h4>
                                <i data-lucide="search" class="w-4 h-4 text-slate-300 group-hover:text-teal-500 transition-colors mt-1 shrink-0"></i>
                            </div>
                            <p class="text-slate-600 leading-relaxed">${activity.desc}</p>
                        </a>
                    </div>
                `;
            }).join('');

            // 注入行程區塊內容
            container.innerHTML = `
                <div class="bg-white rounded-3xl shadow-lg border border-slate-100 overflow-hidden transition-all duration-500">
                    <div class="bg-teal-50/50 p-6 md:p-8 border-b border-teal-100">
                        <div class="flex flex-col md:flex-row md:items-center justify-between gap-4">
                            <div>
                                <h3 class="text-2xl md:text-3xl font-bold text-teal-900 mb-2">${dayData.title}</h3>
                                <div class="flex items-center gap-2 text-teal-700 font-medium">
                                    <i data-lucide="map-pin" class="w-4 h-4"></i>
                                    ${dayData.route}
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="p-6 md:p-8 grid md:grid-cols-3 gap-8">
                        <div class="md:col-span-2 space-y-8 relative before:absolute before:inset-0 before:ml-5 before:-translate-x-px md:before:mx-auto md:before:translate-x-0 before:h-full before:w-0.5 before:bg-gradient-to-b before:from-transparent before:via-slate-200 before:to-transparent">
                            ${activitiesHtml}
                        </div>

                        <div class="space-y-6">
                            <div class="bg-amber-50 rounded-2xl p-6 border border-amber-100">
                                <h4 class="text-lg font-bold text-amber-900 mb-4 flex items-center gap-2">
                                    <i data-lucide="utensils" class="w-5 h-5 text-amber-600"></i>
                                    餐食安排
                                </h4>
                                <ul class="space-y-4">
                                    <li class="flex flex-col gap-1">
                                        <span class="text-xs font-bold text-amber-700/70 uppercase">早餐</span>
                                        <span class="text-slate-700 font-medium">${dayData.meals.breakfast}</span>
                                    </li>
                                    <li class="flex flex-col gap-1">
                                        <span class="text-xs font-bold text-amber-700/70 uppercase">午餐</span>
                                        <span class="text-slate-700 font-medium">${dayData.meals.lunch}</span>
                                    </li>
                                    <li class="flex flex-col gap-1">
                                        <span class="text-xs font-bold text-amber-700/70 uppercase">晚餐</span>
                                        <span class="text-slate-700 font-medium">${dayData.meals.dinner}</span>
                                    </li>
                                </ul>
                            </div>

                            <div class="bg-indigo-50 rounded-2xl p-6 border border-indigo-100">
                                <h4 class="text-lg font-bold text-indigo-900 mb-4 flex items-center gap-2">
                                    <i data-lucide="home" class="w-5 h-5 text-indigo-600"></i>
                                    住宿安排
                                </h4>
                                <p class="text-slate-700 font-medium leading-relaxed">${dayData.hotel}</p>
                            </div>
                        </div>
                    </div>
                </div>
            `;

            // 重新渲染注入的 SVG 圖示
            lucide.createIcons();
        }

        // 初始化：預設顯示第一天並載入所有靜態圖示
        document.addEventListener('DOMContentLoaded', () => {
            setActiveDay(1);
            lucide.createIcons();
        });
    </script>
</body>
</html>
