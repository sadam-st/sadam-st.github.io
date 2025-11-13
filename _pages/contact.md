---
layout: page
title: contact
permalink: /contact/
nav: true
nav_order: 5
---

<h2>Contact Me</h2>
<p>If you'd like to get in touch, please fill out the form below.</p>

<form action="https://formspree.io/f/your-form-id" method="POST" class="contact-form">
  <label for="name">Name</label><br>
  <input type="text" id="name" name="name" required><br><br>

  <label for="email">Email</label><br>
  <input type="email" id="email" name="_replyto" required><br><br>

  <label for="message">Message</label><br>
  <textarea id="message" name="message" rows="5" required></textarea><br><br>

  <button type="submit">Send Message</button>
</form>

<style>
.contact-form {
  max-width: 500px;
}
.contact-form input, .contact-form textarea {
  width: 100%;
  padding: 8px;
  margin-top: 4px;
  border-radius: 6px;
  border: 1px solid #ccc;
  font-size: 1rem;
}
.contact-form button {
  background-color: #007ACC;
  color: white;
  padding: 10px 18px;
  border: none;
  border-radius: 6px;
  cursor: pointer;
}
.contact-form button:hover {
  background-color: #005fa3;
}
</style>
