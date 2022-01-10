<template>
  <section>
    <!--==================== HEADER ====================-->
    <header class="header" id="header">
      <nav class="nav container">
        <a href="#" class="nav__logo">Islam</a>
        <div class="nav__menu" id="nav-menu">
          <ul class="nav__list grid">
            <li class="nav__item">
              <a href="#home" class="nav__link active-link">
                <i class="uil uil-estate nav__icon"></i>Home
              </a>
            </li>
            <li class="nav__item">
              <a href="#about" class="nav__link">
                <i class="uil uil-user nav__icon"></i>About
              </a>
            </li>
            <li class="nav__item">
              <a href="#skills" class="nav__link">
                <i class="uil uil-file-alt nav__icon"></i>Skills
              </a>
            </li>
            <li class="nav__item">
              <a href="#services" class="nav__link">
                <i class="uil uil-briefcase-alt nav__icon"></i>Services
              </a>
            </li>
            <li class="nav__item">
              <a href="#portfolio" class="nav__link">
                <i class="uil uil-scenery nav__icon"></i>Portfolio
              </a>
            </li>
            <li class="nav__item">
              <a href="#contact" class="nav__link">
                <i class="uil uil-message nav__icon"></i>Contact
              </a>
            </li>
          </ul>
          <i class="uil uil-times nav__close" id="nav-close"></i>
        </div>

        <div class="nav__btns">
          <!-- Theme change button -->
          <i class="uil uil-moon change-theme" id="theme-button"></i>
          <div class="nav__toggle" id="nav-toggle">
            <i class="uil uil-apps"></i>
          </div>
        </div>
      </nav>
    </header>

    <!--==================== MAIN ====================-->
    <main class="main">
      <!--==================== HOME ====================-->
      <section class="home section" id="home">
        <div class="home__container container grid">
          <div class="home__content grid">
            <div class="home__social">
              <a
                href="https://www.linkedin.com/in/islam-abd-elkader/"
                target="_blank"
                class="home__social-icon"
              >
                <i class="uil uil-linkedin-alt"></i>
              </a>
              <a
                href="https://github.com/islam-abdelkader"
                target="_blank"
                class="home__social-icon"
              >
                <i class="uil uil-github-alt"></i>
              </a>
              <a
                href="mailto:contact@islamabdelkader.com"
                target="_blank"
                class="home__social-icon"
              >
                <i class="uil uil-envelope-star"></i>
              </a>
            </div>
            <div class="home__img">
              <svg
                class="home__blob"
                viewBox="0 0 200 187"
                xmlns="http://www.w3.org/2000/svg"
                xmlns:xlink="http://www.w3.org/1999/xlink"
              >
                <mask id="mask0" mask-type="alpha">
                  <path
                    d="M190.312 36.4879C206.582 62.1187 201.309 102.826 182.328 134.186C163.346 165.547
                                    130.807 187.559 100.226 186.353C69.6454 185.297 41.0228 161.023 21.7403 129.362C2.45775
                                    97.8511 -7.48481 59.1033 6.67581 34.5279C20.9871 10.1032 59.7028 -0.149132 97.9666
                                    0.00163737C136.23 0.303176 174.193 10.857 190.312 36.4879Z"
                  />
                </mask>
                <g mask="url(#mask0)">
                  <path
                    d="M190.312 36.4879C206.582 62.1187 201.309 102.826 182.328 134.186C163.346
                                    165.547 130.807 187.559 100.226 186.353C69.6454 185.297 41.0228 161.023 21.7403
                                    129.362C2.45775 97.8511 -7.48481 59.1033 6.67581 34.5279C20.9871 10.1032 59.7028
                                    -0.149132 97.9666 0.00163737C136.23 0.303176 174.193 10.857 190.312 36.4879Z"
                  />

                  <image
                    class="home__blob-img"
                    x="10"
                    y="13"
                    xlink:href="assets/img/personal/transparent.png"
                  />
                </g>
              </svg>
            </div>
            <div class="home__data">
              <h1 class="home__title">
                Hi, I'm Islam
              </h1>
              <h2 class="home__subtitle">Full Stack Developer</h2>
              <p class="home__description">
                Bachelor of Communication and Elecronics Engineer, Passionate
                about software development.
              </p>
              <a href="#contact" class="button button--flex">
                Contact <i class="uil uil-message button__icon"></i>
              </a>
            </div>
          </div>
          <div class="home__scroll">
            <a href="#about" class="home__scroll-button button--flex">
              <i class="uil uil-mouse-alt home__scroll-mouse"></i>
              <span class="home__scroll-name">Scroll down</span>
              <i class="uil uil-arrow-down home__scroll-arrow"></i>
            </a>
          </div>
        </div>
      </section>

      <!--==================== ABOUT ====================-->
      <section class="about section" id="about">
        <h2 class="section__title">About Me</h2>
        <span class="section__subtitle">My introduction</span>

        <div class="about__container container grid">
          <img src="assets/img/woman/graphs.png" alt="" class="about__img" />
          <div class="about__data">
            <p class="about__description">
              A Full Stack Developer, with very good experience in programming
              especially in web development, ambitious, and I'm always trying to
              develop myself and develop where I belong. Looking to work in an
              environment that encourages me to succeed and grow professionally
              where I can utilize my skills and knowledge appropriately.
            </p>
            <div class="about__info">
              <div>
                <span class="about__info-title">01+</span>
                <span class="about__info-name"
                  >Years <br />
                  experience</span
                >
              </div>
              <div>
                <span class="about__info-title">10+</span>
                <span class="about__info-name"
                  >Completed <br />
                  project</span
                >
              </div>
              <div>
                <span class="about__info-title">01+</span>
                <span class="about__info-name"
                  >Companies <br />
                  worked</span
                >
              </div>
            </div>
            <div class="about__buttons">
              <a
                download=""
                href="assets/pdf/Islam_Abd-Elkader_Fullstack-PHP-Web-Developer(Laravel).pdf"
                class="button button--flex"
              >
                Download CV<i class="uil uil-download-alt button__icon"></i>
              </a>
            </div>
          </div>
        </div>
      </section>

      <!--==================== SKILLS ====================-->
      <section class="skills section" id="skills">
        <h2 class="section__title">Skills</h2>
        <span class="section__subtitle">My technologies level</span>

        <div class="skills__container container grid">
          <div>
            <!--==================== SKILL 1====================-->
            <div class="skills__content skills__close">
              <div class="skills__header">
                <i class="uil uil-brackets-curly skills__icon"></i>
                <div>
                  <h1 class="skills__titles">Frontend developer</h1>
                  <span class="skills__subtitle">
                    More than 1 years
                  </span>
                </div>

                <i class="uil uil-angle-down skills__arrow"></i>
              </div>
              <div class="skills__list grid">
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">HTML</h3>
                    <span class="skills__number">90%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__html"></span>
                  </div>
                </div>
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">CSS</h3>
                    <span class="skills__number">60%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__css"></span>
                  </div>
                </div>
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">JavaScript</h3>
                    <span class="skills__number">80%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__js"></span>
                  </div>
                </div>
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">JQuery</h3>
                    <span class="skills__number">60%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__jquery"></span>
                  </div>
                </div>
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">Bootstrap</h3>
                    <span class="skills__number">90%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__bootstrap"></span>
                  </div>
                </div>
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">Angular</h3>
                    <span class="skills__number">55%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__angular"></span>
                  </div>
                </div>
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">Vue</h3>
                    <span class="skills__number">75%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__html"></span>
                  </div>
                </div>
              </div>
            </div>

            <!--==================== SKILL 2====================-->
            <div class="skills__content skills__close">
              <div class="skills__header">
                <i class="uil uil-server-network skills__icon"></i>
                <div>
                  <h1 class="skills__titles">Backend developer</h1>
                  <span class="skills__subtitle">
                    More than 1 years
                  </span>
                </div>

                <i class="uil uil-angle-down skills__arrow"></i>
              </div>
              <div class="skills__list grid">
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">PHP</h3>
                    <span class="skills__number">60%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__php"></span>
                  </div>
                </div>
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">MySQL</h3>
                    <span class="skills__number">70%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__sql"></span>
                  </div>
                </div>
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">Laravel</h3>
                    <span class="skills__number">65%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__laravel"></span>
                  </div>
                </div>
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">NoSQL (MongoDB)</h3>
                    <span class="skills__number">50%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__nosql"></span>
                  </div>
                </div>
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">Node Js</h3>
                    <span class="skills__number">40%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__node"></span>
                  </div>
                </div>
              </div>
            </div>
          </div>

          <!--==================== SKILL 3====================-->
          <div>
            <div class="skills__content skills__close">
              <div class="skills__header">
                <i class="uil uil-swatchbook skills__icon"></i>
                <div>
                  <h1 class="skills__titles">Other</h1>
                  <span class="skills__subtitle">
                    More than 1 years
                  </span>
                </div>

                <i class="uil uil-angle-down skills__arrow"></i>
              </div>
              <div class="skills__list grid">
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">Git & Github</h3>
                    <span class="skills__number">70%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__git"></span>
                  </div>
                </div>
                <div class="skills__data">
                  <div class="skills__titles">
                    <h3 class="skills__name">Linux</h3>
                    <span class="skills__number">90%</span>
                  </div>
                  <div class="skills__bar">
                    <span class="skills__percentage skills__linux"></span>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!--==================== QUALIFICATION ====================-->
      <section class="qualification section">
        <h2 class="section__title">Qualification</h2>
        <span class="section__subtitle">My personal journy</span>
        <div class="qualification__container container">
          <div class="qualification__tabs">
            <div
              class="qualification__button button--flex qualification__active"
              data-target="#education"
            >
              <i class="uil uil-graduation-cap qualification__icon"></i>
              Education
            </div>
            <div class="qualification__button button--flex" data-target="#work">
              <i class="uil uil-briefcase-alt qualification__icon"></i>
              Work
            </div>
          </div>

          <div class="qualification__sections">
            <!--==================== QUALIFICATION EDUCATION CONTENT ====================-->
            <div
              class="qualification__content qualification__active"
              data-content
              id="education"
            >
              <!--==================== QUALIFICATION 1====================-->
              <div class="qualification__data">
                <div>
                  <h3 class="qualification__title">
                    Full Stack PHP Web Developer
                  </h3>
                  <span class="qualification__subtitle">Egypt - ITI</span>
                  <div class="qualification__calendar">
                    <i class="uil uil-calendar-alt"></i>
                    2021 - 2021
                  </div>
                </div>
                <div>
                  <span class="qualification__rounder"></span>
                  <span class="qualification__line"></span>
                </div>
              </div>

              <!--==================== QUALIFICATION 2====================-->
              <div class="qualification__data">
                <div></div>
                <div>
                  <span class="qualification__rounder"></span>
                  <span class="qualification__line"></span>
                </div>
                <div>
                  <h3 class="qualification__title">C & Embedded C</h3>
                  <span class="qualification__subtitle">Egypt - NTI</span>
                  <div class="qualification__calendar">
                    <i class="uil uil-calendar-alt"></i>
                    2020 - 2020
                  </div>
                </div>
              </div>
              <!--==================== QUALIFICATION 3====================-->
              <div class="qualification__data">
                <div>
                  <h3 class="qualification__title">
                    Communication & Electronics Engineer
                  </h3>
                  <span class="qualification__subtitle">Egypt - NDETI</span>
                  <div class="qualification__calendar">
                    <i class="uil uil-calendar-alt"></i>
                    2015 - 2020
                  </div>
                </div>
                <div>
                  <span class="qualification__rounder"></span>
                  <!-- <span class="qualification__line"></span> -->
                </div>
              </div>
            </div>

            <!--==================== QUALIFICATION WORK CONTENT====================-->
            <div class="qualification__content" data-content id="work">
              <!--==================== QUALIFICATION 1====================-->
              <div class="qualification__data">
                <div>
                  <h3 class="qualification__title">Full Stack Developer</h3>
                  <span class="qualification__subtitle">Twision</span>
                  <div class="qualification__calendar">
                    <i class="uil uil-calendar-alt"></i>
                    2021 - Present
                  </div>
                </div>
                <div>
                  <span class="qualification__rounder"></span>
                  <!-- <span class="qualification__line"></span> -->
                </div>
              </div>

              <!--==================== QUALIFICATION 2====================-->
              <!-- <div class="qualification__data">
                                <div></div>
                                <div>
                                    <span class="qualification__rounder"></span>
                                    <span class="qualification__line"></span>
                                </div>
                                <div>
                                    <h3 class="qualification__title"> ?Title? </h3>
                                    <span class="qualification__subtitle">?Where?</span>
                                    <div class="qualification__calendar">
                                        <i class="uil uil-calendar-alt"></i>
                                        2020 - 2020
                                    </div>
                                </div>
                            </div> -->
              <!--==================== QUALIFICATION 3====================-->
              <!-- <div class="qualification__data">
                                <div>
                                    <h3 class="qualification__title"> ?Title? </h3>
                                    <span class="qualification__subtitle"> ?Where? </span>
                                    <div class="qualification__calendar">
                                        <i class="uil uil-calendar-alt"></i>
                                        2021 - 2021
                                    </div>
                                </div>
                                <div>
                                    <span class="qualification__rounder"></span>
                                    <span class="qualification__line"></span>
                                </div>
                            </div> -->
            </div>
          </div>
        </div>
      </section>

      <!--==================== SERVICES ====================-->
      <section class="services section" id="services">
        <h2 class="section__title">Services</h2>
        <span class="section__subtitle">What i offer</span>

        <div class="services__container container grid">
          <!--==================== SERVICE 1 ====================-->
          <div class="services__content">
            <div>
              <i class="uil uil-arrow services__icon"></i>
              <h3 class="services__title">Frontend Developer</h3>
            </div>
            <span
              class="button button--flex button--small button--link services__button"
            >
              View More
              <i class="uil uil-arrow-right button__icon"></i>
            </span>

            <div class="services__modal">
              <div class="services__modal-content">
                <h4 class="services__modal-title">
                  Frontend <br />
                  Developer
                </h4>
                <i class="uil uil-times services__modal-close"></i>
                <ul class="services__modal-services grid">
                  <li class="services__modal-service">
                    <i class="uil uil-check-circle services__modal-icon"></i>
                    <p>Ease of use</p>
                  </li>
                  <li class="services__modal-service">
                    <i class="uil uil-check-circle services__modal-icon"></i>
                    <p>Speed sites</p>
                  </li>
                  <li class="services__modal-service">
                    <i class="uil uil-check-circle services__modal-icon"></i>
                    <p>Fluid design</p>
                  </li>
                </ul>
              </div>
            </div>
          </div>

          <!--==================== SERVICE 2 ====================-->
          <div class="services__content">
            <div>
              <i class="uil uil-pen services__icon"></i>
              <h3 class="services__title">Backend Developer</h3>
            </div>
            <span
              class="button button--flex button--small button--link services__button"
            >
              View More
              <i class="uil uil-arrow-right button__icon"></i>
            </span>

            <div class="services__modal">
              <div class="services__modal-content">
                <h4 class="services__modal-title">
                  Backend <br />
                  Developer
                </h4>
                <i class="uil uil-times services__modal-close"></i>
                <ul class="services__modal-services grid">
                  <li class="services__modal-service">
                    <i class="uil uil-check-circle services__modal-icon"></i>
                    <p>Best Practices</p>
                  </li>
                  <li class="services__modal-service">
                    <i class="uil uil-check-circle services__modal-icon"></i>
                    <p>Making a complex websites</p>
                  </li>
                  <li class="services__modal-service">
                    <i class="uil uil-check-circle services__modal-icon"></i>
                    <p>Clean & properly constructed pages</p>
                  </li>
                </ul>
              </div>
            </div>
          </div>
        </div>
      </section>

      <!--==================== PORTFOLIO ====================-->
      <section class="portfolio section" id="portfolio">
        <h2 class="section__title">Portfolio</h2>
        <span class="section__subtitle">Most recent work</span>
        <div class="portfolio__container container swiper-container">
          <div class="swiper-wrapper">
            <!--==================== PORTFOLIO 1 ====================-->
            <div class="portfolio__content grid swiper-slide">
              <img
                src="assets/img/portfolio/twi-shop-site.png"
                alt=""
                class="portfolio__img"
              />
              <div class="portfolio__data">
                <h3 class="portfolio__title">Twi-Shop</h3>
                <p class="portfolio__description">E-Commerce Website</p>
                <div class="portfolio__footer">
                  <div class="portfolio__techs">
                    <span class="portfolio__tech">HTML</span>
                    <span class="portfolio__tech">CSS</span>
                    <span class="portfolio__tech">Bootstrap</span>
                  </div>
                  <div class="portfolio__buttons">
                    <span class="portfolio__tech">JS</span>
                    <span class="portfolio__tech">JQuery</span>
                    <span class="portfolio__tech">Laravel</span>
                  </div>
                </div>
              </div>
            </div>
            <!--==================== PORTFOLIO 2 ====================-->
            <div class="portfolio__content grid swiper-slide">
              <img
                src="assets/img/portfolio/html-css-template.png"
                alt=""
                class="portfolio__img"
              />
              <div class="portfolio__data">
                <h3 class="portfolio__title">HTML & CSS Template</h3>
                <p class="portfolio__description">
                  Website adaptable to all devices
                </p>
                <div class="portfolio__footer">
                  <div class="portfolio__techs">
                    <span class="portfolio__tech">HTML</span>
                    <span class="portfolio__tech">CSS</span>
                  </div>
                  <div class="portfolio__buttons">
                    <a
                      target="_blank"
                      href="https://islam-abdelkader.github.io/HTML-Css-Template-One/"
                      class="button button--flex button--small portfolio__button"
                    >
                      Preview <i class="uil uil-arrow-right button__icon"></i>
                    </a>
                    <a
                      target="_blank"
                      href="https://github.com/islam-abdelkader/HTML-Css-Template-One"
                      class="button button--flex button--small portfolio__button"
                    >
                      Demo <i class="uil uil-arrow-right button__icon"></i>
                    </a>
                  </div>
                </div>
              </div>
            </div>
            <!--==================== PORTFOLIO 3 ====================-->
            <div class="portfolio__content grid swiper-slide">
              <img
                src="assets/img/portfolio/bootstrap-template.png"
                alt=""
                class="portfolio__img"
              />
              <div class="portfolio__data">
                <h3 class="portfolio__title">Bootstrap 5 Lawyer Template</h3>
                <p class="portfolio__description">Responsive Landing Page</p>
                <div class="portfolio__footer">
                  <div class="portfolio__techs">
                    <span class="portfolio__tech">HTML</span>
                    <span class="portfolio__tech">CSS</span>
                    <span class="portfolio__tech">Bootstrap 5</span>
                  </div>
                  <div class="portfolio__buttons">
                    <a
                      target="_blank"
                      href="https://islam-abdelkader.github.io/Responsive-page-Bootstrap5-/"
                      class="button button--flex button--small portfolio__button"
                    >
                      Preview <i class="uil uil-arrow-right button__icon"></i>
                    </a>
                    <a
                      target="_blank"
                      href="https://github.com/islam-abdelkader/Responsive-page-Bootstrap5-"
                      class="button button--flex button--small portfolio__button"
                    >
                      Demo <i class="uil uil-arrow-right button__icon"></i>
                    </a>
                  </div>
                </div>
              </div>
            </div>
            <!--==================== PORTFOLIO 4 ====================-->
            <div class="portfolio__content grid swiper-slide">
              <img
                src="assets/img/portfolio/monster-game.png"
                alt=""
                class="portfolio__img"
              />
              <div class="portfolio__data">
                <h3 class="portfolio__title">Vue Monster Game</h3>
                <p class="portfolio__description">
                  Website adaptable to all devices
                </p>
                <div class="portfolio__footer">
                  <div class="portfolio__techs">
                    <span class="portfolio__tech">HTML</span>
                    <span class="portfolio__tech">CSS</span>
                    <span class="portfolio__tech">Vue js</span>
                  </div>
                  <div class="portfolio__buttons">
                    <a
                      target="_blank"
                      href="https://islam-abdelkader.github.io/MonsterGame-using-Vue/"
                      class="button button--flex button--small portfolio__button"
                    >
                      Preview <i class="uil uil-arrow-right button__icon"></i>
                    </a>
                    <a
                      target="_blank"
                      href="https://github.com/islam-abdelkader/MonsterGame-using-Vue"
                      class="button button--flex button--small portfolio__button"
                    >
                      Demo <i class="uil uil-arrow-right button__icon"></i>
                    </a>
                  </div>
                </div>
              </div>
            </div>
          </div>
          <!-- Add Arrows -->
          <div class="swiper-button-next">
            <i class="uil uil-angle-right-b swiper-portfolio-icon"></i>
          </div>
          <div class="swiper-button-prev">
            <i class="uil uil-angle-left-b swiper-portfolio-icon"></i>
          </div>
          <!-- Add Pagination -->
          <div class="swiper-pagination"></div>
        </div>
      </section>

      <!--==================== PROJECT IN MIND ====================-->
      <section class="project section">
        <div class="project__bg">
          <div class="project__container container grid">
            <div class="project__data">
              <h2 class="project__title">You have a new project</h2>
              <p class="project__description">
                You have an idea. You want to turn it into an online business
                without all the hassle. Perfect! I'm here to help you set up an
                e-commerce store that looks amazing and makes you money.
              </p>
              <a href="#contact" class="button button--flex button--white">
                Contact
                <i class="uil uil-message project__icon button__icon"></i>
              </a>
            </div>
            <img src="assets/img/woman/money.png" alt="" class="project__img" />
          </div>
        </div>
      </section>

      <!--==================== TESTIMONIAL ====================-->
      <section class="testimonial section">
        <!-- <h2 class="section__title">Testimonial</h2>
                <span class="section__subtitle">My client saying</span>

                <div class="testimonial__container container swiper-container">
                    <div class="swiper-wrapper"> -->
        <!--==================== TESTIMONIAL 1 ====================-->
        <!-- <div class="testimonial__content swiper-slide">
                            <div class="testimonial__data">
                                <div class="testimonial__header">
                                    <img src="assets/img/testimonial1.jpg" alt="" class="testimonial__img">
                                    <div>
                                        <h3 class="testimonial__name">JOHN DUOE</h3>
                                        <span class="testimonial__client">Client</span>
                                    </div>
                                </div>
                                <div>
                                    <i class="uil uil-star testimonial__icon-star"></i>
                                    <i class="uil uil-star testimonial__icon-star"></i>
                                    <i class="uil uil-star testimonial__icon-star"></i>
                                    <i class="uil uil-star testimonial__icon-star"></i>
                                    <i class="uil uil-star testimonial__icon-star"></i>
                                </div>
                            </div>
                            <p class="testimonial__description">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo, modi?
                            </p>
                        </div> -->
        <!--==================== TESTIMONIAL 2 ====================-->
        <!-- <div class="testimonial__content swiper-slide">
                            <div class="testimonial__data">
                                <div class="testimonial__header">
                                    <img src="assets/img/testimonial2.jpg" alt="" class="testimonial__img">
                                    <div>
                                        <h3 class="testimonial__name">JOHN DUOE</h3>
                                        <span class="testimonial__client">Client</span>
                                    </div>
                                </div>
                                <div>
                                    <i class="uil uil-star testimonial__icon-star"></i>
                                    <i class="uil uil-star testimonial__icon-star"></i>
                                    <i class="uil uil-star testimonial__icon-star"></i>
                                    <i class="uil uil-star testimonial__icon-star"></i>
                                    <i class="uil uil-star testimonial__icon-star"></i>
                                </div>
                            </div>
                            <p class="testimonial__description">
                                Lorem ipsum dolor sit amet consectetur adipisicing elit. Quo, modi?
                            </p>
                        </div>
                    </div>
                    <div class="swiper-pagination swiper-pagination-testimonial"></div>
                </div> -->
      </section>

      <!--==================== CONTACT ====================-->
      <section class="contact section" id="contact">
        <div class="section__title">Contact</div>
        <span class="section__subtitle">Get in touch</span>

        <div class="contact__container container grid">
          <!-- <div> -->
          <div class="contact__information">
            <i class="uil uil-phone contact__icon"></i>
            <div>
              <h3 class="contact__title">Call Me</h3>
              <span class="contact__subtitle">
                (+20)-1554-742-372
                <br />
                (+20)-1001-074-075
              </span>
            </div>
          </div>
          <div class="contact__information">
            <i class="uil uil-envelope contact__icon"></i>
            <div>
              <h3 class="contact__title">Email</h3>
              <span class="contact__subtitle">contact@islamabdelkader.com</span>
            </div>
          </div>
          <div class="contact__information">
            <i class="uil uil-map-marker contact__icon"></i>
            <div>
              <h3 class="contact__title">Location</h3>
              <span class="contact__subtitle">Egypt - Dakahlia #35666</span>
            </div>
          </div>
          <!-- </div> -->
          <!-- <form action="" class="contact__form grid">
                        <div class="contact__inputs grid">
                            <div class="contact__content">
                                <label for="name" class="contact__label">Name</label>
                                <input type="text" class="contact__input" name="name" id="name">
                            </div>
                            <div class="contact__content">
                                <label for="name" class="contact__label">Email</label>
                                <input type="text" class="contact__input" name="name" id="name">
                            </div>
                        </div>
                        <div class="contact__content">
                            <label for="message" class="contact__label">Messange</label>
                            <textarea name="message" id="message" cols="0" rows="7" class="contact__input"></textarea>
                        </div>
                        <div>
                            <a href="#" class="button button--flex">
                                Send Message <i class="uil uil-message button__icon"></i>
                            </a>
                        </div>
                    </form> -->
        </div>
      </section>
    </main>

    <!--==================== FOOTER ====================-->
    <footer class="footer">
      <div class="footer__bg">
        <div class="footer__container container grid">
          <div>
            <h1 class="footer__title">Islam</h1>
            <span class="footer__subtitle">Full Stack Developer</span>
          </div>
          <ul class="footer__links">
            <li class="footer__link">Services</li>
            <li class="footer__link">Portfolio</li>
            <li class="footer__link">Contact</li>
          </ul>
          <div class="footer__socials">
            <a href="" target="_blank" class="footer__social">
              <i class="uil uil-facebook-f"></i>
            </a>
            <a href="" target="_blank" class="footer__social">
              <i class="uil uil-instagram"></i>
            </a>
            <a href="" target="_blank" class="footer__social">
              <i class="uil uil-twitter-alt"></i>
            </a>
          </div>
        </div>
        <p class="footer__copy">&#169; Islam. All right reserved</p>
      </div>
    </footer>
    <a href="#" class="scrollup" id="scroll-up">
      <i class="uil uil-arrow-up scrollup__icon"></i>
    </a>
  </section>
