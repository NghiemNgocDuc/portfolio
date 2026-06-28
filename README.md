# Duc Nghiem — Portfolio

Live at: `https://NghiemNgocDuc.github.io/portfolio`

---

## Folder structure

```
duc-portfolio/
├── index.html              ← the entire site
├── assets/
│   └── Duc_Nghiem_resume.pdf   ← drop your resume here
├── images/
│   ├── avatar.jpg              ← your profile photo (square, min 400×400)
│   ├── photo1.jpg              ← carousel photos
│   ├── photo2.jpg
│   ├── photo3.jpg
│   ├── photo4.jpg
│   ├── photo5.jpg
│   ├── photo6.jpg
│   ├── project-guardrail.jpg   ← project screenshots (16:9)
│   ├── project-cropscan.jpg
│   ├── project-sharebooth.jpg
│   └── project-dragsoccer.jpg
└── README.md
```

---

## How to add images

### 1 — Profile photo
Drop any square image into `images/` named `avatar.jpg`, then in `index.html` find:

```html
<!-- AVATAR: replace the div below with: -->
<div class="avatar-wrap"><img src="images/avatar.jpg" alt="Duc Nghiem"></div>
```

Delete the `<div class="avatar-placeholder">...</div>` block and paste the line above in its place.

### 2 — Project screenshots
Drop 16:9 screenshots into `images/`. For each project card, find the comment like:

```html
<!-- PROJECT IMAGE: replace div below with:
<div class="project-img-wrap"><img src="images/project-guardrail.jpg" alt="LLM Guardrail"></div>
-->
```

Delete the `<div class="img-placeholder">...</div>` and paste the uncommented line in its place.

### 3 — Carousel photos
Drop any personal photos into `images/` named `photo1.jpg` … `photo6.jpg`. Then in `index.html` find each carousel-slide placeholder and replace with:

```html
<div class="carousel-slide"><img src="images/photo1.jpg" alt=""></div>
```

Do this for **both** sets (the original 6 and the duplicate 6 below — needed for the seamless loop).

---

## Host on GitHub Pages (free, takes 2 minutes)

1. Go to https://github.com/new
2. Create a repo called **`portfolio`** (keep it public)
3. Upload this entire folder (drag & drop all files into the repo)
4. Go to **Settings → Pages**
5. Under "Branch" select `main` and folder `/root`, click **Save**
6. Your site is live at `https://NghiemNgocDuc.github.io/portfolio`

> Want a custom domain like `ducnghiem.dev`?  
> Buy it on Namecheap/Cloudflare, then in Pages settings add it under "Custom domain".

---

## Or host on Netlify (drag & drop, even easier)

1. Go to https://netlify.com and sign in with GitHub
2. Drag the entire `duc-portfolio` folder onto the Netlify dashboard
3. Done — you get a live URL immediately (e.g. `duc-portfolio.netlify.app`)
4. Connect your GitHub repo later for auto-deploys on every push

---

## Resume
Drop `Duc_Nghiem_resume.pdf` into the `assets/` folder. The Resume button in the hero already links to `assets/Duc_Nghiem_resume.pdf`.
