<!DOCTYPE html>
<html lang="ar" dir="rtl">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="الحقني - أول منصة جزائرية متخصصة في تقديم المساعدة السريعة للشاحنات والسيارات على الطريق">
    <meta name="keywords" content="مساعدة طريق, شاحنات, سيارات, ميكانيكي, ديبناج, وقود, الجزائر">
    <meta name="author" content="الحقني">
    <title>الحقني | منصة المساعدة على الطريق</title>
    
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    
    <!-- Google Fonts -->
    <link href="https://fonts.googleapis.com/css2?family=Cairo:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">
    
    <!-- AOS Animation Library -->
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">
    
    <style>
        /* ========================================
           style.css - الحقني (Al Haqni)
           Professional Website Styles - متكامل
           ======================================== */
        
        /* ---------- Reset & Base ---------- */
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: 'Cairo', 'Tajawal', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
            line-height: 1.5;
            direction: rtl;
        }

        /* ---------- Custom Scrollbar ---------- */
        ::-webkit-scrollbar {
            width: 8px;
        }

        ::-webkit-scrollbar-track {
            background: #e2e8f0;
            border-radius: 10px;
        }

        ::-webkit-scrollbar-thumb {
            background: #1e3a8a;
            border-radius: 10px;
        }

        ::-webkit-scrollbar-thumb:hover {
            background: #2563eb;
        }

        /* ---------- Typography ---------- */
        h1, h2, h3, h4, h5, h6 {
            font-weight: 700;
            line-height: 1.3;
        }

        ::selection {
            background-color: #1e3a8a;
            color: white;
        }

        /* ---------- Container ---------- */
        .container {
            max-width: 1280px;
            margin: 0 auto;
            padding: 0 24px;
        }

        @media (max-width: 640px) {
            .container {
                padding: 0 16px;
            }
        }

        /* ---------- Buttons ---------- */
        .btn-primary {
            background: linear-gradient(135deg, #1e3a8a, #3b82f6);
            color: white;
            padding: 14px 32px;
            border-radius: 50px;
            font-weight: 600;
            font-size: 16px;
            border: none;
            cursor: pointer;
            transition: all 0.3s ease;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            gap: 10px;
            box-shadow: 0 4px 14px 0 rgba(30, 58, 138, 0.3);
            text-decoration: none;
        }

        .btn-primary:hover {
            transform: translateY(-3px);
            box-shadow: 0 8px 20px 0 rgba(30, 58, 138, 0.4);
            background: linear-gradient(135deg, #172554, #2563eb);
        }

        .btn-outline {
            background: transparent;
            border: 2px solid #1e3a8a;
            color: #1e3a8a;
            padding: 12px 28px;
            border-radius: 50px;
            font-weight: 600;
            transition: 0.3s;
            cursor: pointer;
            display: inline-flex;
            align-items: center;
            gap: 8px;
        }

        .btn-outline:hover {
            background: #1e3a8a;
            color: white;
        }

        /* ---------- Navbar ---------- */
        .navbar {
            background: rgba(255, 255, 255, 0.95);
            backdrop-filter: blur(10px);
            box-shadow: 0 2px 20px rgba(0, 0, 0, 0.05);
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .nav-flex {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 16px 0;
        }

        .logo {
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .logo i {
            font-size: 32px;
            color: #1e3a8a;
        }

        .logo span {
            font-size: 26px;
            font-weight: 800;
            color: #0f172a;
        }

        .nav-links {
            display: flex;
            gap: 32px;
            align-items: center;
        }

        .nav-links a {
            text-decoration: none;
            color: #334155;
            font-weight: 500;
            transition: 0.2s;
        }

        .nav-links a:hover {
            color: #1e3a8a;
        }

        .mobile-menu {
            display: none;
            font-size: 28px;
            cursor: pointer;
            color: #1e3a8a;
        }

        @media (max-width: 992px) {
            .nav-links {
                display: none;
            }
            .mobile-menu {
                display: block;
            }
            .nav-links.active {
                display: flex;
                flex-direction: column;
                position: absolute;
                top: 80px;
                left: 0;
                right: 0;
                background: white;
                padding: 24px;
                box-shadow: 0 20px 25px -5px rgba(0, 0, 0, 0.1);
                gap: 20px;
                z-index: 100;
            }
        }

        /* ---------- Hero Section ---------- */
        .hero {
            background: linear-gradient(120deg, #eef2ff 0%, #ffffff 100%);
            padding: 80px 0;
            position: relative;
            overflow: hidden;
        }

        .hero-grid {
            display: grid;
            grid-template-columns: 1fr 1fr;
            gap: 48px;
            align-items: center;
        }

        .hero-badge {
            background: #dbeafe;
            color: #1e3a8a;
            padding: 6px 16px;
            border-radius: 50px;
            display: inline-block;
            font-weight: 600;
            margin-bottom: 24px;
        }

        .hero-title {
            font-size: 48px;
            font-weight: 800;
            line-height: 1.3;
            margin-bottom: 20px;
            color: #0f172a;
        }

        .hero-title span {
            color: #2563eb;
        }

        .hero-desc {
            color: #475569;
            font-size: 18px;
            line-height: 1.6;
            margin-bottom: 32px;
        }

        .hero-stats {
            display: flex;
            gap: 32px;
            margin-top: 40px;
        }

        .stat h3 {
            font-size: 28px;
            font-weight: 800;
            color: #1e3a8a;
        }

        .stat p {
            color: #64748b;
        }

        .hero-image img {
            width: 100%;
            border-radius: 40px;
            box-shadow: 0 25px 50px -12px rgba(0, 0, 0, 0.25);
        }

        @media (max-width: 992px) {
            .hero-grid {
                grid-template-columns: 1fr;
                text-align: center;
            }
            .hero-stats {
                justify-content: center;
            }
            .hero-title {
                font-size: 36px;
            }
        }

        @media (max-width: 640px) {
            .hero {
                padding: 50px 0;
            }
            .hero-title {
                font-size: 28px;
            }
            .hero-stats {
                gap: 20px;
            }
            .stat h3 {
                font-size: 22px;
            }
        }

        /* ---------- Section Styles ---------- */
        .section {
            padding: 80px 0;
        }

        .section-title {
            text-align: center;
            font-size: 36px;
            font-weight: 800;
            margin-bottom: 16px;
            position: relative;
        }

        .section-title:after {
            content: '';
            display: block;
            width: 80px;
            height: 4px;
            background: linear-gradient(90deg, #1e3a8a, #60a5fa);
            margin: 20px auto 0;
            border-radius: 4px;
        }

        .section-sub {
            text-align: center;
            color: #64748b;
            max-width: 600px;
            margin: 0 auto 48px;
            font-size: 18px;
        }

        @media (max-width: 768px) {
            .section {
                padding: 50px 0;
            }
            .section-title {
                font-size: 28px;
            }
        }

        /* ---------- Services Cards ---------- */
        .services-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 32px;
        }

        .service-card {
            background: white;
            border-radius: 28px;
            padding: 32px;
            text-align: center;
            transition: all 0.3s ease;
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.05);
            border: 1px solid #e2e8f0;
        }

        .service-card:hover {
            transform: translateY(-8px);
            box-shadow: 0 20px 30px -12px rgba(0, 0, 0, 0.15);
        }

        .service-icon {
            width: 80px;
            height: 80px;
            background: #e0e7ff;
            border-radius: 30px;
            display: flex;
            align-items: center;
            justify-content: center;
            margin: 0 auto 24px;
            transition: 0.3s;
        }

        .service-card:hover .service-icon {
            background: #1e3a8a;
        }

        .service-card:hover .service-icon i {
            color: white;
        }

        .service-icon i {
            font-size: 40px;
            color: #1e3a8a;
            transition: 0.3s;
        }

        .service-card h3 {
            font-size: 24px;
            margin-bottom: 12px;
        }

        .service-card p {
            color: #64748b;
            line-height: 1.5;
        }

        .service-btn {
            background: none;
            border: none;
            color: #1e3a8a;
            font-weight: 700;
            margin-top: 20px;
            cursor: pointer;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            transition: 0.2s;
        }

        .service-btn:hover {
            gap: 12px;
            color: #2563eb;
        }

        /* ---------- Features Grid ---------- */
        .features-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(300px, 1fr));
            gap: 32px;
        }

        .feature-item {
            display: flex;
            gap: 20px;
            align-items: flex-start;
            background: white;
            padding: 24px;
            border-radius: 24px;
            box-shadow: 0 5px 15px rgba(0, 0, 0, 0.05);
        }

        .feature-icon {
            background: #1e3a8a10;
            padding: 14px;
            border-radius: 20px;
            flex-shrink: 0;
        }

        .feature-icon i {
            font-size: 28px;
            color: #1e3a8a;
        }

        .feature-item h3 {
            font-size: 20px;
            margin-bottom: 8px;
        }

        .feature-item p {
            color: #64748b;
        }

        @media (max-width: 640px) {
            .feature-item {
                flex-direction: column;
                text-align: center;
                align-items: center;
            }
        }

        /* ---------- CTA Section ---------- */
        .cta {
            background: linear-gradient(110deg, #0f172a, #1e3a8a);
            border-radius: 48px;
            padding: 64px 48px;
            text-align: center;
            color: white;
        }

        .cta h2 {
            font-size: 32px;
            margin-bottom: 16px;
        }

        .cta p {
            opacity: 0.9;
            max-width: 500px;
            margin: 0 auto;
        }

        .cta .btn-primary {
            background: white;
            color: #1e3a8a;
            box-shadow: none;
            margin-top: 24px;
        }

        .cta .btn-primary:hover {
            transform: translateY(-3px);
            background: #f8fafc;
        }

        @media (max-width: 768px) {
            .cta {
                padding: 40px 24px;
                border-radius: 32px;
            }
            .cta h2 {
                font-size: 26px;
            }
        }

        /* ---------- Testimonials ---------- */
        .testimonials-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
            gap: 32px;
        }

        .testimonial-card {
            background: white;
            border-radius: 24px;
            padding: 28px;
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.05);
            border: 1px solid #e2e8f0;
        }

        .testimonial-card i {
            color: #fbbf24;
            font-size: 20px;
            margin-bottom: 16px;
        }

        .testimonial-card p {
            color: #475569;
            line-height: 1.6;
            margin-bottom: 20px;
        }

        .testimonial-author {
            display: flex;
            align-items: center;
            gap: 12px;
        }

        .testimonial-author img {
            width: 50px;
            height: 50px;
            border-radius: 50%;
            object-fit: cover;
        }

        .testimonial-author h4 {
            font-size: 16px;
            margin-bottom: 4px;
        }

        .testimonial-author span {
            font-size: 13px;
            color: #64748b;
        }

        /* ---------- Footer ---------- */
        .footer {
            background: #0f172a;
            color: #94a3b8;
            padding: 48px 0 24px;
            margin-top: 40px;
        }

        .footer-grid {
            display: grid;
            grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
            gap: 40px;
            margin-bottom: 40px;
        }

        .footer-col h4 {
            color: white;
            margin-bottom: 20px;
            font-size: 18px;
            position: relative;
            display: inline-block;
        }

        .footer-col h4:after {
            content: '';
            position: absolute;
            bottom: -8px;
            right: 0;
            width: 40px;
            height: 2px;
            background: #3b82f6;
        }

        .footer-col a {
            display: block;
            color: #94a3b8;
            text-decoration: none;
            margin-bottom: 12px;
            transition: 0.2s;
        }

        .footer-col a:hover {
            color: white;
            transform: translateX(-5px);
        }

        .footer-col p {
            line-height: 1.6;
        }

        .social-links {
            display: flex;
            gap: 15px;
            margin-top: 16px;
        }

        .social-links a {
            display: inline-block;
            margin-bottom: 0;
        }

        .copyright {
            text-align: center;
            padding-top: 24px;
            border-top: 1px solid #1e293b;
            font-size: 14px;
        }

        /* ---------- Modal Styles ---------- */
        .modal {
            display: none;
            position: fixed;
            top: 0;
            left: 0;
            width: 100%;
            height: 100%;
            background: rgba(0, 0, 0, 0.8);
            z-index: 1100;
            justify-content: center;
            align-items: center;
            backdrop-filter: blur(4px);
        }

        .modal-content {
            background: white;
            border-radius: 32px;
            max-width: 500px;
            width: 90%;
            padding: 32px;
            position: relative;
            animation: modalFadeIn 0.3s ease;
        }

        @keyframes modalFadeIn {
            from {
                opacity: 0;
                transform: scale(0.95);
            }
            to {
                opacity: 1;
                transform: scale(1);
            }
        }

        .modal-content input,
        .modal-content textarea,
        .modal-content select {
            width: 100%;
            padding: 14px;
            border: 1px solid #cbd5e1;
            border-radius: 16px;
            margin: 12px 0;
            font-family: inherit;
            font-size: 15px;
            transition: 0.2s;
            background: #f9fafb;
        }

        .modal-content input:focus,
        .modal-content textarea:focus,
        .modal-content select:focus {
            outline: none;
            border-color: #1e3a8a;
            box-shadow: 0 0 0 3px rgba(30, 58, 138, 0.1);
            background: white;
        }

        .modal-content textarea {
            resize: vertical;
            min-height: 80px;
        }

        .close-modal {
            position: absolute;
            top: 20px;
            left: 20px;
            font-size: 28px;
            cursor: pointer;
            color: #64748b;
            transition: 0.2s;
        }

        .close-modal:hover {
            color: #ef4444;
        }

        .location-btn {
            background: #e2e8f0;
            border: none;
            border-radius: 16px;
            padding: 0 16px;
            cursor: pointer;
            transition: 0.2s;
        }

        .location-btn:hover {
            background: #cbd5e1;
        }

        /* ---------- Toast Message ---------- */
        .toast-message {
            position: fixed;
            bottom: 30px;
            left: 20px;
            right: 20px;
            background: #1e3a8a;
            color: white;
            padding: 14px 20px;
            border-radius: 50px;
            text-align: center;
            z-index: 1200;
            display: none;
            animation: fadeInUp 0.3s ease;
            box-shadow: 0 10px 25px -5px rgba(0, 0, 0, 0.2);
        }

        @keyframes fadeInUp {
            from {
                opacity: 0;
                transform: translateY(20px);
            }
            to {
                opacity: 1;
                transform: translateY(0);
            }
        }

        /* ---------- Back to Top Button ---------- */
        .back-to-top {
            position: fixed;
            bottom: 30px;
            right: 30px;
            background: #1e3a8a;
            color: white;
            width: 50px;
            height: 50px;
            border-radius: 50%;
            display: flex;
            align-items: center;
            justify-content: center;
            cursor: pointer;
            opacity: 0;
            visibility: hidden;
            transition: all 0.3s;
            z-index: 100;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.15);
        }

        .back-to-top.show {
            opacity: 1;
            visibility: visible;
        }

        .back-to-top:hover {
            background: #2563eb;
            transform: translateY(-3px);
        }

        /* ---------- Loading Spinner ---------- */
        .loading-spinner {
            display: inline-block;
            width: 20px;
            height: 20px;
            border: 2px solid white;
            border-radius: 50%;
            border-top-color: transparent;
            animation: spin 0.6s linear infinite;
        }

        @keyframes spin {
            to { transform: rotate(360deg); }
        }

        /* ---------- Utility Classes ---------- */
        .text-center { text-align: center; }
        .text-right { text-align: right; }
    </style>
