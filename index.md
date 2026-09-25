---
layout: default
title: Andrea Gazzi
---

<section class="hero">
  <div class="hero-left">
    <p class="hero-label">// Andrea Gazzi</p>
    <h1 class="hero-title">Team Lead &amp; Senior Software Engineer</h1>
    <p class="hero-bio">Mobile-first engineer based in Switzerland. Skilled in native app development in Android/iOS, and crossplatform development in Kotlin Multiplatform and Flutter, leading cross-functional delivery teams across banking, insurance, and public sector clients at adesso Schweiz AG.</p>
    <div class="hero-links">
      <a href="https://github.com/pizzodev" target="_blank" rel="noopener">GitHub</a>
      <a href="https://www.linkedin.com/in/andrea-gazzi-592344119/" target="_blank" rel="noopener">LinkedIn</a>
    </div>
  </div>
  <div class="hero-right">
    <img src="{{ '/assets/images/avatar.png' | relative_url }}" alt="Andrea Gazzi" class="hero-avatar" />
  </div>
</section>

<section class="section">
  <h2 class="section-title">Everyday life</h2>
  <p class="about-text">Outside of work, I keep myself busy with a mix of hands-on and outdoor pursuits. I cook, do woodworking, and look after a growing collection of plants and terrariums. Football and time spent outdoors keep me grounded. I have a soft spot for indie music, and a long-standing curiosity for space weather and astrophysics — which led me to become an accredited solar observer. Tech is both my profession and a genuine passion.</p>
</section>

<section class="section">
  <h2 class="section-title">Experience</h2>
  <div class="timeline">

    <div class="tl-item">
      <div class="tl-meta">
        <span class="tl-company">adesso Schweiz AG</span>
        <span class="tl-period"><span class="dot-live"></span>Jan 2026 – present</span>
      </div>
      <div class="tl-role">Team Lead &amp; Senior Software Engineer</div>
    </div>

    <div class="tl-item">
      <div class="tl-meta">
        <span class="tl-company">Avaloq &middot; via adesso</span>
        <span class="tl-period"><span class="dot-live"></span>Jul 2025 – present</span>
      </div>
      <div class="tl-role">Kotlin Multiplatform Developer</div>
    </div>

    <div class="tl-item">
      <div class="tl-meta">
        <span class="tl-company">EPAL &middot; via adesso</span>
        <span class="tl-period">Jun 2023 – Mar 2026</span>
      </div>
      <div class="tl-role">Flutter Developer, Product &amp; Project Manager</div>
    </div>

    <div class="tl-item">
      <div class="tl-meta">
        <span class="tl-company">AXA Switzerland &middot; via adesso</span>
        <span class="tl-period">Jan 2024 – Oct 2024</span>
      </div>
      <div class="tl-role">Lead Developer - Engagement Program</div>
    </div>

    <div class="tl-item">
      <div class="tl-meta">
        <span class="tl-company">Avaloq &middot; via adesso</span>
        <span class="tl-period">Nov 2022 – Jun 2023</span>
      </div>
      <div class="tl-role">Mobile Developer &amp; Release Manager</div>
    </div>

    <div class="tl-item">
      <div class="tl-meta">
        <span class="tl-company">Flowe &middot; via Reti S.p.A.</span>
        <span class="tl-period">Sep 2019 – Apr 2021</span>
      </div>
      <div class="tl-role">Android Developer</div>
    </div>

    <div class="tl-item">
      <div class="tl-meta">
        <span class="tl-company">SIDC — Solar Influences Data Analysis Center</span>
        <span class="tl-period"><span class="dot-live"></span>Jan 2013 – present</span>
      </div>
      <div class="tl-role">Accredited Solar Observer</div>
    </div>

  </div>
</section>

<section class="section">
  <h2 class="section-title">Projects</h2>
  <div class="project-grid">

    <a class="project-card" href="https://github.com/pizzodev/CMImageViewer" target="_blank" rel="noopener">
      <div class="project-lang">Kotlin</div>
      <div class="project-name">CMImageViewer</div>
      <div class="project-desc">Sample for a Kotlin Multiplatform project that uses the Compose Multiplatform UI framework.</div>
    </a>

    <a class="project-card" href="https://github.com/pizzodev/flutter-web-docker" target="_blank" rel="noopener">
      <div class="project-lang">C#</div>
      <div class="project-name">flutter-web-docker</div>
      <div class="project-desc">Setup flutter build inside a Docker container

</div>
    </a>

    <a class="project-card" href="https://github.com/pizzodev/woodeveloper" target="_blank" rel="noopener">
      <div class="project-lang">TypeScript</div>
      <div class="project-name">woodeveloper</div>
      <div class="project-desc">The WooDeveloper project began as a hobby, but it reflects my desire to combine creativity, design and attention to detail in everything I do.</div>
    </a>

  </div>
</section>

<section class="section">
  <h2 class="section-title">Publications</h2>
  <ul class="pub-list">
  {% assign pubs = site.publications | sort: 'date' | reverse %}
  {% for pub in pubs %}
    <li class="pub-item">
      <a href="{{ pub.url | relative_url }}">{{ pub.title }}</a>
      <div class="pub-meta">
        <span class="category">{{ pub.category }}</span>
        <span>{{ pub.date | date: "%B %-d, %Y" }}</span>
      </div>
      {% if pub.description %}
      <div class="pub-description">{{ pub.description }}</div>
      {% endif %}
    </li>
  {% endfor %}
  </ul>
</section>