</template>
<style>
/*=========================================================*/
/*====================== GOOGLE FONTS =====================*/
/*=========================================================*/
@import url('https://unicons.iconscout.com/release/v4.0.0/css/line.css');
@import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600&display=swap');

/*=========================================================*/
/*===================== VARIABLES CSS =====================*/
/*=========================================================*/

:root {
  --header-height: 3rem;
  --main-transition: 0.3s;
  /*========== Colors ==========*/
  /* Change favorite color */
  --hue-color: 203; /*Purple 250 - Green 142 - Blue 230 - Pink 340*/

  /* HSL color mode */
  --first-color: hsl(var(--hue-color), 69%, 61%);
  --first-color-second: hsl(var(--hue-color), 69%, 61%);
  --first-color-alt: hsl(var(--hue-color), 57%, 53%);
  --first-color-lighter: hsl(var(--hue-color), 92%, 85%);
  --title-color: hsl(var(--hue-color), 8%, 15%);
  --text-color: hsl(var(--hue-color), 8%, 45%);
  --text-color-light: hsl(var(--hue-color), 8%, 65%);
  --input-color: hsl(var(--hue-color), 70%, 96%);
  --body-color: hsl(var(--hue-color), 60%, 99%);
  --scroll-bar-color: hsl(var(--hue-color), 12%, 90%);
  --scroll-thumb-color: hsl(var(--hue-color), 12%, 80%);

  --container-color: #fff;
  --swiper-theme-color: var(--first-color);
  /*========== Font and typography ==========*/
  --body-font: 'Poppins', sans-serif;

  /* .5rem = 8px, 1rem = 16px, 1.5rem = 24px ... */
  --big-font-size: 2rem;
  --h1-font-size: 1.5rem;
  --h2-font-size: 1.25rem;
  --h3-font-size: 1.15rem;
  --normal-font-size: 0.938rem;
  --small-font-size: 0.813rem;
  --smaller-font-size: 0.75rem;

  /*========== Font weight ==========*/
  --font-medium: 50;
  --font-semi-bold: 600;

  /*========== Margenes Bottom ==========*/
  /* .25rem = 4px, .5rem = 8px, .75rem = 12px ... */
  --mb-0-25: 0.25rem;
  --mb-0-5: 0.5rem;
  --mb-0-75: 0.75rem;
  --mb-1: 1rem;
  --mb-1-5: 1.5rem;
  --mb-2: 2rem;
  --mb-2-5: 2.5rem;
  --mb-3: 3rem;

  /*========== z index ==========*/
  --z-tooltip: 10;
  --z-fixed: 100;
  --z-modal: 1000;
}

