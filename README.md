<head>
    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <title>Финам - Эксклюзивные инвестиционные решения</title>
    
    <!-- Подключение шрифтов -->
    <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600&family=Oswald:wght@400;500;600&display=swap" rel="stylesheet">
    
    <style>
        /* Сброс стилей */
        * {
            box-sizing: border-box;
            margin: 0;
            padding: 0;
        }
        
        body {
            font-family: 'Inter', sans-serif;
            background-color: #ffffff;
            color: #000000;
            line-height: 1.6;
        }
        
        .new-font {
            font-family: 'Oswald', sans-serif;
        }
        
        /* Основные секции */
        .content-section {
            width: 100%;
            padding: 0;
            position: relative;
        }
        
        .content-container {
            max-width: 1268px;
            margin: 0 auto;
            padding: 0 20px;
        }
        
        /* Первая секция с видео */
        .video-section {
            background: #000000;
            position: relative;
            height: 20vh;
            min-height: 600px;
            display: flex;
            align-items: center;
            justify-content: center;
            overflow: hidden;
        }
        
        .video-background {
            width: 100%;
            height: 100%;
            object-fit: cover;
            position: absolute;
            top: 0;
            left: 0;
            z-index: 0;
        }
        
        .logo-overlay {
            position: absolute;
            top: 24px;
            left: 50%;
            transform: translateX(-50%);
            width: 160px;
            height: 160px;
            background-image: url('https://cdn-lpbr01.finam.ru/lpbr-static/Source_Vertical_RU_32723b0a41.svg');
            background-repeat: no-repeat;
            background-position: center center;
            background-size: contain;
            z-index: 1;
        }
        
        /* Вторая секция с продуктами */
        .products-section {
            background-color: #ffffff;
            border-radius: 32px 32px 0 0;
            margin-top: -32px;
            position: relative;
            z-index: 2;
            padding: 32px 0 64px 0;
        }
        
        .section-title {
            font-size: 48px;
            font-weight: 500;
            margin-bottom: 48px;
        }
        
        .accent-red {
            color: #d33e39;
        }
        
        /* Карточки продуктов */
        .card-container {
            background-color: #f8f8fb;
            border-radius: 16px;
            padding: 24px;
            margin-bottom: 16px;
            display: flex;
            flex-wrap: wrap;
            justify-content: space-between;
            align-items: center;
        }
        
        .card-left {
            flex: 1;
            min-width: 250px;
            margin-right: 16px;
        }
        
        .card-right {
            flex: 1;
            min-width: 250px;
            text-align: right;
        }
        
        .card-title {
            font-size: 32px;
            font-weight: 500;
            margin-bottom: 8px;
            color: #000000;
        }
        
        .card-description {
            font-size: 18px;
            color: #666666;
            line-height: 1.4;
        }
        
        .card-yield {
            font-size: 32px;
            font-weight: 500;
            color: #d33e39;
            line-height: 1.2;
        }
        
        /* Третья секция */
        .final-section {
            text-align: center;
            padding: 64px 0;
            background-color: #ffffff;
        }
        
        .final-logo {
            width: 200px;
            height: auto;
            margin-bottom: 24px;
        }
        
        .final-text {
            font-size: 24px;
            color: #000000;
            max-width: 600px;


margin: 0 auto;
            line-height: 1.4;
        }
        
        /* Дисклеймер */
        .disclaimer {
            text-align: center;
            font-size: 18px;
            color: #acafb8;
            margin-top: 32px;
            padding-top: 24px;
            border-top: 1px solid #eeeeee;
        }
        
        /* Адаптивность */
        @media (max-width: 768px) {
            .video-section {
                height: 70vh;
                min-height: 400px;
            }
            
            .logo-overlay {
                width: 120px;
                height: 120px;
                top: 16px;
            }
            
            .products-section {
                margin-top: -24px;
                border-radius: 24px 24px 0 0;
                padding: 24px 0 48px 0;
            }
            
            .section-title {
                font-size: 36px;
                margin-bottom: 32px;
            }
            
            .card-container {
                flex-direction: column;
                text-align: center;
                padding: 20px;
            }
            
            .card-left,
            .card-right {
                width: 100%;
                text-align: center;
                margin: 10px 0;
            }
            
            .card-title {
                font-size: 28px;
            }
            
            .card-yield {
                font-size: 28px;
            }
            
            .final-text {
                font-size: 20px;
                padding: 0 20px;
            }
        }
        
        @media (max-width: 480px) {
            .section-title {
                font-size: 28px;
            }
            
            .card-title {
                font-size: 24px;
            }
            
            .card-description {
                font-size: 16px;
            }
            
            .card-yield {
                font-size: 24px;
            }
            
            .final-text {
                font-size: 18px;
            }
        }
    </style>
