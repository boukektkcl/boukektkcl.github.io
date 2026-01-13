# Claude.md - Academic Website Guidelines

## Overview

This is the personal academic website for **Bouke Klein Teeselink**, Lecturer in Philosophy, Politics, and Economics at King's College London. The site is hosted on GitHub Pages at `https://boukektkcl.github.io/`.

**Research Focus:** Behavioral economics, political economy, and the economics of AI.

---

## Website Structure

```
boukektkcl.github.io/
├── index.html      # Homepage with bio, photo, and contact info
├── research.html   # Publications, working papers, work in progress
├── teaching.html   # Teaching history by institution
├── cv.html         # Curriculum vitae
├── styles.css      # Unified stylesheet
└── claude.md       # This file
```

---

## Academic Website Standards

### Design Principles

Academic websites should be:
- **Clean and minimal** - Content-first, no visual clutter
- **Professional** - Subdued color palette, serif fonts for readability
- **Fast-loading** - No unnecessary JavaScript, optimized images
- **Accessible** - Semantic HTML, proper heading hierarchy, mobile-responsive
- **Easy to navigate** - Clear navigation, predictable structure

### Content Hierarchy

Follow the established academic convention:
1. **About/Home** - Brief bio, photo, institutional affiliation, contact
2. **Research** - Publications first, then working papers, then work in progress
3. **Teaching** - Current first, organized by institution
4. **CV** - Structured chronologically (most recent first)

---

## File-Specific Guidelines

### index.html (Homepage)

**Purpose:** First impression and primary contact point.

**Must include:**
- Professional headshot (replace placeholder when available)
- Current position and institutional affiliation
- 2-3 paragraph bio focusing on research interests
- Email address (primary contact method)
- Office location and hours
- Links to professional profiles (SSRN, LinkedIn, Bluesky)

**Style notes:**
- Keep bio concise (under 200 words)
- Lead with research interests, not personal details
- Affiliations should link to their respective websites

### research.html (Research)

**Purpose:** Showcase scholarly output - the most important page for academic reputation.

**Organization (in order):**
1. **Publications** - Peer-reviewed journal articles
2. **Working Papers** - Papers under review or revision
3. **Work in Progress** - Early-stage projects

**For each publication, include:**
- Title (bold, linked to paper when available)
- Co-authors (use "with" not "and")
- Journal name and year
- Media coverage (if notable)

**Formatting standards:**
```html
<div class="publication">
    <p class="publication-title">Paper Title</p>
    <p class="publication-authors">with Coauthor Name</p>
    <p class="publication-venue">Journal Name, Year</p>
    <p class="publication-abstract"><em>Media coverage: Outlet1, Outlet2</em></p>
</div>
```

**Important:**
- List publications in reverse chronological order within each section
- Include DOI links when available
- Add PDF links for working papers
- Keep titles in sentence case (not Title Case)

### cv.html (Curriculum Vitae)

**Purpose:** Comprehensive academic record.

**Sections (in order):**
1. Employment
2. Education
3. Affiliations
4. Research Interests
5. Selected Publications
6. Contact

**Formatting:**
- Years in left column (120px width)
- Details in right column
- Most recent positions first

**Future additions to consider:**
- Grants and awards
- Conference presentations
- Professional service
- PhD supervision

### teaching.html (Teaching)

**Purpose:** Teaching portfolio organized by institution.

**Organization:**
- Group by institution
- Current courses first within each institution
- Include course level (Undergraduate/Graduate)
- Use date ranges (e.g., "2024 -" for ongoing)

### styles.css (Stylesheet)

**Color palette:**
- Primary: `#2c3e50` (dark blue-gray)
- Secondary: `#3498db` (blue)
- Accent: `#e74c3c` (red - use sparingly)
- Text: `#333` (near-black)
- Light gray: `#f8f9fa` (backgrounds)

**Typography:**
- Body: Georgia, Times New Roman (serif)
- Line height: 1.7
- Max content width: 900px

**Do not:**
- Add animations or transitions beyond subtle hovers
- Use more than 2-3 colors
- Change fonts without good reason
- Add JavaScript unless absolutely necessary

---

## Content Update Procedures

### Adding a New Publication

1. Open `research.html`
2. Add entry at the TOP of the appropriate section (Publications/Working Papers)
3. Move papers from "Working Papers" to "Publications" when accepted
4. Update `cv.html` Selected Publications section to match

### Updating Contact Information

1. Update in `index.html` (primary location)
2. Update in `cv.html` (Contact section)
3. Verify office hours booking link is current

### Adding a New Course

1. Add to `teaching.html` under the appropriate institution
2. Current courses should show "Year -" format
3. Past courses should show "Year - Year" format

### Updating CV

When making CV updates:
- Keep formatting consistent with existing entries
- Maintain chronological order (newest first)
- Abbreviate coauthor first names in publication entries
- Use standard journal abbreviations only if space is limited

---

## Image Guidelines

### Profile Photo

When adding a profile photo:
- Replace the `.profile-photo-placeholder` div with an `<img>` tag
- Use class `profile-photo`
- Recommended size: 280px width, ~320px height
- Format: JPG or WebP for compression
- File name: `profile.jpg` or similar

```html
<!-- Replace placeholder with: -->
<img src="profile.jpg" alt="Bouke Klein Teeselink" class="profile-photo">
```

---

## SEO and Metadata

Each page includes:
- Descriptive `<title>` tag
- `<meta name="description">` with relevant keywords
- Semantic HTML structure

**Keywords to maintain:**
- Bouke Klein Teeselink
- King's College London
- Behavioral economics
- Political economy
- Economics of AI

---

## Deployment

The site deploys automatically via GitHub Pages when changes are pushed to the main branch.

**To update the site:**
1. Make changes locally
2. Commit with descriptive message
3. Push to main branch
4. Changes appear within minutes at https://boukektkcl.github.io/

---

## Quality Checklist

Before committing changes, verify:

- [ ] All links work (internal and external)
- [ ] New publications have correct author order
- [ ] Dates are accurate and consistent
- [ ] No typos in names (especially coauthors)
- [ ] Mobile layout still works (test at 768px width)
- [ ] HTML validates (no unclosed tags)
- [ ] Copyright year in footer is current

---

## Reference: Top Academic Economics Websites

For design inspiration and standards, reference:
- Faculty pages at top economics departments (Harvard, MIT, Stanford, Chicago)
- NBER researcher pages
- Personal sites of prominent behavioral economists

**Common elements across top academic sites:**
- Minimal design, maximum readability
- Research prominently featured
- Clear institutional affiliation
- Easy-to-find contact information
- PDF links for papers
- No clutter, no widgets, no social feeds

---

## Contact

**Bouke Klein Teeselink**
Department of Political Economy
King's College London
Email: bouke.klein_teeselink@kcl.ac.uk
Office: 9.08 NE Bush House
