# The Policy Signal — Your Blog

## File Structure
```
site/
├── index.html                  ← Homepage with post archive
├── about.html                  ← About page
└── posts/
    ├── us-venezuela-tanker.html   ← Post 1
    └── eu-joint-debt.html         ← Post 2
```

## How to Publish (Free, 2 minutes)

### Option 1: Netlify (Easiest)
1. Go to app.netlify.com
2. Sign up with Google
3. Drag and drop the entire `site` folder onto the page
4. Done. You'll get a URL like `random-name.netlify.app`
5. You can set a custom name like `thepolicysignal.netlify.app` for free

### Option 2: GitHub Pages (More pro)
1. Create a GitHub account
2. Create a new repository called `thepolicysignal`
3. Upload all files from the `site` folder
4. Go to Settings → Pages → Source → main branch
5. Your site will be at `yourusername.github.io/thepolicysignal`

## How to Add a New Post
1. Copy any file in `posts/` (e.g. `us-venezuela-tanker.html`)
2. Rename it with a slug (e.g. `china-south-china-sea.html`)
3. Change the title, subtitle, tags, source, and body text
4. Add a new card to `index.html` (there's a template comment in the code)
5. Push to GitHub — Netlify auto-deploys

## Custom Domain (Optional, Later)
Buy a domain like `thepolicysignal.com` from Namecheap (~$10/year)
and connect it to Netlify for free.
