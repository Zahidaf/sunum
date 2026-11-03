<!DOCTYPE html>
<html lang="tr">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Hannah Arendt — Felsefe Sunumu</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=DM+Mono&family=Manrope:wght@400;500;600&family=Playfair+Display:ital,wght@0,400;0,500;0,600;1,400;1,500&display=swap');

:root {
  --bg: #211a16;
  --paper: #f3e9dc;
  --muted: #c4b3a0;
  --accent: #d8a47c;
  --line: rgba(243, 233, 220, .2);
  --nav-h: 56px;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html, body {
  height: 100%;
  overflow: hidden;
}

body {
  background: var(--bg);
  color: var(--paper);
  font-family: 'Manrope', Georgia, serif;
}

/* ===================================
   DECK & NAVIGASI
=================================== */

.deck {
  position: relative;
  width: 100%;
  height: calc(100vh - var(--nav-h));
  height: calc(100svh - var(--nav-h));
  overflow: hidden;
}

.nav {
  position: fixed;
  left: 0;
  right: 0;
  bottom: 0;
  height: var(--nav-h);
  z-index: 100;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 16px;
  padding: 0 6%;
  background: rgba(20, 14, 11, .96);
  border-top: 1px solid var(--line);
}

.nav-btn {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  min-width: 112px;
  padding: 10px 18px;
  background: transparent;
  color: var(--paper);
  border: 1px solid var(--line);
  font: 10px "DM Mono", monospace;
  letter-spacing: 2px;
  text-transform: uppercase;
  cursor: pointer;
  transition: background .2s, border-color .2s, color .2s, opacity .2s;
}

.nav-btn.next {
  justify-content: flex-end;
}

.nav-btn:hover:not(:disabled) {
  background: rgba(216, 164, 124, .12);
  border-color: var(--accent);
  color: var(--accent);
}

.nav-btn:disabled {
  opacity: .3;
  cursor: not-allowed;
}

.nav-center {
  display: flex;
  align-items: center;
  gap: 18px;
}

.dots {
  display: flex;
  gap: 10px;
}

.dot {
  width: 9px;
  height: 9px;
  padding: 0;
  border-radius: 50%;
  border: 1px solid var(--accent);
  background: transparent;
  cursor: pointer;
  transition: background .2s, transform .2s;
}

.dot.active {
  background: var(--accent);
  transform: scale(1.25);
}

.counter {
  font: 10px "DM Mono", monospace;
  letter-spacing: 2px;
  color: var(--muted);
}

.progress {
  position: fixed;
  left: 0;
  bottom: var(--nav-h);
  height: 2px;
  width: 20%;
  background: var(--accent);
  z-index: 101;
  transition: width .5s ease;
}

/* ===================================
   SLIDE UMUM & LAYOUT
=================================== */

.slide {
  position: absolute;
  inset: 0;
  width: 100%;
  height: 100%;
  overflow-x: hidden;
  overflow-y: auto;
  background: var(--bg);
  display: flex;
  flex-direction: column;
  justify-content: space-between;
  opacity: 0;
  visibility: hidden;
  transform: translateX(40px);
  transition: opacity .55s ease, transform .55s ease, visibility 0s linear .55s;
}

.slide.active {
  opacity: 1;
  visibility: visible;
  transform: translateX(0);
  transition: opacity .55s ease, transform .55s ease, visibility 0s;
  z-index: 2;
}

.slide.before {
  transform: translateX(-40px);
}

.back1,
.back2,
.back3,
.back4 {
  position: absolute;
  inset: 0;
  background-size: cover;
  background-position: center;
  background-repeat: no-repeat;
  z-index: 0;
}

.back1 {
  background-image: url("https://lh3.googleusercontent.com/d/1TYknhVPJxEL2ebYB98mFDbNQxTmtDRn7=w1600");
}

.back2,
.back3,
.back4 {
  background-image: url("https://lh3.googleusercontent.com/d/1_fmzykryq_5opHyfrXKYM7N142Qqoac7=w1600");
}

/* Gradasi Slide 1 (Gelap di Kanan) */
.overlay {
  position: absolute;
  inset: 0;
  z-index: 1;
  background: linear-gradient(
    270deg,
    rgba(25, 18, 14, .92) 0%,
    rgba(25, 18, 14, .72) 50%,
    rgba(25, 18, 14, .10) 100%
  );
}

/* Gradasi Klasik Lembut untuk Slide 3 & 4 */
.overlay-classic {
  position: absolute;
  inset: 0;
  z-index: 1;
  background: rgba(28, 21, 17, .88);
}

.content {
  position: relative;
  z-index: 2;
}

.slide-padding {
  padding: 38px 6% 35px;
}

.topbar {
  position: relative;
  z-index: 2;
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 15px;
  padding-bottom: 18px;
  border-bottom: 1px solid var(--line);
  font: 10px "DM Mono", monospace;
  letter-spacing: 2px;
  color: var(--muted);
}

.topbar strong {
  color: var(--accent);
  font-weight: normal;
}

.section-label {
  font: 10px "DM Mono", monospace;
  color: var(--accent);
  text-transform: uppercase;
  letter-spacing: 3px;
  margin-bottom: 14px;
}

.footer {
  position: relative;
  z-index: 2;
  display: flex;
  justify-content: space-between;
  gap: 20px;
  border-top: 1px solid var(--line);
  margin-top: 25px;
  padding-top: 15px;
  font: 9px "DM Mono", monospace;
  letter-spacing: 1.5px;
  color: var(--muted);
}

/* ===================================
   SLIDE 1 — HERO (TEKS DI KANAN)
=================================== */

.hero {
  justify-content: center;
  align-items: flex-end;
  padding: 8%;
}

.hero-content {
  width: min(100%, 620px);
  margin-left: auto;
}

.label {
  font-family: "DM Mono", monospace;
  text-transform: uppercase;
  letter-spacing: 4px;
  font-size: 11px;
  color: var(--accent);
  margin-bottom: 30px;
}

.hero h1 {
  font-family: "Playfair Display", Georgia, serif;
  font-size: clamp(65px, 10vw, 140px);
  line-height: .88;
  letter-spacing: -5px;
  margin-bottom: 30px;
}

.hero h1 span {
  display: inline-block;
  color: var(--accent);
  font-style: italic;
  font-weight: 500;
}

.subtitle {
  max-width: 550px;
  font-size: clamp(15px, 1.6vw, 20px);
  line-height: 1.8;
  color: #e2d5c7;
}

.author {
  margin-top: 45px;
  padding-top: 20px;
  border-top: 1px solid var(--line);
  font-size: 12px;
  letter-spacing: 2px;
  color: var(--muted);
}

.slide-number {
  position: absolute;
  right: 35px;
  bottom: 25px;
  z-index: 4;
  font: 11px "DM Mono", monospace;
  letter-spacing: 2px;
}

/* ===================================
   SLIDE 2 — BIOGRAFI & PENDIDIKAN
=================================== */

.biography {
  background:
    radial-gradient(ellipse at 100% 0%, #493022 0%, transparent 50%),
    var(--bg);
}

.bio-grid {
  display: grid;
  grid-template-columns: 1.1fr .9fr;
  gap: 40px;
  align-items: center;
  padding: 32px 0;
}

.bio-text {
  max-width: 650px;
}

.bio-text h2 {
  font-family: "Playfair Display", Georgia, serif;
  font-size: clamp(40px, 5vw, 70px);
  font-weight: 500;
  line-height: .98;
  letter-spacing: -2px;
  margin-bottom: 22px;
}

.bio-text h2 em {
  color: var(--accent);
  font-weight: 500;
}

.bio-description {
  max-width: 530px;
  color: var(--muted);
  font-size: 13px;
  line-height: 1.9;
  margin-bottom: 22px;
}

.bio-facts {
  display: grid;
  grid-template-columns: 1fr 1fr;
  gap: 16px;
}

.fact {
  border-top: 1px solid var(--line);
  padding-top: 12px;
}

.fact span {
  display: block;
  font: 9px "DM Mono", monospace;
  letter-spacing: 1.5px;
  color: var(--accent);
  text-transform: uppercase;
  margin-bottom: 7px;
}

.fact p {
  font-size: 12px;
  line-height: 1.7;
  color: var(--paper);
}

.map-panel {
  position: relative;
  min-width: 0;
}

.map-heading {
  display: flex;
  justify-content: space-between;
  align-items: center;
  gap: 12px;
  margin-bottom: 12px;
}

.map-heading h3 {
  font-size: 13px;
  font-weight: 600;
}

.map-heading span {
  font: 9px "DM Mono", monospace;
  color: var(--accent);
  letter-spacing: 1px;
}

.map-frame {
  width: 100%;
  height: 290px;
  display: block;
  border: 1px solid rgba(216, 164, 124, .35);
  filter: sepia(.15);
}

.map-caption {
  padding-top: 12px;
  display: flex;
  justify-content: space-between;
  gap: 12px;
  font-size: 10px;
  color: var(--muted);
}

.education {
  border-top: 1px solid var(--line);
  padding-top: 25px;
}

.education-heading {
  display: flex;
  align-items: end;
  justify-content: space-between;
  gap: 20px;
  margin-bottom: 18px;
}

.education-heading h3 {
  font-family: "Playfair Display", Georgia, serif;
  font-size: clamp(25px, 3vw, 38px);
  font-weight: 500;
}

.education-heading p {
  font-size: 10px;
  color: var(--muted);
  max-width: 240px;
  line-height: 1.6;
  text-align: right;
}

.university-grid {
  display: grid;
  grid-template-columns: repeat(3, minmax(0, 1fr));
  gap: 16px;
}

.university-card {
  min-width: 0;
  border: 1px solid var(--line);
  background: rgba(255, 255, 255, .025);
}

.university-photo {
  height: 145px;
  position: relative;
  overflow: hidden;
  background: #473226;
}

.university-photo img {
  display: block;
  width: 100%;
  height: 100%;
  object-fit: cover;
  filter: sepia(.25) brightness(.78);
}

.university-info {
  padding: 15px 16px 17px;
}

.year {
  font: 10px "DM Mono", monospace;
  color: var(--accent);
  letter-spacing: 1px;
  margin-bottom: 8px;
}

.university-info h4 {
  font-size: clamp(14px, 1.5vw, 19px);
  line-height: 1.4;
  margin-bottom: 8px;
}

.university-info p {
  font-size: 11px;
  line-height: 1.75;
  color: var(--muted);
}

/* ===================================
   SLIDE 3 — KLASIK & SEDERHANA (BANALITY OF EVIL)
=================================== */

.classic-layout {
  display: grid;
  grid-template-columns: 320px 1fr;
  gap: 60px;
  align-items: center;
  margin: auto 0;
  padding: 30px 0;
}

.portrait-figure {
  margin: 0;
}

.portrait-figure img {
  width: 100%;
  height: 360px;
  object-fit: cover;
  display: block;
  filter: grayscale(100%) sepia(18%) contrast(1.05);
  border: 1px solid var(--line);
}

.portrait-figure figcaption {
  margin-top: 12px;
  font-family: "Playfair Display", Georgia, serif;
  font-style: italic;
  font-size: 13px;
  color: var(--muted);
  text-align: center;
}

.classic-text h2.main-heading {
  font-family: "Playfair Display", Georgia, serif;
  font-size: clamp(38px, 4.5vw, 58px);
  font-weight: 400;
  line-height: 1.05;
  margin-bottom: 16px;
}

.classic-text h2.main-heading em {
  color: var(--accent);
  font-style: italic;
}

.classic-lead {
  font-family: "Playfair Display", Georgia, serif;
  font-size: 17px;
  line-height: 1.75;
  color: var(--paper);
  max-width: 620px;
  margin-bottom: 32px;
}

.kronologi-heading {
  font-family: "Playfair Display", Georgia, serif;
  font-size: 24px;
  font-weight: 400;
  font-style: italic;
  color: var(--accent);
  margin-bottom: 14px;
  padding-bottom: 8px;
  border-bottom: 1px solid var(--line);
}

.simple-timeline {
  list-style: none;
}

.simple-timeline li {
  display: grid;
  grid-template-columns: 75px 1fr;
  gap: 20px;
  padding: 10px 0;
  border-bottom: 1px solid rgba(243, 233, 220, .1);
  font-size: 13px;
  line-height: 1.6;
  color: var(--muted);
}

.simple-timeline li:last-child {
  border-bottom: none;
}

.simple-timeline strong {
  font-family: "DM Mono", monospace;
  font-size: 11px;
  color: var(--paper);
  font-weight: normal;
  letter-spacing: 1px;
}

/* ===================================
   SLIDE 4 — SANGAT SEDERHANA & POLOS (FEMINISME)
=================================== */

.minimal-center {
  max-width: 720px;
  margin: auto;
  text-align: center;
  padding: 40px 0;
}

.minimal-center h2 {
  font-family: "Playfair Display", Georgia, serif;
  font-size: clamp(42px, 5vw, 68px);
  font-weight: 400;
  line-height: 1.08;
  margin-bottom: 24px;
}

.minimal-center h2 em {
  color: var(--accent);
  font-style: italic;
}

.classic-divider {
  width: 60px;
  height: 1px;
  background: var(--accent);
  margin: 0 auto 30px;
}

.dummy-conclusion {
  font-family: "Playfair Display", Georgia, serif;
  font-size: clamp(17px, 1.8vw, 22px);
  line-height: 1.9;
  color: var(--paper);
  font-weight: 400;
  margin-bottom: 24px;
}

.dummy-subtext {
  font-size: 13px;
  line-height: 1.8;
  color: var(--muted);
  max-width: 560px;
  margin: 0 auto;
}

/* ===================================
   SLIDE 5 — REFERENSI
=================================== */

.refs {
  text-align: left;
  max-width: 760px;
}

.refs h2,
.refs .section-label {
  text-align: center;
}

.ref-list {
  list-style: none;
}

.ref-list li {
  display: grid;
  grid-template-columns: 48px 1fr;
  gap: 16px;
  padding: 18px 0;
  border-bottom: 1px solid rgba(243, 233, 220, .1);
}

.ref-list li:last-child {
  border-bottom: none;
}

.ref-no {
  font: 11px "DM Mono", monospace;
  letter-spacing: 1px;
  color: var(--accent);
  padding-top: 4px;
}

.ref-text {
  font-family: "Playfair Display", Georgia, serif;
  font-size: clamp(16px, 1.6vw, 20px);
  line-height: 1.7;
  color: var(--paper);
}

.ref-link {
  display: inline-block;
  margin-top: 8px;
  font: 11px "DM Mono", monospace;
  letter-spacing: 1px;
  color: var(--accent);
  text-decoration: none;
  border-bottom: 1px solid rgba(216, 164, 124, .4);
  word-break: break-all;
}

.ref-link:hover {
  border-bottom-color: var(--accent);
}

/* ===================================
   RESPONSIVE MEDIA QUERIES
=================================== */

@media (max-width: 850px) {
  .hero {
    padding: 9%;
    align-items: flex-start;
  }

  .hero-content {
    margin-left: 0;
  }

  .slide-padding {
    padding: 25px 6% 30px;
  }

  .bio-grid,
  .classic-layout,
  .university-grid {
    grid-template-columns: 1fr;
    gap: 30px;
  }

  .portrait-figure img {
    height: 280px;
  }

  .education-heading {
    align-items: start;
    flex-direction: column;
  }

  .education-heading p {
    text-align: left;
  }

  .footer {
    flex-direction: column;
    gap: 8px;
  }

  .nav-btn {
    min-width: 0;
    padding: 10px 14px;
  }

  .nav-btn .txt,
  .counter {
    display: none;
  }
}
</style>
</head>

<body>

<main class="deck" id="deck">

<!-- ===================================
     SLIDE 1 — PEMBUKA
=================================== -->
<section class="slide hero active">
  <div class="back1"></div>
  <div class="overlay"></div>

  <div class="content hero-content">
    <p class="label">Felsefe · Siyaset · İnsan</p>

    <h1>
      Hannah<br>
      <span>Arendt</span>
    </h1>

    <p class="subtitle">
      İnsanlık durumu, özgürlük ve kamusal yaşam üzerine
      kısa bir anlatım.
    </p>

    <div class="author">
      ZAHID MUHAMAD KEMAL
    </div>
  </div>

  <div class="slide-number">01 / 05</div>
</section>


<!-- ===================================
     SLIDE 2 — BIOGRAFI & PENDIDIKAN
=================================== -->
<section class="slide biography slide-padding">

  <header class="topbar">
    <span>FELSEFE / PORTRELER</span>
    <strong>HANNAH ARENDT</strong>
    <span>1906 — 1975</span>
  </header>

  <div class="content">
    <div class="bio-grid">
      <div class="bio-text">
        <p class="section-label">01 / Erken yaşam</p>
        <h2>
          Hannah<br>
          <em>Arendt.</em>
        </h2>
        <p class="bio-description">
          Almanya doğumlu siyaset düşünürü ve filozof; totalitarizm, insan eylemi, özgürlük ve kamusal yaşam üzerine düşünceleriyle tanınır.
        </p>

        <div class="bio-facts">
          <div class="fact">
            <span>Doğum</span>
            <p>14 Ekim 1906<br>Linden, Hannover, Almanya</p>
          </div>
          <div class="fact">
            <span>Ölüm</span>
            <p>4 Aralık 1975<br>New York, ABD</p>
          </div>
          <div class="fact">
            <span>Köken</span>
            <p>Alman Yahudi ailesi</p>
          </div>
          <div class="fact">
            <span>Alan</span>
            <p>Siyaset felsefesi ve siyaset teorisi</p>
          </div>
        </div>
      </div>

      <aside class="map-panel">
        <div class="map-heading">
          <h3>Doğum Yeri</h3>
          <span>52°22′ N / 9°43′ E</span>
        </div>

        <iframe
          class="map-frame"
          src="https://maps.google.com/maps?q=Linden%2C%20Hannover%2C%20Germany&t=&z=13&ie=UTF8&iwloc=&output=embed"
          title="Linden, Hannover, Almanya haritası"
          loading="lazy"
          referrerpolicy="no-referrer-when-downgrade"
          allowfullscreen>
        </iframe>

        <div class="map-caption">
          <span>Linden · Hannover</span>
          <span>Alman İmparatorluğu, 1906</span>
        </div>
      </aside>
    </div>

    <section class="education">
      <div class="education-heading">
        <div>
          <p class="section-label">02 / Entelektüel yolculuk</p>
          <h3>Bir düşünürün oluşumu.</h3>
        </div>
        <p>
          Hannah Arendt'in düşüncesini şekillendiren akademik yolculuk.
        </p>
      </div>

      <div class="university-grid">
        <article class="university-card">
          <div class="university-photo">
            <img
              src="https://avatars.mds.yandex.net/i?id=e316db3936c52e4b23a07821bcb445c60dc8649b-4607687-images-thumbs&n=13"
              alt="University of Marburg"
              loading="lazy">
          </div>
          <div class="university-info">
            <p class="year">1924 — MARBURG</p>
            <h4>University of Marburg</h4>
            <p>
              Arendt felsefe eğitimine Marburg'da başladı. Orada Martin Heidegger ile tanıştı; Heidegger'in entelektüel gelişimi üzerinde önemli bir etkisi oldu.
            </p>
          </div>
        </article>

        <article class="university-card">
          <div class="university-photo">
            <img
              src="https://avatars.mds.yandex.net/i?id=fa34f741ff3487f0dbc838bd0825d67754b19ac5-4354773-images-thumbs&n=13"
              alt="University of Freiburg"
              loading="lazy">
          </div>
          <div class="university-info">
            <p class="year">1926 — FREIBURG</p>
            <h4>University of Freiburg</h4>
            <p>
              Arendt eğitimine Freiburg'da devam etti. Burada fenomenoloji geleneğinin önemli ismi Edmund Husserl'in derslerine de katıldı.
            </p>
          </div>
        </article>

        <article class="university-card">
          <div class="university-photo">
            <img
              src="https://avatars.mds.yandex.net/i?id=823e0ca743cf5eb46fab634b4d60eeedd8af75a7-5478991-images-thumbs&n=13"
              alt="University of Heidelberg"
              loading="lazy">
          </div>
          <div class="university-info">
            <p class="year">1926 — 1928</p>
            <h4>University of Heidelberg</h4>
            <p>
              Doktorasını Karl Jaspers danışmanlığında tamamladı. Tezi, Aziz Augustinus'un düşüncesinde sevgi kavramını ele alır.
            </p>
          </div>
        </article>
      </div>
    </section>
  </div>

  <footer class="footer">
    <span>HANNAH ARENDT · SİYASAL DÜŞÜNCE</span>
    <span>ZAHID MUHAMAD KEMAL</span>
    <span>02 / 05</span>
  </footer>
</section>


<!-- ===================================
     SLIDE 3 — BANALITY OF EVIL (KLASIK & RINGKAS)
=================================== -->
<section class="slide slide-padding">
  <div class="back3"></div>
  <div class="overlay-classic"></div>

  <header class="topbar">
    <span>FELSEFE / KUDÜS 1961</span>
    <strong>KÖTÜLÜĞÜN SIRADANLIĞI</strong>
    <span>HANNAH ARENDT</span>
  </header>

  <div class="content classic-layout">
    <!-- FOTO ADOLF EICHMANN -->
    <figure class="portrait-figure">
      <img
        src="https://avatars.mds.yandex.net/i?id=b220448c04f8d5a4bfcd30c767faa69d6bc85cfc-5427959-images-thumbs&n=13"
        alt="Adolf Eichmann Kudüs'teki duruşmasında, 1961">
      <figcaption>Adolf Eichmann, Kudüs'teki duruşması sırasında (1961).</figcaption>
    </figure>

    <!-- PENJELASAN SINGKAT & H2 KRONOLOGI -->
    <div class="classic-text">
      <p class="section-label">03 / Anahtar Kavram</p>
      <h2 class="main-heading">Kötülüğün <em>Sıradanlığı.</em></h2>

      <p class="classic-lead">
        Tarihteki büyük kötülükler çoğu zaman bir canavarın fanatizminden değil, eleştirel düşünmeyi bırakmış sıradan bir bürokratın kör itaatinden doğar.
      </p>

      <h2 class="kronologi-heading">Kronoloji</h2>
      <ul class="simple-timeline">
        <li>
          <strong>1960</strong>
          <span>Adolf Eichmann Arjantin'de yakalandı ve İsrail'e götürüldü.</span>
        </li>
        <li>
          <strong>1961</strong>
          <span>Arendt, <em>The New Yorker</em> için Kudüs'teki duruşmayı izledi; aralık ayında Eichmann ölüm cezasına çarptırıldı.</span>
        </li>
        <li>
          <strong>1962</strong>
          <span>Temyiz reddedildi; Eichmann idam edildi.</span>
        </li>
        <li>
          <strong>1963</strong>
          <span><em>Eichmann in Jerusalem: A Report on the Banality of Evil</em> yayımlandı.</span>
        </li>
      </ul>
    </div>
  </div>

  <footer class="footer">
    <span>HANNAH ARENDT · KÖTÜLÜĞÜN SIRADANLIĞI</span>
    <span>ZAHID MUHAMAD KEMAL</span>
    <span>03 / 05</span>
  </footer>
</section>


<!-- ===================================
     SLIDE 4 — FEMINISME (POLOS / KESIMPULAN SENDIRI)
=================================== -->
<section class="slide slide-padding">
  <div class="back4"></div>
  <div class="overlay-classic"></div>

  <header class="topbar">
    <span>FELSEFE / SONUÇ</span>
    <strong>ARENDT VE FEMİNİZM</strong>
    <span>HANNAH ARENDT</span>
  </header>

  <div class="content minimal-center">
    <p class="section-label">04 / Yansıma ve Sonuç</p>
    <h2>Feminizmle <em>İlişkisi.</em></h2>

    <div class="classic-divider"></div>

    <p class="dummy-conclusion">
      Baskıcı bir iktidarı yürüten erkeklerin yanında yaşayan bir kadın, tarihin yalnızca bir seyircisi midir, yoksa bu iktidarı sorgulama konusunda ahlaki bir sorumluluk taşır mı?
    </p>

    <p class="dummy-subtext">
      Susmak, sorumsuzluk anlamına gelir mi?<br>
      Sisteme itaat, bir insanın adaletsizliği görmezden gelmesine yol açabilir mi?<br>
      Biri, düşünme, konuşma ve iktidarı sorgulama cesaretiyle kötülüğü önleyebilir mi?
    </p>
  </div>

  <footer class="footer">
    <span>HANNAH ARENDT · SONUÇ</span>
    <span>ZAHID MUHAMAD KEMAL</span>
    <span>04 / 05</span>
  </footer>
</section>


<!-- ===================================
     SLIDE 5 — REFERENSI
=================================== -->
<section class="slide slide-padding">
  <div class="back4"></div>
  <div class="overlay-classic"></div>

  <header class="topbar">
    <span>FELSEFE / KAYNAKLAR</span>
    <strong>KAYNAKÇA</strong>
    <span>HANNAH ARENDT</span>
  </header>

  <div class="content minimal-center refs">
    <p class="section-label">05 / Kaynak Listesi</p>
    <h2>Kaynak<em>ça.</em></h2>

    <div class="classic-divider"></div>

    <ol class="ref-list">
      <li>
        <span class="ref-no">01</span>
        <div>
          <p class="ref-text">
            Smeulers, A., &amp; Werner, W. (2009). <em>The Banality of Evil on Trial.</em>
          </p>
          <a class="ref-link" href="https://youtu.be/MFMeZ_FmMC0?si=dbS02DFCUthbGPOa" target="_blank" rel="noopener">
            youtu.be/MFMeZ_FmMC0
          </a>
        </div>
      </li>
      <li>
        <span class="ref-no">02</span>
        <div>
          <p class="ref-text">
            Şengel, S. (t.y.). <em>Hannah Arendt.</em>
          </p>
        </div>
      </li>
    </ol>
  </div>

  <footer class="footer">
    <span>HANNAH ARENDT · KAYNAKÇA</span>
    <span>ZAHID MUHAMAD KEMAL</span>
    <span>05 / 05</span>
  </footer>
</section>

</main>

<!-- ===================================
     NAVIGASI SLIDE
=================================== -->
<div class="progress" id="progress"></div>

<nav class="nav" aria-label="Slayt gezintisi">
  <button class="nav-btn prev" id="prev" aria-label="Önceki slayt">
    <span>←</span><span class="txt">Geri</span>
  </button>

  <div class="nav-center">
    <div class="dots" id="dots"></div>
    <span class="counter" id="counter">01 / 05</span>
  </div>

  <button class="nav-btn next" id="next" aria-label="Sonraki slayt">
    <span class="txt">İleri</span><span>→</span>
  </button>
</nav>

<script>
(function () {
  var slides = Array.prototype.slice.call(document.querySelectorAll('.slide'));
  var total = slides.length;
  var current = 0;

  var prevBtn = document.getElementById('prev');
  var nextBtn = document.getElementById('next');
  var dotsBox = document.getElementById('dots');
  var counter = document.getElementById('counter');
  var progress = document.getElementById('progress');

  // buat titik-titik navigasi
  var dots = slides.map(function (_, i) {
    var d = document.createElement('button');
    d.className = 'dot';
    d.setAttribute('aria-label', (i + 1) + '. slayta git');
    d.addEventListener('click', function () { go(i); });
    dotsBox.appendChild(d);
    return d;
  });

  function pad(n) { return String(n).padStart(2, '0'); }

  function go(n) {
    if (n < 0 || n >= total) return;
    current = n;

    slides.forEach(function (s, i) {
      s.classList.toggle('active', i === current);
      s.classList.toggle('before', i < current);
      if (i === current) s.scrollTop = 0;
    });

    dots.forEach(function (d, i) { d.classList.toggle('active', i === current); });
    counter.textContent = pad(current + 1) + ' / ' + pad(total);
    progress.style.width = ((current + 1) / total * 100) + '%';
    prevBtn.disabled = current === 0;
    nextBtn.disabled = current === total - 1;

    try { history.replaceState(null, '', '#' + (current + 1)); } catch (e) {}
  }

  function next() { go(current + 1); }
  function prev() { go(current - 1); }

  prevBtn.addEventListener('click', prev);
  nextBtn.addEventListener('click', next);

  // keyboard
  document.addEventListener('keydown', function (e) {
    if (e.key === 'ArrowRight' || e.key === 'PageDown' || e.key === ' ') {
      e.preventDefault(); next();
    } else if (e.key === 'ArrowLeft' || e.key === 'PageUp') {
      e.preventDefault(); prev();
    } else if (e.key === 'Home') {
      go(0);
    } else if (e.key === 'End') {
      go(total - 1);
    } else if (e.key === 'f' || e.key === 'F') {
      if (!document.fullscreenElement) {
        document.documentElement.requestFullscreen && document.documentElement.requestFullscreen();
      } else {
        document.exitFullscreen && document.exitFullscreen();
      }
    }
  });

  // swipe di layar sentuh
  var startX = 0, startY = 0;
  document.getElementById('deck').addEventListener('touchstart', function (e) {
    startX = e.changedTouches[0].clientX;
    startY = e.changedTouches[0].clientY;
  }, { passive: true });
  document.getElementById('deck').addEventListener('touchend', function (e) {
    var dx = e.changedTouches[0].clientX - startX;
    var dy = e.changedTouches[0].clientY - startY;
    if (Math.abs(dx) > 60 && Math.abs(dx) > Math.abs(dy) * 1.5) {
      dx < 0 ? next() : prev();
    }
  }, { passive: true });

  // buka langsung ke slide tertentu lewat #2, #3, dst.
  var start = parseInt(location.hash.replace('#', ''), 10);
  go(!isNaN(start) && start >= 1 && start <= total ? start - 1 : 0);
})();
</script>

</body>
</html>