</head>
<body>

<!-- Toast Message -->
<div id="toastMsg" class="toast-message"></div>

<!-- Back to Top Button -->
<div class="back-to-top" id="backToTop">
    <i class="fas fa-arrow-up"></i>
</div>

<!-- Navbar -->
<nav class="navbar">
    <div class="container">
        <div class="nav-flex">
            <div class="logo">
                <i class="fas fa-truck-ramp-box"></i>
                <span>الحقني</span>
            </div>
            <div class="mobile-menu" id="mobileMenuBtn">
                <i class="fas fa-bars"></i>
            </div>
            <div class="nav-links" id="navLinks">
                <a href="#home">الرئيسية</a>
                <a href="#services">الخدمات</a>
                <a href="#about">عن التطبيق</a>
                <a href="#contact">تواصل</a>
                <button class="btn-outline" id="loginBtnNav" style="padding: 8px 20px;">دخول</button>
            </div>
        </div>
    </div>
</nav>

<!-- Hero Section -->
<section class="hero" id="home">
    <div class="container">
        <div class="hero-grid">
            <div data-aos="fade-up">
                <div class="hero-badge">✨ خدمة النجدة على الطريق</div>
                <h1 class="hero-title">مشكلتك <span>خليها علينا</span><br>نحن نأتيك أينما كنت</h1>
                <p class="hero-desc">أول منصة جزائرية متخصصة في تقديم المساعدة السريعة للشاحنات والسيارات. ميكانيكيون، وقود، ديبناج، وقطع غيار في أقرب وقت.</p>
                <button class="btn-primary" id="requestHelpBtn"><i class="fas fa-headset"></i> اطلب المساعدة الآن</button>
                <div class="hero-stats">
                    <div class="stat"><h3>+1500</h3><p>طلب منجز</p></div>
                    <div class="stat"><h3>+120</h3><p>فني محترف</p></div>
                    <div class="stat"><h3>24/7</h3><p>خدمة طوارئ</p></div>
                </div>
            </div>
            <div class="hero-image" data-aos="fade-left">
                <img src="https://images.unsplash.com/photo-1580273916550-e323be2ae537?w=600&h=500&fit=crop" alt="مساعدة شاحنة">
            </div>
        </div>
    </div>
