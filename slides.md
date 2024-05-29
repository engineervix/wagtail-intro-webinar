---
# try also 'default' to start simple
theme: seriph
background: /images/title-image.svg
# some information about your slides, markdown enabled
title: Markdown-Powered Emails in Django
info: |
  ## Markdown-Powered Emails in Django
  Write in Markdown, style with custom CSS, and inline the CSS with premailer.

  [Blog post](https://blog.victor.co.zm/markdown-powered-emails-in-django)
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# https://sli.dev/guide/drawing
drawings:
  persist: false
# slide transition: https://sli.dev/guide/animations#slide-transitions
transition: slide-left
# enable MDC Syntax: https://sli.dev/guide/syntax#mdc-syntax
mdc: true
---

<div class="mb-60">
  <h1>Markdown-Powered Emails in Django</h1>
  <!-- Write in Markdown, style with custom CSS, and inline the CSS with premailer. -->
</div>

---
layout: image-right
image: https://media1.tenor.com/m/dTP4cRnO9bEAAAAC/sweating-nervous.gif
transition: fade-out
---

# HTML Emails are hard

<v-clicks>

- it's not just the same as designing layouts for a web page
- **Inconsistent Rendering**
- **Limited CSS Support**
- that's why we often just send plain text emails
</v-clicks>

---
layout: iframe
url: https://mjml.io/
---

---
layout: center
---

# A simpler approach ...