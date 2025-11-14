<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="css/portfoliyo.css">
    <link rel="web icon" href="imgs/shahruh-img.jpg">
</head>
<body>
    <nav class="navbar">
        <div class="container">
            <h1 class="nav__title">
                <a href="portfoliyo.html">
                    Duschanov Shahruh
                </a>
            </h1>
            <ul class="nav__list">
                <li class="nav__item"><a href="portfoliyo.html" class="nav__link home">Home</a></li>
                <li class="nav__item"><a href="#about" class="nav__link about">About</a></li>
                <li class="nav__item"><a href="#skills" class="nav__link skills">Skills</a></li>
                <li class="nav__item"><a href="#contact" class="nav__link contact">Contact</a></li>
            </ul>
        </div>
    </nav>
    <header class="header">
        <div class="container">
            <div class="header__cards">
                <div class="header__card">
                    <p class="header__card-text">Hello, my name is</p>
                    <h1 class="header__card-title">
                        Duschanov Shahruh
                    </h1>
                    <h3 class="header__card-title-two">Front-End Developer</h3>
                    <p class="header__card-text-two">Men HTML, CSS, JavaScript va React.js bilan ishlayman. Amaliy loyihalarda ishtirok etib, o’z ko’nikmalarimni rivojlantirishni xohlayman. Jamoada ishlash va yangi texnologiyalarni o’rganishni yaxshi ko’raman.</p>
                    <div class="header__card-btns">
                            <a href="resume/resume.pdf" class="header__card-btn btn">Resume (PDF)</a>
                            <a href="#" class="header__card-btn btn">Contact me</a>
                    </div>
                </div>
                <div class="header__card">
                    <div class="header__card-imgs">
                        <img src="imgs/shahruh-img.jpg" alt="" class="header__card-img">
                        <div class="header__card-img-titles">
                            <h3 class="header__card-img-title">Duschanov Shahruhbek</h3>
                            <p class="header__card-img-text">Front-End Developer</p>
                        </div>
                    </div>
                    <ul class="header__card-img-list">
                        <li class="header__card-img-item">
                            <strong>Email:</strong>
                            duschanovabushahruhbek@gmail.com
                        </li>
                        <li class="header__card-img-item">
                            <strong>Telefon:</strong>
                            +998 99 913 89 99
                        </li>
                        <li class="header__card-img-item">
                            <strong>Manzil:</strong>
                            Xorazm viloyati, Xonqa tumani, Madaniyer mahallasi
                        </li>
                    </ul>
                    <h4 class="header__card-img-title-two">Qisqacha ma'lumot</h4>
                    <p class="header__card-img-text-two">Men web-dasturlashda chuqur qiziqaman. HTML/CSS, JavaScript va React bo'yicha loyihalar quraman. Tez o'rganaman va jamoada samarali ishlayman.</p>
                </div>
            </div>
        </div>
    </header>
    <main class="main">
        <section id="about">
            <div class="container">
                <h2 class="about__title">
                    About me
                </h2>
                <p class="about__text">
                    Men — Front-end yo'nalishida ishlaydigan dasturchiman. Hozirgacha o'zimni mustaqil loyihalarda sinab ko'rdim va portfolio to'plash ustidaman. Fikr-mulohaza olish va hamkorlik qilishga ochiqman.
                </p>
            </div> 
        </section>
        <section id="skills">
            <div class="container">
                <h1 class="skills__title">Skills</h1>
                <div class="skills__cards">
                    <div class="skills__card">
                        <h1 class="skills__card-title">
                            75%
                        </h1>
                        <p class="skills__card-text">
                            Html
                        </p>
                    </div>
                    <div class="skills__card">
                        <h1 class="skills__card-title">
                            50%
                        </h1>
                        <p class="skills__card-text">
                            Css
                        </p>
                    </div>
                    <div class="skills__card">
                        <h1 class="skills__card-title">
                            15%
                        </h1>
                        <p class="skills__card-text">
                            JavaScript
                        </p>
                    </div>
                </div>
            </div>
        </section>
        <section id="contact">
            <div class="container">
                <h1 class="contact__title">
                    Contact me
                </h1>
                <div class="contact__cards">
                    <div class="contact__card">
                        <form class="contact__form">
                            <div class="contact__label">
                                <label for="">
                                    Ism
                                </label>
                                <input type="text" placeholder="Ismingizni yozing" required>
                            </div>
                            <div class="contact__label">
                                <label for="">
                                    Email
                                </label>
                                <input type="email" placeholder="email@example.com" required>
                            </div>
                            <div class="contact__label">
                                <label for="">
                                    Xabar
                                    <br>
                                </label>
                                <textarea name="Message" id="Message" placeholder="Xabaringiz....." rows="4" cols="5" class="input"></textarea>
                            </div>
                            <button class="contact__form-btn btn">Yuborish</button>           
                        </form>
                    </div>
                    <div class="contact__card">
                        <h3 class="contact__card-title">
                            Boshqa kontaktlar
                        </h3>
                        <ul class="header__card-img-list">
                            <li class="header__card-img-item">
                                <strong>Email:</strong>
                                duschanovabushahruhbek@gmail.com
                            </li>
                            <li class="header__card-img-item">
                                <strong>Telefon:</strong>
                                +998 99 913 89 99
                            </li>
                            <li class="header__card-img-item">
                                <strong>Github:</strong>
                                <a href="https://github.com/Shahruhbek-desinger" class="contact__card-img-link"> github.com/Shahruhbek-desinger</a>
                            </li>
                        </ul>                    
                    </div>
                </div>
            </div>
        </section>
    </main>
    <footer class="footer">
        <div class="container">
            <p class="footer__text">
                ©2025 Samandarov Shokirjon. All rights reserved.
            </p>
        </div>
    </footer>
</body>
</html>
