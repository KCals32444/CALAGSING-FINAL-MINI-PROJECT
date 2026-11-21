=====================================================
GROUP PROJECT README
HTML5 Forms & Multimedia — Final Project
=====================================================

Folder name : Group01_CampusCafe   <-- CHANGE "01" TO YOUR REAL GROUP NUMBER
Theme       : Campus Café (campus life) — "The Study Cup"
Date        : November 2026

-----------------------------------------------------
1. MEMBERS, ROLES AND WHO CODED WHAT
-----------------------------------------------------
(Fill this in with your real names before submitting. Add or remove rows
so every member is listed.)

Member 1: [Full name]  — Role: [e.g. Project lead]
          Coded: [e.g. index.html, css/style.css layout]

Member 2: [Full name]  — Role: [e.g. Content writer]
          Coded: [e.g. menu.html, copy for all pages]

Member 3: [Full name]  — Role: [e.g. Forms and accessibility]
          Coded: [e.g. contact.html, thanks.html, form styles]

Member 4: [Full name]  — Role: [e.g. Media and QA]
          Coded: [e.g. about.html, images/, media/, testing]

Shared code credit: [Name the author of any code shared inside the group.]

-----------------------------------------------------
2. EDITOR
-----------------------------------------------------
[Confirm before submitting: all files opened, edited and saved in Visual Studio.]

-----------------------------------------------------
3. SITE STRUCTURE
-----------------------------------------------------
Group01_CampusCafe/
  index.html      Home: hero, figure + figcaption, favorites, features
  menu.html       Menu: staff picks and full menu in three sections
  about.html      About: story, hours table, team, audio with caption
  contact.html    Contact: working HTML5 form
  thanks.html     Confirmation page the form sends visitors to
  css/style.css   The one external stylesheet (hand-written, no frameworks)
  images/         5 SVG images, each with meaningful alt text in the HTML
  media/          cafe-ambience.mp3 (one audio file, about 21 seconds)
  README.txt      This file

-----------------------------------------------------
4. HOW EACH REQUIREMENT IS MET
-----------------------------------------------------
HTML5
- Every page has doctype, html, head, title, body, charset and viewport meta.
- Semantic regions: header, nav, main, section, article, aside, footer.
- One h1 per page, then h2 / h3 in order.
- Nav links work between all pages; the current page uses aria-current="page"
  and is highlighted in the CSS.
- Contact form: label + text, email, select, textarea and a submit button.
  Every label's "for" matches its input's "id". Name and email are required.
  The form uses method="get" and action="thanks.html", so it works offline
  without any JavaScript or server.
- figure + figcaption: index.html (hero image) and about.html (study corner).
- Audio: about.html uses <audio controls> inside a figure with a figcaption
  that also gives a text description.

CSS (css/style.css)
- CSS variables for colors, fonts, spacing and radius (see :root).
- Flexbox: header, navigation, buttons, cards, footer, form fields.
- Grid: hero, card grids, menu list, About split, contact layout, form.
- Breakpoints: phone (default), tablet (640px), desktop (960px).
- Hover and focus states on links, buttons, cards and every form field.
- Form fields are stacked in one column on every screen size.

JavaScript: none used (optional and not graded).

-----------------------------------------------------
5. CREDITS AND ORIGINALITY
-----------------------------------------------------
- All copy is original.
- Images are hand-drawn SVG files made for this project.
- The audio loop was generated from original notes for this project.
- No templates, CSS frameworks or outside code were used.
  (Edit this line if your group used anything else.)

-----------------------------------------------------
6. DEMO PLAN (5-7 minutes, every member speaks at least 30 seconds)
-----------------------------------------------------
[Assign who presents what, for example:]
Member 1: Theme and site tour (Home, Menu)
Member 2: HTML5 structure and semantic tags
Member 3: Contact form, labels, required fields
Member 4: CSS variables, Flexbox/Grid, responsive layout and media
