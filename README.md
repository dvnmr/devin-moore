# Devin Moore — Personal Portfolio

**What it is:** A static, two-page personal professional portfolio for Devin Moore of Biloxi, Mississippi — field electrician (IBEW training background) and builder of the CORTEX AI-assisted operating workflow. It tells the dual story truthfully: the trade, the systems work, the real IBM quantum experiments (predictions locked before runs, results stated with receipts), and his three-bucket direction (credential / off the tools / long-range).

**Pages:**
- `index.html` — single-page portfolio: hero, about, skills (electrical + technical), projects, the three-bucket direction, contact.
- `projects.html` — build notes with receipts: CORTEX (typed CLAIM records, deterministic Rust validator, Kani results stated honestly at 13 of 19), the CHSH and GHZ runs on ibm_marrakesh (job IDs and numbers as recorded), Moore Electric, and the crew method.

**Tech:** Pure static HTML + one CSS file. No build step, no JavaScript, no external assets except Google Fonts (Anton / Inter / JetBrains Mono). Dark theme echoing 228mooreelectric.com (near-black, electric blue #19c8fa, volt #ffd400). Mobile-first, sticky mobile call bar, semantic HTML with alt text throughout.

**Images (`img/`):** All real job photos from Devin's own library — no stock.
- `og-image.jpg` — 1200×630 social card composited with PIL from `photo-040.jpg` (the golden-hour pier house job photo) with the name/title set over a legibility gradient.
- `hero.jpg` — pier soffit with blue LED recessed lighting (gallery photo-042).
- `panel-ev.jpg` — panel + ChargePoint EV charger (photo-006). `meter.jpg` — corroded meter socket diagnostic find (photo-036).

**Claims discipline:** No claim of state licensure, insurance, or an LLC appears anywhere (none is true yet). Ratings quoted are the recorded ones (HomeAdvisor 4.9/5 across 8 reviews; Facebook 100% recommended).

**Publish:** Drop the folder contents on any static host. `og:image` is referenced as a relative path (`img/og-image.jpg`) — after publishing, swap it to the absolute published URL in both HTML files so social scrapers resolve it.
