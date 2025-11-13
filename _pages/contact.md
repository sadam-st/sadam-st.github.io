---
layout: page
permalink: /contact/
title: Contact
description: Feel free to contact me if you have any question.
nav: true
nav_order: 5
---

<div class="contact-form-container">

<form action="https://formspree.io/f/mqawangr" method="POST" class="contact-form">
  
  <div class="form-group">
    <label for="name">Name</label>
    <input type="text" id="name" name="name" required class="form-control">
  </div>

  <div class="form-group">
    <label for="email">Email</label>
    <input type="email" id="email" name="_replyto" required class="form-control">
  </div>

  <div class="form-group">
    <label for="subject">Subject</label>
    <input type="text" id="subject" name="_subject" placeholder="Optional" class="form-control">
  </div>

  <div class="form-group">
    <label for="message">Message</label>
    <textarea id="message" name="message" rows="6" required class="form-control"></textarea>
  </div>

  <!-- Optional: redirect to thank-you page after submission -->
  <input type="hidden" name="_next" value="/thank-you/">

  <button type="submit" class="btn btn-primary">Send Message</button>
</form>

</div>

<style>
.contact-form-container {
  max-width: 600px;
  margin: 2rem auto;
  padding: 1rem 2rem;
  background: #f9f9f9;
  border-radius: 12px;
  box-shadow: 0 4px 12px rgba(0,0,0,0.1);
}

.contact-form .form-group {
  margin-bottom: 1rem;
}

.contact-form label {
  display: block;
  font-weight: 600;
  margin-bottom: 0.3rem;
}

.contact-form input,
.contact-form textarea {
  width: 100%;
  padding: 0.6rem 0.8rem;
  border-radius: 6px;
  border: 1px solid #ccc;
  font-size: 1rem;
}

.contact-form .btn-primary {
  background-color: #007bff;
  border: none;
  padding: 0.6rem 1.2rem;
  border-radius: 6px;
  font-size: 1rem;
  cursor: pointer;
}

.contact-form .btn-primary:hover {
  background-color: #0056b3;
}
</style>
