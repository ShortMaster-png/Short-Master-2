<!DOCTYPE html>  
<html lang="ar" dir="rtl">  
<head>  
    <meta charset="UTF-8">  
    <meta name="viewport" content="width=device-width, initial-scale=1.0">  
    <title>Short Master | متجرك الرقمي المتكامل</title>  
    
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
                        dark: { 950: '#030712', 900: '#111827', 800: '#1f2937' },  
                        brand: { cyan: '#00e5ff', blue: '#2563eb', purple: '#9333ea', gold: '#fbbf24', green: '#10b981' }  
                    }  
                }  
            }  
        }  
    </script>  

    <style>  
        body { background-color: #030712; color: #f3f4f6; scroll-behavior: smooth; overflow-x: hidden; }  
        
        /* Gradients */
        .text-gradient { background: linear-gradient(to right, #ffffff, #00e5ff); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }  
        .text-gradient-gold { background: linear-gradient(to right, #fde68a, #fbbf24); -webkit-background-clip: text; -webkit-text-fill-color: transparent; }  

        /* Glass Cards */
        .glass-card { background: rgba(17, 24, 39, 0.7); border: 1px solid rgba(255, 255, 255, 0.08); backdrop-filter: blur(16px); border-radius: 24px; transition: all 0.4s ease; }
        .glass-card:hover { transform: translateY(-8px); border-color: rgba(0, 229, 255, 0.4); box-shadow: 0 20px 40px -10px rgba(0, 229, 255, 0.15); }
        
        /* VIP Glow Card */
        .vip-card { position: relative; z-index: 1; overflow: hidden; }
        .vip-card::before { content: ''; position: absolute; inset: 0; background: linear-gradient(45deg, transparent, rgba(251, 191, 36, 0.1), transparent); z-index: -1; transition: 0.5s; opacity: 0; }
        .vip-card:hover::before { opacity: 1; transform: scale(1.2); }
        .vip-card:hover { border-color: rgba(251, 191, 36, 0.5); box-shadow: 0 20px 40px -10px rgba(251, 191, 36, 0.2); }

        /* Marquee for Payments */
        .marquee { overflow: hidden; white-space: nowrap; mask-image: linear-gradient(to right, transparent, black 10%, black 90%, transparent); border-top: 1px solid rgba(255,255,255,0.05); border-bottom: 1px solid rgba(255,255,255,0.05); background: rgba(255,255,255,0.02); }
        .marquee-content { display: inline-flex; animation: scroll 25s linear infinite; }
        @keyframes scroll { 0% { transform: translateX(0); } 100% { transform: translateX(50%); } } /* Positive for RTL */

        /* Floating WhatsApp */
        .wa-float { position: fixed; bottom: 30px; right: 30px; width: 60px; height: 60px; background: #25D366; color: white; border-radius: 50%; display: flex; align-items: center; justify-content: center; font-size: 30px; box-shadow: 0 10px 20px rgba(37, 211, 102, 0.3); z-index: 100; transition: 0.3s; }
        .wa-float:hover { transform: scale(1.1); }
    </style>  
</head>  
<body class="antialiased">  

    <nav class="fixed w-full z-50 bg-dark-950/80 backdrop-blur-md border-b border-white/5 py-4">
        <div class="max-w-7xl mx-auto px-6 flex justify-between items-center">
            <div class="flex items-center gap-3 cursor-pointer">
                <div class="w-10 h-10 bg-brand-cyan text-dark-950 flex items-center justify-center rounded-xl font-black text-xl">SM</div>
                <span class="font-black text-2xl text-white">Short<span class="text-brand-cyan">Master</span></span>
            </div>
            <div class="hidden md:flex gap-8 text-sm font-bold text-gray-300">
                <a href="#premium-ai" class="hover:text-brand-cyan transition-colors">تفعيلات الذكاء الاصطناعي</a>
                <a href="#ready-accounts" class="hover:text-brand-gold transition-colors">حسابات وقنوات جاهزة</a>
                <a href="#social-video" class="hover:text-brand-cyan transition-colors">خدمات السوشيال والفيديو</a>
            </div>
            <button onclick="order('استفسار عام', '')" class="bg-white text-dark-950 px-6 py-2 rounded-full font-bold hover:bg-gray-200 transition-colors">
                تواصل معنا <i class="fab fa-whatsapp ml-1"></i>
            </button>
        </div>
    </nav>

    <a href="#" onclick="order('مرحباً، أريد الاستفسار عن خدماتكم', ''); return false;" class="wa-float">
        <i class="fab fa-whatsapp"></i>
    </a>

    <section class="pt-40 pb-20 px-6 text-center">
        <div class="max-w-4xl mx-auto">
            <h1 class="text-5xl md:text-7xl font-black mb-6 leading-tight">
                أدواتك للنجاح الرقمي <br> <span class="text-gradient">في مكان واحد.</span>
            </h1>
            <p class="text-xl text-gray-400 mb-10">من اشتراكات الذكاء الاصطناعي الرسمية، إلى القنوات الجاهزة للربح وصناعة الفيديوهات الاحترافية.</p>
            <a href="#premium-ai" class="inline-block bg-brand-cyan text-dark-950 px-10 py-4 rounded-2xl font-black text-lg hover:scale-105 transition-transform shadow-[0_0_30px_rgba(0,229,255,0.3)]">
                تصفح الخدمات
            </a>
        </div>
    </section>

    <div class="marquee py-4 mb-20">
        <div class="marquee-content items-center gap-12 text-gray-400 font-bold text-xl">
            <span class="flex items-center gap-2"><i class="fas fa-wallet text-red-500"></i> فودافون كاش</span> •
            <span class="flex items-center gap-2"><i class="fas fa-mobile-alt text-purple-500"></i> إنستاباي (InstaPay)</span> •
            <span class="flex items-center gap-2"><i class="fab fa-cc-visa text-blue-500"></i> فيزا / ماستركارد</span> •
            <span class="flex items-center gap-2"><i class="fab fa-bitcoin text-yellow-500"></i> بايننس (USDT)</span> •
            <span class="flex items-center gap-2"><i class="fab fa-paypal text-blue-400"></i> باي بال</span> •
            <span class="flex items-center gap-2"><i class="fas fa-wallet text-red-500"></i> فودافون كاش</span> •
            <span class="flex items-center gap-2"><i class="fas fa-mobile-alt text-purple-500"></i> إنستاباي (InstaPay)</span> •
            <span class="flex items-center gap-2"><i class="fab fa-cc-visa text-blue-500"></i> فيزا / ماستركارد</span> •
            <span class="flex items-center gap-2"><i class="fab fa-bitcoin text-yellow-500"></i> بايننس (USDT)</span> •
            <span class="flex items-center gap-2"><i class="fab fa-paypal text-blue-400"></i> باي بال</span>
        </div>
    </div>

    <section id="premium-ai" class="py-16 px-6">
        <div class="max-w-7xl mx-auto">
            <h2 class="text-3xl md:text-4xl font-black mb-10 text-center"><i class="fas fa-crown text-brand-gold mr-2"></i> التفعيلات <span class="text-brand-cyan">الأكثر طلباً</span></h2>
            
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-6">
                <div class="glass-card p-8 text-center">
                    <div class="w-16 h-16 mx-auto bg-green-500/10 text-green-400 rounded-2xl flex items-center justify-center text-3xl mb-6"><i class="fas fa-robot"></i></div>
                    <h3 class="text-2xl font-black text-white mb-2">شات جي بي تي بلس</h3>
                    <p class="text-gray-400 mb-6 text-sm">اشتراك ChatGPT Plus الرسمي (GPT-4) للوصول لأذكى نموذج لغوي.</p>
                    <button onclick="order('اشتراك شات جي بي تي بلس', '')" class="w-full bg-white/10 hover:bg-green-500 hover:text-white border border-white/10 py-3 rounded-xl font-bold transition-all">اطلب التفعيل</button>
                </div>

                <div class="glass-card p-8 text-center">
                    <div class="w-16 h-16 mx-auto bg-orange-500/10 text-orange-400 rounded-2xl flex items-center justify-center text-3xl mb-6"><i class="fas fa-brain"></i></div>
                    <h3 class="text-2xl font-black text-white mb-2">كلود برو (Claude Pro)</h3>
                    <p class="text-gray-400 mb-6 text-sm">العملاق كلود 3، الأفضل في تحليل الملفات الضخمة والكتابة الإبداعية البشرية.</p>
                    <button onclick="order('اشتراك كلود برو', '')" class="w-full bg-white/10 hover:bg-orange-500 hover:text-white border border-white/10 py-3 rounded-xl font-bold transition-all">اطلب التفعيل</button>
                </div>

                <div class="glass-card p-8 text-center">
                    <div class="w-16 h-16 mx-auto bg-blue-500/10 text-blue-400 rounded-2xl flex items-center justify-center text-3xl mb-6"><i class="fas fa-sparkles"></i></div>
                    <h3 class="text-2xl font-black text-white mb-2">جوجل جيمناي أدفانسد</h3>
                    <p class="text-gray-400 mb-6 text-sm">أقوى ذكاء اصطناعي من جوجل (Gemini Advanced) مرتبط بخدمات جوجل.</p>
                    <button onclick="order('اشتراك جيمناي أدفانسد', '')" class="w-full bg-white/10 hover:bg-blue-600 hover:text-white border border-white/10 py-3 rounded-xl font-bold transition-all">اطلب التفعيل</button>
                </div>

                <div class="glass-card p-8 text-center">
                    <div class="w-16 h-16 mx-auto bg-white/10 text-white rounded-2xl flex items-center justify-center text-3xl mb-6"><i class="fa-brands fa-x-twitter"></i></div>
                    <h3 class="text-2xl font-black text-white mb-2">جروك بريميوم (Grok)</h3>
                    <p class="text-gray-400 mb-6 text-sm">الذكاء الاصطناعي الخاص بمنصة X، معلومات حية وغير مفلترة فورياً.</p>
                    <button onclick="order('اشتراك جروك', '')" class="w-full bg-white/10 hover:bg-white hover:text-black border border-white/10 py-3 rounded-xl font-bold transition-all">اطلب التفعيل</button>
                </div>

                <div class="glass-card p-8 text-center">
                    <div class="w-16 h-16 mx-auto bg-gray-800 text-white rounded-2xl flex items-center justify-center text-3xl mb-6 border border-gray-600"><i class="fas fa-scissors"></i></div>
                    <h3 class="text-2xl font-black text-white mb-2">كاب كات برو (CapCut)</h3>
                    <p class="text-gray-400 mb-6 text-sm">اشتراك CapCut Pro لفتح جميع التأثيرات والأدوات الاحترافية للمونتاج.</p>
                    <button onclick="order('اشتراك كاب كات برو', '')" class="w-full bg-white/10 hover:bg-gray-700 hover:text-white border border-white/10 py-3 rounded-xl font-bold transition-all">اطلب التفعيل</button>
                </div>

                <div class="glass-card p-8 text-center">
                    <div class="w-16 h-16 mx-auto bg-blue-600/10 text-blue-500 rounded-2xl flex items-center justify-center text-3xl mb-6"><i class="fas fa-vector-square"></i></div>
                    <h3 class="text-2xl font-black text-white mb-2">فري بيك بريميوم</h3>
                    <p class="text-gray-400 mb-6 text-sm">حمل ملايين الصور، الفيكتور، وملفات الـ PSD بأعلى جودة للمصممين.</p>
                    <button onclick="order('اشتراك فري بيك', '')" class="w-full bg-white/10 hover:bg-blue-600 hover:text-white border border-white/10 py-3 rounded-xl font-bold transition-all">اطلب التفعيل</button>
                </div>
            </div>
        </div>
    </section>

    <section id="ready-accounts" class="py-16 px-6 bg-dark-900/50">
        <div class="max-w-7xl mx-auto">
            <h2 class="text-3xl md:text-4xl font-black mb-10 text-center"><i class="fas fa-store text-brand-gold mr-2"></i> قنوات وحسابات <span class="text-gradient-gold">جاهزة للربح</span></h2>
            
            <div class="grid grid-cols-1 md:grid-cols-3 gap-8">
                <div class="glass-card vip-card p-6 flex flex-col items-center text-center border-brand-gold/20">
                    <i class="fab fa-youtube text-red-500 text-5xl mb-4"></i>
                    <h3 class="text-xl font-black text-white mb-2">قنوات يوتيوب مفعلة الربح</h3>
                    <p class="text-gray-400 text-sm mb-6">قنوات حقيقية مستوفية شروط 4000 ساعة و 1000 مشترك، جاهزة لربط أدسنس والبدء بجني الأرباح فوراً.</p>
                    <button onclick="order('شراء قناة يوتيوب مفعلة', '')" class="mt-auto bg-brand-gold text-dark-950 w-full py-3 rounded-xl font-bold hover:bg-yellow-500">استعرض القنوات</button>
                </div>

                <div class="glass-card vip-card p-6 flex flex-col items-center text-center border-brand-cyan/20">
                    <i class="fab fa-tiktok text-white text-5xl mb-4"></i>
                    <h3 class="text-xl font-black text-white mb-2">حسابات تيك توك قوية</h3>
                    <p class="text-gray-400 text-sm mb-6">حسابات تيك توك بها متابعين حقيقيين، جاهزة لفتح البث المباشر (لايف) والانضمام لبرامج المكافآت.</p>
                    <button onclick="order('شراء حساب تيك توك', '')" class="mt-auto bg-white text-dark-950 w-full py-3 rounded-xl font-bold hover:bg-gray-200">استعرض الحسابات</button>
                </div>

                <div class="glass-card vip-card p-6 flex flex-col items-center text-center border-purple-500/20">
                    <i class="fab fa-instagram text-pink-500 text-5xl mb-4"></i>
                    <h3 class="text-xl font-black text-white mb-2">حسابات انستجرام متفاعلة</h3>
                    <p class="text-gray-400 text-sm mb-6">حسابات انستا بمتابعين حقيقيين ومعدل تفاعل عالي، ممتازة لبدء مشروعك التجاري أو الشخصي.</p>
                    <button onclick="order('شراء حساب انستجرام', '')" class="mt-auto bg-gradient-to-r from-purple-500 to-pink-500 text-white w-full py-3 rounded-xl font-bold hover:opacity-90">استعرض الحسابات</button>
                </div>
            </div>
        </div>
    </section>

    <section id="social-video" class="py-16 px-6">
        <div class="max-w-7xl mx-auto">
            
            <div class="grid grid-cols-1 lg:grid-cols-2 gap-12">
                
                <div>
                    <h2 class="text-2xl font-black mb-6 text-white border-b border-white/10 pb-4"><i class="fas fa-users text-brand-blue mr-2"></i> دعم السوشيال ميديا والمتابعين</h2>
                    <ul class="space-y-3">
                        <li onclick="order('متابعين انستجرام', '')" class="glass-card p-4 rounded-xl flex items-center justify-between cursor-pointer hover:border-brand-blue/50">
                            <div class="flex items-center gap-3"><i class="fab fa-instagram text-pink-500 text-xl w-6"></i> <span class="font-bold text-gray-200">زيادة متابعين انستجرام (جودة عالية)</span></div>
                            <i class="fas fa-chevron-left text-gray-600 text-sm"></i>
                        </li>
                        <li onclick="order('متابعين تيك توك', '')" class="glass-card p-4 rounded-xl flex items-center justify-between cursor-pointer hover:border-white/50">
                            <div class="flex items-center gap-3"><i class="fab fa-tiktok text-white text-xl w-6"></i> <span class="font-bold text-gray-200">متابعين تيك توك (لدعم اللايف والتريند)</span></div>
                            <i class="fas fa-chevron-left text-gray-600 text-sm"></i>
                        </li>
                        <li onclick="order('مشتركين ومشاهدات يوتيوب', '')" class="glass-card p-4 rounded-xl flex items-center justify-between cursor-pointer hover:border-red-500/50">
                            <div class="flex items-center gap-3"><i class="fab fa-youtube text-red-500 text-xl w-6"></i> <span class="font-bold text-gray-200">تحقيق شروط يوتيوب (مشتركين وساعات)</span></div>
                            <i class="fas fa-chevron-left text-gray-600 text-sm"></i>
                        </li>
                        <li onclick="order('لايكات وتفاعل انستا', '')" class="glass-card p-4 rounded-xl flex items-center justify-between cursor-pointer hover:border-pink-500/50">
                            <div class="flex items-center gap-3"><i class="fas fa-heart text-pink-500 text-xl w-6"></i> <span class="font-bold text-gray-200">لايكات ومشاهدات ريلز انستجرام</span></div>
                            <i class="fas fa-chevron-left text-gray-600 text-sm"></i>
                        </li>
                        <li onclick="order('تفاعل صفحات فيسبوك', '')" class="glass-card p-4 rounded-xl flex items-center justify-between cursor-pointer hover:border-blue-500/50">
                            <div class="flex items-center gap-3"><i class="fab fa-facebook text-blue-500 text-xl w-6"></i> <span class="font-bold text-gray-200">متابعين ولايكات لصفحات فيسبوك</span></div>
                            <i class="fas fa-chevron-left text-gray-600 text-sm"></i>
                        </li>
                    </ul>
                </div>

                <div>
                    <h2 class="text-2xl font-black mb-6 text-white border-b border-white/10 pb-4"><i class="fas fa-video text-brand-purple mr-2"></i> صناعة الفيديوهات والتصميم</h2>
                    <ul class="space-y-3">
                        <li onclick="order('مونتاج فيديوهات قصيره', '')" class="glass-card p-4 rounded-xl flex items-center justify-between cursor-pointer hover:border-brand-purple/50">
                            <div class="flex items-center gap-3"><i class="fas fa-cut text-brand-cyan text-xl w-6"></i> <span class="font-bold text-gray-200">مونتاج احترافي (ريلز، شورتس، تيك توك)</span></div>
                            <i class="fas fa-chevron-left text-gray-600 text-sm"></i>
                        </li>
                        <li onclick="order('تصميم موشن جرافيك', '')" class="glass-card p-4 rounded-xl flex items-center justify-between cursor-pointer hover:border-brand-purple/50">
                            <div class="flex items-center gap-3"><i class="fas fa-layer-group text-purple-400 text-xl w-6"></i> <span class="font-bold text-gray-200">تصميم فيديوهات موشن جرافيك إعلانية</span></div>
                            <i class="fas fa-chevron-left text-gray-600 text-sm"></i>
                        </li>
                        <li onclick="order('تصميم UGC', '')" class="glass-card p-4 rounded-xl flex items-center justify-between cursor-pointer hover:border-brand-purple/50">
                            <div class="flex items-center gap-3"><i class="fas fa-mobile-alt text-brand-gold text-xl w-6"></i> <span class="font-bold text-gray-200">صناعة فيديوهات UGC (محتوى مستخدمين)</span></div>
                            <i class="fas fa-chevron-left text-gray-600 text-sm"></i>
                        </li>
                        <li onclick="order('كتابة سكريبت', '')" class="glass-card p-4 rounded-xl flex items-center justify-between cursor-pointer hover:border-brand-purple/50">
                            <div class="flex items-center gap-3"><i class="fas fa-pen-nib text-green-400 text-xl w-6"></i> <span class="font-bold text-gray-200">كتابة سكريبت فيديوهات (Viral Scripts)</span></div>
                            <i class="fas fa-chevron-left text-gray-600 text-sm"></i>
                        </li>
                        <li onclick="order('تصميم صورة مصغرة', '')" class="glass-card p-4 rounded-xl flex items-center justify-between cursor-pointer hover:border-brand-purple/50">
                            <div class="flex items-center gap-3"><i class="fas fa-image text-blue-400 text-xl w-6"></i> <span class="font-bold text-gray-200">تصميم صور مصغرة (Thumbnails) يوتيوب</span></div>
                            <i class="fas fa-chevron-left text-gray-600 text-sm"></i>
                        </li>
                    </ul>
                </div>

            </div>
        </div>
    </section>

    <footer class="bg-dark-950 py-10 border-t border-white/5 text-center px-6">
        <div class="max-w-4xl mx-auto flex flex-col items-center">
            <h3 class="font-black text-2xl text-whit
