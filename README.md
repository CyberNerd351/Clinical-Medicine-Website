# Egerton University – Department of Clinical Medicine Website

A nine-page static website for the Department of Clinical Medicine at Egerton University. It provides information about the department, academic programmes, clinical training, staff, research, resources and contact details.

The website is designed for prospective students, current students, staff and visitors.

**Status:** Frontend prototype  
**Hosting:** Vercel  
**Technologies:** HTML5, CSS3 and Bootstrap 5.3.3

## Pages

The website contains the following pages:

| Page | File |
|---|---|
| Home | `index.html` |
| About | `about.html` |
| Programmes | `programmes.html` |
| Staff | `staff.html` |
| Clinical Training | `clinical-training.html` |
| Research | `research.html` |
| Resources | `resources.html` |
| News | `news.html` |
| Contact | `contact.html` |

## Features

- Responsive layout for desktop, tablet and mobile.
- Bootstrap navigation with a mobile menu.
- Breadcrumb navigation.
- Departmental information and academic programme sections.
- Staff profile layout.
- Research and publication section.
- Academic resources section.
- News page with an empty state.
- Contact form that opens the visitor's email application.

## Technologies Used

- **HTML5:** Page structure and content.
- **CSS3:** Website styling.
- **Bootstrap 5.3.3:** Responsive layout and navigation.
- **Bootstrap JavaScript:** Mobile navigation functionality.
- **Open Sans:** Primary font, loaded from Google Fonts.
- **Arial:** Fallback font.

Bootstrap is loaded from the jsDelivr CDN, while Open Sans is loaded from Google Fonts. Internet access is therefore required for these resources.

No backend, database, frontend framework or build process is used.

## Project Structure

```text
clinical-medicine-website/
│
├── README.md
├── index.html
├── about.html
├── programmes.html
├── staff.html
├── clinical-training.html
├── research.html
├── resources.html
├── news.html
├── contact.html
│
└── assets/
    ├── css/
    │   └── style.css
    │
    └── images/
        ├── logo/
        ├── hero/
        ├── department/
        ├── staff/
        └── research/
```

## Running Locally

Clone the repository:

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

Enter the project directory:

```bash
cd clinical-medicine-website
```

Start a local server:

```bash
python3 -m http.server 8000
```

Open the following address in your browser:

```text
http://localhost:8000
```

You can also open `index.html` directly in a browser.

## Editing the Website

Each page has its own HTML file. Edit the relevant file to change its content.

The main stylesheet is located at:

```text
assets/css/style.css
```

Images should be placed in the appropriate folders under `assets/images/`.

The navigation and footer are repeated across the HTML pages. Changes to these elements should be applied to all nine pages.

Only use approved departmental images, logos and institutional information.

## Deployment

The website is hosted on **Vercel**.

To deploy changes, push the updated files to the connected GitHub repository:

```bash
git add .
git commit -m "Update website"
git push origin main
```

Vercel automatically deploys changes pushed to the configured production branch when Git integration is enabled.

### Vercel Configuration

| Setting | Value |
|---|---|
| Framework Preset | Other |
| Root Directory | `./` |
| Build Command | Empty |
| Output Directory | `.` |
| Install Command | Empty |

No build or installation command is required.

## Contact Form

The contact form uses a `mailto` link to open the visitor's default email application.

It does not send messages directly or store enquiries. Successful use depends on the visitor having a configured email application.

## Limitations

This is a frontend prototype, not an officially approved university website.

The following information still requires confirmation from the department:

- Official departmental email and telephone number.
- Departmental location.
- Approved logo and photographs.
- Departmental history, vision and values.
- Current academic programmes and curricula.
- Staff names and profiles.
- Research publications and projects.
- News and announcements.

The mission included in the original project brief has not been independently verified.

The website currently has no backend, database, content management system, server-side search or analytics.

## Future Improvements

Possible improvements after departmental approval include:

- Adding verified staff profiles.
- Publishing approved academic programmes.
- Adding research publications and departmental news.
- Providing downloadable academic resources.
- Introducing a content management system.
- Implementing a secure contact form.
- Improving accessibility and performance.
