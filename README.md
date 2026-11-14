<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>CÔNG TY TNHH THƯƠNG MẠI KỸ THUẬT R.O.P | Gia Công Cơ Khí & Thiết Bị Inox Đà Nẵng - cokhirop.com</title>
    <meta name="description" content="CÔNG TY TNHH THƯƠNG MẠI KỸ THUẬT R.O.P (cokhirop.com) chuyên sản xuất, gia công thiết bị bếp công nghiệp, inox nhà hàng khách sạn, cửa cổng xếp, chụp hút khói, quả cầu hút nhiệt, cầu thang lan can inox tại Đà Nẵng. Hotline: 0896.134.234">
    
    <!-- Open Graph Thumbnail là Logo trang web khi gửi link chia sẻ -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://cokhirop.com/">
    <meta property="og:title" content="CÔNG TY TNHH THƯƠNG MẠI KỸ THUẬT R.O.P - Cơ Khí & Inox Đà Nẵng">
    <meta property="og:description" content="Chuyên gia công cơ khí chính xác, thiết bị bếp công nghiệp, chụp hút khói, quả cầu hút nhiệt, cửa cổng xếp, lan can cầu thang inox tại Đà Nẵng. ĐT: 0896.134.234">
    <meta property="og:image" content="https://drive.google.com/thumbnail?id=1_T5cgbludB9TiBT5MLfW9I4mpeMcTrrD&sz=w1200">
    <meta property="og:site_name" content="cokhirop.com">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <!-- Font Inter & Montserrat chuẩn Flatsome -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">
    <!-- Font Awesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        rop: {
                            primary: '#0b4d8c',    /* Xanh cơ khí đậm chủ đạo theo logo */
                            dark: '#073461',       /* Xanh navy đậm cho thanh điều hướng */
                            light: '#eef6ff',      /* Nền xanh nhạt Flatsome section */
                            accent: '#e65100',     /* Cam kim loại điểm nhấn logo */
                            steel: '#475569'       /* Xám inox */
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Đảm bảo tuyệt đối không tràn viền, không lệch sang phải trên mọi thiết bị */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0;
            padding: 0;
            width: 100%;
            max-width: 100vw;
            overflow-x: hidden;
            font-family: 'Inter', sans-serif;
            background-color: #f8fafc;
            color: #1e293b;
            scroll-behavior: smooth;
        }

        /* Khung giao diện chuẩn 95% chiều ngang màn hình máy tính, 100% gọn gàng trên điện thoại */
        .rop-container {
            width: 95%;
            max-width: 95%;
            margin-left: auto;
            margin-right: auto;
        }
        @media (max-width: 767px) {
            .rop-container {
                width: 96%;
                max-width: 96%;
            }
        }

        /* Danh mục viết liền trên 1 hàng chữ nhỏ gọn, tuyệt đối không bị xuống dòng bên trong tên danh mục */
        .cat-pill-item {
            white-space: nowrap !important;
            display: inline-flex;
            align-items: center;
            justify-content: center;
            line-height: 1.2;
            transition: all 0.2s ease;
        }

        /* Tiêu đề Section chuẩn Flatsome UX Builder (Title Style: Center / Divided) */
        .flatsome-section-title {
            display: flex;
            align-items: center;
            justify-content: space-between;
            border-bottom: 2px solid #0b4d8c;
            background: #ffffff;
            border-radius: 6px 6px 0 0;
            overflow: hidden;
        }
        .flatsome-title-main {
            background: linear-gradient(135deg, #0b4d8c 0%, #073461 100%);
            color: #ffffff;
            padding: 10px 18px;
            font-weight: 700;
            font-size: 14px;
            text-transform: uppercase;
            letter-spacing: 0.3px;
            display: inline-flex;
            align-items: center;
            gap: 8px;
            position: relative;
            white-space: nowrap;
        }
        @media (min-width: 1024px) {
            .flatsome-title-main {
                font-size: 15px;
                padding: 11px 22px;
            }
        }

        /* Khung ảnh sản phẩm tỉ lệ đồng đều chuẩn Flatsome Box */
        .product-img-wrap {
            position: relative;
            width: 100%;
            aspect-ratio: 4 / 3;
            background-color: #f1f5f9;
            overflow: hidden;
        }
        .product-img-wrap img {
            width: 100%;
            height: 100%;
            object-fit: cover;
            transition: transform 0.35s ease;
        }
        .product-card:hover .product-img-wrap img {
            transform: scale(1.04);
        }

        /* Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ (không dùng ellipsis), không tràn ra ngoài */
        .product-title-full {
            white-space: normal;
            word-wrap: break-word;
            overflow-wrap: break-word;
            line-height: 1.4;
        }

        /* Hiệu ứng nút liên hệ nổi */
        @keyframes pulseRing {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(230, 81, 0, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(230, 81, 0, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(230, 81, 0, 0); }
        }
        .pulse-btn {
            animation: pulseRing 2s infinite;
        }
    </style>
</head>
<body>

    <!-- =========================================================================
         1. TOP BAR (UX BUILDER: Top Bar - Thông tin địa chỉ & Website cokhirop.com)
    ========================================================================== -->
    <div class="bg-rop-dark text-white text-[11px] sm:text-xs py-1.5 border-b border-white/10">
        <div class="rop-container flex flex-wrap items-center justify-between gap-2">
            <div class="flex items-center gap-2 sm:gap-4 max-w-full overflow-hidden">
                <span class="inline-flex items-center gap-1.5 font-medium text-sky-200 truncate">
                    <i class="fa-solid fa-location-dot text-rop-accent shrink-0"></i>
                    <span class="truncate">Thửa đất số 230 - Tờ bản đồ số 257 – Tổ 26, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
                </span>
            </div>
            <div class="hidden md:flex items-center gap-4 shrink-0 text-slate-200">
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-globe text-sky-300"></i>
                    <strong>cokhirop.com</strong>
                </span>
                <span>|</span>
                <span class="inline-flex items-center gap-1.5">
                    <i class="fa-solid fa-certificate text-amber-400"></i>
                    <span>MST: 0402265510</span>
                </span>
                <span>|</span>
                <a href="https://www.facebook.com/rop.tran.7/" target="_blank" rel="noopener noreferrer" class="hover:text-sky-300 inline-flex items-center gap-1">
                    <i class="fa-brands fa-facebook"></i> Facebook R.O.P
                </a>
            </div>
        </div>
    </div>

    <!-- =========================================================================
         2. HEADER CHÍNH (UX BUILDER: Header Main - Logo nhỏ gọn, KHÔNG để nút gọi ngay tránh tràn viền)
    ========================================================================== -->
    <header class="bg-white shadow-sm sticky top-0 z-40 border-b border-slate-200">
        <div class="rop-container py-2.5 flex items-center justify-between gap-2 sm:gap-4">
            
            <!-- LOGO MỚI CHUYÊN NGHIỆP - ĐÃ CHỈNH GỌN NHỎ LẠI -->
            <a href="#" class="flex items-center gap-2.5 shrink-0 group focus:outline-none">
                <div class="w-10 h-10 sm:w-11 sm:h-11 rounded-lg bg-gradient-to-br from-rop-primary to-rop-dark flex items-center justify-center shadow-sm border border-rop-primary/20 shrink-0">
                    <!-- SVG Logo Cơ Khí R.O.P (Bánh răng cơ khí + Khiên Inox + Chữ R.O.P) -->
                    <svg class="w-8 h-8 sm:w-9 sm:h-9" viewBox="0 0 64 64" fill="none" xmlns="http://www.w3.org/2000/svg">
                        <circle cx="32" cy="32" r="28" stroke="#38bdf8" stroke-width="2" stroke-dasharray="5 3"/>
                        <path d="M32 6L36 11H28L32 6ZM32 58L28 53H36L32 58ZM6 32L11 28V36L6 32ZM58 32L53 36V28L58 32Z" fill="#f97316"/>
                        <rect x="12" y="18" width="40" height="28" rx="5" fill="#073461" stroke="#ffffff" stroke-width="1.8"/>
                        <text x="32" y="36" text-anchor="middle" fill="#ffffff" font-family="Inter, sans-serif" font-weight="800" font-size="13" letter-spacing="0.5">R.O.P</text>
                        <path d="M18 41H46" stroke="#f97316" stroke-width="2.2" stroke-linecap="round"/>
                    </svg>
                </div>
                <div class="leading-tight">
                    <div class="text-xs sm:text-sm md:text-[15px] font-extrabold text-rop-primary tracking-tight">
                        CÔNG TY TNHH TM KỸ THUẬT R.O.P
                    </div>
                    <div class="text-[10px] sm:text-[11px] font-medium text-slate-500 flex items-center gap-1.5">
                        <span class="text-rop-accent font-semibold">cokhirop.com</span>
                        <span class="hidden sm:inline">• Cơ Khí & Thiết Bị Inox Đà Nẵng</span>
                    </div>
                </div>
            </a>

            <!-- Ô TÌM KIẾM SẢN PHẨM TRÊN HEADER (Giống mẫu cokhivanpho.com) -->
            <div class="hidden md:flex flex-1 max-w-md mx-2">
                <div class="relative w-full flex items-center">
                    <input id="searchInputDesktop" type="text" oninput="filterProductsBySearch(this.value)" placeholder="Tìm sản phẩm: Quả cầu hút nhiệt, chụp hút khói, bếp inox, cổng xếp..." class="w-full pl-3.5 pr-10 py-1.5 text-xs bg-slate-50 border border-slate-300 rounded-l-md focus:outline-none focus:border-rop-primary focus:bg-white text-slate-700">
                    <button type="button" onclick="filterProductsBySearch(document.getElementById('searchInputDesktop').value)" class="bg-rop-primary hover:bg-rop-dark text-white px-3.5 py-1.5 rounded-r-md text-xs font-semibold transition">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </div>
            </div>

            <!-- Menu nhanh bên phải (KHÔNG để nút gọi ngay trên Header để tránh tràn viền) -->
            <div class="flex items-center gap-1.5 sm:gap-2 shrink-0">
                <a href="#form-bao-gia" class="text-[11px] sm:text-xs font-semibold bg-rop-light text-rop-primary hover:bg-rop-primary hover:text-white border border-rop-primary/20 px-2.5 py-1.5 rounded-md transition">
                    <i class="fa-solid fa-file-signature mr-1"></i>Nhận Báo Giá
                </a>
                <button type="button" onclick="toggleMobileDrawer()" class="lg:hidden p-2 rounded-md text-rop-primary hover:bg-slate-100 border border-slate-200" aria-label="Mở danh mục">
                    <i class="fa-solid fa-bars text-sm"></i>
                </button>
            </div>
        </div>

        <!-- Ô tìm kiếm gọn trên điện thoại -->
        <div class="md:hidden rop-container pb-2">
            <div class="relative w-full flex items-center">
                <input id="searchInputMobile" type="text" oninput="filterProductsBySearch(this.value)" placeholder="Tìm nhanh thiết bị inox, bếp công nghiệp, cổng xếp..." class="w-full pl-3 pr-9 py-1.5 text-xs bg-slate-50 border border-slate-300 rounded-md focus:outline-none focus:border-rop-primary">
                <i class="fa-solid fa-magnifying-glass text-slate-400 text-xs absolute right-3"></i>
            </div>
        </div>

        <!-- =========================================================================
             3. THANH DANH MỤC SẢN PHẨM TRÊN MÁY TÍNH (Chữ nhỏ gọn, viết liền 1 hàng trong từng mục, nằm trên 1 hàng hoặc xuống hàng 2 gọn gàng, tuyệt đối không gãy chữ)
        ========================================================================== -->
        <nav class="hidden lg:block bg-rop-primary text-white border-t border-rop-dark">
            <div class="rop-container py-1.5">
                <div class="flex flex-wrap items-center justify-center gap-x-1.5 gap-y-1">
                    <a href="#trang-chu" onclick="selectCategory('ALL')" class="cat-pill-item text-[11.5px] font-semibold px-2.5 py-1 rounded bg-rop-accent text-white hover:opacity-95">
                        <i class="fa-solid fa-house mr-1 text-[10px]"></i>Trang Chủ
                    </a>
                    <button type="button" onclick="selectCategory('Thiết Bị Bếp Công Nghiệp')" class="cat-pill-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-white/15">
                        Thiết Bị Bếp Công Nghiệp
                    </button>
                    <button type="button" onclick="selectCategory('Inox Nhà Hàng – Khách Sạn')" class="cat-pill-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-white/15">
                        Inox Nhà Hàng – Khách Sạn
                    </button>
                    <button type="button" onclick="selectCategory('Quả Cầu Hút Nhiệt Inox')" class="cat-pill-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-white/15">
                        Quả Cầu Hút Nhiệt Inox
                    </button>
                    <button type="button" onclick="selectCategory('Chụp Hút Khói')" class="cat-pill-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-white/15">
                        Chụp Hút Khói
                    </button>
                    <button type="button" onclick="selectCategory('Cửa Cổng Xếp')" class="cat-pill-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-white/15">
                        Cửa Cổng Xếp
                    </button>
                    <button type="button" onclick="selectCategory('Cầu Thang – Lan Can Inox')" class="cat-pill-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-white/15">
                        Cầu Thang – Lan Can Inox
                    </button>
                    <button type="button" onclick="selectCategory('Nồi Nấu Phở Điện')" class="cat-pill-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-white/15">
                        Nồi Nấu Phở Điện
                    </button>
                    <button type="button" onclick="selectCategory('Dụng Cụ Y Tế – Thủy Sản')" class="cat-pill-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-white/15">
                        Dụng Cụ Y Tế – Thủy Sản
                    </button>
                    <button type="button" onclick="selectCategory('Bàn Ghế Kệ Inox')" class="cat-pill-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-white/15">
                        Bàn Ghế Kệ Inox
                    </button>
                    <button type="button" onclick="selectCategory('Cột Cờ – Máng Xối Inox')" class="cat-pill-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-white/15">
                        Cột Cờ – Máng Xối Inox
                    </button>
                    <a href="#du-an-da-nang" class="cat-pill-item text-[11.5px] font-semibold px-2 py-1 rounded text-amber-300 hover:bg-white/15">
                        Dự Án Đà Nẵng
                    </a>
                    <a href="#tin-tuc" class="cat-pill-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-white/15">
                        Bài Viết
                    </a>
                    <a href="#lien-he-map" class="cat-pill-item text-[11.5px] font-medium px-2 py-1 rounded hover:bg-white/15">
                        Bản Đồ & Liên Hệ
                    </a>
                </div>
            </div>
        </nav>
    </header>

    <!-- MENU DRAWER CHO ĐIỆN THOẠI -->
    <div id="mobileDrawer" class="fixed inset-0 z-50 hidden">
        <div class="absolute inset-0 bg-slate-900/60" onclick="toggleMobileDrawer()"></div>
        <div class="relative w-72 max-w-[85vw] h-full bg-white shadow-xl flex flex-col justify-between overflow-y-auto">
            <div>
                <div class="p-3.5 bg-rop-primary text-white flex items-center justify-between">
                    <span class="font-bold text-xs uppercase tracking-wider">Danh Mục Sản Phẩm R.O.P</span>
                    <button type="button" onclick="toggleMobileDrawer()" class="w-7 h-7 rounded bg-white/10 flex items-center justify-center">
                        <i class="fa-solid fa-xmark"></i>
                    </button>
                </div>
                <div class="p-2 divide-y divide-slate-100 text-xs font-medium text-slate-700">
                    <button onclick="selectCategory('ALL'); toggleMobileDrawer()" class="w-full text-left py-2.5 px-3 hover:bg-rop-light rounded flex items-center justify-between font-bold text-rop-primary">
                        <span>Tất Cả Sản Phẩm</span><i class="fa-solid fa-chevron-right text-[10px]"></i>
                    </button>
                    <button onclick="selectCategory('Thiết Bị Bếp Công Nghiệp'); toggleMobileDrawer()" class="w-full text-left py-2.5 px-3 hover:bg-rop-light rounded flex items-center justify-between">
                        <span>Thiết Bị Bếp Công Nghiệp</span><i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
                    </button>
                    <button onclick="selectCategory('Inox Nhà Hàng – Khách Sạn'); toggleMobileDrawer()" class="w-full text-left py-2.5 px-3 hover:bg-rop-light rounded flex items-center justify-between">
                        <span>Inox Nhà Hàng – Khách Sạn</span><i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
                    </button>
                    <button onclick="selectCategory('Quả Cầu Hút Nhiệt Inox'); toggleMobileDrawer()" class="w-full text-left py-2.5 px-3 hover:bg-rop-light rounded flex items-center justify-between">
                        <span>Quả Cầu Hút Nhiệt Thông Gió Inox</span><i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
                    </button>
                    <button onclick="selectCategory('Chụp Hút Khói'); toggleMobileDrawer()" class="w-full text-left py-2.5 px-3 hover:bg-rop-light rounded flex items-center justify-between">
                        <span>Chụp Hút Khói Công Nghiệp</span><i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
                    </button>
                    <button onclick="selectCategory('Cửa Cổng Xếp'); toggleMobileDrawer()" class="w-full text-left py-2.5 px-3 hover:bg-rop-light rounded flex items-center justify-between">
                        <span>Cửa Cổng Xếp Inox Tự Động</span><i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
                    </button>
                    <button onclick="selectCategory('Cầu Thang – Lan Can Inox'); toggleMobileDrawer()" class="w-full text-left py-2.5 px-3 hover:bg-rop-light rounded flex items-center justify-between">
                        <span>Cầu Thang – Lan Can Inox</span><i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
                    </button>
                    <button onclick="selectCategory('Nồi Nấu Phở Điện'); toggleMobileDrawer()" class="w-full text-left py-2.5 px-3 hover:bg-rop-light rounded flex items-center justify-between">
                        <span>Nồi Nấu Phở Điện Inox 304</span><i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
                    </button>
                    <button onclick="selectCategory('Dụng Cụ Y Tế – Thủy Sản'); toggleMobileDrawer()" class="w-full text-left py-2.5 px-3 hover:bg-rop-light rounded flex items-center justify-between">
                        <span>Dụng Cụ Inox Y Tế & Thủy Sản</span><i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
                    </button>
                    <button onclick="selectCategory('Bàn Ghế Kệ Inox'); toggleMobileDrawer()" class="w-full text-left py-2.5 px-3 hover:bg-rop-light rounded flex items-center justify-between">
                        <span>Bàn Ghế Kệ Inox – Lò Nướng</span><i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
                    </button>
                    <button onclick="selectCategory('Cột Cờ – Máng Xối Inox'); toggleMobileDrawer()" class="w-full text-left py-2.5 px-3 hover:bg-rop-light rounded flex items-center justify-between">
                        <span>Cột Cờ – Cột Chắn – Máng Xối Inox</span><i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
                    </button>
                    <a href="#du-an-da-nang" onclick="toggleMobileDrawer()" class="block py-2.5 px-3 font-semibold text-rop-primary">Dự Án Thi Công Tại Đà Nẵng</a>
                    <a href="#form-bao-gia" onclick="toggleMobileDrawer()" class="block py-2.5 px-3 font-semibold text-rop-accent">Gửi Yêu Cầu Báo Giá</a>
                </div>
            </div>
            <div class="p-3 bg-slate-50 border-t border-slate-200 text-[11px] text-slate-600">
                <div class="font-bold text-rop-primary">CÔNG TY TNHH TM KỸ THUẬT R.O.P</div>
                <div class="mt-1">ĐT/Zalo: <strong class="text-rop-accent">0896.134.234</strong></div>
                <div class="mt-0.5">Web: cokhirop.com</div>
            </div>
        </div>
    </div>

    <!-- =========================================================================
         4. BANNER TỰ TRƯỢT 2 SLIDE KÍCH THƯỚC BẰNG NHAU
         - Thiết kế riêng phiên bản Banner Máy Tính (hidden md:block) và Banner Điện Thoại (block md:hidden)
         - Chữ bên trong ảnh được chỉnh nhỏ gọn, nằm trọn 100% trong khung, không tràn viền
    ========================================================================== -->
    <section id="trang-chu" class="rop-container mt-3">
        <div class="relative rounded-xl overflow-hidden shadow-md border border-slate-200 bg-rop-dark">

            <!-- ================= PHIÊN BẢN BANNER MÁY TÍNH (2 SLIDE BẰNG NHAU H-340px) ================= -->
            <div class="hidden md:block relative h-[330px] lg:h-[360px] w-full overflow-hidden">
                
                <!-- DESKTOP SLIDE 1 -->
                <div data-desktop-slide="0" class="desktop-slide absolute inset-0 transition-opacity duration-700 opacity-100 flex items-center bg-gradient-to-r from-[#062b52] via-[#0b4d8c] to-[#0f3866]">
                    <div class="w-full h-full grid grid-cols-12 items-center px-8 lg:px-12 gap-6">
                        <div class="col-span-7 text-white space-y-2.5 pr-2">
                            <div class="inline-flex items-center gap-2 bg-white/10 border border-white/20 px-3 py-1 rounded-full text-[11px] font-semibold text-sky-200">
                                <i class="fa-solid fa-gears text-rop-accent"></i> WEBSITE CHÍNH THỨC: COKHIROP.COM
                            </div>
                            <h1 class="text-lg lg:text-2xl font-extrabold leading-snug text-white uppercase tracking-tight">
                                CÔNG TY TNHH THƯƠNG MẠI KỸ THUẬT R.O.P
                            </h1>
                            <p class="text-xs lg:text-sm text-sky-100 leading-relaxed max-w-xl">
                                Chuyên tư vấn, thiết kế, gia công & lắp đặt <strong class="text-amber-300">Thiết bị bếp công nghiệp, Inox nhà hàng khách sạn, Chụp hút khói, Quả cầu hút nhiệt, Cửa cổng xếp, Cầu thang – Lan can Inox 304</strong> uy tín hàng đầu tại Đà Nẵng.
                            </p>
                            <div class="grid grid-cols-2 gap-2 pt-1 text-[11px] lg:text-xs text-slate-100">
                                <div class="flex items-center gap-1.5 bg-white/10 px-2.5 py-1.5 rounded">
                                    <i class="fa-solid fa-circle-check text-amber-400"></i> Inox 304 chính hãng, bền đẹp
                                </div>
                                <div class="flex items-center gap-1.5 bg-white/10 px-2.5 py-1.5 rounded">
                                    <i class="fa-solid fa-circle-check text-amber-400"></i> Gia công theo bản vẽ yêu cầu
                                </div>
                            </div>
                            <div class="pt-2 flex flex-wrap items-center gap-3 text-xs">
                                <span class="bg-rop-accent text-white font-bold px-3.5 py-2 rounded-md shadow">
                                    <i class="fa-solid fa-phone-volume mr-1.5"></i>Hotline: 0896.134.234
                                </span>
                                <span class="bg-slate-900/50 border border-white/15 text-sky-100 px-3 py-2 rounded-md text-[11px]">
                                    <i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>Phường Ngũ Hành Sơn, TP Đà Nẵng
                                </span>
                            </div>
                        </div>
                        <div class="col-span-5 h-[265px] lg:h-[290px] grid grid-cols-2 gap-2.5">
                            <div class="rounded-lg overflow-hidden border-2 border-white/25 shadow-lg bg-slate-800 h-full">
                                <img src="https://lh3.googleusercontent.com/d/1_T5cgbludB9TiBT5MLfW9I4mpeMcTrrD=w800"
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1_T5cgbludB9TiBT5MLfW9I4mpeMcTrrD&sz=w800';"
                                     alt="Xưởng cơ khí kỹ thuật R.O.P Đà Nẵng" class="w-full h-full object-cover">
                            </div>
                            <div class="grid grid-rows-2 gap-2.5 h-full">
                                <div class="rounded-lg overflow-hidden border-2 border-white/25 shadow-lg bg-slate-800">
                                    <img src="https://lh3.googleusercontent.com/d/1rWacsW1RzNHcmx6zFQZc5guUswekrmF_=w800"
                                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1rWacsW1RzNHcmx6zFQZc5guUswekrmF_&sz=w800';"
                                         alt="Gia công thiết bị Inox R.O.P" class="w-full h-full object-cover">
                                </div>
                                <div class="rounded-lg overflow-hidden border-2 border-white/25 shadow-lg bg-slate-800">
                                    <img src="https://lh3.googleusercontent.com/d/1tEVQ6Omaki2HDRb1-RAkdzl236nD1K4P=w800"
                                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1tEVQ6Omaki2HDRb1-RAkdzl236nD1K4P&sz=w800';"
                                         alt="Thi công hệ thống bếp và hút khói" class="w-full h-full object-cover">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>

                <!-- DESKTOP SLIDE 2 (Kích thước bằng tuyệt đối Slide 1) -->
                <div data-desktop-slide="1" class="desktop-slide absolute inset-0 transition-opacity duration-700 opacity-0 pointer-events-none flex items-center bg-gradient-to-r from-[#073461] via-[#0e5ca8] to-[#06294d]">
                    <div class="w-full h-full grid grid-cols-12 items-center px-8 lg:px-12 gap-6">
                        <div class="col-span-7 text-white space-y-2.5 pr-2">
                            <div class="inline-flex items-center gap-2 bg-amber-500/20 border border-amber-400/40 px-3 py-1 rounded-full text-[11px] font-semibold text-amber-300">
                                <i class="fa-solid fa-screwdriver-wrench"></i> XƯỞNG SẢN XUẤT & THI CÔNG TRỰC TIẾP TẠI ĐÀ NẴNG
                            </div>
                            <h2 class="text-lg lg:text-2xl font-extrabold leading-snug text-white uppercase tracking-tight">
                                GIẢI PHÁP CƠ KHÍ INOX TOÀN DIỆN – BÁO GIÁ TẬN XƯỞNG
                            </h2>
                            <p class="text-xs lg:text-sm text-sky-100 leading-relaxed max-w-xl">
                                Thi công trọn gói cho nhà hàng, khách sạn, trường học, bệnh viện, khu công nghiệp tại Đà Nẵng & miền Trung: <strong class="text-amber-300">Nồi nấu phở điện, Bàn ghế kệ inox, Máng xối, Dụng cụ y tế & thủy sản</strong>.
                            </p>
                            <div class="grid grid-cols-2 gap-2 pt-1 text-[11px] lg:text-xs text-slate-100">
                                <div class="flex items-center gap-1.5 bg-white/10 px-2.5 py-1.5 rounded">
                                    <i class="fa-solid fa-truck-fast text-amber-400"></i> Khảo sát & lắp đặt tận nơi Đà Nẵng
                                </div>
                                <div class="flex items-center gap-1.5 bg-white/10 px-2.5 py-1.5 rounded">
                                    <i class="fa-solid fa-shield-halved text-amber-400"></i> Bảo hành kỹ thuật dài hạn 24/7
                                </div>
                            </div>
                            <div class="pt-2 flex flex-wrap items-center gap-3 text-xs">
                                <span class="bg-rop-accent text-white font-bold px-3.5 py-2 rounded-md shadow">
                                    <i class="fa-solid fa-phone mr-1.5"></i>Tư Vấn Kỹ Thuật: 0896.134.234
                                </span>
                                <span class="bg-slate-900/50 border border-white/15 text-sky-100 px-3 py-2 rounded-md text-[11px]">
                                    Thửa đất 230 - Tờ bản đồ 257 – Tổ 26, P. Ngũ Hành Sơn
                                </span>
                            </div>
                        </div>
                        <div class="col-span-5 h-[265px] lg:h-[290px] grid grid-cols-2 gap-2.5">
                            <div class="rounded-lg overflow-hidden border-2 border-white/25 shadow-lg bg-slate-800 h-full">
                                <img src="https://lh3.googleusercontent.com/d/1-8SRNLnjUqjfro_HwX6iB48eYOPV-FeP=w800"
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1-8SRNLnjUqjfro_HwX6iB48eYOPV-FeP&sz=w800';"
                                     alt="Sản phẩm cơ khí R.O.P thực tế" class="w-full h-full object-cover">
                            </div>
                            <div class="grid grid-rows-2 gap-2.5 h-full">
                                <div class="rounded-lg overflow-hidden border-2 border-white/25 shadow-lg bg-slate-800">
                                    <img src="https://lh3.googleusercontent.com/d/1KUj3kjfa1Sn0GDF2Ri9THQAqBcmwO_jG=w800"
                                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1KUj3kjfa1Sn0GDF2Ri9THQAqBcmwO_jG&sz=w800';"
                                         alt="Lắp đặt thiết bị inox công nghiệp" class="w-full h-full object-cover">
                                </div>
                                <div class="rounded-lg overflow-hidden border-2 border-white/25 shadow-lg bg-slate-800">
                                    <img src="https://lh3.googleusercontent.com/d/17LUGwzifUH4Y7XymDaIdRXkPJY9vu7Vl=w800"
                                         onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=17LUGwzifUH4Y7XymDaIdRXkPJY9vu7Vl&sz=w800';"
                                         alt="Gia công inox theo yêu cầu Đà Nẵng" class="w-full h-full object-cover">
                                </div>
                            </div>
                        </div>
                    </div>
                </div>
            </div>

            <!-- ================= PHIÊN BẢN BANNER ĐIỆN THOẠI RIÊNG BIỆT (2 SLIDE BẰNG NHAU H-235px) ================= -->
            <!-- Chữ nhỏ gọn nằm trọn bên trong banner điện thoại, không bị tràn viền -->
            <div class="block md:hidden relative h-[235px] w-full overflow-hidden">
                
                <!-- MOBILE SLIDE 1 -->
                <div data-mobile-slide="0" class="mobile-slide absolute inset-0 transition-opacity duration-700 opacity-100 bg-gradient-to-br from-[#062b52] via-[#0b4d8c] to-[#073461] p-3.5 flex flex-col justify-between">
                    <div class="flex items-center justify-between gap-2">
                        <span class="bg-white/15 text-sky-200 text-[10px] font-semibold px-2 py-0.5 rounded">
                            cokhirop.com • Đà Nẵng
                        </span>
                        <span class="bg-rop-accent text-white text-[10px] font-bold px-2 py-0.5 rounded">
                            0896.134.234
                        </span>
                    </div>
                    <div class="grid grid-cols-12 gap-2.5 items-center my-auto">
                        <div class="col-span-7 text-white space-y-1">
                            <div class="text-xs font-extrabold uppercase leading-tight text-amber-300">
                                CÔNG TY TNHH TM KỸ THUẬT R.O.P
                            </div>
                            <p class="text-[11px] text-sky-100 leading-snug">
                                Gia công Bếp công nghiệp, Chụp hút khói, Quả cầu hút nhiệt, Cổng xếp, Cầu thang lan can Inox.
                            </p>
                        </div>
                        <div class="col-span-5 h-[115px] rounded-lg overflow-hidden border border-white/25 bg-slate-800">
                            <img src="https://lh3.googleusercontent.com/d/1_T5cgbludB9TiBT5MLfW9I4mpeMcTrrD=w600"
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1_T5cgbludB9TiBT5MLfW9I4mpeMcTrrD&sz=w600';"
                                 alt="Cơ khí R.O.P Đà Nẵng" class="w-full h-full object-cover">
                        </div>
                    </div>
                    <div class="text-[10px] text-slate-200 bg-slate-900/40 px-2.5 py-1 rounded truncate">
                        <i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>Thửa 230 - Tờ BĐ 257 – Tổ 26, P. Ngũ Hành Sơn, Đà Nẵng
                    </div>
                </div>

                <!-- MOBILE SLIDE 2 (Kích thước bằng tuyệt đối Slide 1 trên điện thoại) -->
                <div data-mobile-slide="1" class="mobile-slide absolute inset-0 transition-opacity duration-700 opacity-0 pointer-events-none bg-gradient-to-br from-[#073461] via-[#0e5ca8] to-[#06294d] p-3.5 flex flex-col justify-between">
                    <div class="flex items-center justify-between gap-2">
                        <span class="bg-amber-400/20 text-amber-300 text-[10px] font-semibold px-2 py-0.5 rounded">
                            Xưởng Inox 304 Chính Hãng
                        </span>
                        <span class="bg-rop-accent text-white text-[10px] font-bold px-2 py-0.5 rounded">
                            0896.134.234
                        </span>
                    </div>
                    <div class="grid grid-cols-12 gap-2.5 items-center my-auto">
                        <div class="col-span-7 text-white space-y-1">
                            <div class="text-xs font-extrabold uppercase leading-tight text-white">
                                THIẾT BỊ INOX NHÀ HÀNG – Y TẾ – DÂN DỤNG
                            </div>
                            <p class="text-[11px] text-sky-100 leading-snug">
                                Nồi phở điện, Bàn ghế kệ inox, Xe đẩy y tế, Thủy sản, Máng xối. Khảo sát tận nơi Đà Nẵng.
                            </p>
                        </div>
                        <div class="col-span-5 h-[115px] rounded-lg overflow-hidden border border-white/25 bg-slate-800">
                            <img src="https://lh3.googleusercontent.com/d/1rWacsW1RzNHcmx6zFQZc5guUswekrmF_=w600"
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1rWacsW1RzNHcmx6zFQZc5guUswekrmF_&sz=w600';"
                                 alt="Xưởng gia công Inox R.O.P" class="w-full h-full object-cover">
                        </div>
                    </div>
                    <div class="text-[10px] text-slate-200 bg-slate-900/40 px-2.5 py-1 rounded truncate">
                        <i class="fa-solid fa-check-circle text-amber-400 mr-1"></i>Báo giá gốc tại xưởng – Bảo hành uy tín dài hạn
                    </div>
                </div>
            </div>

            <!-- Nút điều hướng Slide Banner -->
            <button type="button" onclick="changeBannerSlide(-1)" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center text-xs transition z-10">
                <i class="fa-solid fa-chevron-left"></i>
            </button>
            <button type="button" onclick="changeBannerSlide(1)" aria-label="Slide tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 w-7 h-7 sm:w-8 sm:h-8 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center text-xs transition z-10">
                <i class="fa-solid fa-chevron-right"></i>
            </button>
            <div class="absolute bottom-2 left-1/2 -translate-x-1/2 flex items-center gap-2 z-10">
                <button type="button" onclick="setBannerSlide(0)" id="bannerDot0" class="w-5 h-1.5 rounded-full bg-amber-400 transition-all"></button>
                <button type="button" onclick="setBannerSlide(1)" id="bannerDot1" class="w-2 h-1.5 rounded-full bg-white/50 transition-all"></button>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         5. DANH MỤC SẢN PHẨM TRANG CHỦ (Tối ưu hiển thị đẹp trên máy tính & điện thoại)
         - Chữ danh mục ở trang chủ nhỏ gọn, viết liền trên 1 hàng, không xuống dòng tên danh mục
    ========================================================================== -->
    <section class="rop-container mt-5">
        <div class="bg-white rounded-xl p-3 sm:p-4 shadow-sm border border-slate-200">
            <div class="flex items-center justify-between mb-3 pb-2 border-b border-slate-100">
                <h2 class="text-xs sm:text-sm font-extrabold text-rop-primary uppercase flex items-center gap-2">
                    <i class="fa-solid fa-layer-group text-rop-accent"></i>
                    <span>DANH MỤC SẢN PHẨM CƠ KHÍ & INOX</span>
                </h2>
                <button type="button" onclick="selectCategory('ALL')" id="activeCatIndicator" class="text-[11px] font-semibold text-rop-accent hover:underline">
                    Đang xem: Tất cả danh mục
                </button>
            </div>

            <!-- Danh mục hiển thị gọn gàng: Tên danh mục nằm trên 1 hàng chữ nhỏ gọn, tuyệt đối không bị xuống dòng -->
            <div class="grid grid-cols-2 sm:grid-cols-3 md:grid-cols-4 lg:grid-cols-6 gap-2">
                <button type="button" onclick="selectCategory('Thiết Bị Bếp Công Nghiệp')" class="cat-box-btn group flex items-center gap-2 p-2 rounded-lg border border-slate-200 hover:border-rop-primary hover:bg-rop-light transition text-left">
                    <span class="w-7 h-7 rounded bg-rop-primary/10 text-rop-primary group-hover:bg-rop-primary group-hover:text-white flex items-center justify-center shrink-0 text-xs">
                        <i class="fa-solid fa-fire-burner"></i>
                    </span>
                    <span class="cat-pill-item text-[11px] sm:text-[11.5px] font-semibold text-slate-700 group-hover:text-rop-primary overflow-hidden">Thiết Bị Bếp Công Nghiệp</span>
                </button>

                <button type="button" onclick="selectCategory('Inox Nhà Hàng – Khách Sạn')" class="cat-box-btn group flex items-center gap-2 p-2 rounded-lg border border-slate-200 hover:border-rop-primary hover:bg-rop-light transition text-left">
                    <span class="w-7 h-7 rounded bg-rop-primary/10 text-rop-primary group-hover:bg-rop-primary group-hover:text-white flex items-center justify-center shrink-0 text-xs">
                        <i class="fa-solid fa-utensils"></i>
                    </span>
                    <span class="cat-pill-item text-[11px] sm:text-[11.5px] font-semibold text-slate-700 group-hover:text-rop-primary overflow-hidden">Inox Nhà Hàng – Khách Sạn</span>
                </button>

                <button type="button" onclick="selectCategory('Quả Cầu Hút Nhiệt Inox')" class="cat-box-btn group flex items-center gap-2 p-2 rounded-lg border border-slate-200 hover:border-rop-primary hover:bg-rop-light transition text-left">
                    <span class="w-7 h-7 rounded bg-rop-primary/10 text-rop-primary group-hover:bg-rop-primary group-hover:text-white flex items-center justify-center shrink-0 text-xs">
                        <i class="fa-solid fa-fan"></i>
                    </span>
                    <span class="cat-pill-item text-[11px] sm:text-[11.5px] font-semibold text-slate-700 group-hover:text-rop-primary overflow-hidden">Quả Cầu Hút Nhiệt Inox</span>
                </button>

                <button type="button" onclick="selectCategory('Chụp Hút Khói')" class="cat-box-btn group flex items-center gap-2 p-2 rounded-lg border border-slate-200 hover:border-rop-primary hover:bg-rop-light transition text-left">
                    <span class="w-7 h-7 rounded bg-rop-primary/10 text-rop-primary group-hover:bg-rop-primary group-hover:text-white flex items-center justify-center shrink-0 text-xs">
                        <i class="fa-solid fa-wind"></i>
                    </span>
                    <span class="cat-pill-item text-[11px] sm:text-[11.5px] font-semibold text-slate-700 group-hover:text-rop-primary overflow-hidden">Chụp Hút Khói Bếp Inox</span>
                </button>

                <button type="button" onclick="selectCategory('Cửa Cổng Xếp')" class="cat-box-btn group flex items-center gap-2 p-2 rounded-lg border border-slate-200 hover:border-rop-primary hover:bg-rop-light transition text-left">
                    <span class="w-7 h-7 rounded bg-rop-primary/10 text-rop-primary group-hover:bg-rop-primary group-hover:text-white flex items-center justify-center shrink-0 text-xs">
                        <i class="fa-solid fa-archway"></i>
                    </span>
                    <span class="cat-pill-item text-[11px] sm:text-[11.5px] font-semibold text-slate-700 group-hover:text-rop-primary overflow-hidden">Cửa Cổng Xếp Inox</span>
                </button>

                <button type="button" onclick="selectCategory('Cầu Thang – Lan Can Inox')" class="cat-box-btn group flex items-center gap-2 p-2 rounded-lg border border-slate-200 hover:border-rop-primary hover:bg-rop-light transition text-left">
                    <span class="w-7 h-7 rounded bg-rop-primary/10 text-rop-primary group-hover:bg-rop-primary group-hover:text-white flex items-center justify-center shrink-0 text-xs">
                        <i class="fa-solid fa-stairs"></i>
                    </span>
                    <span class="cat-pill-item text-[11px] sm:text-[11.5px] font-semibold text-slate-700 group-hover:text-rop-primary overflow-hidden">Cầu Thang – Lan Can Inox</span>
                </button>

                <button type="button" onclick="selectCategory('Nồi Nấu Phở Điện')" class="cat-box-btn group flex items-center gap-2 p-2 rounded-lg border border-slate-200 hover:border-rop-primary hover:bg-rop-light transition text-left">
                    <span class="w-7 h-7 rounded bg-rop-primary/10 text-rop-primary group-hover:bg-rop-primary group-hover:text-white flex items-center justify-center shrink-0 text-xs">
                        <i class="fa-solid fa-bowl-food"></i>
                    </span>
                    <span class="cat-pill-item text-[11px] sm:text-[11.5px] font-semibold text-slate-700 group-hover:text-rop-primary overflow-hidden">Nồi Nấu Phở Điện</span>
                </button>

                <button type="button" onclick="selectCategory('Dụng Cụ Y Tế – Thủy Sản')" class="cat-box-btn group flex items-center gap-2 p-2 rounded-lg border border-slate-200 hover:border-rop-primary hover:bg-rop-light transition text-left">
                    <span class="w-7 h-7 rounded bg-rop-primary/10 text-rop-primary group-hover:bg-rop-primary group-hover:text-white flex items-center justify-center shrink-0 text-xs">
                        <i class="fa-solid fa-kit-medical"></i>
                    </span>
                    <span class="cat-pill-item text-[11px] sm:text-[11.5px] font-semibold text-slate-700 group-hover:text-rop-primary overflow-hidden">Dụng Cụ Y Tế – Thủy Sản</span>
                </button>

                <button type="button" onclick="selectCategory('Bàn Ghế Kệ Inox')" class="cat-box-btn group flex items-center gap-2 p-2 rounded-lg border border-slate-200 hover:border-rop-primary hover:bg-rop-light transition text-left">
                    <span class="w-7 h-7 rounded bg-rop-primary/10 text-rop-primary group-hover:bg-rop-primary group-hover:text-white flex items-center justify-center shrink-0 text-xs">
                        <i class="fa-solid fa-table"></i>
                    </span>
                    <span class="cat-pill-item text-[11px] sm:text-[11.5px] font-semibold text-slate-700 group-hover:text-rop-primary overflow-hidden">Bàn Ghế Kệ Inox</span>
                </button>

                <button type="button" onclick="selectCategory('Lò Nướng Inox')" class="cat-box-btn group flex items-center gap-2 p-2 rounded-lg border border-slate-200 hover:border-rop-primary hover:bg-rop-light transition text-left">
                    <span class="w-7 h-7 rounded bg-rop-primary/10 text-rop-primary group-hover:bg-rop-primary group-hover:text-white flex items-center justify-center shrink-0 text-xs">
                        <i class="fa-solid fa-temperature-high"></i>
                    </span>
                    <span class="cat-pill-item text-[11px] sm:text-[11.5px] font-semibold text-slate-700 group-hover:text-rop-primary overflow-hidden">Lò Nướng Inox</span>
                </button>

                <button type="button" onclick="selectCategory('Cột Cờ – Máng Xối Inox')" class="cat-box-btn group flex items-center gap-2 p-2 rounded-lg border border-slate-200 hover:border-rop-primary hover:bg-rop-light transition text-left">
                    <span class="w-7 h-7 rounded bg-rop-primary/10 text-rop-primary group-hover:bg-rop-primary group-hover:text-white flex items-center justify-center shrink-0 text-xs">
                        <i class="fa-solid fa-flag"></i>
                    </span>
                    <span class="cat-pill-item text-[11px] sm:text-[11.5px] font-semibold text-slate-700 group-hover:text-rop-primary overflow-hidden">Cột Cờ – Cột Chắn Inox</span>
                </button>

                <button type="button" onclick="selectCategory('Cột Cờ – Máng Xối Inox')" class="cat-box-btn group flex items-center gap-2 p-2 rounded-lg border border-slate-200 hover:border-rop-primary hover:bg-rop-light transition text-left">
                    <span class="w-7 h-7 rounded bg-rop-primary/10 text-rop-primary group-hover:bg-rop-primary group-hover:text-white flex items-center justify-center shrink-0 text-xs">
                        <i class="fa-solid fa-water"></i>
                    </span>
                    <span class="cat-pill-item text-[11px] sm:text-[11.5px] font-semibold text-slate-700 group-hover:text-rop-primary overflow-hidden">Máng Xối Inox Công Nghiệp</span>
                </button>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         6. CÁC KHỐI SẢN PHẨM THEO DANH MỤC (Giống web mẫu cokhivanpho.com)
         - Tích hợp đầy đủ 11 ảnh thực tế từ Google Drive vào đúng danh mục & sản phẩm
         - Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4)
         - KHÔNG để các nhãn dán (HOT, SALE, NEW...) ở trang chủ
         - Tên sản phẩm hiển thị đầy đủ, không bị tràn ra ngoài hoặc thiếu chữ
    ========================================================================== -->
    <main id="danh-sach-san-pham" class="rop-container space-y-6 mt-6">
        <!-- Nội dung các Section sản phẩm được render tự động từ dữ liệu chuẩn bên dưới để vừa dễ lọc vừa giữ cấu trúc Flatsome đơn giản -->
    </main>

    <!-- =========================================================================
         7. DANH MỤC CÁC DỰ ÁN THỰC TẾ TẠI ĐÀ NẴNG (Sử dụng ảnh thực tế từ Google Drive)
    ========================================================================== -->
    <section id="du-an-da-nang" class="rop-container mt-8">
        <div class="flatsome-section-title shadow-sm">
            <div class="flatsome-title-main">
                <i class="fa-solid fa-building-circle-check text-amber-400"></i>
                <span>DỰ ÁN THI CÔNG THỰC TẾ TẠI ĐÀ NẴNG</span>
            </div>
            <a href="#form-bao-gia" class="text-xs font-semibold text-rop-primary hover:text-rop-accent px-3 py-1">
                Đăng ký khảo sát tận nơi <i class="fa-solid fa-arrow-right ml-1"></i>
            </a>
        </div>

        <div class="bg-white p-3 sm:p-4 rounded-b-xl shadow-sm border border-t-0 border-slate-200">
            <!-- Chia 2 cột trên điện thoại, 4 cột trên máy tính -->
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
                
                <!-- Dự án 1 -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <div>
                        <div class="product-img-wrap">
                            <img src="https://lh3.googleusercontent.com/d/1_T5cgbludB9TiBT5MLfW9I4mpeMcTrrD=w800"
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1_T5cgbludB9TiBT5MLfW9I4mpeMcTrrD&sz=w800';"
                                 alt="Thi công hệ thống bếp inox và chụp hút khói tại Ngũ Hành Sơn, Đà Nẵng">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800">
                                Thi Công Hệ Thống Bếp Công Nghiệp & Chụp Hút Khói Tại Ngũ Hành Sơn, Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1 leading-relaxed">
                                Gia công trọn gói hệ thống bếp Á, bàn sơ chế, bồn rửa và chụp hút khói inox 304 cho khu ẩm thực ven biển Đà Nẵng.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3">
                        <a href="#form-bao-gia" onclick="prefillQuote('Dự án Bếp Công Nghiệp & Chụp Hút Khói Đà Nẵng')" class="block w-full text-center text-[11px] sm:text-xs font-semibold py-1.5 rounded bg-slate-100 hover:bg-rop-primary hover:text-white text-rop-primary transition">
                            Nhận báo giá hạng mục này
                        </a>
                    </div>
                </div>

                <!-- Dự án 2 -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <div>
                        <div class="product-img-wrap">
                            <img src="https://lh3.googleusercontent.com/d/11clRK_a8Pv8ThFLY4E6TlhEkqne0DuOr=w800"
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=11clRK_a8Pv8ThFLY4E6TlhEkqne0DuOr&sz=w800';"
                                 alt="Lắp đặt cửa cổng xếp inox tự động tại KCN Hòa Khánh, Đà Nẵng">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800">
                                Lắp Đặt Cửa Cổng Xếp Inox 304 Tự Động Tại Khu Công Nghiệp Hòa Khánh, Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1 leading-relaxed">
                                Cổng xếp inox điều khiển từ xa kết hợp motor cảm ứng từ hiện đại, vận hành êm ái và bền bỉ dưới thời tiết miền Trung.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3">
                        <a href="#form-bao-gia" onclick="prefillQuote('Dự án Cửa Cổng Xếp Inox Tự Động Đà Nẵng')" class="block w-full text-center text-[11px] sm:text-xs font-semibold py-1.5 rounded bg-slate-100 hover:bg-rop-primary hover:text-white text-rop-primary transition">
                            Nhận báo giá hạng mục này
                        </a>
                    </div>
                </div>

                <!-- Dự án 3 -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <div>
                        <div class="product-img-wrap">
                            <img src="https://lh3.googleusercontent.com/d/1qav0ioO9ax7buKGnhiLrIh15oXQPn3Kq=w800"
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1qav0ioO9ax7buKGnhiLrIh15oXQPn3Kq&sz=w800';"
                                 alt="Lắp đặt quả cầu hút nhiệt thông gió mái nhà xưởng tại Cẩm Lệ, Đà Nẵng">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800">
                                Lắp Đặt Quả Cầu Hút Nhiệt Thông Gió & Máng Xối Inox Nhà Xưởng Cẩm Lệ, Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1 leading-relaxed">
                                Thi công đồng bộ hệ thống quả cầu thông gió inox 304 chống dột tuyệt đối, giúp làm mát nhà xưởng tự nhiên.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3">
                        <a href="#form-bao-gia" onclick="prefillQuote('Dự án Quả Cầu Hút Nhiệt & Máng Xối Inox Đà Nẵng')" class="block w-full text-center text-[11px] sm:text-xs font-semibold py-1.5 rounded bg-slate-100 hover:bg-rop-primary hover:text-white text-rop-primary transition">
                            Nhận báo giá hạng mục này
                        </a>
                    </div>
                </div>

                <!-- Dự án 4 -->
                <div class="bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <div>
                        <div class="product-img-wrap">
                            <img src="https://lh3.googleusercontent.com/d/1CAg0RNyav6zP7W_JZ4BxMya9JuTnFwRd=w800"
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1CAg0RNyav6zP7W_JZ4BxMya9JuTnFwRd&sz=w800';"
                                 alt="Thi công lan can cầu thang inox và thiết bị inox khách sạn Sơn Trà, Đà Nẵng">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800">
                                Gia Công Cầu Thang, Lan Can Inox & Thiết Bị Nhà Hàng Tại Sơn Trà, Đà Nẵng
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1 leading-relaxed">
                                Hoàn thiện hệ thống lan can ban công inox 304 chống gỉ muối biển, bàn kệ inox và xe đẩy phục vụ khách sạn.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3">
                        <a href="#form-bao-gia" onclick="prefillQuote('Dự án Cầu Thang Lan Can & Thiết Bị Khách Sạn Đà Nẵng')" class="block w-full text-center text-[11px] sm:text-xs font-semibold py-1.5 rounded bg-slate-100 hover:bg-rop-primary hover:text-white text-rop-primary transition">
                            Nhận báo giá hạng mục này
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- =========================================================================
         8. FORM YÊU CẦU VÀ BÁO GIÁ TRANG CHỦ + CAM KẾT KỸ THUẬT R.O.P
    ========================================================================== -->
    <section id="form-bao-gia" class="rop-container mt-8">
        <div class="bg-gradient-to-br from-rop-primary to-rop-dark rounded-xl p-4 sm:p-6 shadow-md text-white">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-6 items-center">
                
                <!-- Cột thông tin kỹ thuật -->
                <div class="lg:col-span-5 space-y-3">
                    <div class="inline-block bg-white/10 text-amber-300 text-xs font-bold px-3 py-1 rounded">
                        NHẬN BÁO GIÁ GỐC TẠI XƯỞNG R.O.P
                    </div>
                    <h2 class="text-base sm:text-xl font-extrabold uppercase leading-snug">
                        GỬI YÊU CẦU TƯ VẤN KỸ THUẬT & BÁO GIÁ NHANH
                    </h2>
                    <p class="text-xs sm:text-sm text-sky-100 leading-relaxed">
                        Quý khách cần gia công thiết bị bếp công nghiệp, chụp hút khói, quả cầu hút nhiệt, cửa cổng xếp hay thiết bị inox theo kích thước riêng? Hãy để lại thông tin, kỹ sư của <strong>CÔNG TY TNHH TM KỸ THUẬT R.O.P</strong> sẽ liên hệ báo giá chi tiết trong vòng 15 phút.
                    </p>
                    <div class="space-y-2 pt-1 text-xs text-sky-100">
                        <div class="flex items-center gap-2.5">
                            <i class="fa-solid fa-phone-volume text-amber-400 w-4"></i>
                            <span>Hotline/Zalo trực tiếp: <strong class="text-white text-sm">0896.134.234</strong></span>
                        </div>
                        <div class="flex items-center gap-2.5">
                            <i class="fa-solid fa-location-dot text-amber-400 w-4"></i>
                            <span>Địa chỉ: Thửa đất số 230 - Tờ bản đồ số 257 – Tổ 26, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
                        </div>
                        <div class="flex items-center gap-2.5">
                            <i class="fa-solid fa-globe text-amber-400 w-4"></i>
                            <span>Website: <strong>cokhirop.com</strong></span>
                        </div>
                    </div>
                </div>

                <!-- Cột Form Báo Giá -->
                <div class="lg:col-span-7 bg-white text-slate-800 rounded-xl p-4 sm:p-5 shadow">
                    <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-3">
                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Họ và tên quý khách *</label>
                                <input id="qName" type="text" required placeholder="Nhập họ và tên..." class="w-full px-3 py-2 text-xs border border-slate-300 rounded-md focus:outline-none focus:border-rop-primary">
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                <input id="qPhone" type="tel" required placeholder="Nhập SĐT liên hệ (VD: 0905...)" class="w-full px-3 py-2 text-xs border border-slate-300 rounded-md focus:outline-none focus:border-rop-primary">
                            </div>
                        </div>

                        <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Danh mục sản phẩm cần báo giá *</label>
                                <select id="qCategory" class="w-full px-3 py-2 text-xs border border-slate-300 rounded-md focus:outline-none focus:border-rop-primary bg-white">
                                    <option value="Thiết Bị Bếp Công Nghiệp">Thiết Bị Bếp Công Nghiệp</option>
                                    <option value="Inox Nhà Hàng – Khách Sạn">Inox Nhà Hàng – Khách Sạn</option>
                                    <option value="Quả Cầu Hút Nhiệt Thông Gió Inox">Quả Cầu Hút Nhiệt Thông Gió Inox</option>
                                    <option value="Chụp Hút Khói Bếp Công Nghiệp">Chụp Hút Khói Bếp Công Nghiệp</option>
                                    <option value="Cửa Cổng Xếp Inox">Cửa Cổng Xếp Inox</option>
                                    <option value="Cầu Thang – Lan Can Inox">Cầu Thang – Lan Can Inox</option>
                                    <option value="Nồi Nấu Phở Điện Inox 304">Nồi Nấu Phở Điện Inox 304</option>
                                    <option value="Dụng Cụ Inox Y Tế – Thủy Sản">Dụng Cụ Inox Y Tế – Thủy Sản</option>
                                    <option value="Bàn Ghế Kệ – Lò Nướng – Máng Xối Inox">Bàn Ghế Kệ – Lò Nướng – Máng Xối Inox</option>
                                    <option value="Gia công cơ khí theo bản vẽ yêu cầu">Gia công cơ khí theo bản vẽ yêu cầu</option>
                                </select>
                            </div>
                            <div>
                                <label class="block text-xs font-bold text-slate-700 mb-1">Địa điểm công trình / giao hàng</label>
                                <input id="qAddress" type="text" placeholder="VD: Ngũ Hành Sơn, Đà Nẵng..." class="w-full px-3 py-2 text-xs border border-slate-300 rounded-md focus:outline-none focus:border-rop-primary">
                            </div>
                        </div>

                        <div>
                            <label class="block text-xs font-bold text-slate-700 mb-1">Nội dung yêu cầu / Kích thước cần gia công</label>
                            <textarea id="qNote" rows="3" placeholder="Mô tả sản phẩm, số lượng, quy cách kích thước hoặc yêu cầu khảo sát thực tế..." class="w-full px-3 py-2 text-xs border border-slate-300 rounded-md focus:outline-none focus:border-rop-primary"></textarea>
                        </div>

                        <div class="flex flex-wrap items-center justify-between gap-2 pt-1">
                            <button type="submit" class="bg-rop-accent hover:bg-orange-700 text-white font-bold text-xs sm:text-sm px-5 py-2.5 rounded-md shadow transition flex items-center gap-2">
                                <i class="fa-solid fa-paper-plane"></i>
                                <span>GỬI YÊU CẦU BÁO GIÁ NGAY</span>
                            </button>
                            <a href="tel:0896134234" class="text-xs font-bold text-rop-primary hover:underline">
                                Hoặc gọi trực tiếp: 0896.134.234
                            </a>
                        </div>

                        <!-- Thông báo gửi thành công (thay thế hoàn toàn alert) -->
                        <div id="quoteSuccessBox" class="hidden p-3 rounded-md bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs font-medium"></div>
                    </form>
                </div>

            </div>
        </div>
    </section>

    <!-- =========================================================================
         9. DANH MỤC CÁC BÀI VIẾT / TIN TỨC TRANG CHỦ (Giống mẫu cokhivanpho.com)
    ========================================================================== -->
    <section id="tin-tuc" class="rop-container mt-8">
        <div class="flatsome-section-title shadow-sm">
            <div class="flatsome-title-main">
                <i class="fa-solid fa-newspaper text-amber-400"></i>
                <span>TIN TỨC & KINH NGHIỆM CƠ KHÍ INOX</span>
            </div>
            <span class="text-xs text-slate-500 px-3 hidden sm:inline">Cập nhật kiến thức kỹ thuật hữu ích từ R.O.P</span>
        </div>

        <div class="bg-white p-3 sm:p-4 rounded-b-xl shadow-sm border border-t-0 border-slate-200">
            <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
                
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <div>
                        <div class="product-img-wrap">
                            <img src="https://lh3.googleusercontent.com/d/1YTjrek7h3j5fHGGrcQ7kizosZvCx300Q=w800"
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1YTjrek7h3j5fHGGrcQ7kizosZvCx300Q&sz=w800';"
                                 alt="Quả Cầu Hút Nhiệt Đà Nẵng – Lắp Một Lần Dùng Bền Lâu">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-rop-primary">
                                Quả Cầu Hút Nhiệt Inox Đà Nẵng – Giải Pháp Chống Nóng Mái Nhà & Nhà Xưởng Hiệu Quả
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5 leading-relaxed">
                                Tìm hiểu nguyên lý đối lưu tự nhiên của quả cầu thông gió inox 304 giúp giảm nhiệt độ tầng áp mái và nhà xưởng mà không tốn điện năng.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3 text-[11px] font-semibold text-rop-primary">
                        <span>Tư vấn kỹ thuật: 0896.134.234</span>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <div>
                        <div class="product-img-wrap">
                            <img src="https://lh3.googleusercontent.com/d/1tEVQ6Omaki2HDRb1-RAkdzl236nD1K4P=w800"
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1tEVQ6Omaki2HDRb1-RAkdzl236nD1K4P&sz=w800';"
                                 alt="Chụp Hút Khói Bếp Công Nghiệp Đà Nẵng">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-rop-primary">
                                Chụp Hút Khói Bếp Công Nghiệp Đà Nẵng – Thiết Kế Chuẩn Lưu Lượng, Không Ám Mùi
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5 leading-relaxed">
                                Kinh nghiệm lựa chọn kích thước chụp hút khói inox có phin lọc mỡ và hộp hứng mỡ cho bếp nhà hàng, quán ăn, bếp ăn tập thể.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3 text-[11px] font-semibold text-rop-primary">
                        <span>Tư vấn kỹ thuật: 0896.134.234</span>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <div>
                        <div class="product-img-wrap">
                            <img src="https://lh3.googleusercontent.com/d/1tg5dEZmEqoDksUgkU9e7qyAOn4_EbcbV=w800"
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1tg5dEZmEqoDksUgkU9e7qyAOn4_EbcbV&sz=w800';"
                                 alt="Nồi Nấu Phở Điện Inox 304 Đà Nẵng">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-rop-primary">
                                Nồi Nấu Phở Điện Inox 304 Đà Nẵng – Tiết Kiệm Điện, An Toàn Cho Quán Bún Phở
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5 leading-relaxed">
                                Cách chọn dung tích nồi hầm xương, nồi nấu nước lèo và nồi nhúng bánh từ 20L đến 160L phù hợp với quy mô kinh doanh.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3 text-[11px] font-semibold text-rop-primary">
                        <span>Tư vấn kỹ thuật: 0896.134.234</span>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden flex flex-col justify-between">
                    <div>
                        <div class="product-img-wrap">
                            <img src="https://lh3.googleusercontent.com/d/11clRK_a8Pv8ThFLY4E6TlhEkqne0DuOr=w800"
                                 onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=11clRK_a8Pv8ThFLY4E6TlhEkqne0DuOr&sz=w800';"
                                 alt="Cửa Cổng Xếp & Cầu Thang Lan Can Inox Đà Nẵng">
                        </div>
                        <div class="p-2.5 sm:p-3">
                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-rop-primary">
                                Cửa Cổng Xếp & Lan Can Cầu Thang Inox Đà Nẵng – Bền Đẹp Với Khí Hậu Ven Biển
                            </h3>
                            <p class="text-[11px] text-slate-500 mt-1.5 leading-relaxed">
                                Vì sao nên ưu tiên chất liệu Inox 304 dày dặn khi thi công cổng xếp tự động, lan can ban công và cầu thang tại khu vực Đà Nẵng.
                            </p>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3 text-[11px] font-semibold text-rop-primary">
                        <span>Tư vấn kỹ thuật: 0896.134.234</span>
                    </div>
                </article>

            </div>
        </div>
    </section>

    <!-- =========================================================================
         10. ĐƯA GOOGLE MAP VÀ FACEBOOK RA NGOÀI TRANG CHỦ
         - Google Map: Thửa đất số 230 - Tờ bản đồ số 257 – Tổ 26, Phường Ngũ Hành Sơn, TP Đà Nẵng
         - Facebook: https://www.facebook.com/rop.tran.7/
    ========================================================================== -->
    <section id="lien-he-map" class="rop-container mt-8">
        <div class="flatsome-section-title shadow-sm">
            <div class="flatsome-title-main">
                <i class="fa-solid fa-map-location-dot text-amber-400"></i>
                <span>BẢN ĐỒ GOOGLE MAPS & KẾT NỐI FACEBOOK TRANG CHỦ</span>
            </div>
            <span class="text-xs text-slate-500 px-3 hidden sm:inline">Thửa đất số 230 - Tờ bản đồ số 257 – Tổ 26, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
        </div>

        <div class="bg-white p-3 sm:p-5 rounded-b-xl shadow-sm border border-t-0 border-slate-200">
            <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-stretch">
                
                <!-- BẢN ĐỒ GOOGLE MAPS TRỰC TIẾP NGOÀI TRANG CHỦ (7 CỘT) -->
                <div class="lg:col-span-7 flex flex-col justify-between rounded-xl overflow-hidden border border-slate-200 bg-slate-50">
                    <div class="p-3 bg-slate-100 border-b border-slate-200 flex flex-wrap items-center justify-between gap-2">
                        <div class="text-xs font-bold text-rop-primary flex items-center gap-1.5">
                            <i class="fa-solid fa-location-dot text-rop-accent"></i>
                            <span>Vị trí: Thửa đất số 230 - Tờ bản đồ số 257 – Tổ 26, Phường Ngũ Hành Sơn, TP Đà Nẵng</span>
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=Ph%C6%B0%E1%BB%9Dng+Ng%C5%A9+H%C3%A0nh+S%C6%A1n+TP+%C4%90%C3%A0+N%E1%BA%B5ng" target="_blank" rel="noopener noreferrer" class="text-[11px] font-bold bg-rop-primary text-white px-2.5 py-1 rounded hover:bg-rop-dark transition">
                            <i class="fa-solid fa-diamond-turn-right mr-1"></i>Mở Bản Đồ Lớn
                        </a>
                    </div>
                    <div class="w-full h-[270px] sm:h-[310px]">
                        <iframe
                            title="Bản đồ Google Map Công ty TNHH Thương Mại Kỹ Thuật R.O.P"
                            src="https://maps.google.com/maps?q=Ng%C5%A9%20H%C3%A0nh%20S%C6%A1n,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=14&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>

                <!-- KHUNG FACEBOOK CHÍNH THỨC NGOÀI TRANG CHỦ (5 CỘT) -->
                <div class="lg:col-span-5 flex flex-col justify-between rounded-xl border border-slate-200 bg-white p-4">
                    <div>
                        <div class="flex items-center justify-between border-b border-slate-100 pb-3">
                            <div class="flex items-center gap-2.5">
                                <div class="w-10 h-10 rounded-full bg-[#1877F2] text-white flex items-center justify-center text-lg shadow-sm">
                                    <i class="fa-brands fa-facebook-f"></i>
                                </div>
                                <div>
                                    <div class="text-xs sm:text-sm font-extrabold text-slate-800">Facebook Chính Thức R.O.P</div>
                                    <div class="text-[11px] text-slate-500">facebook.com/rop.tran.7</div>
                                </div>
                            </div>
                            <a href="https://www.facebook.com/rop.tran.7/" target="_blank" rel="noopener noreferrer" class="bg-[#1877F2] hover:bg-blue-700 text-white text-xs font-semibold px-3 py-1.5 rounded-md transition">
                                Kết nối ngay
                            </a>
                        </div>

                        <div class="mt-3 rounded-lg overflow-hidden border border-slate-200 bg-slate-50">
                            <div class="grid grid-cols-3 gap-1 p-1 bg-slate-200 h-32">
                                <img src="https://lh3.googleusercontent.com/d/1_T5cgbludB9TiBT5MLfW9I4mpeMcTrrD=w400"
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1_T5cgbludB9TiBT5MLfW9I4mpeMcTrrD&sz=w400';"
                                     alt="Hình ảnh thực tế Facebook R.O.P 1" class="w-full h-full object-cover rounded-sm">
                                <img src="https://lh3.googleusercontent.com/d/1rWacsW1RzNHcmx6zFQZc5guUswekrmF_=w400"
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1rWacsW1RzNHcmx6zFQZc5guUswekrmF_&sz=w400';"
                                     alt="Hình ảnh thực tế Facebook R.O.P 2" class="w-full h-full object-cover rounded-sm">
                                <img src="https://lh3.googleusercontent.com/d/1tEVQ6Omaki2HDRb1-RAkdzl236nD1K4P=w400"
                                     onerror="this.onerror=null;this.src='https://drive.google.com/thumbnail?id=1tEVQ6Omaki2HDRb1-RAkdzl236nD1K4P&sz=w400';"
                                     alt="Hình ảnh thực tế Facebook R.O.P 3" class="w-full h-full object-cover rounded-sm">
                            </div>
                            <div class="p-3 text-xs text-slate-600 space-y-1.5">
                                <div class="font-bold text-slate-800">CÔNG TY TNHH THƯƠNG MẠI KỸ THUẬT R.O.P</div>
                                <p class="text-[11px] leading-relaxed">
                                    Theo dõi hình ảnh xuất xưởng, video lắp đặt thực tế các công trình cơ khí inox, bếp công nghiệp, cổng xếp, chụp hút khói hàng ngày trên Facebook chính thức.
                                </p>
                            </div>
                        </div>
                    </div>

                    <div class="mt-3 pt-3 border-t border-slate-100 flex flex-wrap items-center justify-between gap-2">
                        <a href="https://www.facebook.com/rop.tran.7/" target="_blank" rel="noopener noreferrer" class="w-full text-center bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-xs py-2.5 rounded-lg transition flex items-center justify-center gap-2">
                            <i class="fa-brands fa-facebook text-sm"></i>
                            <span>XEM TRANG FACEBOOK: FACEBOOK.COM/ROP.TRAN.7</span>
                        </a>
                    </div>
                </div>

            </div>
        </div>
    </section>

    <!-- =========================================================================
         11. DANH MỤC ĐỐI TÁC & KHÁCH HÀNG TIÊU BIỂU
    ========================================================================== -->
    <section id="doi-tac" class="rop-container mt-8 mb-10">
        <div class="bg-white rounded-xl p-4 shadow-sm border border-slate-200">
            <div class="flex items-center justify-between mb-3 pb-2 border-b border-slate-100">
                <h2 class="text-xs sm:text-sm font-extrabold text-rop-primary uppercase flex items-center gap-2">
                    <i class="fa-solid fa-handshake text-rop-accent"></i>
                    <span>ĐỐI TÁC & KHÁCH HÀNG ĐỒNG HÀNH CÙNG R.O.P</span>
                </h2>
                <span class="text-[11px] text-slate-500 hidden sm:inline">Cung cấp vật tư Inox POSCO, Tiến Đạt, Hòa Phát & khối Nhà hàng - Khu công nghiệp Đà Nẵng</span>
            </div>

            <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5 text-center">
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center">
                    <div class="text-xs font-extrabold text-rop-primary">INOX POSCO VST</div>
                    <div class="text-[10px] text-slate-500 mt-0.5">Đối tác vật tư Inox 304</div>
                </div>
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center">
                    <div class="text-xs font-extrabold text-rop-primary">TẬP ĐOÀN HÒA PHÁT</div>
                    <div class="text-[10px] text-slate-500 mt-0.5">Ống thép & Inox công nghiệp</div>
                </div>
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center">
                    <div class="text-xs font-extrabold text-rop-primary">INOX TIẾN ĐẠT</div>
                    <div class="text-[10px] text-slate-500 mt-0.5">Vật tư phụ kiện chuẩn</div>
                </div>
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center">
                    <div class="text-xs font-extrabold text-rop-primary">KCN HÒA KHÁNH</div>
                    <div class="text-[10px] text-slate-500 mt-0.5">Khách hàng nhà xưởng</div>
                </div>
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center">
                    <div class="text-xs font-extrabold text-rop-primary">KHỐI NHÀ HÀNG BIỂN</div>
                    <div class="text-[10px] text-slate-500 mt-0.5">Ngũ Hành Sơn – Sơn Trà</div>
                </div>
                <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 flex flex-col items-center justify-center">
                    <div class="text-xs font-extrabold text-rop-primary">KHỐI TRƯỜNG & Y TẾ</div>
                    <div class="text-[10px] text-slate-500 mt-0.5">Bếp ăn & Thiết bị y tế</div>
                </div>
            </div>
        </div>
    </section>

    <!-- =========================================================================
         12. FOOTER (Chân trang chuẩn Flatsome)
    ========================================================================== -->
    <footer class="bg-rop-dark text-slate-200 pt-8 pb-20 md:pb-8 border-t-4 border-rop-accent">
        <div class="rop-container grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-white/10">
            
            <!-- Thông tin công ty -->
            <div class="lg:col-span-5 space-y-2.5">
                <div class="text-sm sm:text-base font-extrabold text-white uppercase">
                    CÔNG TY TNHH THƯƠNG MẠI KỸ THUẬT R.O.P
                </div>
                <p class="text-xs text-slate-300 leading-relaxed">
                    Đơn vị chuyên sản xuất, gia công và lắp đặt thiết bị bếp công nghiệp, inox nhà hàng khách sạn, cửa cổng xếp, chụp hút khói, quả cầu hút nhiệt thông gió, cầu thang lan can inox, nồi nấu phở điện và thiết bị inox y tế - thủy sản tại TP. Đà Nẵng.
                </p>
                <div class="space-y-1.5 text-xs text-slate-200 pt-1">
                    <div><i class="fa-solid fa-location-dot text-amber-400 w-5"></i><strong>Địa chỉ:</strong> Thửa đất số 230 - Tờ bản đồ số 257 – Tổ 26, Phường Ngũ Hành Sơn, TP Đà Nẵng</div>
                    <div><i class="fa-solid fa-phone text-amber-400 w-5"></i><strong>Điện thoại / Zalo:</strong> <a href="tel:0896134234" class="text-amber-300 font-bold">0896.134.234</a></div>
                    <div><i class="fa-solid fa-globe text-amber-400 w-5"></i><strong>Website:</strong> <a href="https://cokhirop.com" class="text-sky-300">cokhirop.com</a></div>
                    <div><i class="fa-brands fa-facebook text-amber-400 w-5"></i><strong>Facebook:</strong> <a href="https://www.facebook.com/rop.tran.7/" target="_blank" rel="noopener noreferrer" class="text-sky-300 hover:underline">facebook.com/rop.tran.7</a></div>
                </div>
            </div>

            <!-- Danh mục sản phẩm -->
            <div class="lg:col-span-4 space-y-2">
                <div class="text-xs sm:text-sm font-bold text-white uppercase border-b border-white/15 pb-1.5">
                    DANH MỤC SẢN PHẨM CHỦ LỰC
                </div>
                <div class="grid grid-cols-2 gap-1.5 text-xs text-slate-300">
                    <a href="#danh-sach-san-pham" onclick="selectCategory('Thiết Bị Bếp Công Nghiệp')" class="hover:text-amber-300">• Thiết Bị Bếp Công Nghiệp</a>
                    <a href="#danh-sach-san-pham" onclick="selectCategory('Cửa Cổng Xếp')" class="hover:text-amber-300">• Cửa Cổng Xếp Inox</a>
                    <a href="#danh-sach-san-pham" onclick="selectCategory('Inox Nhà Hàng – Khách Sạn')" class="hover:text-amber-300">• Nhà Hàng Khách Sạn</a>
                    <a href="#danh-sach-san-pham" onclick="selectCategory('Dụng Cụ Y Tế – Thủy Sản')" class="hover:text-amber-300">• Dụng Cụ Y Tế & Thủy Sản</a>
                    <a href="#danh-sach-san-pham" onclick="selectCategory('Bàn Ghế Kệ Inox')" class="hover:text-amber-300">• Bàn Ghế Kệ Inox</a>
                    <a href="#danh-sach-san-pham" onclick="selectCategory('Nồi Nấu Phở Điện')" class="hover:text-amber-300">• Nồi Nấu Phở Điện</a>
                    <a href="#danh-sach-san-pham" onclick="selectCategory('Chụp Hút Khói')" class="hover:text-amber-300">• Chụp Hút Khói Bếp</a>
                    <a href="#danh-sach-san-pham" onclick="selectCategory('Quả Cầu Hút Nhiệt Inox')" class="hover:text-amber-300">• Quả Cầu Hút Nhiệt Inox</a>
                    <a href="#danh-sach-san-pham" onclick="selectCategory('Cầu Thang – Lan Can Inox')" class="hover:text-amber-300">• Cầu Thang – Lan Can Inox</a>
                    <a href="#danh-sach-san-pham" onclick="selectCategory('Cột Cờ – Máng Xối Inox')" class="hover:text-amber-300">• Cột Cờ – Máng Xối Inox</a>
                </div>
            </div>

            <!-- Hỗ trợ khách hàng -->
            <div class="lg:col-span-3 space-y-2">
                <div class="text-xs sm:text-sm font-bold text-white uppercase border-b border-white/15 pb-1.5">
                    LIÊN KẾT NHANH
                </div>
                <ul class="space-y-1.5 text-xs text-slate-300">
                    <li><a href="#trang-chu" class="hover:text-amber-300">Trang chủ cokhirop.com</a></li>
                    <li><a href="#du-an-da-nang" class="hover:text-amber-300">Dự án tiêu biểu tại Đà Nẵng</a></li>
                    <li><a href="#form-bao-gia" class="hover:text-amber-300">Yêu cầu khảo sát & báo giá</a></li>
                    <li><a href="#tin-tuc" class="hover:text-amber-300">Tin tức & kinh nghiệm inox</a></li>
                    <li><a href="#lien-he-map" class="hover:text-amber-300">Bản đồ chỉ đường Google Maps</a></li>
                </ul>
            </div>
        </div>

        <div class="rop-container pt-4 flex flex-wrap items-center justify-between gap-2 text-[11px] text-slate-400">
            <div>© Bản quyền thuộc về <strong class="text-white">CÔNG TY TNHH THƯƠNG MẠI KỸ THUẬT R.O.P</strong> (cokhirop.com).</div>
            <div>Thiết kế chuẩn giao diện Flatsome UX Builder – Tối ưu Máy tính & Điện thoại.</div>
        </div>
    </footer>

    <!-- =========================================================================
         13. CÁC NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE 0896.134.234)
         - Tương thích tuyệt đối trên cả Máy tính và Điện thoại, không gây tràn viền
    ========================================================================== -->
    <!-- Cụm nút nổi bên phải màn hình máy tính & điện thoại -->
    <div class="fixed right-2.5 bottom-16 md:bottom-6 z-40 flex flex-col items-end gap-2.5">
        <!-- Nút Zalo -->
        <a href="https://zalo.me/0896134234" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-6 h-6 rounded-full bg-white text-[#0068ff] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="text-xs font-bold hidden sm:inline">Chat Zalo: 0896.134.234</span>
        </a>

        <!-- Nút Facebook -->
        <a href="https://www.facebook.com/rop.tran.7/" target="_blank" rel="noopener noreferrer" class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-6 h-6 rounded-full bg-white text-[#1877F2] flex items-center justify-center shrink-0 text-xs">
                <i class="fa-brands fa-facebook-f"></i>
            </span>
            <span class="text-xs font-bold hidden sm:inline">Facebook R.O.P</span>
        </a>

        <!-- Nút Hotline -->
        <a href="tel:0896134234" class="pulse-btn flex items-center gap-2 bg-rop-accent hover:bg-orange-700 text-white px-3.5 py-2 rounded-full shadow-lg transition">
            <span class="w-6 h-6 rounded-full bg-white text-rop-accent flex items-center justify-center shrink-0 text-xs">
                <i class="fa-solid fa-phone-volume"></i>
            </span>
            <span class="text-xs font-extrabold">0896.134.234</span>
        </a>
    </div>

    <!-- Thanh liên hệ nhanh cố định dưới đáy màn hình Điện thoại (Giống mẫu cokhivanpho.com) -->
    <div class="md:hidden fixed bottom-0 left-0 right-0 z-40 bg-white border-t border-slate-200 shadow-lg grid grid-cols-4 text-[10px] font-bold text-slate-700">
        <a href="tel:0896134234" class="py-2 flex flex-col items-center justify-center text-rop-accent">
            <i class="fa-solid fa-phone-volume text-sm mb-0.5"></i>
            <span>Gọi Điện</span>
        </a>
        <a href="https://zalo.me/0896134234" target="_blank" rel="noopener noreferrer" class="py-2 flex flex-col items-center justify-center text-[#0068ff]">
            <i class="fa-solid fa-comment-dots text-sm mb-0.5"></i>
            <span>Chat Zalo</span>
        </a>
        <a href="https://www.facebook.com/rop.tran.7/" target="_blank" rel="noopener noreferrer" class="py-2 flex flex-col items-center justify-center text-[#1877F2]">
            <i class="fa-brands fa-facebook-messenger text-sm mb-0.5"></i>
            <span>Facebook</span>
        </a>
        <a href="#lien-he-map" class="py-2 flex flex-col items-center justify-center text-rop-primary">
            <i class="fa-solid fa-map-location-dot text-sm mb-0.5"></i>
            <span>Chỉ Đường</span>
        </a>
    </div>

    <!-- =========================================================================
         JAVASCRIPT XỬ LÝ SLIDER BANNER, DANH MỤC SẢN PHẨM (11 ẢNH DRIVE THỰC TẾ) & FORM BÁO GIÁ
    ========================================================================== -->
    <script>
        /* Danh sách 11 ID ảnh thực tế từ Google Drive của khách hàng cung cấp */
        const DRIVE_IDS = [
            "1_T5cgbludB9TiBT5MLfW9I4mpeMcTrrD", // 0
            "1rWacsW1RzNHcmx6zFQZc5guUswekrmF_", // 1
            "1tEVQ6Omaki2HDRb1-RAkdzl236nD1K4P", // 2
            "1-8SRNLnjUqjfro_HwX6iB48eYOPV-FeP", // 3
            "1KUj3kjfa1Sn0GDF2Ri9THQAqBcmwO_jG", // 4
            "17LUGwzifUH4Y7XymDaIdRXkPJY9vu7Vl", // 5
            "11clRK_a8Pv8ThFLY4E6TlhEkqne0DuOr", // 6
            "1qav0ioO9ax7buKGnhiLrIh15oXQPn3Kq", // 7
            "1CAg0RNyav6zP7W_JZ4BxMya9JuTnFwRd", // 8
            "1YTjrek7h3j5fHGGrcQ7kizosZvCx300Q", // 9
            "1tg5dEZmEqoDksUgkU9e7qyAOn4_EbcbV"  // 10
        ];

        function driveImg(index) {
            const id = DRIVE_IDS[index % DRIVE_IDS.length];
            return {
                primary: `https://lh3.googleusercontent.com/d/${id}=w800`,
                fallback: `https://drive.google.com/thumbnail?id=${id}&sz=w800`
            };
        }

        /* Cấu trúc các nhóm danh mục & tên sản phẩm chuẩn theo web mẫu cokhivanpho.com kết hợp 11 ảnh thực tế */
        const PRODUCT_SECTIONS = [
            {
                category: "Thiết Bị Bếp Công Nghiệp",
                icon: "fa-fire-burner",
                products: [
                    { name: "Hệ Thống Bếp Á Công Nghiệp Inox 304 Nhà Hàng", imgIdx: 0, spec: "Inox 304 dày 1.0 - 1.2mm, gia công theo yêu cầu" },
                    { name: "Chậu Rửa Công Nghiệp Inox 2 Hố – 3 Hố Kèm Vòi", imgIdx: 1, spec: "Chống gỉ sét, hố rửa sâu rộng tiện lợi" },
                    { name: "Bàn Sơ Chế Thực Phẩm Inox 2 Tầng Có Gáy", imgIdx: 2, spec: "Chân vuông 40x40mm có tăng đưa chỉnh độ cao" },
                    { name: "Tủ Hấp Cơm Công Nghiệp Inox Điện & Gas", imgIdx: 3, spec: "Nấu từ 30kg – 100kg gạo/mẻ, giữ nhiệt tốt" }
                ]
            },
            {
                category: "Inox Nhà Hàng – Khách Sạn",
                icon: "fa-utensils",
                products: [
                    { name: "Quầy Giữ Nóng Thức Ăn Inox Nhà Hàng – Căn Tin", imgIdx: 4, spec: "Gia nhiệt bằng điện tự động, khay GN tiêu chuẩn" },
                    { name: "Xe Đẩy Thức Ăn Inox 2 Tầng – 3 Tầng Cao Cấp", imgIdx: 5, spec: "Bánh xe xoay 360 độ có khóa phanh êm ái" },
                    { name: "Bồn Rửa Thực Phẩm Công Nghiệp 3 Bồn Lớn", imgIdx: 1, spec: "Thiết kế thoát nước nhanh, đạt chuẩn an toàn vệ sinh" },
                    { name: "Lò Chiên & Quầy Pha Chế Trà Sữa – Cafe Inox 304", imgIdx: 0, spec: "Tích hợp thùng đá âm bàn, khay topping tiện dụng" }
                ]
            },
            {
                category: "Quả Cầu Hút Nhiệt Inox",
                icon: "fa-fan",
                products: [
                    { name: "Quả Cầu Hút Nhiệt Thông Gió Inox 304 Đường Kính Φ450 – Φ600", imgIdx: 9, spec: "Bạc đạn Nhật quay nhẹ, hút gió làm mát mái tôn" },
                    { name: "Quả Cầu Thông Gió Mái Nhà Xưởng Công Nghiệp Φ800", imgIdx: 7, spec: "Chân đế vừa mọi sóng tôn, chống dột mưa tuyệt đối" },
                    { name: "Quả Cầu Hút Nhiệt Inox Lắp Đặt Trọn Gói Tại Đà Nẵng", imgIdx: 9, spec: "Thích hợp nhà phố, giếng trời, kho xưởng sản xuất" },
                    { name: "Ống Thông Gió & Phụ Kiện Đế Quả Cầu Hút Nhiệt Inox", imgIdx: 7, spec: "Độ bền cao, chịu gió bão miền Trung" }
                ]
            },
            {
                category: "Chụp Hút Khói",
                icon: "fa-wind",
                products: [
                    { name: "Chụp Hút Khói Bếp Công Nghiệp Inox Kèm Phin Lọc Mỡ", imgIdx: 2, spec: "Hút khói khử mùi bếp nhà hàng, quán ăn hiệu quả" },
                    { name: "Chụp Hút Khói Bếp Gia Đình & Quán Ăn Thiết Kế Theo Yêu Cầu", imgIdx: 4, spec: "Tích hợp đèn chiếu sáng chịu nhiệt và cốc hứng dầu" },
                    { name: "Hệ Thống Đường Ống Dẫn Khói & Quạt Hút Ly Tâm Công Nghiệp", imgIdx: 3, spec: "Vận hành êm, lực hút mạnh, lắp đặt tận nơi" },
                    { name: "Chụp Hút Khói Đảo Bếp Đôi Cho Khu Bếp Trung Tâm", imgIdx: 0, spec: "Gia công thẩm mỹ bằng máy chấn CNC hiện đại" }
                ]
            },
            {
                category: "Cửa Cổng Xếp",
                icon: "fa-archway",
                products: [
                    { name: "Cửa Cổng Xếp Inox 304 Tự Động Cơ Quan – Nhà Máy", imgIdx: 6, spec: "Motor điện cảm ứng từ, điều khiển từ xa an toàn" },
                    { name: "Cửa Cổng Xếp Hợp Kim Nhôm & Inox Chống Gỉ Cao Cấp", imgIdx: 8, spec: "Nan chéo chắc chắn, bánh xe cao su chịu mài mòn" },
                    { name: "Cổng Xếp Kéo Tay Inox Cho Kho Bãi & Trường Học", imgIdx: 6, spec: "Đóng mở nhẹ nhàng, giá thành tiết kiệm tại xưởng" },
                    { name: "Barie Tự Động & Phụ Kiện Motor Cửa Cổng Xếp Đà Nẵng", imgIdx: 8, spec: "Bảo hành tận nơi, nhận sửa chữa nâng cấp cổng xếp" }
                ]
            },
            {
                category: "Cầu Thang – Lan Can Inox",
                icon: "fa-stairs",
                products: [
                    { name: "Cầu Thang Inox 304 Tay Vịn Tròn – Vuông Hiện Đại", imgIdx: 8, spec: "Sáng bóng vĩnh viễn, kết cấu chịu lực vững chắc" },
                    { name: "Lan Can Ban Công Inox 304 Chống Gỉ Muối Biển Đà Nẵng", imgIdx: 6, spec: "Độ bền vượt trội cho nhà phố, biệt thự, khách sạn" },
                    { name: "Cầu Thang Xoắn Ốc & Cầu Thang Thoát Hiểm Cơ Khí", imgIdx: 5, spec: "Thi công chuẩn kỹ thuật an toàn xây dựng" },
                    { name: "Lan Can Kính Trụ Inox 304 Cao Cấp", imgIdx: 8, spec: "Sang trọng, thông thoáng không gian kiến trúc" }
                ]
            },
            {
                category: "Nồi Nấu Phở Điện",
                icon: "fa-bowl-food",
                products: [
                    { name: "Nồi Nấu Phở Điện Inox 304 Dung Tích 20L – 30L – 50L", imgIdx: 10, spec: "Thành nồi 2 lớp bảo ôn giữ nhiệt, tiết kiệm điện" },
                    { name: "Nồi Hầm Xương & Nấu Nước Lèo Điện 70L – 100L – 160L", imgIdx: 10, spec: "Tủ điện rời chống giật, thanh nhiệt gia nhiệt nhanh" },
                    { name: "Bộ Nồi Nấu Phở Điện Đôi – Ba Liền Bệ Có Bánh Xe", imgIdx: 4, spec: "Thuận tiện di chuyển cho quán bún, phở, hủ tiếu" },
                    { name: "Nồi Điện Công Nghiệp Nấu Cháo, Luộc Bánh Chưng Inox", imgIdx: 10, spec: "Gia công theo dung tích đặt hàng riêng" }
                ]
            },
            {
                category: "Dụng Cụ Y Tế – Thủy Sản",
                icon: "fa-kit-medical",
                products: [
                    { name: "Giường Inox Bệnh Nhân & Tủ Đầu Giường Y Tế Inox 304", imgIdx: 5, spec: "Chuẩn kích thước bệnh viện, phòng khám đa khoa" },
                    { name: "Xe Đẩy Y Tế, Bục Bước Chân & Ghế Xoay Inox Y Tế", imgIdx: 7, spec: "Kháng khuẩn, dễ vệ sinh tiệt trùng" },
                    { name: "Xe Đẩy Thủy Sản, Thùng Đựng Thủy Sản & Xe Bồn Inox", imgIdx: 3, spec: "Chống ăn mòn nước mặn, phục vụ xưởng chế biến hải sản" },
                    { name: "Máng Rửa Tay Inox Công Nghiệp Nhiều Vòi Cho Nhà Xưởng", imgIdx: 1, spec: "Vòi nhấn gối hoặc cảm ứng tự động hiện đại" }
                ]
            },
            {
                category: "Bàn Ghế Kệ Inox",
                icon: "fa-table",
                products: [
                    { name: "Bàn Inox Chữ Nhật, Bàn Tròn & Ghế Đôn Inox Nhà Ăn", imgIdx: 2, spec: "Gấp gọn tiện lợi, chịu tải trọng lớn" },
                    { name: "Kệ Inox Để Chén Bát 4 Tầng – 5 Tầng Nan Thoáng Nước", imgIdx: 1, spec: "Treo tường hoặc đặt sàn cho bếp nhà hàng" },
                    { name: "Lò Nướng Than Inox Không Khói Ngoài Trời & Nhà Hàng BBQ", imgIdx: 4, spec: "Vỉ nướng inox 304 an toàn thực phẩm, dễ tháo rửa" },
                    { name: "Bàn Inox Có Ngăn Đựng Chén Bát Bẩn & Lỗ Xả Rác", imgIdx: 2, spec: "Tối ưu quy trình dọn rửa khu bếp công nghiệp" }
                ]
            },
            {
                category: "Cột Cờ – Máng Xối Inox",
                icon: "fa-flag",
                products: [
                    { name: "Cột Cờ Inox 304 Ngoài Trời Cao 6m – 12m Có Ròng Rọc", imgIdx: 9, spec: "Đốt cột hàn TIG thẩm mỹ, xoay 360 độ không rối cờ" },
                    { name: "Cột Chắn Inox Dây Căng & Dây Nhung Sự Kiện Khách Sạn", imgIdx: 8, spec: "Chân đế đúc nặng vững chắc, sang trọng" },
                    { name: "Máng Xối Inox 304 Thoát Nước Mái Tôn Nhà Xưởng & Dân Dụng", imgIdx: 7, spec: "Chấn gấp theo khổ yêu cầu, dài liền mạch chống thấm" },
                    { name: "Gia Công Phụ Kiện Cơ Khí Inox Theo Bản Vẽ Kỹ Thuật", imgIdx: 5, spec: "Cắt chấn CNC, hàn Argon tinh xảo tại xưởng Đà Nẵng" }
                ]
            }
        ];

        let currentCategoryFilter = 'ALL';
        let currentSearchKeyword = '';

        function renderProductSections() {
            const container = document.getElementById('danh-sach-san-pham');
            const keyword = currentSearchKeyword.trim().toLowerCase();

            let html = '';
            let matchedCount = 0;

            PRODUCT_SECTIONS.forEach(section => {
                if (currentCategoryFilter !== 'ALL' && section.category !== currentCategoryFilter) {
                    if (!(currentCategoryFilter === 'Lò Nướng Inox' && section.category === 'Bàn Ghế Kệ Inox')) {
                        return;
                    }
                }

                const filteredProducts = section.products.filter(p => {
                    if (!keyword) return true;
                    return p.name.toLowerCase().includes(keyword) ||
                           p.spec.toLowerCase().includes(keyword) ||
                           section.category.toLowerCase().includes(keyword);
                });

                if (filteredProducts.length === 0) return;
                matchedCount += filteredProducts.length;

                html += `
                <!-- UX BUILDER SECTION: ${section.category} -->
                <section class="ux-product-section">
                    <div class="flatsome-section-title shadow-sm">
                        <div class="flatsome-title-main">
                            <i class="fa-solid ${section.icon} text-amber-400"></i>
                            <span>${section.category}</span>
                        </div>
                        <a href="#form-bao-gia" onclick="prefillQuote('${section.category}')" class="text-[11px] sm:text-xs font-semibold text-rop-primary hover:text-rop-accent px-3 py-1 shrink-0">
                            Báo giá sỉ & lẻ <i class="fa-solid fa-angle-right ml-1"></i>
                        </a>
                    </div>

                    <div class="bg-white p-3 sm:p-4 rounded-b-xl shadow-sm border border-t-0 border-slate-200">
                        <!-- Chia 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính (lg:grid-cols-4), KHÔNG có nhãn dán -->
                        <div class="grid grid-cols-2 lg:grid-cols-4 gap-3 sm:gap-4">
                            ${filteredProducts.map(prod => {
                                const imgObj = driveImg(prod.imgIdx);
                                return `
                                <div class="product-card bg-white rounded-lg border border-slate-200 hover:border-rop-primary transition overflow-hidden flex flex-col justify-between">
                                    <div>
                                        <div class="product-img-wrap">
                                            <img src="${imgObj.primary}"
                                                 onerror="this.onerror=null;this.src='${imgObj.fallback}';"
                                                 alt="${prod.name}" loading="lazy">
                                        </div>
                                        <div class="p-2.5 sm:p-3">
                                            <h3 class="product-title-full text-xs sm:text-sm font-bold text-slate-800 hover:text-rop-primary">
                                                ${prod.name}
                                            </h3>
                                            <p class="text-[11px] text-slate-500 mt-1 leading-snug">
                                                ${prod.spec}
                                            </p>
                                        </div>
                                    </div>
                                    <div class="px-2.5 pb-2.5 sm:px-3 sm:pb-3 pt-1 flex flex-col sm:flex-row sm:items-center justify-between gap-1.5 border-t border-slate-100 mt-1">
                                        <span class="text-[11px] sm:text-xs font-extrabold text-rop-accent">
                                            Liên hệ: 0896.134.234
                                        </span>
                                        <a href="#form-bao-gia" onclick="prefillQuote('${prod.name}')" class="text-center text-[11px] font-semibold bg-rop-primary hover:bg-rop-dark text-white px-2.5 py-1 rounded transition">
                                            Báo giá
                                        </a>
                                    </div>
                                </div>
                                `;
                            }).join('')}
                        </div>
                    </div>
                </section>
                `;
            });

            if (matchedCount === 0) {
                html = `
                <div class="bg-white rounded-xl p-8 text-center border border-slate-200">
                    <div class="text-sm font-bold text-slate-700">Không tìm thấy sản phẩm phù hợp với từ khóa "${currentSearchKeyword}"</div>
                    <button type="button" onclick="selectCategory('ALL')" class="mt-3 bg-rop-primary text-white text-xs font-semibold px-4 py-2 rounded-md">
                        Xem lại tất cả sản phẩm
                    </button>
                </div>
                `;
            }

            container.innerHTML = html;
        }

        function selectCategory(catName) {
            currentCategoryFilter = catName;
            currentSearchKeyword = '';
            const dInput = document.getElementById('searchInputDesktop');
            const mInput = document.getElementById('searchInputMobile');
            if (dInput) dInput.value = '';
            if (mInput) mInput.value = '';

            const indicator = document.getElementById('activeCatIndicator');
            if (indicator) {
                indicator.textContent = catName === 'ALL' ? 'Đang xem: Tất cả danh mục' : `Đang lọc: ${catName} (Nhấn để xem tất cả)`;
            }

            renderProductSections();

            if (catName !== 'ALL') {
                const target = document.getElementById('danh-sach-san-pham');
                if (target) target.scrollIntoView({ behavior: 'smooth', block: 'start' });
            }
        }

        function filterProductsBySearch(keyword) {
            currentSearchKeyword = keyword || '';
            currentCategoryFilter = 'ALL';
            renderProductSections();
        }

        function prefillQuote(itemName) {
            const noteEl = document.getElementById('qNote');
            if (noteEl) {
                noteEl.value = `Tôi cần tư vấn và báo giá sản phẩm/hạng mục: ${itemName}`;
            }
        }

        function submitQuoteForm(event) {
            event.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const category = document.getElementById('qCategory').value;
            const box = document.getElementById('quoteSuccessBox');

            box.classList.remove('hidden');
            box.innerHTML = `<i class="fa-solid fa-circle-check mr-1.5"></i>Cảm ơn <strong>${name}</strong>! Yêu cầu báo giá hạng mục <strong>${category}</strong> (SĐT: <strong>${phone}</strong>) đã được ghi nhận. Bộ phận kỹ thuật <strong>CÔNG TY TNHH TM KỸ THUẬT R.O.P (0896.134.234)</strong> sẽ liên hệ ngay với quý khách.`;
            document.getElementById('quoteRequestForm').reset();
        }

        function toggleMobileDrawer() {
            const drawer = document.getElementById('mobileDrawer');
            drawer.classList.toggle('hidden');
        }

        /* =========================================================================
           SLIDER 2 BANNER TỰ ĐỘNG TRƯỢT (ĐỒNG BỘ CẢ MÁY TÍNH VÀ ĐIỆN THOẠI)
        ========================================================================== */
        let activeBannerIndex = 0;
        const totalBannerSlides = 2;

        function setBannerSlide(index) {
            activeBannerIndex = (index + totalBannerSlides) % totalBannerSlides;

            const desktopSlides = document.querySelectorAll('.desktop-slide');
            const mobileSlides = document.querySelectorAll('.mobile-slide');

            desktopSlides.forEach((slide, idx) => {
                if (idx === activeBannerIndex) {
                    slide.classList.remove('opacity-0', 'pointer-events-none');
                    slide.classList.add('opacity-100');
                } else {
                    slide.classList.remove('opacity-100');
                    slide.classList.add('opacity-0', 'pointer-events-none');
                }
            });

            mobileSlides.forEach((slide, idx) => {
                if (idx === activeBannerIndex) {
                    slide.classList.remove('opacity-0', 'pointer-events-none');
                    slide.classList.add('opacity-100');
                } else {
                    slide.classList.remove('opacity-100');
                    slide.classList.add('opacity-0', 'pointer-events-none');
                }
            });

            const dot0 = document.getElementById('bannerDot0');
            const dot1 = document.getElementById('bannerDot1');
            if (dot0 && dot1) {
                if (activeBannerIndex === 0) {
                    dot0.className = 'w-5 h-1.5 rounded-full bg-amber-400 transition-all';
                    dot1.className = 'w-2 h-1.5 rounded-full bg-white/50 transition-all';
                } else {
                    dot0.className = 'w-2 h-1.5 rounded-full bg-white/50 transition-all';
                    dot1.className = 'w-5 h-1.5 rounded-full bg-amber-400 transition-all';
                }
            }
        }

        function changeBannerSlide(step) {
            setBannerSlide(activeBannerIndex + step);
        }

        window.onload = function () {
            renderProductSections();
            setInterval(() => {
                changeBannerSlide(1);
            }, 5000);
        };
    </script>
</body>
</html>