/* Font size for large devices */
@media screen and (min-width: 968px) {
  :root {
    --big-font-size: 3rem;
    --h1-font-size: 2.25rem;
    --h2-font-size: 1.5rem;
    --h3-font-size: 1.25rem;
    --normal-font-size: 1rem;
    --small-font-size: 0.875rem;
    --smaller-font-size: 0.813rem;
  }
}

/*=========================================================*/
/*================== Variables Dark theme =================*/
/*=========================================================*/
body.dark-theme {
  /* HSL color mode */
  --first-color-second: hsl(var(--hue-color), 30%, 8%);
  --title-color: hsl(var(--hue-color), 8%, 95%);
  --text-color: hsl(var(--hue-color), 8%, 75%);
  --input-color: hsl(var(--hue-color), 29%, 16%);
  --body-color: hsl(var(--hue-color), 28%, 12%);
  --container-color: hsl(var(--hue-color), 29%, 16%);
  --scroll-bar-color: hsl(var(--hue-color), 12%, 48%);
  --scroll-thumb-color: hsl(var(--hue-color), 12%, 36%);
}

/*=========================================================*/
/*=================== Button Dark/Light ===================*/
/*=========================================================*/
.nav__btns {
  display: flex;
  align-items: center;
}

.change-theme {
  font-size: 1.25rem;
  color: var(--title-color);
  margin-right: var(--mb-1);
  cursor: pointer;
}

