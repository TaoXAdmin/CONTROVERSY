---
layout: default
title: "Contact"
permalink: /contact/
---

<h2>Contactez-moi</h2>

<form action="https://formspree.io/f/votre-identifiant-formspree" method="POST">
    <label for="name">Nom :</label>
    <input type="text" id="name" name="name" required>

    <label for="email">Email :</label>
    <input type="email" id="email" name="_replyto" required>

    <label for="message">Message :</label>
    <textarea id="message" name="message" required></textarea>

    <button type="submit">Envoyer</button>
</form>