</head>
<body>
    <!-- Секция с видео -->
    <section class="content-section video-section">
        <div class="logo-overlay"></div>
        <video class="video-background" autoplay loop muted playsinline>
            <source src="https://cloud.mail.ru/public/Gvq6/21W61YXV7" type="video/mp4">
            Ваш браузер не поддерживает видео.
        </video>
    </section>

    <!-- Секция с продуктами -->
    <section class="content-section products-section">
        <div class="content-container">
            <h1 class="section-title new-font">
                <span class="accent-red">Эксклюзивы</span> — ваш проводник к уникальным инвестиционным решениям с высоким потенциалом, недоступным на открытом рынке
            </h1>
            
            <!-- Карточка 1: PRE-IPO -->
            <div class="card-container">
                <div class="card-left">
                    <h2 class="card-title new-font accent-red">PRE-IPO</h2>
                    <p class="card-description">Circle, Kraken, Anthropic</p>
                </div>
                <div class="card-right">
                    <p class="card-description">
                        С доходностью ($)<br>
                        <span class="card-yield new-font">до 597%*<br>за все время работы</span>
                    </p>
                </div>
            </div>
            
            <!-- Карточка 2: ФОНД АРБИТРАЖ -->
            <div class="card-container">
                <div class="card-left">
                    <h2 class="card-title new-font accent-red">ФОНД АРБИТРАЖ</h2>
                </div>
                <div class="card-right">
                    <p class="card-description">
                        С доходностью (₽)<br>
                        <span class="card-yield new-font">до 30%* годовых</span>
                    </p>
                </div>
            </div>
            
            <!-- Карточка 3: ИМПУЛЬС ЮАНЯ -->


<div class="card-container">
                <div class="card-left">
                    <h2 class="card-title new-font accent-red">ИМПУЛЬС ЮАНЯ</h2>
                </div>
                <div class="card-right">
                    <p class="card-description">
                        С купонной доходностью ($)<br>
                        <span class="card-yield new-font">до 15,7%* годовых</span>
                    </p>
                </div>
            </div>
            
            <p class="disclaimer">*При реализации оптимистичного сценария</p>
        </div>
    </section>

    <!-- Финальная секция -->
    <section class="content-section final-section">
        <div class="content-container">
            <img src="https://cloud.mail.ru/public/ZuWe/ttCvkpWfa" alt="Финам" class="final-logo">
            <p class="final-text">
                Удобный маркетплейс, венчурные новости и свежие идеи — ждут именно вас!
            </p>
        </div>
    </section>

    <script>
        // Скрипт для адаптивного видео
        document.addEventListener('DOMContentLoaded', function() {
            const video = document.querySelector('.video-background');
            
            // Настройка видео для мобильных устройств
            if (/Android|webOS|iPhone|iPad|iPod|BlackBerry|IEMobile|Opera Mini/i.test(navigator.userAgent)) {
                video.setAttribute('playsinline', '');
                video.setAttribute('muted', '');
                video.setAttribute('autoplay', '');
            }
            
            // Автозапуск видео
            video.play().catch(function(error) {
                console.log("Автозапуск видео заблокирован браузером");
            });
        });
    </script>
</body>
