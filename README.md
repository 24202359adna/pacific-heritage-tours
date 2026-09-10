# pacific-heritage-tours
Pacific Heritage Tours – IS229 Web Design project featuring PNG cultural tourism, heritage tours, gallery, and community experiences.

**IS229 – Web Design | Assessment 2**  
**Student:** Adriel NARIA  
**Course:** BBIT/2  
**Student ID:** 24202359  

---

## Project Description

A multi-page website for **Pacific Heritage Tours**, a fictional tourism service offering authentic cultural and nature experiences in the Pacific region. The site supports realistic visitor tasks: learning about the organisation, browsing available tours, viewing a gallery of past experiences, and submitting enquiries or booking requests.

**Target audience:** Independent travellers, couples, families with older children, small groups, and educators seeking respectful cultural tourism experiences.

---

## Pages

| Page | File | Purpose |
|------|------|---------|
| Home | `index.html` | Introduction, value proposition, featured experiences |
| About | `about.html` | Story, values, partners, who the tours suit |
| Tours | `tours.html` | Detailed tour descriptions + indicative schedule table |
| Gallery | `gallery.html` | Photo gallery with figures and captions |
| Contact & Booking | `contact.html` | Substantial form with HTML5 validation and ARIA live region |

---

## Technologies Used

- **HTML5** – full semantic structure (`header`, `nav`, `main`, `section`, `article`, `aside` where appropriate, `footer`, `figure`, `figcaption`)
- **Basic CSS** – external stylesheet for readability, spacing, simple layout and colour contrast only
- **Vanilla JavaScript** – minimal script on the contact page to demonstrate the ARIA live region feedback
- **Git + GitHub** – version control and publication
- **GitHub Pages** (or approved static host) – for live publication

**Not used:** Bootstrap, Tailwind, WordPress, Wix, or any page-builder templates (as required by the assessment).

---

## How to View Locally

1. Clone or download this repository.
2. Open `index.html` in a modern browser, **or**
3. Use a local development server (recommended):


Then visit `[https://github.com/24202359adna/pacific-heritage-tours.git]'


## Published Website

- **Live URL:** *[http://24202359adna.github.io/pacific-heritage-tours/]*  
- **Repository:** *[https://github.com/24202359adna/pacific-heritage-tours]*

---

## Accessibility Features

- Skip-to-main-content link on every page
- Consistent `<nav>` with `aria-current="page"`
- Logical heading hierarchy (one `<h1>` per page)
- Meaningful link text and alternative text
- Properly labelled form controls with HTML5 validation attributes
- ARIA live region (`role="status"`, `aria-live="polite"`) for form feedback
- Sufficient colour contrast and keyboard-accessible interactive elements
- `lang="en"` on the root element

---

## Form & Validation

The Contact & Booking page includes:

- Required fields with visual and programmatic indication
- Appropriate input types (`email`, `tel`, `date`, `number`, `select`, `textarea`)
- `minlength`, `min`/`max`, and `pattern` attributes
- Grouped controls inside a `<fieldset>` with `<legend>`
- Client-side demonstration of success/error messages via an ARIA live region

---

## Development History

This project was developed progressively over several weeks following the assessment weekly plan:

- Week 6: Theme, audience, sitemap, repository setup
- Week 7: Global structure + Home and About pages
- Week 8: Remaining pages, form, gallery
- Week 9: Validation, publication, final checks

Meaningful Git commits record the progressive development of the site.

---

## AI Use Declaration

- AI tools used: ChatGPT
- Purpose: code structure suggestions, accessibility pattern examples, README drafting
- Student responsibility: All final content, structure decisions, testing and submission remain my own work. I understand the code and can explain every part of the site.

---

## Licence / Ownership

This is a student assessment project for IS229 (2026).  
Content and structure are original for the purpose of the assignment.  
Images are  properly licensed or original photographs before any public use beyond assessment.
