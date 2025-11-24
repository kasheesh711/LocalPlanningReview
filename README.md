# Local Supply Chain Center

A fully offline React dashboard for exploring inventory, BOM, and network risk data. Starter CSV files ship inside the app so you can run everything on your laptop with no internet connection.

## What you'll need
- **Node.js LTS** from [nodejs.org](https://nodejs.org) (click "LTS" and install with all defaults).
- About 5 minutes and a browser (Chrome, Edge, Safari, or Firefox).

## Quick start (no coding required)
1. **Get the project**
   - Download or copy this folder to your computer. If you used a ZIP download, right‑click and choose **Extract All** (Windows) or **Open With → Archive Utility** (macOS).
2. **Open the project folder**
   - Windows: open File Explorer, go to the extracted folder, then click the address bar, type `cmd`, and press **Enter**.
   - macOS: open Finder, right‑click the folder, choose **New Terminal at Folder**.
3. **Install the app**
   - In the terminal window that appears, run:
     ```bash
     npm install
     ```
     This downloads everything the app needs for offline use.
4. **Start the dashboard**
   - In the same window, run:
     ```bash
     npm start
     ```
   - When you see a local link like `http://localhost:5173/`, click it (or copy it into your browser). Leave the terminal window open while you browse the dashboard.
5. **Close it later**
   - Return to the terminal and press **Ctrl + C** (or **⌘ + C** on macOS) to stop the app.

## Using your own data (still offline)
- Starter files live in `src/data/inventory.csv` and `src/data/bom.csv`.
- To replace them while the app is running, click **Import CSV** for inventory or **Import BOM** for the bill of materials and pick your own `.csv` files.
- Want to ship the app with different defaults? Replace the CSV files in `src/data/` and restart `npm start`.

## Handy scripts
- `npm start` – run the dashboard locally.
- `npm run build` – create a production build (generates static files in `dist/`).
- `npm run lint` – check code quality.

Everything works without an internet connection once the dependencies are installed.
