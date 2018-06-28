---
permalink: /contact/
layout: single
title: Contact
---


Click <a href="../assets/documents/resume.pdf" target="_blank">here</a> for my resume, or check out more of my work on [GitHub](https://www.github.com/jonwithers)!  

Anything else? Reach out!

<form action="https://formspree.io/jon.s.withers@gmail.com" method="post">
  <input type="email" name="_replyto" placeholder="Your email">
  <textarea name="body" placeholder="Let's get in touch!"></textarea>
  <input type="submit" value="Send">
</form>

<ul>


{% if site.github_username %}
  <li>
    <a href="https://github.com/{{ site.github_username }}">
      <i class="fa fa-github"></i> GitHub
    </a>
  </li>
{% endif %}
</ul>
