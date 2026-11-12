<!-- Website Nội Thất Nhựa Quân Phát - noithatnhuaquanphat.com -->
<!-- Cấu trúc chuẩn Flatsome UX Builder (Section > Row > Col > Box) dễ dàng chỉnh sửa -->
<html lang="vi">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0, maximum-scale=1.0, user-scalable=no">
    <title>Nội Thất Nhựa Quân Phát - Tư Vấn, Thiết Kế, Sản Xuất & Thi Công Nội Thất Nhựa Đà Nẵng</title>
    <meta name="description" content="Nội Thất Nhựa Quân Phát (noithatnhuaquanphat.com) - Chuyên tư vấn, thiết kế, sản xuất và thi công nội thất nhựa Đài Loan, Chin Huei, Ecoplast, Ecostar cao cấp tại 40 Lê Hiến Mai, Phường Hòa Khánh, Tp.Đà Nẵng. Hotline: 0935 437 033 – 0376 758 097.">

    <!-- Thumbnail là ảnh Logo trang web khi gửi link chia sẻ qua Zalo, Facebook, Messenger -->
    <meta property="og:type" content="website">
    <meta property="og:url" content="https://noithatnhuaquanphat.com/">
    <meta property="og:site_name" content="noithatnhuaquanphat.com">
    <meta property="og:title" content="Nội Thất Nhựa Quân Phát - Xưởng Sản Xuất & Thi Công Nội Thất Nhựa Cao Cấp Đà Nẵng">
    <meta property="og:description" content="Chuyên tủ quần áo nhựa Đài Loan, Chin Huei, Ecoplast, tủ bếp nhựa, giường ngủ, bàn học, kệ tivi, ốp tường lam sóng giá gốc tại xưởng. Đ/c: 40 Lê Hiến Mai, P. Hòa Khánh, Đà Nẵng.">
    <meta property="og:image" content="https://lh3.googleusercontent.com/d/16zCoeKfJPHYNPIpp_HZUue-C-j9kbIg3">
    <meta property="og:image:secure_url" content="https://lh3.googleusercontent.com/d/16zCoeKfJPHYNPIpp_HZUue-C-j9kbIg3">
    <meta property="og:image:alt" content="Logo Nội Thất Nhựa Quân Phát">
    <meta name="twitter:card" content="summary_large_image">
    <meta name="twitter:title" content="Nội Thất Nhựa Quân Phát - noithatnhuaquanphat.com">
    <meta name="twitter:image" content="https://lh3.googleusercontent.com/d/16zCoeKfJPHYNPIpp_HZUue-C-j9kbIg3">
    <link rel="icon" type="image/png" href="https://lh3.googleusercontent.com/d/16zCoeKfJPHYNPIpp_HZUue-C-j9kbIg3">
    <link rel="apple-touch-icon" href="https://lh3.googleusercontent.com/d/16zCoeKfJPHYNPIpp_HZUue-C-j9kbIg3">

    <!-- Google Fonts: Inter & Montserrat -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700;800&display=swap" rel="stylesheet">

    <!-- FontAwesome Icons -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">

    <!-- Tailwind CSS -->
    <script src="https://cdn.tailwindcss.com"></script>
    <script>
        tailwind.config = {
            theme: {
                extend: {
                    fontFamily: {
                        sans: ['Inter', 'sans-serif'],
                    },
                    colors: {
                        qp: {
                            primary: '#0b4f82',    /* Xanh thương hiệu theo tông logo & web mẫu */
                            dark: '#07365a',       /* Xanh đậm thanh menu Flatsome */
                            light: '#eef6fc',      /* Nền xanh nhạt */
                            accent: '#f59e0b',     /* Vàng cam điểm nhấn */
                            sale: '#d90429',       /* Đỏ giảm giá chuẩn Flatsome */
                        }
                    }
                }
            }
        }
    </script>

    <style>
        /* Reset & Chống tràn viền, chống lệch phải tuyệt đối trên mọi thiết bị & trình duyệt nhúng */
        *, *::before, *::after {
            box-sizing: border-box;
        }
        html, body {
            margin: 0 !important;
            padding: 0 !important;
            width: 100% !important;
            max-width: 100% !important;
            overflow-x: hidden !important;
            position: relative;
            font-family: 'Inter', sans-serif;
            background-color: #f5f7fa;
            color: #1e293b;
            scroll-behavior: smooth;
            -webkit-text-size-adjust: 100%;
        }
        ul, ol {
            margin: 0;
            padding: 0;
            list-style: none;
        }
        header, main, footer, section, nav, div {
            max-width: 100%;
        }

        /* Khung giao diện chuẩn: 95% chiều ngang màn hình máy tính, 100% căn giữa chuẩn trên điện thoại */
        .flatsome-container {
            width: 100% !important;
            max-width: 100% !important;
            padding-left: 8px !important;
            padding-right: 8px !important;
            margin-left: auto !important;
            margin-right: auto !important;
            overflow-x: hidden;
        }
        @media (min-width: 1024px) {
            .flatsome-container {
                width: 95% !important;
                max-width: 95% !important;
                padding-left: 0 !important;
                padding-right: 0 !important;
                overflow-x: visible;
            }
        }

        /* Thanh danh mục trên máy tính: viết liền trên 1 hàng chữ nhỏ gọn, tuyệt đối không gãy chữ tên danh mục */
        .desktop-nav-list {
            display: flex;
            flex-wrap: wrap;
            align-items: center;
            justify-content: center;
            gap: 2px 6px;
            width: 100%;
        }
        .desktop-nav-item {
            position: relative;
            white-space: nowrap; /* Không bao giờ xuống dòng bên trong tên 1 danh mục */
        }
        .desktop-nav-link {
            display: inline-flex;
            align-items: center;
            gap: 4px;
            padding: 8px 9px;
            font-size: 11.5px;
            font-weight: 700;
            text-transform: uppercase;
            color: #ffffff;
            white-space: nowrap;
            letter-spacing: -0.01em;
            border-radius: 4px;
            transition: background-color 0.2s ease, color 0.2s ease;
        }
        @media (min-width: 1366px) {
            .desktop-nav-link {
                font-size: 12.2px;
                padding: 9px 11px;
            }
        }
        .desktop-nav-link:hover, .desktop-nav-item:hover .desktop-nav-link {
            background-color: rgba(255, 255, 255, 0.14);
            color: #fde047;
        }

        /* Dropdown menu con kiểu Flatsome */
        .flatsome-dropdown {
            display: none;
            position: absolute;
            top: 100%;
            left: 0;
            min-width: 250px;
            background: #ffffff;
            color: #1e293b;
            box-shadow: 0 12px 28px rgba(0, 0, 0, 0.16);
            border-top: 3px solid #f59e0b;
            border-radius: 0 0 8px 8px;
            z-index: 100;
            padding: 8px 0;
        }
        .desktop-nav-item.dropdown-right .flatsome-dropdown {
            left: auto;
            right: 0;
        }
        .desktop-nav-item:hover .flatsome-dropdown {
            display: block;
        }

        /* Thẻ sản phẩm Flatsome: Tên sản phẩm hiển thị đầy đủ, không bị cắt chữ hoặc tràn ra ngoài */
        .product-small-box {
            display: flex;
            flex-direction: column;
            justify-content: space-between;
            height: 100%;
            background: #ffffff;
            border: 1px solid #e2e8f0;
            border-radius: 8px;
            overflow: hidden;
            transition: transform 0.2s ease, box-shadow 0.2s ease;
        }
        .product-small-box:hover {
            transform: translateY(-3px);
            box-shadow: 0 10px 20px rgba(11, 79, 130, 0.12);
            border-color: #93c5fd;
        }
        .product-title-full {
            font-size: 12.5px;
            line-height: 1.4;
            font-weight: 700;
            color: #1e293b;
            white-space: normal;
            word-wrap: break-word;
            overflow-wrap: break-word;
            margin-bottom: 6px;
        }
        @media (min-width: 768px) {
            .product-title-full {
                font-size: 13.5px;
                line-height: 1.42;
            }
        }

        /* Nhãn % Giảm giá góc trên bên trái chuẩn Flatsome */
        .flatsome-sale-badge {
            position: absolute;
            top: 8px;
            left: 8px;
            z-index: 10;
            background-color: #d90429;
            color: #ffffff;
            font-weight: 800;
            font-size: 11px;
            line-height: 1;
            padding: 6px 8px;
            border-radius: 9999px;
            box-shadow: 0 2px 6px rgba(217, 4, 41, 0.35);
        }
        @media (min-width: 768px) {
            .flatsome-sale-badge {
                font-size: 12px;
                padding: 7px 9px;
            }
        }

        /* Tiêu đề Section chuẩn Flatsome (Section Title) */
        .section-title-container {
            margin-bottom: 14px;
        }
        .section-title-main {
            display: flex;
            align-items: center;
            justify-content: space-between;
            background: linear-gradient(90deg, #0b4f82 0%, #07365a 100%);
            color: #ffffff;
            padding: 9px 14px;
            border-radius: 6px;
            border-left: 5px solid #f59e0b;
        }

        /* Hiệu ứng nút liên hệ nổi */
        @keyframes pulseRing {
            0% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 4, 41, 0.6); }
            70% { transform: scale(1); box-shadow: 0 0 0 10px rgba(217, 4, 41, 0); }
            100% { transform: scale(0.95); box-shadow: 0 0 0 0 rgba(217, 4, 41, 0); }
        }
        .pulse-btn {
            animation: pulseRing 2s infinite;
        }
    </style>
