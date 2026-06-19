# Huijun Wu — Homepage

Personal academic homepage for Huijun Wu (NUDT).

Layout inspired by [Jure Leskovec's Stanford page](https://cs.stanford.edu/people/jure/index.html):
dark header & footer, ~260px left sidebar with photo + menu, wide right column with name headline,
bio, news list, latest publications, education, research interests.

## Structure

```
wu_homepage/
├── index.html              # the entire homepage (single-page)
├── assets/
│   ├── css/style.css       # styling
│   └── images/profile.png  # profile photo
└── README.md
```

No build step. Plain HTML + CSS. Drop the directory onto any static host
(GitHub Pages, Netlify, Vercel, plain nginx).

## Local preview

```bash
cd ~/developement/wu_homepage
python3 -m http.server 8000
# open http://localhost:8000
```

## Deploying to GitHub Pages

If you want to publish from this folder on `sktzwhj.github.io`, replace the
existing Jekyll-based site contents with the contents of this directory
(excluding this README) and push to `main`.