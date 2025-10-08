orteplus-Projects-Services-Ltd---Services

Description
Website for a construction company. Shows company info, project details, and contact information.

Features

Company profile
Project details
Contact form
Asset management
Technologies

HTML
CSS
JavaScript
Setup

Clone the repository
Open index.html in your browser
Deploy to Vercel or any static hosting
Usage
Browse the site for company and project information.

Demo
https://forteplus.org/

Author
Fikunmi06

Form integration & testing
--------------------------

What changed
- The site contact forms on `index.html` and `contact/contact_us.html` were replaced with a Zoho Forms embed (public iframe). This centralises submissions to the configured Zoho account.
- A WhatsApp floating button was added to both pages to provide a quick alternate contact channel.

How to test locally
1. Open `index.html` and `contact/contact_us.html` in a browser (double-click the files or serve the directory with a simple static server).
2. Verify the Zoho form iframe loads. If the iframe is blocked by browser mixed-content policies, host the site over HTTPS or test the page from a deployed URL.
3. Submit a test entry through the form and confirm it appears in the Zoho Forms dashboard for the account that owns the form.
4. Click the WhatsApp floating button — it should open WhatsApp Desktop or mobile with a prefilled message to `+2349057240646`.

Smoke test checklist
- [ ] Zoho form loads on both pages
- [ ] Submission is accepted and recorded in Zoho
- [ ] WhatsApp button opens prefilled chat

Rollback
- To revert, restore the previous commit that contained the original forms or remove the iframe markup from the pages.
