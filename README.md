# Lyre of Lament

A minimalist poetry site with typewriter animations, built as a single HTML file. Hosted free on Vercel.

## How to add a new poem

Open `index.html` and find the `poems` array near the bottom of the file (look for the comment **"HOW TO ADD YOUR POEMS"**). Copy this block and fill in your title and text:

```js
{
  title: "Your Poem Title",
  text:
`First line
Second line

New stanza here`
},
```

Leave a blank line between stanzas — it becomes a visual pause in the typewriter animation.

---

## Deploy to Vercel (one-time setup)

1. Push this folder to a GitHub repository.
2. Go to [vercel.com](https://vercel.com) → **Add New Project** → import your GitHub repo.
3. Vercel auto-detects it as a static site. Click **Deploy**.
4. Your site is live. Every time you push a change to GitHub, Vercel redeploys automatically.

## File structure

```
/
├── index.html    ← the entire site (edit this to add poems)
├── vercel.json   ← tells Vercel it's a static site
└── README.md     ← this file
```
