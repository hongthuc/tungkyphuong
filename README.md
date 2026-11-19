<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI TÙNG KỲ PHƯƠNG | tungkyphuong.com</title>
    <meta name="description" content="CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI TÙNG KỲ PHƯƠNG - Thiết kế kiến trúc, thi công xây dựng phần thô, hoàn thiện, nội thất uy tín tại Đà Nẵng. Hotline: 0905.262.564.">

    <!-- Open Graph / Thumbnail Logo khi chia sẻ link trang web -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://tungkyphuong.com/">
    <meta property="og:site_name" content="tungkyphuong.com">
    <meta property="og:title" content="CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI TÙNG KỲ PHƯƠNG">
    <meta property="og:description" content="Thiết kế kiến trúc - Thi công xây dựng trọn gói - Nội thất chuyên nghiệp tại Đà Nẵng. Địa chỉ: Thôn Hà Nha, Xã Hà Nha, TP Đà Nẵng. Hotline: 0905.262.564.">
    <meta property="og:image" content="https://tungkyphuong.com/assets/logo-tung-ky-phuong-thumbnail.png">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI TÙNG KỲ PHƯƠNG">
    <meta name="twitter:description" content="Thiết kế kiến trúc & Thi công xây dựng chuyên nghiệp tại Đà Nẵng - Hotline: 0905.262.564.">
    <meta name="twitter:image" content="https://tungkyphuong.com/assets/logo-tung-ky-phuong-thumbnail.png">

    <!-- Favicon đồng bộ Logo Tùng Kỳ Phương (SVG) -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230F2C59'/%3E%3Cpath d='M12 30L32 13L52 30V51H42V34H35V51H29V26H22V51H12V30Z' fill='%23D98A1E'/%3E%3Cpath d='M10 31L32 12L54 31' stroke='%23FFFFFF' stroke-width='3.5' fill='none' stroke-linecap='round' stroke-linejoin='round'/%3E%3C/svg%3E">

    <!-- Google Fonts: Inter -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'system-ui', '-apple-system', 'sans-serif'],
                    },
                    colors: {
                        brand: {
                            navy: '#0F2C59',
                            navyDark: '#0A1E3E',
                            navyLight: '#1B437E',
                            gold: '#D98A1E',
                            goldDark: '#B87212',
                            goldLight: '#F3B44C',
                            bg: '#F6F8FB'
                        }
                    }
                }
            }
        }
    </script>

    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <style>
        /* Reset chuẩn chống lệch phải, chống tràn viền trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }

        html, body {
            width: 100%;
            max-width: 100%;
            overflow-x: hidden;
            margin: 0;
            padding: 0;
            font-family: 'Inter', system-ui, -apple-system, sans-serif;
            color: #1E293B;
            background-color: #FFFFFF;
            scroll-behavior: smooth;
        }

        /* Khung nội dung chuẩn 95% màn hình trên máy tính và full gọn gàng trên điện thoại */
        .tkp-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }

        @media (min-width: 1024px) {
            .tkp-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Menu máy tính luôn gọn 1 hàng, không xuống dòng */
        .desktop-nav-link {
            white-space: nowrap;
            font-size: 12.5px;
            font-weight: 600;
            letter-spacing: 0.01em;
            color: #0F2C59;
            padding: 8px 9px;
            border-radius: 6px;
            transition: color 0.2s ease, background-color 0.2s ease;
            display: inline-flex;
            align-items: center;
            gap: 4px;
        }

        @media (min-width: 1280px) {
            .desktop-nav-link {
                font-size: 13px;
                padding: 8px 12px;
            }
        }

        .desktop-nav-link:hover,
        .desktop-nav-link.active {
            color: #D98A1E;
            background-color: #F8FAFC;
        }

        /* Dropdown menu chuẩn Flatsome */
        .nav-dropdown {
            position: relative;
        }

        .nav-dropdown-menu {
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 225px;
            background: #FFFFFF;
            border: 1px solid #E2E8F0;
            border-top: 2px solid #D98A1E;
            border-radius: 0 0 8px 8px;
            box-shadow: 0 12px 28px rgba(15, 44, 89, 0.12);
            opacity: 0;
            visibility: hidden;
            transform: translateY(6px);
            transition: all 0.2s ease;
            z-index: 60;
            padding: 6px 0;
        }

        .nav-dropdown:hover .nav-dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        .nav-dropdown-item {
            display: block;
            padding: 9px 16px;
            font-size: 13px;
            font-weight: 500;
            color: #334155;
            white-space: nowrap;
            transition: all 0.18s ease;
        }

        .nav-dropdown-item:hover {
            background-color: #F8FAFC;
            color: #D98A1E;
            padding-left: 20px;
        }

        /* Banner Slider 2 ảnh kích thước bằng nhau tuyệt đối, chữ nằm gọn xa viền */
        .hero-slider-wrapper {
            position: relative;
            width: 100%;
            overflow: hidden;
            background-color: #0A1E3E;
        }

        .hero-slides-track {
            display: flex;
            width: 200%;
            transition: transform 0.65s cubic-bezier(0.25, 0.8, 0.25, 1);
        }

        .hero-slide {
            position: relative;
            width: 50%;
            flex-shrink: 0;
            height: 360px;
            display: flex;
            align-items: center;
            overflow: hidden;
        }

        @media (min-width: 640px) {
            .hero-slide {
                height: 420px;
            }
        }

        @media (min-width: 1024px) {
            .hero-slide {
                height: 500px;
            }
        }

        @media (min-width: 1440px) {
            .hero-slide {
                height: 540px;
            }
        }

        .hero-slide-bg {
            position: absolute;
            inset: 0;
            width: 100%;
            height: 100%;
            object-fit: cover;
            object-position: center;
        }

        .hero-slide-overlay {
            position: absolute;
            inset: 0;
            background: linear-gradient(90deg, rgba(10, 30, 62, 0.90) 0%, rgba(15, 44, 89, 0.78) 55%, rgba(15, 44, 89, 0.42) 100%);
        }

        /* Vùng nội dung chữ trong banner cách xa viền ảnh trên cả mobile & desktop */
        .hero-content-box {
            position: relative;
            z-index: 10;
            width: 100%;
            padding: 24px 48px;
        }

        @media (min-width: 640px) {
            .hero-content-box {
                padding: 36px 72px;
            }
        }

        @media (min-width: 1024px) {
            .hero-content-box {
                width: 95%;
                max-width: 95%;
                margin: 0 auto;
                padding: 48px 80px;
            }
        }

        /* Tab danh mục gọn gàng, tên danh mục luôn viết liền 1 hàng không xuống dòng */
        .category-tab-btn {
            white-space: nowrap;
            flex-shrink: 0;
            font-size: 12px;
            font-weight: 600;
            padding: 7px 14px;
            border-radius: 9999px;
            border: 1px solid #CBD5E1;
            background-color: #FFFFFF;
            color: #0F2C59;
            cursor: pointer;
            transition: all 0.2s ease;
        }

        @media (min-width: 1024px) {
            .category-tab-btn {
                font-size: 12.5px;
                padding: 7px 16px;
            }
        }

        .category-tab-btn:hover {
            border-color: #D98A1E;
            color: #D98A1E;
        }

        .category-tab-btn.active {
            background-color: #0F2C59;
            border-color: #0F2C59;
            color: #FFFFFF;
            box-shadow: 0 4px 12px rgba(15, 44, 89, 0.18);
        }

        /* Ẩn thanh cuộn nhưng vẫn cho lướt ngang nhẹ trên điện thoại nếu cần */
        .no-scrollbar::-webkit-scrollbar {
            display: none;
        }
        .no-scrollbar {
            -ms-overflow-style: none;
            scrollbar-width: none;
        }

        /* Tiêu đề section kiểu Flatsome */
        .section-heading {
            position: relative;
            display: inline-block;
            padding-bottom: 10px;
        }

        .section-heading::after {
            content: '';
            position: absolute;
            bottom: 0;
            left: 50%;
            transform: translateX(-50%);
            width: 56px;
            height: 3px;
            background-color: #D98A1E;
            border-radius: 2px;
        }

        .section-heading-left::after {
            left: 0;
            transform: none;
        }

        /* Hiệu ứng ảnh card mượt mà */
        .card-image-wrap {
            overflow: hidden;
            position: relative;
            aspect-ratio: 4 / 3;
            background-color: #E2E8F0;
        }

        .card-image-wrap img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.45s ease;
        }

        .tkp-card:hover .card-image-wrap img {
            transform: scale(1.05);
        }

        /* Nút liên hệ nổi bật Zalo, Facebook, Hotline */
        .floating-contact-bar {
            position: fixed;
            right: 12px;
            bottom: 16px;
            z-index: 70;
            display: flex;
            flex-direction: column;
            align-items: flex-end;
            gap: 10px;
        }

        @media (min-width: 768px) {
            .floating-contact-bar {
                right: 20px;
                bottom: 24px;
                gap: 12px;
            }
        }

        .float-btn {
            display: flex;
            align-items: center;
            justify-content: center;
            width: 46px;
            height: 46px;
            border-radius: 9999px;
            color: #FFFFFF;
            box-shadow: 0 6px 18px rgba(0, 0, 0, 0.22);
            transition: transform 0.22s ease, box-shadow 0.22s ease;
            position: relative;
            text-decoration: none;
        }

        @media (min-width: 768px) {
            .float-btn {
                width: 50px;
                height: 50px;
            }
        }

        .float-btn:hover {
            transform: scale(1.08);
            box-shadow: 0 8px 22px rgba(0, 0, 0, 0.28);
        }

        .float-tooltip {
            display: none;
            position: absolute;
            right: 60px;
            background-color: #0F2C59;
            color: #FFFFFF;
            font-size: 12px;
            font-weight: 600;
            padding: 6px 12px;
            border-radius: 6px;
            white-space: nowrap;
            box-shadow: 0 4px 12px rgba(0, 0, 0, 0.16);
            pointer-events: none;
        }

        @media (min-width: 768px) {
            .float-btn:hover .float-tooltip {
                display: block;
            }
        }

        @keyframes pulseRing {
            0% {
                transform: scale(1);
                opacity: 0.7;
            }
            100% {
                transform: scale(1.48);
                opacity: 0;
            }
        }

        .hotline-pulse::before {
            content: '';
            position: absolute;
            inset: 0;
            border-radius: 9999px;
            background-color: #D98A1E;
            z-index: -1;
            animation: pulseRing 1.8s infinite;
        }
    </style>
