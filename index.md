---
layout: default
---

<!-- CHIFFRES CLÉS -->
<div style="text-align:center; margin:30px 0; padding:25px;
            background: linear-gradient(135deg, #f0f8ff, #e8f4fd);
            border-radius:15px; border: 2px solid #4A9FD4;">

  <h3 style="color:#4A9FD4; margin-bottom:10px;">
    🌍 Notre impact en chiffres
  </h3>

  <p style="color:#888; font-style:italic;">
    Nos données d'impact sont en cours de compilation.<br>
    Revenez bientôt pour découvrir l'étendue de nos actions !
  </p>

</div>

## <i class="fa-solid fa-bullhorn"></i> Bienvenue sur le site de l'ASI

## <i class="fa-solid fa-newspaper"></i> Dernières actualités

<div class="articles-grid">
{% for post in site.posts limit:3 %}
<div class="article-card">
  <div class="article-card-body">
    <p class="article-date">{{ post.date | date: "%d/%m/%Y" }}</p>
    <h3 class="article-title">
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </h3>
    <p class="article-excerpt">
      {{ post.excerpt | strip_html | truncate: 120 }}
    </p>
    <a href="{{ post.url | relative_url }}" class="article-btn">
      Lire la suite →
    </a>
  </div>
</div>
{% endfor %}
</div>

<div style="text-align:center; margin-top:25px;">
  <a href="/actualites"
     style="background-color:#4A9FD4; color:white; padding:12px 30px;
            border-radius:25px; text-decoration:none; font-weight:bold;">
    📰 Voir toutes les actualités →
  </a>
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
