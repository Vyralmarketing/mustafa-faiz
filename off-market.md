---
layout: default
title: Off-Market Homes
permalink: /off-market/
---

<h3 class="center">Fill out the form below to request lists and information on off-market homes.</h3>

<form class="contact-form" method="post" action="https://formspree.io/{{site.data.settings.client.email}}">
  <input type="text" name="name" placeholder="Name" required>
  <input type="email" name="_replyto" placeholder="Email" required>
  <textarea name="Message" placeholder="Optional Message"></textarea>
  <!-- Cloud cannon settings field -->
  <div class="hidden">
    <input type="hidden" name="_to" value="{{site.data.settings.client.email}}">
    <input type="hidden" name="_subject" value="Off Market Homes Request">
    <input type="text" name="_gotcha">
  </div>

  <input type="submit" value="submit">
</form>
