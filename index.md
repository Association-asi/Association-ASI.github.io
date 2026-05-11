---
layout: default
---

## 📰 Dernières actualités

<div class="articles-grid">
{% for post in site.posts limit:6 %}
<div class="article-card">
  <div class="article-card-body">
    <p class="article-date">{{ post.date | date: "%d/%m/%Y" }}</p>
    <h3 class="article-title">
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </h3>
    <p class="article-excerpt">
      {{ post.excerpt | strip_html | truncate: 100 }}
    </p>
    <a href="{{ post.url | relative_url }}" class="article-btn">
      Lire la suite →
    </a>
  </div>
</div>
{% endfor %}
</div>

<hr>

## 📸 Suivez-nous sur Instagram

<div class="instagram-section">
  <p style="text-align:center; color:#888;">
    Retrouvez nos actions en images sur Instagram
  </p>
  <div class="instagram-placeholder">
    <!-- Widget Instagram à intégrer ici -->
    <a href="https://www.instagram.com/VOTRE_COMPTE_ASI" 
       target="_blank"
       class="instagram-btn">
      📷 Voir notre Instagram
    </a>
  </div>
</div>