.change-theme:hover {
  color: var(--first-color);
}
/*=========================================================*/
/*========================== BASE =========================*/
/*=========================================================*/
* {
  box-sizing: border-box;
  padding: 0;
  margin: 0;
}

html {
  scroll-behavior: smooth !important;
}

body {
  margin: 0 0 var(--header-height) 0;
  font-family: var(--body-font);
  font-size: var(--normal-font-size);
  background-color: var(--body-color);
  color: var(--text-color);
}
h1,
h2,
h3,
h4 {
  color: var(--title-color);
  font-family: var(--font-semi-bold);
}

ul {
  list-style: none;
}

a {
  text-decoration: none;
}

img {
  max-width: 100%;
  height: auto;
}

/*=========================================================*/
/*================== REUSABLE CSS CLASSES =================*/
/*=========================================================*/
.section {
  padding: 2rem 0 4rem;
}

.section__title {
  font-size: var(--h1-font-size);
}

.section__subtitle {
  display: block;
  font-size: var(--small-font-size);
  margin-bottom: var(--mb-3);
}

.section__title,
.section__subtitle {
  text-align: center;
}

/*=========================================================*/
/*========================= LAYOUT ========================*/
/*=========================================================*/
.container {
  max-width: 768px;
  margin-left: var(--mb-1-5);
  margin-right: var(--mb-1-5);
}

