---
layout: ../layouts/ContactLayout.astro
title: Contact
---
<div>
  <form action="https://api.staticforms.xyz/submit" method="post" style="max-width: 500px; margin: 40px auto; padding: 20px; box-shadow: 0 0 10px rgba(255, 107, 1, 0.8);">
  <label for="name" style="display: block; margin-bottom: 10px; color: rgb(255,107,1);">Name:</label>
  <input type="text" id="name" name="name" required style="width: 100%; padding: 10px; margin-bottom: 20px; border: 1px solid #ccc;">
  
  <label for="email" style="display: block; margin-bottom: 10px; color: rgb(255,107,1);">Email:</label>
  <input type="email" id="email" name="email" required style="width: 100%; padding: 10px; margin-bottom: 20px; border: 1px solid #ccc;">
  
  <label for="message" style="display: block; margin-bottom: 10px; color: rgb(255,107,1);">Message:</label>
  <textarea id="message" name="message" required style="width: 100%; padding: 15px; margin-bottom: 20px; border: 1px solid #ccc;"></textarea>
  <input type="text" name="honeypot" style="display:none">
  <input type="submit" value="Send Message" style="background-color: rgb(255,107,1); color: #fff; padding: 10px 20px; border: none; border-radius: 5px; cursor: pointer;"/>
  <input type="hidden" name="accessKey" value="0afa456b-4007-4c8f-bd96-3a68e9d4c60a">
  <input type="hidden" name="redirectTo" value="https://faziblog.pages.dev/contact">
  </form>
</div>
