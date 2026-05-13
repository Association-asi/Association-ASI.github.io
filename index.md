---
layout: default
---

<!-- CHIFFRES CLÉS -->
<div style="text-align:center; margin:30px 0; padding:25px;
            background:linear-gradient(135deg, #f0f8ff, #e8f4fc);
            border-radius:15px; border-left:5px solid #4A9FD4;">
  <p style="font-size:1.2rem; color:#2e7fb5; font-weight:bold; margin:0;">
    <i class="fa-solid fa-earth-africa" style="color:#E8891A;"></i>
    Depuis 2024, l'ASI agit concrètement là où le besoin est le plus grand
  </p>
  <p style="color:#555; margin:15px 0 0 0; font-size:1rem;">
    Matériel médical, soutien hospitalier, autonomie des femmes —
    <strong>chaque action compte, chaque don change une vie.</strong>
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
