# DentGlow website

A responsive, dental-first clinic website built with plain HTML, CSS and JavaScript. The design uses the supplied DentGlow logo, a dedicated dental services grid, a separate skin and hair section, and direct appointment enquiry links. It has no build step or paid service dependency.

## Hero image

`assets/dental-hero.jpg` is an illustrative stock photo by Pavel Danilyuk from [Pexels](https://www.pexels.com/photo/dentist-checking-on-a-patient-6812570/). Pexels permits commercial use under its [license](https://www.pexels.com/legal-pages/license/). The page’s image description and photo note identify it as stock. Replace it with clinic-approved photos before launch if available; do not present the stock photo as DentGlow staff or a DentGlow patient.

## Local preview

From this folder (with Node.js installed), run:

```powershell
node server.cjs
```

Then open [http://127.0.0.1:8000](http://127.0.0.1:8000). Stop the server with `Ctrl+C`.

## Quick demo and check

1. Run `node server.cjs` and open the local address above.
2. On a phone sized screen, open the menu and try the Dental, Skin & hair, Reviews, and Hours & directions links.
3. Check the WhatsApp enquiry and call buttons, Instagram and LinkedIn links, clinic hours, address, and embedded map. WhatsApp opens a message draft; the clinic confirms the appointment.
4. On desktop, move the pointer over the hero image and dental cards to see the gentle 3D tilt. On phones the motion is intentionally off; people who request reduced motion also see a still design.
5. Before showing it as a live clinic site, replace stock photos, confirm current details and ratings, and confirm the clinic approves the reviews and doctor information.

For a quick JavaScript syntax check, run `node --check script.js` in PowerShell. This project has no install or build step.

## Free deployment: Cloudflare Pages

Cloudflare Pages supports direct upload of static site files. Its current Free plan limits include 500 deployments per month, up to 20,000 files, and a 25 MiB per-file cap; this site is comfortably within those limits. Recheck the provider's terms and plan before launch. [Pages plan limits](https://developers.cloudflare.com/pages/platform/limits/) · [Direct Upload instructions](https://developers.cloudflare.com/pages/get-started/direct-upload/).

1. Have the clinic owner create or use a Cloudflare account and open **Workers & Pages**.
2. Choose **Create application → Get started → Drag and drop your files**.
3. Enter an available project name and upload the website files: `index.html`, `styles.css`, `script.js`, and the `assets` folder. Do not upload `server.cjs` or `README.md` as site content.
4. Select **Deploy site**. Cloudflare will provide a `*.pages.dev` address.
5. Review the live page, test its enquiry links, and share it with the owner. Attach a custom domain only after the owner approves and acquires one.

Direct Upload projects cannot later be converted to Git integration; create a new project if automatic repository deployments are needed. Do not publish until the owner confirms the details listed below.

## Owner confirmations before launch

- Confirm the clinic name styling, address, phone/WhatsApp number and email.
- Confirm current opening hours, including holiday hours.
- Confirm the doctors' preferred titles, qualifications and approved biographies.
- Confirm permission to use and attribute the three patient testimonial summaries adapted from the existing clinic website.
- Refresh the 4.8 / 53 Google rating shown in the supplied screenshot before launch.
- Replace the three clearly labeled Pexels stock images with approved DentGlow clinic photography when available.
- Confirm the Instagram and Dr. Anas Patel LinkedIn links are the intended public profiles.
- Confirm that the WhatsApp enquiry wording and clinic response process are suitable.

## Pre-launch checks

- Check WhatsApp, click-to-call, email, embedded Google Map, Maps directions, review and social links on a phone.
- Verify current contact details, hours, doctor credentials and review permissions with the clinic owner.
- Review page text and image alternative text; check mobile layout and keyboard focus.
- Set final canonical URL and social sharing image if the site is moved to an approved domain.
- Deploy only after owner approval. A WhatsApp enquiry is not an appointment confirmation.
## Media sources

- `assets/dental-hero.jpg`: Pavel Danilyuk, [Dentist Checking on a Patient](https://www.pexels.com/photo/dentist-checking-on-a-patient-6812570/).
- `assets/skin-care.jpg`: Vũ Ngọc Long, [Facial Treatment in a Professional Clinic Setting](https://www.pexels.com/photo/facial-treatment-in-a-professional-clinic-setting-30793291/).
- `assets/laser-care.jpg`: Khuram Naseem, [Person Having a Laser Treatment](https://www.pexels.com/photo/person-having-a-laser-treatment-12556695/).

All three are illustrative stock photographs from Pexels. Their image descriptions and the footer note identify them as stock. The [Pexels license](https://www.pexels.com/legal-pages/license/) permits commercial use. Replace them with approved DentGlow photography before client launch when available.