.grid {
  display: grid;
  gap: 1.5rem;
}

.header {
  width: 100%;
  position: fixed;
  bottom: 0;
  left: 0;
  z-index: var(--z-fixed);
  background-color: var(--body-color);
}

/*=========================================================*/
/*========================== NAV ==========================*/
/*=========================================================*/
.nav {
  max-width: 968px;
  height: var(--header-height);
  display: flex;
  justify-content: space-between;
  align-items: center;
}

.nav__logo,
.nav__toggle {
  color: var(--title-color);
  font-weight: var(--font-medium);
}

.nav__logo:hover {
  color: var(--first-color);
}

.nav__toggle {
  font-size: 1.1rem;
  cursor: pointer;
}

.nav__toggle:hover {
  color: var(--first-color);
}

@media screen and (max-width: 767px) {
  .nav__menu {
    position: fixed;
    bottom: -100%;
    left: 0;
    width: 100%;
    background-color: var(--body-color);
    padding: 2rem 1.5rem 4rem;
    box-shadow: 0 -1px 4px rgba(0, 0, 0, 0.15);
    border-radius: 1.5rem 1.5rem 0 0;
    transition: var(--main-transition);
  }
}

.nav__list {
  grid-template-columns: repeat(3, 1fr);
  gap: 2rem;
}

.nav__link {
  display: flex;
  flex-direction: column;
  align-items: center;
  font-size: var(--small-font-size);
  color: var(--title-color);
  font-weight: var(--font-medium);
}

.nav__link:hover {
  color: var(--first-color);
}

.nav__icon {
  font-size: 1.2rem;
}

.nav__close {
  position: absolute;
  right: 1.3rem;
  bottom: 0.5rem;
  font-size: 1.5rem;
  cursor: pointer;
  color: var(--first-color);
}

.nav__colse:hover {
  color: var(--first-color-alt);
}
/* show menu */
.show-menu {
  bottom: 0;
}

/* Active link */
.active-link {
  color: var(--first-color);
}

/* Change background header */
.scroll-header {
  box-shadow: 0 -1px 4px rgba(0, 0, 0, 0.15);
}