</section>

<!-- Services Section -->
<section id="services" class="section">
    <div class="container">
        <h2 class="section-title" data-aos="fade-up">خدماتنا المتكاملة</h2>
        <p class="section-sub" data-aos="fade-up">فريق متخصص على مدار الساعة لتلبية احتياجاتك على الطريق</p>
        <div class="services-grid">
            <div class="service-card" data-aos="zoom-in">
                <div class="service-icon"><i class="fas fa-wrench"></i></div>
                <h3>ميكانيكيون متنقلون</h3>
                <p>فريق ميكانيكي متخصص يصل إلى موقعك لإصلاح سيارتك في الحال.</p>
                <button class="service-btn" data-service="mechanic">طلب ميكانيكي <i class="fas fa-arrow-left"></i></button>
            </div>
            <div class="service-card" data-aos="zoom-in" data-aos-delay="100">
                <div class="service-icon"><i class="fas fa-gas-pump"></i></div>
                <h3>توصيل الوقود</h3>
                <p>نفذ الوقود؟ نوصله لك أينما كنت في أسرع وقت.</p>
                <button class="service-btn" data-service="fuel">طلب وقود <i class="fas fa-arrow-left"></i></button>
            </div>
            <div class="service-card" data-aos="zoom-in" data-aos-delay="200">
                <div class="service-icon"><i class="fas fa-truck"></i></div>
                <h3>ديبناج (شاحنة رفع)</h3>
                <p>نقل سيارتك إلى أقرب مركز صيانة بواسطة شاحنة رفع حديثة.</p>
                <button class="service-btn" data-service="depannage">طلب ديبناج <i class="fas fa-arrow-left"></i></button>
            </div>
            <div class="service-card" data-aos="zoom-in" data-aos-delay="300">
                <div class="service-icon"><i class="fas fa-oil-can"></i></div>
                <h3>زيوت وقطع غيار</h3>
                <p>نوفر لك الزيوت الأصلية وقطع الغيار اللازمة أينما كنت.</p>
                <button class="service-btn" data-service="spare">طلب قطع غيار <i class="fas fa-arrow-left"></i></button>
            </div>
        </div>
    </div>
