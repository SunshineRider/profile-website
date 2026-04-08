# rahulmittal.xyz — Personal Portfolio

Personal portfolio and consulting page for Rahul Mittal — Blockchain Core Developer & DeFi Protocol Engineer.

**Live:** https://sunshinerider.github.io/profile-website

---

## About

Static single-page site. No framework, no build step — plain HTML/CSS/JS.

- Light + dark mode via `prefers-color-scheme`
- Writing section powered by `posts.json` — add an entry, it shows up
- Fully responsive

## Adding a Blog Post or Twitter Thread

Edit `posts.json` and add an entry:

```json
{
  "title": "Your title here",
  "subtitle": "Optional one-liner summary",
  "url": "https://x.com/SunshineRider_/status/...",
  "source": "Thread",
  "date": "Apr 2026"
}
```

`source` options: `Thread` · `Blog` · `LinkedIn`

## Structure

```
index.html      — main page
posts.json      — writing/articles manifest
rahul.png       — profile photo
README.md
```

## Stack

- HTML / CSS / Vanilla JS
- Google Fonts (Inter)
- GitHub Pages for hosting
