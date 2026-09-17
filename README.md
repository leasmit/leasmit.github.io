# Lea Smit — Personal Academic & Research Website

A clean, modern, responsive, and 100% free academic website for **Lea Smit**, PhD Candidate in Zoology at the University of Pretoria Mammal Research Institute (MRI) Whale Unit.

Inspired by [gmaricato.com](https://gmaricato.com/) with a clean academic layout, dark/light mode toggle, mobile navigation, and tailored for marine mammal bio-logging, telemetry, and conservation genetics.

---

## 📂 Project Structure

```
/Users/leasmit/Documents/website/
├── index.html            # Home page (Trestles profile hero, bio, research pillars, highlights)
├── research.html         # Research page (Humpback whale population structure, CATS & satellite tagging, genomics)
├── fieldwork.html        # Fieldwork & Expeditions (RV Algoa cruise, coastal tagging, certifications)
├── publications.html     # Dissertations & theses (PhD in prep, MSc Cum Laude, BSc Hons Cum Laude) & presentations
├── teaching.html         # Teaching & Academic Service (UP Tutoring, ZSSA Student Rep & LOC)
├── cv.html               # Interactive web CV with print-to-PDF & download buttons
├── contact.html          # Contact details, affiliation, and academic links
├── .nojekyll             # Ensures GitHub Pages serves static files verbatim without Jekyll
├── assets/
│   ├── css/
│   │   └── style.css     # Styling with Lato typography, light/dark modes, and print styles
│   ├── js/
│   │   └── main.js       # Theme switcher (light/dark with persistence) and mobile menu
│   ├── images/
│   │   ├── profile.jpg       # Profile photo
│   │   ├── qr-code.png       # High-resolution QR code linking to https://leasmit.github.io/
│   │   ├── qr-code.svg       # Scalable vector QR code for posters & print
│   │   ├── qr-code-card.png  # Academic presentation card with QR code & links
│   │   ├── fieldwork-boat.jpg
│   │   ├── humpback-tails.jpg
│   │   ├── mri-whale-unit.jpg
│   │   └── whale-surface.jpg
│   └── docs/
│       └── CV_Lea_Smit.pdf   # Downloadable CV document (PDF)
└── README.md             # This guide
```

---

## 🌐 How to Publish to GitHub Pages

Your website is pre-configured and ready to publish directly to **GitHub Pages** under your account (`leasmit`).

### Step 1: Create the GitHub Repository
1. Go to [github.com/new](https://github.com/new) in your browser.
2. In the **Repository name** field, enter:
   ```
   leasmit.github.io
   ```
3. Set visibility to **Public**.
4. Leave **"Add a README file"**, **".gitignore"**, and **"license"** **UNCHECKED** (your project already has these configured).
5. Click **Create repository**.

### Step 2: Push Your Website
Open Terminal and run the following commands:
```bash
cd /Users/leasmit/Documents/website
git push -u origin main
```

*(If prompted for authentication, log in with your GitHub account or a Personal Access Token).*

### Step 3: Verify Your Site is Live
Once pushed, your website will be live in ~60 seconds at:
👉 **https://leasmit.github.io/**

---

## 📱 QR Code for Posters & CVs
A scannable QR code linking to **https://leasmit.github.io/** is located in:
- `assets/images/qr-code.png` (High-res PNG for print, slides, and posters)
- `assets/images/qr-code.svg` (Infinite resolution vector format)
- `assets/images/qr-code-card.png` (Presentation card layout)

---

## 🚀 Local Preview

Double-click `index.html` in Finder to open it in your browser, or run:
```bash
python3 -m http.server 8080
```
Then visit [http://localhost:8080](http://localhost:8080).