</section>

<!-- Features Section -->
<section id="about" class="section" style="background: #f1f5f9;">
    <div class="container">
        <h2 class="section-title" data-aos="fade-up">لماذا تختار الحقني؟</h2>
        <div class="features-grid">
            <div class="feature-item" data-aos="fade-right">
                <div class="feature-icon"><i class="fas fa-map-marker-alt"></i></div>
                <div><h3>تحديد الموقع بدقة</h3><p>نصل إليك عبر GPS بدقة متناهية لتقديم المساعدة السريعة.</p></div>
            </div>
            <div class="feature-item" data-aos="fade-right" data-aos-delay="100">
                <div class="feature-icon"><i class="fas fa-clock"></i></div>
                <div><h3>خدمة 24/7</h3><p>طوال أيام الأسبوع، فريق جاهز للاستجابة لنداءاتك.</p></div>
            </div>
            <div class="feature-item" data-aos="fade-right" data-aos-delay="200">
                <div class="feature-icon"><i class="fas fa-shield-alt"></i></div>
                <div><h3>فنيون معتمدون</h3><p>كل الميكانيكيين لديهم خبرة عالية وضمان الجودة.</p></div>
            </div>
            <div class="feature-item" data-aos="fade-right" data-aos-delay="300">
                <div class="feature-icon"><i class="fas fa-dollar-sign"></i></div>
                <div><h3>أسعار تنافسية</h3><p>خدماتنا بأسعار مناسبة وشفافة بدون مفاجآت.</p></div>
            </div>
        </div>
    </div>
