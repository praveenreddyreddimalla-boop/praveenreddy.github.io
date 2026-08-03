# cybersecurity_availabilty_blog — website

A static mini-blog matching your Instagram page: a home page listing all 30 posts from your content calendar, plus a full article page for each one, styled with your logo's navy/cyan/teal theme.

## What's in this folder

- `index.html` — home page (post list)
- `posts/` — 30 individual article pages
- `assets/logo.png` — your profile logo, used as the site icon
- `style.css` — shared styling

No build tools, servers, or dependencies needed — it's plain HTML/CSS that works by itself.

## Publish it for free with GitHub Pages (you already have a GitHub account)

1. Go to https://github.com/new and create a new repository. Name it anything — a common choice is your username followed by `.github.io` (e.g. `yourusername.github.io`), which gives you the shortest possible URL. Any other name works too, it just adds `/reponame` to the URL. Leave it Public. Don't add a README (you already have one here).
2. On the new repo's page, click **"uploading an existing file"** (or the **Add file → Upload files** button).
3. Drag in *everything* from this folder — `index.html`, `style.css`, `README.md`, and the two folders `posts` and `assets` (drag the folders in directly; GitHub's upload preserves the folder structure).
4. Scroll down and click **Commit changes**.
5. Go to the repo's **Settings** tab → **Pages** (left sidebar) → under "Build and deployment", set **Source** to **Deploy from a branch**, branch **main**, folder **/(root)** → **Save**.
6. Wait about a minute, then refresh that Pages settings screen — GitHub will show your live URL at the top:
   - `https://yourusername.github.io/` (if you named the repo `yourusername.github.io`)
   - or `https://yourusername.github.io/reponame/` (for any other repo name)

That URL is what you can put in your Instagram bio link.

## Updating it later

To add more days/posts later, just message me — send the new topics and I'll generate the extra pages in the same style, then you re-upload the changed/added files the same way (GitHub will ask if you want to replace the existing ones — say yes).

If you'd rather edit small wording tweaks yourself: open any file in the repo on GitHub, click the pencil (✏️) icon to edit directly in the browser, then commit — no local setup needed.
