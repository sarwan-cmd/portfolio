<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="theme-color" content="#09080d">
  <meta name="description" content="The personal portfolio of Sarwan Adithya K, an aspiring web developer.">
  <title>SARWAN ADITHYA K — Web Developer</title>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=DM+Mono:wght@400;500&family=Space+Grotesk:wght@400;500;600;700&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="style.css">
</head>
<body>
  <a class="skip-link" href="#main">Skip to content</a>

  <div class="boot-screen" id="boot-screen" aria-label="Loading portfolio">
    <div class="boot-screen__content">
      <p class="eyebrow">PERSONAL PORTFOLIO // SYSTEM BOOT</p>
      <h1>SARWAN <span>ADITHYA K</span></h1>
      <div class="boot-track" role="progressbar" aria-label="Loading" aria-valuemin="0" aria-valuemax="100">
        <span class="boot-track__fill"></span>
      </div>
      <p class="boot-status" aria-live="polite">INITIALIZING INTERFACE <span>...</span></p>
      <button class="boot-skip" id="skip-boot" type="button">SKIP INTRO <span aria-hidden="true">↗</span></button>
    </div>
    <div class="boot-screen__grid" aria-hidden="true"></div>
  </div>

  <header class="site-header">
    <button class="menu-toggle" id="menu-toggle" type="button" aria-label="Open navigation menu" aria-expanded="false" aria-controls="primary-nav">
      <span></span><span></span>
    </button>
    <nav class="site-nav" id="primary-nav" aria-label="Main navigation">
      <a class="site-nav__link is-active" href="#home">HOME</a>
      <a class="site-nav__link" href="#skills">SKILLS</a>
      <a class="site-nav__link" href="#contact">CONTACT</a>
      <span class="nav-indicator" aria-hidden="true"></span>
    </nav>
    <a class="header-status" href="#contact"><span class="status-pulse"></span> AVAILABLE TO CONNECT</a>
  </header>

  <main id="main">
    <section class="hero section-shell" id="home" aria-labelledby="hero-title">
      <div class="hero__scanline" aria-hidden="true"></div>
      <div class="hero__copy">
        <p class="eyebrow hero__eyebrow"><span class="eyebrow__line"></span> INDEPENDENT MIND // DIGITAL WORLD</p>
        <p class="hero__intro">Hello, I'm</p>
        <h1 class="hero__title glitch" id="hero-title" data-text="SARWAN ADITHYA K">SARWAN<br><span>ADITHYA K</span></h1>
        <div class="hero__actions">
          <a class="button button--primary" href="#skills"><span>EXPLORE MY SKILLS</span><span class="button__arrow" aria-hidden="true">↗</span></a>
          <a class="button button--ghost" href="#contact"><span>CONTACT ME</span><span class="button__arrow" aria-hidden="true">↗</span></a>
        </div>
      </div>

      <div class="hero-art" aria-label="Abstract neon portal artwork">
        <div class="hero-art__label hero-art__label--top"><span>FIG. 001</span><span>THE CREATIVE ENGINE</span></div>
        <div class="hero-art__sun"></div>
        <div class="hero-art__orbit hero-art__orbit--one"></div>
        <div class="hero-art__orbit hero-art__orbit--two"></div>
        <div class="hero-art__orbit hero-art__orbit--three"></div>
        <div class="hero-art__core"><span>S</span><i></i></div>
        <div class="hero-art__cross hero-art__cross--one">+</div>
        <div class="hero-art__cross hero-art__cross--two">+</div>
        <div class="hero-art__side-code" aria-hidden="true">0101<br>1010<br>0110</div>
        <div class="hero-art__label hero-art__label--bottom"><span>IDEAS IN MOTION</span><span class="signal-bars"><i></i><i></i><i></i><i></i></span></div>
        <div class="hero-art__corner hero-art__corner--tl"></div><div class="hero-art__corner hero-art__corner--br"></div>
      </div>
      <a class="scroll-cue" href="#skills"><span class="scroll-cue__line"></span> SCROLL TO EXPLORE</a>
      <span class="hero__index" aria-hidden="true">01 — 03</span>
    </section>

    <section class="section-shell skills section-pad" id="skills" aria-labelledby="skills-title">
      <div class="section-heading reveal">
        <p class="eyebrow"><span class="section-number">01</span> THE TOOLS I'M LEARNING</p>
        <h2 id="skills-title">MY TECH <span class="text-accent">STACK.</span></h2>
      </div>
      <div class="skills__grid">
        <article class="skill-card reveal">
          <div class="skill-card__top"><span>01 / STRUCTURE</span><span class="skill-card__corner" aria-hidden="true">↗</span></div>
          <div class="skill-card__visual skill-card__visual--html" aria-hidden="true"><span>&lt;</span><i>/</i><b>&gt;</b></div>
          <h3>HTML</h3>
          <p>Building the meaningful structure behind every page with semantic markup.</p>
          <div class="skill-card__footer"><span>FOUNDATION</span><span class="skill-card__meter"><i></i><i></i><i></i><i></i><i></i></span></div>
        </article>
        <article class="skill-card reveal">
          <div class="skill-card__top"><span>02 / PRESENTATION</span><span class="skill-card__corner" aria-hidden="true">↗</span></div>
          <div class="skill-card__visual skill-card__visual--css" aria-hidden="true"><span>{</span><i>✳</i><b>}</b></div>
          <h3>CSS</h3>
          <p>Exploring layouts, color and motion to shape expressive, responsive interfaces.</p>
          <div class="skill-card__footer"><span>FOUNDATION</span><span class="skill-card__meter"><i></i><i></i><i></i><i></i><i></i></span></div>
        </article>
        <article class="skill-card reveal">
          <div class="skill-card__top"><span>03 / INTERACTION</span><span class="skill-card__corner" aria-hidden="true">↗</span></div>
          <div class="skill-card__visual skill-card__visual--js" aria-hidden="true"><span>JS</span><i></i></div>
          <h3>JAVASCRIPT</h3>
          <p>Learning to bring pages to life with logic, useful interactions and functionality.</p>
          <div class="skill-card__footer"><span>FOUNDATION</span><span class="skill-card__meter"><i></i><i></i><i></i><i></i><i></i></span></div>
        </article>
      </div>
    </section>

    <section class="section-shell contact section-pad" id="contact" aria-label="Contact information">
      <div class="contact__backdrop" aria-hidden="true"></div>
      <div class="contact__methods reveal">
        <a class="contact-method" href="mailto:sarwanadithya47@gmail.com">
          <span class="contact-method__label">EMAIL</span>
          <span class="contact-method__value">sarwanadithya47@gmail.com</span>
          <span class="contact-method__arrow" aria-hidden="true">↗</span>
        </a>
        <a class="contact-method" href="tel:+918015452555">
          <span class="contact-method__label">PHONE</span>
          <span class="contact-method__value">+91 8015455255</span>
          <span class="contact-method__arrow" aria-hidden="true">↗</span>
        </a>
      </div>
    </section>
  </main>

  <footer class="site-footer">
    <p>DESIGNED IN THE PRESENT. BUILT FOR WHAT'S NEXT.<br><span>© <span id="current-year">2026</span> SARWAN ADITHYA K — ALL RIGHTS RESERVED.</span></p>
    <a class="back-to-top" href="#home" aria-label="Back to top">BACK TO TOP <span aria-hidden="true">↑</span></a>
  </footer>

  <div class="custom-cursor" id="custom-cursor" aria-hidden="true"><span class="custom-cursor__ring"></span><span class="custom-cursor__dot"></span><span class="custom-cursor__trail"></span></div>

  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/gsap.min.js" defer></script>
  <script src="https://cdnjs.cloudflare.com/ajax/libs/gsap/3.12.5/ScrollTrigger.min.js" defer></script>
  <script src="https://unpkg.com/lenis@1.1.20/dist/lenis.min.js" defer></script>
  <script src="script.js" defer></script>
</body>
</html>
