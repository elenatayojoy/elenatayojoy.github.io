# elenatayo.art

Your website! Built with Hugo, hosted on GitHub Pages.

---

## How to add a new update / blog post

1. Go to the `content/latest/` folder
2. Create a new file called `anything-you-like.md`
3. Copy this template:

```
---
title: "your title here"
date: 2026-03-01
description: "a short sentence about this update"
tag: art
---
```

4. Change the tag to one of: `art` `zine` `tarot` `note` `ws`
5. Save, commit, push — it's live!

---

## How to add a new artwork to the gallery

1. Put your image in `static/images/` — e.g. `my-collage.jpg`
2. Go to `content/art/` and create a new file:

```
---
title: "collage title"
date: 2026-03-01
image: "/images/my-collage.jpg"
---
```

3. Save, commit, push — done!

---

## How to preview the site locally

In Terminal, go to this folder and run:
```
hugo server
```
Then open http://localhost:1313 in your browser.

---

## How to publish changes

```
git add .
git commit -m "describe what you changed"
git push
```

Your site updates within ~60 seconds!
