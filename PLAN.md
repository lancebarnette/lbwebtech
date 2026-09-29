# LB Web Tech — Codex Implementation Plan

## Objective

Build the initial public website for:

**LB Web Tech**  
**https://lbwebtech.com**

The site will primarily be used as a **QR-code-driven digital business card**.

Most visitors are expected to meet the owner in person, scan a QR code from a phone, and land directly on the site.

The website must therefore be:

- Mobile-first
- Fast
- Professional
- Friendly
- Easy to understand
- Easy to contact from
- Simple to maintain
- Completely static

The visitor should understand what LB Web Tech does within approximately 5–10 seconds.

---

# 1. Business Purpose

LB Web Tech provides practical technology help for:

- Individuals
- Small businesses
- The local community

The business serves an area where access to professional IT assistance may be limited.

LB Web Tech should feel approachable and technically capable without presenting itself like a large corporate IT consulting company.

The website should communicate:

- Practical problem-solving
- Straightforward advice
- Technical competence
- Reliability
- Simplicity
- Personal service
- Community involvement

---

# 2. Core Message

Use the following primary branding:

# LB Web Tech

## Practical Technology Solutions

Primary supporting statement:

**Friendly, straightforward technology help for individuals, small businesses, and the local community.**

Primary service summary:

**Web Development • Computers & Wi-Fi • Home & Business Networks • Security Cameras • Linux & Servers • Python Automation**

Supporting copy:

> Whether you need help solving a technology problem, improving the systems you already use, or building something new, LB Web Tech focuses on practical solutions that fit the situation without unnecessary complexity.

---

# 3. Contact Information

Use the actual contact information below.

Phone:

**813-515-0250**

Email:

**lance@lbwebtech.com**

Phone links must use:

```html
<a href="tel:+18135150250">813-515-0250</a>
```

Email links must use:

```html
<a href="mailto:lance@lbwebtech.com">lance@lbwebtech.com</a>
```

The mobile interface should make both calling and emailing very easy.

---

# 4. Technical Requirements

Build the website using only:

- HTML5
- CSS3
- Minimal vanilla JavaScript

Do not use:

- React
- Vue
- Angular
- Bootstrap
- Tailwind
- jQuery
- Node.js build tools
- npm dependencies
- Server-side frameworks
- Databases
- JavaScript frameworks
- Large third-party libraries

The finished website must be deployable directly as a static site through Cloudflare Pages.

There should be no build step required.

A developer should be able to understand the project by reading the HTML, CSS, and JavaScript files directly.

---

# 5. Project Structure

Create the project using approximately this structure:

```text
lbwebtech/
├── index.html
├── css/
│   └── style.css
├── js/
│   └── main.js
├── images/
├── favicon/
├── README.md
├── PLAN.md
└── .gitignore
```

Avoid unnecessary files or directory nesting.

Copy this implementation plan into `PLAN.md`.

---

# 6. Overall Design Direction

The visual design should be:

- Clean
- Modern
- Professional
- Friendly
- Minimal
- Technically credible
- Easy to scan quickly

Avoid making the site look:

- Overly corporate
- Like a startup landing-page template
- Flashy
- Over-designed
- Futuristic
- Gaming-oriented
- Artificially "high tech"

Avoid:

- Excessive gradients
- Neon effects
- Glassmorphism everywhere
- Animated backgrounds
- Large hero photography
- Stock photos
- Autoplay video
- Carousels
- Excessive icons
- Unnecessary animations

Use tasteful visual hierarchy, spacing, typography, borders, and subtle effects instead.

---

# 7. Mobile-First Requirement

This is one of the most important requirements.

The majority of visitors are expected to use a mobile phone after scanning a QR code.

Do not build a desktop site and then shrink it.

Design the phone experience first and progressively enhance for larger displays.

The expected user flow is:

```text
Meet owner
   ↓
Scan QR code
   ↓
Open lbwebtech.com
   ↓
Understand services quickly
   ↓
Call or email
```

The first mobile viewport should immediately establish:

- LB Web Tech
- Practical Technology Solutions
- Who the service is for
- Major technology areas
- A clear way to make contact

---

