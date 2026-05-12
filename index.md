---
layout: default
---

<!-- CHIFFRES CLÉS -->
<div style="display:flex; justify-content:center; gap:30px; 
            flex-wrap:wrap; margin:30px 0; text-align:center;">

  <div style="background:#f0f8ff; border-radius:15px; padding:20px 30px;
              border-top:4px solid #4A9FD4; min-width:130px;">
    <div style="font-size:2rem; font-weight:bold; color:#4A9FD4;">4</div>
    <div style="color:#555;">🌍 Pays</div>
  </div>

  <div style="background:#fff8f0; border-radius:15px; padding:20px 30px;
              border-top:4px solid #E8891A; min-width:130px;">
    <div style="font-size:2rem; font-weight:bold; color:#E8891A;">3+</div>
    <div style="color:#555;">🏥 Hôpitaux soutenus</div>
  </div>

  <div style="background:#f0fff0; border-radius:15px; padding:20px 30px;
              border-top:4px solid #2e7fb5; min-width:130px;">
    <div style="font-size:2rem; font-weight:bold; color:#2e7fb5;">500+</div>
    <div style="color:#555;">👥 Bénéficiaires</div>
  </div>

  <div style="background:#fff0f8; border-radius:15px; padding:20px 30px;
              border-top:4px solid #E8891A; min-width:130px;">
    <div style="font-size:2rem; font-weight:bold; color:#E8891A;">2</div>
    <div style="color:#555;">🚑 Ambulances envoyées</div>
  </div>

</div>

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
