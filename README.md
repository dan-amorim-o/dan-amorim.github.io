# Daniel Amorim de Oliveira

Personal website focused on product analytics and applied AI leadership.

- Website: https://danielamorim.com/
- CV: https://danielamorim.com/Resume_Daniel_Amorim.pdf
- LinkedIn: https://www.linkedin.com/in/daniel-amorim-de-oliveira

The homepage uses `index.html` and `styles.css`, hosted on GitHub Pages. The downloadable CV remains `Resume_Daniel_Amorim.pdf`.

## Preview

Run `python3 -m http.server 8000` from the repository directory and open http://localhost:8000.

## Content and discovery

The homepage contains all profile and case-study content in semantic HTML; no JavaScript is needed to read it. The formal current job title and public profile links are represented in Person and ProfilePage JSON-LD. Canonical, social-card metadata, `robots.txt`, and `sitemap.xml` use the current domain, danielamorim.com. `llms.txt` provides an optional concise profile and links for tools that support it; it is not required for indexing and does not guarantee AI-search inclusion.

`social-preview.png` is the 1200 × 630 sharing image. Keep its text and homepage metadata aligned when changing positioning. The sitemap lists the canonical homepage; section anchors are not separate pages. Keep case studies and structured data consistent with the current CV and public-safe evidence. Do not add confidential company results or unsupported performance estimates.

After deployment, verify the domain in Google Search Console and Bing Webmaster Tools, submit `https://danielamorim.com/sitemap.xml`, and request indexing for the homepage. Verification requires the owner's account; do not invent verification tokens. Search and AI-search inclusion is controlled by the relevant service and is not guaranteed by metadata.

## Analytics

No visitor analytics provider is configured. The site does not send tracking events. Links have `data-event` attributes (`cv_download`, `linkedin_click`, `contact_click`) to identify intended conversion events for a future integration. Add case-study view measurement only after a provider is selected. Internal navigation works independently of analytics. No visitor data is collected or stored by the website's own code.
