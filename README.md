# 🧬 BioVerse 3D

**BioVerse 3D** is a school-focused human anatomy learning website created by **Yogesh Kumar Yadav**.

It provides a Hindi-English interface for exploring human anatomy, major body parts, body systems and selected interactive 3D models referenced/embedded from Sketchfab.

## ✨ Features

- 🦴 Interactive Human Skeleton 3D viewer
- 🫀 Human Heart 3D viewer
- 🫁 Human Lungs 3D viewer
- 🧠 Brain, eye, ear, kidney, liver, stomach and intestine learning cards
- 🔎 Sketchfab search fallback for additional anatomy models
- 🇮🇳 Hindi + English language selector
- 📚 Simple school-level explanations
- 🌍 Real-world learning examples
- 📱 Responsive mobile/tablet/desktop UI
- 🔍 SEO-ready title, description, semantic content and structured data
- 🤖 `robots.txt`
- 🗺️ `sitemap.xml`
- ♿ Semantic buttons, labels and readable text

## 🗂️ Project Structure

```text
bioverse-3d/
├── index.html
├── robots.txt
├── sitemap.xml
└── README.md
```

## 🚀 Deploy on GitHub + Vercel

### 1. Create GitHub repository

Suggested repository name:

```text
bioverse-3d-anatomy
```

### 2. Upload files

Upload:

- `index.html`
- `robots.txt`
- `sitemap.xml`
- `README.md`

### 3. Update the domain placeholders

Before or immediately after deployment, replace:

```text
https://YOUR-VERCEL-DOMAIN.vercel.app/
```

in:

- `index.html`
- `robots.txt`
- `sitemap.xml`

with the actual Vercel URL.

Also update the canonical URL and JSON-LD URL in `index.html`.

### 4. Deploy on Vercel

Import the GitHub repository into Vercel.

For this static project:

- Framework Preset: Other / Static
- Build Command: leave empty
- Output Directory: `.`
- Install Command: leave empty

Then deploy.

## 🔎 Google Search setup

After deployment:

1. Open Google Search Console.
2. Add the Vercel domain/property.
3. Verify ownership.
4. Submit:

```text
https://YOUR-VERCEL-DOMAIN.vercel.app/sitemap.xml
```

5. Use URL Inspection for the homepage and request indexing.

Indexing and ranking are controlled by Google; SEO implementation does not guarantee a first-page or first-position result.

## 🎓 SEO target topics

The website is intentionally written around useful educational queries such as:

- human anatomy 3D model
- human body 3D model
- human skeleton 3D model
- heart 3D model
- lungs 3D model
- human anatomy in Hindi
- biology 3D learning
- human organs 3D
- school biology human body
- human body parts in Hindi and English

The page contains visible text for these concepts instead of relying only on JavaScript or the 3D viewer.

## ⚖️ Third-party 3D model attribution

The 3D models displayed/referenced by this project are hosted on Sketchfab and belong to their respective creators.

Current examples include:

- Human Skeleton Highresolution model — by `l.kuzyakin`
- Anatomical Human Heart — by `Joshua Whittaker`
- Human Lung Anatomy 3D Model – Anatomi Paru-Paru — by `allalakhansa`

**Important:** Sketchfab models can have different licenses and permissions. Check each model's current Sketchfab page/license before downloading, modifying, redistributing, or commercially using any third-party asset.

This project does not claim ownership of those 3D models.

## 👨‍💻 Author

**Yogesh Kumar Yadav**

BioVerse 3D is an educational project created for school learning and demonstration.

## 📄 License

The website code can be maintained as your own project. Third-party 3D assets are **not automatically covered by the website code license** and remain subject to their respective creator/license terms.

For third-party models, always follow the model's current license and attribution requirements.
