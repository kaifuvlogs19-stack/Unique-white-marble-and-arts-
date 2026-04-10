<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta name="description" content="Unique White Marble & Arts - Premium Handcrafted Marble Fountains & Home Temples">
    <title>Unique White Marble & Arts | Premium Handicrafts</title>
    
    <!-- Fonts -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@400;500;600;700&family=Poppins:wght@300;400;500;600&display=swap" rel="stylesheet">
    
    <!-- Icons & Animations -->
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
    <link href="https://unpkg.com/aos@2.3.1/dist/aos.css" rel="stylesheet">

    <style>
        /* ========================================
           PREMIUM LUXURY STYLESHEET
           Unique White Marble & Arts
        ======================================== */
        :root {
            --primary-gold: #D4AF37;
            --gold-light: #F4E4C1;
            --gold-dark: #B8941E;
            --dark-bg: #0A0A0A;
            --dark-secondary: #1A1A1A;
            --dark-tertiary: #2A2A2A;
            --white: #FFFFFF;
            --text-light: #CCCCCC;
            --text-gray: #999999;
            --font-heading: 'Playfair Display', serif;
            --font-body: 'Poppins', sans-serif;
            --transition: all 0.4s cubic-bezier(0.4, 0, 0.2, 1);
            --shadow-gold: 0 4px 20px rgba(212, 175, 55, 0.3);
        }

        * { margin: 0; padding: 0; box-sizing: border-box; }
        html { scroll-behavior: smooth; }
        body { font-family: var(--font-body); background: var(--dark-bg); color: var(--white); line-height: 1.6; overflow-x: hidden; }
        .container { max-width: 1400px; margin: 0 auto; padding: 0 20px; }
        h1,h2,h3,h4,h5,h6 { font-family: var(--font-heading); font-weight: 600; line-height: 1.2; }
        img { max-width: 100%; height: auto; display: block; }

        /* ========== NAVIGATION ========== */
        .navbar { position: fixed; top: 0; left: 0; width: 100%; background: rgba(10,10,10,0.95); backdrop-filter: blur(10px); padding: 20px 0; z-index: 1000; transition: var(--transition); border-bottom: 1px solid rgba(212,175,55,0.1); }
        .navbar.scrolled { padding: 15px 0; box-shadow: var(--shadow-gold); background: rgba(10,10,10,0.98); }
        .nav-container { max-width: 1400px; margin: 0 auto; padding: 0 20px; display: flex; justify-content: space-between; align-items: center; }
        .nav-logo h1 { font-size: 1.5rem; background: linear-gradient(135deg, var(--primary-gold), var(--gold-light)); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; letter-spacing: 1px; }
        .nav-menu { display: flex; list-style: none; gap: 40px; align-items: center; }
        .nav-link { color: var(--white); text-decoration: none; font-weight: 500; font-size: 0.95rem; position: relative; padding: 5px 0; transition: var(--transition); }
        .nav-link::after { content: ''; position: absolute; bottom: 0; left: 0; width: 0; height: 2px; background: var(--primary-gold); transition: var(--transition); }
        .nav-link:hover { color: var(--primary-gold); }
        .nav-link:hover::after { width: 100%; }
        .hamburger { display: none; flex-direction: column; cursor: pointer; gap: 5px; }
        .hamburger span { width: 28px; height: 3px; background: var(--primary-gold); transition: var(--transition); border-radius: 2px; }
        .hamburger.active span:nth-child(1) { transform: rotate(45deg) translate(8px, 8px); }
        .hamburger.active span:nth-child(2) { opacity: 0; }
        .hamburger.active span:nth-child(3) { transform: rotate(-45deg) translate(8px, -8px); }

        /* ========== HERO SECTION ========== */
        .hero { position: relative; height: 100vh; display: flex; align-items: center; justify-content: center; overflow: hidden; }
        .hero-video-container { position: absolute; top: 0; left: 0; width: 100%; height: 100%; overflow: hidden; }
        .hero-video { width: 100%; height: 100%; object-fit: cover; object-position: center; }
        .hero-overlay { position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: linear-gradient(135deg, rgba(10,10,10,0.85), rgba(26,26,26,0.6)); }
        .hero-content { position: relative; z-index: 2; text-align: center; max-width: 900px; padding: 0 20px; }
        .hero-title { font-size: 4.5rem; margin-bottom: 20px; background: linear-gradient(135deg, var(--white), var(--gold-light)); -webkit-background-clip: text; -webkit-text-fill-color: transparent; background-clip: text; }
        .hero-subtitle { font-size: 1.4rem; color: var(--text-light); margin-bottom: 40px; font-weight: 300; letter-spacing: 1px; }
        .hero-buttons { display: flex; gap: 20px; justify-content: center; flex-wrap: wrap; }
        .scroll-indicator { position: absolute; bottom: 40px; left: 50%; transform: translateX(-50%); z-index: 3; }
        .mouse { width: 30px; height: 50px; border: 2px solid var(--primary-gold); border-radius: 20px; position: relative; }
        .mouse::before { content: ''; width: 4px; height: 10px; background: var(--primary-gold); position: absolute; top: 10px; left: 50%; transform: translateX(-50%); border-radius: 2px; animation: scroll 2s infinite; }
        @keyframes scroll { 0% { top: 10px; opacity: 1; } 100% { top: 30px; opacity: 0; } }

        /* ========== BUTTONS ========== */
        .btn { display: inline-block; padding: 15px 40px; font-weight: 600; text-decoration: none; border-radius: 50px; transition: var(--transition); border: 2px solid transparent; cursor: pointer; font-size: 1rem; text-align: center; }
        .btn-primary { background: linear-gradient(135deg, var(--primary-gold), var(--gold-dark)); color: var(--dark-bg); box-shadow: var(--shadow-gold); }
        .btn-primary:hover { transform: translateY(-3px); box-shadow: 0 8px 30px rgba(212, 175, 55, 0.5); }
        .btn-secondary { background: transparent; border: 2px solid var(--primary-gold); color: var(--primary-gold); }
        .btn-secondary:hover { background: var(--primary-gold); color: var(--dark-bg); transform: translateY(-3px); }
        .btn-whatsapp { background: #25D366; color: white; padding: 12px 25px; border: none; }
        .btn-whatsapp:hover { background: #1EBE57; transform: translateY(-2px); }
        .btn-outline { background: transparent; border: 2px solid var(--primary-gold); color: var(--primary-gold); padding: 12px 35px; }
        .btn-outline:hover { background: var(--primary-gold); color: var(--dark-bg); }

        /* ========== SECTIONS COMMON ========== */
        section { padding: 120px 0; }
        .section-header { text-align: center; margin-bottom: 60px; }
        .section-subtitle { color: var(--primary-gold); font-size: 0.95rem; letter-spacing: 3px; text-transform: uppercase; font-weight: 600; display: block; margin-bottom: 15px; }
        .section-title { font-size: 3rem; color: var(--white); margin-bottom: 20px; }
        .title-divider { width: 80px; height: 3px; background: linear-gradient(90deg, transparent, var(--primary-gold), transparent); margin: 20px auto; }
        .section-description { font-size: 1.1rem; color: var(--text-light); max-width: 700px; margin: 0 auto; }

        /* ========== ABOUT SECTION ========== */
        .about { background: var(--dark-secondary); }
        .about-grid { display: grid; grid-template-columns: 1fr 1fr; gap: 60px; align-items: center; }
        .about-image { position: relative; border-radius: 20px; overflow: hidden; box-shadow: 0 8px 32px rgba(0,0,0,0.3); }
        .about-image img { width: 100%; height: 600px; object-fit: cover; transition: var(--transition); }
        .about-image:hover img { transform: scale(1.05); }
        .about-image-overlay { position: absolute; bottom: 0; left: 0; width: 100%; padding: 40px; background: linear-gradient(to top, rgba(0,0,0,0.9), transparent); }
        .about-stats { display: flex; gap: 40px; }
        .stat-item h3 { font-size: 2.5rem; color: var(--primary-gold); margin-bottom: 5px; }
        .stat-item p { color: var(--white); font-size: 0.9rem; }
        .about-text { padding: 20px 0; }
        .about-description { color: var(--text-light); margin-bottom: 20px; font-size: 1.05rem; line-height: 1.8; }
        .about-features { margin: 40px 0; }
        .feature-item { display: flex; align-items: flex-start; gap: 20px; margin-bottom: 25px; }
        .feature-item i { font-size: 2rem; color: var(--primary-gold); min-width: 50px; }
        .feature-item h4 { color: var(--white); margin-bottom: 5px; font-size: 1.2rem; }
        .feature-item p { color: var(--text-gray); font-size: 0.95rem; }

        /* ========== PRODUCTS (Fountains & Mandirs) ========== */
        .fountains-section { background: var(--dark-bg); }
        .mandirs-section { background: var(--dark-secondary); }
        .products-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(380px, 1fr)); gap: 40px; margin-bottom: 60px; }
        .product-card { background: var(--dark-tertiary); border-radius: 20px; overflow: hidden; transition: var(--transition); border: 1px solid rgba(212,175,55,0.1); }
        .product-card:hover { transform: translateY(-10px); box-shadow: 0 15px 40px rgba(212, 175, 55, 0.2); border-color: var(--primary-gold); }
        .product-image-container { position: relative; overflow: hidden; height: 400px; }
        .product-image { width: 100%; height: 100%; object-fit: cover; transition: var(--transition); }
        .product-card:hover .product-image { transform: scale(1.1); }
        .product-badge { position: absolute; top: 20px; right: 20px; background: var(--primary-gold); color: var(--dark-bg); padding: 8px 20px; border-radius: 30px; font-weight: 600; font-size: 0.85rem; text-transform: uppercase; letter-spacing: 1px; z-index: 2; }
        .product-overlay { position: absolute; top: 0; left: 0; width: 100%; height: 100%; background: rgba(0,0,0,0.7); display: flex; align-items: center; justify-content: center; opacity: 0; transition: var(--transition); }
        .product-card:hover .product-overlay { opacity: 1; }
        .quick-view-btn { background: var(--primary-gold); color: var(--dark-bg); border: none; padding: 15px 30px; border-radius: 50px; font-weight: 600; cursor: pointer; transform: translateY(20px); transition: var(--transition); }
        .product-card:hover .quick-view-btn { transform: translateY(0); }
        .product-info { padding: 30px; }
        .product-title { font-size: 1.5rem; color: var(--white); margin-bottom: 12px; }
        .product-description { color: var(--text-light); margin-bottom: 20px; font-size: 0.95rem; line-height: 1.6; }
        .product-features { display: flex; gap: 15px; margin-bottom: 25px; flex-wrap: wrap; }
        .product-features span { background: rgba(212,175,55,0.1); color: var(--primary-gold); padding: 8px 15px; border-radius: 20px; font-size: 0.85rem; border: 1px solid rgba(212,175,55,0.2); }
        .product-features i { margin-right: 5px; }
        .product-actions { display: flex; gap: 12px; }
        .product-actions .btn { flex: 1; padding: 12px 20px; font-size: 0.9rem; }
        .section-cta { text-align: center; margin-top: 40px; }

        /* ========== WHY CHOOSE US ========== */
        .why-choose { background: var(--dark-bg); }
        .why-grid { display: grid; grid-template-columns: repeat(auto-fit, minmax(280px, 1fr)); gap: 40px; }
        .why-card { background: var(--dark-tertiary); padding: 40px 30px; border-radius: 20px; text-align: center; transition: var(--transition); border: 1px solid rgba(212,175,55,0.1); }
        .why-card:hover { transform: translateY(-10px); border-color: var(--primary-gold); box-shadow: var(--shadow-gold); }
        .why-icon { width: 80px; height: 80px; background: linear-gradient(135deg, var(--primary-gold), var(--gold-dark)); border-radius: 50%; display: flex; align-items: center; justify-content: center; margin: 0 auto 25px; transition: var(--transition); }
        .why-card:hover .why-icon { transform: rotateY(360deg); }
        .why-icon i { font-size: 2rem; color: var(--dark-bg); }
        .why-card h3 { color: var(--white); margin-bottom: 15px; font-size: 1.3rem; }
        .why-card p { color: var(--text-light); font-size: 0.95rem; }

        /* ========== CONTACT SECTION ========== */
        .contact { background: var(--dark-secondary); }
        .contact-grid { display: grid; grid-template-columns: 1fr 1.2fr; gap: 60px; align-items: start; }
        .contact-info h3 { font-size: 2rem; color: var(--white); margin-bottom: 30px; }
        .contact-item { display: flex; gap: 20px; margin-bottom: 30px; align-items: flex-start; }
        .contact-item i { font-size: 1.5rem; color: var(--primary-gold); min-width: 40px; }
        .contact-item h4 { color: var(--white); margin-bottom: 5px; font-size: 1.1rem; }
        .contact-item p { color: var(--text-light); }
        .social-links { display: flex; gap: 15px; margin-top: 40px; }
        .social-link { width: 50px; height: 50px; background: rgba(212,175,55,0.1); border: 2px solid var(--primary-gold); border-radius: 50%; display: flex; align-items: center; justify-content: center; color: var(--primary-gold); font-size: 1.2rem; transition: var(--transition); text-decoration: none; }
        .social-link:hover { background: var(--primary-gold); color: var(--dark-bg); transform: translateY(-5px); }
        .contact-form { background: var(--dark-tertiary); padding: 40px; border-radius: 20px; border: 1px solid rgba(212,175,55,0.1); }
        .form-group { margin-bottom: 25px; }
        .form-group input, .form-group textarea, .form-group select { width: 100%; padding: 15px 20px; background: var(--dark-secondary); border: 2px solid rgba(212,175,55,0.2); border-radius: 10px; color: var(--white); font-family: var(--font-body); font-size: 1rem; transition: var(--transition); }
        .form-group input:focus, .form-group textarea:focus, .form-group select:focus { outline: none; border-color: var(--primary-gold); box-shadow: 0 0 20px rgba(212,175,55,0.2); }
        .form-group textarea { resize: vertical; }
        .form-group input::placeholder, .form-group textarea::placeholder { color: var(--text-gray); }

        /* ========== FOOTER ========== */
        .footer { background: var(--dark-bg); padding: 80px 0 30px; border-top: 1px solid rgba(212,175,55,0.1); }
        .footer-grid { display: grid; grid-template-columns: 2fr 1fr 1fr 1.5fr; gap: 40px; margin-bottom: 50px; }
        .footer-col h3 { color: var(--primary-gold); margin-bottom: 20px; font-size: 1.5rem; }
        .footer-col h4 { color: var(--white); margin-bottom: 20px; font-size: 1.2rem; }
        .footer-col p { color: var(--text-light); line-height: 1.8; margin-bottom: 20px; }
        .footer-col ul { list-style: none; }
        .footer-col ul li { margin-bottom: 12px; }
        .footer-col ul li a { color: var(--text-light); text-decoration: none; transition: var(--transition); display: inline-block; }
        .footer-col ul li a:hover { color: var(--primary-gold); transform: translateX(5px); }
        .footer-col ul li i { margin-right: 10px; color: var(--primary-gold); }
        .footer-social { display: flex; gap: 15px; margin-top: 20px; }
        .footer-social a { width: 45px; height: 45px; background: rgba(212,175,55,0.1); border: 2px solid var(--primary-gold); border-radius: 50%; display: flex; align-items: center; justify-content: center; color: var(--primary-gold); font-size: 1.1rem; transition: var(--transition); text-decoration: none; }
        .footer-social a:hover { background: var(--primary-gold); color: var(--dark-bg); transform: translateY(-3px); }
        .footer-bottom { text-align: center; padding-top: 30px; border-top: 1px solid rgba(212,175,55,0.1); }
        .footer-bottom p { color: var(--text-gray); margin: 5px 0; }

        /* ========== FLOATING ELEMENTS ========== */
        .whatsapp-float { position: fixed; bottom: 30px; right: 30px; width: 60px; height: 60px; background: #25D366; border-radius: 50%; display: flex; align-items: center; justify-content: center; color: white; font-size: 2rem; box-shadow: 0 4px 20px rgba(37,211,102,0.4); z-index: 999; transition: var(--transition); animation: pulse 2s infinite; text-decoration: none; }
        .whatsapp-float:hover { transform: scale(1.1); box-shadow: 0 6px 30px rgba(37,211,102,0.6); }
        @keyframes pulse { 0% { box-shadow: 0 4px 20px rgba(37,211,102,0.4); } 50% { box-shadow: 0 4px 30px rgba(37,211,102,0.7); } 100% { box-shadow: 0 4px 20px rgba(37,211,102,0.4); } }
        .scroll-top { position: fixed; bottom: 30px; left: 30px; width: 50px; height: 50px; background: var(--primary-gold); border: none; border-radius: 50%; color: var(--dark-bg); font-size: 1.2rem; cursor: pointer; opacity: 0; visibility: hidden; transition: var(--transition); z-index: 999; }
        .scroll-top.active { opacity: 1; visibility: visible; }
        .scroll-top:hover { transform: translateY(-5px); box-shadow: var(--shadow-gold); }

        /* ========== RESPONSIVE ========== */
        @media (max-width: 1200px) { .hero-title { font-size: 3.5rem; } .section-title { font-size: 2.5rem; } }
        @media (max-width: 992px) {
            .nav-menu { position: fixed; top: 80px; right: -100%; width: 300px; height: calc(100vh - 80px); background: rgba(10,10,10,0.98); flex-direction: column; padding: 40px 20px; gap: 20px; transition: var(--transition); border-left: 1px solid rgba(212,175,55,0.2); box-shadow: -5px 0 30px rgba(0,0,0,0.5); }
            .nav-menu.active { right: 0; }
            .hamburger { display: flex; }
            .about-grid, .contact-grid { grid-template-columns: 1fr; gap: 40px; }
            .footer-grid { grid-template-columns: 1fr 1fr; }
            .hero-title { font-size: 3rem; }
            .products-grid { grid-template-columns: repeat(auto-fit, minmax(300px, 1fr)); }
        }
        @media (max-width: 768px) {
            .hero-title { font-size: 2.5rem; } .hero-subtitle { font-size: 1.1rem; }
            .hero-buttons { flex-direction: column; width: 100%; } .hero-buttons .btn { width: 100%; }
            .section-title { font-size: 2rem; } .products-grid, .why-grid { grid-template-columns: 1fr; }
            .footer-grid { grid-template-columns: 1fr; } .about-image img { height: 400px; }
            .whatsapp-float { width: 55px; height: 55px; font-size: 1.8rem; bottom: 20px; right: 20px; }
            .scroll-top { bottom: 90px; left: 20px; }
        }
        @media (max-width: 480px) { .nav-logo h1 { font-size: 1.1rem; } .hero-title { font-size: 2rem; } .section-title { font-size: 1.7rem; } .product-image-container { height: 300px; } .contact-form { padding: 25px; } }
    </style>
</head>
<body>

    <!-- ========== NAVIGATION ========== -->
    <nav class="navbar" id="navbar">
        <div class="nav-container">
            <div class="nav-logo"><h1>Unique White Marble & Arts</h1></div>
            <ul class="nav-menu" id="navMenu">
                <li><a href="#home" class="nav-link">Home</a></li>
                <li><a href="#about" class="nav-link">About Us</a></li>
                <li><a href="#fountains" class="nav-link">Fountains</a></li>
                <li><a href="#mandirs" class="nav-link">Home Temples</a></li>
                <li><a href="#contact" class="nav-link">Contact</a></li>
            </ul>
            <div class="hamburger" id="hamburger">
                <span></span><span></span><span></span>
            </div>
        </div>
    </nav>

    <!-- ========== HERO SECTION ========== -->
    <section class="hero" id="home">
        <div class="hero-video-container">
            <!-- REPLACE: hero-video.mp4 with your actual video file -->
            <video autop
