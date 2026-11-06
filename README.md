# 📄 Resume Builder Studio

A modern, fast, and fully client-side SaaS-style resume builder built with pure **HTML5**, **CSS3**, and **Vanilla JavaScript**. No frameworks, no external dependencies, no backend, and no account required—everything runs and stays securely in your browser.

Deployable directly to **GitHub Pages** with zero configuration.

---

## 🌟 Features

### 🖥️ Dashboard & Document Management
- **Multiple Resumes**: Create, edit, duplicate, and delete multiple resumes.
- **Instant Search & Filter**: Filter resumes by name or title with real-time text search.
- **Sorting Options**: Sort by Last Modified, Name (A–Z), or Date Created.
- **Safe Deletion**: Modal confirmation dialog prevents accidental data loss.
- **Backup & Restore**: Export all your resumes as a single `.json` file and restore or transfer them across machines anytime.

### ✍️ Structured Interactive Editor
- **Personal Information**: Full name, title, contact details, LinkedIn, GitHub, portfolio URL, and profile image upload (via FileReader base64).
- **Professional Summary**: Live character counter with autosave.
- **Work Experience**: Add/remove unlimited work history items with dynamic fields (Role, Company, Location, Start/End date, bullet points).
- **Education**: Add/remove educational qualifications, degrees, fields of study, and GPA.
- **Key Projects**: Document open-source or commercial projects with links and tech stacks.
- **Skills Tag Manager**: Keyboard-driven interactive skill tag creation (supports <kbd>Enter</kbd> and `,`).

### 🎨 Design & Customization
- **3 Professional Templates**:
  - **Modern Tech Sidebar**: Sleek two-column format with dark accent sidebar and photo badge.
  - **Classic Corporate**: High-impact, ATS-friendly single-column layout with serif typography options.
  - **Minimalist Accent**: Clean, modern left-bordered layout with colored section dividers.
- **Live Theme Customizer**: Pick custom accent colors and switch between modern font families (*Inter*, *Poppins*, *Merriweather*).
- **Live Preview Canvas**: Dual-pane editor with zoom controls (50% to 130%) simulating an A4 sheet in real time.
- **UI Dark Mode**: Built-in light/dark mode switch for comfortable editing anytime.

### 🖨️ PDF Export & ATS Compliance
- Dedicated `@media print` CSS tuned specifically for standard **A4** dimensions.
- Native `window.print()` integration: hides editor chrome, dashboards, and background panels to output a clean, high-resolution vector PDF.

---

## 🚀 Live Demo

You can host this project on GitHub Pages immediately:
> `https://<your-username>.github.io/<your-repo-name>/`

---

## 🛠️ Tech Stack

- **HTML5**: Semantic markup, accessible input structures, and modals.
- **CSS3**: Custom properties (CSS variables), Flexbox, CSS Grid, media queries, print styling.
- **Vanilla JavaScript (ES6+)**: SPA architecture, DOM manipulation, `localStorage` persistence, FileReader API.
- **Google Fonts**: Inter, Poppins, Merriweather.

---

## 📂 Project Structure

```text
resume-builder-studio/
├── index.html        # Complete standalone application (HTML, CSS, JS)
├── README.md         # Project documentation
└── LICENSE           # License file (MIT)
