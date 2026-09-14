# Granite City Tech Showcase — Static Microsite

A responsive, accessible static website built for **CS551S: Web Development (Assessment 1)**. This project implements a multi-page showcase platform using HTML5 and custom CSS to highlight event exhibits, visiting details, and interactive content with clean information hierarchy.

---

## Technical Features & Implementation

### Core Architecture & File Structure
* **Project Setup:** Organized with dedicated `/css/` and `/images/` subdirectories, sharing a single external stylesheet (`styles.css`).
* **Metadata & Head Elements:** Configured page-specific `<title>` tags and `<meta name="description">` strings across all HTML documents.
* **Direct Browser Loading:** Fully static implementation designed to run out of the box by opening `index.html` in any web browser.

### Layout, Accessibility & Semantic Structure
* **Semantic HTML5:** Structured using `<header>`, `<nav>`, `<main>`, and `<footer>` elements on all pages.
* **Heading Hierarchy:** Enforces strict heading levels (single `<h1>` per page with logical `<h2>`/`<h3>` nesting).
* **Accessible Media:** Includes descriptive `alt` attributes and semantic `<figure>` / `<figcaption>` elements for exhibit images (`image_creative.png`, `image_educational.png`, `image_outdoor.png`).

### Navigation & Links
* **Primary Navigation:** Consistent global navigation bar linking between **Home**, **Exhibits**, and **Visit** pages.
* **Internal Action Links:** Contextual links on the landing page connecting directly to site sub-pages.

### Visual Design & Responsive Layout
* **Fluid Layouts:** Uses modern CSS layout techniques (Flexbox/Grid and media queries) to adapt seamlessly to mobile, tablet, and desktop screens.
* **Typography & Contrast:** Ensures high color contrast and consistent spacing for optimal readability.

---

### How to Run the Project Locally
Clone or extract the project files into your working directory.

Open the site: Double-click index.html or drag it into any web browser (Chrome, Firefox, Safari, Edge).

No build tools or server installation are required.

### Accessing the Application
When opened in a browser, you can navigate between pages:

Home Page: index.html

Exhibits Page: exhibits.html

Visit Page: visit.html

### Academic Integrity & Citation
This project was completed independently as part of individual assessment requirements for CS551S at the University of Aberdeen.

---

## Project Structure

```text
/tech-showcase-site/
├── index.html                   # Home page
├── exhibits.html                # Exhibits page featuring 3 showcase areas
├── visit.html                   # Event logistics, travel & contact details
├── css/
│   └── styles.css               # Shared external stylesheet
├── images/
│   ├── image_creative.png       # Creative tech section image
│   ├── image_educational.png    # Educational tech section image
│   └── image_outdoor.png        # Outdoor tech section image
├── content.txt                  # Content specification reference
└── README.md                    # Project documentation
