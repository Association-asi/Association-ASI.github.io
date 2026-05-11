layout: default
---

<div style="text-align:center; padding:20px 0;">
  <img src="ASI2.jpeg" 
       alt="Logo ASI" 
       style="width:150px; border-radius:10px;">
</div>

## Bienvenue sur le site de l'ASI

L'**Association de Soutien International** œuvre chaque jour pour améliorer les conditions de vie des familles, développer la protection des droits des femmes et des enfants.

---
layout: default
---

<nav style="text-align:center; margin-bottom:30px;">
  <a href="/about" style="margin:0 15px; color:#E8891A; font-weight:bold;">À propos</a>
  <a href="/adhesion" style="margin:0 15px; color:#E8891A; font-weight:bold;">Adhésion</a>
  <a href="/contact" style="margin:0 15px; color:#E8891A; font-weight:bold;">Contact</a>
</nav>

---

## Dernières actualités

{% for post in site.posts %}
### [{{ post.title }}]({{ post.url | relative_url }})
{{ post.date | date: "%d/%m/%Y" }}

{{ post.excerpt }}

---
{% endfor %}