# 8. Header

Create a clean header containing:

**LB Web Tech**

Navigation:

- About
- Services
- Community
- Contact

On desktop, a simple horizontal navigation is appropriate.

On mobile, use either:

- A compact navigation menu, or
- Another simple touch-friendly pattern

Do not implement a complicated menu system.

A small hamburger menu is acceptable if useful.

---

# 9. Hero Section

The hero is the most important part of the page.

Use:

# LB Web Tech

## Practical Technology Solutions

**Friendly, straightforward technology help for individuals, small businesses, and the local community.**

Then display the service summary:

**Web Development • Computers & Wi-Fi • Home & Business Networks • Security Cameras • Linux & Servers • Python Automation**

Then:

> Whether you need help solving a technology problem, improving the systems you already use, or building something new, LB Web Tech focuses on practical solutions that fit the situation without unnecessary complexity.

Create prominent mobile-friendly actions:

**Call 813-515-0250**

**Email LB Web Tech**

Also provide:

**View Services**

The Call and Email buttons should visually receive higher priority than unnecessary decorative elements.

---

# 10. About Section

Heading:

## Technology Help Without the Complexity

Use this copy:

> LB Web Tech provides practical technology services for individuals and small businesses, especially in communities where reliable local IT help can be difficult to find.
>
> The goal is simple: understand what you need, explain the options clearly, and find a solution that is reliable, maintainable, and appropriate for you.
>
> That might mean fixing a computer or Wi-Fi problem, improving a home or business network, setting up security cameras, building a website, configuring a server, automating repetitive work, or helping you make sense of the technology you already have.
>
> You do not need to know the technical terms before asking for help.

The final sentence should receive some visual emphasis without becoming oversized or gimmicky.

---

# 11. Services Section

Heading:

## How I Can Help

Keep descriptions concise and easy for nontechnical visitors to understand.

Create service blocks for the following.

### Computers & Everyday Technology

> Computer setup, troubleshooting, upgrades, backups, device integration, and general technology assistance.

### Home & Business Networks

> Wi-Fi problems, network setup, router configuration, coverage improvements, and reliable connectivity for homes and small businesses.

### Security Cameras

> Help planning, setting up, and integrating security camera systems for homes and small businesses.

### Web Development

> Professional websites and custom web applications, from simple business sites to Python-based applications.

### Linux & Servers

> Linux installation, server configuration, troubleshooting, web servers, self-hosted systems, backups, and system maintenance.

### Automation & Python

> Custom scripts and automation that reduce repetitive work, process data, generate reports, and connect existing systems.

### Technology Consulting

> Straightforward advice on technology purchases, upgrades, backup planning, infrastructure, and practical solutions to technical problems.

---

# 12. Service Layout

On phones:

- One service per row
- Easy vertical scanning
- Comfortable spacing
- Clear headings
- Short descriptions

On tablets and desktop:

- Use CSS Grid or Flexbox
- Allow multiple cards or columns
- Maintain readable widths
- Do not stretch text excessively across wide displays

The service area should not resemble an online store.

Use cards only if they improve readability.

---

# 13. Community Section

Create a dedicated section because community involvement is part of the identity of LB Web Tech but is not a paid service offering.

Heading:

## Technology Should Be Accessible

Use this copy:

> LB Web Tech also supports local technology education through mentoring, demonstrations, and hands-on learning opportunities for students who may have limited exposure to technology.
>
> The goal is to encourage curiosity, problem-solving, and confidence with computers, software, networking, and other areas of technology.
>
> Sometimes seeing what is possible is all it takes to get someone started.

The design should convey community involvement without making this section look like a separate organization or charity.

---

# 14. Contact Section

Heading:

## Need Help With Technology?

Use:

> Have a problem, a question, or an idea?
>
> You do not need to know exactly what service you need. Get in touch, explain what you are trying to accomplish, and we can start there.

Display:

**Phone:** 813-515-0250

**Email:** lance@lbwebtech.com

Add large touch-friendly actions:

**Call Now**

**Send Email**

Then include:

> Serving individuals, small businesses, and the local community.

Do not create a contact form in Version 1.

---

