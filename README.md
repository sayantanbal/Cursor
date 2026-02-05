# Cursor Landing Page Clone

A pixel-perfect recreation of the [Cursor](https://cursor.com) landing page using only HTML and CSS. This project demonstrates visual and structural accuracy without JavaScript, TailwindCSS, or animations.

## 📸 Preview

![Landing Page Preview](screenshots/preview.png)

## ✅ Sections Recreated

All 11 sections from the original design have been implemented:

| # | Section | Status |
|---|---------|--------|
| 1 | **Top Navigation Bar** | ✅ Complete |
| 2 | **Hero Section** | ✅ Complete |
| 3 | **Trusted By / Logos** | ✅ Complete |
| 4 | **Feature Sections (3 blocks)** | ✅ Complete |
| 5 | **Feature Cards Section** | ✅ Complete |
| 6 | **Testimonials** | ✅ Complete |
| 7 | **Changelog / Updates** | ✅ Complete |
| 8 | **About / Team** | ✅ Complete |
| 9 | **Recent Highlights** | ✅ Complete |
| 10 | **Final CTA** | ✅ Complete |
| 11 | **Footer** | ✅ Complete |

## 🎨 Design System

### Fonts

- **Primary Font:** Inter (Google Fonts)
- **Weights Used:** 400 (Regular), 500 (Medium), 600 (Semi-bold), 700 (Bold)
- **Code Font:** SF Mono, Monaco, Inconsolata, Fira Code (system monospace)

### Color Palette

| Color | Hex Code | Usage |
|-------|----------|-------|
| Background Primary | `#0a0a0a` | Main page background |
| Background Secondary | `#111111` | Cards, sections |
| Background Tertiary | `#1a1a1a` | Code blocks, sidebars |
| Background Card | `#161616` | Card backgrounds |
| Text Primary | `#ffffff` | Headings, main text |
| Text Secondary | `#a1a1a1` | Body text, descriptions |
| Text Muted | `#6b6b6b` | Labels, metadata |
| Accent Green | `#00d084` | Links, CTAs, highlights |
| Border Color | `#2a2a2a` | Borders, dividers |
| Diff Added | `#3fb950` | Code additions |
| Diff Removed | `#f85149` | Code deletions |

### Code Syntax Colors

| Element | Hex Code |
|---------|----------|
| Keywords | `#c586c0` |
| Strings | `#ce9178` |
| Functions | `#dcdcaa` |
| Tags | `#569cd6` |
| Attributes | `#9cdcfe` |

## 📁 Project Structure

```
cursor-landing-page/
├── index.html      # Main HTML file with all sections
├── styles.css      # Complete CSS styling
├── README.md       # Project documentation
└── screenshots/    # Preview images (optional)
    └── preview.png
```

## 🚀 How to Run

1. Clone the repository:
   ```bash
   git clone https://github.com/sayantanbal/Cursor.git
   ```

2. Navigate to the project folder:
   ```bash
   cd Cursor
   ```

3. Open `index.html` in your browser:
   - Double-click the file, or
   - Use Live Server extension in VS Code, or
   - Run `open index.html` (macOS) / `start index.html` (Windows)

## 🔧 Technical Details

### Constraints Met

- ✅ Only HTML and CSS used
- ✅ No JavaScript
- ✅ No TailwindCSS
- ✅ No animations or fancy effects
- ✅ Desktop-only (no responsiveness required)

### Key Features

- **Fixed Navigation:** Sticky header with blur effect using `backdrop-filter`
- **CSS Grid:** Used extensively for layouts (feature sections, cards, footer)
- **CSS Flexbox:** Used for alignment and component layouts
- **CSS Variables:** Centralized color palette for easy theming
- **Semantic HTML:** Proper use of `<nav>`, `<section>`, `<footer>`, etc.
- **Mock UI Components:** Recreated editor screenshots, chat interfaces, and code snippets

## 📐 Layout Specifications

- **Max Width:** 1200px (content container)
- **Navigation Height:** 64px
- **Section Padding:** 100px vertical
- **Card Border Radius:** 12px
- **Grid Gap:** 24px

## 🖼️ Assets Notes

Since brand assets couldn't be directly fetched, the following approximations were made:

- **Logo:** SVG recreation of the Cursor logo style
- **Company Logos:** Text-based representations
- **Author Avatars:** Placeholder circles with initials
- **Screenshots:** CSS-based mock recreations

## 📝 License

This project is for educational purposes only. The original design belongs to [Cursor/Anysphere Inc.](https://cursor.com)

## 👤 Author

Created as part of a frontend development assignment.
