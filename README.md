<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>فارسكور - دليلك الشامل</title>
    <script src="https://cdn.tailwindcss.com/3.4.16"></script>
    <script>tailwind.config={theme:{extend:{colors:{primary:'#2563eb',secondary:'#f59e0b'},borderRadius:{'none':'0px','sm':'4px',DEFAULT:'8px','md':'12px','lg':'16px','xl':'20px','2xl':'24px','3xl':'32px','full':'9999px','button':'8px'}}}}</script>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Pacifico&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Tajawal:wght@300;400;500;700&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/remixicon/4.6.0/remixicon.min.css">
    <style>
        :where([class^="ri-"])::before { content: "\f3c2"; }
        body {
            font-family: 'Tajawal', sans-serif;
            background-color: #f8f9fa;
        }
        .banner-slider::-webkit-scrollbar {
            display: none;
        }
        .categories-slider::-webkit-scrollbar {
            display: none;
        }
        .news-slider::-webkit-scrollbar {
            display: none;
        }
    </style>
</head>
<body class="bg-white text-gray-800">
    <!-- Nav Bar -->
    <div class="fixed top-0 w-full bg-primary text-white shadow-md z-50">
        <div class="flex items-center justify-between px-4 py-3">
            <div class="flex items-center space-x-2 space-x-reverse">
                <div class="w-8 h-8 flex items-center justify-center">
                    <i class="ri-menu-line ri-lg"></i>
                </div>
                <h1 class="text-xl font-['Pacifico'] font-bold">logo</h1>
            </div>
            <div class="flex items-center space-x-3 space-x-reverse">
                <div class="w-8 h-8 flex items-center justify-center relative cursor-pointer">
                    <i class="ri-notification-3-line ri-lg"></i>
                    <span class="absolute top-0 right-0 w-2 h-2 bg-red-500 rounded-full"></span>
                </div>
                <div class="w-8 h-8 flex items-center justify-center cursor-pointer">
                    <i class="ri-search-line ri-lg"></i>
                </div>
            </div>
        </div>
    </div>

    <!-- Main Content -->
    <div class="pt-16 pb-16">
        <!-- Categories Slider -->
        <div class="px-4 mt-4">
            <div class="categories-slider flex overflow-x-auto space-x-3 space-x-reverse py-2">
                <div class="flex flex-col items-center min-w-[60px] cursor-pointer">
                    <div class="w-12 h-12 rounded-full bg-blue-100 flex items-center justify-center">
                        <i class="ri-store-2-line ri-lg text-primary"></i>
                    </div>
                    <span class="text-xs mt-1 whitespace-nowrap overflow-hidden text-overflow-ellipsis">المحلات</span>
                </div>
                <div class="flex flex-col items-center min-w-[60px] cursor-pointer">
                    <div class="w-12 h-12 rounded-full bg-red-100 flex items-center justify-center">
                        <i class="ri-restaurant-line ri-lg text-red-500"></i>
                    </div>
                    <span class="text-xs mt-1 whitespace-nowrap overflow-hidden text-overflow-ellipsis">المطاعم</span>
                </div>
                <div class="flex flex-col items-center min-w-[60px] cursor-pointer">
                    <div class="w-12 h-12 rounded-full bg-green-100 flex items-center justify-center">
                        <i class="ri-medicine-bottle-line ri-lg text-green-500"></i>
                    </div>
                    <span class="text-xs mt-1 whitespace-nowrap overflow-hidden text-overflow-ellipsis">الصيدليات</span>
                </div>
                <div class="flex flex-col items-center min-w-[60px] cursor-pointer">
                    <div class="w-12 h-12 rounded-full bg-purple-100 flex items-center justify-center">
                        <i class="ri-home-gear-line ri-lg text-purple-500"></i>
                    </div>
                    <span class="text-xs mt-1 whitespace-nowrap overflow-hidden text-overflow-ellipsis">الخدمات</span>
                </div>
                <div class="flex flex-col items-center min-w-[60px] cursor-pointer">
                    <div class="w-12 h-12 rounded-full bg-yellow-100 flex items-center justify-center">
                        <i class="ri-newspaper-line ri-lg text-yellow-600"></i>
                    </div>
                    <span class="text-xs mt-1 whitespace-nowrap overflow-hidden text-overflow-ellipsis">الأخبار</span>
                </div>
                <div class="flex flex-col items-center min-w-[60px] cursor-pointer">
                    <div class="w-12 h-12 rounded-full bg-pink-100 flex items-center justify-center">
                        <i class="ri-calendar-event-line ri-lg text-pink-500"></i>
                    </div>
                    <span class="text-xs mt-1 whitespace-nowrap overflow-hidden text-overflow-ellipsis">الفعاليات</span>
                </div>
                <div class="flex flex-col items-center min-w-[60px] cursor-pointer">
                    <div class="w-12 h-12 rounded-full bg-indigo-100 flex items-center justify-center">
                        <i class="ri-price-tag-3-line ri-lg text-indigo-500"></i>
                    </div>
                    <span class="text-xs mt-1 whitespace-nowrap overflow-hidden text-overflow-ellipsis">العروض</span>
                </div>
            </div>
        </div>

        <!-- Banner Slider -->
        <div class="px-4 mt-4">
            <div class="banner-slider overflow-x-auto flex space-x-4 space-x-reverse py-2">
                <div class="min-w-[300px] h-[140px] rounded-lg overflow-hidden shadow-sm relative">
                    <img src="https://readdy.ai/api/search-image?query=Arabic%20city%20marketplace%20with%20colorful%20shops%20and%20people%2C%20vibrant%20colors%2C%20modern%20Middle%20Eastern%20architecture%2C%20daytime%20scene%2C%20bustling%20activity%2C%20no%20text%20overlay%2C%20photorealistic%20style&width=300&height=140&seq=1&orientation=landscape" class="w-full h-full object-cover" alt="عروض المحلات">
                    <div class="absolute bottom-0 left-0 right-0 bg-gradient-to-t from-black/70 to-transparent p-3">
                        <h3 class="text-white font-bold">عروض المحلات الجديدة</h3>
                        <p class="text-white text-xs">خصومات تصل إلى 50٪ في مركز المدينة</p>
                    </div>
                </div>
                <div class="min-w-[300px] h-[140px] rounded-lg overflow-hidden shadow-sm relative">
                    <img src="https://readdy.ai/api/search-image?query=Modern%20Arabic%20restaurant%20interior%20with%20traditional%20elements%2C%20warm%20lighting%2C%20elegant%20setting%2C%20people%20dining%2C%20photorealistic%20style&width=300&height=140&seq=2&orientation=landscape" class="w-full h-full object-cover" alt="مطاعم فارسكور">
                    <div class="absolute bottom-0 left-0 right-0 bg-gradient-to-t from-black/70 to-transparent p-3">
                        <h3 class="text-white font-bold">أفضل المطاعم في فارسكور</h3>
                        <p class="text-white text-xs">اكتشف تجارب طعام فريدة</p>
                    </div>
                </div>
            </div>
        </div>

        <!-- Main Services Grid -->
        <div class="px-4 mt-6">
            <h2 class="text-lg font-bold mb-3">الخدمات الرئيسية</h2>
            <div class="grid grid-cols-4 gap-3">
                <div class="flex flex-col items-center cursor-pointer">
                    <div class="w-14 h-14 rounded-lg bg-blue-50 flex items-center justify-center shadow-sm">
                        <img src="https://readdy.ai/api/search-image?query=icon%2C%203D%20cartoon%2C%20delivery%20scooter%2C%20the%20icon%20should%20take%20up%2070%25%20of%20the%20frame%2C%20vibrant%20colors%20with%20soft%20gradients%2C%20minimalist%20design%2C%20smooth%20rounded%20shapes%2C%20subtle%20shading%2C%20no%20outlines%2C%20centered%20composition%2C%20isolated%20on%20white%20background%2C%20playful%20and%20friendly%20aesthetic%2C%20isometric%20perspective%2C%20high%20detail%20quality%2C%20clean%20and%20modern%20look%2C%20single%20object%20focus&width=56&height=56&seq=3&orientation=squarish" class="w-full h-full object-contain rounded-lg" alt="توصيل">
                    </div>
                    <span class="text-xs mt-1 text-center whitespace-nowrap overflow-hidden text-overflow-ellipsis">توصيل</span>
                </div>
                <div class="flex flex-col items-center cursor-pointer">
                    <div class="w-14 h-14 rounded-lg bg-red-50 flex items-center justify-center shadow-sm">
                        <img src="https://readdy.ai/api/search-image?query=icon%2C%203D%20cartoon%2C%20discount%20tag%20with%20percentage%2C%20the%20icon%20should%20take%20up%2070%25%20of%20the%20frame%2C%20vibrant%20colors%20with%20soft%20gradients%2C%20minimalist%20design%2C%20smooth%20rounded%20shapes%2C%20subtle%20shading%2C%20no%20outlines%2C%20centered%20composition%2C%20isolated%20on%20white%20background%2C%20playful%20and%20friendly%20aesthetic%2C%20isometric%20perspective%2C%20high%20detail%20quality%2C%20clean%20and%20modern%20look%2C%20single%20object%20focus&width=56&height=56&seq=4&orientation=squarish" class="w-full h-full object-contain rounded-lg" alt="عروض">
                    </div>
                    <span class="text-xs mt-1 text-center whitespace-nowrap overflow-hidden text-overflow-ellipsis">عروض</span>
                </div>
                <div class="flex flex-col items-center cursor-pointer">
                    <div class="w-14 h-14 rounded-lg bg-green-50 flex items-center justify-center shadow-sm">
                        <img src="https://readdy.ai/api/search-image?query=icon%2C%203D%20cartoon%2C%20briefcase%20or%20job%20application%2C%20the%20icon%20should%20take%20up%2070%25%20of%20the%20frame%2C%20vibrant%20colors%20with%20soft%20gradients%2C%20minimalist%20design%2C%20smooth%20rounded%20shapes%2C%20subtle%20shading%2C%20no%20outlines%2C%20centered%20composition%2C%20isolated%20on%20white%20background%2C%20playful%20and%20friendly%20aesthetic%2C%20isometric%20perspective%2C%20high%20detail%20quality%2C%20clean%20and%20modern%20look%2C%20single%20object%20focus&width=56&height=56&seq=5&orientation=squarish" class="w-full h-full object-contain rounded-lg" alt="وظائف">
                    </div>
                    <span class="text-xs mt-1 text-center whitespace-nowrap overflow-hidden text-overflow-ellipsis">وظائف</span>
                </div>
                <div class="flex flex-col items-center cursor-pointer">
                    <div class="w-14 h-14 rounded-lg bg-purple-50 flex items-center justify-center shadow-sm">
                        <img src="https://readdy.ai/api/search-image?query=icon%2C%203D%20cartoon%2C%20house%20or%20real%20estate%20building%2C%20the%20icon%20should%20take%20up%2070%25%20of%20the%20frame%2C%20vibrant%20colors%20with%20soft%20gradients%2C%20minimalist%20design%2C%20smooth%20rounded%20shapes%2C%20subtle%20shading%2C%20no%20outlines%2C%20centered%20composition%2C%20isolated%20on%20white%20background%2C%20playful%20and%20friendly%20aesthetic%2C%20isometric%20perspective%2C%20high%20detail%20quality%2C%20clean%20and%20modern%20look%2C%20single%20object%20focus&width=56&height=56&seq=6&orientation=squarish" class="w-full h-full object-contain rounded-lg" alt="عقارات">
                    </div>
                    <span class="text-xs mt-1 text-center whitespace-nowrap overflow-hidden text-overflow-ellipsis">عقارات</span>
                </div>
                <div class="flex flex-col items-center cursor-pointer">
                    <div class="w-14 h-14 rounded-lg bg-yellow-50 flex items-center justify-center shadow-sm">
                        <img src="https://readdy.ai/api/search-image?query=icon%2C%203D%20cartoon%2C%20medical%20cross%20or%20healthcare%20symbol%2C%20the%20icon%20should%20take%20up%2070%25%20of%20the%20frame%2C%20vibrant%20colors%20with%20soft%20gradients%2C%20minimalist%20design%2C%20smooth%20rounded%20shapes%2C%20subtle%20shading%2C%20no%20outlines%2C%20centered%20composition%2C%20isolated%20on%20white%20background%2C%20playful%20and%20friendly%20aesthetic%2C%20isometric%20perspective%2C%20high%20detail%20quality%2C%20clean%20and%20modern%20look%2C%20single%20object%20focus&width=56&height=56&seq=7&orientation=squarish" class="w-full h-full object-contain rounded-lg" alt="صحة">
                    </div>
                    <span class="text-xs mt-1 text-center whitespace-nowrap overflow-hidden text-overflow-ellipsis">صحة</span>
                </div>
                <div class="flex flex-col items-center cursor-pointer">
                    <div class="w-14 h-14 rounded-lg bg-pink-50 flex items-center justify-center shadow-sm">
                        <img src="https://readdy.ai/api/search-image?query=icon%2C%203D%20cartoon%2C%20shopping%20cart%20or%20marketplace%2C%20the%20icon%20should%20take%20up%2070%25%20of%20the%20frame%2C%20vibrant%20colors%20with%20soft%20gradients%2C%20minimalist%20design%2C%20smooth%20rounded%20shapes%2C%20subtle%20shading%2C%20no%20outlines%2C%20centered%20composition%2C%20isolated%20on%20white%20background%2C%20playful%20and%20friendly%20aesthetic%2C%20isometric%20perspective%2C%20high%20detail%20quality%2C%20clean%20and%20modern%20look%2C%20single%20object%20focus&width=56&height=56&seq=8&orientation=squarish" class="w-full h-full object-contain rounded-lg" alt="سوق">
                    </div>
                    <span class="text-xs mt-1 text-center whitespace-nowrap overflow-hidden text-overflow-ellipsis">سوق</span>
                </div>
                <div class="flex flex-col items-center cursor-pointer">
                    <div class="w-14 h-14 rounded-lg bg-indigo-50 flex items-center justify-center shadow-sm">
                        <img src="https://readdy.ai/api/search-image?query=icon%2C%203D%20cartoon%2C%20graduation%20cap%20or%20education%20symbol%2C%20the%20icon%20should%20take%20up%2070%25%20of%20the%20frame%2C%20vibrant%20colors%20with%20soft%20gradients%2C%20minimalist%20design%2C%20smooth%20rounded%20shapes%2C%20subtle%20shading%2C%20no%20outlines%2C%20centered%20composition%2C%20isolated%20on%20white%20background%2C%20playful%20and%20friendly%20aesthetic%2C%20isometric%20perspective%2C%20high%20detail%20quality%2C%20clean%20and%20modern%20look%2C%20single%20object%20focus&width=56&height=56&seq=9&orientation=squarish" class="w-full h-full object-contain rounded-lg" alt="تعليم">
                    </div>
                    <span class="text-xs mt-1 text-center whitespace-nowrap overflow-hidden text-overflow-ellipsis">تعليم</span>
                </div>
                <div class="flex flex-col items-center cursor-pointer">
                    <div class="w-14 h-14 rounded-lg bg-cyan-50 flex items-center justify-center shadow-sm">
                        <img src="https://readdy.ai/api/search-image?query=icon%2C%203D%20cartoon%2C%20family%20or%20children%20icon%2C%20the%20icon%20should%20take%20up%2070%25%20of%20the%20frame%2C%20vibrant%20colors%20with%20soft%20gradients%2C%20minimalist%20design%2C%20smooth%20rounded%20shapes%2C%20subtle%20shading%2C%20no%20outlines%2C%20centered%20composition%2C%20isolated%20on%20white%20background%2C%20playful%20and%20friendly%20aesthetic%2C%20isometric%20perspective%2C%20high%20detail%20quality%2C%20clean%20and%20modern%20look%2C%20single%20object%20focus&width=56&height=56&seq=10&orientation=squarish" class="w-full h-full object-contain rounded-lg" alt="عائلة">
                    </div>
                    <span class="text-xs mt-1 text-center whitespace-nowrap overflow-hidden text-overflow-ellipsis">عائلة</span>
                </div>
            </div>
        </div>

        <!-- City Map -->
        <div class="px-4 mt-6">
            <div class="flex justify-between items-center mb-3">
                <h2 class="text-lg font-bold">خريطة فارسكور</h2>
                <a href="#" class="text-primary text-sm">عرض الكل</a>
            </div>
            <div class="h-[180px] rounded-lg overflow-hidden shadow-sm relative">
                <div class="absolute inset-0 bg-cover bg-center" style="background-image: url('https://public.readdy.ai/gen_page/map_placeholder_1280x720.png')"></div>
                <div class="absolute inset-0 flex items-center justify-center">
                    <button class="bg-primary text-white px-4 py-2 rounded-button shadow-md flex items-center space-x-2 space-x-reverse">
                        <i class="ri-map-pin-line"></i>
                        <span>استكشف المدينة</span>
                    </button>
                </div>
            </div>
        </div>

        <!-- Latest News -->
        <div class="px-4 mt-6">
            <div class="flex justify-between items-center mb-3">
                <h2 class="text-lg font-bold">أخبار فارسكور</h2>
                <a href="#" class="text-primary text-sm">المزيد</a>
            </div>
            <div class="news-slider flex overflow-x-auto space-x-4 space-x-reverse">
                <div class="min-w-[250px] bg-white rounded-lg shadow-sm overflow-hidden cursor-pointer">
                    <img src="https://readdy.ai/api/search-image?query=Middle%20Eastern%20city%20council%20meeting%2C%20officials%20discussing%20urban%20development%2C%20modern%20conference%20room%20with%20Arabic%20architectural%20elements%2C%20professional%20setting%2C%20photorealistic%20style&width=250&height=140&seq=11&orientation=landscape" class="w-full h-[140px] object-cover" alt="اجتماع المجلس البلدي">
                    <div class="p-3">
                        <div class="flex items-center text-xs text-gray-500 mb-1">
                            <i class="ri-calendar-line ri-sm ml-1"></i>
                            <span>2 يونيو 2025</span>
                        </div>
                        <h3 class="font-bold text-sm mb-1">المجلس البلدي يناقش مشاريع التطوير الجديدة</h3>
                        <p class="text-xs text-gray-600 line-clamp-2">ناقش المجلس البلدي في اجتماعه الأخير خطط تطوير البنية التحتية في المدينة وتحسين الخدمات العامة...</p>
                    </div>
                </div>
                <div class="min-w-[250px] bg-white rounded-lg shadow-sm overflow-hidden cursor-pointer">
                    <img src="https://readdy.ai/api/search-image?query=Middle%20Eastern%20cultural%20festival%2C%20outdoor%20celebration%20with%20colorful%20decorations%2C%20people%20in%20traditional%20attire%2C%20music%20performance%2C%20food%20stalls%2C%20photorealistic%20style&width=250&height=140&seq=12&orientation=landscape" class="w-full h-[140px] object-cover" alt="مهرجان ثقافي">
                    <div class="p-3">
                        <div class="flex items-center text-xs text-gray-500 mb-1">
                            <i class="ri-calendar-line ri-sm ml-1"></i>
                            <span>10 يونيو 2025</span>
                        </div>
                        <h3 class="font-bold text-sm mb-1">مهرجان فارسكور الثقافي يعود بفعاليات متنوعة</h3>
                        <p class="text-xs text-gray-600 line-clamp-2">يستعد سكان المدينة للمشاركة في مهرجان فارسكور الثقافي السنوي الذي سيقام في ساحة المدينة الرئيسية...</p>
                    </div>
                </div>
            </div>
        </div>

        <!-- Popular Services -->
        <div class="px-4 mt-6">
            <h2 class="text-lg font-bold mb-3">الخدمات الأكثر طلباً</h2>
            <div class="space-y-3">
                <div class="bg-white rounded-lg
