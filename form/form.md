---
layout: layouts/post.njk
title: Form
templateClass: tmpl-post
eleventyNavigation:
  key: Form
  order: 3
---


<form name="contact" method="POST" data-netlify="true">

  <p>
    <label>First Name: <input type="text" name="name" /></label>   
  </p>
  
  <p>
    <label>Surname:    <input type="text" name="name" /></label>   
  </p>

  <p>
    <label>Email:      <input type="email" name="email" /></label>
  </p>
  
  <p>
    <label>Message:    <textarea name="message"></textarea></label>
  </p>

  <p>
    <button type="submit">Send</button>
  </p>

</form>