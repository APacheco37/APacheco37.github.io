---
title: "Home"
---

### My Data

- Email: apacheco37@outlook.com

- [Linkedin](https://www.linkedin.com/in/andres-pacheco-/)

- [Github](https://github.com/apacheco37)

### Projects

- [Spotify Data Explorer](https://spotify-data-explorer.netlify.app/) [_(code)_](https://github.com/apacheco37/spotify-scraper)

### Posts

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>
