# The Policy Signal — Your Blog

## File Structure
```
site/
├── index.html          ← Homepage with post archive
├── about.html          ← About page
└── posts/
    └── week12.html     ← Your first post
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
1. Copy `posts/week12.html`
2. Rename it (e.g. `week13.html`)
3. Change the title, subtitle, tags, and body text
4. Add a new card to `index.html` (there's a template comment in the code)
5. Re-upload to Netlify (just drag and drop again)

## Custom Domain (Optional, Later)
Buy a domain like `thepolicysignal.com` from Namecheap (~$10/year)
and connect it to Netlify for free.
