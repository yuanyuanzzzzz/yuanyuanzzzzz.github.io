# yuanyuan.github.io

Here’s an organized folder structure for your GitHub Pages website:

```
yourusername.github.io/
├── index.html               # Main homepage (HTML)
├── assets/                  # Folder for images, CV, etc.
│   ├── banner.jpg
│   ├── profile.jpg
│   └── cv.pdf
├── style/                   # Folder for CSS files
│   └── style.css
├── pages/                   # Folder for additional pages you will add later (e.g., about.html, projects.html)
│   └── placeholder.html
├── README.md                # (optional) Project description for GitHub repo
```

✅ **How to set up links:**
- In `index.html`, link images and files like this:
```html
<img src="assets/banner.jpg">
<a href="assets/cv.pdf">Download CV</a>
<link rel="stylesheet" href="style/style.css">
<a href="pages/about.html">About</a>
```

✅ **Local testing:**
1. Open `index.html` directly in your browser to preview.
2. Or use a lightweight server:
```bash
python -m http.server 8000
```
Then go to `http://localhost:8000`.

Let me know if you want me to generate the starter `style.css` and placeholder `about.html` page!