/*=========================================================*/
/*========================== HOME =========================*/
/*=========================================================*/
.home__container {
  gap: 1rem;
}

.home__content {
  grid-template-columns: 0.5fr 3fr;
  padding-top: 3.5rem;
  align-items: center;
}

.home__social {
  display: grid;
  grid-template-columns: max-content;
  row-gap: 1rem;
}

.home__social-icon {
  font-size: 1.25rem;
  color: var(--first-color);
}

.home__social-icon:hover {
  color: var(--first-color-alt);
}

.home__blob {
  width: 200px;
  fill: var(--first-color);
}

.home__blob-img {
  width: 190px;
}

.home__data {
  grid-column: 1/3;
}

.home__title {
  font-size: var(--big-font-size);
}

.home__subtitle {
  font-size: var(--h3-font-size);
  color: var(--first-color);
  font-weight: var(--font-semi-bold);
  margin-bottom: var(--mb-0-75);
}

.home__description {
  margin-bottom: var(--mb-2);
}

.home__scroll {
  /* display: none; */
}

.home__scroll-button {
  color: var(--first-color);
  transition: var(--main-transition);
}

.home__scroll-button:hover {
  transform: translateY(0.25rem);
}

.home__scroll-mouse {
  font-size: 2rem;
}

.home__scroll-name {
  font-size: var(--small-font-size);
  color: var(--title-color);
  font-weight: var(--font-medium);
  margin-right: var(--mb-0-25);
}

.home__scroll-arrow {
  font-size: 1.25rem;
}

/*=========================================================*/
/*======================== BUTTONS ========================*/
/*=========================================================*/
.button {
  display: inline-block;
  background-color: var(--first-color);
  color: #fff;
  padding: 1rem;
  border-radius: 0.5rem;
  font-weight: var(--font-medium);
}

.button:hover {
  background-color: var(--first-color-alt);
}

.button__icon {
  font-size: 1.25rem;
  margin-left: var(--mb-0-5);
  transition: var(--main-transition);
}

/* .button--white{
    background-color: #FFF;
    color: var(--first-color);
}

.button--white:hover{
    background-color: #FFF;
} */
.button--white {
  background-color: transparent;
  border: 1px solid #fff;
  color: white;
}

.button--white:hover {
  background-color: #fff;
  color: var(--first-color);
}

.button--flex {
  display: inline-flex;
  align-items: center;
}

.button--small {
  padding: 0.75rem 1rem;
}

.button--link {
  padding: 0;
  background-color: transparent;
  color: var(--first-color);
}

.button--link:hover {
  background-color: transparent;
  color: var(--first-color-alt);
}

/*=========================================================*/
/*========================= ABOUT =========================*/
/*=========================================================*/
.about__img {
  width: 200px;
  border-radius: 0.5rem;
  justify-self: center;
  align-self: center;
}

.about__description {
  text-align: center;
  margin-bottom: var(--mb-2-5);
}
.about__info {
  display: flex;
  justify-content: space-evenly;
  margin-bottom: var(--mb-2-5);
}

.about__info-title {
  font-size: var(--h2-font-size);
  font-weight: var(--font-semi-bold);
  color: var(--title-color);
}

.about__info-name {
  font-size: var(--small-font-size);
}

.about__info-title,
.about__info-name {
  display: block;
}

.about__buttons {
  display: flex;
  justify-content: center;
}

/*=========================================================*/
/*========================= SKILLS ========================*/
/*=========================================================*/
.skills__container {
  row-gap: 0;
}

.skills__header {
  display: flex;
  align-items: center;
  margin-bottom: var(--mb-2-5);
  cursor: pointer;
}

.skills__icon,
.skills__arrow {
  font-size: 2rem;
  color: var(--first-color);
}

.skills__icon {
  margin-right: var(--mb-0-75);
}

.skills__title {
  font-size: var(--h3-font-size);
}

.skills__subtitle {
  font-size: var(--small-font-size);
  color: var(--text-color-light);
}

.skills__arrow {
  margin-left: auto;
  transition: 0.4s;
}

.skills__list {
  row-gap: 1.5rem;
  padding-left: 2.7rem;
}

.skills__titles {
  display: flex;
  justify-content: space-between;
  margin-bottom: var(--mb-0-5);
}

.skills__name {
  font-size: var(--normal-font-size);
  font-weight: var(--font-medium);
}

.skills__bar,
.skills__percentage {
  height: 5px;
  border-radius: 0.25rem;
}

.skills__bar {
  background-color: var(--first-color-lighter);
}

.skills__percentage {
  display: block;
  background-color: var(--first-color);
}

.skills__close .skills__list {
  height: 0;
  overflow: hidden;
}

.skills__open .skills__list {
  height: max-content;
  margin-bottom: var(--mb-2-5);
}

.skills__open .skills__arrow {
  transform: rotate(-180deg);
}
/*=========== Skill 1 =============*/

.skills__html {
  width: 90%;
}
.skills__css {
  width: 60%;
}
.skills__js {
  width: 80%;
}
.skills__jquery {
  width: 60%;
}
.skills__bootstrap {
  width: 90%;
}
.skills__angular {
  width: 55%;
}
.skills__vue {
  width: 75%;
}
/*=========== Skill 2 =============*/

.skills__php {
  width: 60%;
}
.skills__sql {
  width: 70%;
}
.skills__laravel {
  width: 65%;
}
.skills__nosql {
  width: 50%;
}
.skills__node {
  width: 40%;
}
/*=========== Skill 3 =============*/

.skills__git {
  width: 70%;
}
.skills__linux {
  width: 90%;
}

/*=========================================================*/
/*===================== QUALIFICATION =====================*/
/*=========================================================*/
.qualification__tabs {
  display: flex;
  justify-content: space-evenly;
  margin-bottom: var(--mb-2);
}

.qualification__button {
  font-size: var(--h3-font-size);
  font-weight: var(--font-medium);
  cursor: pointer;
}

.qualification__button:hover {
  color: var(--first-color);
}

.qualification__icon {
  font-size: 1.8rem;
  margin-right: var(--mb-0-25);
}

.qualification__data {
  display: grid;
  grid-template-columns: 1fr max-content 1fr;
  column-gap: 1.5rem;
}

.qualification__title {
  font-size: var(--normal-font-size);
  font-weight: var(--font-medium);
}

.qualification__subtitle {
  display: inline-block;
  font-size: var(--small-font-size);
  margin-bottom: var(--mb-1);
}

.qualification__calendar {
  font-size: var(--small-font-size);
  color: var(--text-color-light);
}

.qualification__rounder {
  display: inline-block;
  width: 13px;
  height: 13px;
  background-color: var(--first-color);
  border-radius: 50%;
}

.qualification__line {
  display: block;
  width: 1px;
  height: 100%;
  background-color: var(--first-color);
  transform: translate(6px, -7px);
}

.qualification [data-content] {
  display: none;
}

