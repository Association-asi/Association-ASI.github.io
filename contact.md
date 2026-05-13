---
layout: default
title: Contact
permalink: /contact/
---

## <i class="fa-solid fa-envelope"></i> Nous contacter

<div class="contact-wrapper">

  <div class="contact-info">
    <div class="contact-info-item">
      <i class="fa-solid fa-location-dot"></i>
      <div>
        <strong>Adresse</strong><br>
        Bâtiment 23, 23 Allée de Fontainebleau<br>
        Boîte 34 — 75019 Paris
      </div>
    </div>
    <div class="contact-info-item">
      <i class="fa-solid fa-envelope"></i>
      <div>
        <strong>Email</strong><br>
        <a href="mailto:asid.paris@protonmail.com">
          asid.paris@protonmail.com
        </a>
      </div>
    </div>
    <div class="contact-info-item">
      <i class="fa-solid fa-clock"></i>
      <div>
        <strong>Réponse sous</strong><br>
        48 heures ouvrées
      </div>
    </div>
  </div>

  <div class="contact-form-wrapper">
    <form name="contact" method="POST" 
          data-netlify="true"
          netlify-honeypot="bot-field"
          class="contact-form">

      <input type="hidden" name="form-name" value="contact">
      <p hidden><input name="bot-field"></p>

      <div class="form-row">
        <div class="form-group">
          <label>
            <i class="fa-solid fa-user"></i> Nom *
          </label>
          <input type="text" name="nom" 
                 placeholder="Votre nom complet" required>
        </div>
        <div class="form-group">
          <label>
            <i class="fa-solid fa-envelope"></i> Email *
          </label>
          <input type="email" name="email"
                 placeholder="votre@email.com" required>
        </div>
      </div>

      <div class="form-group">
        <label>
          <i class="fa-solid fa-tag"></i> Sujet
        </label>
        <select name="sujet">
          <option value="">-- Choisir un sujet --</option>
          <option value="don">💶 Faire un don</option>
          <option value="benevole">🙋 Devenir bénévole</option>
          <option value="parrainage">👐 Parrainage</option>
          <option value="partenariat">🤝 Partenariat</option>
          <option value="autre">💬 Autre</option>
        </select>
      </div>

      <div class="form-group">
        <label>
          <i class="fa-solid fa-message"></i> Message *
        </label>
        <textarea name="message" rows="5"
                  placeholder="Votre message..." required>
        </textarea>
      </div>

      <div class="form-group form-check">
        <input type="checkbox" name="rgpd" id="rgpd" required>
        <label for="rgpd" class="check-label">
          J'accepte que mes données soient utilisées pour traiter
          ma demande conformément à la
          <a href="/politique-confidentialite">
            politique de confidentialité
          </a>
        </label>
      </div>

      <div style="text-align:center;">
        <button type="submit" class="submit-btn">
          <i class="fa-solid fa-paper-plane"></i>
          Envoyer le message
        </button>
      </div>

    </form>
  </div>

</div>
