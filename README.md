# 💎 Gemstone Trio Builder & Metaphysical Synergy Analyzer

[![Live Demo](https://img.shields.io/badge/Live%20Demo-GitHub%20Pages-0D9488?style=for-the-badge&logo=github)](https://yusuke614.github.io/gemstone-trio-builder/)
[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg?style=for-the-badge)](LICENSE)
[![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-success?style=for-the-badge)](index.html)
[![Guide Edition](https://img.shields.io/badge/Guide%20Edition-v19%20(5--Page%20Master)-orange?style=for-the-badge)](Gemstone_Metaphysical_Properties_Guide_v19.pdf)

> **Live Web Application:** [https://yusuke614.github.io/gemstone-trio-builder/](https://yusuke614.github.io/gemstone-trio-builder/)

A comprehensive, interactive web reference and bracelet stacking analyzer for **8 foundational gemstones**. This tool evaluates 3-gemstone combinations in real time across metaphysical chakral resonances, elemental polarities, wearing dynamics (*Receptive Left vs. Projective Right hand*), and physical **Mohs hardness clashing risks**.

Includes a complete **30-Stack Curated Intentional Trio Catalog**, the **20-Stack Incompatible Trios to Avoid Catalog**, and a **Printable 5-Page Landscape PDF Reference Guide (Edition v19)**.

---

## 🔮 Core Features & Interactive Architecture

### 1. Interactive Bracelet Trio Analyzer
* **8 Interactive Gemstone Selectors:** Click any stone chip to toggle selection. Each stone displays authentic color swatches, chakra center, elemental frequency, and Mohs hardness rating.
* **Live Bracelet Mockup String:** Displays the 3 selected gemstone beads in real time with authentic colors and chakral tags.
* **Instant Compatibility Engine:**
  * **✨ Harmonious Synergy (Curated Good Trio):** Detects matches across all **30 curated stacks**, displaying stack title, core purpose, metaphysical synergy description, primary chakral alignment, and receptive/projective wrist recommendations.
  * **⚠️ Incompatible Trio / Caution Advised (Trio to Avoid):** Detects matches across the **20 avoid stacks** (reverted to Revision 16/19), detailing the primary **Conflict** (chakra/elemental tension), **Daily Symptoms** (restlessness, fatigue, irritability, etc.), and **How to Fix** (targeted stone substitutions).
  * **🔄 Context-Dependent Synergy & Caution:** For combinations that have a curated intentional role but also carry specific situational risks (specifically *Tiger’s Eye + Red Coral + Malachite*, which serves as Curated Stack #11 *The Creative Spark & Bold Action Stack* for daytime momentum, but is categorized as Avoid Stack #3 *The 'Brake & Accelerator' Sleep Clash* if worn during bedtime rest), it triggers a specialized dual-mode amber banner and presents **both profiles side-by-side**.
  * **🔵 Custom Triad Dynamic Synthesis:** Automatically evaluates unlisted combinations in real time, calculating chakra coverage, elemental distribution, and black stone ratios.
* **🔨 Mohs Hardness Clashing & Bead Abrasion Check:** Calculates the exact hardness differential ($\Delta$) across your 3 chosen stones. If a hard stone (e.g., Tourmaline 7.5 or Onyx 7.0) touches a soft stone (e.g., Red Coral 3.5 or Malachite 3.5), it triggers an **Abrasion Hazard Warning** with specific care instructions (silicone/leather spacers or splitting between wrists).
* **Presets:** Quick-action buttons for *Random Good Trio*, *Random Avoid Trio*, *Contextual Trio*, and *Clear Selection*.

### 2. One-Click Circuit Loaders & Catalog Jump Analyzers
Every section of the application is interconnected with the live analyzer:
* **Section 3 Resonant Circuit Loaders:** Clicking **"Analyze in Tool ↗"** on any of the 4 foundational circuits instantly populates that circuit's stones into the analyzer, renders the bracelet string, evaluates compatibility, smoothly scrolls up to the top, and triggers a visual highlight glow (`highlight-flash`).
  * *The Grounding & Boundary Circuit* (`Black Onyx + Black Tourmaline + Tiger's Eye`)
  * *The Deep Catalyst & Clearing Circuit* (`Black Obsidian + Malachite + Black Tourmaline`)
  * *The Throat, Voice & Truth Circuit* (`Lapis Lazuli + Blue Turquoise + Tiger's Eye`)
  * *The Primal Vitality & Drive Circuit* (`Red Coral + Tiger's Eye + Black Onyx`)
* **Section 5 & 6 Catalog Loaders:** All **30 Curated Stacks** and **20 Avoid Stacks** feature dedicated **"Analyze in Tool ↗"** buttons that immediately load that specific trio into the active analyzer dock and scroll up to the results.
* **Section 1 Table Selectors:** Each stone row in the Master Reference Table contains a **"+ Select"** button to toggle individual stones into your active trio.
* **Robust Identifier Architecture:** All interactive buttons use clean numeric indices and slug IDs (`loadCircuit(id)`, `loadCuratedTrio(id)`, `loadAvoidTrio(id)`, `toggleStoneSelectionById(id)`), preventing string escaping collisions on stones with apostrophes (such as *Tiger’s Eye*).

### 3. Master Reference Table (Section 1)
* Live search bar across stone names, chakras, themes, and metaphysical properties.
* One-click chakra filters (*Root, Sacral, Solar Plexus, Heart, Throat, Third Eye*).
* Detailed breakdown of all 8 gemstones with core themes, affinity tags, sister stones, key properties, emotional/energetic support, and an **"+ Select"** button.

### 4. Affinities & Cross-Reference Index (Section 2)
* Interactive tabbed views for:
  * **Chakra Centers:** Alignments and shared roles across energy centers.
  * **Elemental Alignments:** Earth, Fire, Water, and Wind/Storm foundational energies.
  * **Functional Archetypes:** Complementary pairs (The Shield & Filter, The Excavators, The Communicators, The Vitalizers).
  * **Daily Wellness Applications:** Targeted stone selections for anxiety, grief, procrastination, and brain fog.

### 5. Resonant Circuits & Wearing Dynamics (Sections 3 & 4)
* **4 Resonant Circuits:** The primary energetic circuits that balance foundational intention across chakras.
* **Receptive (Left Hand) vs. Projective (Right Hand) Dynamics:** Detailed breakdown of energetic directionality and optimal stone placement.
* **The 1:1 Black Stone Ratio:** Clear guidelines on balancing protective black stones with uplifting and communicative gems.

### 6. Curated Bracelet Trios Catalog (Section 5)
* Filterable search grid containing the complete **30 Curated Intentional Stacks**.
* Complete descriptions, energetic synergies, and **"Analyze in Tool ↗"** buttons.

### 7. Gemstone Bracelet Trios to Avoid Catalog (Section 6)
* Filterable search grid containing the **20 Incompatible Stacks to Avoid** (reverted to Revision 16/19).
* Comprehensive friction analysis, physical/psychological symptoms, and targeted remedies.

### 8. Rules of Thumb & Mohs Hardness Reference (Sections 7 & 8)
* The 4 foundational stacking rules.
* Complete mineral durability table with durability tiers.
* **Interactive Bead-on-Bead Scratch Simulator:** Select any two gemstones from dropdown menus to test physical scratch vulnerability and bead abrasion risks in real time.

---

## 💎 The 8 Foundational Gemstones

| Gemstone | Primary Chakra | Element | Mohs Hardness | Durability Tier | Core Metaphysical Theme |
| :--- | :--- | :--- | :---: | :--- | :--- |
| **Black Tourmaline** | Root *(Muladhara)* | Earth | **7.0 – 7.5** | High (Durable) | Shielding, EMF Protection & Transmutation |
| **Black Onyx** | Root *(Muladhara)* | Earth | **6.5 – 7.0** | High (Durable) | Endurance, Self-Mastery & Emotional Containment |
| **Tiger’s Eye** | Solar Plexus & Root | Fire & Earth | **6.5 – 7.0** | High (Durable) | Courage, Grounded Action & Discernment |
| **Blue Turquoise** | Throat & Heart | Storm & Earth | **5.0 – 6.0** | Medium-Soft (Porous) | Wholeness, Serenity & Master Healing |
| **Black Obsidian** | Root *(Muladhara)* | Fire & Earth | **5.0 – 5.5** | Medium (Brittle) | Truth-Telling, Cord-Cutting & Shadow Integration |
| **Lapis Lazuli** | Third Eye & Throat | Water & Wind | **5.0 – 5.5** | Medium (Granular) | Inner Wisdom, Visionary Insight & Divine Truth |
| **Malachite** | Heart & Solar Plexus | Earth & Fire | **3.5 – 4.0** | Soft (Fragile) | Deep Emotional Transformation & Heart Cleansing |
| **Red Coral** | Root & Sacral | Water & Fire | **3.0 – 4.0** | Softest (Fragile) | Primal Life-Force, Passion & Bodily Resilience |

---

## 🚀 GitHub Pages Deployment

This repository is built with **zero external dependencies** (vanilla HTML5, CSS3, and ES6 JavaScript), making it fast and ready for instant deployment on GitHub Pages.

### Setup Instructions

1. **Clone or create the repository:**
   ```bash
   git clone https://github.com/yusuke614/gemstone-trio-builder.git
   cd gemstone-trio-builder
   ```

2. **Ensure `index.html` is in the repository root:**
   * The root `index.html` serves as the live entry point for GitHub Pages.

3. **Commit and push to GitHub:**
   ```bash
   git add .
   git commit -m "Release Edition v19 with header clearance on pages 2-5 and 20-stack avoid catalog"
   git branch -M main
   git push -u origin main
   ```

4. **Enable GitHub Pages:**
   * In your repository on GitHub, navigate to **Settings** > **Pages** (under "Code and automation").
   * Under **Build and deployment** > **Source**, select **Deploy from a branch**.
   * Under **Branch**, select `main` and the `/ (root)` folder.
   * Click **Save**.
   * Your site will be live at: **`https://yusuke614.github.io/gemstone-trio-builder/`**

---

## 📁 Repository Structure & Revision Archives

Following the versioning and archive structure of the interactive game wikis master hub:

```text
gemstone-trio-builder/
├── index.html                                        # Active web app (GitHub Pages root - v3)
├── Gemstone_Metaphysical_Guide_Interactive_v3.html  # Active standalone HTML guide (v3)
├── Gemstone_Metaphysical_Guide_Interactive_v2.html  # Archived standalone HTML guide (v2)
├── Gemstone_Metaphysical_Guide_Interactive_v1.html  # Archived initial HTML guide (v1)
├── Gemstone_Metaphysical_Properties_Guide_v19.pdf     # Active 5-page landscape master reference PDF (v19)
├── Gemstone_Metaphysical_Properties_Guide_v18.pdf     # Preserved milestone PDF (v18 - 30 Avoid Stacks)
├── Gemstone_Metaphysical_Properties_Guide_v16.pdf     # Preserved milestone PDF (v16 - 20 Avoid Stacks)
├── README.md                                         # Active project documentation (v4)
└── LICENSE                                           # MIT License
```

---

## 📄 Printable PDF Master Guide (Edition v19)

In addition to the interactive web application, this repository includes **`Gemstone_Metaphysical_Properties_Guide_v19.pdf`**, a print-ready, 5-page landscape reference document with full 26 pt header clearance spacing on pages 2 through 5 and the complete 20-Stack Incompatible Trios Catalog:
* **Page 1:** Section 1 (*Metaphysical & Spiritual Properties Master Reference Table* for all 8 stones).
* **Page 2:** Section 2 (*Affinities Index*), Section 3 (*Quick-Scan Synergies*), and Section 4 (*Practical Wearing Dynamics & Hand Guidelines*).
* **Page 3:** Section 5 (*Complete 30-Stack Curated Intentional Bracelet Trio Catalog* on a single page).
* **Page 4:** Section 6 (*Complete 20-Stack Incompatible Trios to Avoid Catalog* on a single page, with spacious 4-column layout).
* **Page 5:** Section 7 (*Summary Rules of Thumb for Harmonious Stacking*) and Section 8 (*Physical Wear Considerations: Mohs Hardness Clashing & Material Preservation*).

---

## 📜 License

This project is open-source and available under the [MIT License](LICENSE).