</section>

<!-- Testimonials Section -->
<section class="section">
    <div class="container">
        <h2 class="section-title" data-aos="fade-up">ماذا يقول عملاؤنا؟</h2>
        <p class="section-sub" data-aos="fade-up">آراء حقيقية من مستخدمي منصة الحقني</p>
        <div class="testimonials-grid">
            <div class="testimonial-card" data-aos="fade-up">
                <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                <p>"خدمة رائعة وسريعة، الميكانيكي وصل في أقل من 20 دقيقة وحل المشكلة. شكراً للحقني"</p>
                <div class="testimonial-author">
                    <img src="https://randomuser.me/api/portraits/men/1.jpg" alt="عميل">
                    <div><h4>أحمد رضا</h4><span>سائق شاحنة</span></div>
                </div>
            </div>
            <div class="testimonial-card" data-aos="fade-up" data-aos-delay="100">
                <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                <p>"نصيحة لكل سائق، حمل تطبيق الحقني. أنقذوني مرة كنت عالق في منتصف الطريق السريع."</p>
                <div class="testimonial-author">
                    <img src="https://randomuser.me/api/portraits/women/1.jpg" alt="عميلة">
                    <div><h4>سارة بن عمر</h4><span>سائقة سيارة</span></div>
                </div>
            </div>
            <div class="testimonial-card" data-aos="fade-up" data-aos-delay="200">
                <i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i><i class="fas fa-star"></i>
                <p>"أفضل خدمة ديبناج في الجزائر، شاحنة الرفع وصلت بسرعة وتعامل محترف."</p>
                <div class="testimonial-author">
                    <img src="https://randomuser.me/api/portraits/men/2.jpg" alt="عميل">
                    <div><h4>محمد كمال</h4><span>صاحب شاحنة</span></div>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- CTA Section -->
