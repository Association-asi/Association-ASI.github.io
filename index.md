---
layout: default
title: "Accueil"
description: "L'ASI est une association humanitaire loi 1901 fondée en 2024. Nous agissons pour l'accès aux soins en Afrique et l'aide aux personnes vulnérables en France."
keywords: "association humanitaire Paris, aide médicale Afrique, don association, soutien international"
---

<!-- PHRASE D'ACCROCHE -->
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

<!-- CHIFFRES CLÉS -->
<div style="display:flex; justify-content:center; gap:20px;
            flex-wrap:wrap; margin:30px 0; text-align:center;">

  <div style="background:#f0f8ff; border-radius:15px; padding:20px 25px;
              border-top:4px solid #4A9FD4; min-width:130px;">
    <div style="font-size:2rem; font-weight:bold; color:#4A9FD4;">2+</div>
    <div style="color:#555; font-size:0.9rem;">
      <i class="fa-solid fa-earth-africa" style="color:#4A9FD4;"></i>
      Pays d'intervention
    </div>
    <div style="color:#aaa; font-size:0.75rem;">3 en cours</div>
  </div>

  <div style="background:#fff8f0; border-radius:15px; padding:20px 25px;
              border-top:4px solid #E8891A; min-width:130px;">
    <div style="font-size:2rem; font-weight:bold; color:#E8891A;">13</div>
    <div style="color:#555; font-size:0.9rem;">
      <i class="fa-solid fa-hospital" style="color:#E8891A;"></i>
      Structures de santé
    </div>
    <div style="color:#aaa; font-size:0.75rem;">hôpitaux, cliniques, centres</div>
  </div>

  <div style="background:#f0fff0; border-radius:15px; padding:20px 25px;
              border-top:4px solid #2e9e4f; min-width:130px;">
    <div style="font-size:2rem; font-weight:bold; color:#2e9e4f;">2</div>
    <div style="color:#555; font-size:0.9rem;">
      <i class="fa-solid fa-truck-medical" style="color:#2e9e4f;"></i>
      Ambulances envoyées
    </div>
    <div style="color:#aaa; font-size:0.75rem;">6 en cours</div>
  </div>

  <div style="background:#fff0f8; border-radius:15px; padding:20px 25px;
              border-top:4px solid #2e7fb5; min-width:130px;">
    <div style="font-size:2rem; font-weight:bold; color:#2e7fb5;">25</div>
    <div style="color:#555; font-size:0.9rem;">
      <i class="fa-solid fa-people-group" style="color:#2e7fb5;"></i>
      Bénévoles
    </div>
    <div style="color:#aaa; font-size:0.75rem;">5 actifs · 20 en renfort</div>
  </div>

  <div style="background:#f8f0ff; border-radius:15px; padding:20px 25px;
              border-top:4px solid #9b59b6; min-width:130px;">
    <div style="font-size:2rem; font-weight:bold; color:#9b59b6;">2024</div>
    <div style="color:#555; font-size:0.9rem;">
      <i class="fa-solid fa-calendar" style="color:#9b59b6;"></i>
      Année de création
    </div>
    <div style="color:#aaa; font-size:0.75rem;">une association jeune et engagée</div>
  </div>

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
     style="display:inline-flex; align-items:center; gap:10px;
            background:linear-gradient(135deg, #4A9FD4, #2e7fb5);
            color:white; padding:14px 35px; border-radius:30px;
            text-decoration:none; font-weight:bold; font-size:1rem;
            box-shadow:0 4px 15px rgba(74,159,212,0.4);
            transition:all 0.3s;">
    <i class="fa-solid fa-newspaper"></i>
    Voir toutes les actualités
    <i class="fa-solid fa-arrow-right"></i>
  </a>
</div>

<hr>

<div style="text-align:center; margin:30px 0;">

  <h2 style="color:#2e7fb5;">
    <i class="fa-brands fa-instagram" style="color:#E1306C;"></i>
    Suivez-nous sur Instagram
  </h2>

  <p style="color:#888; margin:10px 0 20px 0;">
    Retrouvez nos actions en images sur Instagram
  </p>

  <a href="https://www.instagram.com/VOTRE_COMPTE_ASI"
     target="_blank"
     style="display:inline-flex; align-items:center; gap:10px;
            background:linear-gradient(45deg, #f09433, #e6683c, #dc2743, #cc2366, #bc1888);
            color:white; padding:14px 35px; border-radius:30px;
            text-decoration:none; font-weight:bold; font-size:1rem;
            box-shadow:0 4px 15px rgba(220,39,67,0.3);
            transition:all 0.3s;">
    <i class="fa-brands fa-instagram"></i>
    Voir notre Instagram
    <i class="fa-solid fa-arrow-up-right-from-square"></i>
  </a>

</div>
