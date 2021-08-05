---
title: "Home"
---

### My Data

- Email: apacheco73@hotmail.com

- [Linkedin](https://www.linkedin.com/in/andres-pacheco-/)

- [Github](https://github.com/APacheco37)

### Projects

- [Spotify Data Explorer](https://elastic-tereshkova-7f9c72.netlify.app/) [_(code)_](https://github.com/apacheco37/spotify-scraper)

### Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
