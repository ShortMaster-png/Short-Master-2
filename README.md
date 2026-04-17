<!DOCTYPE html>  
<html lang="ar" dir="rtl">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>AI ZONE | الإمبراطورية الرقمية</title>  
    
    <link rel="preconnect" href="https://fonts.googleapis.com">  
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>  
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@400;600;800;900&display=swap" rel="stylesheet">  
      
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css" />  

    <script src="https://cdn.tailwindcss.com"></script>  
      
    <script>  
        tailwind.config = {  
            theme: {  
                extend: {  
                    fontFamily: { sans: ['Cairo', 'sans-serif'] },  
                    colors: {  
                        dark: { bg: '#05050A', card: '#0A0A12', border: '#1A1A2E' },  
                        neon: { blue: '#00F0FF', purple: '#7000FF' }  
                    }  
                }  
            }  
        }  
    </script>  

    <style>  
        /* Cinematic & Luxury Base */
        body { background-color: #05050A; color: #FFFFFF; overflow-x: hidden; scroll-behavior: smooth; }  
        ::-webkit-scrollbar { width: 6px; }  
        ::-webkit-scrollbar-track { background: #05050A; }  
        ::-webkit-scrollbar-thumb { background: #7000FF; border-radius: 10px; }  

        /* Neon Gradients */
        .text-gradient { background: linear-gradient(to right, #00F0FF, #7000FF); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }  
        .bg-gradient-neon { background: linear-gradient(135deg, #00F0FF, #7000FF); }

        /* Cinematic Lighting Orbs */
        .orb { position: absolute; border-radius: 50%; filter: blur(120px); opacity: 0.4; pointer-events: none; z-index: -1; animation: pulse 8s infinite alternate; }
        .orb-blue { width: 500px; height: 500px; background: #00F0FF; top: -100px; right: -100px; }
        .orb-purple { width: 600px; height: 600px; background: #7000FF; bottom: -200px; left: -100px; }
        @keyframes pulse { 0% { transform: scale(1) opacity(0.3); } 100% { transform: scale(1.2) opacity(0.6); } }

        /* Ultra Premium Glass Cards */
        .glass-card { 
            background: rgba(10, 10, 18, 0.6); 
            border: 1px solid rgba(112, 0, 255, 0.2); 
            backdrop-filter: blur(20px); 
            border-radius: 24px; 
            transition: all 0.5s cubic-bezier(0.175, 0.885, 0.32, 1.275); 
            position: relative;
            overflow: hidden;
        }
        .glass-card::before {
            content: ''; position: absolute; top: 0; left: 0; width: 100%; height: 100%;
            background: linear-gradient(45deg, transparent, rgba(0, 240, 255, 0.05), transparent);
            transform: translateX(-100%); transition: 0.6s;
        }
        .glass-card:hover::before { transform: translateX(100%); }
        .glass-card:hover { 
            transform: translateY(-10px); 
            border-color: rgba(0, 240, 255, 0.6); 
            box-shadow: 0 20px 50px -10px rgba(112, 0, 255, 0.4); 
        }

        /* Payment Marquee */
        .marquee { overflow: hidden; white-space: nowrap; border-top: 1px solid rgba(0,240,255,0.1); border-bottom: 1px solid rgba(112,0,255,0.1); background: rgba(0,0,0,0.5); backdrop-filter: blur(10px); }
        .marquee-content { display: inline-flex; animation: scroll 20s linear infinite; }
        @keyframes scroll { 0% { transform: translateX(0); } 100% { transform: translateX(50%); } } 

        /* Floating WhatsApp Button - 100% Working */
        .wa-float { 
            position: fixed; bottom: 30px; right: 30px; width: 65px; height: 65px; 
            background: #25D366; color: white; border-radius: 50%; 
            display: flex; align-items: center; justify-content: center; font-size: 35px; 
            box-shadow: 0 10px 30px rgba(37, 211, 102, 0.4); z-index: 1000; 
            transition: all 0.3s ease; animation: bounce 2s infinite;
        }
        .wa-float:hover { transform: scale(1.15); background: #1EBE55; }
        @keyframes bounce { 0%, 20%, 50%, 80%, 100% {transform: translateY(0);} 40% {transform: translateY(-15px);} 60% {transform: translateY(-7px);} }
        
        .whatsapp-btn {
            display: block; text-align: center; width: 100%; padding: 12px; border-radius: 12px;
            font-weight: 900; transition: all 0.3s;
            background: rgba(255,255,255,0.05); border: 1px solid rgba(255,255,255,0.1); color: white;
        }
        .whatsapp-btn:hover { background: #25D366; border-color: #25D366; color: white; box-shadow: 0 0 20px rgba(37, 211, 102, 0.4); }
    </style>  
</head>  
<body class="antialiased">  

    <div class="orb orb-blue"></div>
    <div class="orb orb-purple"></div>
    <div class="fixed inset-0 bg-[url('data:image/svg+xml;base64,PHN2ZyB3aWR0aD0iMjAiIGhlaWdodD0iMjAiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyI+PGNpcmNsZSBjeD0iMiIgY3k9IjIiIHI9IjEiIGZpbGw9InJnYmEoMjU1LDI1NSwyNTUsMC4wMykiLz48L3N2Zz4=')] opacity-30 z-[-1]"></div>

    <nav class="fixed w-full z-50 bg-dark-bg/80 backdrop-blur-xl border-b border-white/5 py-5">
        <div class="max-w-7xl mx-auto px-6 flex justify-between items-center">
            <div class="flex items-center gap-3 cursor-pointer">
                <div class="w-12 h-12 bg-gradient-neon flex items-center justify-center rounded-xl font-black text-2xl text-white shadow-[0_0_20px_rgba(0,240,255,0.4)]">AI</div>
                <span class="font-black text-3xl tracking-widest text-white uppercase">ZONE</span>
            </div>
            <div class="hidden md:flex gap-8 text-sm font-bold text-gray-300">
                <a href="#ai-tools" class="hover:text-neon-blue transition-colors">أدوات الذكاء الاصطناعي</a>
                <a href="#accounts" class="hover:text-neon-purple transition-colors">حسابات جاهزة</a>
                <a href="#media" class="hover:text-neon-blue transition-colors">المونتاج والسوشيال</a>
            </div>
            <a href="https://wa.me/201500950624?text=مرحباً%20إدارة%20AI%20ZONE%20أريد%20الاستفسار" target="_blank" class="bg-white text-black px-6 py-2.5 rounded-full font-black hover:scale-105 transition-transform flex items-center gap-2">
                تواصل الآن <i class="fab fa-whatsapp text-lg text-green-500"></i>
            </a>
        </div>
    </nav>

    <a href="https://wa.me/201500950624?text=مرحباً%20إدارة%20AI%20ZONE%20أريد%20الاستفسار%20عن%20خدماتكم" target="_blank" class="wa-float">
        <i class="fab fa-whatsapp"></i>
    </a>

    <section class="pt-48 pb-20 px-6 text-center relative z-10">
        <div class="max-w-4xl mx-auto">
            <div class="inline-flex items-center gap-2 px-4 py-1 rounded-full border border-neon-purple/50 bg-neon-purple/10 text-neon-purple font-bold text-sm mb-6">
                <i class="fas fa-headset"></i> دعم مستمر 24 ساعة
            </div>
            <h1 class="text-6xl md:text-8xl font-black mb-6 leading-tight tracking-tighter">
                الترسانة الرقمية <br> <span class="text-gradient">بين يديك.</span>
            </h1>
            <p class="text-xl md:text-2xl text-gray-400 mb-10 font-medium max-w-2xl mx-auto">
                المنصة الأقوى لتفعيلات الذكاء الاصطناعي، القنوات المليونية، وخدمات السوشيال ميديا الاحترافية.
            </p>
            <a href="#ai-tools" class="inline-flex items-center justify-center bg-gradient-neon text-white px-12 py-4 rounded-2xl font-black text-xl hover:scale-105 transition-transform shadow-[0_0_40px_rgba(112,0,255,0.4)]">
                اكتشف الخدمات <i class="fas fa-arrow-down mr-3"></i>
            </a>
        </div>
    </section>

    <div class="marquee py-5 mb-24">
        <div class="marquee-content items-center gap-16 text-gray-300 font-black text-2xl uppercase tracking-wider">
            <span class="flex items-center gap-3"><i class="fas fa-wallet text-red-500"></i> فودافون كاش</span> •
            <span class="flex items-center gap-3"><i class="fas fa-mobile-alt text-purple-400"></i> إنستاباي</span> •
            <span class="flex items-center gap-3"><i class="fab fa-cc-visa text-blue-400"></i> فيزا / ماستركارد</span> •
            <span class="flex items-center gap-3"><i class="fab fa-bitcoin text-yellow-500"></i> بايننس (USDT)</span> •
            <span class="flex items-center gap-3"><i class="fas fa-wallet text-red-500"></i> فودافون كاش</span> •
            <span class="flex items-center gap-3"><i class="fas fa-mobile-alt text-purple-400"></i> إنستاباي</span> •
            <span class="flex items-center gap-3"><i class="fab fa-cc-visa text-blue-400"></i> فيزا / ماستركارد</span> •
            <span class="flex items-center gap-3"><i class="fab fa-bitcoin text-yellow-500"></i> بايننس (USDT)</span>
        </div>
    </div>

    <section id="ai-tools" class="py-16 px-6 relative z-10">
        <div class="max-w-7xl mx-auto">
            <h2 class="text-4xl md:text-5xl font-black mb-12 text-center text-white">تفعيلات <span class="text-neon-blue">الذكاء الاصطناعي</span></h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
                <div class="glass-card p-8 text-center flex flex-col h-full">
                    <div class="w-20 h-20 mx-auto bg-[#10a37f]/10 border border-[#10a37f]/30 text-[#10a37f] rounded-2xl flex items-center justify-center text-4xl mb-6 shadow-[0_0_20px_rgba(16,163,127,0.2)]"><i class="fas fa-robot"></i></div>
                    <h3 class="text-2xl font-black text-white mb-3">شات جي بي تي بلس</h3>
                    <p class="text-gray-400 mb-8 font-medium">وصول غير محدود لنموذج GPT-4 المتطور، والمكونات الإضافية الذكية.</p>
                    <div class="mt-auto">
                        <a href="https://wa.me/201500950624?text=مرحباً%20AI%20ZONE%20أريد%20الاستفسار%20عن%20اشتراك%20شات%20جي%20بي%20تي%20بلس" target="_blank" class="whatsapp-btn">
                            <i class="fab fa-whatsapp text-lg mr-2"></i> اطلب التفعيل الآن
                        </a>
                    </div>
                </div>

                <div class="glass-card p-8 text-center flex flex-col h-full">
                    <div class="w-20 h-20 mx-auto bg-[#d97757]/10 border border-[#d97757]/30 text-[#d97757] rounded-2xl flex items-center justify-center text-4xl mb-6 shadow-[0_0_20px_rgba(217,119,87,0.2)]"><i class="fas fa-brain"></i></div>
                    <h3 class="text-2xl font-black text-white mb-3">كلود برو (Claude 3)</h3>
                    <p class="text-gray-400 mb-8 font-medium">الأقوى في تحليل الملفات الضخمة وكتابة المحتوى بلمسة بشرية إبداعية.</p>
                    <div class="mt-auto">
                        <a href="https://wa.me/201500950624?text=مرحباً%20AI%20ZONE%20أريد%20الاستفسار%20عن%20اشتراك%20كلود%20برو" target="_blank" class="whatsapp-btn">
                            <i class="fab fa-whatsapp text-lg mr-2"></i> اطلب التفعيل الآن
                        </a>
                    </div>
                </div>

                <div class="glass-card p-8 text-center flex flex-col h-full">
                    <div class="w-20 h-20 mx-auto bg-[#1b61d1]/10 border border-[#1b61d1]/30 text-[#1b61d1] rounded-2xl flex items-center justify-center text-4xl mb-6 shadow-[0_0_20px_rgba(27,97,209,0.2)]"><i class="fas fa-sparkles"></i></div>
                    <h3 class="text-2xl font-black text-white mb-3">جيمناي أدفانسد</h3>
                    <p class="text-gray-400 mb-8 font-medium">ذكاء جوجل المدمر، مرتبط بمساحة عمل جوجل للإنتاجية القصوى.</p>
                    <div class="mt-auto">
                        <a href="https://wa.me/201500950624?text=مرحباً%20AI%20ZONE%20أريد%20الاستفسار%20عن%20اشتراك%20جيمناي%20أدفانسد" target="_blank" class="whatsapp-btn">
                            <i class="fab fa-whatsapp text-lg mr-2"></i> اطلب التفعيل الآن
                        </a>
                    </div>
                </div>

                <div class="glass-card p-8 text-center flex flex-col h-full">
                    <div class="w-20 h-20 mx-auto bg-white/10 border border-white/20 text-white rounded-2xl flex items-center justify-center text-4xl mb-6 shadow-[0_0_20px_rgba(255,255,255,0.1)]"><i class="fa-brands fa-x-twitter"></i></div>
                    <h3 class="text-2xl font-black text-white mb-3">جروك بريميوم (Grok)</h3>
                    <p class="text-gray-400 mb-8 font-medium">وصول فوري للبيانات الحية من منصة X، ذكاء اصطناعي غير مفلتر.</p>
                    <div class="mt-auto">
                        <a href="https://wa.me/201500950624?text=مرحباً%20AI%20ZONE%20أريد%20الاستفسار%20عن%20اشتراك%20جروك" target="_blank" class="whatsapp-btn">
                            <i class="fab fa-whatsapp text-lg mr-2"></i> اطلب التفعيل الآن
                        </a>
                    </div>
                </div>

                <div class="glass-card p-8 text-center flex flex-col h-full">
                    <div class="w-20 h-20 mx-auto bg-[#ffffff]/10 border border-[#ffffff]/30 text-white rounded-2xl flex items-center justify-center text-4xl mb-6 shadow-[0_0_20px_rgba(255,255,255,0.1)]"><i class="fas fa-video"></i></div>
                    <h3 class="text-2xl font-black text-white mb-3">كاب كات برو (CapCut)</h3>
                    <p class="text-gray-400 mb-8 font-medium">اشتراك صُناع المحتوى، تأثيرات حصرية وأدوات مونتاج بالذكاء الاصطناعي.</p>
                    <div class="mt-auto">
                        <a href="https://wa.me/201500950624?text=مرحباً%20AI%20ZONE%20أريد%20الاستفسار%20عن%20اشتراك%20كاب%20كات%20برو" target="_blank" class="whatsapp-btn">
                            <i class="fab fa-whatsapp text-lg mr-2"></i> اطلب التفعيل الآن
                        </a>
                    </div>
                </div>

                <div class="glass-card p-8 text-center flex flex-col h-full">
                    <div class="w-20 h-20 mx-auto bg-[#1273eb]/10 border border-[#1273eb]/30 text-[#1273eb] rounded-2xl flex items-center justify-center text-4xl mb-6 shadow-[0_0_20px_rgba(18,115,235,0.2)]"><i class="fas fa-layer-group"></i></div>
                    <h3 class="text-2xl font-black text-white mb-3">فري بيك بريميوم</h3>
                    <p class="text-gray-400 mb-8 font-medium">الكنز الأكبر للمصممين، تحميل لا محدود للصور المفتوحة والفيكتور.</p>
                    <div class="mt-auto">
                        <a href="https://wa.me/201500950624?text=مرحباً%20AI%20ZONE%20أريد%20الاستفسار%20عن%20اشتراك%20فري%20بيك" target="_blank" class="whatsapp-btn">
                            <i class="fab fa-whatsapp text-lg mr-2"></i> اطلب التفعيل الآن
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <section id="accounts" class="py-16 px-6 relative z-10">
        <div class="max-w-7xl mx-auto">
            <h2 class="text-4xl md:text-5xl font-black mb-12 text-center text-white">قنوات وحسابات <span class="text-neon-purple">جاهزة</span></h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="glass-card p-8 text-center border-t-4 border-t-red-500">
                    <i class="fab fa-youtube text-red-500 text-6xl mb-6 drop-shadow-[0_0_15px_rgba(239,68,68,0.5)]"></i>
                    <h3 class="text-2xl font-black text-white mb-4">قنوات يوتيوب للربح</h3>
                    <p class="text-gray-400 font-medium mb-8">قنوات مستوفية شروط 4000 ساعة و 1000 مشترك، جاهزة لربط أدسنس واستلام الأرباح.</p>
                    <a href="https://wa.me/201500950624?text=مرحباً%20AI%20ZONE%20أريد%20شراء%20قناة%20يوتيوب%20مفعلة" target="_blank" class="whatsapp-btn">تواصل لطلب قناة</a>
                </div>

                <div class="glass-card p-8 text-center border-t-4 border-t-white">
                    <i class="fab fa-tiktok text-white text-6xl mb-6 drop-shadow-[0_0_15px_rgba(255,255,255,0.5)]"></i>
                    <h3 class="text-2xl font-black text-white mb-4">حسابات تيك توك قوية</h3>
                    <p class="text-gray-400 font-medium mb-8">حسابات بمتابعين حقيقيين، ميزة البث المباشر (اللايف) مفعلة وجاهزة للصعود للتريند.</p>
                    <a href="https://wa.me/201500950624?text=مرحباً%20AI%20ZONE%20أريد%20شراء%20حساب%20تيك%20توك" target="_blank" class="whatsapp-btn">تواصل لطلب حساب</a>
                </div>

                <div class="glass-card p-8 text-center border-t-4 border-t-pink-500">
                    <i class="fab fa-instagram text-pink-500 text-6xl mb-6 drop-shadow-[0_0_15px_rgba(236,72,153,0.5)]"></i>
                    <h3 class="text-2xl font-black text-white mb-4">حسابات انستجرام</h3>
                    <p class="text-gray-400 font-medium mb-8">حسابات انستا بمعدل تفاعل عالي جداً، مثالية لبدء البزنس الخاص بك أو التوثيق.</p>
                    <a href="https://wa.me/201500950624?text=مرحباً%20AI%20ZONE%20أريد%20شراء%20حساب%20انستجرام" target="_blank" class="whatsapp-btn">تواصل لطلب حساب</a>
                </div>
            </div>
        </div>
    </section>

    <section id="media" class="py-16 px-6 relative z-10 mb-20">
        <div class="max-w-7xl mx-auto">
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
                
                <div>
                    <h2 class="text-3xl font-black mb-8 text-white flex items-center gap-3"><i class="fas fa-users text-neon-blue"></i> دعم السوشيال ميديا</h2>
                    <div class="space-y-4">
                        <a href="https://wa.me/201500950624?text=مرحباً%20AI%20ZONE%20أريد%20خدمة%20متابعين%20انستجرام" target="_blank" class="glass-card p-5 flex items-center justify-between hover:border-pink-500/50 group block">
                            <div class="flex items-center gap-4"><i class="fab fa-instagram text-pink-500 text-2xl w-8"></i> <span class="font-bold text-lg text-white">متابعين ولايكات انستجرام VIP</span></div>
                            <i class="fas fa-chevron-left text-gray-500 group-hover:text-pink-500 transition-colors"></i>
                        </a>
                        <a href="https://wa.me/201500950624?text=مرحباً%20AI%20ZONE%20أريد%20خدمة%20دعم%20تيك%20توك" target="_blank" class="glass-card p-5 flex items-center justify-between hover:border-white/50 group block">
                            <div class="flex items-center gap-4"><i class="fab fa-tiktok text-white text-2xl w-8"></i> <span class="font-bold text-lg text-white">متابعين ومشاهدات تيك توك</span></div>
                            <i class="fas fa-chevron-left text-gray-500 group-hover:text-white transition-colors"></i>
                        </a>
                        <a href="https://wa.me/201500950624?text=مرحباً%20AI%20ZONE%20أريد%20خدمة%20شروط%20يوتيوب" target="_blank" class="glass-card p-5 flex items-center justify-between hover:border-red-500/50 group block">
                            <div class="flex items-center gap-4"><i class="fab fa-youtube text-red-500 text-2xl w-8"></i> <span class="font-bold text-lg text-white">تحقيق شروط يوتيوب بالكامل</span></div>
                            <i class="fas fa-chevron-left text-gray-500 group-hover:text-red-500 transition-colors"></i>
                        </a>
                        <a href="https://wa.me/201500950624?text=مرحباً%20AI%20ZONE%20أريد%20خدمة%20دعم%20فيسبوك" target="_blank" class="glass-card p-5 flex items-center justify-between hover:border-blue-500/50 group block">
                            <div class="flex items-center gap-4"><i class="fab fa-facebook text-blue-500 text-2xl w-8"></i> <span class="font-bold text-lg text-white">تفاعل ومتابعين لصفحات فيسبوك</span></div>
                            <i class="fas fa-chevron-left text-gray-500 group-hover:text-blue-500 transition-colors"></i>
                        </a>
                    </div>
                </div>

                <div>
                    <h2 class="text-3xl 