</head>
<body class="min-h-screen w-full max-w-full overflow-x-hidden m-0 p-0">

    <!-- ===================================================================== -->
    <!-- 1. TOP BAR CHUẨN FLATSOME (Không có thanh công cụ UX Builder)           -->
    <!-- ===================================================================== -->
    <div id="top-bar" class="bg-qp-dark text-white text-[11px] md:text-xs py-1.5 border-b border-white/10 w-full overflow-hidden">
        <div class="flatsome-container flex items-center justify-between gap-2">
            <div class="flex items-center gap-1.5 font-medium min-w-0 flex-1 overflow-hidden">
                <i class="fa-solid fa-award text-amber-400 shrink-0"></i>
                <span class="block truncate">Tư vấn – Thiết kế – Sản xuất – Thi công nội thất nhựa cao cấp tại Đà Nẵng</span>
            </div>
            <div class="hidden md:flex items-center gap-4 text-slate-200 shrink-0">
                <span><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>40 Lê Hiến Mai, P. Hòa Khánh, Tp.Đà Nẵng</span>
                <span>|</span>
                <span><i class="fa-solid fa-shield-halved text-amber-400 mr-1"></i>Chất lượng tốt nhất - Bảo hành tận nhà</span>
            </div>
        </div>
    </div>

    <!-- ===================================================================== -->
    <!-- 2. HEADER (Logo chỉnh nhỏ gọn, KHÔNG để nút gọi ngay tránh tràn viền) -->
    <!-- ===================================================================== -->
    <header id="header" class="bg-white sticky top-0 z-40 shadow-sm border-b border-slate-200 w-full overflow-hidden lg:overflow-visible">
        <!-- Header Main -->
        <div class="header-main py-2 md:py-3 w-full">
            <div class="flatsome-container flex items-center justify-between gap-1.5 sm:gap-2 md:gap-6">
                
                <!-- Nút mở Danh mục trên Điện thoại -->
                <button type="button" onclick="toggleMobileMenu()" aria-label="Mở danh mục" class="lg:hidden inline-flex items-center justify-center w-8 h-8 sm:w-9 sm:h-9 rounded-md bg-qp-primary text-white shrink-0">
                    <i class="fa-solid fa-bars text-sm sm:text-base"></i>
                </button>

                <!-- Logo chỉnh gọn nhỏ lại + Tên trang web (Co giãn linh hoạt trên mobile, không đẩy tràn phải) -->
                <a href="#top-bar" class="flex items-center gap-1.5 sm:gap-2.5 flex-1 lg:flex-initial min-w-0 overflow-hidden">
                    <div class="w-9 h-9 sm:w-10 sm:h-10 md:w-12 md:h-12 rounded-lg border border-slate-200 bg-white p-0.5 flex items-center justify-center overflow-hidden shrink-0 shadow-xs">
                        <img src="https://lh3.googleusercontent.com/d/16zCoeKfJPHYNPIpp_HZUue-C-j9kbIg3"
                             data-drive-id="16zCoeKfJPHYNPIpp_HZUue-C-j9kbIg3"
                             onerror="handleDriveImageError(this)"
                             alt="Logo Nội Thất Nhựa Quân Phát"
                             class="w-full h-full object-contain">
                    </div>
                    <div class="min-w-0 flex-1 overflow-hidden">
                        <div class="text-[11.5px] sm:text-sm md:text-base font-extrabold text-qp-primary tracking-tight leading-tight truncate">
                            NỘI THẤT NHỰA QUÂN PHÁT
                        </div>
                        <div class="text-[9.5px] sm:text-[10px] md:text-[11px] font-semibold text-amber-600 truncate">
                            noithatnhuaquanphat.com
                        </div>
                    </div>
                </a>

                <!-- Ô Tìm kiếm sản phẩm (Máy tính) -->
                <div class="hidden md:flex flex-1 max-w-xl mx-2 min-w-0">
                    <div class="relative flex w-full min-w-0">
                        <input id="desktopSearchInput"
                               type="text"
                               oninput="handleSearchProducts(this.value)"
                               placeholder="Tìm tủ nhựa Đài Loan, Chin Huei, Ecoplast, tủ bếp, giường ngủ..."
                               class="w-full min-w-0 pl-3.5 pr-10 py-2 text-xs lg:text-sm border-2 border-qp-primary/80 rounded-l-md focus:outline-none focus:border-qp-primary">
                        <button type="button"
                                onclick="handleSearchProducts(document.getElementById('desktopSearchInput').value)"
                                class="bg-qp-primary hover:bg-qp-dark text-white px-4 rounded-r-md text-sm font-semibold transition shrink-0">
                            <i class="fa-solid fa-magnifying-glass"></i>
                        </button>
                    </div>
                </div>

                <!-- Cam kết & Giỏ báo giá bên phải (Không để nút gọi ngay để tránh tràn viền) -->
                <div class="flex items-center gap-1.5 md:gap-4 shrink-0">
                    <div class="hidden xl:flex items-center gap-2 text-xs text-slate-600 bg-slate-50 px-3 py-1.5 rounded-md border border-slate-200">
                        <i class="fa-solid fa-truck-fast text-qp-primary text-sm"></i>
                        <div class="leading-tight">
                            <div class="font-bold text-slate-800">Xưởng Tại Hòa Khánh</div>
                            <div class="text-[11px] text-slate-500">Đo đạc & Lắp đặt tận nơi</div>
                        </div>
                    </div>
                    <a href="#form-bao-gia" class="inline-flex items-center gap-1 px-2 py-1.5 sm:px-2.5 md:px-3.5 md:py-2 rounded-md bg-amber-500 hover:bg-amber-600 text-white text-[10.5px] sm:text-[11px] md:text-xs font-bold transition shrink-0 shadow-xs whitespace-nowrap">
                        <i class="fa-solid fa-file-signature"></i>
                        <span>Nhận Báo Giá</span>
                    </a>
                </div>
            </div>

            <!-- Ô Tìm kiếm trên Điện thoại -->
            <div class="flatsome-container mt-2 md:hidden">
                <div class="relative flex w-full min-w-0 overflow-hidden">
                    <input id="mobileSearchInput"
                           type="text"
                           oninput="handleSearchProducts(this.value)"
                           placeholder="Tìm kiếm mẫu tủ áo, tủ bếp, bàn học, giường nhựa..."
                           class="w-full min-w-0 flex-1 pl-2.5 pr-2 py-1.5 text-xs border border-qp-primary/70 rounded-l-md focus:outline-none">
                    <button type="button"
                            onclick="handleSearchProducts(document.getElementById('mobileSearchInput').value)"
                            class="bg-qp-primary text-white px-3 rounded-r-md text-xs shrink-0">
                        <i class="fa-solid fa-magnifying-glass"></i>
                    </button>
                </div>
            </div>
        </div>

        <!-- ===================================================================== -->
        <!-- 3. THANH DANH MỤC SẢN PHẨM TRÊN MÁY TÍNH (Viết liền trên 1 hàng chữ nhỏ) -->
        <!-- ===================================================================== -->
        <nav id="header-bottom-nav" class="hidden lg:block bg-qp-primary border-t border-white/15">
            <div class="flatsome-container py-0.5">
                <ul class="desktop-nav-list">
                    <li class="desktop-nav-item">
                        <a href="#san-pham-thuc-te" onclick="filterByCategory('all')" class="desktop-nav-link bg-amber-500 text-slate-950 hover:bg-amber-400 hover:text-slate-950">
                            <i class="fa-solid fa-house"></i> TRANG CHỦ
                        </a>
                    </li>

                    <!-- Danh mục 1: Nội thất nhựa Đài Loan -->
                    <li class="desktop-nav-item">
                        <a href="#danh-muc-san-pham" onclick="filterByCategory('dai-loan')" class="desktop-nav-link">
                            NỘI THẤT NHỰA ĐÀI LOAN <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="flatsome-dropdown">
                            <div class="px-3 py-1.5 text-[11px] font-extrabold text-qp-primary uppercase border-b border-slate-100">Tủ Áo Người Lớn & Cánh Lùa</div>
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('dai-loan')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Tủ áo 2 cánh - 3 cánh - 4 cánh</a>
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('dai-loan')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Tủ áo 5-6 cánh & Tủ kịch trần</a>
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('canh-lua')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Tủ áo cánh lùa có kệ trang trí</a>
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('tre-em-ban')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Tủ áo trẻ em & Tủ ngăn kéo</a>
                            <div class="px-3 py-1.5 text-[11px] font-extrabold text-qp-primary uppercase border-y border-slate-100 mt-1">Tủ Kệ, Bàn Học & Giường Ngủ</div>
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('tre-em-ban')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Tủ giày dép thông minh & Kệ tivi</a>
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('tre-em-ban')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Bàn học sinh, Bàn trang điểm, Bàn làm việc</a>
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('tu-bep-giuong')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Tủ bếp, Giường ngủ, Combo phòng ngủ</a>
                        </div>
                    </li>

                    <!-- Danh mục 2: Nội thất nhựa CHIN HUEI -->
                    <li class="desktop-nav-item">
                        <a href="#danh-muc-san-pham" onclick="filterByCategory('chin-huei')" class="desktop-nav-link">
                            NỘI THẤT NHỰA CHIN HUEI <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="flatsome-dropdown">
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('chin-huei')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Tủ áo cánh mở Chin Huei (2-3-4-5-6 cánh)</a>
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('canh-lua')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Tủ áo cánh lùa Chin Huei</a>
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('chin-huei')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Tủ áo lớn & Tủ áo Full trần Chin Huei</a>
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('tre-em-ban')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Tủ áo trẻ em, Bàn học, Bàn trang điểm CH</a>
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('tu-bep-giuong')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Tủ bếp, Giường ngủ, Tủ Lavabo Chin Huei</a>
                        </div>
                    </li>

                    <!-- Danh mục 3: Nội thất nhựa cao cấp ECOPLAST -->
                    <li class="desktop-nav-item">
                        <a href="#danh-muc-san-pham" onclick="filterByCategory('ecoplast')" class="desktop-nav-link">
                            NỘI THẤT NHỰA ECOPLAST <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="flatsome-dropdown">
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('ecoplast')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Tủ áo người lớn & Cánh lùa Ecoplast</a>
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('tu-bep-giuong')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Tủ bếp nhựa cao cấp Ecoplast</a>
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('tu-bep-giuong')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Giường ngủ & Combo phòng ngủ Ecoplast</a>
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('tre-em-ban')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Kệ Tivi, Tủ rượu, Tủ cầu thang Ecoplast</a>
                        </div>
                    </li>

                    <!-- Danh mục 4: Nội thất nhựa CHIN HUEI 2.0 PLUS - PRO18 -->
                    <li class="desktop-nav-item">
                        <a href="#danh-muc-san-pham" onclick="filterByCategory('chin-huei')" class="desktop-nav-link">
                            CHIN HUEI 2.0 PLUS - PRO18 <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="flatsome-dropdown">
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('chin-huei')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Tủ áo cánh mở & cánh lùa Chin Huei 2.0 Plus</a>
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('tu-bep-giuong')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Tủ bếp & Giường ngủ Chin Huei 2.0 Plus</a>
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('tu-bep-giuong')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Combo nội thất phòng ngủ Chin Huei 2.0 Plus</a>
                        </div>
                    </li>

                    <!-- Danh mục 5: Nội thất nhựa ECOSTAR -->
                    <li class="desktop-nav-item">
                        <a href="#danh-muc-san-pham" onclick="filterByCategory('ecoplast')" class="desktop-nav-link">
                            NỘI THẤT NHỰA ECOSTAR <i class="fa-solid fa-angle-down text-[10px] opacity-80"></i>
                        </a>
                        <div class="flatsome-dropdown">
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('ecoplast')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Tủ áo nhựa Ecostar</a>
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('tu-bep-giuong')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Tủ bếp nhựa Ecostar</a>
                            <a href="#danh-muc-san-pham" onclick="filterByCategory('tu-bep-giuong')" class="block px-3.5 py-1.5 text-xs hover:bg-qp-light hover:text-qp-primary">Giường ngủ nhựa Ecostar</a>
                        </div>
                    </li>

                    <!-- Danh mục 6: Thi công ốp tường, lam sóng, giả đá, trần nhựa -->
                    <li class="desktop-nav-item dropdown-right">
                        <a href="#danh-muc-san-pham" onclick="filterByCategory('tu-bep-giuong')" class="desktop-nav-link">
                            ỐP TƯỜNG, LAM SÓNG, TRẦN NHỰA
                        </a>
                    </li>

                    <!-- Bài viết & Liên hệ -->
                    <li class="desktop-nav-item dropdown-right">
                        <a href="#bai-viet-trang-chu" class="desktop-nav-link">
                            BÀI VIẾT
                        </a>
                    </li>
                    <li class="desktop-nav-item dropdown-right">
                        <a href="#bando-fanpage" class="desktop-nav-link">
                            BẢN ĐỒ & FANPAGE
                        </a>
                    </li>
                </ul>
            </div>
        </nav>
    </header>

    <!-- ===================================================================== -->
    <!-- MENU DANH MỤC TRÊN ĐIỆN THOẠI (Drawer trượt mượt mà, rõ ràng)          -->
    <!-- ===================================================================== -->
    <div id="mobileMenuOverlay" class="fixed inset-0 bg-slate-900/60 z-50 hidden" onclick="toggleMobileMenu()"></div>
    <aside id="mobileMenuDrawer" class="fixed top-0 left-0 bottom-0 w-[84%] max-w-[310px] bg-white z-50 -translate-x-full transition-transform duration-300 flex flex-col shadow-2xl">
        <div class="p-3.5 bg-qp-primary text-white flex items-center justify-between">
            <div class="flex items-center gap-2 min-w-0">
                <img src="https://lh3.googleusercontent.com/d/16zCoeKfJPHYNPIpp_HZUue-C-j9kbIg3"
                     data-drive-id="16zCoeKfJPHYNPIpp_HZUue-C-j9kbIg3"
                     onerror="handleDriveImageError(this)"
                     alt="Logo"
                     class="w-8 h-8 rounded bg-white p-0.5 object-contain shrink-0">
                <div class="truncate">
                    <div class="text-xs font-extrabold uppercase truncate">Nội Thất Nhựa Quân Phát</div>
                    <div class="text-[10px] text-amber-300 truncate">noithatnhuaquanphat.com</div>
                </div>
            </div>
            <button type="button" onclick="toggleMobileMenu()" class="w-8 h-8 rounded-full bg-white/15 flex items-center justify-center text-white">
                <i class="fa-solid fa-xmark"></i>
            </button>
        </div>

        <div class="p-3 overflow-y-auto flex-1 divide-y divide-slate-100 text-xs font-semibold text-slate-700">
            <div class="pb-2 text-[11px] font-extrabold text-qp-primary uppercase tracking-wider">
                Danh Mục Sản Phẩm Chuẩn Xưởng
            </div>
            <a href="#danh-muc-san-pham" onclick="filterByCategory('all'); toggleMobileMenu();" class="flex items-center justify-between py-2.5 hover:text-qp-primary">
                <span><i class="fa-solid fa-border-all text-qp-primary mr-2"></i>Tất Cả Sản Phẩm Thực Tế (13+)</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#danh-muc-san-pham" onclick="filterByCategory('dai-loan'); toggleMobileMenu();" class="flex items-center justify-between py-2.5 hover:text-qp-primary">
                <span><i class="fa-solid fa-wardrobe text-qp-primary mr-2"></i>Nội Thất Nhựa Đài Loan</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#danh-muc-san-pham" onclick="filterByCategory('chin-huei'); toggleMobileMenu();" class="flex items-center justify-between py-2.5 hover:text-qp-primary">
                <span><i class="fa-solid fa-medal text-qp-primary mr-2"></i>Nội Thất Nhựa Chin Huei</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#danh-muc-san-pham" onclick="filterByCategory('ecoplast'); toggleMobileMenu();" class="flex items-center justify-between py-2.5 hover:text-qp-primary">
                <span><i class="fa-solid fa-gem text-qp-primary mr-2"></i>Nội Thất Nhựa Cao Cấp Ecoplast</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#danh-muc-san-pham" onclick="filterByCategory('canh-lua'); toggleMobileMenu();" class="flex items-center justify-between py-2.5 hover:text-qp-primary">
                <span><i class="fa-solid fa-door-closed text-qp-primary mr-2"></i>Tủ Áo Cánh Lùa & Full Trần</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#danh-muc-san-pham" onclick="filterByCategory('tre-em-ban'); toggleMobileMenu();" class="flex items-center justify-between py-2.5 hover:text-qp-primary">
                <span><i class="fa-solid fa-child-reaching text-qp-primary mr-2"></i>Tủ Trẻ Em, Bàn Học, Bàn Trang Điểm</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#danh-muc-san-pham" onclick="filterByCategory('tu-bep-giuong'); toggleMobileMenu();" class="flex items-center justify-between py-2.5 hover:text-qp-primary">
                <span><i class="fa-solid fa-kitchen-set text-qp-primary mr-2"></i>Tủ Bếp, Giường Ngủ, Ốp Lam Sóng</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#form-bao-gia" onclick="toggleMobileMenu();" class="flex items-center justify-between py-2.5 hover:text-qp-primary">
                <span><i class="fa-solid fa-calculator text-amber-500 mr-2"></i>Yêu Cầu Đo Đạc & Báo Giá</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#bai-viet-trang-chu" onclick="toggleMobileMenu();" class="flex items-center justify-between py-2.5 hover:text-qp-primary">
                <span><i class="fa-solid fa-newspaper text-qp-primary mr-2"></i>Bài Viết & Kinh Nghiệm Nội Thất</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
            <a href="#bando-fanpage" onclick="toggleMobileMenu();" class="flex items-center justify-between py-2.5 hover:text-qp-primary">
                <span><i class="fa-solid fa-map-location-dot text-qp-primary mr-2"></i>Bản Đồ Xưởng & Fanpage</span>
                <i class="fa-solid fa-chevron-right text-[10px] text-slate-400"></i>
            </a>
        </div>

        <div class="p-3 bg-slate-50 border-t border-slate-200 text-[11px] text-slate-600 space-y-1">
            <div class="font-bold text-slate-800"><i class="fa-solid fa-location-dot text-qp-sale mr-1"></i>40 Lê Hiến Mai, P. Hòa Khánh, Đà Nẵng</div>
            <div class="font-bold text-qp-primary"><i class="fa-solid fa-phone mr-1"></i>0935 437 033 – 0376 758 097</div>
        </div>
    </aside>

    <!-- ===================================================================== -->
    <!-- MAIN CONTENT (UX BUILDER FLATSOME STRUCTURE)                          -->
    <!-- ===================================================================== -->
    <main id="main" class="flex-1 py-3 md:py-4 space-y-5 md:space-y-7">

        <!-- ================================================================= -->
        <!-- SECTION 1: 2 ẢNH BANNER TỰ TRƯỢT CHUYÊN NGHIỆP KÍCH THƯỚC BẰNG NHAU-->
        <!-- Thiết kế riêng bản Máy tính (Desktop) & bản Điện thoại (Mobile)    -->
        <!-- Chữ nhỏ gọn nằm trọn bên trong ảnh banner, tuyệt đối không tràn viền-->
        <!-- ================================================================= -->
        <section id="banner-slider-section" class="flatsome-container">
            <div class="relative w-full overflow-hidden rounded-xl shadow-md border border-slate-200 bg-qp-dark">
                
                <!-- ================= SLIDE 1 ================= -->
                <div class="banner-slide transition-opacity duration-500 opacity-100 block" data-slide="0">
                    
                    <!-- BẢN BANNER MÁY TÍNH 1 (Cố định chiều cao h-[340px] lg:h-[370px] bằng nhau) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center w-full h-[340px] lg:h-[370px] bg-gradient-to-r from-[#062c49] via-[#0b4f82] to-[#1268a8] px-8 lg:px-12 py-6 relative overflow-hidden">
                        <!-- Họa tiết nền nhẹ -->
                        <div class="absolute -right-12 -bottom-12 w-72 h-72 rounded-full bg-white/5 pointer-events-none"></div>
                        
                        <!-- Cột chữ bên trong banner máy tính: Chữ chỉnh nhỏ gọn nằm hết trong ảnh -->
                        <div class="col-span-7 pr-4 text-white z-10 space-y-2.5">
                            <div class="inline-block bg-amber-400 text-slate-950 text-[11px] font-extrabold uppercase px-3 py-1 rounded-md">
                                XƯỞNG SẢN XUẤT TRỰC TIẾP TẠI ĐÀ NẴNG - KHÔNG QUA TRUNG GIAN
                            </div>
                            <h1 class="text-xl lg:text-2xl xl:text-[26px] font-extrabold leading-snug text-white">
                                NỘI THẤT NHỰA QUÂN PHÁT<br>
                                <span class="text-amber-300">CHUYÊN TỦ ÁO, TỦ BẾP, GIƯỜNG NGỦ NHỰA CAO CẤP</span>
                            </h1>
                            <p class="text-xs lg:text-[13px] text-slate-100 leading-relaxed max-w-xl">
                                Thi công nhựa Đài Loan Chin Huei, Ecoplast, Chin Huei 2.0 Plus chính hãng. Chống nước 100%, không mối mọt, không cong vênh – Bảo hành tận nhà chu đáo.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-x-5 gap-y-1.5 text-xs font-semibold text-amber-200">
                                <span><i class="fa-solid fa-location-dot mr-1.5"></i>40 Lê Hiến Mai, P. Hòa Khánh, Tp.Đà Nẵng</span>
                                <span><i class="fa-solid fa-phone-volume mr-1.5"></i>0935 437 033 – 0376 758 097</span>
                            </div>
                            <div class="pt-1.5 flex items-center gap-3">
                                <a href="#san-pham-thuc-te" class="bg-amber-400 hover:bg-amber-300 text-slate-950 font-extrabold text-xs px-4 py-2 rounded-md shadow-xs transition">
                                    XEM ẢNH SẢN PHẨM THỰC TẾ
                                </a>
                                <a href="#form-bao-gia" class="bg-white/15 hover:bg-white/25 text-white border border-white/30 font-bold text-xs px-4 py-2 rounded-md transition">
                                    NHẬN BÁO GIÁ TẠI XƯỞNG
                                </a>
                            </div>
                        </div>

                        <!-- Cột ảnh thực tế bên phải banner máy tính -->
                        <div class="col-span-5 h-full flex items-center justify-end gap-3 z-10">
                            <div class="w-1/2 h-[270px] lg:h-[295px] rounded-lg overflow-hidden border-2 border-white/30 shadow-lg bg-white">
                                <img src="https://lh3.googleusercontent.com/d/1Ca4i0-aZt_U98yfMk1xEBe2mBnuQwBx7"
                                     data-drive-id="1Ca4i0-aZt_U98yfMk1xEBe2mBnuQwBx7"
                                     onerror="handleDriveImageError(this)"
                                     alt="Sản phẩm thực tế Quân Phát 1"
                                     class="w-full h-full object-cover">
                            </div>
                            <div class="w-1/2 h-[270px] lg:h-[295px] rounded-lg overflow-hidden border-2 border-amber-400/70 shadow-lg bg-white">
                                <img src="https://lh3.googleusercontent.com/d/1B5nPgMgfz8GhoOPdL6pNFOzxGuIZZ8Bx"
                                     data-drive-id="1B5nPgMgfz8GhoOPdL6pNFOzxGuIZZ8Bx"
                                     onerror="handleDriveImageError(this)"
                                     alt="Sản phẩm thực tế Quân Phát 2"
                                     class="w-full h-full object-cover">
                            </div>
                        </div>
                    </div>

                    <!-- BẢN BANNER ĐIỆN THOẠI 1 (Thiết kế riêng cho Mobile, chiều cao bằng nhau h-[215px], chữ nhỏ gọn nằm hết trong ảnh) -->
                    <div class="grid md:hidden grid-cols-12 items-center w-full h-[215px] bg-gradient-to-br from-[#062c49] via-[#0b4f82] to-[#0f5c96] px-2.5 py-2.5 relative overflow-hidden">
                        <div class="col-span-7 min-w-0 pr-1.5 text-white space-y-1 z-10 overflow-hidden">
                            <span class="inline-block bg-amber-400 text-slate-950 text-[8.5px] font-extrabold px-1.5 py-0.5 rounded max-w-full truncate">
                                GIÁ GỐC TẠI XƯỞNG ĐÀ NẴNG
                            </span>
                            <h2 class="text-[12px] font-extrabold leading-tight text-white">
                                NỘI THẤT NHỰA QUÂN PHÁT
                            </h2>
                            <p class="text-[10px] text-amber-300 font-bold leading-tight">
                                Tủ Áo • Tủ Bếp • Giường Ngủ • Bàn Học Nhựa Đài Loan, Ecoplast
                            </p>
                            <div class="text-[9px] text-slate-100 leading-tight pt-0.5 space-y-0.5">
                                <div class="truncate"><i class="fa-solid fa-location-dot text-amber-400 mr-1"></i>40 Lê Hiến Mai, P.Hòa Khánh, ĐN</div>
                                <div class="truncate"><i class="fa-solid fa-phone text-amber-400 mr-1"></i>0935 437 033 – 0376 758 097</div>
                            </div>
                        </div>
                        <div class="col-span-5 min-w-0 h-[170px] rounded-lg overflow-hidden border border-white/30 bg-white shadow-sm">
                            <img src="https://lh3.googleusercontent.com/d/1Ca4i0-aZt_U98yfMk1xEBe2mBnuQwBx7"
                                 data-drive-id="1Ca4i0-aZt_U98yfMk1xEBe2mBnuQwBx7"
                                 onerror="handleDriveImageError(this)"
                                 alt="Banner Mobile Quân Phát 1"
                                 class="w-full h-full object-cover">
                        </div>
                    </div>
                </div>

                <!-- ================= SLIDE 2 ================= -->
                <div class="banner-slide transition-opacity duration-500 opacity-0 hidden" data-slide="1">
                    
                    <!-- BẢN BANNER MÁY TÍNH 2 (Cùng kích thước h-[340px] lg:h-[370px] bằng Slide 1) -->
                    <div class="hidden md:grid md:grid-cols-12 items-center w-full h-[340px] lg:h-[370px] bg-gradient-to-r from-[#07365a] via-[#0e5a8a] to-[#063254] px-8 lg:px-12 py-6 relative overflow-hidden">
                        <div class="col-span-7 pr-4 text-white z-10 space-y-2.5">
                            <div class="inline-block bg-amber-400 text-slate-950 text-[11px] font-extrabold uppercase px-3 py-1 rounded-md">
                                MIỄN PHÍ ĐO ĐẠC & THIẾT KẾ THEO KÍCH THƯỚC YÊU CẦU
                            </div>
                            <h2 class="text-xl lg:text-2xl xl:text-[26px] font-extrabold leading-snug text-white">
                                THI CÔNG TRỌN GÓI PHÒNG NGỦ & PHÒNG BẾP<br>
                                <span class="text-amber-300">ƯU ĐÃI GIẢM GIÁ LÊN ĐẾN 35% - 45% TẠI XƯỞNG</span>
                            </h2>
                            <p class="text-xs lg:text-[13px] text-slate-100 leading-relaxed max-w-xl">
                                Chuyên nhận đóng tủ áo kịch trần, tủ cánh lùa, tủ bếp nhựa chống ẩm mốc, bàn trang điểm, kệ tivi, ốp tường lam sóng nhựa cao cấp tại Đà Nẵng.
                            </p>
                            <div class="pt-1 flex flex-wrap items-center gap-x-5 gap-y-1.5 text-xs font-semibold text-amber-200">
                                <span><i class="fa-solid fa-globe mr-1.5"></i>Website: noithatnhuaquanphat.com</span>
                                <span><i class="fa-solid fa-phone-volume mr-1.5"></i>Hotline/Zalo: 0935 437 033 – 0376 758 097</span>
                            </div>
                            <div class="pt-1.5 flex items-center gap-3">
                                <a href="#form-bao-gia" class="bg-amber-400 hover:bg-amber-300 text-slate-950 font-extrabold text-xs px-4 py-2 rounded-md shadow-xs transition">
                                    ĐẶT LỊCH KHẢO SÁT TẬN NHÀ
                                </a>
                                <a href="#bando-fanpage" class="bg-white/15 hover:bg-white/25 text-white border border-white/30 font-bold text-xs px-4 py-2 rounded-md transition">
                                    XEM ĐỊA CHỈ XƯỞNG TRÊN BẢN ĐỒ
                                </a>
                            </div>
                        </div>

                        <div class="col-span-5 h-full flex items-center justify-end gap-3 z-10">
                            <div class="w-1/2 h-[270px] lg:h-[295px] rounded-lg overflow-hidden border-2 border-white/30 shadow-lg bg-white">
                                <img src="https://lh3.googleusercontent.com/d/1CVdxkRUQnqgmLjdNgoqk3jO8G7smMfy7"
                                     data-drive-id="1CVdxkRUQnqgmLjdNgoqk3jO8G7smMfy7"
                                     onerror="handleDriveImageError(this)"
                                     alt="Sản phẩm thực tế Quân Phát 3"
                                     class="w-full h-full object-cover">
                            </div>
                            <div class="w-1/2 h-[270px] lg:h-[295px] rounded-lg overflow-hidden border-2 border-amber-400/70 shadow-lg bg-white">
                                <img src="https://lh3.googleusercontent.com/d/1iTekNNs2j4p4A-OZDmHlIOubDD0Zbt0Y"
                                     data-drive-id="1iTekNNs2j4p4A-OZDmHlIOubDD0Zbt0Y"
                                     onerror="handleDriveImageError(this)"
                                     alt="Sản phẩm thực tế Quân Phát 4"
                                     class="w-full h-full object-cover">
                            </div>
                        </div>
                    </div>

                    <!-- BẢN BANNER ĐIỆN THOẠI 2 (Cùng chiều cao h-[215px] bằng Slide 1, chữ nhỏ gọn không tràn viền) -->
                    <div class="grid md:hidden grid-cols-12 items-center w-full h-[215px] bg-gradient-to-br from-[#07365a] via-[#0e5a8a] to-[#063254] px-2.5 py-2.5 relative overflow-hidden">
                        <div class="col-span-7 min-w-0 pr-1.5 text-white space-y-1 z-10 overflow-hidden">
                            <span class="inline-block bg-amber-400 text-slate-950 text-[8.5px] font-extrabold px-1.5 py-0.5 rounded max-w-full truncate">
                                MIỄN PHÍ ĐO ĐẠC TẬN NƠI
                            </span>
                            <h2 class="text-[12px] font-extrabold leading-tight text-white">
                                ĐÓNG TỦ NHỰA THEO YÊU CẦU
                            </h2>
                            <p class="text-[10px] text-amber-300 font-bold leading-tight">
                                Nhựa Chin Huei 2.0 Plus • Ecoplast • Chống Nước & Mối Mọt 100%
                            </p>
                            <div class="text-[9px] text-slate-100 leading-tight pt-0.5 space-y-0.5">
                                <div class="truncate"><i class="fa-solid fa-check-circle text-amber-400 mr-1"></i>Bảo hành uy tín tận nhà</div>
                                <div class="truncate"><i class="fa-solid fa-phone text-amber-400 mr-1"></i>0935 437 033 – 0376 758 097</div>
                            </div>
                        </div>
                        <div class="col-span-5 min-w-0 h-[170px] rounded-lg overflow-hidden border border-white/30 bg-white shadow-sm">
                            <img src="https://lh3.googleusercontent.com/d/1CVdxkRUQnqgmLjdNgoqk3jO8G7smMfy7"
                                 data-drive-id="1CVdxkRUQnqgmLjdNgoqk3jO8G7smMfy7"
                                 onerror="handleDriveImageError(this)"
                                 alt="Banner Mobile Quân Phát 2"
                                 class="w-full h-full object-cover">
                        </div>
                    </div>
                </div>

                <!-- Nút điều hướng Slide trái/phải & Chấm tròn chỉ báo -->
                <button type="button" onclick="changeSlide(-1)" aria-label="Slide trước" class="absolute left-2 top-1/2 -translate-y-1/2 w-7 h-7 md:w-9 md:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center z-20 transition">
                    <i class="fa-solid fa-chevron-left text-xs md:text-sm"></i>
                </button>
                <button type="button" onclick="changeSlide(1)" aria-label="Slide tiếp" class="absolute right-2 top-1/2 -translate-y-1/2 w-7 h-7 md:w-9 md:h-9 rounded-full bg-black/35 hover:bg-black/60 text-white flex items-center justify-center z-20 transition">
                    <i class="fa-solid fa-chevron-right text-xs md:text-sm"></i>
                </button>
                <div class="absolute bottom-2 left-1/2 -translate-x-1/2 flex items-center gap-2 z-20">
                    <button type="button" onclick="goToSlide(0)" id="slideDot0" class="w-6 h-2 rounded-full bg-amber-400 transition-all"></button>
                    <button type="button" onclick="goToSlide(1)" id="slideDot1" class="w-2.5 h-2 rounded-full bg-white/60 transition-all"></button>
                </div>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- SECTION 2: DANH MỤC SẢN PHẨM TRANG CHỦ (Chữ nhỏ gọn, đẹp trên PC & Mobile) -->
        <!-- ================================================================= -->
        <section id="danh-muc-san-pham" class="flatsome-container">
            <div class="bg-white rounded-xl p-3 md:p-4 border border-slate-200 shadow-xs">
                <div class="flex items-center justify-between mb-3 pb-2 border-b border-slate-100">
                    <h2 class="text-xs md:text-sm font-extrabold uppercase text-qp-primary flex items-center gap-2">
                        <i class="fa-solid fa-layer-group text-amber-500"></i>
                        DANH MỤC SẢN PHẨM NỘI THẤT NHỰA
                    </h2>
                    <span class="text-[11px] text-slate-500 hidden sm:inline">Chọn danh mục để lọc nhanh sản phẩm</span>
                </div>

                <!-- Lưới danh mục trang chủ: Chữ nhỏ gọn, không xuống dòng gãy chữ -->
                <div class="grid grid-cols-2 sm:grid-cols-4 lg:grid-cols-7 gap-2">
                    <button type="button" onclick="filterByCategory('all')" data-cat-btn="all" class="cat-pill active-cat flex items-center gap-2 p-2 rounded-lg border border-qp-primary bg-qp-primary text-white text-left transition">
                        <div class="w-7 h-7 rounded-md bg-white/20 flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-border-all text-xs"></i>
                        </div>
                        <div class="min-w-0">
                            <div class="text-[11px] font-bold leading-tight truncate">Tất Cả Mẫu</div>
                            <div class="text-[9.5px] opacity-85 truncate">13+ Ảnh thực tế</div>
                        </div>
                    </button>

                    <button type="button" onclick="filterByCategory('dai-loan')" data-cat-btn="dai-loan" class="cat-pill flex items-center gap-2 p-2 rounded-lg border border-slate-200 bg-slate-50 hover:border-qp-primary text-slate-800 text-left transition">
                        <div class="w-7 h-7 rounded-md bg-qp-light text-qp-primary flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-shirt text-xs"></i>
                        </div>
                        <div class="min-w-0">
                            <div class="text-[11px] font-bold leading-tight truncate">Nhựa Đài Loan</div>
                            <div class="text-[9.5px] text-slate-500 truncate">Tủ áo 2-6 cánh</div>
                        </div>
                    </button>

                    <button type="button" onclick="filterByCategory('chin-huei')" data-cat-btn="chin-huei" class="cat-pill flex items-center gap-2 p-2 rounded-lg border border-slate-200 bg-slate-50 hover:border-qp-primary text-slate-800 text-left transition">
                        <div class="w-7 h-7 rounded-md bg-qp-light text-qp-primary flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-medal text-xs"></i>
                        </div>
                        <div class="min-w-0">
                            <div class="text-[11px] font-bold leading-tight truncate">Nhựa Chin Huei</div>
                            <div class="text-[9.5px] text-slate-500 truncate">Bản 2.0 Plus</div>
                        </div>
                    </button>

                    <button type="button" onclick="filterByCategory('ecoplast')" data-cat-btn="ecoplast" class="cat-pill flex items-center gap-2 p-2 rounded-lg border border-slate-200 bg-slate-50 hover:border-qp-primary text-slate-800 text-left transition">
                        <div class="w-7 h-7 rounded-md bg-qp-light text-qp-primary flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-gem text-xs"></i>
                        </div>
                        <div class="min-w-0">
                            <div class="text-[11px] font-bold leading-tight truncate">Nhựa Ecoplast</div>
                            <div class="text-[9.5px] text-slate-500 truncate">Siêu cứng cáp</div>
                        </div>
                    </button>

                    <button type="button" onclick="filterByCategory('canh-lua')" data-cat-btn="canh-lua" class="cat-pill flex items-center gap-2 p-2 rounded-lg border border-slate-200 bg-slate-50 hover:border-qp-primary text-slate-800 text-left transition">
                        <div class="w-7 h-7 rounded-md bg-qp-light text-qp-primary flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-door-closed text-xs"></i>
                        </div>
                        <div class="min-w-0">
                            <div class="text-[11px] font-bold leading-tight truncate">Tủ Cánh Lùa</div>
                            <div class="text-[9.5px] text-slate-500 truncate">& Tủ kịch trần</div>
                        </div>
                    </button>

                    <button type="button" onclick="filterByCategory('tre-em-ban')" data-cat-btn="tre-em-ban" class="cat-pill flex items-center gap-2 p-2 rounded-lg border border-slate-200 bg-slate-50 hover:border-qp-primary text-slate-800 text-left transition">
                        <div class="w-7 h-7 rounded-md bg-qp-light text-qp-primary flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-graduation-cap text-xs"></i>
                        </div>
                        <div class="min-w-0">
                            <div class="text-[11px] font-bold leading-tight truncate">Tủ Trẻ Em & Bàn</div>
                            <div class="text-[9.5px] text-slate-500 truncate">Bàn học, Tủ giày</div>
                        </div>
                    </button>

                    <button type="button" onclick="filterByCategory('tu-bep-giuong')" data-cat-btn="tu-bep-giuong" class="cat-pill col-span-2 sm:col-span-1 flex items-center gap-2 p-2 rounded-lg border border-slate-200 bg-slate-50 hover:border-qp-primary text-slate-800 text-left transition">
                        <div class="w-7 h-7 rounded-md bg-qp-light text-qp-primary flex items-center justify-center shrink-0">
                            <i class="fa-solid fa-kitchen-set text-xs"></i>
                        </div>
                        <div class="min-w-0">
                            <div class="text-[11px] font-bold leading-tight truncate">Tủ Bếp & Giường</div>
                            <div class="text-[9.5px] text-slate-500 truncate">Combo & Lam sóng</div>
                        </div>
                    </button>
                </div>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- SECTION 3: 13 SẢN PHẨM THỰC TẾ TỪ GOOGLE DRIVE (CHIA 2 CỘT MOBILE)-->
        <!-- Có nhãn % giảm giá góc trên bên trái giống Flatsome & Giá giảm    -->
        <!-- ================================================================= -->
        <section id="san-pham-thuc-te" class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-star text-amber-400 text-sm"></i>
                        <h2 id="currentCategoryTitle" class="text-xs sm:text-sm md:text-base font-extrabold uppercase tracking-wide">
                            SẢN PHẨM THỰC TẾ THI CÔNG TẠI XƯỞNG QUÂN PHÁT
                        </h2>
                    </div>
                    <button type="button" onclick="filterByCategory('all')" class="text-[11px] md:text-xs font-bold text-amber-300 hover:underline shrink-0">
                        Xem tất cả (13) <i class="fa-solid fa-angle-right ml-0.5"></i>
                    </button>
                </div>
            </div>

            <!-- Grid sản phẩm: 2 cột trên điện thoại (grid-cols-2), 4 cột trên máy tính -->
            <div id="mainProductGrid" class="grid grid-cols-2 md:grid-cols-3 lg:grid-cols-4 gap-2.5 md:gap-4">
                <!-- Được render tự động từ mảng 13 ảnh thực tế Google Drive bên dưới -->
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- SECTION 4: TỦ ÁO NHỰA ĐÀI LOAN - CHIN HUEI - ECOPLAST NỔI BẬT     -->
        <!-- ================================================================= -->
        <section class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-fire text-amber-400 text-sm"></i>
                        <h2 class="text-xs sm:text-sm md:text-base font-extrabold uppercase tracking-wide">
                            TỦ QUẦN ÁO NHỰA ĐÀI LOAN & CHIN HUEI 2.0 PLUS BÁN CHẠY
                        </h2>
                    </div>
                    <a href="#form-bao-gia" class="text-[11px] md:text-xs font-bold text-amber-300 hover:underline shrink-0">
                        Đặt kích thước riêng <i class="fa-solid fa-angle-right ml-0.5"></i>
                    </a>
                </div>
            </div>

            <div id="wardrobeProductGrid" class="grid grid-cols-2 md:grid-cols-4 gap-2.5 md:gap-4">
                <!-- Render 8 mẫu tủ áo tiêu biểu -->
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- SECTION 5: TỦ BẾP NHỰA, GIƯỜNG NGỦ, BÀN HỌC & COMBO PHÒNG NGỦ      -->
        <!-- ================================================================= -->
        <section class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-kitchen-set text-amber-400 text-sm"></i>
                        <h2 class="text-xs sm:text-sm md:text-base font-extrabold uppercase tracking-wide">
                            TỦ BẾP NHỰA, GIƯỜNG NGỦ, BÀN HỌC & TỦ TRẺ EM CAO CẤP
                        </h2>
                    </div>
                    <a href="#form-bao-gia" class="text-[11px] md:text-xs font-bold text-amber-300 hover:underline shrink-0">
                        Tư vấn miễn phí <i class="fa-solid fa-angle-right ml-0.5"></i>
                    </a>
                </div>
            </div>

            <div id="kitchenBedProductGrid" class="grid grid-cols-2 md:grid-cols-4 gap-2.5 md:gap-4">
                <!-- Render các mẫu Tủ bếp, Giường ngủ, Bàn học, Tủ trẻ em -->
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- SECTION 6: FORM YÊU CẦU TƯ VẤN & BÁO GIÁ TRANG CHỦ                -->
        <!-- ================================================================= -->
        <section id="form-bao-gia" class="flatsome-container">
            <div class="bg-gradient-to-br from-qp-dark via-qp-primary to-[#0d5c94] rounded-xl p-4 md:p-6 text-white shadow-md border border-qp-primary">
                <div class="grid grid-cols-1 lg:grid-cols-12 gap-5 items-center">
                    
                    <!-- Cột thông tin cam kết xưởng -->
                    <div class="lg:col-span-5 space-y-3">
                        <div class="inline-block bg-amber-400 text-slate-950 text-[11px] font-extrabold uppercase px-2.5 py-1 rounded">
                            BÁO GIÁ TRỰC TIẾP TẠI XƯỞNG QUÂN PHÁT
                        </div>
                        <h2 class="text-base md:text-xl font-extrabold leading-snug">
                            ĐĂNG KÝ YÊU CẦU TƯ VẤN, ĐO ĐẠC TẬN NHÀ & NHẬN BÁO GIÁ MIỄN PHÍ
                        </h2>
                        <p class="text-xs md:text-sm text-slate-100 leading-relaxed">
                            Quý khách tại Đà Nẵng và khu vực lân cận chỉ cần để lại thông tin hoặc kích thước mong muốn, kỹ thuật viên <strong>Nội Thất Nhựa Quân Phát</strong> sẽ liên hệ báo giá chi tiết và mang mẫu nhựa tận nơi khảo sát miễn phí!
                        </p>
                        <div class="space-y-2 pt-1 text-xs md:text-sm">
                            <div class="flex items-start gap-2.5">
                                <i class="fa-solid fa-circle-check text-amber-400 mt-0.5"></i>
                                <span><strong>Xưởng sản xuất:</strong> 40 Lê Hiến Mai, Phường Hòa Khánh, Tp.Đà Nẵng</span>
                            </div>
                            <div class="flex items-start gap-2.5">
                                <i class="fa-solid fa-circle-check text-amber-400 mt-0.5"></i>
                                <span><strong>Hotline / Zalo hỗ trợ 24/7:</strong> 0935 437 033 – 0376 758 097</span>
                            </div>
                            <div class="flex items-start gap-2.5">
                                <i class="fa-solid fa-circle-check text-amber-400 mt-0.5"></i>
                                <span><strong>Cam kết:</strong> Nhựa chính hãng dày dặn, phụ kiện bản lề giảm chấn inox bền bỉ, bảo hành dài hạn.</span>
                            </div>
                        </div>
                    </div>

                    <!-- Cột Form nhập yêu cầu báo giá -->
                    <div class="lg:col-span-7 bg-white text-slate-800 rounded-xl p-4 md:p-5 shadow-lg">
                        <h3 class="text-sm md:text-base font-extrabold text-qp-primary uppercase mb-3 border-b border-slate-100 pb-2">
                            <i class="fa-solid fa-file-invoice-dollar text-amber-500 mr-1.5"></i>Form Yêu Cầu & Báo Giá Nhanh
                        </h3>
                        <form id="quoteRequestForm" onsubmit="submitQuoteForm(event)" class="space-y-3 text-xs md:text-sm">
                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block font-bold text-slate-700 mb-1">Họ và tên khách hàng *</label>
                                    <input type="text" id="qName" required placeholder="Nhập họ tên của bạn..." class="w-full px-3 py-2 border border-slate-300 rounded-md focus:outline-none focus:border-qp-primary">
                                </div>
                                <div>
                                    <label class="block font-bold text-slate-700 mb-1">Số điện thoại / Zalo *</label>
                                    <input type="tel" id="qPhone" required placeholder="Ví dụ: 0935 437 033" class="w-full px-3 py-2 border border-slate-300 rounded-md focus:outline-none focus:border-qp-primary">
                                </div>
                            </div>

                            <div class="grid grid-cols-1 sm:grid-cols-2 gap-3">
                                <div>
                                    <label class="block font-bold text-slate-700 mb-1">Danh mục sản phẩm quan tâm</label>
                                    <select id="qCategory" class="w-full px-3 py-2 border border-slate-300 rounded-md focus:outline-none focus:border-qp-primary bg-white">
                                        <option value="Tủ quần áo nhựa Đài Loan / Chin Huei">Tủ quần áo nhựa Đài Loan / Chin Huei</option>
                                        <option value="Tủ quần áo cánh lùa / Full trần">Tủ quần áo cánh lùa / Full trần</option>
                                        <option value="Nội thất nhựa cao cấp Ecoplast">Nội thất nhựa cao cấp Ecoplast</option>
                                        <option value="Nội thất nhựa Chin Huei 2.0 Plus">Nội thất nhựa Chin Huei 2.0 Plus</option>
                                        <option value="Tủ bếp nhựa chống nước cao cấp">Tủ bếp nhựa chống nước cao cấp</option>
                                        <option value="Giường ngủ nhựa & Combo phòng ngủ">Giường ngủ nhựa & Combo phòng ngủ</option>
                                        <option value="Tủ trẻ em, Bàn học, Bàn trang điểm">Tủ trẻ em, Bàn học, Bàn trang điểm</option>
                                        <option value="Thi công ốp tường, lam sóng, trần nhựa">Thi công ốp tường, lam sóng, trần nhựa</option>
                                    </select>
                                </div>
                                <div>
                                    <label class="block font-bold text-slate-700 mb-1">Địa chỉ lắp đặt (Quận/Phường tại Đà Nẵng)</label>
                                    <input type="text" id="qAddress" placeholder="VD: Hòa Khánh, Liên Chiểu, Hải Châu..." class="w-full px-3 py-2 border border-slate-300 rounded-md focus:outline-none focus:border-qp-primary">
                                </div>
                            </div>

                            <div>
                                <label class="block font-bold text-slate-700 mb-1">Yêu cầu chi tiết (Kích thước, màu sắc, mẫu mã...)</label>
                                <textarea id="qNote" rows="2" placeholder="Nhập kích thước dự kiến hoặc tên sản phẩm bạn muốn báo giá..." class="w-full px-3 py-2 border border-slate-300 rounded-md focus:outline-none focus:border-qp-primary"></textarea>
                            </div>

                            <div class="flex flex-wrap items-center justify-between gap-2 pt-1">
                                <button type="submit" class="w-full sm:w-auto bg-qp-sale hover:bg-red-700 text-white font-extrabold px-5 py-2.5 rounded-md shadow-sm transition flex items-center justify-center gap-2 cursor-pointer">
                                    <i class="fa-solid fa-paper-plane"></i>
                                    <span>GỬI YÊU CẦU & NHẬN BÁO GIÁ NGAY</span>
                                </button>
                                <span class="text-[11px] text-slate-500">
                                    Tư vấn trực tiếp qua Zalo: <strong class="text-qp-primary">0935 437 033 – 0376 758 097</strong>
                                </span>
                            </div>

                            <!-- Hộp thông báo xác nhận trực tiếp trên trang (Không dùng alert) -->
                            <div id="quoteSuccessBox" class="hidden p-3 rounded-lg bg-emerald-50 border border-emerald-300 text-emerald-800 text-xs font-medium"></div>
                        </form>
                    </div>
                </div>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- SECTION 7: DANH MỤC CÁC BÀI VIẾT TRANG CHỦ (TƯ VẤN & KINH NGHIỆM) -->
        <!-- ================================================================= -->
        <section id="bai-viet-trang-chu" class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-newspaper text-amber-400 text-sm"></i>
                        <h2 class="text-xs sm:text-sm md:text-base font-extrabold uppercase tracking-wide">
                            DANH MỤC BÀI VIẾT & KINH NGHIỆM CHỌN NỘI THẤT NHỰA
                        </h2>
                    </div>
                    <span class="text-[11px] md:text-xs font-semibold text-amber-200 hidden sm:inline">
                        Cẩm nang nội thất nhựa Đà Nẵng
                    </span>
                </div>
            </div>

            <div class="grid grid-cols-1 sm:grid-cols-2 lg:grid-cols-4 gap-3 md:gap-4">
                <!-- Bài viết 1 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between">
                    <div>
                        <div class="h-40 w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1Ca4i0-aZt_U98yfMk1xEBe2mBnuQwBx7"
                                 data-drive-id="1Ca4i0-aZt_U98yfMk1xEBe2mBnuQwBx7"
                                 onerror="handleDriveImageError(this)"
                                 alt="So sánh nhựa Ecoplast và nhựa Chin Huei Đài Loan"
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-3">
                            <div class="text-[10.5px] font-bold text-qp-primary uppercase mb-1">Tư Vấn Vật Liệu Nhựa</div>
                            <h3 class="text-xs md:text-[13.5px] font-extrabold text-slate-800 leading-snug mb-1.5">
                                So sánh tủ nhựa Đài Loan Chin Huei và nhựa cao cấp Ecoplast: Nên chọn loại nào?
                            </h3>
                            <p class="text-[11.5px] text-slate-600 leading-relaxed">
                                Phân tích chi tiết cấu tạo tấm nhựa 2 lớp, gân tăng cứng, độ chịu lực, khả năng chống nước 100% và chống mối mọt tuyệt đối tại Đà Nẵng.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 pt-1">
                        <a href="#form-bao-gia" class="text-[11px] font-bold text-qp-primary hover:text-amber-600 inline-flex items-center gap-1">
                            Nhận tư vấn mẫu nhựa <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 2 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between">
                    <div>
                        <div class="h-40 w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1CVdxkRUQnqgmLjdNgoqk3jO8G7smMfy7"
                                 data-drive-id="1CVdxkRUQnqgmLjdNgoqk3jO8G7smMfy7"
                                 onerror="handleDriveImageError(this)"
                                 alt="Kinh nghiệm đóng tủ quần áo nhựa kịch trần cánh lùa"
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-3">
                            <div class="text-[10.5px] font-bold text-qp-primary uppercase mb-1">Giải Pháp Phòng Ngủ</div>
                            <h3 class="text-xs md:text-[13.5px] font-extrabold text-slate-800 leading-snug mb-1.5">
                                Kinh nghiệm đóng tủ quần áo nhựa kịch trần & cánh lùa tối ưu diện tích phòng ngủ
                            </h3>
                            <p class="text-[11.5px] text-slate-600 leading-relaxed">
                                Tủ nhựa cánh lùa kết hợp kệ góc trang trí và hộc để chăn màn phía trên giúp tiết kiệm không gian mở cửa cho nhà phố và căn hộ.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 pt-1">
                        <a href="#form-bao-gia" class="text-[11px] font-bold text-qp-primary hover:text-amber-600 inline-flex items-center gap-1">
                            Đặt lịch đo đạc tận nơi <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 3 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between">
                    <div>
                        <div class="h-40 w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1RmJlqi7GU1cSxZI9l1dLhgehw9YfhUkV"
                                 data-drive-id="1RmJlqi7GU1cSxZI9l1dLhgehw9YfhUkV"
                                 onerror="handleDriveImageError(this)"
                                 alt="Báo giá thi công tủ bếp nhựa tại Đà Nẵng"
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-3">
                            <div class="text-[10.5px] font-bold text-qp-primary uppercase mb-1">Nội Thất Phòng Bếp</div>
                            <h3 class="text-xs md:text-[13.5px] font-extrabold text-slate-800 leading-snug mb-1.5">
                                Báo giá thi công tủ bếp nhựa Ecoplast & Chin Huei 2.0 Plus chống ẩm mốc tại Đà Nẵng
                            </h3>
                            <p class="text-[11.5px] text-slate-600 leading-relaxed">
                                Giải pháp thay thế bền bỉ cho tủ bếp gỗ công nghiệp dễ ẩm mốc. Tủ bếp nhựa Quân Phát chịu nước tuyệt đối, bề mặt bóng mịn dễ lau chùi.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 pt-1">
                        <a href="#form-bao-gia" class="text-[11px] font-bold text-qp-primary hover:text-amber-600 inline-flex items-center gap-1">
                            Xem báo giá tại xưởng <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>

                <!-- Bài viết 4 -->
                <article class="bg-white rounded-lg border border-slate-200 overflow-hidden shadow-xs flex flex-col justify-between">
                    <div>
                        <div class="h-40 w-full overflow-hidden bg-slate-100">
                            <img src="https://lh3.googleusercontent.com/d/1Wznb_uJwitLeAostLt4mhNwilQLUVfUe"
                                 data-drive-id="1Wznb_uJwitLeAostLt4mhNwilQLUVfUe"
                                 onerror="handleDriveImageError(this)"
                                 alt="Chọn bàn học sinh và tủ nhựa trẻ em an toàn"
                                 class="w-full h-full object-cover hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-3">
                            <div class="text-[10.5px] font-bold text-qp-primary uppercase mb-1">Nội Thất Trẻ Em</div>
                            <h3 class="text-xs md:text-[13.5px] font-extrabold text-slate-800 leading-snug mb-1.5">
                                Cách chọn tủ nhựa trẻ em & bàn học đôi liền giá sách chuẩn kích thước chống gù
                            </h3>
                            <p class="text-[11.5px] text-slate-600 leading-relaxed">
                                Nhựa nguyên sinh an toàn không mùi, màu sắc tươi sáng giúp bé rèn luyện thói quen tự sắp xếp quần áo và góc học tập ngăn nắp.
                            </p>
                        </div>
                    </div>
                    <div class="px-3 pb-3 pt-1">
                        <a href="#form-bao-gia" class="text-[11px] font-bold text-qp-primary hover:text-amber-600 inline-flex items-center gap-1">
                            Tư vấn mẫu cho bé <i class="fa-solid fa-arrow-right text-[10px]"></i>
                        </a>
                    </div>
                </article>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- SECTION 8: DANH MỤC CÁC ĐỐI TÁC THƯƠNG HIỆU VẬT LIỆU CHÍNH HÃNG    -->
        <!-- ================================================================= -->
        <section id="danh-muc-doi-tac" class="flatsome-container">
            <div class="bg-white rounded-xl p-3.5 md:p-5 border border-slate-200 shadow-xs">
                <div class="flex flex-wrap items-center justify-between gap-2 mb-3 pb-2 border-b border-slate-100">
                    <h2 class="text-xs sm:text-sm md:text-base font-extrabold uppercase text-qp-primary flex items-center gap-2">
                        <i class="fa-solid fa-handshake text-amber-500"></i>
                        DANH MỤC CÁC ĐỐI TÁC CUNG CẤP VẬT LIỆU & PHỤ KIỆN CHÍNH HÃNG
                    </h2>
                    <span class="text-[11px] text-slate-500">Cam kết 100% tấm nhựa chính hãng có logo dập chìm</span>
                </div>

                <div class="grid grid-cols-2 sm:grid-cols-3 lg:grid-cols-6 gap-2.5">
                    <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
                        <div class="text-xs md:text-sm font-extrabold text-qp-primary tracking-tight">CHIN HUEI</div>
                        <div class="text-[10.5px] text-slate-600 font-medium mt-0.5">Nhựa Đài Loan Chính Hãng</div>
                    </div>
                    <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
                        <div class="text-xs md:text-sm font-extrabold text-emerald-700 tracking-tight">ECOPLAST</div>
                        <div class="text-[10.5px] text-slate-600 font-medium mt-0.5">Nhựa Cao Cấp Siêu Bền</div>
                    </div>
                    <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
                        <div class="text-xs md:text-sm font-extrabold text-amber-600 tracking-tight">CHIN HUEI 2.0 PLUS</div>
                        <div class="text-[10.5px] text-slate-600 font-medium mt-0.5">Dòng Nhựa Dày Pro18</div>
                    </div>
                    <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
                        <div class="text-xs md:text-sm font-extrabold text-blue-700 tracking-tight">ECOSTAR</div>
                        <div class="text-[10.5px] text-slate-600 font-medium mt-0.5">Tấm Nhựa Nội Thất Cao Cấp</div>
                    </div>
                    <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
                        <div class="text-xs md:text-sm font-extrabold text-slate-800 tracking-tight">LAM SÓNG & PVC</div>
                        <div class="text-[10.5px] text-slate-600 font-medium mt-0.5">Ốp Tường Vân Đá & Vân Gỗ</div>
                    </div>
                    <div class="p-3 rounded-lg border border-slate-200 bg-slate-50 text-center flex flex-col items-center justify-center">
                        <div class="text-xs md:text-sm font-extrabold text-qp-sale tracking-tight">PHỤ KIỆN INOX 304</div>
                        <div class="text-[10.5px] text-slate-600 font-medium mt-0.5">Bản Lề Giảm Chấn & Ray Bi</div>
                    </div>
                </div>
            </div>
        </section>

        <!-- ================================================================= -->
        <!-- SECTION 9: ĐƯA GOOGLE MAP & FANPAGE FACEBOOK RA NGOÀI TRANG CHỦ    -->
        <!-- ================================================================= -->
        <section id="bando-fanpage" class="flatsome-container">
            <div class="section-title-container">
                <div class="section-title-main">
                    <div class="flex items-center gap-2">
                        <i class="fa-solid fa-map-location-dot text-amber-400 text-sm"></i>
                        <h2 class="text-xs sm:text-sm md:text-base font-extrabold uppercase tracking-wide">
                            BẢN ĐỒ GOOGLE MAPS & KẾT NỐI FANPAGE TRANG CHỦ
                        </h2>
                    </div>
                    <span class="text-[11px] md:text-xs font-semibold text-amber-200 hidden sm:inline">
                        40 Lê Hiến Mai, Phường Hòa Khánh, Tp.Đà Nẵng
                    </span>
                </div>
            </div>

            <div class="grid grid-cols-1 lg:grid-cols-12 gap-4">
                <!-- Cột Google Maps ngoài trang chủ (7 phần) -->
                <div class="lg:col-span-7 bg-white rounded-xl border border-slate-200 p-3 md:p-4 shadow-xs flex flex-col justify-between">
                    <div class="flex flex-wrap items-center justify-between gap-2 mb-2.5">
                        <div>
                            <h3 class="text-xs md:text-sm font-extrabold text-qp-primary uppercase">
                                <i class="fa-solid fa-location-dot text-qp-sale mr-1.5"></i>Địa Chỉ Xưởng Nội Thất Nhựa Quân Phát
                            </h3>
                            <p class="text-[11.5px] text-slate-600 mt-0.5">
                                Đ/c: <strong>40 Lê Hiến Mai, Phường Hòa Khánh, Tp.Đà Nẵng</strong> | Hotline: <strong>0935 437 033 – 0376 758 097</strong>
                            </p>
                        </div>
                        <a href="https://www.google.com/maps/search/?api=1&query=40+L%C3%AA+Hi%E1%BA%BFn+Mai,+H%C3%B2a+Kh%C3%A1nh,+%C4%90%C3%A0+N%E1%BA%B5ng"
                           target="_blank" rel="noopener noreferrer"
                           class="inline-flex items-center gap-1.5 bg-qp-primary hover:bg-qp-dark text-white text-[11px] font-bold px-3 py-1.5 rounded-md transition">
                            <i class="fa-solid fa-diamond-turn-right"></i> Xem Chỉ Đường Lớn
                        </a>
                    </div>

                    <div class="w-full h-[270px] md:h-[320px] rounded-lg overflow-hidden border border-slate-200 bg-slate-100">
                        <iframe
                            title="Bản đồ Nội Thất Nhựa Quân Phát - 40 Lê Hiến Mai, Phường Hòa Khánh, Tp.Đà Nẵng"
                            src="https://maps.google.com/maps?q=40%20L%C3%AA%20Hi%E1%BA%BFn%20Mai,%20H%C3%B2a%20Kh%C3%A1nh,%20%C4%90%C3%A0%20N%E1%BA%B5ng&t=&z=16&ie=UTF8&iwloc=&output=embed"
                            class="w-full h-full border-0"
                            loading="lazy"
                            referrerpolicy="no-referrer-when-downgrade">
                        </iframe>
                    </div>
                </div>

                <!-- Cột Fanpage Facebook ngoài trang chủ (5 phần) -->
                <div class="lg:col-span-5 bg-white rounded-xl border border-slate-200 p-3 md:p-4 shadow-xs flex flex-col justify-between">
                    <div>
                        <div class="flex items-center justify-between gap-2 mb-2.5">
                            <h3 class="text-xs md:text-sm font-extrabold text-[#1877F2] uppercase flex items-center gap-1.5">
                                <i class="fa-brands fa-facebook text-base"></i> Fanpage Facebook Chính Thức
                            </h3>
                            <a href="https://www.facebook.com/profile.php?id=61559665464907"
                               target="_blank" rel="noopener noreferrer"
                               class="text-[11px] font-bold text-[#1877F2] hover:underline">
                                Mở Fanpage <i class="fa-solid fa-up-right-from-square text-[10px]"></i>
                            </a>
                        </div>

                        <!-- Khung hiển thị Fanpage trực quan ngoài trang chủ -->
                        <div class="rounded-lg border border-slate-200 overflow-hidden bg-slate-50">
                            <div class="bg-gradient-to-r from-[#07365a] to-[#0b4f82] p-3 text-white flex items-center gap-3">
                                <img src="https://lh3.googleusercontent.com/d/16zCoeKfJPHYNPIpp_HZUue-C-j9kbIg3"
                                     data-drive-id="16zCoeKfJPHYNPIpp_HZUue-C-j9kbIg3"
                                     onerror="handleDriveImageError(this)"
                                     alt="Logo Nội Thất Nhựa Quân Phát"
                                     class="w-12 h-12 rounded-lg bg-white p-1 object-contain shrink-0">
                                <div class="min-w-0">
                                    <a href="https://www.facebook.com/profile.php?id=61559665464907"
                                       target="_blank" rel="noopener noreferrer"
                                       class="text-sm font-extrabold text-white hover:underline block truncate">
                                        Nội Thất Nhựa Quân Phát
                                    </a>
                                    <div class="text-[11px] text-amber-300 font-medium truncate">
                                        Tư vấn – Thiết kế – Sản xuất – Thi công nội thất nhựa
                                    </div>
                                    <div class="mt-1.5 flex flex-wrap gap-2">
                                        <a href="https://www.facebook.com/profile.php?id=61559665464907"
                                           target="_blank" rel="noopener noreferrer"
                                           class="inline-flex items-center gap-1 bg-[#1877F2] hover:bg-blue-700 text-white text-[10.5px] font-bold px-2.5 py-1 rounded">
                                            <i class="fa-solid fa-thumbs-up"></i> Theo dõi trang
                                        </a>
                                        <a href="https://www.facebook.com/profile.php?id=61559665464907"
                                           target="_blank" rel="noopener noreferrer"
                                           class="inline-flex items-center gap-1 bg-white text-slate-800 hover:bg-slate-100 text-[10.5px] font-bold px-2.5 py-1 rounded">
                                            <i class="fa-brands fa-facebook-messenger text-[#1877F2]"></i> Nhắn tin
                                        </a>
                                    </div>
                                </div>
                            </div>

                            <!-- Ảnh sản phẩm thực tế trên Fanpage -->
                            <div class="p-3 space-y-2">
                                <div class="text-[11px] text-slate-600 leading-relaxed">
                                    <i class="fa-solid fa-circle-check text-emerald-600 mr-1"></i>
                                    Cập nhật hình ảnh bàn giao lắp đặt thực tế hằng ngày tại <strong>40 Lê Hiến Mai, P. Hòa Khánh, Tp.Đà Nẵng</strong>.
                                </div>
                                <div class="grid grid-cols-4 gap-1.5">
                                    <a href="https://www.facebook.com/profile.php?id=61559665464907" target="_blank" rel="noopener noreferrer" class="h-16 rounded overflow-hidden border border-slate-200 block">
                                        <img src="https://lh3.googleusercontent.com/d/1Ca4i0-aZt_U98yfMk1xEBe2mBnuQwBx7" data-drive-id="1Ca4i0-aZt_U98yfMk1xEBe2mBnuQwBx7" onerror="handleDriveImageError(this)" alt="Ảnh thực tế 1" class="w-full h-full object-cover">
                                    </a>
                                    <a href="https://www.facebook.com/profile.php?id=61559665464907" target="_blank" rel="noopener noreferrer" class="h-16 rounded overflow-hidden border border-slate-200 block">
                                        <img src="https://lh3.googleusercontent.com/d/1B5nPgMgfz8GhoOPdL6pNFOzxGuIZZ8Bx" data-drive-id="1B5nPgMgfz8GhoOPdL6pNFOzxGuIZZ8Bx" onerror="handleDriveImageError(this)" alt="Ảnh thực tế 2" class="w-full h-full object-cover">
                                    </a>
                                    <a href="https://www.facebook.com/profile.php?id=61559665464907" target="_blank" rel="noopener noreferrer" class="h-16 rounded overflow-hidden border border-slate-200 block">
                                        <img src="https://lh3.googleusercontent.com/d/1CVdxkRUQnqgmLjdNgoqk3jO8G7smMfy7" data-drive-id="1CVdxkRUQnqgmLjdNgoqk3jO8G7smMfy7" onerror="handleDriveImageError(this)" alt="Ảnh thực tế 3" class="w-full h-full object-cover">
                                    </a>
                                    <a href="https://www.facebook.com/profile.php?id=61559665464907" target="_blank" rel="noopener noreferrer" class="h-16 rounded overflow-hidden border border-slate-200 block">
                                        <img src="https://lh3.googleusercontent.com/d/1RmJlqi7GU1cSxZI9l1dLhgehw9YfhUkV" data-drive-id="1RmJlqi7GU1cSxZI9l1dLhgehw9YfhUkV" onerror="handleDriveImageError(this)" alt="Ảnh thực tế 4" class="w-full h-full object-cover">
                                    </a>
                                </div>
                            </div>
                        </div>
                    </div>

                    <div class="mt-3 pt-2.5 border-t border-slate-100 flex flex-wrap items-center justify-between gap-2 text-xs">
                        <span class="font-semibold text-slate-700">
                            <i class="fa-solid fa-phone-volume text-qp-sale mr-1"></i>0935 437 033 – 0376 758 097
                        </span>
                        <a href="https://www.facebook.com/profile.php?id=61559665464907"
                           target="_blank" rel="noopener noreferrer"
                           class="bg-[#1877F2] hover:bg-blue-700 text-white font-bold text-[11px] px-3 py-1.5 rounded-md transition">
                            Kết Nối Fanpage Quân Phát
                        </a>
                    </div>
                </div>
            </div>
        </section>

    </main>

    <!-- ===================================================================== -->
    <!-- FOOTER CHUẨN FLATSOME                                                 -->
    <!-- ===================================================================== -->
    <footer id="footer" class="bg-qp-dark text-slate-200 pt-8 pb-20 lg:pb-8 border-t-4 border-amber-400">
        <div class="flatsome-container">
            <div class="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-12 gap-6 pb-6 border-b border-white/10">
                <!-- Cột 1: Thông tin xưởng -->
                <div class="lg:col-span-5 space-y-2.5">
                    <div class="flex items-center gap-2.5">
                        <img src="https://lh3.googleusercontent.com/d/16zCoeKfJPHYNPIpp_HZUue-C-j9kbIg3"
                             data-drive-id="16zCoeKfJPHYNPIpp_HZUue-C-j9kbIg3"
                             onerror="handleDriveImageError(this)"
                             alt="Logo Nội Thất Nhựa Quân Phát"
                             class="w-10 h-10 rounded-lg bg-white p-0.5 object-contain shrink-0">
                        <div>
                            <div class="text-sm md:text-base font-extrabold text-white uppercase">NỘI THẤT NHỰA QUÂN PHÁT</div>
                            <div class="text-xs font-semibold text-amber-300">Website: noithatnhuaquanphat.com</div>
                        </div>
                    </div>
                    <p class="text-xs text-slate-300 leading-relaxed">
                        Chuyên tư vấn, thiết kế, sản xuất và thi công nội thất nhựa Đài Loan, Chin Huei, Ecoplast, Chin Huei 2.0 Plus, Ecostar cao cấp tại Đà Nẵng. Giá gốc trực tiếp tại xưởng – Đo đạc & lắp đặt tận nơi.
                    </p>
                    <ul class="space-y-1.5 text-xs text-slate-200">
                        <li><i class="fa-solid fa-location-dot text-amber-400 w-4"></i> <strong>Địa chỉ:</strong> 40 Lê Hiến Mai, Phường Hòa Khánh, Tp.Đà Nẵng</li>
                        <li><i class="fa-solid fa-phone-volume text-amber-400 w-4"></i> <strong>Hotline / Zalo:</strong> 0935 437 033 – 0376 758 097</li>
                        <li><i class="fa-brands fa-facebook text-amber-400 w-4"></i> <strong>Fanpage:</strong> <a href="https://www.facebook.com/profile.php?id=61559665464907" target="_blank" rel="noopener noreferrer" class="underline hover:text-amber-300">Nội Thất Nhựa Quân Phát</a></li>
                    </ul>
                </div>

                <!-- Cột 2: Danh mục sản phẩm -->
                <div class="lg:col-span-4 space-y-2">
                    <h3 class="text-xs md:text-sm font-extrabold uppercase text-amber-400">DANH MỤC SẢN PHẨM CHÍNH</h3>
                    <ul class="grid grid-cols-1 sm:grid-cols-2 gap-1.5 text-xs text-slate-300">
                        <li><a href="#danh-muc-san-pham" onclick="filterByCategory('dai-loan')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right text-[10px] mr-1"></i>Nội thất nhựa Đài Loan</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="filterByCategory('chin-huei')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right text-[10px] mr-1"></i>Nội thất nhựa Chin Huei</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="filterByCategory('ecoplast')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right text-[10px] mr-1"></i>Nội thất nhựa Ecoplast</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="filterByCategory('chin-huei')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right text-[10px] mr-1"></i>Chin Huei 2.0 Plus - Pro18</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="filterByCategory('ecoplast')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right text-[10px] mr-1"></i>Nội thất nhựa Ecostar</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="filterByCategory('canh-lua')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right text-[10px] mr-1"></i>Tủ áo cánh lùa & kịch trần</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="filterByCategory('tu-bep-giuong')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right text-[10px] mr-1"></i>Tủ bếp & Giường ngủ nhựa</a></li>
                        <li><a href="#danh-muc-san-pham" onclick="filterByCategory('tre-em-ban')" class="hover:text-amber-300"><i class="fa-solid fa-angle-right text-[10px] mr-1"></i>Tủ trẻ em & Bàn học sinh</a></li>
                    </ul>
                </div>

                <!-- Cột 3: Cam kết chất lượng -->
                <div class="lg:col-span-3 space-y-2">
                    <h3 class="text-xs md:text-sm font-extrabold uppercase text-amber-400">CAM KẾT TẠI XƯỞNG</h3>
                    <ul class="space-y-1.5 text-xs text-slate-300">
                        <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Khảo sát & đo đạc tận nhà miễn phí</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Thiết kế theo kích thước yêu cầu</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Chống nước, chống mối mọt 100%</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Giao hàng & lắp đặt nhanh tại Đà Nẵng</li>
                        <li><i class="fa-solid fa-check text-emerald-400 mr-1.5"></i>Bảo hành uy tín tận nhà dài hạn</li>
                    </ul>
                </div>
            </div>

            <div class="pt-4 flex flex-wrap items-center justify-between gap-2 text-[11px] text-slate-400">
                <div>© 2025 <strong>Nội Thất Nhựa Quân Phát (noithatnhuaquanphat.com)</strong>. Đ/c: 40 Lê Hiến Mai, P. Hòa Khánh, Tp.Đà Nẵng.</div>
                <div>Thiết kế chuẩn bố cục Flatsome UX Builder – Tương thích Điện thoại & Máy tính.</div>
            </div>
        </div>
    </footer>

    <!-- ===================================================================== -->
    <!-- CỤM NÚT LIÊN HỆ NỔI BẬT (ZALO, FACEBOOK, HOTLINE) TRÊN PC & MOBILE    -->
    <!-- ===================================================================== -->
    <div class="fixed right-2.5 bottom-4 z-40 flex flex-col items-end gap-2">
        <!-- Nút Zalo nổi bật -->
        <a href="https://zalo.me/0935437033"
           target="_blank" rel="noopener noreferrer"
           class="flex items-center gap-2 bg-[#0068ff] hover:bg-blue-700 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-6 h-6 rounded-full bg-white text-[#0068ff] font-extrabold text-[10px] flex items-center justify-center shrink-0">Zalo</span>
            <span class="text-xs font-bold hidden sm:inline">Chat Zalo: 0935 437 033</span>
        </a>

        <!-- Nút Facebook Fanpage nổi bật -->
        <a href="https://www.facebook.com/profile.php?id=61559665464907"
           target="_blank" rel="noopener noreferrer"
           class="flex items-center gap-2 bg-[#1877F2] hover:bg-blue-800 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-6 h-6 rounded-full bg-white/20 flex items-center justify-center shrink-0">
                <i class="fa-brands fa-facebook-f text-xs"></i>
            </span>
            <span class="text-xs font-bold hidden sm:inline">Fanpage Quân Phát</span>
        </a>

        <!-- Nút Hotline 1 nổi bật -->
        <a href="tel:0935437033"
           class="pulse-btn flex items-center gap-2 bg-qp-sale hover:bg-red-700 text-white px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-6 h-6 rounded-full bg-white/20 flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone-volume text-xs"></i>
            </span>
            <span class="text-xs font-extrabold">0935 437 033</span>
        </a>

        <!-- Nút Hotline 2 nổi bật -->
        <a href="tel:0376758097"
           class="flex items-center gap-2 bg-amber-500 hover:bg-amber-600 text-slate-950 px-3 py-2 rounded-full shadow-lg transition">
            <span class="w-6 h-6 rounded-full bg-black/15 flex items-center justify-center shrink-0">
                <i class="fa-solid fa-phone text-xs"></i>
            </span>
            <span class="text-xs font-extrabold">0376 758 097</span>
        </a>
    </div>

    <!-- ===================================================================== -->
    <!-- MODAL XEM CHI TIẾT SẢN PHẨM & ĐẶT HÀNG NHANH                          -->
    <!-- ===================================================================== -->
    <div id="productModal" class="fixed inset-0 bg-slate-900/70 z-50 hidden items-center justify-center p-3" onclick="closeProductModal()">
        <div class="bg-white rounded-xl max-w-2xl w-full overflow-hidden shadow-2xl border border-slate-200" onclick="event.stopPropagation()">
            <div class="bg-qp-primary text-white px-4 py-3 flex items-center justify-between">
                <h3 id="modalProductTitle" class="text-xs sm:text-sm font-extrabold uppercase truncate pr-2">Chi tiết sản phẩm</h3>
                <button type="button" onclick="closeProductModal()" class="w-7 h-7 rounded-full bg-white/15 hover:bg-white/25 flex items-center justify-center cursor-pointer">
                    <i class="fa-solid fa-xmark text-sm"></i>
                </button>
            </div>
            <div class="p-4 grid grid-cols-1 sm:grid-cols-12 gap-4 items-center">
                <div class="sm:col-span-6 h-64 sm:h-72 rounded-lg overflow-hidden border border-slate-200 bg-slate-50 relative">
                    <span id="modalSaleBadge" class="flatsome-sale-badge">-35%</span>
                    <img id="modalProductImg" src="" alt="Sản phẩm Nội Thất Nhựa Quân Phát" class="w-full h-full object-cover">
                </div>
                <div class="sm:col-span-6 space-y-2.5 text-xs">
                    <div id="modalProductCat" class="text-[11px] font-bold text-qp-primary uppercase"></div>
                    <div id="modalProductFullName" class="text-sm md:text-base font-extrabold text-slate-800 leading-snug"></div>
                    <div class="flex items-baseline gap-2 pt-1">
                        <span id="modalProductPrice" class="text-base md:text-lg font-extrabold text-qp-sale"></span>
                        <span id="modalProductOldPrice" class="text-xs text-slate-400 line-through"></span>
                    </div>
                    <div id="modalProductSpec" class="text-slate-600 leading-relaxed bg-slate-50 p-2.5 rounded-lg border border-slate-200"></div>
                    <div class="space-y-1 text-[11.5px] text-slate-700">
                        <div><i class="fa-solid fa-check text-emerald-600 mr-1.5"></i>Xưởng sản xuất: 40 Lê Hiến Mai, P. Hòa Khánh, Đà Nẵng</div>
                        <div><i class="fa-solid fa-check text-emerald-600 mr-1.5"></i>Nhận đóng theo kích thước & màu sắc yêu cầu</div>
                    </div>
                    <div class="pt-2 flex flex-wrap gap-2">
                        <a href="tel:0935437033" class="flex-1 text-center bg-qp-sale hover:bg-red-700 text-white font-extrabold py-2 px-3 rounded-md">
                            <i class="fa-solid fa-phone mr-1"></i>Gọi 0935 437 033
                        </a>
                        <a href="https://zalo.me/0935437033" target="_blank" rel="noopener noreferrer" class="flex-1 text-center bg-[#0068ff] hover:bg-blue-700 text-white font-extrabold py-2 px-3 rounded-md">
                            Chat Zalo Báo Giá
                        </a>
                    </div>
                </div>
            </div>
        </div>
    </div>

    <!-- ===================================================================== -->
    <!-- JAVASCRIPT: DỮ LIỆU 13 ẢNH THỰC TẾ GOOGLE DRIVE, FILTER & SLIDER      -->
    <!-- ===================================================================== -->
    <script>
        // Tự động chuyển đổi sang link dự phòng nếu ảnh Google Drive gặp giới hạn hiển thị
        function handleDriveImageError(imgEl) {
            const driveId = imgEl.getAttribute('data-drive-id');
            if (!driveId) return;
            const step = parseInt(imgEl.getAttribute('data-fallback-step') || '0', 10);
            if (step === 0) {
                imgEl.setAttribute('data-fallback-step', '1');
                imgEl.src = 'https://drive.google.com/thumbnail?id=' + driveId + '&sz=w1000';
            } else if (step === 1) {
                imgEl.setAttribute('data-fallback-step', '2');
                imgEl.src = 'https://drive.google.com/uc?export=view&id=' + driveId;
            }
        }

        // Danh sách đầy đủ 13 sản phẩm thực tế từ 13 file Google Drive, phân loại chuẩn xác theo danh mục
        const REAL_PRODUCTS = [
            {
                id: 1,
                driveId: '1Ca4i0-aZt_U98yfMk1xEBe2mBnuQwBx7',
                name: 'Tủ Quần Áo Nhựa Đài Loan 4 Cánh Mở Liền Kệ Góc Trang Trí Kịch Trần',
                category: 'dai-loan',
                categoryLabel: 'Nội Thất Nhựa Đài Loan',
                salePercent: '-33%',
                price: '3.950.000đ',
                oldPrice: '5.900.000đ',
                spec: 'Chất liệu nhựa Đài Loan 2 lớp bền đẹp, thiết kế 4 cánh mở kèm hộc kéo và kệ góc để túi xách tiện lợi.'
            },
            {
                id: 2,
                driveId: '1B5nPgMgfz8GhoOPdL6pNFOzxGuIZZ8Bx',
                name: 'Tủ Quần Áo Nhựa Chin Huei 2.0 Plus 4 Cánh Full Trần Vân Gỗ Phối Trắng',
                category: 'chin-huei',
                categoryLabel: 'Nội Thất Nhựa Chin Huei',
                salePercent: '-35%',
                price: '4.450.000đ',
                oldPrice: '6.850.000đ',
                spec: 'Nhựa Chin Huei chính hãng dày dặn, chống ẩm mốc 100%, bản lề giảm chấn inox 304 đóng mở êm ái.'
            },
            {
                id: 3,
                driveId: '1CVdxkRUQnqgmLjdNgoqk3jO8G7smMfy7',
                name: 'Tủ Áo Nhựa Cánh Lùa Cao Cấp Kịch Trần Tích Hợp Kệ Trang Trí Đa Năng',
                category: 'canh-lua',
                categoryLabel: 'Tủ Áo Cánh Lùa & Full Trần',
                salePercent: '-36%',
                price: '4.690.000đ',
                oldPrice: '7.300.000đ',
                spec: 'Hệ ray trượt cánh lùa hợp kim nhôm cao cấp tiết kiệm diện tích phòng ngủ, hộc tủ trên để chăn màn rộng rãi.'
            },
            {
                id: 4,
                driveId: '1iTekNNs2j4p4A-OZDmHlIOubDD0Zbt0Y',
                name: 'Tủ Quần Áo Nhựa Ecoplast 5 Cánh Mở Kịch Trần Cao Cấp Sang Trọng',
                category: 'ecoplast',
                categoryLabel: 'Nội Thất Nhựa Ecoplast',
                salePercent: '-32%',
                price: '5.490.000đ',
                oldPrice: '8.100.000đ',
                spec: 'Nhựa Ecoplast gân dày siêu cứng cáp, chia buồng treo đồ dài và ngăn gấp khoa học cho cả gia đình.'
            },
            {
                id: 5,
                driveId: '1THY2eR30wOb7KcQRSPM0k3VWh183fXs0',
                name: 'Tủ Quần Áo Nhựa Đài Loan 3 Cánh Mở Kèm Ngăn Kéo Tiện Lợi Giá Xưởng',
                category: 'dai-loan',
                categoryLabel: 'Nội Thất Nhựa Đài Loan',
                salePercent: '-38%',
                price: '2.550.000đ',
                oldPrice: '4.100.000đ',
                spec: 'Kích thước gọn gàng dễ bố trí, không cong vênh, không mối mọt, giao lắp tận nơi tại Đà Nẵng.'
            },
            {
                id: 6,
                driveId: '1g4y3vpyjK-YCBuJESf_38EN0FZLDZZJo',
                name: 'Tủ Áo Nhựa Chin Huei Kết Hợp Bàn Trang Điểm & Kệ Góc Hiện Đại',
                category: 'chin-huei',
                categoryLabel: 'Nội Thất Nhựa Chin Huei',
                salePercent: '-34%',
                price: '4.850.000đ',
                oldPrice: '7.350.000đ',
                spec: 'Thiết kế đồng bộ vừa làm tủ quần áo kịch trần vừa tích hợp bàn phấn trang điểm sang trọng.'
            },
            {
                id: 7,
                driveId: '1RmJlqi7GU1cSxZI9l1dLhgehw9YfhUkV',
                name: 'Tủ Bếp Nhựa Cao Cấp Ecoplast Chống Nước & Chống Mối Mọt Tuyệt Đối',
                category: 'tu-bep-giuong',
                categoryLabel: 'Tủ Bếp & Giường Ngủ Nhựa',
                salePercent: '-35%',
                price: '3.200.000đ',
                oldPrice: '4.900.000đ',
                spec: 'Thi công tủ bếp trên và tủ bếp dưới bằng nhựa Ecoplast siêu chịu lực, chống nước 100%, dễ vệ sinh.'
            },
            {
                id: 8,
                driveId: '1-_QwGpx_bZED-aYtkCo-YjEaP_JU8Fcb',
                name: 'Combo Phòng Ngủ Nhựa Ecoplast: Tủ Quần Áo Kịch Trần & Giường Ngủ Đồng Bộ',
                category: 'tu-bep-giuong',
                categoryLabel: 'Tủ Bếp & Giường Ngủ Nhựa',
                salePercent: '-37%',
                price: '7.850.000đ',
                oldPrice: '12.500.000đ',
                spec: 'Combo trọn gói phòng ngủ hiện đại đóng trực tiếp tại xưởng Quân Phát, tiết kiệm chi phí tối đa.'
            },
            {
                id: 9,
                driveId: '1htQJeM6eZVamMm28-7oher14e8NpJzpR',
                name: 'Tủ Quần Áo Nhựa Cánh Lùa 2 Buồng Lớn Phối Màu Vân Gỗ Óc Chó',
                category: 'canh-lua',
                categoryLabel: 'Tủ Áo Cánh Lùa & Full Trần',
                salePercent: '-33%',
                price: '3.890.000đ',
                oldPrice: '5.800.000đ',
                spec: 'Cánh lùa trượt nhẹ nhàng không tốn diện tích mở cửa, phù hợp phòng ngủ nhỏ và căn hộ.'
            },
            {
                id: 10,
                driveId: '1JxJl3ll15GHe7q98CfZ0Dq9aokE95DE0',
                name: 'Tủ Quần Áo Nhựa Trẻ Em & Ngăn Kéo Đa Năng Nhựa Đài Loan An Toàn',
                category: 'tre-em-ban',
                categoryLabel: 'Tủ Trẻ Em, Bàn Học, Tủ Giày',
                salePercent: '-39%',
                price: '1.850.000đ',
                oldPrice: '3.050.000đ',
                spec: 'Nhựa nguyên sinh không mùi, an toàn cho sức khỏe của bé, nhiều ngăn kéo phân loại đồ sơ sinh.'
            },
            {
                id: 11,
                driveId: '1Wznb_uJwitLeAostLt4mhNwilQLUVfUe',
                name: 'Bàn Học Sinh Nhựa Đài Loan Liền Giá Sách & Hộc Kéo Đôi Chống Nước',
                category: 'tre-em-ban',
                categoryLabel: 'Tủ Trẻ Em, Bàn Học, Tủ Giày',
                salePercent: '-36%',
                price: '1.650.000đ',
                oldPrice: '2.600.000đ',
                spec: 'Bàn học liền kệ sách chắc chắn, chiều cao chuẩn tư thế ngồi học, chống thấm nước và mực bút.'
            },
            {
                id: 12,
                driveId: '1zPWghpChEunub0adSmQtBorgkTIj9j_T',
                name: 'Bàn Trang Điểm Nhựa Cao Cấp Kèm Gương LED & Tủ Giày Thông Minh',
                category: 'tre-em-ban',
                categoryLabel: 'Tủ Trẻ Em, Bàn Học, Tủ Giày',
                salePercent: '-35%',
                price: '1.950.000đ',
                oldPrice: '3.000.000đ',
                spec: 'Thiết kế tinh tế hiện đại, nhiều ô để mỹ phẩm và phụ kiện gọn gàng, bề mặt nhựa bóng mịn.'
            },
            {
                id: 13,
                driveId: '1iY90E4eci9hSrctSVEMRSC6tw8OVz4sc',
                name: 'Giường Ngủ Nhựa Cao Cấp Ecoplast Có Hộc Kéo & Ốp Vách Đầu Giường Lam Sóng',
                category: 'tu-bep-giuong',
                categoryLabel: 'Tủ Bếp & Giường Ngủ Nhựa',
                salePercent: '-34%',
                price: '3.650.000đ',
                oldPrice: '5.550.000đ',
                spec: 'Hệ khung xương giường đan dày chịu lực cao, không kêu cọt kẹt, tích hợp ngăn kéo chứa đồ tiện lợi.'
            }
        ];

        // Tạo thẻ sản phẩm chuẩn Flatsome:
        // - Chỉ để duy nhất nhãn % giảm giá góc trên bên trái (.flatsome-sale-badge), không để nhãn dán phụ
        // - Tên sản phẩm hiển thị đầy đủ (.product-title-full), không bị cắt chữ hay tràn viền
        function createFlatsomeProductCard(product) {
            const imgUrl = 'https://lh3.googleusercontent.com/d/' + product.driveId;
            return `
                <div class="product-small-box group">
                    <div>
                        <div class="relative w-full aspect-square bg-slate-100 overflow-hidden cursor-pointer" onclick="openProductModal(${product.id})">
                            <span class="flatsome-sale-badge">${product.salePercent}</span>
                            <img src="${imgUrl}"
                                 data-drive-id="${product.driveId}"
                                 onerror="handleDriveImageError(this)"
                                 alt="${product.name}"
                                 loading="lazy"
                                 class="w-full h-full object-cover group-hover:scale-105 transition duration-300">
                        </div>
                        <div class="p-2.5 md:p-3">
                            <div class="text-[10px] font-semibold text-slate-400 uppercase mb-0.5 truncate">${product.categoryLabel}</div>
                            <h3 class="product-title-full cursor-pointer hover:text-qp-primary" onclick="openProductModal(${product.id})">
                                ${product.name}
                            </h3>
                        </div>
                    </div>
                    <div class="px-2.5 pb-2.5 md:px-3 md:pb-3 pt-1 border-t border-slate-100 flex flex-col gap-2">
                        <div class="flex flex-wrap items-baseline gap-x-2 gap-y-0.5">
                            <span class="text-xs sm:text-sm md:text-[15px] font-extrabold text-qp-sale">${product.price}</span>
                            <span class="text-[10.5px] md:text-xs text-slate-400 line-through">${product.oldPrice}</span>
                        </div>
                        <div class="grid grid-cols-2 gap-1.5">
                            <button type="button"
                                    onclick="openProductModal(${product.id})"
                                    class="w-full py-1.5 px-2 rounded bg-qp-light hover:bg-qp-primary text-qp-primary hover:text-white font-bold text-[10.5px] md:text-xs transition text-center cursor-pointer">
                                Chi Tiết
                            </button>
                            <a href="#form-bao-gia"
                               onclick="prefillQuoteProduct('${product.name.replace(/'/g, "\\'")}')"
                               class="w-full py-1.5 px-2 rounded bg-qp-primary hover:bg-qp-dark text-white font-bold text-[10.5px] md:text-xs transition text-center">
                                Báo Giá
                            </a>
                        </div>
                    </div>
                </div>
            `;
        }

        // Render danh sách sản phẩm ra các Section trang chủ
        function renderAllProductSections(list = REAL_PRODUCTS) {
            const mainGrid = document.getElementById('mainProductGrid');
            if (mainGrid) {
                if (list.length === 0) {
                    mainGrid.innerHTML = `
                        <div class="col-span-full bg-white rounded-lg p-6 text-center border border-slate-200">
                            <p class="text-xs md:text-sm font-bold text-slate-700">Không tìm thấy mẫu sản phẩm phù hợp với từ khóa.</p>
                            <button type="button" onclick="filterByCategory('all')" class="mt-2 bg-qp-primary text-white text-xs font-bold px-4 py-1.5 rounded cursor-pointer">
                                Xem tất cả 13 sản phẩm thực tế
                            </button>
                        </div>
                    `;
                } else {
                    mainGrid.innerHTML = list.map(createFlatsomeProductCard).join('');
                }
            }

            // Section 4: 8 mẫu Tủ quần áo tiêu biểu
            const wardrobeGrid = document.getElementById('wardrobeProductGrid');
            if (wardrobeGrid && wardrobeGrid.children.length === 0) {
                const wardrobes = REAL_PRODUCTS.filter(p => ['dai-loan', 'chin-huei', 'ecoplast', 'canh-lua'].includes(p.category)).slice(0, 8);
                wardrobeGrid.innerHTML = wardrobes.map(createFlatsomeProductCard).join('');
            }

            // Section 5: Tủ bếp, Giường ngủ, Bàn học, Tủ trẻ em
            const kitchenBedGrid = document.getElementById('kitchenBedProductGrid');
            if (kitchenBedGrid && kitchenBedGrid.children.length === 0) {
                const items = REAL_PRODUCTS.filter(p => ['tu-bep-giuong', 'tre-em-ban'].includes(p.category));
                const combined = [...items, REAL_PRODUCTS[2], REAL_PRODUCTS[5]].slice(0, 8);
                kitchenBedGrid.innerHTML = combined.map(createFlatsomeProductCard).join('');
            }
        }

        // Lọc sản phẩm theo danh mục
        function filterByCategory(catKey) {
            const titleEl = document.getElementById('currentCategoryTitle');
            const categoryNames = {
                'all': 'SẢN PHẨM THỰC TẾ THI CÔNG TẠI XƯỞNG QUÂN PHÁT (13 MẪU)',
                'dai-loan': 'NỘI THẤT NHỰA ĐÀI LOAN CAO CẤP',
                'chin-huei': 'NỘI THẤT NHỰA CHIN HUEI & CHIN HUEI 2.0 PLUS',
                'ecoplast': 'NỘI THẤT NHỰA CAO CẤP ECOPLAST & ECOSTAR',
                'canh-lua': 'TỦ QUẦN ÁO NHỰA CÁNH LÙA & TỦ KỊCH TRẦN',
                'tre-em-ban': 'TỦ NHỰA TRẺ EM, BÀN HỌC SINH & BÀN TRANG ĐIỂM',
                'tu-bep-giuong': 'TỦ BẾP NHỰA, GIƯỜNG NGỦ & COMBO PHÒNG NGỦ'
            };

            if (titleEl) {
                titleEl.textContent = categoryNames[catKey] || categoryNames['all'];
            }

            document.querySelectorAll('.cat-pill').forEach(btn => {
                const isMatch = btn.getAttribute('data-cat-btn') === catKey;
                if (isMatch) {
                    btn.className = 'cat-pill active-cat flex items-center gap-2 p-2 rounded-lg border border-qp-primary bg-qp-primary text-white text-left transition';
                } else {
                    btn.className = 'cat-pill flex items-center gap-2 p-2 rounded-lg border border-slate-200 bg-slate-50 hover:border-qp-primary text-slate-800 text-left transition';
                }
            });

            const filtered = catKey === 'all'
                ? REAL_PRODUCTS
                : REAL_PRODUCTS.filter(p => p.category === catKey);

            renderAllProductSections(filtered);
        }

        // Tìm kiếm sản phẩm
        function handleSearchProducts(keyword) {
            const q = (keyword || '').trim().toLowerCase();
            if (!q) {
                renderAllProductSections(REAL_PRODUCTS);
                return;
            }
            const matched = REAL_PRODUCTS.filter(p =>
                p.name.toLowerCase().includes(q) ||
                p.categoryLabel.toLowerCase().includes(q) ||
                p.spec.toLowerCase().includes(q)
            );
            renderAllProductSections(matched);
        }

        // Đóng / Mở menu danh mục trên điện thoại
        function toggleMobileMenu() {
            const overlay = document.getElementById('mobileMenuOverlay');
            const drawer = document.getElementById('mobileMenuDrawer');
            const isHidden = overlay.classList.contains('hidden');
            if (isHidden) {
                overlay.classList.remove('hidden');
                drawer.classList.remove('-translate-x-full');
            } else {
                overlay.classList.add('hidden');
                drawer.classList.add('-translate-x-full');
            }
        }

        // Điều khiển 2 Banner tự trượt kích thước bằng nhau
        let currentSlideIndex = 0;
        let slideInterval = null;

        function goToSlide(index) {
            const slides = document.querySelectorAll('.banner-slide');
            if (!slides.length) return;
            currentSlideIndex = (index + slides.length) % slides.length;

            slides.forEach((slide, idx) => {
                if (idx === currentSlideIndex) {
                    slide.classList.remove('hidden', 'opacity-0');
                    slide.classList.add('block', 'opacity-100');
                } else {
                    slide.classList.remove('block', 'opacity-100');
                    slide.classList.add('hidden', 'opacity-0');
                }
            });

            const dot0 = document.getElementById('slideDot0');
            const dot1 = document.getElementById('slideDot1');
            if (dot0 && dot1) {
                dot0.className = currentSlideIndex === 0
                    ? 'w-6 h-2 rounded-full bg-amber-400 transition-all'
                    : 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
                dot1.className = currentSlideIndex === 1
                    ? 'w-6 h-2 rounded-full bg-amber-400 transition-all'
                    : 'w-2.5 h-2 rounded-full bg-white/60 transition-all';
            }
        }

        function changeSlide(step) {
            goToSlide(currentSlideIndex + step);
            restartSlideTimer();
        }

        function restartSlideTimer() {
            if (slideInterval) clearInterval(slideInterval);
            slideInterval = setInterval(() => {
                goToSlide(currentSlideIndex + 1);
            }, 5000);
        }

        // Mở Modal chi tiết sản phẩm
        function openProductModal(productId) {
            const product = REAL_PRODUCTS.find(item => item.id === productId);
            if (!product) return;
            document.getElementById('modalProductTitle').textContent = product.categoryLabel;
            document.getElementById('modalProductCat').textContent = product.categoryLabel;
            document.getElementById('modalProductFullName').textContent = product.name;
            document.getElementById('modalProductPrice').textContent = product.price;
            document.getElementById('modalProductOldPrice').textContent = product.oldPrice;
            document.getElementById('modalProductSpec').textContent = product.spec;
            document.getElementById('modalSaleBadge').textContent = product.salePercent;

            const imgEl = document.getElementById('modalProductImg');
            imgEl.setAttribute('data-drive-id', product.driveId);
            imgEl.setAttribute('data-fallback-step', '0');
            imgEl.onerror = function () { handleDriveImageError(imgEl); };
            imgEl.src = 'https://lh3.googleusercontent.com/d/' + product.driveId;

            const modal = document.getElementById('productModal');
            modal.classList.remove('hidden');
            modal.classList.add('flex');
        }

        function closeProductModal() {
            const modal = document.getElementById('productModal');
            modal.classList.remove('flex');
            modal.classList.add('hidden');
        }

        // Tự động điền tên mẫu vào Form Báo Giá
        function prefillQuoteProduct(productName) {
            const noteInput = document.getElementById('qNote');
            if (noteInput) {
                noteInput.value = 'Tôi muốn tư vấn & nhận báo giá mẫu: ' + productName;
                noteInput.focus();
            }
        }

        // Xử lý gửi Form Báo Giá (Hiển thị thông báo trực tiếp, không dùng alert)
        function submitQuoteForm(e) {
            e.preventDefault();
            const name = document.getElementById('qName').value.trim();
            const phone = document.getElementById('qPhone').value.trim();
            const category = document.getElementById('qCategory').value;
            const address = document.getElementById('qAddress').value.trim() || 'Đà Nẵng';
            const box = document.getElementById('quoteSuccessBox');

            box.innerHTML = `<i class="fa-solid fa-circle-check mr-1.5"></i>Cảm ơn <strong>${name}</strong> (${phone})! Yêu cầu báo giá <strong>${category}</strong> tại <strong>${address}</strong> đã được gửi thành công. Kỹ thuật viên Nội Thất Nhựa Quân Phát sẽ liên hệ ngay qua số <strong>0935 437 033 – 0376 758 097</strong>.`;
            box.classList.remove('hidden');
            document.getElementById('quoteRequestForm').reset();
        }

        // Khởi tạo giao diện khi tải trang
        window.addEventListener('DOMContentLoaded', function () {
            renderAllProductSections(REAL_PRODUCTS);
            restartSlideTimer();
        });
    </script>
</body>
</html>
