# 🎤 StagePlot v2 (v1.4.1)

StagePlot v2 is a fast, offline-capable stage plot builder for bands, venues, and sound engineers.

Drag gear onto a stage, label inputs and monitor mixes, add notes, and print a clean one-page handoff (or save it as a PDF). No accounts. No clutter. Works on desktop, tablet, and phone.

---

## ✅ What it does
- Build a stage diagram in real-world feet (Width x Depth)
- Add musicians + gear from a built-in library (plus quick “Misc” blocks)
- Auto-generate a readable Inputs list + Monitor Mix list
- Add item notes and show notes (load-in, backline, contact, etc.)
- Print a clean one-page sheet for venues and engineers
- Export/import a project JSON to share with bandmates or FOH

---

## ✨ Features

### 🧱 Visual stage builder
- Stage presets plus custom size (feet)
- Drag-and-drop musicians, instruments, wedges, risers, power, and more
- Scale + rotate items
- Color-code and label for fast reading
- Works with mouse, touch, trackpad

### 🎛️ Inputs and monitor mixes
- Inputs list auto-generated from stage items
- Monitor mix list grouped automatically
- Notes per item + notes per show

### 🧰 Item library
- Built-in gear catalog
- Import/export custom libraries (JSON)
- Quick-add Misc blocks (small/medium/large) for anything weird on the fly

### 🖨️ One-page print output (and PDF)
- Stage diagram + inputs + mixes + notes
- Designed to fit on a single page
- Venue-friendly, readable layout

### 📦 Project files
- Export/import complete stage plots as JSON
- Easy sharing between band, FOH, and venues

### 📱 Mobile-friendly + PWA
- Responsive layout + touch-optimized dragging
- Installable on iOS, Android, and desktop
- Works offline (no backend required)

---

## 🚀 Getting started

### Option 1 - Use it online
Host the files on GitHub Pages (or any static web server) and open `index.html`.

### Option 2 - Install as an app (PWA)
1. Open StagePlot in your browser
2. Use “Add to Home Screen” (mobile) or “Install App” (desktop)
3. Use it offline at gigs and rehearsals

---

## 🧭 Quick workflow
1. Pick a stage size (preset or custom)
2. Add items from the library (or drop Misc blocks for mystery gear)
3. Click items to set label, input, mix, color, and notes
4. Add show notes (load-in, contact, backline, set length, parking)
5. Print or save to PDF, then send it to the venue

---

## 🖨️ Printing and saving as PDF

Use the in-app **Print** button (not the browser menu) so StagePlot can switch into the print-safe one-page layout first.

### Windows (PC)
- Print
- Choose **Microsoft Print to PDF**
- Print
- Save

### macOS (Mac)
- Print
- Click **PDF** (bottom-left)
- **Save as PDF**

### iPhone / iPad (iOS)
- Print
- On the preview, **pinch out (zoom)** to open the PDF view
- Share
- Save to Files

### Android
- Print
- Choose **Save as PDF**
- Save

Troubleshooting tip:
- If print preview looks blank, hit the app Print button again. Some browsers need a quick rerender.
- If you are using an installed PWA and printing is weird, try printing from the normal browser tab once.

---

## 📁 Project structure
/
├─ index.html
├─ guide.html
├─ manifest.json
├─ service-worker.js
├─ stageplotlogo.png
└─ icons/
├─ icon-192.png
├─ icon-512.png
├─ maskable-192.png
└─ maskable-512.png
---

## 🧠 How it works
- The stage is defined in feet (Width x Depth)
- Items are stored in stage coordinates and scaled visually
- Inputs and monitor mixes are generated from your item data
- Everything saves locally in your browser via localStorage (no cloud dependency)
- Export JSON is your portable backup and share file

---

## 🛠️ Customization

### Add custom gear fast (Misc blocks)
Use **+ Misc 1 / + Misc 2 / + Misc 3** to drop generic gear boxes, then rename, resize, rotate, and color them.

### Add custom gear properly (Library JSON)
1. Export your library
2. Edit or create new item definitions
3. Import the updated library JSON

Perfect for:
- Venue-specific power drops
- Lighting elements
- Backline variations
- Oddball instruments and special requests

---

## 🧩 Tech stack
- Vanilla HTML / CSS / JavaScript
- SVG icons for crisp visuals
- No frameworks
- No build step
- No backend

---

## ❤️ Why StagePlot exists
Stage plots should be:
- Fast to make
- Easy to read
- Easy to share
- Usable at load-in, not just buried in email threads

StagePlot v2 is built by musicians and event organizers who actually use this stuff in the real world.

---

## 📄 License
MIT License - Use it, remix it, improve it, ship it.

---

## 🧠 Ideas for v3 (Pinned)
- Snap-to-grid
- Cable runs / arrows
- FOH view toggle
- Dark/light print themes
- Optional extra export formats
