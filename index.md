---
layout: home
title: Welcome
---

# 👋 Welcome to My Blog!

Hello there, I’m Dan Murphy, a SRE engineer, open-source enthusiast, and lifelong learner. This is where I share tutorials, project stories, and personal reflections on coding, technology, and beyond.

---

## 📝 Latest Posts

<ul>
  {% for post in site.posts limit:5 %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      <small>• {{ post.date | date: "%b %-d, %Y" }}</small>
    </li>
  {% endfor %}
</ul>

[Read all posts »](/archives)

---

## 💡 What You’ll Find Here

- **Tutorials & How-Tos:** Step-by-step guides on web development, tooling, and best practices.  
- **Project Deep Dives:** Behind-the-scenes of open-source libraries and side-projects.  
- **Tech Musings:** Thoughts on industry trends, new languages, and my learning journey.

---

## 📬 Stay in Touch

If you’d like new posts delivered straight to your inbox, subscribe here:

```html
<form action="https://your-mailing-service.com/subscribe" method="post">
  <input type="email" name="email" placeholder=danielmurphy02830@gmail.com required>
  <button type="submit">Subscribe</button>
</form>