</head>
<body class="bg-white text-slate-800 antialiased">

    <!-- =========================================================
         TOP BAR (Chuẩn Flatsome - Thông tin liên hệ gọn nhẹ)
    ========================================================== -->
    <div class="bg-brand-navy text-white text-xs border-b border-white/10">
        <div class="tkp-container py-2 flex flex-wrap items-center justify-between gap-2">
            <div class="flex flex-wrap items-center gap-x-4 gap-y-1">
                <a href="tel:0905262564" class="inline-flex items-center gap-1.5 hover:text-brand-goldLight transition-colors">
                    <i class="fa-solid fa-phone text-brand-gold text-[11px]"></i>
                    <span class="font-semibold">0905.262.564</span>
                </a>
                <span class="hidden sm:inline text-white/30">|</span>
                <span class="hidden sm:inline-flex items-center gap-1.5 text-slate-200">
                    <i class="fa-solid fa-location-dot text-brand-gold text-[11px]"></i>
                    Thôn Hà Nha, Xã Hà Nha, TP Đà Nẵng
                </span>
            </div>
            <div class="flex items-center gap-3">
                <span class="hidden md:inline text-slate-300">Website: <strong class="text-white">tungkyphuong.com</strong></span>
                <a href="https://www.facebook.com/profile.php?id=100057053437402" target="_blank" rel="noopener noreferrer" aria-label="Facebook Tùng Kỳ Phương" class="hover:text-brand-goldLight transition-colors">
                    <i class="fa-brands fa-facebook-f text-xs"></i>
                </a>
                <a href="https://zalo.me/0905262564" target="_blank" rel="noopener noreferrer" aria-label="Zalo Tùng Kỳ Phương" class="hover:text-brand-goldLight transition-colors font-bold text-[11px]">
                    Zalo
                </a>
            </div>
        </div>
    </div>

    <!-- =========================================================
         HEADER CHÍNH (Logo gọn nhỏ + Menu 1 hàng, KHÔNG có nút gọi ngay)
    ========================================================== -->
    <header id="site-header" class="sticky top-0 z-50 bg-white/95 backdrop-blur border-b border-slate-200 shadow-sm">
        <div class="tkp-container py-2.5 flex items-center justify-between gap-3">
            <!-- Logo công ty chuyên nghiệp - Thiết kế gọn nhỏ -->
            <a href="#trang-chu" class="flex items-center gap-2.5 shrink-0 group focus:outline-none">
                <svg class="w-9 h-9 sm:w-10 sm:h-10 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg" aria-label="Logo Tùng Kỳ Phương">
                    <rect width="64" height="64" rx="10" fill="#0F2C59"/>
                    <rect x="2" y="2" width="60" height="60" rx="8.5" stroke="#D98A1E" stroke-opacity="0.45" stroke-width="1.5"/>
                    <!-- Khối mái và trụ kiến trúc TKP -->
                    <path d="M12 31L32 14L52 31" stroke="#FFFFFF" stroke-width="3.2" stroke-linecap="round" stroke-linejoin="round"/>
                    <path d="M18 32H25V50H18V32Z" fill="#D98A1E"/>
                    <path d="M28.5 24H35.5V50H28.5V24Z" fill="#FFFFFF"/>
                    <path d="M39 32H46V50H39V32Z" fill="#D98A1E"/>
                    <rect x="14" y="48.5" width="36" height="3" rx="1.5" fill="#D98A1E"/>
                </svg>
                <div class="leading-tight">
                    <div class="text-[13.5px] sm:text-[15px] font-extrabold tracking-tight text-brand-navy group-hover:text-brand-gold transition-colors whitespace-nowrap">
                        TÙNG KỲ PHƯƠNG
                    </div>
                    <div class="text-[8.5px] sm:text-[9px] font-bold uppercase tracking-widest text-brand-gold whitespace-nowrap">
                        XÂY DỰNG &amp; THƯƠNG MẠI
                    </div>
                </div>
            </a>

            <!-- Navigation Menu Máy Tính (Viết liền 1 hàng, không xuống dòng, không nút gọi ngay) -->
            <nav class="hidden lg:flex items-center justify-end flex-nowrap gap-0.5 xl:gap-1" aria-label="Menu chính">
                <a href="#trang-chu" class="desktop-nav-link active">Trang chủ</a>
                <a href="#gioi-thieu" class="desktop-nav-link">Giới thiệu</a>

                <div class="nav-dropdown">
                    <a href="#linh-vuc" class="desktop-nav-link">
                        Lĩnh vực hoạt động
                        <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                    </a>
                    <div class="nav-dropdown-menu">
                        <a href="#linh-vuc" class="nav-dropdown-item">Thiết kế Kiến trúc – Nội thất</a>
                        <a href="#cong-trinh" onclick="filterConstruction('phan-tho')" class="nav-dropdown-item">Thi công phần thô</a>
                        <a href="#cong-trinh" onclick="filterConstruction('hoan-thien')" class="nav-dropdown-item">Thi công hoàn thiện</a>
                        <a href="#cong-trinh" onclick="filterConstruction('noi-that')" class="nav-dropdown-item">Thi công nội thất</a>
                    </div>
                </div>

                <div class="nav-dropdown">
                    <a href="#cong-trinh" class="desktop-nav-link">
                        Công trình thực tế
                        <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                    </a>
                    <div class="nav-dropdown-menu">
                        <a href="#cong-trinh" onclick="filterConstruction('khach-san-can-ho')" class="nav-dropdown-item">Khách sạn – Căn hộ – Phòng trọ</a>
                        <a href="#cong-trinh" onclick="filterConstruction('biet-thu')" class="nav-dropdown-item">Biệt thự</a>
                        <a href="#cong-trinh" onclick="filterConstruction('nha-pho')" class="nav-dropdown-item">Nhà phố</a>
                        <a href="#cong-trinh" onclick="filterConstruction('van-phong')" class="nav-dropdown-item">Văn phòng</a>
                    </div>
                </div>

                <a href="#du-an-da-nang" class="desktop-nav-link">Dự án Đà Nẵng</a>

                <div class="nav-dropdown">
                    <a href="#bao-gia" class="desktop-nav-link">
                        Báo giá
                        <i class="fa-solid fa-chevron-down text-[9px] opacity-70"></i>
                    </a>
                    <div class="nav-dropdown-menu">
                        <a href="#bao-gia" class="nav-dropdown-item">Báo giá thiết kế kiến trúc</a>
                        <a href="#bao-gia" class="nav-dropdown-item">Báo giá thi công phần thô</a>
                        <a href="#bao-gia" class="nav-dropdown-item">Báo giá thi công hoàn thiện</a>
                        <a href="#bao-gia" class="nav-dropdown-item">Báo giá thi công trọn gói</a>
                    </div>
                </div>

                <a href="#bai-viet" class="desktop-nav-link">Tin tức</a>
                <a href="#lien-he" class="desktop-nav-link">Liên hệ</a>
            </nav>

            <!-- Nút Menu Mobile (Hiển thị gọn gàng trên điện thoại & tablet) -->
            <button id="mobile-menu-btn" type="button" aria-label="Mở menu điều hướng" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-brand-navy hover:bg-slate-50 transition-colors">
                <i class="fa-solid fa-bars text-lg"></i>
            </button>
        </div>

        <!-- Drawer Menu Mobile -->
        <div id="mobile-menu" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg">
            <div class="tkp-container py-3 flex flex-col divide-y divide-slate-100 text-sm font-medium">
                <a href="#trang-chu" class="py-2.5 px-2 text-brand-navy hover:text-brand-gold mobile-nav-link">Trang chủ</a>
                <a href="#gioi-thieu" class="py-2.5 px-2 text-brand-navy hover:text-brand-gold mobile-nav-link">Giới thiệu</a>
                <a href="#linh-vuc" class="py-2.5 px-2 text-brand-navy hover:text-brand-gold mobile-nav-link">Lĩnh vực hoạt động</a>
                <a href="#cong-trinh" class="py-2.5 px-2 text-brand-navy hover:text-brand-gold mobile-nav-link">Công trình thực tế</a>
                <a href="#du-an-da-nang" class="py-2.5 px-2 text-brand-navy hover:text-brand-gold mobile-nav-link">Dự án tại Đà Nẵng</a>
                <a href="#bao-gia" class="py-2.5 px-2 text-brand-navy hover:text-brand-gold mobile-nav-link">Yêu cầu báo giá</a>
                <a href="#doi-tac" class="py-2.5 px-2 text-brand-navy hover:text-brand-gold mobile-nav-link">Đối tác</a>
                <a href="#bai-viet" class="py-2.5 px-2 text-brand-navy hover:text-brand-gold mobile-nav-link">Tin tức &amp; Bài viết</a>
                <a href="#lien-he" class="py-2.5 px-2 text-brand-navy hover:text-brand-gold mobile-nav-link">Liên hệ &amp; Bản đồ</a>
            </div>
        </div>
    </header>

    <!-- =========================================================
         BANNER SLIDER 2 ẢNH TỰ TRƯỢT CHUYÊN NGHIỆP
         - Kích thước 2 ảnh bằng nhau tuyệt đối
         - Hình ảnh & chữ nằm trọn trong banner, chữ cách xa viền
         - Không bị thiếu chữ trên cả điện thoại và máy tính
    ========================================================== -->
    <section id="trang-chu" class="hero-slider-wrapper" aria-label="Banner giới thiệu">
        <div id="hero-track" class="hero-slides-track">
            <!-- Banner 1 -->
            <div class="hero-slide">
                <img
                    src="https://drive.google.com/thumbnail?id=13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz&sz=w1600"
                    data-drive-id="13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz"
                    onerror="handleDriveImageError(this, 'Thi công xây dựng Tùng Kỳ Phương')"
                    alt="Thi công xây dựng trọn gói Tùng Kỳ Phương tại Đà Nẵng"
                    class="hero-slide-bg"
                >
                <div class="hero-slide-overlay"></div>
                <div class="hero-content-box">
                    <div class="max-w-2xl">
                        <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-brand-goldLight mb-2 sm:mb-3">
                            CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI TÙNG KỲ PHƯƠNG
                        </p>
                        <h1 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold text-white leading-snug mb-3 sm:mb-4">
                            Thiết Kế Kiến Trúc &amp; Thi Công Xây Dựng Trọn Gói Chuyên Nghiệp
                        </h1>
                        <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-5 sm:mb-6">
                            Giải pháp xây dựng chuẩn kỹ thuật, bền vững theo thời gian cho Nhà phố, Biệt thự, Khách sạn, Căn hộ và Văn phòng tại Đà Nẵng.
                        </p>
                        <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                            <a href="#bao-gia" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white font-semibold text-xs sm:text-sm transition-colors shadow-md">
                                Nhận Báo Giá Miễn Phí
                            </a>
                            <a href="#cong-trinh" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/40 font-semibold text-xs sm:text-sm transition-colors">
                                Xem Công Trình Thực Tế
                            </a>
                        </div>
                    </div>
                </div>
            </div>

            <!-- Banner 2 -->
            <div class="hero-slide">
                <img
                    src="https://drive.google.com/thumbnail?id=157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT&sz=w1600"
                    data-drive-id="157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT"
                    onerror="handleDriveImageError(this, 'Dự án xây dựng tại Đà Nẵng')"
                    alt="Dự án xây dựng thực tế tại Đà Nẵng - Tùng Kỳ Phương"
                    class="hero-slide-bg"
                >
                <div class="hero-slide-overlay"></div>
                <div class="hero-content-box">
                    <div class="max-w-2xl">
                        <p class="text-[11px] sm:text-xs md:text-sm font-semibold uppercase tracking-widest text-brand-goldLight mb-2 sm:mb-3">
                            AN TOÀN – CHẤT LƯỢNG – ĐÚNG TIẾN ĐỘ
                        </p>
                        <h2 class="text-xl sm:text-3xl md:text-4xl lg:text-[42px] font-extrabold text-white leading-snug mb-3 sm:mb-4">
                            Kiến Tạo Không Gian Sống Đẳng Cấp Tại Đà Nẵng
                        </h2>
                        <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed mb-5 sm:mb-6">
                            Đội ngũ kỹ sư tận tâm, quy trình giám sát chặt chẽ từng hạng mục phần thô đến hoàn thiện nội thất, tối ưu chi phí cho chủ đầu tư.
                        </p>
                        <div class="flex flex-wrap items-center gap-2.5 sm:gap-3">
                            <a href="#du-an-da-nang" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white font-semibold text-xs sm:text-sm transition-colors shadow-md">
                                Khám Phá Dự Án Đà Nẵng
                            </a>
                            <a href="tel:0905262564" class="inline-flex items-center justify-center px-4 sm:px-6 py-2.5 sm:py-3 rounded-lg bg-white/15 hover:bg-white/25 text-white border border-white/40 font-semibold text-xs sm:text-sm transition-colors">
                                Tư Vấn: 0905.262.564
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>

        <!-- Nút điều hướng slider trái/phải gọn ở sát mép ngoài, không che chữ -->
        <button id="prev-slide" type="button" aria-label="Banner trước" class="absolute left-2 sm:left-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition-colors">
            <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
        </button>
        <button id="next-slide" type="button" aria-label="Banner tiếp theo" class="absolute right-2 sm:right-4 top-1/2 -translate-y-1/2 z-20 w-8 h-8 sm:w-10 sm:h-10 rounded-full bg-black/35 hover:bg-brand-gold text-white flex items-center justify-center transition-colors">
            <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
        </button>

        <!-- Chấm chỉ báo slide -->
        <div class="absolute bottom-3.5 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2.5">
            <button type="button" onclick="goToSlide(0)" id="dot-0" aria-label="Slide 1" class="w-7 h-2 rounded-full bg-brand-gold transition-all"></button>
            <button type="button" onclick="goToSlide(1)" id="dot-1" aria-label="Slide 2" class="w-2.5 h-2 rounded-full bg-white/60 hover:bg-white transition-all"></button>
        </div>
    </section>

    <!-- =========================================================
         DỊCH VỤ TIÊU BIỂU (3 Cột Flatsome Icon Box giống web mẫu)
    ========================================================== -->
    <section id="linh-vuc" class="py-10 sm:py-14 bg-white">
        <div class="tkp-container">
            <div class="text-center mb-8 sm:mb-10">
                <h2 class="section-heading text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
                    Dịch Vụ Tiêu Biểu
                </h2>
            </div>

            <div class="grid grid-cols-1 md:grid-cols-3 gap-5 sm:gap-6">
                <!-- Dịch vụ 1 -->
                <div class="bg-brand-bg border border-slate-200 rounded-xl p-6 text-center hover:border-brand-gold hover:shadow-md transition-all">
                    <div class="w-14 h-14 mx-auto mb-4 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center text-2xl">
                        <i class="fa-solid fa-compass-drafting"></i>
                    </div>
                    <h3 class="text-base sm:text-lg font-bold text-brand-navy uppercase mb-2">
                        Thiết Kế Kiến Trúc
                    </h3>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        Tư vấn ý tưởng, lập hồ sơ bản vẽ kiến trúc 2D, phối cảnh 3D nhà phố, biệt thự, khách sạn, căn hộ và văn phòng tối ưu công năng sử dụng.
                    </p>
                </div>

                <!-- Dịch vụ 2 -->
                <div class="bg-brand-bg border border-slate-200 rounded-xl p-6 text-center hover:border-brand-gold hover:shadow-md transition-all">
                    <div class="w-14 h-14 mx-auto mb-4 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center text-2xl">
                        <i class="fa-solid fa-helmet-safety"></i>
                    </div>
                    <h3 class="text-base sm:text-lg font-bold text-brand-navy uppercase mb-2">
                        Thi Công Xây Dựng
                    </h3>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        Nhận thầu thi công phần thô, thi công hoàn thiện và xây nhà trọn gói chìa khóa trao tay. Cam kết vật tư chuẩn chất lượng và tiến độ.
                    </p>
                </div>

                <!-- Dịch vụ 3 -->
                <div class="bg-brand-bg border border-slate-200 rounded-xl p-6 text-center hover:border-brand-gold hover:shadow-md transition-all">
                    <div class="w-14 h-14 mx-auto mb-4 rounded-xl bg-brand-navy text-brand-gold flex items-center justify-center text-2xl">
                        <i class="fa-solid fa-couch"></i>
                    </div>
                    <h3 class="text-base sm:text-lg font-bold text-brand-navy uppercase mb-2">
                        Thi Công Nội Thất &amp; Thương Mại
                    </h3>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        Thiết kế, sản xuất và lắp đặt hoàn thiện nội thất đồng bộ cùng cung ứng vật liệu xây dựng chính hãng, giá cạnh tranh cho công trình.
                    </p>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         GIỚI THIỆU & THẾ MẠNH CỦA CHÚNG TÔI (Cấu trúc chuẩn web mẫu)
    ========================================================== -->
    <section id="gioi-thieu" class="py-10 sm:py-14 bg-brand-bg border-y border-slate-200">
        <div class="tkp-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-center mb-10 sm:mb-12">
                <div class="lg:col-span-6">
                    <p class="text-xs font-bold uppercase tracking-widest text-brand-gold mb-2">Về chúng tôi</p>
                    <h2 class="section-heading section-heading-left text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-navy mb-5">
                        CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI TÙNG KỲ PHƯƠNG
                    </h2>
                    <p class="text-sm sm:text-[15px] text-slate-700 leading-relaxed mb-4">
                        <strong>Tùng Kỳ Phương</strong> là đơn vị chuyên Thiết kế – Thi công xây dựng – Hoàn thiện nội thất và Thương mại vật tư cho các công trình Nhà phố, Biệt thự, Khách sạn, Căn hộ cho thuê và Văn phòng tại khu vực <strong>TP Đà Nẵng</strong> và miền Trung.
                    </p>
                    <p class="text-sm sm:text-[15px] text-slate-700 leading-relaxed mb-5">
                        Đặt chữ <strong>“TÂM”</strong> và uy tín nghề nghiệp lên hàng đầu, chúng tôi luôn đồng hành cùng chủ đầu tư từ khâu tư vấn giải pháp, lập dự toán minh bạch đến thi công chuẩn kỹ thuật nhằm mang lại kết quả <strong>“AN TOÀN – CHẤT LƯỢNG – TIẾN ĐỘ – HIỆU QUẢ”</strong> cho từng công trình.
                    </p>
                    <div class="grid grid-cols-3 gap-3 pt-2">
                        <div class="bg-white border border-slate-200 rounded-lg p-3.5 text-center">
                            <div class="text-xl sm:text-2xl font-extrabold text-brand-navy">100%</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-1">Thi công đúng kỹ thuật</div>
                        </div>
                        <div class="bg-white border border-slate-200 rounded-lg p-3.5 text-center">
                            <div class="text-xl sm:text-2xl font-extrabold text-brand-gold">24/7</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-1">Hỗ trợ tư vấn miễn phí</div>
                        </div>
                        <div class="bg-white border border-slate-200 rounded-lg p-3.5 text-center">
                            <div class="text-xl sm:text-2xl font-extrabold text-brand-navy">Bảo hành</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-1">Kết cấu &amp; hậu mãi dài lâu</div>
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-6">
                    <div class="rounded-xl overflow-hidden shadow-md border border-slate-200 bg-white">
                        <img
                            src="https://drive.google.com/thumbnail?id=1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR&sz=w1200"
                            data-drive-id="1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR"
                            onerror="handleDriveImageError(this, 'Tùng Kỳ Phương - Thi công xây dựng thực tế')"
                            alt="Hình ảnh thi công thực tế Công ty TNHH Xây dựng và Thương mại Tùng Kỳ Phương"
                            class="w-full h-64 sm:h-80 lg:h-96 object-cover"
                        >
                    </div>
                </div>
            </div>

            <!-- 6 Thế mạnh của chúng tôi -->
            <div class="text-center mb-7">
                <h3 class="section-heading text-lg sm:text-xl md:text-2xl font-extrabold text-brand-navy uppercase">
                    Thế Mạnh Của Chúng Tôi
                </h3>
            </div>
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
                <div class="bg-white border border-slate-200 rounded-xl p-5 flex items-start gap-4">
                    <div class="w-11 h-11 rounded-lg bg-brand-navy/10 text-brand-navy flex items-center justify-center shrink-0 text-lg">
                        <i class="fa-solid fa-users-gear"></i>
                    </div>
                    <div>
                        <h4 class="font-bold text-sm sm:text-[15px] text-brand-navy mb-1">Đội ngũ kỹ sư, kiến trúc sư chuyên nghiệp</h4>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Kiến trúc sư sáng tạo cùng đội ngũ kỹ sư hiện trường và thợ thi công tay nghề cao, giàu kinh nghiệm thực chiến.</p>
                    </div>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-5 flex items-start gap-4">
                    <div class="w-11 h-11 rounded-lg bg-brand-gold/15 text-brand-goldDark flex items-center justify-center shrink-0 text-lg">
                        <i class="fa-solid fa-layer-group"></i>
                    </div>
                    <div>
                        <h4 class="font-bold text-sm sm:text-[15px] text-brand-navy mb-1">Cập nhật xu hướng thiết kế hiện đại</h4>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Ứng dụng vật liệu mới, giải pháp kiến trúc thông thoáng, tối ưu ánh sáng và công năng theo chuẩn sống hiện đại.</p>
                    </div>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-5 flex items-start gap-4">
                    <div class="w-11 h-11 rounded-lg bg-brand-navy/10 text-brand-navy flex items-center justify-center shrink-0 text-lg">
                        <i class="fa-solid fa-clipboard-check"></i>
                    </div>
                    <div>
                        <h4 class="font-bold text-sm sm:text-[15px] text-brand-navy mb-1">Giám sát tiến độ chuẩn xác</h4>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Báo cáo tiến độ và hình ảnh thi công thường xuyên, đảm bảo bàn giao công trình đúng cam kết hợp đồng.</p>
                    </div>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-5 flex items-start gap-4">
                    <div class="w-11 h-11 rounded-lg bg-brand-gold/15 text-brand-goldDark flex items-center justify-center shrink-0 text-lg">
                        <i class="fa-solid fa-shield-halved"></i>
                    </div>
                    <div>
                        <h4 class="font-bold text-sm sm:text-[15px] text-brand-navy mb-1">Bảo hành công trình lâu dài</h4>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Chính sách bảo hành kết cấu và hoàn thiện rõ ràng, hỗ trợ bảo trì nhanh chóng giúp gia chủ luôn an tâm.</p>
                    </div>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-5 flex items-start gap-4">
                    <div class="w-11 h-11 rounded-lg bg-brand-navy/10 text-brand-navy flex items-center justify-center shrink-0 text-lg">
                        <i class="fa-solid fa-file-invoice-dollar"></i>
                    </div>
                    <div>
                        <h4 class="font-bold text-sm sm:text-[15px] text-brand-navy mb-1">Chi phí minh bạch, hợp lý</h4>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Bóc tách dự toán chi tiết từng hạng mục, không phát sinh chi phí bất hợp lý, tối ưu ngân sách cho chủ đầu tư.</p>
                    </div>
                </div>
                <div class="bg-white border border-slate-200 rounded-xl p-5 flex items-start gap-4">
                    <div class="w-11 h-11 rounded-lg bg-brand-gold/15 text-brand-goldDark flex items-center justify-center shrink-0 text-lg">
                        <i class="fa-solid fa-headset"></i>
                    </div>
                    <div>
                        <h4 class="font-bold text-sm sm:text-[15px] text-brand-navy mb-1">Hỗ trợ tư vấn miễn phí 24/7</h4>
                        <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">Sẵn sàng khảo sát thực tế, tư vấn phương án thiết kế và dự trù kinh phí hoàn toàn miễn phí qua Hotline &amp; Zalo.</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         CÔNG TRÌNH THỰC TẾ & DANH MỤC SẢN PHẨM (Lấy từ web mẫu + 9 ảnh Drive)
         - Danh mục gọn đẹp, tên danh mục 1 hàng không xuống dòng
         - 2 cột trên điện thoại, tên sản phẩm rõ đủ chữ không tràn viền
         - KHÔNG dùng nhãn dán (badge/sticker) trên trang chủ
    ========================================================== -->
    <section id="cong-trinh" class="py-10 sm:py-14 bg-white">
        <div class="tkp-container">
            <div class="text-center mb-6 sm:mb-8">
                <h2 class="section-heading text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
                    Công Trình Thực Tế &amp; Hạng Mục Thi Công
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                    Hình ảnh thi công thực tế tại công trường của Công ty TNHH Xây dựng và Thương mại Tùng Kỳ Phương theo từng hạng mục chuyên môn.
                </p>
            </div>

            <!-- Thanh Danh mục sản phẩm chuẩn web mẫu - gọn nhẹ, mỗi tên danh mục luôn nằm trên 1 hàng -->
            <div class="mb-7">
                <div id="construction-tabs" class="flex items-center justify-start lg:justify-center gap-2 overflow-x-auto lg:overflow-visible lg:flex-wrap no-scrollbar pb-2 lg:pb-0">
                    <button type="button" class="category-tab-btn active" data-filter="all" onclick="filterConstruction('all')">Tất cả</button>
                    <button type="button" class="category-tab-btn" data-filter="nha-pho" onclick="filterConstruction('nha-pho')">Nhà phố</button>
                    <button type="button" class="category-tab-btn" data-filter="biet-thu" onclick="filterConstruction('biet-thu')">Biệt thự</button>
                    <button type="button" class="category-tab-btn" data-filter="khach-san-can-ho" onclick="filterConstruction('khach-san-can-ho')">Khách sạn - Căn hộ</button>
                    <button type="button" class="category-tab-btn" data-filter="van-phong" onclick="filterConstruction('van-phong')">Văn phòng</button>
                    <button type="button" class="category-tab-btn" data-filter="phan-tho" onclick="filterConstruction('phan-tho')">Thi công phần thô</button>
                    <button type="button" class="category-tab-btn" data-filter="hoan-thien" onclick="filterConstruction('hoan-thien')">Thi công hoàn thiện</button>
                    <button type="button" class="category-tab-btn" data-filter="noi-that" onclick="filterConstruction('noi-that')">Thi công nội thất</button>
                </div>
            </div>

            <!-- Lưới sản phẩm / công trình thực tế: 2 cột trên điện thoại, 3 cột tablet, 3-4 cột máy tính -->
            <div id="construction-grid" class="grid grid-cols-2 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-3 gap-3 sm:gap-5">
                <!-- Được render tự động bằng JS từ 9 ảnh thực tế Google Drive -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         DỰ ÁN TẠI ĐÀ NẴNG (10 ảnh dự án thực tế Google Drive)
         - 2 cột trên điện thoại, 4-5 cột trên máy tính
         - Tên dự án đầy đủ, không cắt chữ, không tràn viền
    ========================================================== -->
    <section id="du-an-da-nang" class="py-10 sm:py-14 bg-brand-bg border-y border-slate-200">
        <div class="tkp-container">
            <div class="text-center mb-7 sm:mb-9">
                <h2 class="section-heading text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
                    Các Dự Án Tiêu Biểu Tại Đà Nẵng
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                    Tổng hợp các công trình nhà phố, biệt thự, khách sạn, căn hộ và công trình dân dụng do Tùng Kỳ Phương trực tiếp triển khai tại TP Đà Nẵng.
                </p>
            </div>

            <div id="danang-projects-grid" class="grid grid-cols-2 sm:grid-cols-2 md:grid-cols-3 lg:grid-cols-5 gap-3 sm:gap-4">
                <!-- Được render tự động từ 10 ảnh dự án Đà Nẵng Google Drive -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         DANH MỤC CÁC ĐỐI TÁC (Partners Strip chuyên nghiệp)
    ========================================================== -->
    <section id="doi-tac" class="py-10 sm:py-12 bg-white">
        <div class="tkp-container">
            <div class="text-center mb-7">
                <h2 class="section-heading text-xl sm:text-2xl font-extrabold text-brand-navy uppercase">
                    Đối Tác &amp; Thương Hiệu Vật Tư Đồng Hành
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-2.5">
                    Hợp tác trực tiếp cùng các nhà cung cấp thép, xi măng, sơn và thiết bị xây dựng uy tín hàng đầu Việt Nam.
                </p>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-5 gap-3 sm:gap-4">
                <!-- Đối tác 1 -->
                <div class="border border-slate-200 rounded-xl p-4 bg-slate-50/70 hover:bg-white hover:border-brand-gold hover:shadow-sm transition-all flex flex-col items-center justify-center text-center min-h-[84px]">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">THÉP HÒA PHÁT</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Kết cấu thép xây dựng</span>
                </div>
                <!-- Đối tác 2 -->
                <div class="border border-slate-200 rounded-xl p-4 bg-slate-50/70 hover:bg-white hover:border-brand-gold hover:shadow-sm transition-all flex flex-col items-center justify-center text-center min-h-[84px]">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">SƠN JOTUN</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Sơn nội ngoại thất</span>
                </div>
                <!-- Đối tác 3 -->
                <div class="border border-slate-200 rounded-xl p-4 bg-slate-50/70 hover:bg-white hover:border-brand-gold hover:shadow-sm transition-all flex flex-col items-center justify-center text-center min-h-[84px]">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">VIGLACERA</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Gạch ốp lát &amp; Sứ vệ sinh</span>
                </div>
                <!-- Đối tác 4 -->
                <div class="border border-slate-200 rounded-xl p-4 bg-slate-50/70 hover:bg-white hover:border-brand-gold hover:shadow-sm transition-all flex flex-col items-center justify-center text-center min-h-[84px]">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">SIKA VIỆT NAM</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Giải pháp chống thấm</span>
                </div>
                <!-- Đối tác 5 -->
                <div class="border border-slate-200 rounded-xl p-4 bg-slate-50/70 hover:bg-white hover:border-brand-gold hover:shadow-sm transition-all flex flex-col items-center justify-center text-center min-h-[84px]">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">CADIVI</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Dây cáp điện công trình</span>
                </div>
                <!-- Đối tác 6 -->
                <div class="border border-slate-200 rounded-xl p-4 bg-slate-50/70 hover:bg-white hover:border-brand-gold hover:shadow-sm transition-all flex flex-col items-center justify-center text-center min-h-[84px]">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">NHỰA BÌNH MINH</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Hệ thống cấp thoát nước</span>
                </div>
                <!-- Đối tác 7 -->
                <div class="border border-slate-200 rounded-xl p-4 bg-slate-50/70 hover:bg-white hover:border-brand-gold hover:shadow-sm transition-all flex flex-col items-center justify-center text-center min-h-[84px]">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">PANASONIC</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Thiết bị điện dân dụng</span>
                </div>
                <!-- Đối tác 8 -->
                <div class="border border-slate-200 rounded-xl p-4 bg-slate-50/70 hover:bg-white hover:border-brand-gold hover:shadow-sm transition-all flex flex-col items-center justify-center text-center min-h-[84px]">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">NHÔM XINGFA</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Hệ cửa nhôm kính cao cấp</span>
                </div>
                <!-- Đối tác 9 -->
                <div class="border border-slate-200 rounded-xl p-4 bg-slate-50/70 hover:bg-white hover:border-brand-gold hover:shadow-sm transition-all flex flex-col items-center justify-center text-center min-h-[84px]">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">AN CƯỜNG</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Vật liệu gỗ nội thất</span>
                </div>
                <!-- Đối tác 10 -->
                <div class="border border-slate-200 rounded-xl p-4 bg-slate-50/70 hover:bg-white hover:border-brand-gold hover:shadow-sm transition-all flex flex-col items-center justify-center text-center min-h-[84px]">
                    <span class="text-sm sm:text-base font-extrabold tracking-wide text-brand-navy">XI MĂNG SÔNG GIANH</span>
                    <span class="text-[11px] text-slate-500 mt-0.5">Vật liệu xây dựng miền Trung</span>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ (Chuẩn web mẫu)
    ========================================================== -->
    <section id="bao-gia" class="py-10 sm:py-14 bg-brand-navy text-white">
        <div class="tkp-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-8 items-start">
                <!-- Cột thông tin báo giá -->
                <div class="lg:col-span-5">
                    <p class="text-xs font-bold uppercase tracking-widest text-brand-goldLight mb-2">Miễn phí tư vấn &amp; dự toán</p>
                    <h2 class="text-xl sm:text-2xl md:text-3xl font-extrabold text-white mb-4 leading-snug">
                        Đăng Ký Yêu Cầu Tư Vấn &amp; Báo Giá Xây Dựng
                    </h2>
                    <p class="text-sm text-slate-200 leading-relaxed mb-6">
                        Quý khách đang chuẩn bị xây nhà phố, biệt thự, căn hộ cho thuê hay cải tạo công trình tại Đà Nẵng? Hãy để lại thông tin, đội ngũ kỹ sư <strong>Tùng Kỳ Phương</strong> sẽ liên hệ khảo sát và gửi bảng báo giá chi tiết trong thời gian sớm nhất.
                    </p>

                    <div class="space-y-3 text-sm">
                        <div class="flex items-start gap-3 bg-white/10 rounded-lg p-3.5">
                            <i class="fa-solid fa-check-circle text-brand-goldLight mt-0.5"></i>
                            <span>Báo giá thiết kế kiến trúc &amp; nội thất theo diện tích thực tế.</span>
                        </div>
                        <div class="flex items-start gap-3 bg-white/10 rounded-lg p-3.5">
                            <i class="fa-solid fa-check-circle text-brand-goldLight mt-0.5"></i>
                            <span>Báo giá thi công phần thô, hoàn thiện và xây nhà trọn gói rõ ràng từng chủng loại vật tư.</span>
                        </div>
                        <div class="flex items-start gap-3 bg-white/10 rounded-lg p-3.5">
                            <i class="fa-solid fa-phone-volume text-brand-goldLight mt-0.5"></i>
                            <span>Hotline hỗ trợ nhanh: <a href="tel:0905262564" class="font-bold text-brand-goldLight hover:underline">0905.262.564</a></span>
                        </div>
                    </div>
                </div>

                <!-- Cột Form Yêu Cầu & Báo Giá -->
                <div class="lg:col-span-7">
                    <div class="bg-white text-slate-800 rounded-xl p-5 sm:p-7 shadow-xl">
                        <h3 class="text-base sm:text-lg font-bold text-brand-navy mb-4 pb-2 border-b border-slate-200">
                            Điền thông tin nhận báo giá chi tiết
                        </h3>

                        <form id="quote-form" class="space-y-4" novalidate>
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label for="q-name" class="block text-xs font-semibold text-slate-700 mb-1.5">Họ và tên <span class="text-red-600">*</span></label>
                                    <input type="text" id="q-name" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none">
                                </div>
                                <div>
                                    <label for="q-phone" class="block text-xs font-semibold text-slate-700 mb-1.5">Số điện thoại <span class="text-red-600">*</span></label>
                                    <input type="tel" id="q-phone" required placeholder="Ví dụ: 0905 262 564" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label for="q-type" class="block text-xs font-semibold text-slate-700 mb-1.5">Loại công trình</label>
                                    <select id="q-type" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none">
                                        <option value="Nhà phố">Nhà phố</option>
                                        <option value="Biệt thự">Biệt thự</option>
                                        <option value="Khách sạn - Căn hộ cho thuê - Phòng trọ">Khách sạn – Căn hộ cho thuê – Phòng trọ</option>
                                        <option value="Văn phòng">Văn phòng</option>
                                        <option value="Thi công phần thô">Thi công phần thô</option>
                                        <option value="Thi công hoàn thiện & Nội thất">Thi công hoàn thiện &amp; Nội thất</option>
                                        <option value="Cải tạo sửa chữa">Cải tạo sửa chữa</option>
                                    </select>
                                </div>
                                <div>
                                    <label for="q-budget" class="block text-xs font-semibold text-slate-700 mb-1.5">Mức đầu tư dự kiến</label>
                                    <select id="q-budget" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none">
                                        <option value="Chưa xác định">Chưa xác định</option>
                                        <option value="Dưới 500 triệu">Dưới 500 triệu</option>
                                        <option value="500 triệu - 1 tỷ">500 triệu – 1 tỷ</option>
                                        <option value="1 tỷ - 2 tỷ">1 tỷ – 2 tỷ</option>
                                        <option value="2 tỷ - 3 tỷ">2 tỷ – 3 tỷ</option>
                                        <option value="Trên 3 tỷ">Trên 3 tỷ</option>
                                    </select>
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-4">
                                <div>
                                    <label for="q-email" class="block text-xs font-semibold text-slate-700 mb-1.5">Email (không bắt buộc)</label>
                                    <input type="email" id="q-email" placeholder="email@domain.com" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none">
                                </div>
                                <div>
                                    <label for="q-area" class="block text-xs font-semibold text-slate-700 mb-1.5">Địa điểm &amp; Diện tích dự kiến</label>
                                    <input type="text" id="q-area" placeholder="VD: Đà Nẵng, 5x20m, 3 tầng" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none">
                                </div>
                            </div>

                            <div>
                                <label for="q-note" class="block text-xs font-semibold text-slate-700 mb-1.5">Nội dung yêu cầu chi tiết</label>
                                <textarea id="q-note" rows="3" placeholder="Mô tả nhu cầu thiết kế, thi công phần thô, hoàn thiện hoặc hạng mục cần báo giá..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-brand-gold focus:ring-2 focus:ring-brand-gold/20 outline-none"></textarea>
                            </div>

                            <!-- Thông báo phản hồi Form (Không dùng alert) -->
                            <div id="quote-feedback" class="hidden rounded-lg p-3.5 text-sm font-medium"></div>

                            <button type="submit" class="w-full sm:w-auto px-7 py-3 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white font-bold text-sm transition-colors shadow-md">
                                Gửi Yêu Cầu Báo Giá Ngay
                            </button>
                        </form>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (Tin tức & Kinh nghiệm xây dựng)
    ========================================================== -->
    <section id="bai-viet" class="py-10 sm:py-14 bg-white">
        <div class="tkp-container">
            <div class="text-center mb-7 sm:mb-9">
                <h2 class="section-heading text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
                    Tin Tức &amp; Kinh Nghiệm Xây Dựng
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3 max-w-2xl mx-auto">
                    Chia sẻ kiến thức kỹ thuật thi công, kinh nghiệm dự toán và xu hướng thiết kế kiến trúc hữu ích cho chủ đầu tư.
                </p>
            </div>

            <div id="articles-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-5">
                <!-- Render tự động danh sách bài viết bằng JS -->
            </div>
        </div>
    </section>

    <!-- =========================================================
         GOOGLE MAP & FACEBOOK FANPAGE TRANG CHỦ
    ========================================================== -->
    <section id="lien-he" class="py-10 sm:py-14 bg-brand-bg border-t border-slate-200">
        <div class="tkp-container">
            <div class="text-center mb-8">
                <h2 class="section-heading text-xl sm:text-2xl md:text-3xl font-extrabold text-brand-navy uppercase">
                    Bản Đồ Chỉ Đường &amp; Kết Nối Facebook
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-3">
                    Trụ sở: Thôn Hà Nha, Xã Hà Nha, TP Đà Nẵng — Hotline: 0905.262.564
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-stretch">
                <!-- Khung Google Maps nhúng trực tiếp ra trang chủ -->
                <div class="lg:col-span-7 bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm flex flex-col">
                    <div class="px-5 py-3.5 border-b border-slate-200 flex items-center justify-between gap-2 bg-slate-50">
                        <div class="flex items-center gap-2 text-brand-navy font-bold text-sm">
                            <i class="fa-solid fa-map-location-dot text-brand-gold"></i>
                            <span>Vị trí Google Maps – Tùng Kỳ Phương</span>
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=Thôn+Hà+Nha,+Xã+Hà+Nha,+Đà+Nẵng" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-brand-goldDark hover:underline whitespace-nowrap">
                            Mở bản đồ lớn <i class="fa-solid fa-arrow-up-right-from-square ml-0.5 text-[10px]"></i>
                        </a>
                    </div>
                    <div class="w-full flex-1 min-h-[320px] sm:min-h-[360px] bg-slate-100">
                        <iframe
                            title="Bản đồ Công ty TNHH Xây dựng và Thương mại Tùng Kỳ Phương - Thôn Hà Nha, Xã Hà Nha, TP Đà Nẵng"
                            src="https://maps.google.com/maps?q=Th%C3%B4n%20H%C3%A0%20Nha,%20X%C3%A3%20H%C3%A0%20Nha,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=14&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full min-h-[320px] sm:min-h-[360px] border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade"
                            allowfullscreen>
                        </iframe>
                    </div>
                </div>

                <!-- Khung Facebook trang chủ dẫn trực tiếp đến profile Facebook của công ty -->
                <div class="lg:col-span-5 bg-white border border-slate-200 rounded-xl overflow-hidden shadow-sm flex flex-col">
                    <div class="px-5 py-3.5 border-b border-slate-200 flex items-center justify-between gap-2 bg-slate-50">
                        <div class="flex items-center gap-2 text-brand-navy font-bold text-sm">
                            <i class="fa-brands fa-facebook text-[#1877F2] text-base"></i>
                            <span>Facebook Chính Thức</span>
                        </div>
                        <a href="https://www.facebook.com/profile.php?id=100057053437402" target="_blank" rel="noopener noreferrer" class="text-xs font-semibold text-[#1877F2] hover:underline whitespace-nowrap">
                            Xem trang <i class="fa-solid fa-arrow-up-right-from-square ml-0.5 text-[10px]"></i>
                        </a>
                    </div>

                    <div class="p-5 flex-1 flex flex-col justify-between gap-4">
                        <!-- Thẻ giao diện Facebook trực quan + ổn định trên mọi thiết bị -->
                        <div class="rounded-xl border border-slate-200 overflow-hidden bg-slate-50">
                            <div class="relative h-32 sm:h-36 bg-brand-navy">
                                <img
                                    src="https://drive.google.com/thumbnail?id=1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv&sz=w1000"
                                    data-drive-id="1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv"
                                    onerror="handleDriveImageError(this, 'Facebook Tùng Kỳ Phương')"
                                    alt="Ảnh bìa Facebook Tùng Kỳ Phương"
                                    class="w-full h-full object-cover opacity-80"
                                >
                                <div class="absolute inset-0 bg-gradient-to-t from-brand-navy/85 via-brand-navy/35 to-transparent"></div>
                                <div class="absolute bottom-3 left-3.5 right-3.5 flex items-center gap-3">
                                    <div class="w-12 h-12 rounded-lg bg-brand-navy border-2 border-white shadow flex items-center justify-center shrink-0">
                                        <svg class="w-9 h-9" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                                            <path d="M12 31L32 14L52 31" stroke="#FFFFFF" stroke-width="3.5" stroke-linecap="round" stroke-linejoin="round"/>
                                            <path d="M18 32H25V50H18V32Z" fill="#D98A1E"/>
                                            <path d="M28.5 24H35.5V50H28.5V24Z" fill="#FFFFFF"/>
                                            <path d="M39 32H46V50H39V32Z" fill="#D98A1E"/>
                                        </svg>
                                    </div>
                                    <div class="min-w-0">
                                        <h3 class="text-white font-bold text-sm leading-snug break-words">
                                            Xây Dựng &amp; Thương Mại Tùng Kỳ Phương
                                        </h3>
                                        <p class="text-[11px] text-slate-200">Thiết kế &amp; Thi công xây dựng tại Đà Nẵng</p>
                                    </div>
                                </div>
                            </div>

                            <div class="p-4 space-y-3 bg-white">
                                <p class="text-xs sm:text-sm text-slate-600 leading-relaxed">
                                    Theo dõi trang Facebook chính thức của <strong>Tùng Kỳ Phương</strong> để cập nhật hình ảnh thi công thực tế hàng ngày, tiến độ công trình tại Đà Nẵng và các mẫu nhà đẹp mới nhất.
                                </p>
                                <div class="flex flex-wrap gap-2.5 pt-1">
                                    <a href="https://www.facebook.com/profile.php?id=100057053437402" target="_blank" rel="noopener noreferrer" class="flex-1 inline-flex items-center justify-center gap-2 px-4 py-2.5 rounded-lg bg-[#1877F2] hover:bg-[#1464CC] text-white font-semibold text-xs sm:text-sm transition-colors">
                                        <i class="fa-brands fa-facebook-f"></i>
                                        <span>Theo Dõi Facebook</span>
                                    </a>
                                    <a href="https://zalo.me/0905262564" target="_blank" rel="noopener noreferrer" class="inline-flex items-center justify-center gap-1.5 px-4 py-2.5 rounded-lg bg-brand-navy hover:bg-brand-navyDark text-white font-semibold text-xs sm:text-sm transition-colors">
                                        <i class="fa-solid fa-comment-dots"></i>
                                        <span>Nhắn Zalo</span>
                                    </a>
                                </div>
                            </div>
                        </div>

                        <!-- Thông tin liên hệ bổ sung -->
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3 text-xs text-slate-700">
                            <div class="p-3 rounded-lg bg-slate-50 border border-slate-200">
                                <div class="font-bold text-brand-navy mb-1"><i class="fa-solid fa-clock text-brand-gold mr-1.5"></i>Giờ làm việc</div>
                                <div>Thứ 2 – Thứ 7: 07:30 – 17:30</div>
                                <div>Tư vấn Hotline/Zalo: 24/7</div>
                            </div>
                            <div class="p-3 rounded-lg bg-slate-50 border border-slate-200">
                                <div class="font-bold text-brand-navy mb-1"><i class="fa-solid fa-building text-brand-gold mr-1.5"></i>Mã số thuế</div>
                                <div>MST: 4001315835</div>
                                <div>Website: tungkyphuong.com</div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================
         FOOTER CHUẨN FLATSOME
    ========================================================== -->
    <footer class="bg-brand-navyDark text-slate-300 pt-12 pb-6">
        <div class="tkp-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-12 gap-8 pb-9 border-b border-white/10">
                <!-- Cột 1: Thông tin doanh nghiệp -->
                <div class="lg:col-span-5">
                    <div class="flex items-center gap-2.5 mb-4">
                        <svg class="w-9 h-9 shrink-0" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                            <rect width="64" height="64" rx="10" fill="#0F2C59"/>
                            <rect x="2" y="2" width="60" height="60" rx="8.5" stroke="#D98A1E" stroke-width="1.8"/>
                            <path d="M12 31L32 14L52 31" stroke="#FFFFFF" stroke-width="3.2" stroke-linecap="round" stroke-linejoin="round"/>
                            <path d="M18 32H25V50H18V32Z" fill="#D98A1E"/>
                            <path d="M28.5 24H35.5V50H28.5V24Z" fill="#FFFFFF"/>
                            <path d="M39 32H46V50H39V32Z" fill="#D98A1E"/>
                            <rect x="14" y="48.5" width="36" height="3" rx="1.5" fill="#D98A1E"/>
                        </svg>
                        <div class="leading-tight">
                            <div class="text-sm sm:text-base font-extrabold text-white">CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI TÙNG KỲ PHƯƠNG</div>
                            <div class="text-[10px] font-semibold uppercase tracking-wider text-brand-goldLight">tungkyphuong.com</div>
                        </div>
                    </div>
                    <ul class="space-y-2.5 text-sm">
                        <li class="flex items-start gap-2.5">
                            <i class="fa-solid fa-location-dot text-brand-gold mt-1"></i>
                            <span>Trụ sở: Thôn Hà Nha, Xã Hà Nha, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone text-brand-gold"></i>
                            <span>Hotline / Zalo: <a href="tel:0905262564" class="text-white font-semibold hover:text-brand-goldLight">0905.262.564</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-globe text-brand-gold"></i>
                            <span>Website: <a href="https://tungkyphuong.com" class="text-white hover:text-brand-goldLight">tungkyphuong.com</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-brands fa-facebook text-brand-gold"></i>
                            <span>Facebook: <a href="https://www.facebook.com/profile.php?id=100057053437402" target="_blank" rel="noopener noreferrer" class="text-white hover:text-brand-goldLight">Xây Dựng Tùng Kỳ Phương</a></span>
                        </li>
                        <li class="flex items-center gap-2.5">
                            <i class="fa-solid fa-file-contract text-brand-gold"></i>
                            <span>Mã số thuế: 4001315835</span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Lĩnh vực hoạt động -->
                <div class="lg:col-span-3">
                    <h4 class="text-white font-bold text-sm uppercase tracking-wider mb-4 pb-2 border-b border-brand-gold/50 inline-block">
                        Lĩnh Vực Hoạt Động
                    </h4>
                    <ul class="space-y-2 text-sm">
                        <li><a href="#linh-vuc" class="hover:text-brand-goldLight transition-colors">Thiết kế kiến trúc – nội thất</a></li>
                        <li><a href="#cong-trinh" onclick="filterConstruction('phan-tho')" class="hover:text-brand-goldLight transition-colors">Thi công phần thô</a></li>
                        <li><a href="#cong-trinh" onclick="filterConstruction('hoan-thien')" class="hover:text-brand-goldLight transition-colors">Thi công hoàn thiện</a></li>
                        <li><a href="#cong-trinh" onclick="filterConstruction('noi-that')" class="hover:text-brand-goldLight transition-colors">Thi công nội thất trọn gói</a></li>
                        <li><a href="#bao-gia" class="hover:text-brand-goldLight transition-colors">Báo giá xây dựng trọn gói</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục công trình -->
                <div class="lg:col-span-4">
                    <h4 class="text-white font-bold text-sm uppercase tracking-wider mb-4 pb-2 border-b border-brand-gold/50 inline-block">
                        Danh Mục Công Trình
                    </h4>
                    <ul class="space-y-2 text-sm">
                        <li><a href="#cong-trinh" onclick="filterConstruction('nha-pho')" class="hover:text-brand-goldLight transition-colors">Thi công Nhà phố hiện đại</a></li>
                        <li><a href="#cong-trinh" onclick="filterConstruction('biet-thu')" class="hover:text-brand-goldLight transition-colors">Thi công Biệt thự cao cấp</a></li>
                        <li><a href="#cong-trinh" onclick="filterConstruction('khach-san-can-ho')" class="hover:text-brand-goldLight transition-colors">Khách sạn – Căn hộ – Phòng trọ</a></li>
                        <li><a href="#cong-trinh" onclick="filterConstruction('van-phong')" class="hover:text-brand-goldLight transition-colors">Thiết kế &amp; Thi công Văn phòng</a></li>
                        <li><a href="#du-an-da-nang" class="hover:text-brand-goldLight transition-colors">Dự án tiêu biểu tại Đà Nẵng</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 text-center text-xs text-slate-400">
                Copyright 2026 © <strong class="text-white">CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI TÙNG KỲ PHƯƠNG</strong> — tungkyphuong.com
            </div>
        </div>
    </footer>

    <!-- =========================================================
         CÁC NÚT LIÊN HỆ NỔI BẬT: HOTLINE, ZALO, FACEBOOK
         Tương thích hoàn hảo trên máy tính & điện thoại
    ========================================================== -->
    <div class="floating-contact-bar" aria-label="Liên hệ nhanh">
        <!-- Nút Lên đầu trang -->
        <button id="back-to-top" type="button" onclick="window.scrollTo({top: 0, behavior: 'smooth'})" aria-label="Lên đầu trang" class="hidden float-btn bg-brand-navy/90 hover:bg-brand-navy">
            <i class="fa-solid fa-arrow-up text-sm"></i>
            <span class="float-tooltip">Lên đầu trang</span>
        </button>

        <!-- Nút Facebook -->
        <a href="https://www.facebook.com/profile.php?id=100057053437402" target="_blank" rel="noopener noreferrer" aria-label="Facebook Tùng Kỳ Phương" class="float-btn bg-[#1877F2]">
            <i class="fa-brands fa-facebook-f text-lg"></i>
            <span class="float-tooltip">Facebook Tùng Kỳ Phương</span>
        </a>

        <!-- Nút Zalo -->
        <a href="https://zalo.me/0905262564" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0905.262.564" class="float-btn bg-[#0068FF]">
            <span class="font-extrabold text-[13px] tracking-tight">Zalo</span>
            <span class="float-tooltip">Chat Zalo: 0905.262.564</span>
        </a>

        <!-- Nút Hotline -->
        <a href="tel:0905262564" aria-label="Gọi Hotline 0905.262.564" class="float-btn bg-brand-gold hotline-pulse">
            <i class="fa-solid fa-phone-volume text-lg"></i>
            <span class="float-tooltip">Hotline: 0905.262.564</span>
        </a>
    </div>

    <!-- =========================================================
         MODAL XEM ẢNH CÔNG TRÌNH / ĐỌC BÀI VIẾT CHI TIẾT
    ========================================================== -->
    <div id="detail-modal" class="hidden fixed inset-0 z-[80] bg-black/75 backdrop-blur-xs flex items-center justify-center p-3 sm:p-6" role="dialog" aria-modal="true">
        <div class="bg-white rounded-xl max-w-3xl w-full max-h-[90vh] overflow-y-auto shadow-2xl relative">
            <button type="button" onclick="closeModal()" aria-label="Đóng hộp thoại" class="sticky top-3 float-right mr-3 mt-3 z-10 w-9 h-9 rounded-full bg-brand-navy text-white hover:bg-brand-gold flex items-center justify-center transition-colors">
                <i class="fa-solid fa-xmark"></i>
            </button>
            <div id="modal-body" class="p-4 sm:p-6 clear-both"></div>
        </div>
    </div>

    <!-- =========================================================
         JAVASCRIPT: QUẢN LÝ ẢNH DRIVE, SLIDER, BỘ LỌC, FORM, MODAL
    ========================================================== -->
    <script>
        /**
         * Cơ chế tải ảnh Google Drive có dự phòng đa tầng:
         * 1) drive.google.com/thumbnail?id=...&sz=w1000 (nhanh & ổn định)
         * 2) lh3.googleusercontent.com/d/... (dự phòng 1)
         * 3) placehold.co với màu nhận diện thương hiệu (dự phòng cuối)
         */
        function handleDriveImageError(img, labelText) {
            const driveId = img.getAttribute('data-drive-id');
            const attempt = parseInt(img.getAttribute('data-attempt') || '0', 10);

            if (driveId && attempt === 0) {
                img.setAttribute('data-attempt', '1');
                img.src = 'https://lh3.googleusercontent.com/d/' + driveId;
                return;
            }
            if (driveId && attempt === 1) {
                img.setAttribute('data-attempt', '2');
                img.src = 'https://drive.google.com/uc?export=view&id=' + driveId;
                return;
            }
            img.onerror = null;
            const safeText = encodeURIComponent(labelText || 'Tung Ky Phuong');
            img.src = 'https://placehold.co/800x600/0F2C59/FFFFFF?text=' + safeText;
        }

        function getDriveThumb(id, size) {
            return 'https://drive.google.com/thumbnail?id=' + id + '&sz=w' + (size || 1000);
        }

        /* =========================================================
           1. DỮ LIỆU 9 ẢNH THỰC TẾ THI CÔNG XÂY DỰNG (TỪ GOOGLE DRIVE)
        ========================================================== */
        const constructionProjects = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                title: 'Thi Công Phần Thô & Kết Cấu Sàn Bê Tông Cốt Thép',
                category: ['nha-pho', 'phan-tho'],
                categoryLabel: 'Thi công phần thô · Nhà phố',
                location: 'TP Đà Nẵng',
                desc: 'Thi công chuẩn kỹ thuật hệ dầm, cột, thép sàn 2 lớp và đổ bê tông thương phẩm đảm bảo độ bền vững kết cấu lâu dài.'
            },
            {
                id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                title: 'Thi Công Nhà Phố Hiện Đại Trọn Gói Chìa Khóa Trao Tay',
                category: ['nha-pho', 'hoan-thien'],
                categoryLabel: 'Nhà phố · Thi công hoàn thiện',
                location: 'TP Đà Nẵng',
                desc: 'Triển khai trọn gói từ phần móng, khung kết cấu đến hoàn thiện mặt tiền, sơn nước, cửa nhôm kính và hệ thống điện nước.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                title: 'Thi Công Hoàn Thiện Biệt Thự & Ngoại Thất Cao Cấp',
                category: ['biet-thu', 'hoan-thien'],
                categoryLabel: 'Biệt thự · Thi công hoàn thiện',
                location: 'TP Đà Nẵng',
                desc: 'Hoàn thiện mặt đứng kiến trúc biệt thự sang trọng, xử lý chống thấm tường ngoài và ốp đá tự nhiên tinh xảo.'
            },
            {
                id: '1Wlhms5ZB_mL9OptenKvrBS-rGCP2xU1_',
                title: 'Thi Công Phần Thô Công Trình Khách Sạn & Căn Hộ Cho Thuê',
                category: ['khach-san-can-ho', 'phan-tho'],
                categoryLabel: 'Khách sạn - Căn hộ · Phần thô',
                location: 'TP Đà Nẵng',
                desc: 'Thi công khung kết cấu nhiều tầng cho tổ hợp căn hộ dịch vụ và khách sạn với quy trình kiểm soát an toàn lao động nghiêm ngặt.'
            },
            {
                id: '1bRJmtvTDnszz8dMG3_a3Z8hoL5igG-hO',
                title: 'Thi Công Xây Tô, Chống Thấm & Ốp Lát Hoàn Thiện',
                category: ['nha-pho', 'hoan-thien'],
                categoryLabel: 'Thi công hoàn thiện',
                location: 'Xã Hà Nha, TP Đà Nẵng',
                desc: 'Kỹ thuật xây tường chuẩn mạch, tô trát phẳng mịn, chống thấm sàn mái và nhà vệ sinh nhiều lớp theo tiêu chuẩn Sika.'
            },
            {
                id: '1_0OVVXoqQgYvoVEaZSC5iZh_SKGBbr-t',
                title: 'Xây Dựng Căn Hộ Dịch Vụ & Phòng Trọ Cao Cấp',
                category: ['khach-san-can-ho', 'hoan-thien'],
                categoryLabel: 'Khách sạn - Căn hộ',
                location: 'TP Đà Nẵng',
                desc: 'Giải pháp thiết kế và thi công tối ưu số lượng phòng, thông thoáng tự nhiên, tiết kiệm chi phí vận hành cho chủ đầu tư.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                title: 'Thi Công Hoàn Thiện Văn Phòng & Nội Thất Đồng Bộ',
                category: ['van-phong', 'noi-that'],
                categoryLabel: 'Văn phòng · Thi công nội thất',
                location: 'TP Đà Nẵng',
                desc: 'Thi công trần thạch cao, vách kính, hệ thống chiếu sáng, điều hòa và lắp đặt đồ gỗ nội thất văn phòng hiện đại.'
            },
            {
                id: '1wHGqk7znpnGmrOjz4_EdpHnHK8xKyxkT',
                title: 'Thi Công Cải Tạo, Nâng Tầng & Hoàn Thiện Nhà Phố',
                category: ['nha-pho', 'noi-that', 'hoan-thien'],
                categoryLabel: 'Nhà phố · Nội thất',
                location: 'TP Đà Nẵng',
                desc: 'Gia cố kết cấu, nâng tầng mở rộng không gian sinh hoạt và cải tạo nội ngoại thất mang lại diện mạo mới hoàn toàn.'
            },
            {
                id: '1-eBgG9wF3I6_gyPir2CmCnwJg4sP7Bnn',
                title: 'Thi Công Biệt Thự Sân Vườn & Hạng Mục Cảnh Quan',
                category: ['biet-thu', 'phan-tho', 'hoan-thien'],
                categoryLabel: 'Biệt thự · Thi công trọn gói',
                location: 'TP Đà Nẵng',
                desc: 'Thi công trọn gói biệt thự nhà vườn kết hợp cổng tường rào, sân vườn xanh mát và hệ thống chiếu sáng ngoại thất.'
            }
        ];

        /* =========================================================
           2. DỮ LIỆU 10 ẢNH DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (TỪ GOOGLE DRIVE)
        ========================================================== */
        const danangProjects = [
            {
                id: '157Suq0BLEh2zFs3X-uaNTN-ARDWhfjfT',
                title: 'Dự Án Nhà Phố Hiện Đại – Khu Đô Thị Hòa Xuân, Đà Nẵng',
                scope: 'Thi công trọn gói'
            },
            {
                id: '1FVfIU7HJM8cAb-lO7wnjGvji6ZEvl7ff',
                title: 'Dự Án Biệt Thự 2 Mặt Tiền – Ngũ Hành Sơn, Đà Nẵng',
                scope: 'Thiết kế & Thi công'
            },
            {
                id: '1wkzckXZhRrWh3V2GIOfdqBmOwQTBVFhz',
                title: 'Dự Án Căn Hộ Dịch Vụ Cho Thuê – Sơn Trà, Đà Nẵng',
                scope: 'Thi công phần thô & Hoàn thiện'
            },
            {
                id: '1I7lc3ghS0tyqh6Pq3xsZTidKsr0oT-8k',
                title: 'Dự Án Khách Sạn Boutique – Hải Châu, Đà Nẵng',
                scope: 'Thi công trọn gói'
            },
            {
                id: '1Q8VoCbT7s09UNaoI8GNcYdvKpJ2wz78N',
                title: 'Dự Án Nhà Phố Thương Mại – Cẩm Lệ, Đà Nẵng',
                scope: 'Xây dựng hoàn thiện'
            },
            {
                id: '1tkQlfZJTkaSunwOIMhfnzkEG2YHwxhML',
                title: 'Dự Án Văn Phòng Làm Việc – TP Đà Nẵng',
                scope: 'Thi công & Nội thất'
            },
            {
                id: '1An7LyMVwj3rhKZlsVnYQ2UrLe48IeTBF',
                title: 'Dự Án Nhà Ở Gia Đình – Xã Hà Nha, TP Đà Nẵng',
                scope: 'Thi công trọn gói'
            },
            {
                id: '1R1Da04pAYI9-NJz1IsAfa7pVKkuK7J-A',
                title: 'Dự Án Biệt Thự Phố – Khu Nam Việt Á, Đà Nẵng',
                scope: 'Thiết kế & Xây dựng'
            },
            {
                id: '1FdQEsiEBrIW5TiN22dvzV5g6amDPp-80',
                title: 'Dự Án Nhà Phố 3 Tầng – Liên Chiểu, Đà Nẵng',
                scope: 'Thi công phần thô & Hoàn thiện'
            },
            {
                id: '1So_3V4rw1y7lHegiIkYmh2Z9UIdozAL4',
                title: 'Dự Án Tổ Hợp Căn Hộ – Thanh Khê, Đà Nẵng',
                scope: 'Thi công trọn gói'
            }
        ];

        /* =========================================================
           3. DỮ LIỆU BÀI VIẾT / TIN TỨC TRANG CHỦ
        ========================================================== */
        const articlesData = [
            {
                id: '13S9xBPbSGKY6Kmr5Mc0x4Dk-1CdozBlz',
                date: '15/10/2026',
                title: 'Hướng Dẫn Bảo Dưỡng Bê Tông Móng Và Sàn Đúng Kỹ Thuật',
                excerpt: 'Quy trình tưới ẩm và che phủ bê tông trong 7 ngày đầu sau khi đổ giúp kết cấu đạt cường độ tối đa, hạn chế nứt bề mặt.',
                content: 'Trong quá trình thi công phần thô, bảo dưỡng bê tông móng và sàn là công đoạn mang tính quyết định đến tuổi thọ công trình. Sau khi đổ bê tông từ 4 đến 6 giờ, bề mặt cần được che phủ bằng bao tải ẩm hoặc bạt chuyên dụng để tránh mất nước đột ngột dưới nắng gió miền Trung. Trong 7 ngày đầu tiên, cần duy trì độ ẩm liên tục bằng cách phun sương nhẹ đều đặn mỗi ngày.'
            },
            {
                id: '1taZEEvo_cWqkQxBcCPhpoDRIIMQ-50eR',
                date: '02/10/2026',
                title: 'Kinh Nghiệm Xây Nhà Trọn Gói Tại Đà Nẵng Không Phát Sinh Chi Phí',
                excerpt: 'Những lưu ý quan trọng về hồ sơ bản vẽ, bảng chủng loại vật tư và tiến độ thanh toán giúp chủ đầu tư kiểm soát ngân sách hiệu quả.',
                content: 'Để xây nhà trọn gói không phát sinh chi phí, chủ đầu tư nên hoàn thiện bản vẽ thiết kế kiến trúc và nội thất chi tiết trước khi khởi công. Hợp đồng thi công cần quy định rõ mã vật tư phần thô (thép, xi măng, gạch, dây điện, ống nước) và vật tư hoàn thiện. Lựa chọn nhà thầu uy tín tại địa phương như Tùng Kỳ Phương giúp giảm chi phí quản lý và đảm bảo bảo hành nhanh chóng.'
            },
            {
                id: '1Y1HUmEwHLU9YbOhwPzHpFwKQecXvLhUv',
                date: '18/09/2026',
                title: 'Giải Pháp Chống Thấm Mùa Mưa Bão Cho Nhà Phố Miền Trung',
                excerpt: 'Tổng hợp các vị trí dễ thấm dột như sân thượng, tường tiếp giáp, hộp gen kỹ thuật và phương án xử lý triệt để ngay từ phần thô.',
                content: 'Khí hậu Đà Nẵng có mùa mưa kéo dài kết hợp gió lớn nên hạng mục chống thấm cần được chú trọng ngay từ khâu xây thô. Các khu vực sân thượng, ban công, sàn vệ sinh và cổ ống xuyên sàn phải được vệ sinh sạch, bo góc chân tường và quét tối thiểu 2-3 lớp vật liệu chống thấm chuyên dụng, sau đó ngâm nước kiểm tra tối thiểu 48 giờ trước khi cán nền lát gạch.'
            },
            {
                id: '1UB12E_spzIvo7TNREjBJXUV9o_HVWOv_',
                date: '05/09/2026',
                title: 'Xu Hướng Thiết Kế Không Gian Mở Và Nội Thất Tối Giản Hiện Đại',
                excerpt: 'Tối ưu thông gió tự nhiên, tận dụng ánh sáng trời và lựa chọn vật liệu bền bỉ giúp không gian sống luôn rộng rãi, thoáng mát.',
                content: 'Thiết kế không gian mở kết hợp giếng trời và mảng xanh đang là lựa chọn hàng đầu cho nhà phố và biệt thự tại Đà Nẵng. Việc lược bỏ các vách ngăn không cần thiết giữa phòng khách và bếp giúp lưu thông không khí tốt hơn, đồng thời mang lại cảm giác rộng rãi và gắn kết cho cả gia đình.'
            }
        ];

        /* =========================================================
           RENDER CÔNG TRÌNH THỰC TẾ (2 CỘT MOBILE, ĐỦ TÊN KHÔNG CẮT CHỮ)
        ========================================================== */
        function renderConstructionGrid(filterKey) {
            const container = document.getElementById('construction-grid');
            if (!container) return;

            const filtered = filterKey === 'all'
                ? constructionProjects
                : constructionProjects.filter(item => item.category.includes(filterKey));

            container.innerHTML = filtered.map((item, idx) => `
                <article
                    onclick="openProjectModal('${item.id}', '${escapeHtml(item.title)}', '${escapeHtml(item.categoryLabel)}', '${escapeHtml(item.location)}', '${escapeHtml(item.desc)}')"
                    class="tkp-card cursor-pointer bg-white border border-slate-200 rounded-xl overflow-hidden hover:border-brand-gold hover:shadow-md transition-all flex flex-col"
                >
                    <div class="card-image-wrap">
                        <img
                            src="${getDriveThumb(item.id, 900)}"
                            data-drive-id="${item.id}"
                            onerror="handleDriveImageError(this, 'Công trình Tùng Kỳ Phương')"
                            alt="${escapeHtml(item.title)}"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <h3 class="text-[12.5px] sm:text-sm md:text-[15px] font-bold text-brand-navy leading-snug break-words mb-1.5">
                                ${item.title}
                            </h3>
                            <p class="text-[11px] sm:text-xs text-slate-500 leading-normal break-words">
                                ${item.categoryLabel}
                            </p>
                        </div>
                        <div class="mt-2.5 pt-2 border-t border-slate-100 flex items-center justify-between text-[11px] sm:text-xs text-brand-goldDark font-semibold">
                            <span>Xem chi tiết</span>
                            <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        function filterConstruction(filterKey) {
            document.querySelectorAll('#construction-tabs .category-tab-btn').forEach(btn => {
                if (btn.getAttribute('data-filter') === filterKey) {
                    btn.classList.add('active');
                } else {
                    btn.classList.remove('active');
                }
            });
            renderConstructionGrid(filterKey);
        }

        /* =========================================================
           RENDER 10 DỰ ÁN ĐÀ NẴNG (2 CỘT MOBILE, 5 CỘT DESKTOP)
        ========================================================== */
        function renderDanangProjects() {
            const container = document.getElementById('danang-projects-grid');
            if (!container) return;

            container.innerHTML = danangProjects.map(item => `
                <article
                    onclick="openProjectModal('${item.id}', '${escapeHtml(item.title)}', '${escapeHtml(item.scope)}', 'TP Đà Nẵng', 'Công trình thực tế được triển khai bởi Công ty TNHH Xây dựng và Thương mại Tùng Kỳ Phương tại khu vực TP Đà Nẵng. Đảm bảo kỹ thuật, thẩm mỹ và tiến độ bàn giao.')"
                    class="tkp-card cursor-pointer bg-white border border-slate-200 rounded-xl overflow-hidden hover:border-brand-gold hover:shadow-md transition-all flex flex-col"
                >
                    <div class="card-image-wrap">
                        <img
                            src="${getDriveThumb(item.id, 800)}"
                            data-drive-id="${item.id}"
                            onerror="handleDriveImageError(this, 'Dự án Đà Nẵng')"
                            alt="${escapeHtml(item.title)}"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-2.5 sm:p-3.5 flex-1 flex flex-col justify-between">
                        <h3 class="text-[12px] sm:text-[13.5px] font-bold text-brand-navy leading-snug break-words mb-1.5">
                            ${item.title}
                        </h3>
                        <p class="text-[11px] text-brand-goldDark font-medium break-words">
                            ${item.scope}
                        </p>
                    </div>
                </article>
            `).join('');
        }

        /* =========================================================
           RENDER BÀI VIẾT TRANG CHỦ
        ========================================================== */
        function renderArticles() {
            const container = document.getElementById('articles-grid');
            if (!container) return;

            container.innerHTML = articlesData.map((art, index) => `
                <article
                    onclick="openArticleModal(${index})"
                    class="tkp-card cursor-pointer bg-white border border-slate-200 rounded-xl overflow-hidden hover:border-brand-gold hover:shadow-md transition-all flex flex-col"
                >
                    <div class="card-image-wrap">
                        <img
                            src="${getDriveThumb(art.id, 800)}"
                            data-drive-id="${art.id}"
                            onerror="handleDriveImageError(this, 'Tin tức xây dựng')"
                            alt="${escapeHtml(art.title)}"
                            loading="lazy"
                        >
                    </div>
                    <div class="p-4 flex-1 flex flex-col justify-between">
                        <div>
                            <div class="text-[11px] text-slate-400 mb-1.5">
                                <i class="fa-regular fa-calendar mr-1"></i>${art.date}
                            </div>
                            <h3 class="text-sm font-bold text-brand-navy leading-snug mb-2 break-words">
                                ${art.title}
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">
                                ${art.excerpt}
                            </p>
                        </div>
                        <div class="mt-3 pt-2.5 border-t border-slate-100 text-xs font-semibold text-brand-goldDark flex items-center gap-1.5">
                            <span>Đọc bài viết</span>
                            <i class="fa-solid fa-angle-right text-[11px]"></i>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        /* =========================================================
           MODAL CHI TIẾT CÔNG TRÌNH & BÀI VIẾT
        ========================================================== */
        function escapeHtml(str) {
            return String(str).replace(/'/g, "\\'").replace(/"/g, '&quot;');
        }

        function openProjectModal(driveId, title, category, location, desc) {
            const modal = document.getElementById('detail-modal');
            const body = document.getElementById('modal-body');
            body.innerHTML = `
                <div class="rounded-lg overflow-hidden bg-slate-100 mb-4">
                    <img
                        src="${getDriveThumb(driveId, 1400)}"
                        data-drive-id="${driveId}"
                        onerror="handleDriveImageError(this, 'Tùng Kỳ Phương')"
                        alt="${title}"
                        class="w-full max-h-[60vh] object-contain mx-auto bg-slate-900"
                    >
                </div>
                <h3 class="text-lg sm:text-xl font-extrabold text-brand-navy mb-2">${title}</h3>
                <div class="flex flex-wrap gap-3 text-xs text-slate-600 mb-3">
                    <span><i class="fa-solid fa-folder-open text-brand-gold mr-1"></i>${category}</span>
                    <span><i class="fa-solid fa-location-dot text-brand-gold mr-1"></i>${location}</span>
                </div>
                <p class="text-sm text-slate-700 leading-relaxed mb-5">${desc}</p>
                <div class="flex flex-wrap gap-3">
                    <a href="#bao-gia" onclick="closeModal()" class="px-5 py-2.5 rounded-lg bg-brand-gold hover:bg-brand-goldDark text-white font-semibold text-sm transition-colors">
                        Yêu Cầu Báo Giá Công Trình Tương Tự
                    </a>
                    <a href="tel:0905262564" class="px-5 py-2.5 rounded-lg bg-brand-navy hover:bg-brand-navyDark text-white font-semibold text-sm transition-colors">
                        Gọi Tư Vấn: 0905.262.564
                    </a>
                </div>
            `;
            modal.classList.remove('hidden');
            document.body.style.overflow = 'hidden';
        }

        function openArticleModal(index) {
            const art = articlesData[index];
            if (!art) return;
            const modal = document.getElementById('detail-modal');
            const body = document.getElementById('modal-body');
            body.innerHTML = `
                <div class="rounded-lg overflow-hidden bg-slate-100 mb-4">
                    <img
                        src="${getDriveThumb(art.id, 1200)}"
                        data-drive-id="${art.id}"
                        onerror="handleDriveImageError(this, 'Bài viết xây dựng')"
                        alt="${art.title}"
                        class="w-full h-56 sm:h-72 object-cover"
                    >
                </div>
                <div class="text-xs text-slate-500 mb-1.5"><i class="fa-regular fa-calendar mr-1"></i>${art.date} · Tùng Kỳ Phương</div>
                <h3 class="text-lg sm:text-2xl font-extrabold text-brand-navy mb-3 leading-snug">${art.title}</h3>
                <p class="text-sm sm:text-[15px] text-slate-700 leading-relaxed mb-4">${art.content}</p>
                <p class="text-sm text-slate-600 leading-relaxed bg-brand-bg p-4 rounded-lg border border-slate-200">
                    Quý khách cần tư vấn kỹ thuật hoặc nhận bảng báo giá xây dựng mới nhất tại Đà Nẵng vui lòng liên hệ <strong>CÔNG TY TNHH XÂY DỰNG VÀ THƯƠNG MẠI TÙNG KỲ PHƯƠNG</strong> qua số điện thoại <a href="tel:0905262564" class="text-brand-goldDark font-bold">0905.262.564</a>.
                </p>
            `;
            modal.classList.remove('hidden');
            document.body.style.overflow = 'hidden';
        }

        function closeModal() {
            const modal = document.getElementById('detail-modal');
            modal.classList.add('hidden');
            document.body.style.overflow = '';
        }

        document.getElementById('detail-modal').addEventListener('click', function (e) {
            if (e.target === this) closeModal();
        });

        /* =========================================================
           SLIDER 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT CẢM ỨNG MOBILE
        ========================================================== */
        let currentSlide = 0;
        const totalSlides = 2;
        let sliderTimer = null;

        function updateSliderUI() {
            const track = document.getElementById('hero-track');
            if (track) {
                track.style.transform = 'translateX(-' + (currentSlide * 50) + '%)';
            }
            for (let i = 0; i < totalSlides; i++) {
                const dot = document.getElementById('dot-' + i);
                if (!dot) continue;
                if (i === currentSlide) {
                    dot.classList.remove('w-2.5', 'bg-white/60');
                    dot.classList.add('w-7', 'bg-brand-gold');
                } else {
                    dot.classList.remove('w-7', 'bg-brand-gold');
                    dot.classList.add('w-2.5', 'bg-white/60');
                }
            }
        }

        function goToSlide(idx) {
            currentSlide = (idx + totalSlides) % totalSlides;
            updateSliderUI();
            resetAutoSlide();
        }

        function resetAutoSlide() {
            if (sliderTimer) clearInterval(sliderTimer);
            sliderTimer = setInterval(() => {
                currentSlide = (currentSlide + 1) % totalSlides;
                updateSliderUI();
            }, 5200);
        }

        document.getElementById('prev-slide').addEventListener('click', () => goToSlide(currentSlide - 1));
        document.getElementById('next-slide').addEventListener('click', () => goToSlide(currentSlide + 1));

        // Hỗ trợ vuốt cảm ứng trái/phải trên điện thoại cho Banner Slider
        (function initTouchSwipe() {
            const sliderEl = document.getElementById('trang-chu');
            let startX = 0;
            sliderEl.addEventListener('touchstart', (e) => {
                startX = e.changedTouches[0].screenX;
            }, { passive: true });
            sliderEl.addEventListener('touchend', (e) => {
                const endX = e.changedTouches[0].screenX;
                if (startX - endX > 45) goToSlide(currentSlide + 1);
                if (endX - startX > 45) goToSlide(currentSlide - 1);
            }, { passive: true });
        })();

        /* =========================================================
           MENU MOBILE & NÚT LÊN ĐẦU TRANG
        ========================================================== */
        const mobileMenuBtn = document.getElementById('mobile-menu-btn');
        const mobileMenu = document.getElementById('mobile-menu');
        mobileMenuBtn.addEventListener('click', () => {
            mobileMenu.classList.toggle('hidden');
        });
        document.querySelectorAll('.mobile-nav-link').forEach(link => {
            link.addEventListener('click', () => mobileMenu.classList.add('hidden'));
        });

        window.addEventListener('scroll', () => {
            const btn = document.getElementById('back-to-top');
            if (window.scrollY > 380) {
                btn.classList.remove('hidden');
            } else {
                btn.classList.add('hidden');
            }
        });

        /* =========================================================
           XỬ LÝ FORM YÊU CẦU & BÁO GIÁ (KHÔNG DÙNG ALERT)
        ========================================================== */
        document.getElementById('quote-form').addEventListener('submit', function (e) {
            e.preventDefault();
            const name = document.getElementById('q-name').value.trim();
            const phone = document.getElementById('q-phone').value.trim();
            const type = document.getElementById('q-type').value;
            const feedback = document.getElementById('quote-feedback');

            if (!name || !phone) {
                feedback.className = 'rounded-lg p-3.5 text-sm font-medium bg-red-50 text-red-700 border border-red-200';
                feedback.textContent = 'Vui lòng nhập đầy đủ Họ và tên cùng Số điện thoại để Tùng Kỳ Phương liên hệ báo giá.';
                return;
            }

            feedback.className = 'rounded-lg p-3.5 text-sm font-medium bg-emerald-50 text-emerald-800 border border-emerald-200';
            feedback.innerHTML = 'Cảm ơn <strong>' + name + '</strong>! Yêu cầu báo giá hạng mục <strong>' + type + '</strong> đã được ghi nhận. Kỹ sư Tùng Kỳ Phương sẽ gọi lại qua số <strong>' + phone + '</strong> trong thời gian sớm nhất (Hotline hỗ trợ nhanh: 0905.262.564).';
            this.reset();
        });

        /* =========================================================
           KHỞI TẠO TRANG
        ========================================================== */
        window.addEventListener('DOMContentLoaded', () => {
            renderConstructionGrid('all');
            renderDanangProjects();
            renderArticles();
            updateSliderUI();
            resetAutoSlide();
        });
    </script>
</body>
</html>
