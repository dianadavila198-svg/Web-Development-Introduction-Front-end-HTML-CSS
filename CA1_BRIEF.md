# CS551S: Web Development

## Assessment 1: Individual Coursework (no group work)

This part of the assessment contributes **25%** of the overall mark for the module. Marks for individual questions and items appear in the specification below.

---

## Learning Outcomes

This assessment, through its various tasks, has the following learning outcomes:

* Ability to build valid, accessible static pages using HTML5 and CSS
* Skills in structuring multi section content and applying responsive layout techniques
* Competence in designing simple navigation with clear information hierarchy
* Understanding of basic branding choices and visual emphasis through typography and colour

---

## Plagiarism and Collusion

This is an individual assessment, not a team based one; its purpose is to assess your knowledge, not your ability to find answers on the Internet. Submissions may be checked for similarity and investigated if there is evidence of collusion. You must appropriately cite all materials you have used in your work. Plagiarism and collusion are serious issues and will not be tolerated.

It is your responsibility to familiarise yourself with the University's code of practice on Student Discipline: [https://tinyurl.com/y92xgkq6](https://tinyurl.com/y92xgkq6)
Please also read the following information provided by the university: [https://www.abdn.ac.uk/sls/online-resources/avoiding-plagiarism/](https://www.abdn.ac.uk/sls/online-resources/avoiding-plagiarism/)

---

## Frontend Assessment

### Static Microsite: Granite City Tech Showcase

**Overview**

Build a small static website using only the wording supplied in **`content.txt`** and the supplied images. Do not add new wording. Your task is to place the given text into suitable HTML elements, style with CSS, and ensure it works well on different screen sizes.

**Pages required**

* `index.html` (Home)
* `exhibits.html` (Exhibits)
* `visit.html` (Visit)

All pages must share one external stylesheet and include a header, simple navigation, a main content area, and a footer.

---

## Task 1: Project Setup and File Structure (10 marks)

Set up the site files and head elements.

* Create the folder structure exactly as shown in Required Structure and link `/css/styles.css` from all pages (2 marks)
* Each page has a meaningful `<title>` based on `content.txt` (2 marks)
* Each page includes the meta description from `content.txt` in the `<head>` (3 marks)
* Project opens by loading `index.html` in a browser with no extra steps (3 marks)

---

## Task 2: Structure and Content Placement (35 marks)

Place the wording from `content.txt` on the correct pages with clear structure.

* Use `<header>`, `<nav>`, `<main>`, `<footer>` correctly (5 marks)
* One `<h1>` per page and a logical heading order for other headings (5 marks)
* Insert the exact text from `content.txt` in the order it appears for each page (10 marks)
* On `exhibits.html`, create three areas using the headings from `content.txt`, each with one paragraph and one image (10 marks)
* Footer shows the year **2026** and the text **GTS** exactly as written in `content.txt` (5 marks)

---

## Task 3: Navigation and Linking (10 marks)

Ensure the pages and in page links work.

* Primary navigation links correctly between Home, Exhibits, and Visit on all pages (5 marks)
* Implement the Home page links to Exhibits and Visit using the exact link wording from `content.txt` (5 marks)

---

## Task 4: Images and Text Alternatives (10 marks)

Use the supplied images with correct text alternatives and captions.

* Use the correct image file on each area of `exhibits.html` (3 marks)
* Use the correct `alt` text strings from `content.txt` for each image (4 marks)
* Display a short caption under each image using the wording provided in `content.txt` where given (3 marks)

---

## Task 5: Visual Design and Responsive Layout (20 marks)

Apply consistent styling and make the layout adapt to different screen sizes.

* Consistent typography and spacing throughout the site (5 marks)
* Readable text with appropriate colour contrast (5 marks)
* Sensible layout that works on mobile, tablet, and desktop (10 marks)

---

## Materials Provided

* `content.txt` containing all page text, meta descriptions, image alt text, anchor IDs, and short notes in comments
* `images/image_creative.png`
* `images/image_educational.png`
* `images/image_outdoor.png`

Use the wording from `content.txt` 

---

## Required Structure

```
/tech-showcase-site/
  index.html
  exhibits.html
  visit.html
  /css/
    styles.css
  /images/
    image_creative.png
    image_educational.png
    image_outdoor.png
  content.txt
```

---

## Required Page Content

Each page must use the content from `content.txt`:

* **Home**: page heading, welcome text, brief description of what is on show, links to Exhibits and Visit
* **Exhibits**: short overview, three named areas, one image and one short paragraph per area, captions and IDs as given
* **Visit**: essentials (date, place, time), travel, access, contact, and the closing note

---

## Submission Instructions

Submit a **.zip** on MyAberdeen with all of your code and a short `README.md` that explains how to open the page and where each task has been implemented.

