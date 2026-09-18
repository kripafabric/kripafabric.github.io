# Kripa Fabric - Official Modern Website Redesign

A luxury, high-converting, responsive web presence for **Kripa Fabric** (Estd. 1991, Chowk, Lucknow), crafted to replace the legacy TeleportHQ template on `https://kripafabric.github.io/`.

---

## 🌟 Key Features & Improvements

1. **Luxury Brand Identity & Heritage**:
   - Palette inspired by Awadhi royal heritage: Royal Burgundy (`#6A1425`), Champagne Gold (`#C79A2B`), and Warm Silk Ivory (`#FAF7F2`).
   - Classic editorial typography with Cormorant Garamond & Playfair Display combined with crisp Plus Jakarta Sans.
   - Highlights 34+ years of legacy supplying master Chikankari karigars, boutiques, and fashion designers.

2. **Interactive Fabric Catalog**:
   - Live category tabs: *Pure Cotton & Mulmul*, *Pure & Viscose Georgette*, *Fine Silks & Chanderi*, *Kota Doria & Chiffon*, *Designer & Prints*.
   - Real-time search by weave, yarn, GSM, and use case.
   - Fabric cards with technical specs (width, weight, dyeability, use cases).
   - Dedicated "Quick Specs" modal for each fabric category with care instructions.

3. **High-Converting B2B Wholesale Tools**:
   - **Instant WhatsApp Quote Generator**: Pre-fills buyer type, quantity (meters), city, and notes directly into an official WhatsApp inquiry format for the store desk (`+91 9839201666`).
   - One-click "Inquire on WhatsApp" buttons on every fabric card.
   - Floating WhatsApp quick-chat widget.

4. **Chikankari Craft & Base Fabric Spotlight**:
   - Educates buyers on warp/weft balance, shadow-work compatibility, pre-shrunk finish, and color absorption for delicate pastel Chikankari dyes.

5. **Authentic Store Walkthrough & Real Photos**:
   - Integrated real photos from Shop No. 10 (`inside2-1500w.jpeg`, `inside3-1500w.jpeg`, cotton fabric stacks).
   - Interactive full-screen image lightbox on click.

6. **Store Locator & Directions (Chowk, Lucknow)**:
   - Full verified address card with **"Copy Full Address"** one-click toast feedback.
   - One-click **"Get Directions"** via Google Maps GPS navigation.
   - High-fidelity Google Maps embed.

---

## 🚀 How to Deploy to GitHub Pages (`kripafabric.github.io`)

### Method 1: Git Command Line

If you have git configured with access to your repository:

```bash
# Navigate to this project folder
cd C:\Users\frien\.gemini\antigravity\scratch\kripa-fabric

# Initialize or link to your repo
git init
git remote add origin https://github.com/kripafabric/kripafabric.github.io.git

# Pull or checkout the main branch
git fetch
git checkout main

# Add files and commit
git add index.html 404.html public/ README.md
git commit -m "Revamp UI: luxury design, interactive fabric catalog & WhatsApp inquiry system"

# Push live
git push origin main
```

### Method 2: GitHub Web Interface

1. Go to [https://github.com/kripafabric/kripafabric.github.io](https://github.com/kripafabric/kripafabric.github.io).
2. Click **Add file** -> **Upload files**.
3. Drag and drop the new `index.html`, `404.html`, and `README.md` from `C:\Users\frien\.gemini\antigravity\scratch\kripa-fabric`.
4. Click **Commit changes**.
5. GitHub Pages will build and deploy the update in ~30 seconds!

---

## 💻 Local Preview

Run any local static server:

```powershell
# In PowerShell:
cd C:\Users\frien\.gemini\antigravity\scratch\kripa-fabric
python -m http.server 8088
```
Then visit `http://localhost:8088/` in your browser.
