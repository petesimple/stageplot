🎤 StagePlot v2 (v1.5.9 – reset)

StagePlot v2 is a fast, offline-capable stage plot builder for bands, venues, and sound engineers.

Drag gear onto a stage, label inputs and monitor mixes, add notes, flip stage perspective, zoom your view for precision, and print a clean one-page handoff (or save it as a PDF).

No accounts. No clutter. Works on desktop, tablet, and phone.

⸻

✅ What it does
	•	Build a stage diagram in real-world feet (Width x Depth)
	•	Add musicians and gear from a built-in library (plus quick “Misc” blocks)
	•	Auto-generate readable Inputs and Monitor Mix lists
	•	Add item notes and show notes (load-in, backline, contact, etc.)
	•	Flip between Stage View and Audience View
	•	Zoom your view for precision without changing physical scale
	•	Print a clean one-page sheet for venues and engineers
	•	Export and import project files as JSON to share with bandmates or FOH

⸻

✨ Features

🧱 Visual stage builder
	•	Stage presets plus custom size (feet)
	•	Drag-and-drop musicians, instruments, wedges, risers, power, and more
	•	Scale and rotate items
	•	Color-code and label for fast reading
	•	Works with mouse, touch, and trackpad

🔍 Scale vs View Zoom (important distinction)
	•	Scale changes the physical size of an item on the stage
	•	View Zoom zooms your view in and out inside the stage square
	•	Zoom in to fine-tune placement, zoom back to 100 percent for a clean overview
	•	Reset View button instantly returns the view to 100 percent
	•	Stage always stays fully visible at 100 percent (no cut-off edges)

🔄 Stage View and Audience View
	•	Default layout follows standard convention: upstage at top, audience at bottom
	•	One-click toggle to flip the entire plot to Audience View
	•	Items rotate and reposition correctly with a true 180-degree flip
	•	Useful for thinking like a performer or like FOH

🎛️ Inputs and monitor mixes
	•	Inputs list auto-generated from stage items
	•	Monitor mix list grouped automatically
	•	Notes per item and notes per show

🧰 Item library
	•	Built-in gear catalog
	•	Import and export custom libraries (JSON)
	•	Quick-add Misc blocks (small, medium, large) for anything weird on the fly

🖨️ One-page print output (and PDF)
	•	Stage diagram plus inputs, mixes, and notes
	•	Designed to fit on a single page
	•	Venue-friendly, readable layout
	•	Uses system print-to-PDF for universal reliability

📦 Project files
	•	Export and import complete stage plots as JSON
	•	Easy sharing between band, FOH, and venues

📱 Mobile-friendly and PWA
	•	Responsive layout with touch-optimized dragging
	•	Accordion panels on mobile to save space
	•	Installable on iOS, Android, and desktop
	•	Works offline (no backend required)

⸻

🆕 What’s new in v1.5.9
	•	Minor UI and layout polish
	•	Improved zoom and reset behavior
	•	Better print consistency across browsers
	•	Small interaction fixes and stability improvements
	•	Prep work for future v2.x refinements

(No breaking changes. Existing projects remain compatible.)

⸻

🚀 Getting started

Option 1: Use it online

Open the app here:
https://petesimple.github.io/stageplot/

Option 2: Install as an app (PWA)
	1.	Open StagePlot in your browser
	2.	Use “Add to Home Screen” (mobile) or “Install App” (desktop)
	3.	Use it offline at gigs and rehearsals

⸻

🧭 Quick workflow
	1.	Pick a stage size (preset or custom)
	2.	Add items from the library (or drop Misc blocks for mystery gear)
	3.	Click items to set label, input, mix, color, scale, rotation, and notes
	4.	Zoom in to fine-tune placement if needed
	5.	Add show notes (load-in, contact, backline, set length, parking)
	6.	Choose Stage View or Audience View if useful
	7.	Print or save as PDF and send it to the venue

⸻

🖨️ Printing and saving as PDF

Use the in-app Print button (not the browser menu) so StagePlot can switch into its print-safe one-page layout first.

Windows (PC)
	•	Print
	•	Choose Microsoft Print to PDF
	•	Print
	•	Save

macOS (Mac)
	•	Print
	•	Click PDF (bottom-left)
	•	Choose Save as PDF

iPhone and iPad (iOS)
	•	Tap Print
	•	In the preview, pinch out (zoom) to open the PDF view
	•	Tap Share
	•	Save to Files or send it

Android
	•	Tap Print
	•	Choose Save as PDF
	•	Save

Troubleshooting
	•	If print preview looks blank, click the app Print button again
	•	Some browsers need a brief rerender before painting
	•	If printing from an installed PWA is odd, try printing from a normal browser tab once

⸻

📁 Project structure

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

⸻

🧠 How it works
	•	The stage is defined in feet (Width x Depth)
	•	Items are stored in stage coordinates and scaled visually
	•	View Zoom is purely visual and does not affect print scale
	•	Inputs and monitor mixes are generated from item data
	•	Everything saves locally in your browser via localStorage
	•	Exported JSON files are your portable backup and share format

⸻

🛠️ Customization

Add custom gear fast (Misc blocks)

Use + Misc 1 / + Misc 2 / + Misc 3 to drop generic gear boxes, then rename, resize, rotate, and color them.

Add custom gear properly (Library JSON)
	1.	Export your library
	2.	Edit or create new item definitions
	3.	Import the updated library JSON

Perfect for:
	•	Venue-specific power drops
	•	Lighting elements
	•	Backline variations
	•	Oddball instruments and special requests

⸻

🧩 Tech stack
	•	Vanilla HTML, CSS, JavaScript
	•	SVG icons for crisp visuals
	•	No frameworks
	•	No build step
	•	No backend

⸻

❤️ Why StagePlot exists

Stage plots should be:
	•	Fast to make
	•	Easy to read
	•	Easy to share
	•	Usable at load-in, not just buried in email threads

StagePlot is built by musicians and event organizers who actually use this stuff in the real world.

⸻

📄 License

MIT License
Use it, remix it, improve it, ship it.

⸻

🧠 Ideas for v3 (Pinned)
	•	Snap-to-grid
	•	Cable runs and arrows
	•	FOH view toggle refinements
	•	Dark and light print themes
	•	Optional additional export formats