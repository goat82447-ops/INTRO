
How to run
1. Place your photo at `assets/profile.jpg`.
2. Place your resume PDF at `assets/Krishna-Kumar-Bandoju-Resume.pdf`.
3. Open `index.html` in any modern browser.

Quick configuration
- Open `script.js` and update these constants at the top:
  - `LINKEDIN_URL` — your LinkedIn profile (already set if you provided it).
  - `GITHUB_URL` — your GitHub profile.
  - `RESUME_FILE` — path to resume PDF in `assets/` (defaults to `assets/Krishna-Kumar-Bandoju-Resume.pdf`).

Update skills and content
- Skills are defined in the `SKILLS_DATA` object inside `script.js`. Edit categories or skill items there — no HTML changes necessary.
- Project case studies are in `PROJECT_CASES` in `script.js`. Edit descriptions or responsibilities as required.

Accessibility & interactions implemented
- Smooth scrolling (native + JS hooks)
- Sticky navigation with active-section highlighting
- Responsive mobile menu (hamburger)
- Keyboard accessible modal (ESC to close)
- Click outside modal closes it
- Skill-accordion (single-open behavior)
- Experience expandable panels
- Stats animation when in viewport
- Scroll reveal animations using IntersectionObserver
- Back-to-top button
- LinkedIn / GitHub buttons open in new tabs
- Resume download buttons wired to `RESUME_FILE`
- Email button uses `mailto:` (update email in script.js)

Customization suggestions
- Replace text content and project descriptions with more specific numbers and outcomes (impact statements).
- Swap fonts or tweak color variables in `style.css` under `:root`.
- If you want additional animations or analytics, add them carefully preserving performance.

Support
If you'd like, I can:
- Fill in phrasing to better match your resume for each project and experience bullet.
- Create a light-theme variant or an accessible-high-contrast variant.
- Provide a zip with all files ready to drop into GitHub Pages.

Thank you — open index.html and verify your photo and resume paths; tell me if you want me to customize copy for a specific job target (e.g., Cloud/Platform Engineer, .NET Architect), and I will tailor the content and tone accordingly.
