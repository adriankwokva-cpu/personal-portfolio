# Adrian Kwok — Portfolio

## Run it locally
1. Install Node.js (LTS) from https://nodejs.org if you haven't.
2. Open Terminal, cd into this folder (type `cd ` then drag the folder in).
3. Run: npm install     (one time)
4. Run: npm run dev      (preview at http://localhost:4321)
5. Edit src/pages/index.astro — the browser updates as you save.

## What to edit
- Projects: the list at the very top of src/pages/index.astro.
- Links: the <nav class="links"> section (email, LinkedIn, GitHub URLs).
- The "-  -  -" placeholders are the tags row. Replace with real tags,
  e.g. tags: ["Python", "ML", "Research"], or set tags: [] for none.

## Fonts
- "Adrian Kwok" and "Projects I'm Working On:" use Lora (loaded from Google Fonts).
- The three links use Georgia.
- Everything else uses Arial.

## Deploy
Push to GitHub, connect to Cloudflare Pages
(build command: npm run build, output dir: dist), then add your custom domain.
