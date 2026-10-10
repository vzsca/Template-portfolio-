---
layout: default
title: Legal Notice
permalink: /legal/
---

<section id="legal-notice" class="about-section">
  <h2><span class="sym">~/</span>legal-notice</h2>
  <p>This page is a starting point only. Review and adapt it before publishing to reflect your location, hosting setup, and the services used on your site.</p>
</section>

<section class="legal-terminal-section">
  <h2><span class="sym">$</span>cat legal-notice.md</h2>
  <div class="term legal-terminal">
    <div class="term-bar" aria-hidden="true">
      <span class="dot r"></span><span class="dot y"></span><span class="dot g"></span>
      <span class="term-title">~/legal-notice</span>
    </div>
    <section class="legal-grid">
      <article class="legal-card">
        <h2>Site owner</h2>
        <p><strong>{{ site.title }}</strong></p>
        <p>Describe who operates this website and provide any details required in your jurisdiction.</p>
        {% if site.email != "" %}<p>Contact: <a href="mailto:{{ site.email }}">{{ site.email }}</a></p>{% else %}<p>Add a public contact address in <code>_config.yml</code> if appropriate.</p>{% endif %}
      </article>
      <article class="legal-card">
        <h2>Hosting</h2>
        <p>This template is designed for GitHub Pages. Confirm the hosting details and applicable terms for your published site.</p>
        <p><a href="https://docs.github.com/en/pages" target="_blank" rel="noopener noreferrer">GitHub Pages documentation</a></p>
      </article>
      <article class="legal-card">
        <h2>Privacy and data</h2>
        <p>Explain what data your website and any third-party services collect. This template does not include an analytics service or contact form by default; document any services you add.</p>
      </article>
      <article class="legal-card">
        <h2>Intellectual property</h2>
        <p>Identify relevant licenses for text, images, fonts, icons, and other assets. Only publish material you have permission to use.</p>
      </article>
      <article class="legal-card">
        <h2>External links</h2>
        <p>Explain the purpose of external links and how visitors can contact you about an issue with the site.</p>
      </article>
    </section>
  </div>
</section>

<p class="legal-back"><a href="{{ '/' | relative_url }}">← Back to home</a></p>
