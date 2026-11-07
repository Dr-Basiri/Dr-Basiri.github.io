DR. MOHAMMAD HOSSEIN BASIRI — MULTI-PAGE FACULTY WEBSITE

Pages
- index.html: About, academic/professional journey, research overview, technology updates, awards, CV, contact
- research.html: Research & Projects
- publications.html: Publications and awards/patent details
- lab.html: Students and recommendation-letter information
- teaching.html: Courses

Deployment
1. Upload all HTML files and the images/ folder to the same directory on your web host.
2. Keep the filenames and images/ folder structure unchanged.
3. The Technology Updates feed fetches from the configured Cloudflare Worker and requires internet access and suitable CORS settings.
4. External fonts, university logo, Three.js demo, and some linked assets require internet access.
5. Contact form uses FormSubmit; complete its first-time email confirmation after deployment if prompted.
6. Student social links are placeholders/general profile destinations and should be replaced with each student's actual profile URLs before publication.
7. Course pages currently link to the configured /courses/... URLs; ensure those routes exist on your host. A static website cannot securely protect private course files by itself.

Navigation is shared across pages. This package keeps CSS and JavaScript self-contained in each HTML page for straightforward static hosting.


Latest visual corrections (October 2026): the supplied official AUT and Electrical Engineering logos are included locally in images/ and displayed larger in a separate institutional branding row above navigation. Automotive OEM logo strip and quick facts have been removed from standalone Publications, Students, Teaching, and Research pages. Standalone pages now have more top spacing.

Research Group: lab.html — Autonomous Driving Lab, directed by Dr. Mohammad Hossein Basiri; includes the student directory / lab members.
