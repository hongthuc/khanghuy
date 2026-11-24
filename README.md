<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=5.0">
    <title>CÔNG TY TNHH ĐẦU TƯ PHÁT TRIỂN KHANG HUY | Cửa Nhôm Xingfa & Kính Cường Lực Đà Nẵng</title>
    <meta name="description" content="Công ty TNHH Đầu Tư Phát Triển Khang Huy (khanghuy.com) - Chuyên sản xuất, thi công Cửa nhôm Xingfa nhập khẩu, Cửa kính cường lực, Cửa nhựa lõi thép, Cầu thang kính, Phòng tắm kính tại Đà Nẵng. Hotline: 0915.493.033.">

    <!-- Meta Thumbnail (Logo Khang Huy) khi chia sẻ link trang web lên Zalo, Facebook -->
    <meta property="og:type" content="website">
    <meta property="og:site_name" content="CÔNG TY TNHH ĐẦU TƯ PHÁT TRIỂN KHANG HUY">
    <meta property="og:url" content="https://khanghuy.com/">
    <meta property="og:title" content="CÔNG TY TNHH ĐẦU TƯ PHÁT TRIỂN KHANG HUY | Cửa Nhôm Xingfa Đà Nẵng">
    <meta property="og:description" content="Chuyên thiết kế, sản xuất & thi công Cửa nhôm Xingfa chính hãng, Cửa kính cường lực, Cầu thang kính, Phòng tắm kính tại Đà Nẵng. Hotline: 0915.493.033.">
    <meta property="og:image" content="https://placehold.co/1200x630/0B3C5D/D98218?text=KHANG+HUY+WINDOW+-+khanghuy.com">
    <meta property="og:image:width" content="1200">
    <meta property="og:image:height" content="630">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:image" content="https://placehold.co/1200x630/0B3C5D/D98218?text=KHANG+HUY+WINDOW+-+khanghuy.com">

    <!-- Favicon đồng bộ màu Logo Khang Huy -->
    <link rel="icon" type="image/svg+xml" href="data:image/svg+xml,%3Csvg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 64 64'%3E%3Crect width='64' height='64' rx='12' fill='%230B3C5D'/%3E%3Crect x='8' y='8' width='48' height='48' rx='6' fill='none' stroke='%23E59500' stroke-width='3'/%3E%3Cpath d='M18 18h6v28h-6zm6 14l14-14h8L31 32l15 14h-8L24 32z' fill='%23FFFFFF'/%3E%3C/svg%3E">

    <!-- Fonts & Icons -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS CDN -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'system-ui', 'sans-serif'],
                    },
                    colors: {
                        /* Bảng màu đồng bộ theo Logo Khang Huy: Xanh Navy Kiến Trúc + Vàng Đồng Thịnh Vượng */
                        khNavy: {
                            50: '#F0F6FA',
                            100: '#DCEAF3',
                            600: '#13537D',
                            700: '#0E4468',
                            800: '#0B3C5D',
                            900: '#072940',
                        },
                        khGold: {
                            400: '#F5B041',
                            500: '#E59500',
                            600: '#C97A00',
                            700: '#A66300',
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* =========================================================
           CẤU HÌNH GIAO DIỆN FLATSOME CHUẨN - KHÔNG TRÀN VIỀN
        ========================================================= */
        *, *::before, *::after {
            box-sizing: border-box;
        }

        html {
            scroll-behavior: smooth;
            overflow-x: hidden;
            width: 100%;
        }

        body {
            font-family: 'Inter', sans-serif;
            color: #1E293B;
            background-color: #FFFFFF;
            overflow-x: hidden;
            width: 100%;
            margin: 0;
            padding: 0;
        }

        /* Chiều ngang giao diện trên máy tính đúng bằng 95% kích thước màn hình */
        .kh-container {
            width: 100%;
            max-width: 100%;
            margin-left: auto;
            margin-right: auto;
            padding-left: 12px;
            padding-right: 12px;
        }

        @media (min-width: 640px) {
            .kh-container {
                padding-left: 16px;
                padding-right: 16px;
            }
        }

        @media (min-width: 1024px) {
            .kh-container {
                width: 95%;
                max-width: 95%;
                padding-left: 0;
                padding-right: 0;
            }
        }

        /* Menu Dropdown Flatsome mượt mà trên Desktop */
        .nav-dropdown-wrap {
            position: relative;
        }
        .nav-dropdown-menu {
            opacity: 0;
            visibility: hidden;
            transform: translateY(8px);
            transition: all 0.2s ease;
        }
        .nav-dropdown-wrap:hover .nav-dropdown-menu,
        .nav-dropdown-wrap:focus-within .nav-dropdown-menu {
            opacity: 1;
            visibility: visible;
            transform: translateY(0);
        }

        /* Tiêu đề mục phong cách Flatsome gạch chân giữa */
        .flatsome-heading {
            position: relative;
            display: inline-block;
            padding-bottom: 10px;
        }
        .flatsome-heading::after {
            content: "";
            position: absolute;
            left: 50%;
            bottom: 0;
            transform: translateX(-50%);
            width: 64px;
            height: 3px;
            background: linear-gradient(90deg, #0B3C5D, #E59500);
            border-radius: 999px;
        }

        /* Hiệu ứng nút liên hệ nổi bật */
        @keyframes khPulse {
            0% { box-shadow: 0 0 0 0 rgba(229, 149, 0, 0.55); }
            70% { box-shadow: 0 0 0 12px rgba(229, 149, 0, 0); }
            100% { box-shadow: 0 0 0 0 rgba(229, 149, 0, 0); }
        }
        .btn-hotline-pulse {
            animation: khPulse 2s infinite;
        }

        /* Slider mượt cho 2 banner bằng kích thước nhau */
        .kh-slides-track {
            display: flex;
            transition: transform 0.65s cubic-bezier(0.4, 0, 0.2, 1);
            width: 100%;
        }
        .kh-slide-item {
            flex: 0 0 100%;
            width: 100%;
            min-width: 100%;
        }
    </style>
</head>

<body class="bg-white text-slate-800 antialiased selection:bg-khNavy-800 selection:text-white">

    <!-- =========================================================================
         1. TOP BAR (FLATSOME HEADER TOP) - THÔNG TIN NHANH
    ========================================================================== -->
    <div class="bg-khNavy-900 text-slate-100 text-[11px] sm:text-xs border-b border-khNavy-700/60">
        <div class="kh-container py-1.5 flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-3 sm:gap-5 min-w-0">
                <span class="flex items-center gap-1.5 truncate">
                    <i class="fa-solid fa-location-dot text-khGold-400 shrink-0"></i>
                    <span class="truncate">Lô CN1, CCN Thường Tín, P. Điện Bàn Đông, TP Đà Nẵng</span>
                </span>
                <span class="hidden md:inline-flex items-center gap-1.5 shrink-0 text-slate-300">
                    <i class="fa-regular fa-clock text-khGold-400"></i>
                    Làm việc 24/7
                </span>
            </div>
            <div class="flex items-center gap-4 shrink-0">
                <a href="tel:0915493033" class="inline-flex items-center gap-1.5 font-semibold text-khGold-400 hover:text-white transition">
                    <i class="fa-solid fa-phone-volume"></i>
                    <span>0915.493.033</span>
                </a>
                <span class="hidden sm:inline text-slate-400">|</span>
                <a href="#trang-chu" class="hidden sm:inline text-slate-200 hover:text-khGold-400 transition">khanghuy.com</a>
            </div>
        </div>
    </div>

    <!-- =========================================================================
         2. HEADER CHÍNH + LOGO NHỎ GỌN + MENU 1 HÀNG KHÔNG TRÀN VIỀN
         (Không đặt nút Gọi ngay trên Header để giữ giao diện gọn đẹp)
    ========================================================================== -->
    <header id="main-header" class="sticky top-0 z-40 bg-white/95 backdrop-blur-md border-b border-slate-200 shadow-sm">
        <div class="kh-container">
            <div class="flex items-center justify-between h-14 sm:h-16 gap-2">

                <!-- Logo Công ty Khang Huy chuyên nghiệp, kích thước gọn nhỏ -->
                <a href="#trang-chu" class="flex items-center gap-2 shrink-0 group focus:outline-none" aria-label="Công ty TNHH Đầu Tư Phát Triển Khang Huy">
                    <div class="w-9 h-9 sm:w-10 sm:h-10 shrink-0">
                        <svg viewBox="0 0 64 64" class="w-full h-full drop-shadow-sm" xmlns="http://www.w3.org/2000/svg">
                            <defs>
                                <linearGradient id="khLogoBg" x1="0%" y1="0%" x2="100%" y2="100%">
                                    <stop offset="0%" stop-color="#0B3C5D"/>
                                    <stop offset="100%" stop-color="#13537D"/>
                                </linearGradient>
                                <linearGradient id="khLogoGold" x1="0%" y1="0%" x2="100%" y2="100%">
                                    <stop offset="0%" stop-color="#F5B041"/>
                                    <stop offset="100%" stop-color="#C97A00"/>
                                </linearGradient>
                            </defs>
                            <!-- Khung cửa nhôm kiến trúc -->
                            <rect x="2" y="2" width="60" height="60" rx="12" fill="url(#khLogoBg)"/>
                            <rect x="7" y="7" width="50" height="50" rx="8" fill="none" stroke="url(#khLogoGold)" stroke-width="2.6"/>
                            <!-- Chữ lồng K & H biểu tượng khung cửa kính -->
                            <path d="M16 17H22V47H16V17Z" fill="#FFFFFF"/>
                            <path d="M22 31.5L35 17H42.5L28.5 32L43 47H35.2L22 32.5V31.5Z" fill="url(#khLogoGold)"/>
                            <path d="M43 17H48.5V47H43V17Z" fill="#FFFFFF"/>
                            <rect x="33" y="29.5" width="12" height="4.5" rx="1" fill="#FFFFFF" opacity="0.9"/>
                        </svg>
                    </div>
                    <div class="flex flex-col leading-none">
                        <span class="text-sm sm:text-base font-extrabold tracking-tight text-khNavy-800 group-hover:text-khGold-600 transition">KHANG HUY</span>
                        <span class="text-[9px] sm:text-[10px] font-semibold tracking-wider text-khGold-600 uppercase mt-0.5">Nhôm Kính Cao Cấp</span>
                    </div>
                </a>

                <!-- Menu Desktop: Chữ nhỏ gọn, viết liền trên 1 hàng, tuyệt đối không xuống dòng -->
                <nav class="hidden lg:flex items-center justify-end flex-1 min-w-0" aria-label="Danh mục chính">
                    <ul class="flex items-center flex-nowrap gap-0.5 xl:gap-1.5 text-[11.5px] xl:text-[13px] font-semibold text-khNavy-800">
                        <li class="shrink-0">
                            <a href="#trang-chu" class="whitespace-nowrap px-2 xl:px-2.5 py-2 rounded-md hover:bg-khNavy-50 hover:text-khGold-600 transition">Trang chủ</a>
                        </li>
                        <li class="shrink-0">
                            <a href="#gioi-thieu" class="whitespace-nowrap px-2 xl:px-2.5 py-2 rounded-md hover:bg-khNavy-50 hover:text-khGold-600 transition">Giới thiệu</a>
                        </li>

                        <!-- Dropdown: Cửa nhôm xingfa -->
                        <li class="nav-dropdown-wrap shrink-0">
                            <a href="#san-pham" onclick="filterProductsBySub('xingfa')" class="whitespace-nowrap inline-flex items-center gap-1 px-2 xl:px-2.5 py-2 rounded-md hover:bg-khNavy-50 hover:text-khGold-600 transition">
                                <span>Cửa nhôm xingfa</span>
                                <i class="fa-solid fa-chevron-down text-[9px] text-slate-400"></i>
                            </a>
                            <div class="nav-dropdown-menu absolute left-0 top-full pt-1.5 w-52 z-50">
                                <div class="bg-white rounded-lg shadow-xl border border-slate-100 py-1.5 text-xs font-medium text-slate-700">
                                    <a href="#san-pham" onclick="highlightProduct('Cửa đi quay mở 1 cánh nhôm xingfa')" class="block px-3.5 py-2 hover:bg-khNavy-50 hover:text-khNavy-800 transition">Cửa nhôm xingfa 1 cánh</a>
                                    <a href="#san-pham" onclick="highlightProduct('Cửa đi quay mở 2 cánh nhôm xingfa')" class="block px-3.5 py-2 hover:bg-khNavy-50 hover:text-khNavy-800 transition">Cửa nhôm xingfa 2 cánh</a>
                                    <a href="#san-pham" onclick="highlightProduct('Cửa đi quay mở 3 cánh nhôm xingfa')" class="block px-3.5 py-2 hover:bg-khNavy-50 hover:text-khNavy-800 transition">Cửa nhôm xingfa 3 cánh</a>
                                    <a href="#san-pham" onclick="highlightProduct('Cửa đi quay mở 4 cánh nhôm xingfa')" class="block px-3.5 py-2 hover:bg-khNavy-50 hover:text-khNavy-800 transition">Cửa nhôm xingfa 4 cánh</a>
                                    <a href="#san-pham" onclick="highlightProduct('Cửa Nhôm Xingfa Cửa Đi Xếp Trượt')" class="block px-3.5 py-2 hover:bg-khNavy-50 hover:text-khNavy-800 transition">Cửa nhôm xingfa 5 cánh</a>
                                </div>
                            </div>
                        </li>

                        <li class="shrink-0">
                            <a href="#bao-gia" onclick="switchPriceTab('kinh')" class="whitespace-nowrap px-2 xl:px-2.5 py-2 rounded-md hover:bg-khNavy-50 hover:text-khGold-600 transition">Cửa kính cường lực</a>
                        </li>

                        <!-- Dropdown: Sản phẩm -->
                        <li class="nav-dropdown-wrap shrink-0">
                            <a href="#danh-muc" class="whitespace-nowrap inline-flex items-center gap-1 px-2 xl:px-2.5 py-2 rounded-md hover:bg-khNavy-50 hover:text-khGold-600 transition">
                                <span>Sản phẩm</span>
                                <i class="fa-solid fa-chevron-down text-[9px] text-slate-400"></i>
                            </a>
                            <div class="nav-dropdown-menu absolute left-0 top-full pt-1.5 w-52 z-50">
                                <div class="bg-white rounded-lg shadow-xl border border-slate-100 py-1.5 text-xs font-medium text-slate-700">
                                    <a href="#danh-muc" onclick="selectCategoryNotice('Cửa nhôm xingfa')" class="block px-3.5 py-2 hover:bg-khNavy-50 hover:text-khNavy-800 transition">Cửa nhôm xingfa</a>
                                    <a href="#danh-muc" onclick="selectCategoryNotice('Cửa nhựa lõi thép')" class="block px-3.5 py-2 hover:bg-khNavy-50 hover:text-khNavy-800 transition">Cửa nhựa lõi thép</a>
                                    <a href="#danh-muc" onclick="selectCategoryNotice('Cửa kính tự động')" class="block px-3.5 py-2 hover:bg-khNavy-50 hover:text-khNavy-800 transition">Cửa kính tự động</a>
                                    <a href="#danh-muc" onclick="selectCategoryNotice('Cầu thang kính')" class="block px-3.5 py-2 hover:bg-khNavy-50 hover:text-khNavy-800 transition">Cầu thang kính</a>
                                    <a href="#danh-muc" onclick="selectCategoryNotice('Kính ốp bếp')" class="block px-3.5 py-2 hover:bg-khNavy-50 hover:text-khNavy-800 transition">Kính ốp bếp</a>
                                    <a href="#danh-muc" onclick="selectCategoryNotice('Phòng tắm kính')" class="block px-3.5 py-2 hover:bg-khNavy-50 hover:text-khNavy-800 transition">Phòng tắm kính</a>
                                </div>
                            </div>
                        </li>

                        <li class="shrink-0">
                            <a href="#cong-trinh" class="whitespace-nowrap px-2 xl:px-2.5 py-2 rounded-md hover:bg-khNavy-50 hover:text-khGold-600 transition">Công trình</a>
                        </li>
                        <li class="shrink-0">
                            <a href="#bao-gia" class="whitespace-nowrap px-2 xl:px-2.5 py-2 rounded-md hover:bg-khNavy-50 hover:text-khGold-600 transition">Báo giá</a>
                        </li>
                        <li class="shrink-0">
                            <a href="#tin-tuc" class="whitespace-nowrap px-2 xl:px-2.5 py-2 rounded-md hover:bg-khNavy-50 hover:text-khGold-600 transition">Tin tức</a>
                        </li>
                        <li class="shrink-0">
                            <a href="#lien-he" class="whitespace-nowrap px-2 xl:px-2.5 py-2 rounded-md hover:bg-khNavy-50 hover:text-khGold-600 transition">Liên hệ</a>
                        </li>
                    </ul>
                </nav>

                <!-- Nút mở Menu Mobile (Không có nút gọi ngay trên header) -->
                <button id="mobile-menu-btn" type="button" class="lg:hidden inline-flex items-center justify-center w-10 h-10 rounded-lg border border-slate-200 text-khNavy-800 hover:bg-khNavy-50 transition" aria-label="Mở danh mục">
                    <i class="fa-solid fa-bars text-lg"></i>
                </button>
            </div>
        </div>

        <!-- Drawer Menu trên Điện thoại & Tablet -->
        <div id="mobile-menu-drawer" class="hidden lg:hidden bg-white border-t border-slate-200 shadow-lg max-h-[80vh] overflow-y-auto">
            <div class="kh-container py-3 space-y-1 text-sm font-medium text-khNavy-800">
                <a href="#trang-chu" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg hover:bg-khNavy-50">Trang chủ</a>
                <a href="#gioi-thieu" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg hover:bg-khNavy-50">Giới thiệu</a>

                <!-- Accordion Cửa nhôm xingfa -->
                <div class="border-y border-slate-100 py-1">
                    <button type="button" onclick="toggleMobileSub('sub-xingfa')" class="w-full flex items-center justify-between px-3 py-2.5 rounded-lg hover:bg-khNavy-50 text-left font-semibold">
                        <span>Cửa nhôm xingfa</span>
                        <i id="icon-sub-xingfa" class="fa-solid fa-chevron-down text-xs transition-transform"></i>
                    </button>
                    <div id="sub-xingfa" class="hidden pl-5 pb-1 space-y-1 text-xs text-slate-600">
                        <a href="#san-pham" onclick="closeMobileMenu(); highlightProduct('Cửa đi quay mở 1 cánh nhôm xingfa')" class="block py-2 hover:text-khGold-600">+ Cửa nhôm xingfa 1 cánh</a>
                        <a href="#san-pham" onclick="closeMobileMenu(); highlightProduct('Cửa đi quay mở 2 cánh nhôm xingfa')" class="block py-2 hover:text-khGold-600">+ Cửa nhôm xingfa 2 cánh</a>
                        <a href="#san-pham" onclick="closeMobileMenu(); highlightProduct('Cửa đi quay mở 3 cánh nhôm xingfa')" class="block py-2 hover:text-khGold-600">+ Cửa nhôm xingfa 3 cánh</a>
                        <a href="#san-pham" onclick="closeMobileMenu(); highlightProduct('Cửa đi quay mở 4 cánh nhôm xingfa')" class="block py-2 hover:text-khGold-600">+ Cửa nhôm xingfa 4 cánh</a>
                        <a href="#san-pham" onclick="closeMobileMenu(); highlightProduct('Cửa Nhôm Xingfa Cửa Đi Xếp Trượt')" class="block py-2 hover:text-khGold-600">+ Cửa nhôm xingfa 5 cánh</a>
                    </div>
                </div>

                <a href="#bao-gia" onclick="closeMobileMenu(); switchPriceTab('kinh')" class="block px-3 py-2.5 rounded-lg hover:bg-khNavy-50">Cửa kính cường lực</a>

                <!-- Accordion Sản phẩm -->
                <div class="border-y border-slate-100 py-1">
                    <button type="button" onclick="toggleMobileSub('sub-sanpham')" class="w-full flex items-center justify-between px-3 py-2.5 rounded-lg hover:bg-khNavy-50 text-left font-semibold">
                        <span>Sản phẩm</span>
                        <i id="icon-sub-sanpham" class="fa-solid fa-chevron-down text-xs transition-transform"></i>
                    </button>
                    <div id="sub-sanpham" class="hidden pl-5 pb-1 space-y-1 text-xs text-slate-600">
                        <a href="#danh-muc" onclick="closeMobileMenu(); selectCategoryNotice('Cửa nhôm xingfa')" class="block py-2 hover:text-khGold-600">+ Cửa nhôm xingfa</a>
                        <a href="#danh-muc" onclick="closeMobileMenu(); selectCategoryNotice('Cửa nhựa lõi thép')" class="block py-2 hover:text-khGold-600">+ Cửa nhựa lõi thép</a>
                        <a href="#danh-muc" onclick="closeMobileMenu(); selectCategoryNotice('Cửa kính tự động')" class="block py-2 hover:text-khGold-600">+ Cửa kính tự động</a>
                        <a href="#danh-muc" onclick="closeMobileMenu(); selectCategoryNotice('Cầu thang kính')" class="block py-2 hover:text-khGold-600">+ Cầu thang kính</a>
                        <a href="#danh-muc" onclick="closeMobileMenu(); selectCategoryNotice('Kính ốp bếp')" class="block py-2 hover:text-khGold-600">+ Kính ốp bếp</a>
                        <a href="#danh-muc" onclick="closeMobileMenu(); selectCategoryNotice('Phòng tắm kính')" class="block py-2 hover:text-khGold-600">+ Phòng tắm kính</a>
                    </div>
                </div>

                <a href="#cong-trinh" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg hover:bg-khNavy-50">Công trình</a>
                <a href="#bao-gia" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg hover:bg-khNavy-50">Báo giá</a>
                <a href="#tin-tuc" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg hover:bg-khNavy-50">Tin tức</a>
                <a href="#lien-he" onclick="closeMobileMenu()" class="block px-3 py-2.5 rounded-lg hover:bg-khNavy-50">Liên hệ</a>
            </div>
        </div>
    </header>

    <!-- =========================================================================
         3. BANNER TỰ TRƯỢT 2 SLIDE BẰNG KÍCH THƯỚC NHAU (UX BUILDER SLIDER)
         - Chữ và hình ảnh nằm gọn hoàn toàn bên trong, cách xa viền ảnh banner
         - Tối ưu hiển thị rõ ràng, đầy đủ chữ trên cả Điện thoại và Máy tính
    ========================================================================== -->
    <section id="trang-chu" class="bg-khNavy-50 py-3 sm:py-4">
        <div class="kh-container">
            <div id="hero-slider" class="relative overflow-hidden rounded-xl shadow-md bg-khNavy-800">
                <!-- Track chứa 2 Banner có chiều cao đồng nhất tuyệt đối -->
                <div id="hero-track" class="kh-slides-track">

                    <!-- BANNER 1 -->
                    <div class="kh-slide-item">
                        <div class="relative w-full min-h-[380px] sm:min-h-[410px] lg:min-h-[440px] flex items-center bg-gradient-to-br from-khNavy-900 via-khNavy-800 to-khNavy-600 overflow-hidden">
                            <!-- Họa tiết hình học kiến trúc tinh tế -->
                            <div class="absolute inset-0 opacity-15 pointer-events-none">
                                <svg class="w-full h-full" preserveAspectRatio="none" viewBox="0 0 1200 450" fill="none">
                                    <path d="M0 360L1200 80V450H0V360Z" fill="#E59500"/>
                                    <line x1="150" y1="0" x2="150" y2="450" stroke="#FFFFFF" stroke-width="1"/>
                                    <line x1="450" y1="0" x2="450" y2="450" stroke="#FFFFFF" stroke-width="1"/>
                                    <line x1="750" y1="0" x2="750" y2="450" stroke="#FFFFFF" stroke-width="1"/>
                                </svg>
                            </div>

                            <!-- Vùng an toàn cách xa 4 viền banner (px-8 sm:px-14 md:px-20 py-10 sm:py-12) -->
                            <div class="relative z-10 w-full px-8 sm:px-14 md:px-20 py-10 sm:py-12 grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                                <div class="lg:col-span-7 space-y-3 sm:space-y-4 text-left">
                                    <p class="text-[11px] sm:text-xs font-bold tracking-widest uppercase text-khGold-400">
                                        CÔNG TY TNHH ĐẦU TƯ PHÁT TRIỂN KHANG HUY
                                    </p>
                                    <h1 class="text-xl sm:text-3xl lg:text-4xl font-extrabold text-white leading-snug">
                                        CỬA NHÔM XINGFA NHẬP KHẨU CHÍNH HÃNG TẠI ĐÀ NẴNG
                                    </h1>
                                    <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-2xl">
                                        Chuyên thiết kế, sản xuất &amp; thi công lắp đặt trọn gói cửa nhôm Xingfa tem đỏ Quảng Đông, phụ kiện Kinlong đồng bộ, bảo hành dài hạn, giá xuất xưởng tối ưu.
                                    </p>
                                    <div class="pt-1 flex flex-wrap items-center gap-3">
                                        <a href="#form-bao-gia" class="inline-flex items-center gap-2 px-4 sm:px-5 py-2.5 rounded-lg bg-khGold-500 hover:bg-khGold-600 text-white text-xs sm:text-sm font-bold shadow transition">
                                            <i class="fa-solid fa-file-invoice-dollar"></i>
                                            Nhận báo giá ngay
                                        </a>
                                        <a href="#san-pham" class="inline-flex items-center gap-2 px-4 sm:px-5 py-2.5 rounded-lg border border-white/40 hover:bg-white/10 text-white text-xs sm:text-sm font-semibold transition">
                                            Xem mẫu sản phẩm
                                        </a>
                                    </div>
                                </div>

                                <!-- Khung ảnh sản phẩm thực tế đặt gọn trong Banner 1 -->
                                <div class="hidden lg:flex lg:col-span-5 justify-end">
                                    <div class="w-full max-w-[400px] aspect-[16/10] rounded-xl overflow-hidden border-2 border-khGold-400/70 shadow-2xl bg-khNavy-900">
                                        <img src="https://drive.google.com/thumbnail?id=1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX&sz=w1000"
                                             data-gdrive="1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX"
                                             data-fallback="Cua+Nhom+Xingfa+Khang+Huy"
                                             onerror="handleDriveFallback(this)"
                                             alt="Cửa nhôm Xingfa nhập khẩu Khang Huy"
                                             class="w-full h-full object-cover">
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                    <!-- BANNER 2 (CÙNG KÍCH THƯỚC TUYỆT ĐỐI VỚI BANNER 1) -->
                    <div class="kh-slide-item">
                        <div class="relative w-full min-h-[380px] sm:min-h-[410px] lg:min-h-[440px] flex items-center bg-gradient-to-br from-[#072940] via-[#0E4468] to-[#165A85] overflow-hidden">
                            <!-- Họa tiết hình học kiến trúc tinh tế -->
                            <div class="absolute inset-0 opacity-15 pointer-events-none">
                                <svg class="w-full h-full" preserveAspectRatio="none" viewBox="0 0 1200 450" fill="none">
                                    <path d="M0 90L1200 370V450H0V90Z" fill="#F5B041"/>
                                    <circle cx="1050" cy="90" r="180" stroke="#FFFFFF" stroke-width="1.5"/>
                                    <circle cx="1050" cy="90" r="120" stroke="#E59500" stroke-width="1"/>
                                </svg>
                            </div>

                            <!-- Vùng an toàn cách xa 4 viền banner (px-8 sm:px-14 md:px-20 py-10 sm:py-12) -->
                            <div class="relative z-10 w-full px-8 sm:px-14 md:px-20 py-10 sm:py-12 grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                                <div class="lg:col-span-7 space-y-3 sm:space-y-4 text-left">
                                    <p class="text-[11px] sm:text-xs font-bold tracking-widest uppercase text-khGold-400">
                                        THI CÔNG CÔNG TRÌNH KHÁCH SẠN &amp; BIỆT THỰ ĐÀ NẴNG
                                    </p>
                                    <h2 class="text-xl sm:text-3xl lg:text-4xl font-extrabold text-white leading-snug">
                                        CỬA KÍNH CƯỜNG LỰC, CẦU THANG &amp; PHÒNG TẮM KÍNH
                                    </h2>
                                    <p class="text-xs sm:text-sm md:text-base text-slate-200 leading-relaxed max-w-2xl">
                                        Giải pháp nhôm kính tổng thể cho nhà phố, resort, khách sạn chuẩn thẩm mỹ hiện đại. Khảo sát đo đạc tận nơi miễn phí — tiến độ chuẩn xác — hậu mãi tận tâm.
                                    </p>
                                    <div class="pt-1 flex flex-wrap items-center gap-3">
                                        <a href="#cong-trinh" class="inline-flex items-center gap-2 px-4 sm:px-5 py-2.5 rounded-lg bg-khGold-500 hover:bg-khGold-600 text-white text-xs sm:text-sm font-bold shadow transition">
                                            <i class="fa-solid fa-building"></i>
                                            Xem công trình đã thi công
                                        </a>
                                        <a href="tel:0915493033" class="inline-flex items-center gap-2 px-4 sm:px-5 py-2.5 rounded-lg border border-white/40 hover:bg-white/10 text-white text-xs sm:text-sm font-semibold transition">
                                            <i class="fa-solid fa-phone"></i>
                                            0915.493.033
                                        </a>
                                    </div>
                                </div>

                                <!-- Khung ảnh dự án thực tế đặt gọn trong Banner 2 -->
                                <div class="hidden lg:flex lg:col-span-5 justify-end">
                                    <div class="w-full max-w-[400px] aspect-[16/10] rounded-xl overflow-hidden border-2 border-khGold-400/70 shadow-2xl bg-khNavy-900">
                                        <img src="https://drive.google.com/thumbnail?id=1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ&sz=w1000"
                                             data-gdrive="1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ"
                                             data-fallback="Du+An+Khang+Huy+Da+Nang"
                                             onerror="handleDriveFallback(this)"
                                             alt="Thi công dự án nhôm kính tại Đà Nẵng - Khang Huy"
                                             class="w-full h-full object-cover">
                                    </div>
                                </div>
                            </div>
                        </div>
                    </div>

                </div>

                <!-- Nút điều hướng trái / phải gọn sát mép không đè chữ -->
                <button type="button" onclick="moveSlide(-1)" aria-label="Banner trước" class="absolute left-2 sm:left-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/30 hover:bg-khGold-500 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-left text-xs sm:text-sm"></i>
                </button>
                <button type="button" onclick="moveSlide(1)" aria-label="Banner sau" class="absolute right-2 sm:right-3 top-1/2 -translate-y-1/2 z-20 w-7 h-7 sm:w-9 sm:h-9 rounded-full bg-black/30 hover:bg-khGold-500 text-white flex items-center justify-center transition">
                    <i class="fa-solid fa-chevron-right text-xs sm:text-sm"></i>
                </button>

                <!-- Chấm chỉ báo 2 banner -->
                <div class="absolute bottom-3 left-1/2 -translate-x-1/2 z-20 flex items-center gap-2">
                    <button type="button" onclick="goToSlide(0)" id="dot-0" aria-label="Slide 1" class="w-6 h-2 rounded-full bg-khGold-500 transition-all"></button>
                    <button type="button" onclick="goToSlide(1)" id="dot-1" aria-label="Slide 2" class="w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all"></button>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         4. DANH MỤC SẢN PHẨM NỔI BẬT (UX BUILDER ROW - 6 CỘT DESKTOP / 2 CỘT MOBILE)
         - Chữ danh mục nhỏ gọn, dễ nhìn trên cả máy tính và điện thoại
    ========================================================================== -->
    <section id="danh-muc" class="py-8 sm:py-10 bg-white">
        <div class="kh-container">
            <div class="text-center mb-6 sm:mb-8">
                <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-khNavy-800 tracking-tight">
                    Danh Mục Sản Phẩm
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-2">
                    Cung cấp và thi công đồng bộ các hạng mục nhôm kính cao cấp cho mọi công trình
                </p>
            </div>

            <!-- 6 Danh mục sản phẩm chuẩn web mẫu -->
            <div id="category-grid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4">
                <!-- Được render từ JS với đúng ảnh Google Drive người dùng cung cấp -->
            </div>
        </div>
    </section>

    <!-- =========================================================================
         5. SẢN PHẨM CỬA NHÔM XINGFA NỔI BẬT (CÓ GIÁ & GIẢM GIÁ % GÓC TRÊN BÊN TRÁI)
         - Chia đúng 2 cột trên điện thoại, tên sản phẩm hiển thị đầy đủ không tràn/thiếu chữ
    ========================================================================== -->
    <section id="san-pham" class="py-8 sm:py-12 bg-khNavy-50/70 border-y border-slate-200/70">
        <div class="kh-container">
            <div class="text-center mb-6 sm:mb-8">
                <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-khNavy-800 tracking-tight">
                    Cửa Nhôm Xingfa Nổi Bật
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-2">
                    Nhôm Xingfa nhập khẩu tem đỏ Quảng Đông dày 1.4mm – 2.0mm, kính cường lực &amp; phụ kiện chính hãng
                </p>
            </div>

            <!-- Grid sản phẩm: Mobile 2 cột chuẩn, Tablet/Desktop 3 cột rộng đẹp -->
            <div id="product-grid" class="grid grid-cols-2 md:grid-cols-3 gap-2.5 sm:gap-5">
                <!-- Render tự động 6 sản phẩm từ JS với đúng link ảnh Drive -->
            </div>

            <!-- Cam kết dịch vụ ngắn gọn chuẩn Flatsome -->
            <div class="mt-8 grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
                <div class="bg-white rounded-xl p-3.5 sm:p-4 border border-slate-200 flex items-center gap-3">
                    <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-lg bg-khNavy-50 text-khNavy-800 flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-shield-halved text-base sm:text-lg text-khGold-600"></i>
                    </div>
                    <div class="min-w-0">
                        <p class="text-xs sm:text-sm font-bold text-khNavy-800 leading-tight">Nhôm Chính Hãng</p>
                        <p class="text-[11px] text-slate-500 mt-0.5">Tem đỏ Quảng Đông 100%</p>
                    </div>
                </div>
                <div class="bg-white rounded-xl p-3.5 sm:p-4 border border-slate-200 flex items-center gap-3">
                    <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-lg bg-khNavy-50 text-khNavy-800 flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-ruler-combined text-base sm:text-lg text-khGold-600"></i>
                    </div>
                    <div class="min-w-0">
                        <p class="text-xs sm:text-sm font-bold text-khNavy-800 leading-tight">Đo Đạc Miễn Phí</p>
                        <p class="text-[11px] text-slate-500 mt-0.5">Khảo sát tận nơi Đà Nẵng</p>
                    </div>
                </div>
                <div class="bg-white rounded-xl p-3.5 sm:p-4 border border-slate-200 flex items-center gap-3">
                    <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-lg bg-khNavy-50 text-khNavy-800 flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-award text-base sm:text-lg text-khGold-600"></i>
                    </div>
                    <div class="min-w-0">
                        <p class="text-xs sm:text-sm font-bold text-khNavy-800 leading-tight">Bảo Hành Dài Hạn</p>
                        <p class="text-[11px] text-slate-500 mt-0.5">Hỗ trợ bảo trì 24/7</p>
                    </div>
                </div>
                <div class="bg-white rounded-xl p-3.5 sm:p-4 border border-slate-200 flex items-center gap-3">
                    <div class="w-9 h-9 sm:w-10 sm:h-10 rounded-lg bg-khNavy-50 text-khNavy-800 flex items-center justify-center shrink-0">
                        <i class="fa-solid fa-hand-holding-dollar text-base sm:text-lg text-khGold-600"></i>
                    </div>
                    <div class="min-w-0">
                        <p class="text-xs sm:text-sm font-bold text-khNavy-800 leading-tight">Giá Tận Xưởng</p>
                        <p class="text-[11px] text-slate-500 mt-0.5">Ưu đãi chiết khấu công trình</p>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         6. GIỚI THIỆU CÔNG TY KHANG HUY & THÔNG SỐ NĂNG LỰC (UX BUILDER)
    ========================================================================== -->
    <section id="gioi-thieu" class="py-10 sm:py-12 bg-white">
        <div class="kh-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                <div class="lg:col-span-7 space-y-4">
                    <p class="text-xs font-bold uppercase tracking-wider text-khGold-600">Về Chúng Tôi</p>
                    <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold text-khNavy-800 leading-snug">
                        CÔNG TY TNHH ĐẦU TƯ PHÁT TRIỂN KHANG HUY
                    </h2>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        <strong>Khang Huy (khanghuy.com)</strong> là đơn vị chuyên thiết kế, gia công sản xuất và thi công lắp đặt trọn gói các hạng mục nhôm kính cao cấp tại Đà Nẵng và khu vực Miền Trung. Với nhà xưởng hiện đại đặt tại <strong>Lô CN1, CCN Thường Tín, Phường Điện Bàn Đông, TP Đà Nẵng</strong>, chúng tôi trực tiếp sản xuất giúp kiểm soát chặt chẽ chất lượng và tối ưu chi phí cho khách hàng.
                    </p>
                    <p class="text-sm text-slate-600 leading-relaxed">
                        Các dòng sản phẩm chủ lực gồm: <strong>Cửa nhôm Xingfa nhập khẩu</strong>, <strong>Cửa kính cường lực</strong>, <strong>Cửa nhựa lõi thép</strong>, <strong>Cửa kính tự động</strong>, <strong>Cầu thang kính</strong>, <strong>Kính ốp bếp</strong> và <strong>Phòng tắm kính</strong>. Phương châm hoạt động của Khang Huy là <em>"Uy tín – Chất lượng – Thẩm mỹ – Bền vững cho mọi công trình"</em>.
                    </p>

                    <!-- 4 Chỉ số nổi bật -->
                    <div class="grid grid-cols-2 sm:grid-cols-4 gap-3 pt-2">
                        <div class="rounded-xl bg-khNavy-50 p-3.5 text-center border border-khNavy-100">
                            <div class="text-xl sm:text-2xl font-extrabold text-khNavy-800">150+</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Dự án hoàn thành</div>
                        </div>
                        <div class="rounded-xl bg-khNavy-50 p-3.5 text-center border border-khNavy-100">
                            <div class="text-xl sm:text-2xl font-extrabold text-khNavy-800">50+</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Kỹ thuật kinh nghiệm</div>
                        </div>
                        <div class="rounded-xl bg-khNavy-50 p-3.5 text-center border border-khNavy-100">
                            <div class="text-xl sm:text-2xl font-extrabold text-khNavy-800">100+</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Mẫu cửa chất lượng</div>
                        </div>
                        <div class="rounded-xl bg-khNavy-50 p-3.5 text-center border border-khNavy-100">
                            <div class="text-xl sm:text-2xl font-extrabold text-khGold-600">100%</div>
                            <div class="text-[11px] sm:text-xs text-slate-600 mt-0.5">Khách hàng hài lòng</div>
                        </div>
                    </div>
                </div>

                <div class="lg:col-span-5">
                    <div class="rounded-2xl overflow-hidden shadow-lg border border-slate-200 aspect-[4/3] bg-slate-100">
                        <img src="https://drive.google.com/thumbnail?id=1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-&sz=w1000"
                             data-gdrive="1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-"
                             data-fallback="Nha+Xuong+Khang+Huy"
                             onerror="handleDriveFallback(this)"
                             alt="Thi công cửa nhôm Xingfa chính hãng Khang Huy"
                             class="w-full h-full object-cover">
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         7. BẢNG BÁO GIÁ THAM KHẢO (CỬA NHÔM XINGFA & CỬA KÍNH CƯỜNG LỰC)
    ========================================================================== -->
    <section id="bao-gia" class="py-10 sm:py-12 bg-khNavy-50/70 border-y border-slate-200/70">
        <div class="kh-container">
            <div class="text-center mb-6">
                <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-khNavy-800 tracking-tight">
                    Bảng Báo Giá Tham Khảo
                </h2>
                <p class="text-xs sm:text-sm text-slate-600 mt-2">
                    Đơn giá minh bạch, cạnh tranh trực tiếp từ xưởng sản xuất Khang Huy Đà Nẵng
                </p>
            </div>

            <!-- Tabs chuyển đổi Báo giá -->
            <div class="flex justify-center gap-2 sm:gap-3 mb-5">
                <button type="button" id="tab-price-xingfa" onclick="switchPriceTab('xingfa')" class="px-4 py-2 rounded-lg text-xs sm:text-sm font-bold bg-khNavy-800 text-white shadow transition">
                    Báo giá Cửa Nhôm Xingfa
                </button>
                <button type="button" id="tab-price-kinh" onclick="switchPriceTab('kinh')" class="px-4 py-2 rounded-lg text-xs sm:text-sm font-bold bg-white text-khNavy-800 border border-slate-200 hover:bg-khNavy-50 transition">
                    Báo giá Cửa Kính Cường Lực
                </button>
            </div>

            <!-- Bảng giá Nhôm Xingfa -->
            <div id="table-price-xingfa" class="bg-white rounded-xl shadow-sm border border-slate-200 overflow-x-auto">
                <table class="w-full text-left border-collapse text-xs sm:text-sm">
                    <thead>
                        <tr class="bg-khNavy-800 text-white">
                            <th class="py-3 px-3 sm:px-4 font-semibold">STT</th>
                            <th class="py-3 px-3 sm:px-4 font-semibold">Hạng Mục Cửa Nhôm Xingfa</th>
                            <th class="py-3 px-3 sm:px-4 font-semibold">Hệ Nhôm &amp; Độ Dày</th>
                            <th class="py-3 px-3 sm:px-4 font-semibold text-right">Đơn Giá (VNĐ/m²)</th>
                        </tr>
                    </thead>
                    <tbody class="divide-y divide-slate-100">
                        <tr class="hover:bg-khNavy-50/50">
                            <td class="py-3 px-3 sm:px-4 font-semibold">01</td>
                            <td class="py-3 px-3 sm:px-4 font-medium text-khNavy-800">Vách kính cố định nhôm Xingfa</td>
                            <td class="py-3 px-3 sm:px-4 text-slate-600">Hệ 55 dày 1.4mm</td>
                            <td class="py-3 px-3 sm:px-4 text-right font-bold text-khGold-600">1.550.000 đ</td>
                        </tr>
                        <tr class="hover:bg-khNavy-50/50">
                            <td class="py-3 px-3 sm:px-4 font-semibold">02</td>
                            <td class="py-3 px-3 sm:px-4 font-medium text-khNavy-800">Cửa sổ mở hất / mở quay 1-2 cánh</td>
                            <td class="py-3 px-3 sm:px-4 text-slate-600">Hệ 55 dày 1.4mm</td>
                            <td class="py-3 px-3 sm:px-4 text-right font-bold text-khGold-600">1.850.000 đ</td>
                        </tr>
                        <tr class="hover:bg-khNavy-50/50">
                            <td class="py-3 px-3 sm:px-4 font-semibold">03</td>
                            <td class="py-3 px-3 sm:px-4 font-medium text-khNavy-800">Cửa đi mở quay 1 cánh, 2 cánh, 3 cánh, 4 cánh</td>
                            <td class="py-3 px-3 sm:px-4 text-slate-600">Hệ 55 dày 2.0mm</td>
                            <td class="py-3 px-3 sm:px-4 text-right font-bold text-khGold-600">1.950.000 đ</td>
                        </tr>
                        <tr class="hover:bg-khNavy-50/50">
                            <td class="py-3 px-3 sm:px-4 font-semibold">04</td>
                            <td class="py-3 px-3 sm:px-4 font-medium text-khNavy-800">Cửa đi mở trượt lùa 2 cánh, 4 cánh</td>
                            <td class="py-3 px-3 sm:px-4 text-slate-600">Hệ 93 dày 2.0mm</td>
                            <td class="py-3 px-3 sm:px-4 text-right font-bold text-khGold-600">1.900.000 đ</td>
                        </tr>
                        <tr class="hover:bg-khNavy-50/50">
                            <td class="py-3 px-3 sm:px-4 font-semibold">05</td>
                            <td class="py-3 px-3 sm:px-4 font-medium text-khNavy-800">Cửa đi xếp trượt gấp 4 – 5 – 6 cánh</td>
                            <td class="py-3 px-3 sm:px-4 text-slate-600">Hệ 63 dày 2.0mm</td>
                            <td class="py-3 px-3 sm:px-4 text-right font-bold text-khGold-600">2.100.000 đ</td>
                        </tr>
                    </tbody>
                </table>
            </div>

            <!-- Bảng giá Cửa Kính Cường Lực -->
            <div id="table-price-kinh" class="hidden bg-white rounded-xl shadow-sm border border-slate-200 overflow-x-auto">
                <table class="w-full text-left border-collapse text-xs sm:text-sm">
                    <thead>
                        <tr class="bg-khNavy-800 text-white">
                            <th class="py-3 px-3 sm:px-4 font-semibold">STT</th>
                            <th class="py-3 px-3 sm:px-4 font-semibold">Hạng Mục Kính Cường Lực</th>
                            <th class="py-3 px-3 sm:px-4 font-semibold">Thông Số Tiêu Chuẩn</th>
                            <th class="py-3 px-3 sm:px-4 font-semibold text-right">Đơn Giá (VNĐ/m²)</th>
                        </tr>
                    </thead>
                    <tbody class="divide-y divide-slate-100">
                        <tr class="hover:bg-khNavy-50/50">
                            <td class="py-3 px-3 sm:px-4 font-semibold">01</td>
                            <td class="py-3 px-3 sm:px-4 font-medium text-khNavy-800">Kính cường lực 8mm (8 ly)</td>
                            <td class="py-3 px-3 sm:px-4 text-slate-600">Phôi kính Việt Nhật</td>
                            <td class="py-3 px-3 sm:px-4 text-right font-bold text-khGold-600">550.000 đ</td>
                        </tr>
                        <tr class="hover:bg-khNavy-50/50">
                            <td class="py-3 px-3 sm:px-4 font-semibold">02</td>
                            <td class="py-3 px-3 sm:px-4 font-medium text-khNavy-800">Kính cường lực 10mm (10 ly) - Cửa bản lề sàn</td>
                            <td class="py-3 px-3 sm:px-4 text-slate-600">Phôi kính Việt Nhật</td>
                            <td class="py-3 px-3 sm:px-4 text-right font-bold text-khGold-600">650.000 đ</td>
                        </tr>
                        <tr class="hover:bg-khNavy-50/50">
                            <td class="py-3 px-3 sm:px-4 font-semibold">03</td>
                            <td class="py-3 px-3 sm:px-4 font-medium text-khNavy-800">Kính cường lực 12mm (12 ly) - Mặt tiền lớn</td>
                            <td class="py-3 px-3 sm:px-4 text-slate-600">Phôi kính Việt Nhật</td>
                            <td class="py-3 px-3 sm:px-4 text-right font-bold text-khGold-600">780.000 đ</td>
                        </tr>
                        <tr class="hover:bg-khNavy-50/50">
                            <td class="py-3 px-3 sm:px-4 font-semibold">04</td>
                            <td class="py-3 px-3 sm:px-4 font-medium text-khNavy-800">Phòng tắm kính / Cabin tắm kính 10mm</td>
                            <td class="py-3 px-3 sm:px-4 text-slate-600">Phụ kiện Inox 304 đồng bộ</td>
                            <td class="py-3 px-3 sm:px-4 text-right font-bold text-khGold-600">720.000 đ</td>
                        </tr>
                        <tr class="hover:bg-khNavy-50/50">
                            <td class="py-3 px-3 sm:px-4 font-semibold">05</td>
                            <td class="py-3 px-3 sm:px-4 font-medium text-khNavy-800">Kính ốp bếp cường lực 8mm sơn màu</td>
                            <td class="py-3 px-3 sm:px-4 text-slate-600">Tính theo mét dài</td>
                            <td class="py-3 px-3 sm:px-4 text-right font-bold text-khGold-600">750.000 đ/md</td>
                        </tr>
                    </tbody>
                </table>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         8. CÁC DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG (6 DỰ ÁN VỚI ẢNH THỰC TẾ TỪ DRIVE)
    ========================================================================== -->
    <section id="cong-trinh" class="py-10 sm:py-12 bg-white">
        <div class="kh-container">
            <div class="text-center mb-6 sm:mb-8">
                <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-khNavy-800 tracking-tight">
                    Các Dự Án Tiêu Biểu Tại Đà Nẵng
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-2">
                    Dấu ấn chất lượng nhôm kính Khang Huy tại các khách sạn, resort và công trình lớn
                </p>
            </div>

            <div id="project-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-3 gap-4 sm:gap-5">
                <!-- Render 6 dự án thực tế từ JS -->
            </div>
        </div>
    </section>

    <!-- =========================================================================
         9. FORM YÊU CẦU TƯ VẤN & BÁO GIÁ NGAY TRÊN TRANG CHỦ (UX BUILDER)
    ========================================================================== -->
    <section id="form-bao-gia" class="py-10 sm:py-12 bg-khNavy-800 text-white">
        <div class="kh-container">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 lg:gap-10 items-center">
                <div class="lg:col-span-5 space-y-4">
                    <p class="text-xs font-bold uppercase tracking-widest text-khGold-400">Đăng Ký Tư Vấn Miễn Phí</p>
                    <h2 class="text-xl sm:text-2xl lg:text-3xl font-extrabold leading-snug">
                        GỬI YÊU CẦU &amp; NHẬN BÁO GIÁ CHI TIẾT TRONG 15 PHÚT
                    </h2>
                    <p class="text-xs sm:text-sm text-slate-200 leading-relaxed">
                        Để lại thông tin kích thước hoặc hạng mục bạn quan tâm, đội ngũ kỹ sư của <strong>Công ty TNHH Đầu Tư Phát Triển Khang Huy</strong> sẽ liên hệ tư vấn mẫu cửa phù hợp và gửi bảng dự toán chi tiết hoàn toàn miễn phí.
                    </p>
                    <ul class="space-y-2 text-xs sm:text-sm text-slate-100">
                        <li class="flex items-center gap-2.5"><i class="fa-solid fa-circle-check text-khGold-400"></i> Khảo sát, đo đạc thực tế tận công trình miễn phí</li>
                        <li class="flex items-center gap-2.5"><i class="fa-solid fa-circle-check text-khGold-400"></i> Cam kết nhôm Xingfa &amp; kính cường lực chuẩn chất lượng</li>
                        <li class="flex items-center gap-2.5"><i class="fa-solid fa-circle-check text-khGold-400"></i> Hỗ trợ hotline trực tiếp: <a href="tel:0915493033" class="font-bold text-khGold-400 underline">0915.493.033</a></li>
                    </ul>
                </div>

                <div class="lg:col-span-7">
                    <form id="quote-form" class="bg-white text-slate-800 rounded-2xl p-5 sm:p-7 shadow-xl space-y-4">
                        <h3 class="text-base sm:text-lg font-extrabold text-khNavy-800 border-b border-slate-100 pb-2.5">
                            Thông Tin Yêu Cầu Báo Giá
                        </h3>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                            <div>
                                <label for="q-name" class="block text-xs font-semibold text-slate-700 mb-1">Họ và tên *</label>
                                <input id="q-name" type="text" required placeholder="Nhập họ tên của bạn" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-khNavy-700 focus:ring-2 focus:ring-khNavy-100 outline-none transition">
                            </div>
                            <div>
                                <label for="q-phone" class="block text-xs font-semibold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                <input id="q-phone" type="tel" required placeholder="Ví dụ: 0915 493 033" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-khNavy-700 focus:ring-2 focus:ring-khNavy-100 outline-none transition">
                            </div>
                        </div>
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3.5">
                            <div>
                                <label for="q-category" class="block text-xs font-semibold text-slate-700 mb-1">Hạng mục quan tâm</label>
                                <select id="q-category" class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 bg-white focus:border-khNavy-700 focus:ring-2 focus:ring-khNavy-100 outline-none transition">
                                    <option value="Cửa nhôm Xingfa">Cửa nhôm Xingfa</option>
                                    <option value="Cửa kính cường lực">Cửa kính cường lực</option>
                                    <option value="Cửa nhựa lõi thép">Cửa nhựa lõi thép</option>
                                    <option value="Cửa kính tự động">Cửa kính tự động</option>
                                    <option value="Cầu thang kính">Cầu thang kính</option>
                                    <option value="Kính ốp bếp">Kính ốp bếp</option>
                                    <option value="Phòng tắm kính">Phòng tắm kính</option>
                                </select>
                            </div>
                            <div>
                                <label for="q-address" class="block text-xs font-semibold text-slate-700 mb-1">Khu vực thi công</label>
                                <input id="q-address" type="text" placeholder="Quận/Huyện, Đà Nẵng..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-khNavy-700 focus:ring-2 focus:ring-khNavy-100 outline-none transition">
                            </div>
                        </div>
                        <div>
                            <label for="q-note" class="block text-xs font-semibold text-slate-700 mb-1">Nội dung yêu cầu (Số lượng cửa, kích thước ước tính...)</label>
                            <textarea id="q-note" rows="3" placeholder="Mô tả sơ bộ nhu cầu để Khang Huy báo giá chính xác nhất..." class="w-full px-3.5 py-2.5 text-sm rounded-lg border border-slate-300 focus:border-khNavy-700 focus:ring-2 focus:ring-khNavy-100 outline-none transition"></textarea>
                        </div>
                        <button type="submit" class="w-full py-3 rounded-lg bg-khGold-500 hover:bg-khGold-600 text-white font-bold text-sm shadow-md transition flex items-center justify-center gap-2">
                            <i class="fa-solid fa-paper-plane"></i>
                            GỬI YÊU CẦU BÁO GIÁ NGAY
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         10. DANH MỤC CÁC BÀI VIẾT & TIN TỨC NỔI BẬT TRÊN TRANG CHỦ
    ========================================================================== -->
    <section id="tin-tuc" class="py-10 sm:py-12 bg-white">
        <div class="kh-container">
            <div class="text-center mb-6 sm:mb-8">
                <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-khNavy-800 tracking-tight">
                    Tin Tức &amp; Kiến Thức Nhôm Kính
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-2">
                    Cập nhật kinh nghiệm lựa chọn, lắp đặt và bảo dưỡng cửa nhôm Xingfa, kính cường lực
                </p>
            </div>

            <div id="articles-grid" class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-4 sm:gap-5">
                <!-- Render 4 bài viết nổi bật từ JS -->
            </div>
        </div>
    </section>

    <!-- =========================================================================
         11. ĐỐI TÁC CỦA CHÚNG TÔI (6 ẢNH ĐỐI TÁC TỪ GOOGLE DRIVE)
    ========================================================================== -->
    <section class="py-8 sm:py-10 bg-khNavy-50/70 border-y border-slate-200/70">
        <div class="kh-container">
            <div class="text-center mb-6">
                <h2 class="flatsome-heading text-base sm:text-xl font-extrabold uppercase text-khNavy-800 tracking-tight">
                    Đối Tác Của Chúng Tôi
                </h2>
            </div>
            <div id="partner-grid" class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-3 sm:gap-4 items-center">
                <!-- Render 6 logo đối tác từ JS -->
            </div>
        </div>
    </section>

    <!-- =========================================================================
         12. BẢN ĐỒ GOOGLE MAPS & FANPAGE FACEBOOK NGAY TRÊN TRANG CHỦ
    ========================================================================== -->
    <section id="lien-he" class="py-10 sm:py-12 bg-white">
        <div class="kh-container">
            <div class="text-center mb-6 sm:mb-8">
                <h2 class="flatsome-heading text-lg sm:text-2xl font-extrabold uppercase text-khNavy-800 tracking-tight">
                    Bản Đồ Chỉ Đường &amp; Kết Nối Fanpage
                </h2>
                <p class="text-xs sm:text-sm text-slate-500 mt-2">
                    Lô CN1, CCN Thường Tín, Phường Điện Bàn Đông, TP Đà Nẵng — Hotline: 0915.493.033
                </p>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 sm:gap-6 items-stretch">
                <!-- Cột Trái: Google Maps trực tiếp ra trang chủ -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
                    <div class="px-4 py-3 bg-khNavy-800 text-white flex items-center justify-between gap-2">
                        <div class="flex items-center gap-2 text-xs sm:text-sm font-bold truncate">
                            <i class="fa-solid fa-map-location-dot text-khGold-400"></i>
                            <span class="truncate">Bản Đồ Xưởng &amp; Văn Phòng Khang Huy</span>
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=Lô+CN1,+CCN+Thường+Tín,+Phường+Điện+Bàn+Đông,+Đà+Nẵng" target="_blank" rel="noopener noreferrer" class="text-[11px] font-semibold text-khGold-400 hover:text-white shrink-0 underline">
                            Mở Google Maps
                        </a>
                    </div>
                    <div class="w-full h-[290px] sm:h-[340px] bg-slate-100 relative">
                        <iframe
                            title="Bản đồ Công ty TNHH Đầu Tư Phát Triển Khang Huy"
                            src="https://maps.google.com/maps?q=C%E1%BB%A5m%20C%C3%B4ng%20Nghi%E1%BB%87p%20Th%C6%B0%E1%BB%9Dng%20T%C3%ADn%2C%20%C4%90i%E1%BB%87n%20B%C3%A0n%20%C4%90%C3%B4ng%2C%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=14&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                    <div class="px-4 py-3 bg-slate-50 border-t border-slate-200 text-xs text-slate-600 flex flex-wrap items-center justify-between gap-2">
                        <span><i class="fa-solid fa-location-dot text-khGold-600 mr-1"></i> Lô CN1, CCN Thường Tín, Phường Điện Bàn Đông, TP Đà Nẵng</span>
                        <a href="tel:0915493033" class="font-bold text-khNavy-800 hover:text-khGold-600">Hotline: 0915.493.033</a>
                    </div>
                </div>

                <!-- Cột Phải: Fanpage Facebook đặt trực tiếp trên trang chủ -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 shadow-sm overflow-hidden flex flex-col">
                    <div class="px-4 py-3 bg-[#1877F2] text-white flex items-center justify-between">
                        <div class="flex items-center gap-2 text-xs sm:text-sm font-bold">
                            <i class="fa-brands fa-facebook text-base"></i>
                            <span>Fanpage Facebook Chính Thức</span>
                        </div>
                        <span class="text-[11px] bg-white/20 px-2 py-0.5 rounded">khanghuy.com</span>
                    </div>

                    <!-- Khung mô phỏng Fanpage Widget sắc nét tương thích mọi trình duyệt -->
                    <div class="flex-1 flex flex-col justify-between">
                        <div>
                            <!-- Ảnh bìa Fanpage -->
                            <div class="relative h-36 bg-gradient-to-r from-khNavy-900 to-khNavy-700 overflow-hidden">
                                <img src="https://drive.google.com/thumbnail?id=1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ&sz=w1000"
                                     data-gdrive="1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ"
                                     data-fallback="Fanpage+Khang+Huy+Window"
                                     onerror="handleDriveFallback(this)"
                                     alt="Ảnh bìa Fanpage Công ty Khang Huy"
                                     class="w-full h-full object-cover opacity-55">
                                <div class="absolute inset-0 bg-gradient-to-t from-black/75 via-black/25 to-transparent"></div>
                                <div class="absolute bottom-3 left-3 right-3 flex items-end gap-3">
                                    <!-- Avatar Logo -->
                                    <div class="w-12 h-12 rounded-lg border-2 border-white bg-khNavy-800 p-1 shadow shrink-0">
                                        <svg viewBox="0 0 64 64" class="w-full h-full" xmlns="http://www.w3.org/2000/svg">
                                            <rect x="2" y="2" width="60" height="60" rx="10" fill="#0B3C5D"/>
                                            <rect x="7" y="7" width="50" height="50" rx="6" fill="none" stroke="#E59500" stroke-width="3"/>
                                            <path d="M16 17H22V47H16V17Z" fill="#FFFFFF"/>
                                            <path d="M22 31.5L35 17H42.5L28.5 32L43 47H35.2L22 32.5V31.5Z" fill="#E59500"/>
                                            <path d="M43 17H48.5V47H43V17Z" fill="#FFFFFF"/>
                                        </svg>
                                    </div>
                                    <div class="min-w-0 text-white">
                                        <h3 class="text-sm font-bold leading-tight truncate">Nhôm Kính Khang Huy Đà Nẵng</h3>
                                        <p class="text-[11px] text-slate-200 mt-0.5">5.8K người theo dõi • Phản hồi nhanh</p>
                                    </div>
                                </div>
                            </div>

                            <!-- Bài đăng mới nhất trên Fanpage -->
                            <div class="p-4 space-y-3">
                                <div class="flex items-center justify-between gap-2">
                                    <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" class="flex-1 inline-flex items-center justify-center gap-1.5 py-2 px-3 rounded-lg bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-bold transition">
                                        <i class="fa-solid fa-thumbs-up"></i> Thích Trang
                                    </a>
                                    <a href="https://m.me/" target="_blank" rel="noopener noreferrer" class="flex-1 inline-flex items-center justify-center gap-1.5 py-2 px-3 rounded-lg bg-slate-100 hover:bg-slate-200 text-slate-800 text-xs font-bold transition">
                                        <i class="fa-brands fa-facebook-messenger text-[#1877F2]"></i> Nhắn Tin
                                    </a>
                                </div>
                                <div class="rounded-lg bg-slate-50 border border-slate-100 p-3 text-xs text-slate-600 space-y-1.5">
                                    <p class="font-semibold text-khNavy-800">Công Ty TNHH Đầu Tư Phát Triển Khang Huy</p>
                                    <p class="leading-relaxed">
                                        Cập nhật hình ảnh bàn giao công trình Cửa nhôm Xingfa nhập khẩu &amp; vách kính cường lực tại Đà Nẵng. Liên hệ ngay <strong>0915.493.033</strong> để nhận ưu đãi chiết khấu tốt nhất trong tháng!
                                    </p>
                                    <p class="text-[11px] text-slate-400"><i class="fa-regular fa-clock mr-1"></i> Cập nhật thường xuyên tại Fanpage Khang Huy</p>
                                </div>
                            </div>
                        </div>

                        <div class="px-4 py-3 bg-slate-50 border-t border-slate-200 text-xs text-center">
                            <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" class="font-semibold text-[#1877F2] hover:underline">
                                Truy cập Fanpage Facebook Nhôm Kính Khang Huy <i class="fa-solid fa-arrow-up-right-from-square ml-1 text-[10px]"></i>
                            </a>
                        </div>
                    </div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         13. FOOTER (CHUẨN CẤU TRÚC FLATSOME FOOTER)
    ========================================================================== -->
    <footer class="bg-khNavy-900 text-slate-300 pt-10 pb-6 border-t-4 border-khGold-500">
        <div class="kh-container">
            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-8 pb-8 border-b border-khNavy-700/70">
                <!-- Cột 1: Thông tin công ty -->
                <div class="space-y-3">
                    <div class="flex items-center gap-2.5">
                        <div class="w-9 h-9 shrink-0">
                            <svg viewBox="0 0 64 64" class="w-full h-full" xmlns="http://www.w3.org/2000/svg">
                                <rect x="2" y="2" width="60" height="60" rx="12" fill="#0E4468"/>
                                <rect x="7" y="7" width="50" height="50" rx="8" fill="none" stroke="#E59500" stroke-width="2.8"/>
                                <path d="M16 17H22V47H16V17Z" fill="#FFFFFF"/>
                                <path d="M22 31.5L35 17H42.5L28.5 32L43 47H35.2L22 32.5V31.5Z" fill="#E59500"/>
                                <path d="M43 17H48.5V47H43V17Z" fill="#FFFFFF"/>
                            </svg>
                        </div>
                        <div>
                            <div class="text-sm font-extrabold text-white leading-tight">KHANG HUY WINDOW</div>
                            <div class="text-[10px] text-khGold-400 uppercase tracking-wider">khanghuy.com</div>
                        </div>
                    </div>
                    <p class="text-xs font-bold text-white uppercase">CÔNG TY TNHH ĐẦU TƯ PHÁT TRIỂN KHANG HUY</p>
                    <ul class="space-y-2 text-xs leading-relaxed">
                        <li class="flex items-start gap-2">
                            <i class="fa-solid fa-location-dot text-khGold-400 mt-1 shrink-0"></i>
                            <span>Địa chỉ: Lô CN1, CCN Thường Tín, Phường Điện Bàn Đông, TP Đà Nẵng</span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-phone text-khGold-400 shrink-0"></i>
                            <span>Hotline / Zalo: <a href="tel:0915493033" class="text-white font-bold hover:text-khGold-400">0915.493.033</a></span>
                        </li>
                        <li class="flex items-center gap-2">
                            <i class="fa-solid fa-globe text-khGold-400 shrink-0"></i>
                            <span>Website: <a href="#trang-chu" class="text-white hover:text-khGold-400">www.khanghuy.com</a></span>
                        </li>
                    </ul>
                </div>

                <!-- Cột 2: Cửa nhôm Xingfa -->
                <div>
                    <h4 class="text-sm font-bold text-white uppercase mb-3 pb-1.5 border-b border-khNavy-700">Cửa Nhôm Xingfa</h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#san-pham" onclick="highlightProduct('Cửa đi quay mở 1 cánh nhôm xingfa')" class="hover:text-khGold-400 transition">Cửa nhôm xingfa 1 cánh</a></li>
                        <li><a href="#san-pham" onclick="highlightProduct('Cửa đi quay mở 2 cánh nhôm xingfa')" class="hover:text-khGold-400 transition">Cửa nhôm xingfa 2 cánh</a></li>
                        <li><a href="#san-pham" onclick="highlightProduct('Cửa đi quay mở 3 cánh nhôm xingfa')" class="hover:text-khGold-400 transition">Cửa nhôm xingfa 3 cánh</a></li>
                        <li><a href="#san-pham" onclick="highlightProduct('Cửa đi quay mở 4 cánh nhôm xingfa')" class="hover:text-khGold-400 transition">Cửa nhôm xingfa 4 cánh</a></li>
                        <li><a href="#san-pham" onclick="highlightProduct('Cửa Nhôm Xingfa Cửa Đi Xếp Trượt')" class="hover:text-khGold-400 transition">Cửa nhôm xingfa 5 cánh &amp; xếp trượt</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Danh mục sản phẩm -->
                <div>
                    <h4 class="text-sm font-bold text-white uppercase mb-3 pb-1.5 border-b border-khNavy-700">Danh Mục Sản Phẩm</h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#danh-muc" class="hover:text-khGold-400 transition">Cửa nhôm xingfa Đà Nẵng</a></li>
                        <li><a href="#danh-muc" class="hover:text-khGold-400 transition">Cửa nhựa lõi thép</a></li>
                        <li><a href="#danh-muc" class="hover:text-khGold-400 transition">Cửa kính tự động</a></li>
                        <li><a href="#danh-muc" class="hover:text-khGold-400 transition">Cầu thang kính cường lực</a></li>
                        <li><a href="#danh-muc" class="hover:text-khGold-400 transition">Kính ốp bếp &amp; Phòng tắm kính</a></li>
                    </ul>
                </div>

                <!-- Cột 4: Liên kết nhanh -->
                <div>
                    <h4 class="text-sm font-bold text-white uppercase mb-3 pb-1.5 border-b border-khNavy-700">Hỗ Trợ Khách Hàng</h4>
                    <ul class="space-y-2 text-xs">
                        <li><a href="#gioi-thieu" class="hover:text-khGold-400 transition">Giới thiệu công ty</a></li>
                        <li><a href="#cong-trinh" class="hover:text-khGold-400 transition">Công trình tiêu biểu Đà Nẵng</a></li>
                        <li><a href="#bao-gia" class="hover:text-khGold-400 transition">Bảng báo giá mới nhất</a></li>
                        <li><a href="#tin-tuc" class="hover:text-khGold-400 transition">Tin tức &amp; Tư vấn kỹ thuật</a></li>
                        <li><a href="#form-bao-gia" class="hover:text-khGold-400 transition">Đăng ký khảo sát miễn phí</a></li>
                    </ul>
                </div>
            </div>

            <div class="pt-5 flex flex-col sm:flex-row items-center justify-between gap-2 text-xs text-slate-400">
                <p>Copyright &copy; 2026 <strong>CÔNG TY TNHH ĐẦU TƯ PHÁT TRIỂN KHANG HUY</strong> (khanghuy.com). All rights reserved.</p>
                <p>Thiết kế chuẩn bố cục Flatsome • Tối ưu di động &amp; máy tính</p>
            </div>
        </div>
    </footer>

    <!-- =========================================================================
         14. CÁC NÚT LIÊN HỆ NỔI BẬT: ZALO, FACEBOOK, HOTLINE (TƯƠNG THÍCH PC & MOBILE)
    ========================================================================== -->
    <div class="fixed right-3 sm:right-5 bottom-4 sm:bottom-6 z-50 flex flex-col items-end gap-2.5">
        <!-- Nút Zalo -->
        <a href="https://zalo.me/0915493033" target="_blank" rel="noopener noreferrer" aria-label="Chat Zalo 0915.493.033"
           class="group flex items-center gap-2 bg-[#0068FF] hover:bg-blue-700 text-white px-3 py-2 sm:px-3.5 sm:py-2.5 rounded-full shadow-lg transition-all">
            <span class="w-6 h-6 rounded-full bg-white text-[#0068FF] font-extrabold text-[11px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="hidden sm:inline text-xs font-bold pr-1">Chat Zalo</span>
        </a>

        <!-- Nút Facebook -->
        <a href="https://facebook.com" target="_blank" rel="noopener noreferrer" aria-label="Facebook Khang Huy"
           class="group flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white px-3 py-2 sm:px-3.5 sm:py-2.5 rounded-full shadow-lg transition-all">
            <i class="fa-brands fa-facebook-messenger text-lg w-6 text-center"></i>
            <span class="hidden sm:inline text-xs font-bold pr-1">Facebook</span>
        </a>

        <!-- Nút Hotline nổi bật -->
        <a href="tel:0915493033" aria-label="Gọi Hotline 0915.493.033"
           class="btn-hotline-pulse flex items-center gap-2 bg-khGold-500 hover:bg-khGold-600 text-white px-3.5 py-2.5 sm:px-4 sm:py-3 rounded-full shadow-xl transition-all">
            <i class="fa-solid fa-phone-volume text-base sm:text-lg"></i>
            <span class="text-xs sm:text-sm font-extrabold tracking-tight">0915.493.033</span>
        </a>
    </div>

    <!-- =========================================================================
         15. MODAL XEM CHI TIẾT SẢN PHẨM / DỰ ÁN / BÀI VIẾT & THÔNG BÁO TOAST
    ========================================================================== -->
    <div id="detail-modal" class="hidden fixed inset-0 z-50 bg-black/60 backdrop-blur-xs flex items-center justify-center p-3 sm:p-5">
        <div class="bg-white rounded-2xl max-w-2xl w-full max-h-[90vh] overflow-y-auto shadow-2xl border border-slate-200">
            <div class="flex items-center justify-between px-4 sm:px-5 py-3.5 border-b border-slate-100 sticky top-0 bg-white z-10">
                <h3 id="modal-title" class="text-sm sm:text-base font-extrabold text-khNavy-800 pr-4"></h3>
                <button type="button" onclick="closeDetailModal()" class="w-8 h-8 rounded-full bg-slate-100 hover:bg-slate-200 text-slate-600 flex items-center justify-center shrink-0">
                    <i class="fa-solid fa-xmark"></i>
                </button>
            </div>
            <div id="modal-body" class="p-4 sm:p-5 space-y-4"></div>
        </div>
    </div>

    <!-- Toast Thông báo (Thay thế hoàn toàn alert()) -->
    <div id="kh-toast" class="hidden fixed top-20 left-1/2 -translate-x-1/2 z-50 max-w-[92vw] sm:max-w-md bg-khNavy-900 text-white px-4 py-3 rounded-xl shadow-2xl border border-khGold-500/60 text-xs sm:text-sm font-medium flex items-center gap-2.5">
        <i class="fa-solid fa-circle-check text-khGold-400 text-base shrink-0"></i>
        <span id="kh-toast-text"></span>
    </div>

    <!-- =========================================================================
         16. JAVASCRIPT QUẢN LÝ DỮ LIỆU, SLIDER, ẢNH GOOGLE DRIVE & TƯƠNG TÁC
    ========================================================================== -->
    <script>
        /**
         * Cơ chế tải ảnh Google Drive tin cậy 3 lớp:
         * Lớp 1: drive.google.com/thumbnail?id=...&sz=w1000
         * Lớp 2: lh3.googleusercontent.com/d/...=w1000
         * Lớp 3: Placeholder có thương hiệu Khang Huy nếu link bị giới hạn quyền riêng tư
         */
        function getDriveImgUrl(fileId) {
            return `https://drive.google.com/thumbnail?id=${fileId}&sz=w1000`;
        }

        function handleDriveFallback(img) {
            const step = parseInt(img.getAttribute('data-fb-step') || '0', 10);
            const fileId = img.getAttribute('data-gdrive');
            const label = img.getAttribute('data-fallback') || 'Khang+Huy+Window';

            if (step === 0 && fileId) {
                img.setAttribute('data-fb-step', '1');
                img.src = `https://lh3.googleusercontent.com/d/${fileId}=w1000`;
            } else if (step === 1) {
                img.setAttribute('data-fb-step', '2');
                img.src = `https://placehold.co/600x450/0B3C5D/FFFFFF?text=${encodeURIComponent(label.replace(/\+/g, ' '))}`;
            }
        }

        // ==========================================================
        // DỮ LIỆU DANH MỤC SẢN PHẨM (6 DANH MỤC TỪ LINK DRIVE)
        // ==========================================================
        const CATEGORIES = [
            {
                name: 'Cửa nhôm xingfa',
                fileId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
                desc: 'Nhôm Xingfa nhập khẩu tem đỏ Quảng Đông hệ 55, 63, 93 kết hợp phụ kiện Kinlong chính hãng.'
            },
            {
                name: 'Cửa nhựa lõi thép',
                fileId: '1jiHBW-2MoWUHjQUicSe-rO6NlmfNuZNA',
                desc: 'Cửa nhựa uPVC lõi thép gia cường cách âm, cách nhiệt vượt trội, chống cong vênh.'
            },
            {
                name: 'Cửa kính tự động',
                fileId: '1PIFP1UCQs_FIaKCgGwcJWt-5wTnST9iJ',
                desc: 'Hệ cửa trượt kính tự động cảm biến mắt thần Hàn Quốc, Nhật Bản cho showroom & khách sạn.'
            },
            {
                name: 'Cầu thang kính',
                fileId: '1FnuITlKMjk-xTxkIV96ABv43S1PG--Ul',
                desc: 'Lan can cầu thang kính cường lực 10mm-12mm tay vịn gỗ/Inox 304 sang trọng, an toàn.'
            },
            {
                name: 'Kính ốp bếp',
                fileId: '1ilanOshTrs9llnMXWl5iZ8DtgptJ0hCb',
                desc: 'Kính cường lực 8mm sơn màu chịu nhiệt cao cấp, dễ lau chùi, sáng bóng hiện đại.'
            },
            {
                name: 'Phòng tắm kính',
                fileId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
                desc: 'Vách tắm kính cường lực 10mm mở quay, mở lùa chống tràn nước, phụ kiện Inox 304.'
            }
        ];

        // ==========================================================
        // DỮ LIỆU SẢN PHẨM CỬA NHÔM XINGFA (CÓ GIÁ & GIẢM GIÁ %)
        // ==========================================================
        const PRODUCTS = [
            {
                name: 'Cửa đi quay mở 1 cánh nhôm xingfa',
                fileId: '1-0eBWGjPwzQ-C9c1Wjws9wt0gbsulkPm',
                price: '1.950.000 ₫',
                oldPrice: '2.250.000 ₫',
                discount: '-13%',
                spec: 'Thanh profile nhôm Xingfa hệ 55 dày 2.0mm, kính an toàn 6.38mm hoặc cường lực 8mm, phụ kiện Kinlong nhập khẩu đồng bộ.',
                unit: '/m²'
            },
            {
                name: 'Cửa đi quay mở 2 cánh nhôm xingfa',
                fileId: '1h2r2rbPrEL7dgLE-MiE5lBBuE8gFNehb',
                price: '1.950.000 ₫',
                oldPrice: '2.300.000 ₫',
                discount: '-15%',
                spec: 'Thiết kế mở quay 2 cánh hệ 55 dày 2.0mm, gioăng EPDM kín khít tuyệt đối, chống nước mưa và cách âm hiệu quả.',
                unit: '/m²'
            },
            {
                name: 'Cửa đi quay mở 3 cánh nhôm xingfa',
                fileId: '17Qi2D8ntACnVrTeRPZ2V7rC0FmI8ecaR',
                price: '2.050.000 ₫',
                oldPrice: '2.400.000 ₫',
                discount: '-15%',
                spec: 'Phù hợp mặt tiền nhà phố hiện đại, khung nhôm Xingfa nhập khẩu Quảng Đông sơn tĩnh điện cao cấp chống ăn mòn muối biển.',
                unit: '/m²'
            },
            {
                name: 'Cửa đi quay mở 4 cánh nhôm xingfa',
                fileId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
                price: '2.050.000 ₫',
                oldPrice: '2.450.000 ₫',
                discount: '-16%',
                spec: 'Mở rộng tối đa không gian mặt tiền biệt thự, nhà phố. Hệ 55 dày 2.0mm chịu lực gió bão vượt trội tại Đà Nẵng.',
                unit: '/m²'
            },
            {
                name: 'Cửa Nhôm Xingfa Cửa Đi Xếp Trượt',
                fileId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
                price: '2.100.000 ₫',
                oldPrice: '2.500.000 ₫',
                discount: '-16%',
                spec: 'Hệ nhôm Xingfa 63 xếp trượt gấp gọn linh hoạt (3, 4, 5, 6 cánh), ray trượt êm ái, tối ưu tầm nhìn sân vườn & ban công.',
                unit: '/m²'
            },
            {
                name: 'Cửa sổ mở hất 2 cánh nhôm Xingfa',
                fileId: '11fS_oEeJtnDICQZ77fJlYl6GhHf-GOhA',
                price: '1.850.000 ₫',
                oldPrice: '2.150.000 ₫',
                discount: '-14%',
                spec: 'Nhôm Xingfa hệ 55 dày 1.4mm, thanh định vị chống va đập gió, mở thoáng ngay cả khi trời mưa nhỏ.',
                unit: '/m²'
            }
        ];

        // ==========================================================
        // DỮ LIỆU 6 DỰ ÁN TIÊU BIỂU TẠI ĐÀ NẴNG
        // ==========================================================
        const PROJECTS = [
            {
                title: 'DỰ ÁN KHÁCH SẠN RUBY LIGHT',
                fileId: '1wH-JJ2rOYRmDGsNapl3bIBjfiG3Qm6zZ',
                location: 'TP. Đà Nẵng',
                scope: 'Thi công trọn gói hệ cửa đi, cửa sổ nhôm Xingfa nhập khẩu và vách kính tắm cường lực.'
            },
            {
                title: 'DỰ ÁN RESORT MỸ SƠN 4 SAO “MY SON HERITAGE RESORT & SPA”',
                fileId: '1MmAfsyp3s3YCaEMymrkk8TZbD38jCsAQ',
                location: 'Quảng Nam – Đà Nẵng',
                scope: 'Sản xuất và lắp đặt hệ cửa nhôm kính cao cấp chống ồn, chống ăn mòn khí hậu miền Trung.'
            },
            {
                title: 'THI CÔNG DỰ ÁN KHÁCH SẠN GODEN LINE',
                fileId: '1YeuDLiSXUK_Epupq9QiGzM90_EGW3Kfy',
                location: 'TP. Đà Nẵng',
                scope: 'Cung cấp vách kính mặt dựng, cửa kính tự động sảnh chính và phòng tắm kính.'
            },
            {
                title: 'THI CÔNG DỰ ÁN KHÁCH SẠN JOLIA',
                fileId: '1WRgx-EUIrn8IKFZdpmdv6Z2Xyb7L8_64',
                location: 'TP. Đà Nẵng',
                scope: 'Thi công toàn bộ hạng mục cửa nhôm Xingfa tem đỏ, lan can kính ban công cường lực.'
            },
            {
                title: 'THI CÔNG DỰ ÁN KHÁCH SẠN SOHO',
                fileId: '1-C5bdt4K-PpLX_KqSN6QAR5ULo1WnNzt',
                location: 'TP. Đà Nẵng',
                scope: 'Lắp đặt đồng bộ cửa sổ nhôm Xingfa cách âm, cửa đi ban công và cabin kính phòng tắm.'
            },
            {
                title: 'THI CÔNG DỰ ÁN RAON ĐÀ NẴNG BEACH HOTEL',
                fileId: '1za_IJpAm850uulT6IuhBsk1THb3LuPuc',
                location: 'Biển Mỹ Khê, Đà Nẵng',
                scope: 'Hạng mục nhôm kính chịu gió biển cường độ cao, phụ kiện Inox 304 và kính cường lực an toàn.'
            }
        ];

        // ==========================================================
        // DỮ LIỆU 6 ĐỐI TÁC (LINK DRIVE NGƯỜI DÙNG CUNG CẤP)
        // ==========================================================
        const PARTNERS = [
            { name: 'Đối tác Nhôm Kính 1', fileId: '13il4TeS8ZnrK0CD4VDPMdNX3EKxY8AFk' },
            { name: 'Đối tác Nhôm Kính 2', fileId: '1QRcPtjWfg5PEQXw6UMg6ZylQhg8BpzUq' },
            { name: 'Đối tác Nhôm Kính 3', fileId: '1-Ka-zScPzx653Tg2oWE9-qmFtTdn3Svn' },
            { name: 'Đối tác Nhôm Kính 4', fileId: '1Oy52Wdfy5x6DKF1lyfYxpZTD5fvGH5vT' },
            { name: 'Đối tác Nhôm Kính 5', fileId: '1SDcarhnX0yypmqdbawICjYBRtFnKngn-' },
            { name: 'Đối tác Nhôm Kính 6', fileId: '1Ua4C1iiZqrjkWx-3h2quvqM0w_Xj33fg' }
        ];

        // ==========================================================
        // DỮ LIỆU BÀI VIẾT TIN TỨC NỔI BẬT TRÊN TRANG CHỦ
        // ==========================================================
        const ARTICLES = [
            {
                title: 'Cửa nhôm Xingfa có phù hợp với khí hậu ven biển Đà Nẵng không?',
                date: '18/11/2026',
                fileId: '1zRlHJBAneXS7EQ1jdT__hVRCTf2mzOiX',
                excerpt: 'Tìm hiểu khả năng chống ăn mòn hơi muối biển, chống bão và cách âm vượt trội của nhôm Xingfa nhập khẩu tem đỏ.',
                content: 'Với lớp sơn tĩnh điện cao cấp đạt tiêu chuẩn quốc tế và cấu trúc khoang trống có gân gia cường, cửa nhôm Xingfa nhập khẩu tem đỏ hoàn toàn phù hợp với thời tiết nắng gió, mưa bão và khí hậu ven biển tại Đà Nẵng. Khi kết hợp kính cường lực và gioăng EPDM kép, cửa giữ độ bền màu hàng chục năm.'
            },
            {
                title: 'Kinh nghiệm phân biệt nhôm Xingfa nhập khẩu Quảng Đông chính hãng',
                date: '12/11/2026',
                fileId: '1lxzMKWX3e_HJn7UELFZDOURuxh-NYZg-',
                excerpt: 'Hướng dẫn kiểm tra tem đỏ QR code, màu ánh kim bên trong khoang nhôm và độ dày tiêu chuẩn 1.4mm – 2.0mm.',
                content: 'Để chọn đúng nhôm Xingfa Quảng Đông chính hãng, khách hàng nên kiểm tra 3 yếu tố chính: Tem đỏ sắc nét có mã QR truy xuất nguồn gốc, mặt cắt thanh nhôm ánh kim nhờ công nghệ mạ crom chống oxy hóa, và độ dày chuẩn 1.4mm cho cửa sổ – 2.0mm cho cửa đi.'
            },
            {
                title: 'So sánh cửa nhôm Xingfa và cửa gỗ tự nhiên cho nhà phố hiện đại',
                date: '05/11/2026',
                fileId: '1lJpUJBpR_cJp8mIaZ4FnRTynQ_-paNwZ',
                excerpt: 'Phân tích chi tiết về độ bền, khả năng chống mối mọt, cong vênh và chi phí đầu tư giữa hai dòng cửa phổ biến.',
                content: 'Khác với cửa gỗ dễ bị co ngót, cong vênh hoặc mối mọt sau vài mùa mưa nắng, cửa nhôm Xingfa khắc phục hoàn toàn các nhược điểm này. Ngoài ra, cửa nhôm kính còn tận dụng tối đa ánh sáng tự nhiên, mang lại vẻ sang trọng và tiết kiệm điện năng cho ngôi nhà.'
            },
            {
                title: 'Báo giá lắp đặt phòng tắm kính và cầu thang kính cường lực mới nhất',
                date: '28/10/2026',
                fileId: '1MhCILHQ5goD1cAPTt1hZsY_ajeOMs-qH',
                excerpt: 'Tổng hợp các mẫu vách kính tắm 90 độ, 135 độ, cửa lùa và lan can cầu thang kính đẹp đang được ưa chuộng.',
                content: 'Phòng tắm kính cường lực 10mm cùng phụ kiện Inox 304 giúp không gian nhà vệ sinh luôn khô ráo, sạch sẽ và rộng rãi hơn. Khang Huy trực tiếp khảo sát, đo đạc cắt kính chuẩn xác từng milimet và lắp đặt nhanh chóng tại Đà Nẵng.'
            }
        ];

        // ==========================================================
        // RENDER CÁC KHU VỰC LÊN GIAO DIỆN
        // ==========================================================
        function renderCategories() {
            const container = document.getElementById('category-grid');
            container.innerHTML = CATEGORIES.map(cat => `
                <button type="button" onclick="selectCategoryNotice('${cat.name}')"
                        class="group bg-white rounded-xl border border-slate-200 hover:border-khGold-500 shadow-xs hover:shadow-md overflow-hidden transition text-center flex flex-col">
                    <div class="w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                        <img src="${getDriveImgUrl(cat.fileId)}"
                             data-gdrive="${cat.fileId}"
                             data-fallback="${cat.name.replace(/\s+/g, '+')}"
                             onerror="handleDriveFallback(this)"
                             alt="${cat.name}"
                             loading="lazy"
                             class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-2.5 sm:p-3 flex-1 flex items-center justify-center">
                        <h3 class="text-[11.5px] sm:text-xs font-bold uppercase text-khNavy-800 group-hover:text-khGold-600 transition leading-snug break-words">
                            ${cat.name}
                        </h3>
                    </div>
                </button>
            `).join('');
        }

        function renderProducts() {
            const container = document.getElementById('product-grid');
            container.innerHTML = PRODUCTS.map((prod, idx) => `
                <article id="prod-card-${idx}" class="group bg-white rounded-xl border border-slate-200 hover:border-khNavy-600 shadow-xs hover:shadow-lg overflow-hidden transition flex flex-col">
                    <div class="relative w-full aspect-[4/3] bg-slate-100 overflow-hidden">
                        <!-- Giảm giá % ở góc trên bên trái sản phẩm -->
                        <span class="absolute top-2 left-2 z-10 px-2 py-0.5 rounded-md bg-red-600 text-white text-[10px] sm:text-xs font-extrabold shadow">
                            ${prod.discount}
                        </span>
                        <img src="${getDriveImgUrl(prod.fileId)}"
                             data-gdrive="${prod.fileId}"
                             data-fallback="${prod.name.replace(/\s+/g, '+')}"
                             onerror="handleDriveFallback(this)"
                             alt="${prod.name}"
                             loading="lazy"
                             class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>

                    <div class="p-2.5 sm:p-4 flex-1 flex flex-col justify-between gap-2">
                        <!-- Tên sản phẩm đầy đủ, không cắt chữ, không tràn khung trên mobile 2 cột -->
                        <h3 class="text-[12.5px] sm:text-sm font-bold text-khNavy-800 group-hover:text-khGold-600 transition leading-snug break-words">
                            ${prod.name}
                        </h3>

                        <div class="space-y-2 pt-1">
                            <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                                <span class="text-xs sm:text-base font-extrabold text-red-600">${prod.price}<span class="text-[10px] sm:text-xs font-medium text-slate-500">${prod.unit}</span></span>
                                <span class="text-[10px] sm:text-xs text-slate-400 line-through">${prod.oldPrice}</span>
                            </div>

                            <div class="grid grid-cols-2 gap-1.5 pt-1">
                                <button type="button" onclick="openProductModal(${idx})" class="py-1.5 sm:py-2 px-2 rounded-lg bg-khNavy-800 hover:bg-khNavy-700 text-white text-[11px] sm:text-xs font-semibold transition">
                                    Chi tiết
                                </button>
                                <button type="button" onclick="requestQuoteFor('${prod.name}')" class="py-1.5 sm:py-2 px-2 rounded-lg bg-khGold-500 hover:bg-khGold-600 text-white text-[11px] sm:text-xs font-bold transition">
                                    Báo giá
                                </button>
                            </div>
                        </div>
                    </div>
                </article>
            `).join('');
        }

        function renderProjects() {
            const container = document.getElementById('project-grid');
            container.innerHTML = PROJECTS.map((proj, idx) => `
                <article class="group bg-white rounded-xl border border-slate-200 hover:border-khGold-500 shadow-xs hover:shadow-lg overflow-hidden transition flex flex-col">
                    <div class="w-full aspect-[16/10] bg-slate-100 overflow-hidden cursor-pointer" onclick="openProjectModal(${idx})">
                        <img src="${getDriveImgUrl(proj.fileId)}"
                             data-gdrive="${proj.fileId}"
                             data-fallback="${proj.title.replace(/\s+/g, '+')}"
                             onerror="handleDriveFallback(this)"
                             alt="${proj.title}"
                             loading="lazy"
                             class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3.5 sm:p-4 flex-1 flex flex-col justify-between gap-2">
                        <div>
                            <p class="text-[11px] font-semibold text-khGold-600 mb-1">
                                <i class="fa-solid fa-location-dot mr-1"></i>${proj.location}
                            </p>
                            <h3 onclick="openProjectModal(${idx})" class="cursor-pointer text-xs sm:text-sm font-bold text-khNavy-800 group-hover:text-khGold-600 transition leading-snug break-words">
                                ${proj.title}
                            </h3>
                        </div>
                        <p class="text-xs text-slate-600 leading-relaxed">${proj.scope}</p>
                    </div>
                </article>
            `).join('');
        }

        function renderArticles() {
            const container = document.getElementById('articles-grid');
            container.innerHTML = ARTICLES.map((art, idx) => `
                <article class="group bg-white rounded-xl border border-slate-200 hover:border-khNavy-600 shadow-xs hover:shadow-md overflow-hidden transition flex flex-col">
                    <div class="w-full aspect-[16/10] bg-slate-100 overflow-hidden cursor-pointer" onclick="openArticleModal(${idx})">
                        <img src="${getDriveImgUrl(art.fileId)}"
                             data-gdrive="${art.fileId}"
                             data-fallback="Tin+Tuc+Khang+Huy"
                             onerror="handleDriveFallback(this)"
                             alt="${art.title}"
                             loading="lazy"
                             class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                    </div>
                    <div class="p-3.5 sm:p-4 flex-1 flex flex-col justify-between gap-2">
                        <div class="space-y-1.5">
                            <p class="text-[11px] text-slate-400"><i class="fa-regular fa-calendar mr-1"></i>${art.date}</p>
                            <h3 onclick="openArticleModal(${idx})" class="cursor-pointer text-xs sm:text-sm font-bold text-khNavy-800 group-hover:text-khGold-600 transition leading-snug break-words">
                                ${art.title}
                            </h3>
                            <p class="text-xs text-slate-600 leading-relaxed">${art.excerpt}</p>
                        </div>
                        <button type="button" onclick="openArticleModal(${idx})" class="self-start text-xs font-bold text-khGold-600 hover:text-khNavy-800 transition pt-1">
                            Xem chi tiết <i class="fa-solid fa-arrow-right text-[10px] ml-1"></i>
                        </button>
                    </div>
                </article>
            `).join('');
        }

        function renderPartners() {
            const container = document.getElementById('partner-grid');
            container.innerHTML = PARTNERS.map(p => `
                <div class="bg-white rounded-xl border border-slate-200 p-3 h-20 sm:h-24 flex items-center justify-center shadow-xs hover:shadow transition">
                    <img src="${getDriveImgUrl(p.fileId)}"
                         data-gdrive="${p.fileId}"
                         data-fallback="${p.name.replace(/\s+/g, '+')}"
                         onerror="handleDriveFallback(this)"
                         alt="${p.name}"
                         loading="lazy"
                         class="max-h-full max-w-full object-contain">
                </div>
            `).join('');
        }

        // ==========================================================
        // SLIDER 2 BANNER TỰ TRƯỢT + HỖ TRỢ VUỐT CẢM ỨNG MOBILE
        // ==========================================================
        let currentSlide = 0;
        const totalSlides = 2;
        let slideTimer = null;

        function updateSliderUI() {
            const track = document.getElementById('hero-track');
            track.style.transform = `translateX(-${currentSlide * 100}%)`;

            for (let i = 0; i < totalSlides; i++) {
                const dot = document.getElementById(`dot-${i}`);
                if (!dot) continue;
                if (i === currentSlide) {
                    dot.className = 'w-6 h-2 rounded-full bg-khGold-500 transition-all';
                } else {
                    dot.className = 'w-2.5 h-2 rounded-full bg-white/50 hover:bg-white transition-all';
                }
            }
        }

        function moveSlide(step) {
            currentSlide = (currentSlide + step + totalSlides) % totalSlides;
            updateSliderUI();
            resetAutoSlide();
        }

        function goToSlide(index) {
            currentSlide = index;
            updateSliderUI();
            resetAutoSlide();
        }

        function resetAutoSlide() {
            if (slideTimer) clearInterval(slideTimer);
            slideTimer = setInterval(() => {
                currentSlide = (currentSlide + 1) % totalSlides;
                updateSliderUI();
            }, 5000);
        }

        // Vuốt cảm ứng trên điện thoại cho Banner
        function initBannerSwipe() {
            const slider = document.getElementById('hero-slider');
            let touchStartX = 0;
            slider.addEventListener('touchstart', (e) => {
                touchStartX = e.changedTouches[0].screenX;
            }, { passive: true });
            slider.addEventListener('touchend', (e) => {
                const touchEndX = e.changedTouches[0].screenX;
                if (touchStartX - touchEndX > 45) moveSlide(1);
                if (touchEndX - touchStartX > 45) moveSlide(-1);
            }, { passive: true });
        }

        // ==========================================================
        // MENU MOBILE & DROPDOWNS
        // ==========================================================
        const mobileBtn = document.getElementById('mobile-menu-btn');
        const mobileDrawer = document.getElementById('mobile-menu-drawer');

        mobileBtn.addEventListener('click', () => {
            mobileDrawer.classList.toggle('hidden');
        });

        function closeMobileMenu() {
            mobileDrawer.classList.add('hidden');
        }

        function toggleMobileSub(id) {
            const el = document.getElementById(id);
            const icon = document.getElementById('icon-' + id);
            el.classList.toggle('hidden');
            icon.classList.toggle('rotate-180');
        }

        // ==========================================================
        // TƯƠNG TÁC TAB BÁO GIÁ, MODAL CHI TIẾT & FORM BÁO GIÁ
        // ==========================================================
        function switchPriceTab(type) {
            const tabXingfa = document.getElementById('tab-price-xingfa');
            const tabKinh = document.getElementById('tab-price-kinh');
            const tableXingfa = document.getElementById('table-price-xingfa');
            const tableKinh = document.getElementById('table-price-kinh');

            if (type === 'xingfa') {
                tableXingfa.classList.remove('hidden');
                tableKinh.classList.add('hidden');
                tabXingfa.className = 'px-4 py-2 rounded-lg text-xs sm:text-sm font-bold bg-khNavy-800 text-white shadow transition';
                tabKinh.className = 'px-4 py-2 rounded-lg text-xs sm:text-sm font-bold bg-white text-khNavy-800 border border-slate-200 hover:bg-khNavy-50 transition';
            } else {
                tableKinh.classList.remove('hidden');
                tableXingfa.classList.add('hidden');
                tabKinh.className = 'px-4 py-2 rounded-lg text-xs sm:text-sm font-bold bg-khNavy-800 text-white shadow transition';
                tabXingfa.className = 'px-4 py-2 rounded-lg text-xs sm:text-sm font-bold bg-white text-khNavy-800 border border-slate-200 hover:bg-khNavy-50 transition';
            }
        }

        function highlightProduct(name) {
            const idx = PRODUCTS.findIndex(p => p.name.toLowerCase() === name.toLowerCase());
            if (idx >= 0) {
                const card = document.getElementById(`prod-card-${idx}`);
                if (card) {
                    card.classList.add('ring-2', 'ring-khGold-500');
                    setTimeout(() => card.classList.remove('ring-2', 'ring-khGold-500'), 2200);
                }
            }
        }

        function filterProductsBySub() {
            showToast('Đang hiển thị các dòng sản phẩm Cửa nhôm Xingfa chính hãng.');
        }

        function selectCategoryNotice(catName) {
            const found = CATEGORIES.find(c => c.name.toLowerCase() === catName.toLowerCase());
            if (found) {
                document.getElementById('modal-title').textContent = 'Danh mục: ' + found.name;
                document.getElementById('modal-body').innerHTML = `
                    <div class="aspect-[16/10] rounded-xl overflow-hidden bg-slate-100">
                        <img src="${getDriveImgUrl(found.fileId)}" data-gdrive="${found.fileId}" data-fallback="${found.name}" onerror="handleDriveFallback(this)" class="w-full h-full object-cover" alt="${found.name}">
                    </div>
                    <p class="text-sm text-slate-700 leading-relaxed">${found.desc}</p>
                    <div class="flex flex-wrap gap-2.5 pt-2">
                        <button type="button" onclick="closeDetailModal(); requestQuoteFor('${found.name}')" class="px-4 py-2.5 rounded-lg bg-khGold-500 hover:bg-khGold-600 text-white text-xs sm:text-sm font-bold">
                            Nhận báo giá ${found.name}
                        </button>
                        <a href="tel:0915493033" class="px-4 py-2.5 rounded-lg bg-khNavy-800 hover:bg-khNavy-700 text-white text-xs sm:text-sm font-semibold">
                            Gọi 0915.493.033
                        </a>
                    </div>
                `;
                document.getElementById('detail-modal').classList.remove('hidden');
            }
        }

        function openProductModal(idx) {
            const prod = PRODUCTS[idx];
            document.getElementById('modal-title').textContent = prod.name;
            document.getElementById('modal-body').innerHTML = `
                <div class="relative aspect-[16/10] rounded-xl overflow-hidden bg-slate-100">
                    <span class="absolute top-3 left-3 px-2.5 py-1 rounded-md bg-red-600 text-white text-xs font-extrabold">${prod.discount}</span>
                    <img src="${getDriveImgUrl(prod.fileId)}" data-gdrive="${prod.fileId}" data-fallback="${prod.name}" onerror="handleDriveFallback(this)" class="w-full h-full object-cover" alt="${prod.name}">
                </div>
                <div class="flex flex-wrap items-baseline gap-3">
                    <span class="text-xl font-extrabold text-red-600">${prod.price}${prod.unit}</span>
                    <span class="text-sm text-slate-400 line-through">${prod.oldPrice}</span>
                </div>
                <p class="text-sm text-slate-700 leading-relaxed">${prod.spec}</p>
                <div class="rounded-lg bg-khNavy-50 p-3 text-xs text-khNavy-800 space-y-1">
                    <p><strong>Đơn vị thi công:</strong> CÔNG TY TNHH ĐẦU TƯ PHÁT TRIỂN KHANG HUY</p>
                    <p><strong>Bảo hành:</strong> Nhôm chính hãng 5 năm, phụ kiện đồng bộ 2 năm.</p>
                </div>
                <div class="flex flex-wrap gap-2.5 pt-1">
                    <button type="button" onclick="closeDetailModal(); requestQuoteFor('${prod.name}')" class="px-4 py-2.5 rounded-lg bg-khGold-500 hover:bg-khGold-600 text-white text-xs sm:text-sm font-bold">
                        Yêu cầu báo giá sản phẩm này
                    </button>
                    <a href="https://zalo.me/0915493033" target="_blank" rel="noopener noreferrer" class="px-4 py-2.5 rounded-lg bg-[#0068FF] hover:bg-blue-700 text-white text-xs sm:text-sm font-semibold">
                        Tư vấn qua Zalo
                    </a>
                </div>
            `;
            document.getElementById('detail-modal').classList.remove('hidden');
        }

        function openProjectModal(idx) {
            const proj = PROJECTS[idx];
            document.getElementById('modal-title').textContent = proj.title;
            document.getElementById('modal-body').innerHTML = `
                <div class="aspect-[16/10] rounded-xl overflow-hidden bg-slate-100">
                    <img src="${getDriveImgUrl(proj.fileId)}" data-gdrive="${proj.fileId}" data-fallback="${proj.title}" onerror="handleDriveFallback(this)" class="w-full h-full object-cover" alt="${proj.title}">
                </div>
                <p class="text-xs font-bold text-khGold-600"><i class="fa-solid fa-location-dot mr-1"></i>Khu vực: ${proj.location}</p>
                <p class="text-sm text-slate-700 leading-relaxed">${proj.scope}</p>
                <div class="pt-2">
                    <button type="button" onclick="closeDetailModal(); requestQuoteFor('Dự án tương tự: ${proj.title}')" class="px-4 py-2.5 rounded-lg bg-khNavy-800 hover:bg-khNavy-700 text-white text-xs sm:text-sm font-bold">
                        Liên hệ tư vấn thi công công trình
                    </button>
                </div>
            `;
            document.getElementById('detail-modal').classList.remove('hidden');
        }

        function openArticleModal(idx) {
            const art = ARTICLES[idx];
            document.getElementById('modal-title').textContent = art.title;
            document.getElementById('modal-body').innerHTML = `
                <div class="aspect-[16/10] rounded-xl overflow-hidden bg-slate-100">
                    <img src="${getDriveImgUrl(art.fileId)}" data-gdrive="${art.fileId}" data-fallback="Tin+Tuc+Khang+Huy" onerror="handleDriveFallback(this)" class="w-full h-full object-cover" alt="${art.title}">
                </div>
                <p class="text-xs text-slate-400">Ngày đăng: ${art.date} • Bởi Khang Huy Window</p>
                <p class="text-sm text-slate-700 leading-relaxed">${art.content}</p>
                <div class="pt-2 border-t border-slate-100 flex items-center justify-between flex-wrap gap-2">
                    <span class="text-xs font-semibold text-khNavy-800">Cần tư vấn chi tiết? Gọi ngay 0915.493.033</span>
                    <button type="button" onclick="closeDetailModal(); document.getElementById('form-bao-gia').scrollIntoView({behavior:'smooth'})" class="px-3.5 py-2 rounded-lg bg-khGold-500 text-white text-xs font-bold">
                        Đăng ký báo giá
                    </button>
                </div>
            `;
            document.getElementById('detail-modal').classList.remove('hidden');
        }

        function closeDetailModal() {
            document.getElementById('detail-modal').classList.add('hidden');
        }

        document.getElementById('detail-modal').addEventListener('click', (e) => {
            if (e.target.id === 'detail-modal') closeDetailModal();
        });

        function requestQuoteFor(itemName) {
            const noteEl = document.getElementById('q-note');
            if (noteEl) {
                noteEl.value = `Tôi cần tư vấn và báo giá chi tiết cho hạng mục: ${itemName}.`;
            }
            document.getElementById('form-bao-gia').scrollIntoView({ behavior: 'smooth' });
            setTimeout(() => document.getElementById('q-name').focus(), 500);
        }

        // Xử lý gửi Form Báo Giá
        document.getElementById('quote-form').addEventListener('submit', function(e) {
            e.preventDefault();
            const name = document.getElementById('q-name').value.trim();
            const phone = document.getElementById('q-phone').value.trim();
            if (!name || !phone) {
                showToast('Vui lòng nhập đầy đủ Họ tên và Số điện thoại để Khang Huy liên hệ.');
                return;
            }
            showToast(`Cảm ơn ${name}! Khang Huy đã nhận yêu cầu và sẽ gọi lại số ${phone} trong ít phút.`);
            this.reset();
        });

        let toastTimer = null;
        function showToast(msg) {
            const toast = document.getElementById('kh-toast');
            document.getElementById('kh-toast-text').textContent = msg;
            toast.classList.remove('hidden');
            if (toastTimer) clearTimeout(toastTimer);
            toastTimer = setTimeout(() => toast.classList.add('hidden'), 4200);
        }

        // Khởi chạy toàn bộ trang khi tải xong
        window.addEventListener('DOMContentLoaded', () => {
            renderCategories();
            renderProducts();
            renderProjects();
            renderArticles();
            renderPartners();
            updateSliderUI();
            resetAutoSlide();
            initBannerSwipe();
        });
    </script>
</body>
</html>
