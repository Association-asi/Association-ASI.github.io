---
layout: default
---

<div style="text-align:center; padding: 20px 0;">
  <img src="/assets/ASI2.jpeg" alt="Logo ASI" style="width:150px;">
</div>

## Bienvenue sur le site de l'ASI

L'**Association de Soutien International** œuvre chaque jour
pour endiguer la pauvreté; promotionner l'accès au soin; améliorer les conditions de vie des familles;   
développer la protection des droits des femmes et des enfants; développer l'automatisation des femmes

---

## 📰 Dernières actualités

{% for post in site.posts limit:5 %}
### [{{ post.title }}]({{ post.url }})
*{{ post.date | date: "%d/%m/%Y" }}*

{{ post.excerpt }}

---
{% endfor %}
