
<!-- ARCANE PREMIUM HERO -->
<section class="arcane-hero">
  <div class="arcane-glow glow-one"></div>
  <div class="arcane-glow glow-two"></div>

  <nav class="arcane-nav">
    <a href="#" class="arcane-brand">
      <span class="brand-icon">A</span>
      <span>ARCANE<span class="brand-dot">.</span></span>
    </a>
    <span class="nav-status">
      <span class="status-dot"></span> GAMING ECOSYSTEM
    </span>
    <a class="nav-github"
       href="https://github.com/hadibader/Arcane"
       target="_blank" rel="noopener">
      GitHub ↗
    </a>
  </nav>

  <div class="hero-content">
    <div class="hero-badge">
      <span>✦</span> YOUR ULTIMATE GAMING HUB
    </div>

    <h1>
      EVERY GAME.<br>
      <span>ONE UNIVERSE.</span>
    </h1>

    <p class="hero-description">
      Meet ARCANE — a modern gaming library designed to bring
      your PC games, emulators and gaming worlds together.
      One library. Your rules. Your experience.
    </p>

    <div class="hero-actions">
      <a class="hero-btn primary"
         href="https://github.com/hadibader/Arcane/releases">
        ↓ &nbsp; Get ARCANE
      </a>
      <a class="hero-btn secondary"
         href="https://github.com/hadibader/Arcane">
        Explore on GitHub ↗
      </a>
    </div>

    <div class="hero-features">
      <div class="feature">
        <span class="feature-icon">◈</span>
        <div>
          <strong>SmartScan</strong>
          <small>Discover your games</small>
        </div>
      </div>
      <div class="feature">
        <span class="feature-icon">▧</span>
        <div>
          <strong>SmartCover</strong>
          <small>Beautiful game artwork</small>
        </div>
      </div>
      <div class="feature">
        <span class="feature-icon">⌘</span>
        <div>
          <strong>Pocket Nova</strong>
          <small>Explore more gaming worlds</small>
        </div>
      </div>
    </div>

    <div class="hero-footer">
      <span>BUILT FOR GAMERS</span>
      <span>DESIGNED FOR YOUR WORLD.</span>
    </div>
  </div>
</section>