# 15. Footer

Keep the footer simple.

Suggested content:

**LB Web Tech**

**Practical Technology Solutions**

**813-515-0250 • lance@lbwebtech.com**

Copyright:

**© LB Web Tech**

The year may be populated using minimal JavaScript.

---

# 16. Navigation Behavior

Navigation links should scroll to:

- About
- Services
- Community
- Contact

Smooth scrolling is acceptable.

Respect users who prefer reduced motion.

Do not add complex page transitions.

---

# 17. Mobile Contact Experience

Because most traffic is expected to be mobile, consider implementing a small fixed mobile contact bar:

```text
[ Call ]    [ Email ]
```

This is optional.

Only implement it if it improves usability.

If implemented:

- Show it only at appropriate mobile widths
- Do not cover content
- Account for mobile safe-area insets
- Keep it visually restrained
- Ensure buttons use `tel:` and `mailto:`
- Do not rely on JavaScript if CSS is sufficient

---

# 18. Touch Accessibility

Interactive controls should be comfortable for fingers.

Target approximately 44×44 CSS pixels or greater where practical.

Requirements:

- No tiny links
- Adequate spacing between buttons
- No important hover-only interactions
- Visible keyboard focus states
- Appropriate active states
- Good contrast

---

# 19. Typography

Typography should be modern and highly readable.

Prefer:

- Native system font stack, or
- Locally hosted font assets only if there is a strong design reason

Do not depend on Google Fonts or another remote font provider for the initial version.

Use responsive typography.

CSS functions such as:

```css
clamp()
min()
max()
```

are encouraged where appropriate.

Avoid giant headings that dominate small mobile displays.

---

# 20. Color Palette

Use a restrained palette.

Recommended approach:

- Light primary background
- Dark readable text
- One primary accent color
- Neutral secondary tones
- Subtle borders/background variations for sections

Do not introduce many competing colors.

Choose an accent that communicates professional technology services without looking overly corporate.

Ensure WCAG-appropriate contrast.

---

# 21. Accessibility

Use semantic HTML.

Expected elements include:

```html
<header>
<nav>
<main>
<section>
<footer>
```

Requirements:

- Proper heading hierarchy
- Keyboard accessibility
- Visible focus states
- Correct `alt` attributes
- Sufficient color contrast
- Logical DOM order
- Meaningful links
- No unnecessary ARIA

Prefer semantic HTML rather than using ARIA to repair non-semantic markup.

---

# 22. Performance

This site should be exceptionally lightweight.

This is particularly important because visitors may access it through cellular connections in rural areas.

Prioritize:

- Small HTML
- Small CSS
- Minimal JavaScript
- Optimized images
- No autoplay media
- No giant background images
- No unnecessary dependencies
- No remote font downloads
- No third-party trackers

The useful page content should become available quickly even on slower connections.

---

# 23. Images

Version 1 does not require photography.

Do not add random stock photography.

If subtle icons or graphical elements improve the design:

- Prefer simple inline SVG
- Keep the visual language consistent
- Do not depend on a large external icon library

The site should still look complete if there are very few images.

---

# 24. SEO and Metadata

Include an appropriate title:

```html
<title>LB Web Tech | Practical Technology Solutions</title>
```

Suggested meta description:

> LB Web Tech provides practical technology help for individuals and small businesses, including computers, Wi-Fi, home and business networks, security cameras, web development, Linux servers, and Python automation.

Include:

- UTF-8 charset
- Responsive viewport
- Meta description
- Canonical URL for `https://lbwebtech.com/`
- Basic Open Graph metadata
- Favicon support
- Appropriate theme color if relevant

Do not over-engineer SEO.

---

# 25. No Projects Section

Do not include a Projects section in Version 1.

The current purpose of the site is primarily:

- Digital introduction
- Explanation of services
- Professional credibility
- Easy contact

A projects or portfolio section may be added in the future.

Do not create placeholder projects.

---

# 26. Future Expansion

Design the site so it does not prevent future integration with:

```text
projects.lbwebtech.com
lab.lbwebtech.com
docs.lbwebtech.com
status.lbwebtech.com
```

Do not build these now.

