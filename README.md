<!DOCTYPE html>
<html lang="zh-CN">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>盛乐博物馆 - 2025年国庆节祝福留言板</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link href="https://cdn.jsdelivr.net/npm/font-awesome@4.7.0/css/font-awesome.min.css" rel="stylesheet">
    
    <!-- 配置Tailwind自定义颜色和字体 -->
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    colors: {
                        primary: '#C41E3A', // 中国红
                        secondary: '#D4AF37', // 金色
                        dark: '#1A1A2E',
                        light: '#F5F5F7'
                    },
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                        serif: ['Noto Serif SC', 'serif']
                    }
                }
            }
        }
    </script>
    
    <style type="text/tailwindcss">
        @layer utilities {
            .text-shadow {
                text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
            }
            .text-shadow-sm {
                text-shadow: 1px 1px 2px rgba(0, 0, 0, 0.3);
            }
            .animate-float {
                animation: float 6s ease-in-out infinite;
            }
            .animate-pulse-slow {
                animation: pulse 4s cubic-bezier(0.4, 0, 0.6, 1) infinite;
            }
        }
        
        @keyframes float {
            0% { transform: translateY(0px); }
            50% { transform: translateY(-15px); }
            100% { transform: translateY(0px); }
        }
    </style>
</head>
<body class="bg-light font-sans text-dark">
    <!-- 顶部导航栏 -->
    <header class="sticky top-0 z-50 bg-primary/95 text-white shadow-lg backdrop-blur-sm transition-all duration-300">
        <div class="container mx-auto px-4 py-3 flex justify-between items-center">
            <div class="flex items-center space-x-2">
                <i class="fa fa-university text-2xl text-secondary"></i>
                <h1 class="text-xl md:text-2xl font-bold">盛乐博物馆</h1>
            </div>
            
            <nav class="hidden md:flex space-x-6">
                <a href="#about" class="hover:text-secondary transition-colors duration-300">关于博物馆</a>
                <a href="#message-board" class="hover:text-secondary transition-colors duration-300">祝福留言板</a>
                <a href="#leave-message" class="hover:text-secondary transition-colors duration-300">留下祝福</a>
                <a href="#visit-info" class="hover:text-secondary transition-colors duration-300">参观信息</a>
            </nav>
            
            <button class="md:hidden text-white focus:outline-none" id="mobile-menu-button">
                <i class="fa fa-bars text-xl"></i>
            </button>
        </div>
        
        <!-- 移动端菜单 -->
        <div class="md:hidden hidden bg-primary/95 shadow-lg absolute w-full" id="mobile-menu">
            <div class="container mx-auto px-4 py-3 flex flex-col space-y-3">
                <a href="#about" class="hover:text-secondary transition-colors duration-300 py-2">关于博物馆</a>
                <a href="#message-board" class="hover:text-secondary transition-colors duration-300 py-2">祝福留言板</a>
                <a href="#leave-message" class="hover:text-secondary transition-colors duration-300 py-2">留下祝福</a>
                <a href="#visit-info" class="hover:text-secondary transition-colors duration-300 py-2">参观信息</a>
            </div>
        </div>
    </header>

    <!-- 英雄区域 -->
    <section class="relative h-[80vh] flex items-center justify-center overflow-hidden">
        <!-- 背景图片 -->
        <div class="absolute inset-0 z-0">
            <img src="https://picsum.photos/id/1031/1920/1080" alt="盛乐博物馆外观" class="w-full h-full object-cover">
            <div class="absolute inset-0 bg-dark/50"></div>
        </div>
        
        <!-- 国庆装饰元素 -->
        <div class="absolute top-10 left-10 text-secondary text-6xl opacity-80 animate-float hidden md:block">
            <i class="fa fa-star"></i>
        </div>
        <div class="absolute bottom-20 right-16 text-secondary text-5xl opacity-80 animate-float" style="animation-delay: 1s;">
            <i class="fa fa-flag"></i>
        </div>
        <div class="absolute top-1/3 right-20 text-secondary text-4xl opacity-80 animate-float" style="animation-delay: 2s;">
            <i class="fa fa-star"></i>
        </div>
        
        <!-- 主要内容 -->
        <div class="container mx-auto px-4 z-10 text-center">
            <div class="inline-block mb-4 bg-primary/80 text-white px-6 py-2 rounded-full transform transition-transform hover:scale-105">
                <p class="text-lg md:text-xl font-medium">2025年10月1日</p>
            </div>
            <h1 class="text-4xl md:text-6xl lg:text-7xl font-bold text-white mb-6 text-shadow animate-pulse-slow">
                庆祝中华人民共和国成立76周年
            </h1>
            <p class="text-xl md:text-2xl text-white max-w-3xl mx-auto mb-8 text-shadow-sm">
                盛乐博物馆国庆祝福留言板 — 记录您对祖国的美好祝愿
            </p>
            <a href="#leave-message" class="inline-block bg-secondary hover:bg-secondary/90 text-dark font-bold px-8 py-3 rounded-full text-lg transition-all duration-300 transform hover:scale-105 hover:shadow-lg">
                留下您的祝福
            </a>
        </div>
        
        <!-- 向下滚动指示 -->
        <div class="absolute bottom-8 left-1/2 transform -translate-x-1/2 text-white animate-bounce">
            <i class="fa fa-angle-down text-3xl"></i>
        </div>
    </section>

    <!-- 博物馆 -->
    <section id="about" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold mb-4 text-dark">关于盛乐博物馆</h2>
                <div class="w-24 h-1 bg-primary mx-auto"></div>
            </div>
            
            <div class="flex flex flex-col md:flex-row items-center gap-10">
                <div class="md:w-1/2">
                    <img src="https://bkimg.cdn.bcebos.com/smart/6d81800a19d8bc3eb13529b2f8dcb11ea8d3fd1fef36-bkimg-process,v_1,rw_1,rh_1,pad_1,color_ffffff?x-bce-process=image/format,f_auto" alt="盛乐博物馆展品" class="rounded-lg shadow-xl w-full h-auto transform transition-transform hover:scale-[1.02] duration-500">
                </div>
                
                <div class="md:w-1/2">
                    <h3 class="text-2xl font-bold mb-4 text-primary">探寻历史足迹，传承文化根脉</h3>
                    <p class="text-lg mb-4 leading-relaxed">
                        盛乐博物馆成立于2007年6月16日，该馆位于全国重点文物保护单位——和林格尔土城子遗址东侧，占地面积40000平方米,建筑面积5558平方米。
                    </p>
                    <p class="text-lg mb-4 leading-relaxed">
                        盛乐古城从春秋战国起，历朝历代都在此设都建郡，在古城东侧发现海生不浪文化类型的彩陶片，石斧、石杵等足以证明早在6000年前的新石器时代就有人类在此繁衍生息，人类的出现就开启了各民族间“你中有我，我中有你，谁也离不开谁”的中华民族多元一体格局。
                    </p>
                    <p class="text-lg mb-6 leading-relaxed">
                       我馆真实记录了千百年来我国各族儿女团结和睦、共同奋斗的壮丽篇章,着重宣传和林格尔历史文化和鲜卑民族历史文化，是广大干部、群众、学校师生培养爱国情怀、宣传民族政策、弘扬民族团结进步精神的重要阵地，更是宣扬中华民族交往交流交融的平台，促进各民族在理想、信念、情感、文化上的团结统一，守望相助、手足情深，铸牢中华民族共同体意识。
                    </p>
                    <div class="flex items-center space-x-4">
                        <div class="flex items-center">
                            <i class="fa fa-map-marker text-primary mr-2"></i>
                            <span>内蒙古呼和浩特市和林格尔县</span>
                        </div>
                        <div class="flex items-center">
                            <i class="fa fa-clock-o text-primary mr-2"></i>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 留言板展示区 -->
    <section id="message-board" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold mb-4 text-dark">国庆祝福留言板</h2>
                <p class="text-lg text-gray-600 max-w-3xl mx-auto">来自全国各地游客的真诚祝福，共同祝愿祖国繁荣昌盛</p>
                <div class="w-24 h-1 bg-primary mx-auto mt-4"></div>
            </div>
            
            <!-- 留言过滤和搜索 -->
            <div class="mb-10 flex flex-col md:flex-row justify-between items-center gap-4">
                <div class="flex flex-wrap gap-2">
                    <button class="filter-btn bg-primary text-white px-4 py-2 rounded-full text-sm font-medium" data-filter="all">全部留言</button>
                    <button class="filter-btn bg-gray-200 hover:bg-gray-300 px-4 py-2 rounded-full text-sm font-medium transition-colors" data-filter="visitor">游客留言</button>
                    <button class="filter-btn bg-gray-200 hover:bg-gray-300 px-4 py-2 rounded-full text-sm font-medium transition-colors" data-filter="student">学生留言</button>
                    <button class="filter-btn bg-gray-200 hover:bg-gray-300 px-4 py-2 rounded-full text-sm font-medium transition-colors" data-filter="foreign">外国友人</button>
                </div>
                
                <div class="relative w-full md:w-64">
                    <input type="text" id="message-search" placeholder="搜索留言内容..." class="w-full pl-10 pr-4 py-2 border border-gray-300 rounded-full focus:outline-none focus:ring-2 focus:ring-primary/50">
                    <i class="fa fa-search absolute left-4 top-1/2 transform -translate-y-1/2 text-gray-400"></i>
                </div>
            </div>
            
            <!-- 留言列表 -->
            <div id="messages-container" class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <!-- 留言1 -->
                <div class="message-card bg-light rounded-xl p-6 shadow-md hover:shadow-lg transition-shadow duration-300" data-category="visitor">
                    <div class="flex items-center mb-4">
                        <img src="https://picsum.photos/id/1012/100/100" alt="张先生头像" class="w-12 h-12 rounded-full object-cover">
                        <div class="ml-4">
                            <h4 class="font-bold">张先生</h4>
                            <p class="text-sm text-gray-500">来自北京 · 2025-09-28</p>
                        </div>
                    </div>
                    <p class="text-gray-700 mb-4">
                        参观盛乐博物馆，深深感受到中华文明的博大精深。在国庆76周年之际，祝愿祖国更加繁荣富强，人民幸福安康！
                    </p>
                    <div class="flex items-center justify-between">
                        <span class="inline-block bg-primary/10 text-primary px-3 py-1 rounded-full text-xs">游客</span>
                        <button class="like-btn flex items-center text-gray-500 hover:text-primary transition-colors">
                            <i class="fa fa-heart-o mr-1"></i> <span>24</span>
                        </button>
                    </div>
                </div>
                
                <!-- 留言2 -->
                <div class="message-card bg-light rounded-xl p-6 shadow-md hover:shadow-lg transition-shadow duration-300" data-category="student">
                    <div class="flex items-center mb-4">
                        <img src="https://picsum.photos/id/1027/100/100" alt="李同学头像" class="w-12 h-12 rounded-full object-cover">
                        <div class="ml-4">
                            <h4 class="font-bold">李同学</h4>
                            <p class="text-sm text-gray-500">来自上海 · 2025-09-29</p>
                        </div>
                    </div>
                    <p class="text-gray-700 mb-4">
                        作为一名历史系学生，盛乐博物馆的展览让我受益匪浅。国庆佳节，祝愿祖国的文化遗产得到更好的保护和传承，青春中国，未来可期！
                    </p>
                    <div class="flex items-center justify-between">
                        <span class="inline-block bg-secondary/20 text-secondary px-3 py-1 rounded-full text-xs">学生</span>
                        <button class="like-btn flex items-center text-gray-500 hover:text-primary transition-colors">
                            <i class="fa fa-heart-o mr-1"></i> <span>36</span>
                        </button>
                    </div>
                </div>
                
                <!-- 留言3 -->
                <div class="message-card bg-light rounded-xl p-6 shadow-md hover:shadow-lg transition-shadow duration-300" data-category="foreign">
                    <div class="flex items-center mb-4">
                        <img src="https://picsum.photos/id/1062/100/100" alt="John头像" class="w-12 h-12 rounded-full object-cover">
                        <div class="ml-4">
                            <h4 class="font-bold">John Smith</h4>
                            <p class="text-sm text-gray-500">来自美国 · 2025-09-27</p>
                        </div>
                    </div>
                    <p class="text-gray-700 mb-4">
                        This is my first time visiting China, and Shengle Museum has given me a wonderful understanding of Chinese history. Happy National Day! China is amazing!
                    </p>
                    <div class="flex items-center justify-between">
                        <span class="inline-block bg-green-100 text-green-700 px-3 py-1 rounded-full text-xs">外国友人</span>
                        <button class="like-btn flex items-center text-gray-500 hover:text-primary transition-colors">
                            <i class="fa fa-heart-o mr-1"></i> <span>18</span>
                        </button>
                    </div>
                </div>
                
                <!-- 留言4 -->
                <div class="message-card bg-light rounded-xl p-6 shadow-md hover:shadow-lg transition-shadow duration-300" data-category="visitor">
                    <div class="flex items-center mb-4">
                        <img src="https://picsum.photos/id/1005/100/100" alt="王女士头像" class="w-12 h-12 rounded-full object-cover">
                        <div class="ml-4">
                            <h4 class="font-bold">王女士</h4>
                            <p class="text-sm text-gray-500">来自广州 · 2025-09-30</p>
                        </div>
                    </div>
                    <p class="text-gray-700 mb-4">
                        带着孩子一起来参观，他对草原文化产生了浓厚的兴趣。国庆之际，希望我们的下一代能更好地了解和热爱自己的国家和文化，祝福祖国！
                    </p>
                    <div class="flex items-center justify-between">
                        <span class="inline-block bg-primary/10 text-primary px-3 py-1 rounded-full text-xs">游客</span>
                        <button class="like-btn flex items-center text-gray-500 hover:text-primary transition-colors">
                            <i class="fa fa-heart-o mr-1"></i> <span>42</span>
                        </button>
                    </div>
                </div>
                
                <!-- 留言5 -->
                <div class="message-card bg-light rounded-xl p-6 shadow-md hover:shadow-lg transition-shadow duration-300" data-category="student">
                    <div class="flex items-center mb-4">
                        <img src="https://picsum.photos/id/1074/100/100" alt="赵同学头像" class="w-12 h-12 rounded-full object-cover">
                        <div class="ml-4">
                            <h4 class="font-bold">赵同学</h4>
                            <p class="text-sm text-gray-500">来自呼和浩特 · 2025-09-26</p>
                        </div>
                    </div>
                    <p class="text-gray-700 mb-4">
                        作为本地大学生，第一次如此深入了解家乡的历史。76载风雨兼程，祖国取得了辉煌成就。愿祖国永远年轻，永远充满活力！
                    </p>
                    <div class="flex items-center justify-between">
                        <span class="inline-block bg-secondary/20 text-secondary px-3 py-1 rounded-full text-xs">学生</span>
                        <button class="like-btn flex items-center text-gray-500 hover:text-primary transition-colors">
                            <i class="fa fa-heart-o mr-1"></i> <span>29</span>
                        </button>
                    </div>
                </div>
                
                <!-- 留言6 -->
                <div class="message-card bg-light rounded-xl p-6 shadow-md hover:shadow-lg transition-shadow duration-300" data-category="visitor">
                    <div class="flex items-center mb-4">
                        <img src="https://picsum.photos/id/1025/100/100" alt="刘先生头像" class="w-12 h-12 rounded-full object-cover">
                        <div class="ml-4">
                            <h4 class="font-bold">刘先生</h4>
                            <p class="text-sm text-gray-500">来自成都 · 2025-09-29</p>
                        </div>
                    </div>
                    <p class="text-gray-700 mb-4">
                        国庆假期特意来参观盛乐博物馆，感受草原文明的魅力。各民族文化交融共生，共同构成了中华文明的灿烂画卷。祝福祖国生日快乐！
                    </p>
                    <div class="flex items-center justify-between">
                        <span class="inline-block bg-primary/10 text-primary px-3 py-1 rounded-full text-xs">游客</span>
                        <button class="like-btn flex items-center text-gray-500 hover:text-primary transition-colors">
                            <i class="fa fa-heart-o mr-1"></i> <span>33</span>
                        </button>
                    </div>
                </div>
            </div>
            
            <!-- 加载更多按钮 -->
            <div class="text-center mt-10">
                <button id="load-more" class="bg-white border border-primary text-primary hover:bg-primary hover:text-white font-medium px-8 py-3 rounded-full transition-colors duration-300">
                    加载更多留言
                </button>
            </div>
        </div>
    </section>

    <!-- 留言表单区 -->
    <section id="leave-message" class="py-16 bg-gradient-to-br from-primary/5 to-secondary/5">
        <div class="container mx-auto px-4">
            <div class="max-w-3xl mx-auto bg-white rounded-2xl shadow-xl overflow-hidden">
                <div class="md:flex">
                    <!-- 左侧图片 -->
                    <div class="md:w-2/5 bg-primary p-8 flex items-center justify-center hidden md:flex">
                        <div class="text-center">
                            <div class="text-secondary text-6xl mb-4 animate-float">
                                <i class="fa fa-paper-plane"></i>
                            </div>
                            <h3 class="text-2xl font-bold text-white mb-4">留下您的祝福</h3>
                            <p class="text-white/80">
                                在这个特殊的日子里，写下您对祖国的祝福和期盼，让我们共同见证祖国的繁荣昌盛。
                            </p>
                        </div>
                    </div>
                    
                    <!-- 右侧表单 -->
                    <div class="md:w-3/5 p-8">
                        <h3 class="text-2xl font-bold mb-6 text-dark md:hidden">留下您的祝福</h3>
                        <form id="message-form" class="space-y-6">
                            <div>
                                <label for="name" class="block text-gray-700 font-medium mb-2">您的姓名</label>
                                <input type="text" id="name" name="name" required
                                    class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary/50 transition-shadow">
                            </div>
                            
                            <div>
                                <label for="location" class="block text-gray-700 font-medium mb-2">来自哪里</label>
                                <input type="text" id="location" name="location" required
                                    class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary/50 transition-shadow">
                            </div>
                            
                            <div>
                                <label for="category" class="block text-gray-700 font-medium mb-2">您的身份</label>
                                <select id="category" name="category" required
                                    class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary/50 transition-shadow">
                                    <option value="visitor">普通游客</option>
                                    <option value="student">学生</option>
                                    <option value="foreign">外国友人</option>
                                    <option value="other">其他</option>
                                </select>
                            </div>
                            
                            <div>
                                <label for="message" class="block text-gray-700 font-medium mb-2">您的祝福</label>
                                <textarea id="message" name="message" rows="4" required
                                    class="w-full px-4 py-3 border border-gray-300 rounded-lg focus:outline-none focus:ring-2 focus:ring-primary/50 transition-shadow"
                                    placeholder="请写下您对祖国的祝福..."></textarea>
                                <p class="text-xs text-gray-500 mt-1">字数不超过300字</p>
                            </div>
                            
                            <div>
                                <button type="submit" 
                                    class="w-full bg-primary hover:bg-primary/90 text-white font-bold py-3 px-6 rounded-lg transition-colors duration-300 transform hover:scale-[1.02] active:scale-[0.98]">
                                    提交祝福
                                </button>
                            </div>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 参观信息 -->
    <section id="visit-info" class="py-16 bg-white">
        <div class="container mx-auto px-4">
            <div class="text-center mb-12">
                <h2 class="text-3xl md:text-4xl font-bold mb-4 text-dark">参观信息</h2>
                <p class="text-lg text-gray-600 max-w-3xl mx-auto">国庆期间盛乐博物馆开放时间及参观指南</p>
                <div class="w-24 h-1 bg-primary mx-auto mt-4"></div>
            </div>
            
            <div class="grid grid-cols-1 md:grid-cols-2 gap-10">
                <!-- 开放时间 -->
                <div class="bg-light rounded-xl p-8 shadow-md">
                    <div class="flex items-center mb-6">
                        <div class="w-12 h-12 bg-primary/10 rounded-full flex items-center justify-center text-primary mr-4">
                            <i class="fa fa-clock-o text-xl"></i>
                        </div>
                        <h3 class="text-2xl font-bold">开放时间</h3>
                    </div>
                    
                    <ul class="space-y-4">
                        <li class="flex justify-between pb-3 border-b border-gray-200">
                            <span class="font-medium">10月1日 - 10月7日</span>
                            <span>09:00 - 17:00（16:30停止入场）</span>
                        </li>
                        <li class="flex justify-between pb-3 border-b border-gray-200">
                            <span class="font-medium">10月8日起</span>
                            <span>09:00 - 17:00（16:30停止入场）</span>
                        </li>
                        <li class="flex justify-between">
                            <span class="font-medium">每周一</span>
                            <span>闭馆（法定节假日除外）</span>
                        </li>
                    </ul>
                    
                    <div class="mt-6 p-4 bg-primary/10 rounded-lg">
                        <p class="text-primary font-medium">
                            <i class="fa fa-info-circle mr-2"></i> 国庆期间人流量较大，建议提前通过官方公众号预约参观
                        </p>
                    </div>
                </div>
                
                <!-- 门票信息 -->
                <div class="bg-light rounded-xl p-8 shadow-md">
                    <div class="flex items-center mb-6">
                        <div class="w-12 h-12 bg-primary/10 rounded-full flex items-center justify-center text-primary mr-4">
                            <i class="fa fa-ticket text-xl"></i>
                        </div>
                        <h3 class="text-2xl font-bold">门票信息</h3>
                    </div>
                    
                    <ul class="space-y-4">
                        <li class="flex justify-between pb-3 border-b border-gray-200">
                            <span class="font-medium">成人票</span>
                            <span>免费</span>
                        </li>
                        <li class="flex justify-between pb-3 border-b border-gray-200">
                            <span class="font-medium">学生票（凭学生证）</span>
                            <span>免费</span>
                        </li>
                        <li class="flex justify-between pb-3 border-b border-gray-200">
                            <span class="font-medium">65岁以上老人（凭身份证）</span>
                            <span>免费</span>
                        </li>
                        <li class="flex justify-between">
                            <span class="font-medium">1.2米以下儿童</span>
                            <span>免费</span>
                        </li>
                    </ul>
                    
                    <div class="mt-6 p-4 bg-secondary/10 rounded-lg">
                        <p class="text-secondary font-medium">
                            <i class="fa fa-gift mr-2"></i> 
                        </p>
                    </div>
                </div>
                
                <!-- 交通指南 -->
                <div class="bg-light rounded-xl p-8 shadow-md">
                    <div class="flex items-center mb-6">
                        <div class="w-12 h-12 bg-primary/10 rounded-full flex items-center justify-center text-primary mr-4">
                            <i class="fa fa-map-marker text-xl"></i>
                        </div>
                        <h3 class="text-2xl font-bold">交通指南</h3>
                    </div>
                    
                    <div class="space-y-4">
                        <div>
                            <h4 class="font-medium mb-1">地址</h4>
                            <p>内蒙古自治区呼和浩特市和林格尔县盛乐经济园区</p>
                        </div>
                        
                        <div>
                            <h4 class="font-medium mb-1">公共交通</h4>
                            <p>乘坐呼和浩特市公交K8路至盛乐博物馆站下车</p>
                        </div>
                        
                        <div>
                            <h4 class="font-medium mb-1">自驾</h4>
                            <p>从呼和浩特市区沿G209国道向南行驶约40公里即达，博物馆设有免费停车场</p>
                        </div>
                    </div>
                </div>
                
                <!-- 联系我们 -->
                <div class="bg-light rounded-xl p-8 shadow-md">
                    <div class="flex items-center mb-6">
                        <div class="w-12 h-12 bg-primary/10 rounded-full flex items-center justify-center text-primary mr-4">
                            <i class="fa fa-phone text-xl"></i>
                        </div>
                        <h3 class="text-2xl font-bold">联系我们</h3>
                    </div>
                    
                    <div class="space-y-4">
                        <div class="flex items-center">
                            <i class="fa fa-phone-square text-primary mr-3 w-5 text-center"></i>
                            <span>咨询电话：0471-73800002</span>
                        </div>
                        
                        <div class="flex items-center">
                            <i class="fa fa-envelope text-primary mr-3 w-5 text-center"></i>
                            <span>邮箱：395689042@qq.com</span>
                        </div>
                        
                        <div class="flex items-center">
                            <i class="fa fa-weixin text-primary mr-3 w-5 text-center"></i>
                            <span>微信公众号：盛乐博物馆</span>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- 页脚 -->
    <footer class="bg-dark text-white py-12">
        <div class="container mx-auto px-4">
            <div class="grid grid-cols-1 md:grid-cols-4 gap-8">
                <!-- 博物馆简介 -->
                <div>
                    <div class="flex items-center space-x-2 mb-4">
                        <i class="fa fa-university text-2xl text-secondary"></i>
                        <h3 class="text-xl font-bold">盛乐博物馆</h3>
                    </div>
                    <p class="text-gray-400 mb-4">
                        探寻历史足迹，传承文化根脉，盛乐博物馆致力于保护、研究和展示中华民族的优秀文化遗产。
                    </p>
                    <div class="flex space-x-4">
                        <a href="#" class="text-gray-400 hover:text-secondary transition-colors">
                            <i class="fa fa-weixin text-xl"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-secondary transition-colors">
                            <i class="fa fa-weibo text-xl"></i>
                        </a>
                        <a href="#" class="text-gray-400 hover:text-secondary transition-colors">
                            <i class="fa fa-youtube-play text-xl"></i>
                        </a>
                    </div>
                </div>
                
                <!-- 快速链接 -->
                <div>
                    <h3 class="text-lg font-bold mb-4">快速链接</h3>
                    <ul class="space-y-2">
                        <li><a href="#about" class="text-gray-400 hover:text-white transition-colors">关于博物馆</a></li>
                        <li><a href="#message-board" class="text-gray-400 hover:text-white transition-colors">祝福留言板</a></li>
                        <li><a href="#leave-message" class="text-gray-400 hover:text-white transition-colors">留下祝福</a></li>
                        <li><a href="#visit-info" class="text-gray-400 hover:text-white transition-colors">参观信息</a></li>
                        <li><a href="#" class="text-gray-400 hover:text-white transition-colors">展览活动</a></li>
                    </ul>
                </div>
                
                <!-- 开放时间 -->
                <div>
                    <h3 class="text-lg font-bold mb-4">开放时间</h3>
                    <ul class="space-y-2 text-gray-400">
                        <li> 09:00 - 17:00</li>
                        <li>每周一闭馆（法定节假日除外）</li>
                        <li>最后入场时间: 闭馆前30分钟</li>
                    </ul>
                </div>
                
                <!-- 订阅 -->
                <div>
                    <h3 class="text-lg font-bold mb-4">订阅活动信息</h3>
                    <p class="text-gray-400 mb-4">订阅我们的 newsletter，获取最新展览和活动信息</p>
                    <form class="flex">
                        <input type="email" placeholder="您的邮箱地址" 
                            class="px-4 py-2 rounded-l-lg w-full focus:outline-none text-dark">
                        <button type="submit" class="bg-primary hover:bg-primary/90 text-white px-4 py-2 rounded-r-lg transition-colors">
                            <i class="fa fa-paper-plane"></i>
                        </button>
                    </form>
                </div>
            </div>
            
            <div class="border-t border-gray-800 mt-10 pt-6 flex flex-col md:flex-row justify-between items-center">
                <p class="text-gray-500 text-sm mb-4 md:mb-0">
                    &copy; 2025 盛乐博物馆 版权所有 | 鄂ICP备XXXXXXXX号
                </p>
                <div class="flex space-x-6">
                    <a href="#" class="text-gray-500 hover:text-gray-300 text-sm">隐私政策</a>
                    <a href="#" class="text-gray-500 hover:text-gray-300 text-sm">使用条款</a>
                    <a href="#" class="text-gray-500 hover:text-gray-300 text-sm">网站地图</a>
                </div>
            </div>
        </div>
    </footer>

    <!-- 留言成功弹窗 -->
    <div id="success-modal" class="fixed inset-0 bg-black/50 flex items-center justify-center z-50 hidden">
        <div class="bg-white rounded-xl p-8 max-w-md w-full mx-4 transform transition-all duration-300 scale-95 opacity-0" id="modal-content">
            <div class="text-center">
                <div class="w-16 h-16 bg-green-100 rounded-full flex items-center justify-center text-green-500 mx-auto mb-4">
                    <i class="fa fa-check text-2xl"></i>
                </div>
                <h3 class="text-2xl font-bold mb-2">提交成功！</h3>
                <p class="text-gray-600 mb-6">
                    感谢您的祝福，您的留言已成功提交到国庆祝福留言板！
                </p>
                <button id="close-modal" class="bg-primary hover:bg-primary/90 text-white font-bold py-2 px-6 rounded-lg transition-colors">
                    确定
                </button>
            </div>
        </div>
    </div>

    <!-- JavaScript -->
    <script>
        // 移动端菜单切换
        const mobileMenuButton = document.getElementById('mobile-menu-button');
        const mobileMenu = document.getElementById('mobile-menu');
        
        mobileMenuButton.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
        
        // 平滑滚动
        document.querySelectorAll('a[href^="#"]').forEach(anchor => {
            anchor.addEventListener('click', function (e) {
                e.preventDefault();
                
                // 关闭移动菜单（如果打开）
                if (!mobileMenu.classList.contains('hidden')) {
                    mobileMenu.classList.add('hidden');
                }
                
                const targetId = this.getAttribute('href');
                const targetElement = document.querySelector(targetId);
                
                if (targetElement) {
                    window.scrollTo({
                        top: targetElement.offsetTop - 80,
                        behavior: 'smooth'
                    });
                }
            });
        });
        
        // 导航栏滚动效果
        window.addEventListener('scroll', () => {
            const header = document.querySelector('header');
            if (window.scrollY > 50) {
                header.classList.add('py-2');
                header.classList.remove('py-3');
            } else {
                header.classList.add('py-3');
                header.classList.remove('py-2');
            }
        });
        
        // 留言过滤功能
        const filterButtons = document.querySelectorAll('.filter-btn');
        const messageCards = document.querySelectorAll('.message-card');
        
        filterButtons.forEach(button => {
            button.addEventListener('click', () => {
                // 更新按钮样式
                filterButtons.forEach(btn => {
                    btn.classList.remove('bg-primary', 'text-white');
                    btn.classList.add('bg-gray-200', 'hover:bg-gray-300');
                });
                button.classList.remove('bg-gray-200', 'hover:bg-gray-300');
                button.classList.add('bg-primary', 'text-white');
                
                const filter = button.getAttribute('data-filter');
                
                // 过滤留言
                messageCards.forEach(card => {
                    if (filter === 'all' || card.getAttribute('data-category') === filter) {
                        card.style.display = 'block';
                    } else {
                        card.style.display = 'none';
                    }
                });
            });
        });
        
        // 留言搜索功能
        const searchInput = document.getElementById('message-search');
        
        searchInput.addEventListener('input', () => {
            const searchTerm = searchInput.value.toLowerCase();
            
            messageCards.forEach(card => {
                const messageText = card.querySelector('p').textContent.toLowerCase();
                const nameText = card.querySelector('h4').textContent.toLowerCase();
                
                if (messageText.includes(searchTerm) || nameText.includes(searchTerm)) {
                    card.style.display = 'block';
                } else {
                    card.style.display = 'none';
                }
            });
        });
        
        // 点赞功能
        const likeButtons = document.querySelectorAll('.like-btn');
        
        likeButtons.forEach(button => {
            button.addEventListener('click', () => {
                const icon = button.querySelector('i');
                const countElement = button.querySelector('span');
                let count = parseInt(countElement.textContent);
                
                if (icon.classList.contains('fa-heart-o')) {
                    icon.classList.remove('fa-heart-o');
                    icon.classList.add('fa-heart', 'text-primary');
                    countElement.textContent = count + 1;
                } else {
                    icon.classList.remove('fa-heart', 'text-primary');
                    icon.classList.add('fa-heart-o');
                    countElement.textContent = count - 1;
                }
            });
        });
        
        // 留言表单提交
        const messageForm = document.getElementById('message-form');
        const successModal = document.getElementById('success-modal');
        const modalContent = document.getElementById('modal-content');
        const closeModal = document.getElementById('close-modal');
        const messagesContainer = document.getElementById('messages-container');
        
        messageForm.addEventListener('submit', (e) => {
            e.preventDefault();
            
            // 获取表单数据
            const name = document.getElementById('name').value;
            const location = document.getElementById('location').value;
            const category = document.getElementById('category').value;
            const message = document.getElementById('message').value;
            
            // 显示成功弹窗
            successModal.classList.remove('hidden');
            setTimeout(() => {
                modalContent.classList.remove('scale-95', 'opacity-0');
                modalContent.classList.add('scale-100', 'opacity-100');
            }, 10);
            
            // 创建新留言卡片并添加到留言板
            const today = new Date();
            const dateString = `${today.getFullYear()}-${String(today.getMonth() + 1).padStart(2, '0')}-${String(today.getDate()).padStart(2, '0')}`;
            
            let categoryText, categoryClass;
            switch(category) {
                case 'student':
                    categoryText = '学生';
                    categoryClass = 'bg-secondary/20 text-secondary';
                    break;
                case 'foreign':
                    categoryText = '外国友人';
                    categoryClass = 'bg-green-100 text-green-700';
                    break;
                case 'other':
                    categoryText = '其他';
                    categoryClass = 'bg-purple-100 text-purple-700';
                    break;
                default:
                    categoryText = '游客';
                    categoryClass = 'bg-primary/10 text-primary';
            }
            
            const randomAvatarId = Math.floor(Math.random() * 100) + 1000;
            
            const newMessage = document.createElement('div');
            newMessage.className = `message-card bg-light rounded-xl p-6 shadow-md hover:shadow-lg transition-shadow duration-300 animate-float`;
            newMessage.setAttribute('data-category', category);
            newMessage.innerHTML = `
                <div class="flex items-center mb-4">
                    <img src="https://picsum.photos/id/${randomAvatarId}/100/100" alt="${name}头像" class="w-12 h-12 rounded-full object-cover">
                    <div class="ml-4">
                        <h4 class="font-bold">${name}</h4>
                        <p class="text-sm text-gray-500">来自${location} · ${dateString}</p>
                    </div>
                </div>
                <p class="text-gray-700 mb-4">
                    ${message}
                </p>
                <div class="flex items-center justify-between">
                    <span class="inline-block ${categoryClass} px-3 py-1 rounded-full text-xs">${categoryText}</span>
                    <button class="like-btn flex items-center text-gray-500 hover:text-primary transition-colors">
                        <i class="fa fa-heart-o mr-1"></i> <span>0</span>
                    </button>
                </div>
            `;
            
            // 添加到留言容器顶部
            messagesContainer.insertBefore(newMessage, messagesContainer.firstChild);
            
            // 为新留言添加点赞功能
            const newLikeButton = newMessage.querySelector('.like-btn');
            newLikeButton.addEventListener('click', () => {
                const icon = newLikeButton.querySelector('i');
                const countElement = newLikeButton.querySelector('span');
                let count = parseInt(countElement.textContent);
                
                if (icon.classList.contains('fa-heart-o')) {
                    icon.classList.remove('fa-heart-o');
                    icon.classList.add('fa-heart', 'text-primary');
                    countElement.textContent = count + 1;
                } else {
                    icon.classList.remove('fa-heart', 'text-primary');
                    icon.classList.add('fa-heart-o');
                    countElement.textContent = count - 1;
                }
            });
            
            // 重置表单
            messageForm.reset();
        });
        
        // 关闭弹窗
        closeModal.addEventListener('click', () => {
            modalContent.classList.remove('scale-100', 'opacity-100');
            modalContent.classList.add('scale-95', 'opacity-0');
            
            setTimeout(() => {
                successModal.classList.add('hidden');
            }, 300);
        });
        
        // 点击弹窗外部关闭
        successModal.addEventListener('click', (e) => {
            if (e.target === successModal) {
                modalContent.classList.remove('scale-100', 'opacity-100');
                modalContent.classList.add('scale-95', 'opacity-0');
                
                setTimeout(() => {
                    successModal.classList.add('hidden');
                }, 300);
            }
        });
        
        // 加载更多留言
        const loadMoreButton = document.getElementById('load-more');
        let loadCount = 0;
        
        loadMoreButton.addEventListener('click', () => {
            // 模拟加载更多留言
            loadMoreButton.innerHTML = '<i class="fa fa-spinner fa-spin mr-2"></i> 加载中...';
            
            setTimeout(() => {
                // 复制现有留言并稍作修改作为新留言
                const existingMessages = document.querySelectorAll('.message-card');
                const randomIndex = Math.floor(Math.random() * existingMessages.length);
                const clonedMessage = existingMessages[randomIndex].cloneNode(true);
                
                // 修改一些内容使其看起来不同
                const randomAvatarId = Math.floor(Math.random() * 100) + 1100;
                clonedMessage.querySelector('img').src = `https://picsum.photos/id/${randomAvatarId}/100/100`;
                
                const today = new Date();
                today.setDate(today.getDate() - loadCount);
                const dateString = `${today.getFullYear()}-${String(today.getMonth() + 1).padStart(2, '0')}-${String(today.getDate()).padStart(2, '0')}`;
                clonedMessage.querySelector('.text-gray-500').textContent = `来自随机城市 · ${dateString}`;
                
                // 重置点赞
                const likeButton = clonedMessage.querySelector('.like-btn');
                likeButton.innerHTML = '<i class="fa fa-heart-o mr-1"></i> <span>0</span>';
                
                // 添加点赞功能
                likeButton.addEventListener('click', () => {
                    const icon = likeButton.querySelector('i');
                    const countElement = likeButton.querySelector('span');
                    let count = parseInt(countElement.textContent);
                    
                    if (icon.classList.contains('fa-heart-o')) {
                        icon.classList.remove('fa-heart-o');
                        icon.classList.add('fa-heart', 'text-primary');
                        countElement.textContent = count + 1;
                    } else {
                        icon.classList.remove('fa-heart', 'text-primary');
                        icon.classList.add('fa-heart-o');
                        countElement.textContent = count - 1;
                    }
                });
                
                // 添加到留言容器
                messagesContainer.appendChild(clonedMessage);
                
                loadCount++;
                loadMoreButton.textContent = '加载更多留言';
                
                // 滚动到新加载的留言
                clonedMessage.scrollIntoView({ behavior: 'smooth', block: 'nearest' });
            }, 1000);
        });
    </script>
</body>
</html>
