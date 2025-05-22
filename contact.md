---
layout: page
title: Contact
permalink: /contact/
---

<div class="contact-form">
  <form action="https://formspree.io/f/mvgankrw" method="POST">
    <div class="form-group">
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
    </div>
    
    <div class="form-group">
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
    </div>
    
    <div class="form-group">
      <label for="subject">Subject:</label>
      <input type="text" id="subject" name="subject" required>
    </div>
    
    <div class="form-group">
      <label for="message">Message:</label>
      <textarea id="message" name="message" rows="6" required></textarea>
    </div>
    
    <button type="submit" class="submit-button">Send Message</button>
  </form>
</div>

<style>
.contact-form {
  max-width: 600px;
  margin: 2em auto;
  padding: 2em;
  background: #f8f9fa;
  border-radius: 8px;
  box-shadow: 0 2px 4px rgba(0,0,0,0.1);
}

.form-group {
  margin-bottom: 1.5em;
}

.form-group label {
  display: block;
  margin-bottom: 0.5em;
  font-weight: bold;
  color: #333;
}

.form-group input,
.form-group textarea {
  width: 100%;
  padding: 0.8em;
  border: 1px solid #ddd;
  border-radius: 4px;
  font-size: 1em;
}

.form-group textarea {
  resize: vertical;
}

.submit-button {
  background-color: #2a7ae2;
  color: white;
  padding: 0.8em 1.5em;
  border: none;
  border-radius: 4px;
  cursor: pointer;
  font-size: 1em;
  transition: background-color 0.3s ease;
}

.submit-button:hover {
  background-color: #1a5cb3;
}
</style> 