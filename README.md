# LINK
[# 🎮 PUBG Live Scoreboard Overlay](https://kengthailand.github.io/pubg-Realtime-scoreboard/)
<img width="587" height="986" alt="image" src="https://github.com/user-attachments/assets/0094f83a-cac1-42ef-a24d-77a87b8ba7e4" />

# 🎮 PUBG Live Scoreboard Overlay
## ✨ Features
* **Real-Time Data:** Automatically fetches live match data from the tournament API.
* **Remote Control Panel:** Customize colors, text, and Tournament IDs remotely via a web-based dashboard.
* **Hybrid Hosting Setup:** Uses GitHub Pages for the code and local XAMPP for images/GIFs, ensuring instant graphics loading.
* **Dynamic Animations:** Includes auto-folding Top 4 logic, smooth team ranking transitions, and animated ELIMINATED/REVIVED banners.
* **Custom Fonts & Sharp UI:** Utilizes the TransducerCondensed font with broadcast-standard sharp edges and precise alignments.

## ⚙️ Installation & Setup

To use this overlay perfectly, you need to set up two parts:

### Part 1: Local Assets (XAMPP on Streaming PC)
1. Install and run **XAMPP** on your streaming PC.
2. Go to `C:\xampp\htdocs\` and create a new folder named `Keng`.
3. Place the following graphic files into `C:\xampp\htdocs\Keng\`:
   * **Team Logos:** Named exactly as their abbreviations (e.g., `TTB.png`, `R3ZO.png`).
   * **Custom Banner:** `ELIMINATED.gif`.
   * **Static Assets:** `REVIVED.png` and `Blue Chip.png` (You can also host these two directly on GitHub).

### Part 2: GitHub Pages (Control Panel)
1. Upload `index.html`, `overlay.html`, and the `.otf` font file to this GitHub repository.
2. Go to repository **Settings > Pages**.
3. Set the source to deploy from the `main` branch to make it live.

## 🚀 How to Use (Workflow)

1. **Open the Control Panel:** Open your GitHub Pages link (e.g., `https://yourusername.github.io/your-repo-name/`) on any browser/device.
2. **Configure:** Enter your Tournament ID (e.g., `sea-thsc`) and customize your desired theme colors.
3. **Copy URL:** Click the **"📋 COPY URL"** button. This will generate a special link containing all your color settings.
4. **Add to OBS:** * Open OBS Studio on your streaming PC.
   * Add a new **Browser Source**.
   * Paste the copied URL.
   * Set **Width** to `320` (Important: Do not use 270px, or the right-side icons will be cut off).
   * Set **Height** to `1000` (or according to your screen proportion).

