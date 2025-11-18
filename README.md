# NOVAXIA Thank You Page

This repository hosts a custom thank-you page used in conjunction with a JotForm submission flow.  
After a user completes the form, JotForm redirects them to this page and dynamically injects the
generated PDF link into the download button.

## How it works
- JotForm redirects the user using the parameter:  
  `?pdfUrl={URLENCODE:pdfUrl}`
- The HTML page reads the URL parameter and updates the **Download PDF** button automatically.
- The styling is customized to match the NOVAXIA Property Investment Project design.

## Files
- `index.html` — Main thank-you page (styled with embedded CSS).
- Assets — Logo, images, and supporting graphics.

## Deployment
Hosted via **GitHub Pages**:
- `https://despinanitti.github.io/novaxia-thank-you-page/`

No build step is required. Simply edit the HTML and commit.