.qualification__active[data-content] {
  display: block;
}

.qualification__button.qualification__active {
  color: var(--first-color);
}

/*=========================================================*/
/*======================== SERVICES =======================*/
/*=========================================================*/
.services__container {
  gap: 1.5rem;
  grid-template-columns: repeat(2, 1fr);
}

.services__content {
  position: relative;
  background-color: var(--container-color);
  padding: 3.5em 0.5rem 1.25rem 1.5rem;
  border-radius: 0.25rem;
  box-shadow: 0 2px 4px rgba(0, 0, 0, 0.15);
  transition: var(--main-transition);
}

.services__content:hover {
  box-shadow: 0 4px 8px rgba(0, 0, 0, 0.15);
}

.services__icon {
  display: block;
  font-size: 1.5rem;
  color: var(--first-color);
  margin-bottom: var(--mb-1);
}

.services__title {
  font-size: var(--h3-font-size);
  margin-bottom: var(--mb-1);
  font-weight: var(--font-medium);
}

.services__button {
  cursor: pointer;
  font-size: var(--small-font-size);
}

.services__button:hover .button__icon {
  transform: translateX(0.25rem);
}

.services__modal {
  position: fixed;
  top: 0;
  left: 0;
  right: 0;
  bottom: 0;
  background-color: rgba(0, 0, 0, 0.5);
  display: flex;
  align-items: center;
  justify-content: center;
  padding: 0 1rem;
  z-index: var(--z-modal);
  opacity: 0;
  visibility: hidden;
  transition: var(--main-transition);
}

.services__modal-content {
  position: relative;
  background-color: var(--container-color);
  padding: 1.5rem;
  border-radius: 0.5rem;
}

.services__modal-services {
  row-gap: 1rem;
}

.services__modal-service {
  display: flex;
}

.services__modal-title {
  font-size: var(--h3-font-size);
  font-weight: var(--font-medium);
  margin-bottom: var(--mb-1-5);
}

.services__modal-close {
  position: absolute;
  top: 1rem;
  right: 1rem;
  font-size: 1.5rem;
  color: var(--first-color);
  cursor: pointer;
}

.services__modal-icon {
  color: var(--first-color);
  margin-right: var(--mb-0-25);
}

/* Active Modal */
.active-modal {
  opacity: 1;
  visibility: visible;
}

/*=========================================================*/
/*======================= PORTFOLIO =======================*/
/*=========================================================*/
.portfolio__container {
  overflow: initial;
}

.portfolio__content {
  padding: 0 1.5rem;
}

.portfolio__img {
  width: 256px;
  border-radius: 0.5rem;
  justify-self: center;
}

.portfolio__title {
  font-size: var(--h3-font-size);
  margin-bottom: var(--mb-0-5);
}

.portfolio__description {
  margin-bottom: var(--mb-0-75);
}

.portfolio__button:hover .button__icon {
  transform: translateX(0.25rem);
}

.swiper-button-prev::after,
.swiper-button-next::after {
  content: '';
}

.swiper-portfolio-icon {
  font-size: 2rem;
  color: var(--first-color);
}

.swiper-button-prev {
  left: -0.5rem;
}

.swiper-button-next {
  right: -0.5rem;
}

.swiper-container-horizontal > .swiper-pagination-bullets {
  bottom: -2.5rem;
  color: var(--first-color);
}

.swiper-button-prev,
.swiper-button-next,
.swiper-pagination-bullet {
  outline: none;
}

/*========= PORTFOLIO BUTTONS UPDATE =========*/
.portfolio__footer {
  display: flex;
  justify-content: space-between;
  align-items: flex-end;
  flex-wrap: wrap;
}

.portfolio__tech {
  display: flex;
  width: fit-content;
  border: 1px solid hsl(0, 0%, 78%);
  border-radius: 0.25rem;
  padding: 0.25rem 1rem;
  margin-bottom: var(--mb-0-25);
}

.portfolio__buttons {
  display: flex;
  flex-direction: column;
}

.portfolio__button:nth-child(2) {
  background-color: transparent;
  border: 1px solid var(--first-color);
  color: var(--first-color);
  margin-top: var(--mb-0-25);
}

.portfolio__button:nth-child(2):hover {
  background-color: var(--input-color);
}

/*=========================================================*/
/*==================== PROJECT IN MIND ====================*/
/*=========================================================*/
.project {
  text-align: center;
}

.project__bg {
  background-color: var(--first-color-second);
  padding-top: 3rem;
}
.project__title {
  font-size: var(--h2-font-size);
  margin-bottom: var(--mb-0-75);
  color: #fff;
}

.project__description {
  margin-bottom: var(--mb-1-5);
}

.project__title,
.project__description {
  color: #fff;
}

.project__img {
  width: 200px;
  justify-self: center;
}

/*=========================================================*/
/*==================== TESTIMONIAL ========================*/
/*=========================================================*/
.testimonial__data,
.testimonial__header {
  display: flex;
}

.testimonial__data {
  justify-content: space-between;
  margin-bottom: var(--mb-1);
}

.testimonial__img {
  width: 60px;
  height: 60px;
  border-radius: 50%;
  margin-right: var(--mb-0-75);
}

.testimonial__name {
  font-size: var(--h3-font-size);
  font-weight: var(--font-medium);
}

.testimonial__client {
  font-size: var(--small-font-size);
  color: var(--text-color-light);
}

.testimonial__description {
  margin-bottom: var(--mb-2-5);
}

.testimonial__icon-star {
  color: var(--first-color);
}

.swiper-container .swiper-pagination-testimonial {
  bottom: 0;
}
/*=========================================================*/
/*==================== CONTACT ME =========================*/
/*=========================================================*/
.contact__container {
  row-gap: 3rem;
}

.contact__information {
  display: flex;
  margin-bottom: var(--mb-2);
}

.contact__icon {
  font-size: 2rem;
  color: var(--first-color);
  margin-right: var(--mb-0-75);
}

.contact__title {
  font-size: var(--h3-font-size);
  font-weight: var(--font-medium);
}

.contact__subtitle {
  font-size: var(--small-font-size);
  color: var(--text-color-light);
}

.contact__content {
  background-color: var(--input-color);
  border-radius: 0.5rem;
  padding: 0.75rem 1rem 0.25rem;
}

.contact__label {
  font-size: var(--small-font-size);
  color: var(--title-color);
}
.contact__input {
  width: 100%;
  background-color: var(--input-color);
  color: var(--text-color);
  font-family: var(--body-font);
  font-size: var(--normal-font-size);
  border: none;
  outline: none;
  padding: 0.25rem 0.5rem 0.5rem 0;
  border-bottom: 1px solid var(--first-color-lighter);
}

/*=========================================================*/
/*==================== FOOTER =============================*/
/*=========================================================*/
.footer {
  padding-top: 2rem;
}

.footer__container {
  row-gap: 3.5rem;
}

.footer__bg {
  background-color: var(--first-color-second);
  padding: 2rem 0 3rem;
}