<section class="section">
    <div class="container">
        <div class="cta" data-aos="flip-up">
            <h2>جاهز لطلب المساعدة؟</h2>
            <p>فريقنا ينتظر اتصالك، فقط اضغط على الزر وحدد الخدمة التي تحتاجها</p>
            <button class="btn-primary" id="ctaBtn" style="background:white; color:#1e3a8a;"><i class="fas fa-phone-alt"></i> اطلب النجدة الآن</button>
        </div>
    </div>
</section>

<!-- Footer -->
<footer class="footer" id="contact">
    <div class="container">
        <div class="footer-grid">
            <div class="footer-col">
                <h4>الحقني</h4>
                <p>منصة متخصصة في خدمات الطوارئ على الطريق للشاحنات والسيارات في الجزائر.</p>
                <div class="social-links">
                    <a href="#"><i class="fab fa-facebook fa-lg"></i></a>
                    <a href="#"><i class="fab fa-instagram fa-lg"></i></a>
                    <a href="#"><i class="fab fa-twitter fa-lg"></i></a>
                    <a href="#"><i class="fab fa-whatsapp fa-lg"></i></a>
                </div>
            </div>
            <div class="footer-col">
                <h4>روابط سريعة</h4>
                <a href="#home">الرئيسية</a>
                <a href="#services">الخدمات</a>
                <a href="#about">من نحن</a>
                <a href="#">الأسئلة الشائعة</a>
            </div>
            <div class="footer-col">
                <h4>تواصل معنا</h4>
                <a href="mailto:fullvixxx@gmail.com"><i class="fas fa-envelope"></i> fullvixxx@gmail.com</a>
                <a href="tel:+213555123456"><i class="fas fa-phone"></i> +213 555 123 456</a>
                <a href="#"><i class="fas fa-map-marker-alt"></i> الجزائر، الجزائر العاصمة</a>
            </div>
            <div class="footer-col">
                <h4>ساعات العمل</h4>
                <p>السبت - الخميس: 24 ساعة</p>
                <p>الجمعة: 24 ساعة</p>
                <p>خدمة طوارئ على مدار الساعة</p>
            </div>
        </div>
        <div class="copyright">
            <p>© 2025 الحقني - جميع الحقوق محفوظة | تصميم جزائري 100%</p>
        </div>
    </div>
</footer>

<!-- Modal طلب الخدمة -->
<div id="requestModal" class="modal">
    <div class="modal-content">
        <span class="close-modal">&times;</span>
        <h3 id="modalTitle" style="margin-bottom: 20px;">طلب خدمة</h3>
        <input type="text" id="fullName" placeholder="الاسم الكامل" required>
        <input type="tel" id="phoneNumber" placeholder="رقم الهاتف" required>
        <textarea id="problemDesc" rows="3" placeholder="وصف المشكلة بالتفصيل"></textarea>
        <div style="display: flex; gap: 8px;">
            <input type="text" id="locationInput" placeholder="موقعك (GPS أو عنوان)" style="flex:1">
            <button id="getLocationBtn" class="location-btn"><i class="fas fa-location-dot"></i></button>
        </div>
        <select id="serviceTypeSelect">
            <
