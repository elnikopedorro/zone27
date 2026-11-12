# Potrero Sector Map & Blitz Exam Trainer (Zones 27A / 27B / 27C)

An interactive, browser-based tactical navigation trainer and certification exam built around the **Potrero, California** sector map (**Zones 27A, 27B, and 27C**). Designed for field personnel, navigators, and trainees learning the road networks, numbered trail markers (`1T`–`18T`), and key tactical landmarks along the Tecate / CA-94 corridor.

---

## Included Applications

1. **`potrero_map_trainer.html` — Interactive Sector Map & Multi-Mode Trainer**
   - **Study / Explore Mode:** Pan and zoom across an upright (North-Up) vector schematic of Zones 27A, 27B, and 27C. Tap any marker, intersection, or landmark to inspect its tactical notes and direct road connections, or toggle map labels off to self-quiz.
   - **Landmark Locator:** Pinpoint target landmarks directly on the map with labels hidden.
   - **Route Nav:** Navigate turn-by-turn across connected roads (`Airport Rd`, `Harris Ranch Rd`, `Ridge Rd`, `Old 94`, `G-Road`, `The Grade`, and `Bell Valley Rd`).
   - **Sector Blitz & Exam Mode:** Rapid-fire drills and a built-in 10-question certification check.

2. **`potrero_sector_blitz_exam.html` — Standalone Sector Blitz Exam Portal**
   - **Configurable Exam Sessions:** Choose between **10, 20, or 30 questions**, filter by specific zones (**All Zones**, **27A**, **27B**, or **27C**), and toggle between **Timed Blitz (20s/question)** or **Untimed Study** pacing.
   - **32+ Tactical Routing & Landmark Scenarios:** Covers turn-by-turn routes, sequential trail markers, next-waypoint checks, and sector identification.
   - **Post-Answer Map Verification:** Automatically illuminates the verified route from origin (blue) to destination (green) on the synchronized SVG schematic map after each answer.
   - **Scorecard & Missed-Route Review:** Displays zone-by-zone accuracy breakdowns, average response times, an interactive route inspector map, and a **Retake Missed Questions Only** option.

---

## Sector Coverage Overview

| Sector | Geographic Orientation | Key Roads, Markers & Landmarks |
| :--- | :--- | :--- |
| **Zone 27A** | West Sector (Border / Park) | Tecate POE, Airport Rd, Water Tank, Cement Pillars, `1T`–`8T`, Marron's/Murphy's Ranch, 3-Corners, Potrero Park, Four Corners, Camphor Park, Old Baker Rd, Cemetery (27A), Harris Ranch Rd |
| **Zone 27B** | South-East Sector (Ridge / Border) | Red House, Ridge Rd, `8T`–`13T`, `12+1 Slope`, 11 Tear Canyons Rd, 9-Dead, Brickyard High Point, Brickyard, Little Cutie, Cat's Cradle, 297 Monument, Tire Shop, Hwy 94 |
| **Zone 27C** | North-East Sector (Bell Valley) | Potrero Creek, Buzzards Roost, Old 94, Magic Banana, Rick's Notch, Waterfalls, Bee Hives, Bell Valley Rd, National Guard Lot, Bug Out, `13T`–`18T`, `15/4 Turnout`, G-Road, The Grade, Bob's Porch, Bell Valley Overlook |

---

## Getting Started & GitHub Pages Deployment

Both applications are built as zero-dependency, single-file HTML apps using Tailwind CSS (via CDN) and inline SVG/JavaScript—no build tools or servers required.

### Run Locally
1. Download `potrero_map_trainer.html` and/or `potrero_sector_blitz_exam.html`.
2. Double-click either `.html` file to open it directly in any desktop or mobile web browser.

### Host on GitHub Pages
1. Create a new GitHub repository and upload `README.md`, `potrero_map_trainer.html`, and `potrero_sector_blitz_exam.html` (optionally rename your preferred landing file to `index.html`).
2. Go to **Settings → Pages** in your repository.
3. Under **Source**, select **Deploy from a branch**, choose `main` (`/root`), and click **Save**.
4. Your live training site will be accessible at `https://<your-username>.github.io/<repository-name>/`.