Do not create navigation links to nonexistent subdomains.

---

# 27. CSS Approach

Use a clean CSS architecture.

CSS custom properties are encouraged for:

- Colors
- Spacing
- Font sizes
- Border radius
- Content width
- Shadows

Example concept:

```css
:root {
    --content-width: 72rem;
    --radius: 0.75rem;
}
```

Do not create an elaborate design system for a single-page site.

Favor readable CSS over clever abstractions.

---

# 28. JavaScript

Use JavaScript only where it meaningfully improves the page.

Reasonable examples:

- Mobile navigation toggle
- Footer year
- Small progressive enhancement

The site should remain largely useful if JavaScript is disabled.

Do not implement unnecessary animation libraries or UI frameworks.

---

# 29. Responsive Testing

Test the site at minimum around these widths:

```text
320px
375px
390px
430px
768px
1024px
1440px
```

Also manually resize the browser across intermediate sizes.

Verify:

- No horizontal scrolling
- No overlapping elements
- No clipped content
- Correct line wrapping
- Comfortable button sizing
- Navigation usability
- Service layout behavior
- Contact usability
- Reasonable spacing
- Readable typography

---

# 30. Local Development

The finished project must be viewable locally using Python's built-in HTTP server.

Use:

```bash
cd lbwebtech
python -m http.server 8000
```

The website should then be available at:

```text
http://localhost:8000
```

Do not require any additional local development dependencies.

---

# 31. README

Create a concise `README.md` explaining:

- What the project is
- Project structure
- How to run it locally
- That it is intended for static deployment to Cloudflare Pages
- That no build system is required
- Basic editing locations

Example usage instructions:

```bash
cd lbwebtech
python -m http.server 8000
```

Then:

```text
http://localhost:8000
```

---

# 32. Git

If the directory is not already a Git repository, initialize one.

Create an appropriate `.gitignore`.

Because this is a static project, `.gitignore` should remain minimal.

Make an initial commit after the implementation is complete and reviewed locally only if Git identity is already configured.

Do not invent Git identity settings.

Do not create a GitHub repository yet.

Do not push anything to GitHub.

---

# 33. Cloudflare

Do not configure Cloudflare yet.

Do not request or use:

- Cloudflare API tokens
- Account credentials
- DNS credentials

The deployment phase will occur separately after the local site is reviewed.

The eventual architecture will be:

```text
Local Development
       │
       ▼
      Git
       │
       ▼
     GitHub
       │
       ▼
Cloudflare Pages
       │
       ▼
  lbwebtech.com
```

For now, stop at the local development stage.

---

# 34. Implementation Philosophy

Prefer:

```text
Simple > Clever

Readable > Abstract

Static > Dynamic

Native Browser Features > Dependencies

Maintainable > Feature-Rich

Useful > Decorative
```

Do not introduce complexity without a clear benefit to the visitor.

---

# 35. Codex Task

Implement the complete Version 1 website according to this plan.

Perform the following work:

1. Create the project directory structure.
2. Create `PLAN.md` containing this specification.
3. Build `index.html`.
4. Build the complete mobile-first stylesheet.
5. Add only necessary JavaScript.
6. Add favicon support or create reasonable placeholder favicon assets if practical.
7. Implement the About section.
8. Implement all seven service areas.
9. Implement the Community section.
10. Implement the Contact section.
11. Implement functioning telephone and email links.
12. Ensure all navigation anchors function correctly.
13. Ensure the page works without external libraries.
14. Check semantic HTML and accessibility.
15. Check responsive behavior.
16. Review code for unnecessary complexity.
17. Create `README.md`.
18. Start a local static web server.
19. Verify that the site loads successfully.
20. Leave the web server running so the site can be reviewed locally.

Use:

```bash
python -m http.server 8000
```

or:

```bash
python3 -m http.server 8000
```

depending on the local environment.

When complete, report:

- The project directory
- The files created
- The local URL
- Any design decisions that materially differ from this plan
- Any issues that remain

The expected local review URL is:

```text
http://localhost:8000
```

Do not proceed to GitHub or Cloudflare deployment.

Stop after the website is built, tested, and available for local review.