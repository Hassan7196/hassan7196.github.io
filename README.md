# hassan7196.github.io

Personal portfolio site for **Hassan Raza**, Data Scientist.

Live at: https://hassan7196.github.io

## What this is

A single-page portfolio built as one static HTML file. No build step, no framework, no dependencies, no backend. Open `index.html` in a browser and it works.

## Contents

| Section | What it covers |
|---|---|
| About | Short professional summary |
| How I got here | The academic turnaround story |
| Selected work | Five projects: clinical survival modelling, RAG over 800 PDFs, real-time sensor dashboard, scraping and OCR pipelines, bio-signal emotion study |
| Experience | Roles from 2020 to present |
| Education | MSc Artificial Intelligence (Distinction, Essex), BSc Software Engineering (Gold Medalist, BNU) |
| Skills | Languages, libraries, cloud, tooling |
| Contact | Email, phone, LinkedIn, GitHub |

## Stack

- Plain HTML and CSS in one file
- System font stack, so it renders natively on every platform
- Responsive down to mobile
- Keyboard focus states and `prefers-reduced-motion` respected
- Scroll reveal via IntersectionObserver, roughly 15 lines of vanilla JS

## Hosting

Deployed free on GitHub Pages from the `main` branch, root folder.

## Editing

Everything lives in `index.html`. To change content, search for the section heading and edit the text directly. Colours are CSS custom properties at the top of the `<style>` block:

```css
--blue:  #0071e3;   /* accent, links and buttons */
--ink:   #1d1d1f;   /* primary text */
--ink-2: #6e6e73;   /* secondary text */
--grey:  #f5f5f7;   /* alternating section background */
```

## Contact

- Email: hassanraza.softwares@gmail.com
- LinkedIn: https://www.linkedin.com/in/hassanraza7196
- GitHub: https://github.com/Hassan7196
