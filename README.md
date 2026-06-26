# Tom Pesso - Academic Portfolio Website

This repository contains the source code for the personal and academic portfolio website of **Tom Pesso** (Ph.D. Candidate in Economics at UPF/BSE).

---

## 🤖 Guide for Future AI Agents & Developers

This website is designed for high performance, simplicity, and ease of maintenance. Below is the blueprint of its architecture, design guidelines, and code conventions to help you work with this repository efficiently.

### 1. Repository Architecture
The website has been simplified from a legacy Jekyll structure to a **fully static, single-page setup**. There are no build steps, bundlers, or static site generators. GitHub Pages serves the static assets directly.

```
.
├── .gitignore
├── CNAME             # Configures the custom domain
├── index.html        # Main markup, scripts, and analytical tracking
├── index.css         # Main stylesheet (custom styling system)
├── README.md         # This documentation
├── files/            # PDF and document assets
│   ├── 12e016-econometric-methods-ii.pdf
│   ├── CV-TomPesso.pdf
│   └── JMP_TomPesso.pdf  # Keep: Used for direct URL sharing online
└── images/           # Image assets
    └── about_picture.jpeg
```

### 2. Design System & CSS Guide ([index.css](file:///c:/Users/tompe/Documents/tom-pesso.github.io/index.css))
*   **Typography**: Powered by the **Inter** font family, loaded via Google Fonts.
*   **Colors**: Sleek, academic palette focusing on readability and professionalism:
    *   Primary Text: `#111827` (Charcoal / Tailwind `gray-900`)
    *   Secondary Text: `#374151` (Tailwind `gray-700`)
    *   Accent/Link Color: `#1f4b8e` (Academic Blue)
    *   Secondary Links (Co-authors): `#4b5563` (Tailwind `gray-600`)
*   **Aesthetics**: 
    *   **"No Gray Boxes"** layout. Sections use alternate clean backgrounds, and list items or papers have distinct, clean indentation (`margin-left: 1.5rem` under headings) rather than bulky boxed borders.
    *   **Buttons** (`.btn`, `.btn-cv`, `.btn-pdf`): Outlined blue borders (`#1f4b8e`) that fill with blue and turn text white on hover.
    *   **Badges** (`.badge-jmp`, `.presentation-pill`): Small inline markers used for distinguishing the Job Market Paper (JMP) or presentation venues.

### 3. Responsive Breakpoints
The layout adapts for tablets and mobile devices via CSS media queries (`max-width: 768px`):
*   **Hero Grid**: The layout switches from a two-column side-by-side flex layout (Image | Info Text) to a single column vertical stack.
*   **Image Alignment**: Centered on mobile; left-aligned on desktop.
*   **Typography Scale**: Font sizes shrink on mobile (e.g., hero title shrinks to `2.5rem`, paragraphs shrink to `0.9rem`).

### 4. Interactive Components & Scripts
*   **Collapsible Abstracts**: Clicking `.toggle-abstract` triggers a custom vanilla JS script at the bottom of `index.html`. It performs the following:
    1. Prevents default link behavior.
    2. Collapses any other open abstracts.
    3. Toggles the `.open` class and updates the inline CSS `maxHeight` attribute to match the container's `scrollHeight`.
    4. Animates using the transition: `transition: all 0.3s ease-in-out` on the `.abstract` class.
*   **Google Analytics**:
    *   Uses Google Tag Manager (`G-ZV87M1VLDK`).
    *   Click-tracking is automated. The JS checks for any click bubble-up target containing `[data-track-category]`. If present, it fires a GA custom event using `data-track-action` and `data-track-label`.

---

## 🛠️ How-To Guides for Common Tasks

### Adding a New Working Paper or WIP
To add a new article, insert an `<article class="card">` structure inside the `#working-papers` or `#wip` sections of `index.html`:

```html
<article class="card">
    <h3 class="paper-title">Paper Title Here</h3>
    <div class="paper-details">
        <!-- Co-authors, links, etc. -->
        with <a href="LINK" target="_blank" class="link-coauthor">Co-Author Name</a>
        <span class="separator">|</span>
        <a href="#" class="btn toggle-abstract" 
           data-track-category="paper" 
           data-track-action="toggle_abstract" 
           data-track-label="paper_unique_label">abstract</a>
        <a href="files/YOUR_PDF.pdf" class="btn" 
           target="_blank" 
           data-track-category="paper" 
           data-track-action="download" 
           data-track-label="paper_unique_label">paper</a>
    </div>
    <div class="abstract">
        <p>Your abstract text here...</p>
    </div>
</article>
```

### Updating files (CV / Papers)
1. Add the new PDF file to the `files/` folder (e.g. `files/CV-TomPesso-new.pdf`).
2. Update the references in `index.html` (e.g., in the main mini-nav and the intro section buttons).
3. Delete the older version from the `files/` directory to keep the repository clean.
