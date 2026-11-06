# Egerton University – Department of Clinical Medicine website

A nine-page static departmental website for prospective and current students, staff and visitors. It presents programme pathways, clinical education, research, resources and contact routes while clearly marking unverified departmental details.

## Objectives and features

Provide a credible, accessible starting point for academic and departmental information, with responsive navigation, breadcrumbs, a staff profile template, a publication template, an announcements empty state and a contact form that opens an email application rather than storing messages.

## Technologies

HTML5, CSS3 and Bootstrap 5.3.3 (official jsDelivr CDN). Bootstrap's bundled JavaScript powers the mobile navbar; no custom JavaScript or backend is included. Open Sans is loaded from Google Fonts, with Arial fallback. CDN access is needed for Bootstrap's layout and mobile menu; the site is not fully functional offline without locally hosting Bootstrap.

## Structure

```
index.html, about.html, programmes.html, staff.html
clinical-training.html, research.html, resources.html, news.html, contact.html
assets/css/style.css
assets/images/{logo,hero,department,staff,research}/
assets/documents/
docs/ (project, structure, design, content, testing and deployment guides)
```

Empty asset directories are reserved for approved material and may not be preserved by Git until files are added.

## Run locally

Download the project and open `index.html` in a browser, or serve the project folder using any static HTTP server. No build or installation step is required. Internet access is needed for the Bootstrap CDN and web font. Check the mobile menu with JavaScript enabled. Email form behaviour depends on a configured email application.

## Edit and deploy

Edit the relevant HTML page in a text editor; header and footer are repeated in each page and must be updated consistently. Styling is in `assets/css/style.css`. Replace the illustrative photo only with an approved, appropriately licensed image, update its alt text, caption, CSS path and attribution. See `docs/CONTENT_MANAGEMENT.md` and `docs/DEPLOYMENT_GUIDE.md` for details.

## Limitations

This is a frontend draft, not an official university publication. The department's official email, phone, exact location, current vision, history, values, objectives, approved curricula, staff, research and news require verification. The mission was supplied in the project brief and has not been independently verified. Admissions contacts are campus-level, not departmental. The email form opens a mail client and does not transmit or store anything itself; some browsers or mail clients may not support form-to-email. No server, analytics, search, privacy policy or accessibility statement is provided. Links to the campus site were found via search but TLS requests from the test environment failed; confirm them before publication.

## Future improvements

After institutional approval, add verified staff, programmes, research and news, an authorised university logo, approved photographs and current contact details. A separately approved backend could support secure enquiries; re-test accessibility and privacy before adding one.
