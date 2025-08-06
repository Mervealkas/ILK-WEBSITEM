ilk web sitem kodları ve html dosyasını paylaşıyorum.
<!DOCTYPE html>
<html lang="tr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Merve Nur Alkaş - Kişisel Web Sayfası</title>
    <style>
        /* Genel Stil Ayarları */
        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            margin: 0;
            padding: 0;
            background-color: #f4f4f9;
            color: #333;
        }

        /* Navigasyon Menüsü */
        nav {
            background: #007acc;
            color: #fff;
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 15px 30px;
        }

        nav a {
            color: #fff;
            text-decoration: none;
            margin-left: 20px;
        }

        nav a:hover {
            text-decoration: underline;
        }

        /* Başlık Bölümü */
        .hero {
            text-align: center;
            background: linear-gradient(to right, #007acc, #00bcd4);
            color: #fff;
            padding: 50px 20px;
        }

        .hero img {
            width: 150px;
            height: 150px;
            border-radius: 50%;
            margin-bottom: 20px;
            border: 5px solid #fff;
        }

        .hero h1 {
            font-size: 3rem;
        }

        .hero p {
            font-size: 1.5rem;
            margin-top: 10px;
        }

        /* Ana İçerik */
        .container {
            max-width: 1100px;
            margin: 20px auto;
            padding: 20px;
            background: #fff;
            border-radius: 10px;
            box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
        }

        section {
            margin-bottom: 30px;
        }

        h2 {
            color: #007acc;
            border-bottom: 2px solid #007acc;
            padding-bottom: 5px;
        }

        ul {
            list-style: none;
            padding: 0;
        }

        ul li {
            margin-bottom: 10px;
        }

        .skills span {
            display: inline-block;
            margin: 5px;
            padding: 8px 12px;
            background-color: #e0f7fa;
            color: #00796b;
            border-radius: 20px;
            font-size: 14px;
        }

        /* Alt Bilgi */
        footer {
            text-align: center;
            padding: 15px;
            background: #007acc;
            color: #fff;
        }

        footer a {
            color: #fff;
            text-decoration: none;
        }

        footer a:hover {
            text-decoration: underline;
        }
    </style>
</head>
<body>
    <!-- Navigasyon Menüsü -->
    <nav>
        <div><strong>Merve Nur Alkaş</strong></div>
        <div>
            <a href="#about">Hakkımda</a>
            <a href="#skills">Beceriler</a>
            <a href="#projects">Projeler</a>
            <a href="#contact">İletişim</a>
        </div>
    </nav>

    <!-- Başlık Bölümü -->
    <header class="hero">
        <img src="https://via.placeholder.com/150" alt="Merve Nur Alkaş">
        <h1>Merve Nur Alkaş</h1>
        <p>Yazılım Geliştirici | Yönetim Bilişim Sistemleri Öğrencisi</p>
    </header>

    <!-- Ana İçerik -->
    <div class="container">
        <!-- Hakkımda Bölümü -->
        <section id="about">
            <h2>Hakkımda</h2>
            <p>
                2002 doğumluyum ve İstanbul Esenyurt Üniversitesi Yönetim Bilişim Sistemleri bölümünde tam burslu olarak son sınıf öğrencisiyim. 
                Yazılım geliştirme, algoritmalar, veri analitiği ve makine öğrenimi gibi alanlara ilgi duyuyorum. 
                Projelerimde yenilikçi teknolojiler kullanarak etkili çözümler üretmeye odaklanıyorum.
            </p>
        </section>

        <!-- Beceriler Bölümü -->
        <section id="skills">
            <h2>Beceriler</h2>
            <div class="skills">
                <span>Office Programları</span>
                <span>Visual Studio</span>
                <span>Python</span>
                <span>C++</span>
                <span>SQL</span>
                <span>Excel VBA</span>
                <span>R</span>
                <span>HTML/CSS</span>
                <span>Ekip Liderliği</span>
            </div>
        </section>

        <!-- Projeler Bölümü -->
        <section id="projects">
            <h2>Projeler</h2>
            <ul>
                <li><strong>TÜBİTAK Mobil Uygulama - MATADOR:</strong> Yenilikçi bir mobil uygulama geliştirme projesi.</li>
                <li><strong>Siber Güvenliğin Süper Kadınları:</strong> Turkcell sponsorluğunda bir siber güvenlik projesi.</li>
            </ul>
        </section>

        <!-- İletişim Bölümü -->
        <section id="contact">
            <h2>İletişim</h2>
            <ul>
                <li><strong>Telefon:</strong> 0552 241 9321</li>
                <li><strong>Email:</strong> <a href="mailto:alkasmervenur@gmail.com">alkasmervenur@gmail.com</a></li>
                <li><strong>Adres:</strong> Zafer Mahallesi, Esenyurt/İstanbul</li>
            </ul>
        </section>
    </div>

    <!-- Alt Bilgi -->
    <footer>
        <p>Bu kişisel web sayfası, HTML ve CSS kullanılarak oluşturulmuştur.</p>
    </footer>
</body>
</html>