.footer__title {
  font-size: var(--h1-font-size);
  margin-bottom: var(--mb-0-25);
}

.footer__subtitle {
  font-size: var(--small-font-size);
}

.footer__links {
  display: flex;
  flex-direction: column;
  row-gap: 1.5rem;
}

.footer__link:hover {
  color: var(--first-color-lighter);
}

.footer__social {
  font-size: 1.25rem;
  margin-right: var(--mb-1-5);
}

.footer__social:hover {
  color: var(--first-color-lighter);
}

.footer__copy {
  font-size: var(--smaller-font-size);
  text-align: center;
  color: var(--text-color);
  margin-top: var(--mb-3);
}

.footer__title,
.footer__subtitle,
.footer__link,
.footer__social {
  color: #fff;
}
/*=========================================================*/
/*======================= SCROLL UP =======================*/
/*=========================================================*/
.scrollup {
  position: fixed;
  right: 1rem;
  bottom: -20%;
  background-color: var(--first-color);
  opacity: 0.8;
  padding: 0 0.3rem;
  border-radius: 0.4rem;
  z-index: var(--z-tooltip);
  transition: var(--main-transition);
}

.scrollup__icon {
  font-size: 1.5rem;
  color: #fff;
}
/* Show scroll */
.show-scroll {
  bottom: 5rem;
}

/*=========================================================*/
/*======================= SCROLL BAR ======================*/
/*=========================================================*/
::-webkit-scrollbar {
  width: 0.5rem;
  background-color: var(--scroll-bar-color);
  border-radius: 0.5rem;
}
::-webkit-scrollbar-thumb {
  background-color: var(--scroll-thumb-color);
  border-radius: 0.5rem;
}

::-webkit-scrollbar-thumb:hover {
  background-color: var(--text-color-light);
}
/*=========================================================*/
/*===================== MEDIA QUERIES =====================*/
/*=========================================================*/
/* For small devices */
@media screen and (max-width: 350px) {
  .container {
    margin-left: var(--mb-1);
    margin-right: var(--mb-1);
  }

  .nav__menu {
    padding: 2rem 0.25rem 4rem;
  }

  .nav__list {
    column-gap: 0;
  }

  .contact__content {
    grid-template-columns: 0.25fr 3fr;
  }

  .home__blob {
    width: 180px;
  }

  .skills__title {
    font-size: var(--normal-font-size);
  }

  .qualification__data {
    gap: 0.5rem;
  }

  .services__container {
    grid-template-columns: max-content;
    justify-content: center;
  }

  .services__content {
    padding-right: 3.5rem;
  }

  .services__modal {
    padding: 0 0.5rem;
  }

  .testimonial__data,
  .testimonial__header {
    flex-direction: column;
    align-items: center;
  }

  .testimonial__img {
    margin-right: 0;
    margin-bottom: var(--mb-0-25);
  }

  .testimonial__data,
  .testimonial__description {
    text-align: center;
  }
}

/* For medium devices */
@media screen and (min-width: 568px) {
  .home__content {
    grid-template-columns: max-content 1fr 1fr;
  }

  .home__data {
    grid-column: initial;
  }

  .home__img {
    order: 1;
    justify-self: center;
  }

  .about__container,
  .skills__container,
  .portfolio__container,
  .contact__container,
  .footer__container {
    grid-template-columns: repeat(2, 1fr);
  }

  .qualification__sections {
    display: grid;
    grid-template-columns: 0.6fr;
    justify-content: center;
  }
}
@media screen and (min-width: 768px) {
  .container {
    margin-left: auto;
    margin-right: auto;
  }

  body {
    margin: 0;
  }

  .section {
    padding: 6rem 0 2rem;
  }

  .section__subtitle {
    margin-bottom: 4rem;
  }

  .header {
    top: 0;
    bottom: initial;
  }

  .header,
  .main,
  .footer__container {
    padding: 0 1rem;
  }

  .nav {
    height: calc(var(--header-height) + 1.5rem);
    column-gap: 1rem;
  }

  .nav__icon,
  .nav__close,
  .nav__toggle {
    display: none;
  }

  .nav__list {
    display: flex;
    column-gap: 2rem;
  }

  .nav__menu {
    margin-left: auto;
  }

  .change-theme {
    margin: 0;
  }

  .home__container {
    row-gap: 5rem;
  }

  .home__content {
    padding-top: 5.5rem;
    column-gap: 2rem;
  }

  .home__blob {
    width: 270px;
  }

  .home__scroll {
    display: block;
  }

  .home__scroll-button {
    margin-left: 3rem;
  }

  .about__container {
    column-gap: 5rem;
  }

  .about__img {
    width: 350px;
  }

  .about__description {
    text-align: initial;
  }

  .about__info {
    justify-content: space-between;
  }

  .qualification__tabs {
    justify-content: center;
  }

  .qualification__button {
    margin: 0 var(--mb-1);
  }

  .qualification__sections {
    grid-template-columns: 0.5fr;
  }

  .services__container {
    grid-template-columns: repeat(2, 1fr);
    justify-content: center;
  }

  .services__icon {
    font-size: 2rem;
  }

  .services__content {
    padding: 6rem 0 2rem 2.5rem;
  }

  .services__modal-content {
    width: 450px;
  }

  .portfolio__img {
    width: 320px;
  }

  .portfolio__content {
    align-items: center;
  }

  .project {
    text-align: initial;
  }

  .project__bg {
    background: none;
  }

  .project__container {
    background-color: var(--first-color-second);
    border-radius: 1rem;
    padding: 3rem 2.5rem;
    grid-template-columns: 1fr max-content;
    column-gap: 3rem;
  }

  .project__data {
    padding-top: 0.8rem;
  }

  .footer__container {
    grid-template-columns: repeat(3, 1fr);
  }

  .footer__bg {
    padding: 3rem 0 3.5rem;
  }
  .footer__links {
    flex-direction: row;
    column-gap: 2rem;
  }

  .footer__socials {
    justify-self: flex-end;
  }

  .footer__copy {
    margin-top: 4.5rem;
  }
}
/* For large devices */

@media screen and (min-width: 1024px) {
  .header,
  .main,
  .footer__container {
    padding: 0;
  }

  .home__blob {
    width: 320px;
  }
  .home__social {
    transform: translateX(-6rem);
  }

  .services__container {
    grid-template-columns: repeat(2, 1fr);
  }

  .portfolio__content {
    column-gap: 5rem;
  }

  .swiper-portfolio-icon {
    font-size: 3.5rem;
  }

  .swiper-button-prev {
    left: -3.5rem;
  }

  .swiper-button-next {
    right: -3.5rem;
  }

  .swiper-container-horizontal > .swiper-pagination-bullets {
    bottom: -4.5rem;
  }

  .contact__form {
    width: 460px;
  }

  .contact__inputs {
    grid-template-columns: repeat(2, 1fr);
  }
}
</style>
