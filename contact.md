---
layout: page
title: Yell at Andy
permalink: /contact/
check: https://getsimpleform.com/messages?api_token=9858ef6dff009d68a3744037c7c61309
---

<form action="//formspree.io/matt@matt.cc"
      method="POST">
  <!-- the redirect_to is optional, the form will redirect to the referrer on submission -->


  <input type="hidden" name="_next" value="http://mattmotel.github.io/goodbadshow/" />
  <!-- all your input fields here.... -->

  <p><label>Name</label>
  <input type="text" name="name"></p>
  <p><label>Email</label>
  <input type="email" name="_replyto"></p>
  <p><label>Message</label>
  <textarea name="message"></textarea></p>
  <input type="submit" value="Send">
</form>

