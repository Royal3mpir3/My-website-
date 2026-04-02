# My-website-<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="BOADU’S LAUNDRY SERVICES - Professional laundry & dry cleaning in Accra. Fast pickup & delivery from GC-088-6285 and across Greater Accra.">
    <title>BOADU’S LAUNDRY SERVICES | Accra</title>
    <script src="https://cdn.tailwindcss.com"></script>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.6.0/css/all.min.css">
    <style>
        @import url('https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&family=Playfair+Display:wght@700&display=swap');
        .tail-container * { font-family: 'Inter', system_ui, sans-serif; }
        .heading-font { font-family: 'Playfair Display', sans-serif; }
        .hero-bg {
            background: linear-gradient(rgba(0, 166, 81, 0.85), rgba(0, 166, 81, 0.85)), url('https://picsum.photos/id/1015/2000/1200') center/cover no-repeat;
        }
        .service-card:hover { transform: translateY(-8px); box-shadow: 0 25px 50px -12px rgb(0 166 81 / 0.15); }
        .whatsapp-float { animation: pulse 2s infinite; }
        @keyframes pulse { 0%, 100% { transform: scale(1); } 50% { transform: scale(1.1); } }
        .map-container { position: relative; overflow: hidden; border-radius: 24px; }
        .map-container img { width: 100%; height: auto; display: block; }
        .map-pin { position: absolute; color: #00a651; font-size: 28px; transform: translate(-50%, -100%); animation: drop 0.6s ease; }
    </style>
</head>
<body class="tail-container">

    <!-- NAVBAR (unchanged) -->
    <nav class="bg-white border-b sticky top-0 z-50 shadow-sm">
        <div class="max-w-7xl mx-auto px-6 py-4 flex items-center justify-between">
            <div class="flex items-center gap-x-3">
                <div class="w-10 h-10 bg-[#00a651] rounded-2xl flex items-center justify-center text-white text-2xl">
                    <i class="fa-solid fa-shirt"></i>
                </div>
                <div>
                    <h1 class="heading-font text-2xl font-bold tracking-tight text-gray-900">BOADU’S</h1>
                    <p class="text-xs text-[#00a651] -mt-1 font-semibold">LAUNDRY SERVICES</p>
                </div>
            </div>

            <div class="hidden md:flex items-center gap-x-8 text-sm font-medium">
                <a href="#services" class="hover:text-[#00a651]">Services</a>
                <a href="#pricing" class="hover:text-[#00a651]">Pricing</a>
                <a href="#map" class="hover:text-[#00a651]">Service Areas</a>
                <a href="#how" class="hover:text-[#00a651]">How It Works</a>
                <a href="#contact" class="hover:text-[#00a651]">Contact</a>
            </div>

            <div class="flex items-center gap-x-4">
                <a href="https://wa.me/233549591110" target="_blank" 
                   class="px-5 py-2.5 bg-[#00a651] text-white text-sm font-semibold rounded-2xl hover:bg-green-600 flex items-center gap-x-2">
                    <i class="fa-solid fa-credit-card"></i>
                    Pay with Paystack
                </a>
                <a href="https://wa.me/233549591110?text=Hi%20Boadi%2C%20I%20want%20to%20book%20laundry%20pickup%20today" 
                   target="_blank"
                   class="flex items-center justify-center w-10 h-10 bg-green-500 text-white rounded-2xl hover:scale-110 whatsapp-float">
                    <i class="fa-brands fa-whatsapp text-2xl"></i>
                </a>
            </div>
        </div>
    </nav>

    <!-- HERO (unchanged) -->
    <header class="hero-bg text-white py-24">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center max-w-3xl mx-auto">
                <h2 class="text-6xl md:text-7xl leading-none font-bold heading-font tracking-tighter mb-6">
                    Fresh clothes.<br>Fast delivery.<br><span class="text-[#00a651]">Zero stress.</span>
                </h2>
                <p class="text-xl mb-8">Professional laundry & dry cleaning in Accra.<br>Free pickup & delivery • Same-day service available.</p>
                
                <div class="flex flex-col sm:flex-row gap-4 justify-center">
                    <a href="https://wa.me/233549591110?text=Hi%20Boadi%21%20Please%20come%20and%20pick%20up%20my%20laundry" 
                       target="_blank"
                       class="bg-white text-[#00a651] hover:bg-green-50 font-semibold text-lg px-10 py-5 rounded-3xl flex items-center justify-center gap-x-3">
                        <i class="fa-solid fa-truck"></i>
                        BOOK PICKUP NOW
                    </a>
                    <a href="tel:0549591110" 
                       class="border-2 border-white hover:bg-white/10 font-semibold text-lg px-10 py-5 rounded-3xl flex items-center justify-center gap-x-3">
                        📞 054 959 1110
                    </a>
                </div>

                <div class="mt-8 text-sm flex justify-center items-center gap-x-6">
                    <div>📍 GC-088-6285, Accra</div>
                    <div>⭐ 4.9/5 (128 reviews)</div>
                </div>
            </div>
        </div>
    </header>

    <!-- SERVICES (unchanged) -->
    <section id="services" class="py-20 bg-gray-50">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-12">
                <h2 class="text-5xl heading-font font-bold">Our Services</h2>
            </div>
            <div class="grid md:grid-cols-3 gap-8">
                <div class="service-card bg-white rounded-3xl p-8">
                    <div class="text-5xl mb-6">🧼</div>
                    <h3 class="text-2xl font-semibold mb-3">Wash & Fold</h3>
                    <p class="text-gray-600 mb-6">Everyday laundry washed, dried and neatly folded.</p>
                    <p class="font-semibold text-[#00a651]">From GH₵28 per kg</p>
                </div>
                <div class="service-card bg-white rounded-3xl p-8 relative">
                    <div class="absolute top-6 right-6 bg-[#00a651] text-white text-xs px-4 py-1 rounded-full">POPULAR</div>
                    <div class="text-5xl mb-6">👔</div>
                    <h3 class="text-2xl font-semibold mb-3">Wash, Dry & Iron</h3>
                    <p class="text-gray-600 mb-6">Professional cleaning and perfect ironing.</p>
                    <p class="font-semibold text-[#00a651]">From GH₵45 per kg</p>
                </div>
                <div class="service-card bg-white rounded-3xl p-8">
                    <div class="text-5xl mb-6">🧥</div>
                    <h3 class="text-2xl font-semibold mb-3">Dry Cleaning</h3>
                    <p class="text-gray-600 mb-6">Suits, gowns, traditional wear & delicate items.</p>
                    <p class="font-semibold text-[#00a651]">From GH₵55 per item</p>
                </div>
            </div>
        </div>
    </section>

    <!-- NEW SERVICE AREA MAP SECTION -->
    <section id="map" class="py-20 bg-white">
        <div class="max-w-7xl mx-auto px-6">
            <div class="text-center mb-12">
                <span class="inline-block bg-green-100 text-[#00a651] px-6 py-2 rounded-3xl text-sm font-semibold mb-4">WE DELIVER ACROSS GREATER ACCRA</span>
                <h2 class="text-5xl heading-font font-bold">Our Service Areas</h2>
                <p class="mt-4 text-gray-600 max-w-md mx-auto">Free pickup & delivery from your location at <strong>GC-088-6285</strong> and the following areas:</p>
            </div>

            <div class="map-container shadow-xl border border-gray-100">
                <!-- Accra Map Image -->
                <img src="https://www.mapsofworld.com/ghana/accra.html" alt="Map of Accra Ghana" 
                     onerror="this.src='https://picsum.photos/id/1015/1200/700'; this.alt='Accra Service Area Map';" 
                     class="w-full">
                
                <!-- Overlay pins and labels (you can adjust positions if needed) -->
                <div style="top: 35%; left: 48%;" class="map-pin">📍</div>
                <div style="top: 42%; left: 52%;" class="map-pin text-lg">📍</div>
                <div style="top: 28%; left: 55%;" class="map-pin">📍</div>
                
                <!-- Legend / Areas -->
                <div class="absolute bottom-6 left-6 bg-white/95 backdrop-blur-md p-6 rounded-3xl shadow-lg max-w-xs text-sm">
                    <div class="font-semibold mb-3 flex items-center gap-x-2">
                        <span class="text-[#00a651]">●</span> We Serve These Areas
                    </div>
                    <div class="grid grid-cols-2 gap-x-8 gap-y-2 text-gray-700">
                        <div>East Legon</div>
                        <div>Cantonments</div>
                        <div>Airport Residential</div>
                        <div>Osu</div>
                        <div>Labone</div>
                        <div>Adabraka</div>
                        <div>Achimota</div>
                        <div>Spintex</div>
                        <div>Tema</div>
                        <div><strong>GC-088-6285</strong> (Your Area)</div>
                    </div>
                    <p class="text-xs text-gray-500 mt-4">Free pickup in most areas • Same-day available</p>
                </div>
            </div>

            <p class="text-center text-sm text-gray-500 mt-8">
                Not sure if we cover your exact location? WhatsApp us at <strong>054 959 1110</strong> or <strong>059 262 6580</strong> — we’ll confirm instantly!
            </p>
        </div>
    </section>

    <!-- PRICING, HOW IT WORKS, CONTACT & FOOTER remain the same as previous version -->
    <!-- (For brevity, they are unchanged – copy them from the previous code I sent you) -->

    <script>
        function bookNow() {
            window.location.href = "#contact";
        }

        function handleSubmit(e) {
            e.preventDefault();
            const name = document.getElementById('name').value || 'Customer';
            alert(`✅ Thank you, ${name}!\n\nYour pickup request has been received.\n\nWe will contact you shortly on 054 959 1110 or 059 262 6580.\n\nBOADU’S LAUNDRY SERVICES 🧼`);
        }

        console.log("%c✅ BOADU’S LAUNDRY WEBSITE UPDATED with Service Area Map", "color:#00a651; font-size:16px; font-weight:bold");
    </script>
</body>
</html>
