<!DOCTYPE html>
<html lang="ru">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Biography</title>
    <style>
        * { margin: 0; padding: 0; box-sizing: border-box; }
        body { background: #000; color: #fff; font-family: Arial; min-height: 100vh; overflow-x: hidden; }
        
        @keyframes glow {
            0%, 100% { text-shadow: 0 0 5px #fff, 0 0 10px #fff, 0 0 15px #00b3ff, 0 0 20px #00b3ff; }
            50% { text-shadow: 0 0 10px #fff, 0 0 20px #fff, 0 0 30px #00b3ff, 0 0 40px #00b3ff; }
        }
        .glowing-text { animation: glow 2s ease-in-out infinite; font-weight: bold; }

        .top-nav { background: #000; padding: 1.2rem 0; border-bottom: 2px solid #333; position: fixed; top: 0; width: 100%; z-index: 1000; }
        .nav-container { max-width: 1200px; margin: 0 auto; padding: 0 2rem; display: flex; justify-content: space-between; align-items: center; }
        .logo h1 { font-size: 2.5rem; font-weight: 900; letter-spacing: 2px; text-transform: uppercase; margin: -2px 0 0 -3px; }
        
        .social-icons { display: flex; gap: 1rem; margin-right: -30px; }
        .social-btn { width: 40px; height: 40px; border: 2px solid #fff; border-radius: 50%; display: flex; align-items: center; justify-content: center; transition: all 0.3s ease; background: transparent; }
        .social-btn:hover { transform: scale(1.1); box-shadow: 0 0 15px rgba(255,255,255,0.4); background: rgba(255,255,255,0.1); }
        .icon { width: 24px; height: 24px; object-fit: contain; }
        
        .telegram-btn { width: 40px; height: 40px; border: 2px solid #fff; border-radius: 50%; display: flex; align-items: center; justify-content: center; transition: all 0.3s ease; background: white; }
        .telegram-btn:hover { transform: scale(1.1); box-shadow: 0 0 15px rgba(255,255,255,0.4); }
        .telegram-icon { width: 22px; height: 22px; object-fit: contain; filter: brightness(0) contrast(100%); }

        .sidebar { position: fixed; right: -250px; top: 0; height: 100vh; width: 250px; background: rgba(0,0,0,0.95); border-left: 1px solid #333; transition: right 0.3s ease; z-index: 999; padding: 80px 1rem 2rem 1rem; }
        .sidebar:hover { right: 0; }
        .sidebar-trigger { position: fixed; right: 20px; top: 50%; transform: translateY(-50%); width: 30px; height: 100px; background: rgba(0,0,0,0.7); border-radius: 10px 0 0 10px; display: flex; align-items: center; justify-content: center; cursor: pointer; z-index: 998; transition: right 0.3s ease; }
        .sidebar-trigger::before { content: '☰'; color: white; font-size: 18px; font-weight: bold; }
        .sidebar:hover ~ .sidebar-trigger { right: 250px; }
        .sidebar-nav { display: flex; flex-direction: column; gap: 1rem; }
        .sidebar-btn { color: #fff; text-decoration: none; padding: 1rem; border: 1px solid #fff; border-radius: 8px; transition: all 0.3s ease; text-align: center; font-weight: bold; text-transform: uppercase; }
        .sidebar-btn:hover { background: #fff; color: #000; transform: translateX(-5px); }

        .main-content { margin-top: 80px; padding: 2rem; }
        .page-section { min-height: 100vh; display: flex; align-items: center; justify-content: center; padding: 4rem 2rem; opacity: 0; transform: translateY(50px); transition: all 0.8s ease; }
        .page-section.active { opacity: 1; transform: translateY(0); }
        .container { max-width: 1200px; margin: 0 auto; }

        .photo-left, .photo-right { display: grid; grid-template-columns: 1fr 1fr; gap: 4rem; align-items: center; }
        .photo-left .photo, .photo-right .photo { order: 1; }
        .photo-right .photo { order: 2; }
        .photo-left .text-content, .photo-right .text-content { order: 2; }
        .photo-right .text-content { order: 1; }
        .photo img { width: 100%; height: 400px; object-fit: cover; border-radius: 10px; border: 2px solid #fff; }
        
        .text-content, .full-text { text-align: center; }
        .text-content h2, .full-text h2 { font-size: 2.5rem; margin-bottom: 2rem; font-weight: bold; text-transform: uppercase; }
        .text-content p, .full-text p { font-size: 1.1rem; line-height: 1.8; opacity: 0.9; font-weight: bold; margin-bottom: 1.5rem; }
        .full-text { max-width: 800px; margin: 0 auto; }

        .bottom-footer { background: #000; padding: 2rem 0; border-top: 1px solid #333; text-align: center; }
        .footer-container { max-width: 1200px; margin: 0 auto; padding: 0 2rem; }
        .footer-container p { font-size: 1.1rem; opacity: 0.7; font-weight: bold; }

        @media (max-width: 768px) {
            .nav-container { flex-direction: column; gap: 1rem; }
            .photo-left, .photo-right { grid-template-columns: 1fr; gap: 2rem; }
            .logo h1 { font-size: 2rem; }
            .sidebar { width: 200px; right: -200px; }
            .sidebar:hover ~ .sidebar-trigger { right: 200px; }
            .text-content h2, .full-text h2 { font-size: 2rem; }
            .social-icons { margin-right: 0; }
        }
    </style>
</head>
<body>
    <nav class="top-nav">
        <div class="nav-container">
            <div class="logo"><h1 class="glowing-text">BIOGRAPHY</h1></div>
            <div class="social-icons">
                <a href="https://t.me/+fe73LRBQUlcxYmQy" class="telegram-btn" target="_blank">
                    <img src="https://upload.wikimedia.org/wikipedia/commons/8/83/Telegram_2019_Logo.svg" alt="Telegram" class="telegram-icon">
                </a>
                <a href="#discord-url" class="social-btn"><img src="images/discord.png" alt="Discord" class="icon"></a>
                <a href="#gmail-url" class="social-btn"><img src="images/gmail.png" alt="Gmail" class="icon"></a>
            </div>
        </div>
    </nav>

    <aside class="sidebar">
        <nav class="sidebar-nav">
            <a href="#page1" class="sidebar-btn">Раздел 1</a>
            <a href="#page2" class="sidebar-btn">Раздел 2</a>
            <a href="#page3" class="sidebar-btn">Раздел 3</a>
        </nav>
    </aside>
    <div class="sidebar-trigger"></div>

    <main class="main-content">
        <section id="page1" class="page-section">
            <div class="container">
                <div class="photo-left">
                    <div class="photo"><img src="images/photo1.jpg" alt="Фото 1"></div>
                    <div class="text-content">
                        <h2>Заголовок раздела 1</h2>
                        <p>Текст будет здесь...</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="page2" class="page-section">
            <div class="container">
                <div class="photo-right">
                    <div class="photo"><img src="images/photo2.jpg" alt="Фото 2"></div>
                    <div class="text-content">
                        <h2>Заголовок раздела 2</h2>
                        <p>Текст будет здесь...</p>
                    </div>
                </div>
            </div>
        </section>

        <section id="page3" class="page-section">
            <div class="container">
                <div class="full-text">
                    <h2>Заголовок раздела 3</h2>
                    <p>Текст будет здесь...</p>
                    <p>Дополнительный текст...</p>
                    <p>Еще больше текста...</p>
                </div>
            </div>
        </section>
    </main>

    <footer class="bottom-footer">
        <div class="footer-container">
            <p>Powered by RoDonations</p>
        </div>
    </footer>

    <script>
        document.addEventListener('DOMContentLoaded', function() {
            const sidebarLinks = document.querySelectorAll('.sidebar-btn');
            const pageSections = document.querySelectorAll('.page-section');
            
            sidebarLinks.forEach(link => {
                link.addEventListener('click', function(e) {
                    e.preventDefault();
                    const targetId = this.getAttribute('href').substring(1);
                    const targetSection = document.getElementById(targetId);
                    if (targetSection) {
                        targetSection.scrollIntoView({ behavior: 'smooth', block: 'start' });
                    }
                });
            });
            
            function checkScroll() {
                pageSections.forEach(section => {
                    const sectionTop = section.getBoundingClientRect().top;
                    if (sectionTop < window.innerHeight * 0.8) {
                        section.classList.add('active');
                    }
                });
            }
            checkScroll();
            window.addEventListener('scroll', checkScroll);
        });
    </script>
</body>
</html>