<style>
.arcane-hero {
  --purple: #a78bfa;
  --muted: #a5a5ba;
  position: relative;
  isolation: isolate;
  overflow: hidden;
  min-height: 680px;
  padding: 0 7%;
  color: #f8f7ff;
  background:
    radial-gradient(ellipse at 50% 65%,
      #33205e 0%, #171128 34%, transparent 67%),
    linear-gradient(135deg, #080810, #100c1d 55%, #090910);
  font-family: Inter, "Segoe UI", sans-serif;
}

.arcane-hero * {
  box-sizing: border-box;
}

.arcane-glow {
  position: absolute;
  z-index: -1;
  width: 330px;
  height: 330px;
  border-radius: 50%;
  filter: blur(110px);
  opacity: .22;
  pointer-events: none;
}

.glow-one {
  background: #7945ff;
  top: 20%;
  left: -170px;
}

.glow-two {
  background: #5735e9;
  right: -180px;
  bottom: 0;
}

.arcane-nav {
  min-height: 86px;
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 18px;
  border-bottom: 1px solid #ffffff12;
}

.arcane-brand {
  display: flex;
  align-items: center;
  gap: 12px;
  color: white;
  font-size: 19px;
  font-weight: 900;
  letter-spacing: 3px;
  text-decoration: none;
}

.brand-icon {
  display: grid;
  place-items: center;
  width: 38px;
  height: 38px;
  border: 1px solid #b9a0ff80;
  border-radius: 12px;
  background: linear-gradient(145deg, #8c5cff55, #25153f);
  box-shadow: 0 0 25px #8b5cf633;
  font-size: 22px;
}

.brand-dot { color: var(--purple); }

.nav-status {
  color: #b8b3ce;
  font-size: 10px;
  letter-spacing: 2px;
}

.status-dot {
  display: inline-block;
  width: 7px;
  height: 7px;
  margin-right: 8px;
  border-radius: 50%;
  background: #a78bfa;
  box-shadow: 0 0 12px #a78bfa;
}

.nav-github {
  color: #eee9ff;
  text-decoration: none;
  font-size: 13px;
  padding: 11px 17px;
  border: 1px solid #ffffff25;
  border-radius: 10px;
  transition: .25s;
}

.nav-github:hover {
  background: #ffffff12;
  border-color: #a78bfa;
}

.hero-content {
  max-width: 920px;
  margin: 0 auto;
  padding: 95px 0 25px;
  text-align: center;
  animation: arcane-enter .8s ease both;
}

.hero-badge {
  display: inline-flex;
  align-items: center;
  gap: 9px;
  padding: 10px 16px;
  color: #d8cbff;
  background: #a78bfa12;
  border: 1px solid #a78bfa35;
  border-radius: 100px;
  font-size: 10px;
  font-weight: 700;
  letter-spacing: 2px;
}

.hero-badge span { color: #c4b5fd; }

.hero-content h1 {
  margin: 28px 0 20px;
  font-size: clamp(44px, 7vw, 88px);
  line-height: .99;
  font-weight: 950;
  letter-spacing: -4px;
}

.hero-content h1 span {
  color: transparent;
  background: linear-gradient(100deg, #c4b5fd, #8b5cf6 50%, #e9d5ff);
  -webkit-background-clip: text;
  background-clip: text;
}

.hero-description {
  max-width: 610px;
  margin: 0 auto;
  color: var(--muted);
  font-size: 16px;
  line-height: 1.9;
}

.hero-actions {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
  gap: 13px;
  margin: 32px 0 54px;
}

.hero-btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  min-height: 49px;
  padding: 0 23px;
  border-radius: 11px;
  text-decoration: none;
  font-size: 13px;
  font-weight: 750;
  transition: transform .25s, box-shadow .25s,
              background .25s;
}

.hero-btn:hover { transform: translateY(-3px); }

.hero-btn.primary {
  color: #10091d;
  background: linear-gradient(120deg, #c4b5fd, #a78bfa);
  box-shadow: 0 8px 35px #8b5cf633;
}

.hero-btn.primary:hover {
  box-shadow: 0 10px 45px #8b5cf666;
}

.hero-btn.secondary {
  color: #f2edff;
  border: 1px solid #ffffff27;
  background: #ffffff07;
}

.hero-btn.secondary:hover { background: #ffffff12; }

.hero-features {
  display: grid;
  grid-template-columns: repeat(3, 1fr);
  max-width: 760px;
  margin: 0 auto;
  padding: 24px 0;
  border-top: 1px solid #ffffff17;
  border-bottom: 1px solid #ffffff17;
  text-align: left;
}

.feature {
  display: flex;
  align-items: center;
  justify-content: center;
  gap: 12px;
  padding: 8px;
}

.feature-icon {
  display: grid;
  place-items: center;
  flex-shrink: 0;
  width: 40px;
  height: 40px;
  color: #c4b5fd;
  background: #a78bfa14;
  border: 1px solid #a78bfa25;
  border-radius: 12px;
  font-size: 21px;
}

.feature strong,
.feature small { display: block; }

.feature strong {
  font-size: 12px;
  margin-bottom: 5px;
}

.feature small {
  color: #9994ad;
  font-size: 10px;
}

.hero-footer {
  display: flex;
  justify-content: space-between;
  gap: 12px;
  max-width: 760px;
  margin: 25px auto 0;
  color: #858098;
  font-size: 9px;
  letter-spacing: 2px;
}

@keyframes arcane-enter {
  from { opacity: 0; transform: translateY(18px); }
  to { opacity: 1; transform: translateY(0); }
}

@media (max-width: 600px) {
  .arcane-hero { padding: 0 20px; min-height: auto; }
  .arcane-nav { min-height: 72px; }
  .arcane-brand { font-size: 15px; letter-spacing: 2px; }
  .brand-icon { width: 33px; height: 33px; }
  .nav-status { display: none; }
  .nav-github { padding: 9px 11px; font-size: 12px; }
  .hero-content { padding-top: 75px; }
  .hero-content h1 { letter-spacing: -2px; }
  .hero-description { font-size: 14px; }
  .hero-actions { margin-bottom: 38px; }
  .hero-btn { width: 100%; }
  .hero-features { grid-template-columns: 1fr; gap: 12px; }
  .feature { justify-content: flex-start; padding: 5px 12px; }
  .hero-footer { font-size: 8px; letter-spacing: 1px; }
}

@media (prefers-reduced-motion: reduce) {
  .arcane-hero * {
    animation: none !important;
    transition: none !important;
  }
}
</style>
