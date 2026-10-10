---
layout: default
title: Mentions légales
permalink: /mentions-legales/
---

<section id="mentions-legales" class="profil">
  <h2><span class="sym">~/</span>mentions-legales</h2>
  <p>Modèle à personnaliser avant publication : vérifiez les informations relatives à l'éditeur, à l'hébergement, aux données personnelles et aux licences.</p>
</section>

<section class="legal-terminal-section">
  <h2><span class="sym">$</span>cat mentions-legales.md</h2>
  <div class="term legal-terminal">
    <div class="term-bar" aria-hidden="true">
      <span class="dot r"></span><span class="dot y"></span><span class="dot g"></span>
      <span class="term-title">~/mentions-legales</span>
    </div>
    <section class="legal-grid">
      <article class="legal-card">
        <h2>Éditeur du site</h2>
        <p><strong>{{ site.title }}</strong></p>
        <p>Site personnel. Complétez cette rubrique selon votre situation et les obligations qui vous concernent.</p>
        {% if site.email != "" %}<p>Contact : <a href="mailto:{{ site.email }}">{{ site.email }}</a></p>{% else %}<p>Ajoutez une adresse de contact dans `_config.yml` si vous souhaitez la publier.</p>{% endif %}
      </article>
      <article class="legal-card">
        <h2>Hébergement</h2>
        <p>Ce modèle est prévu pour GitHub Pages. Vérifiez les informations d'hébergement et les conditions de service applicables au site publié.</p>
        <p><a href="https://docs.github.com/en/pages" target="_blank" rel="noopener noreferrer">Documentation GitHub Pages</a></p>
      </article>
      <article class="legal-card">
        <h2>Données personnelles</h2>
        <p>Décrivez honnêtement les données collectées par votre site et ses services tiers. Ce modèle ne contient pas de formulaire ni d'outil d'audience par défaut ; toute intégration ajoutée doit être prise en compte.</p>
      </article>
      <article class="legal-card">
        <h2>Propriété intellectuelle</h2>
        <p>Indiquez les licences des textes, images, polices, icônes et autres ressources. Ne publiez que les contenus que vous êtes autorisé à utiliser.</p>
      </article>
      <article class="legal-card">
        <h2>Liens externes et responsabilité</h2>
        <p>Précisez la nature de vos liens externes et les modalités de contact pour signaler une erreur.</p>
      </article>
    </section>
  </div>
</section>

<p class="legal-back"><a href="{{ '/' | relative_url }}">← Retour à l'accueil</a></p>
