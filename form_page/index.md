---
layout: layouts/base.njk
title: Sign-Up Form
templateClass: tmpl-post
eleventyNavigation:
  key: Contact Me
  order: 
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
    <label>Do you agree to the <a href="">terms and conditions</a><select name="role[]" multiple>
      <option value="yes">Yes</option>
      <option value="no">No</option>
    </select></label>
  </p>
  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>