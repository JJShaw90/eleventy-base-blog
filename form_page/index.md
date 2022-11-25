---
layout: layouts/base.njk
title: Sign-Up Form
templateClass: tmpl-post
eleventyNavigation:
  key: Contact Me
  order: 4
---
<p>Please fill out the form below if you want to collaborate on any fun projects:</p>
<form name="contact" method="POST" data-netlify="true">
  <p>
    <label>Your Name: <input type="text" name="name" /></label>
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>
  <p>
    <label>Do you agree to the <a href="">terms and conditions:</a>
     <input type="radio" id="yes_t&c" name="ts_cs" value="yes_t&c">
  <label for="yes_t&c">Yes</label>
  <input type="radio" id="no_t&c" name="ts_cs" value="no_t&c">
  <label for="no_t&c">No</label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>