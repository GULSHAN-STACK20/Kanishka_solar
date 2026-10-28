# Kanishka Solar Energy website

A free, static website for Kanishka Solar Energy (Udaipur, Rajasthan). It runs on GitHub Pages with no server.

## Pages
`index.html`, `services.html`, `subsidy.html`, `faq.html`, `about.html`, `enquiry.html`, `contact.html`, `404.html`. Styles and scripts are in `assets/`.

## 1. Put it on GitHub Pages
1. Sign in at github.com and click **New repository**. Name it `kanishka-solar` (or `<your-username>.github.io` for a shorter address). Set it to **Public** and create it.
2. Click **uploading an existing file**, drag in everything from this folder (the HTML files, the `assets` folder, `.nojekyll`, `README.md`) and click **Commit changes**. Make sure `index.html` is at the top level of the repository, not inside another folder.
3. Open **Settings > Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, choose branch **main** and folder **/ (root)**, then **Save**.
4. Wait one to two minutes. Your site is live at `https://<your-username>.github.io/kanishka-solar/` (the exact link is shown at the top of the Pages settings).

## 2. Save customer queries (free)
GitHub Pages cannot store form data, so the form uses Formspree's free plan.
1. Create a free account at formspree.io and click **New form**.
2. Copy the form code from its URL (the part after `/f/`).
3. Edit `assets/config.js` on GitHub (pencil icon) and paste the code into `formspreeId`, then commit.
4. Each query now arrives in your Formspree dashboard and in your email. You can view all customer details there and export them as a file.

Until you do step 2, the form shows a WhatsApp button so queries still reach you.

## 3. Change details later
- Phone numbers and address: edit the HTML files (search for `9079019494`).
- WhatsApp number: `assets/config.js` and the WhatsApp button in `contact.html`.
- Colours: the variables at the top of `assets/style.css`.
- Subsidy figures: `subsidy.html` and `assets/app.js`. Check them against pmsuryaghar.gov.in from time to time.

## Custom domain (optional)
Buy a domain, then add it under **Settings > Pages > Custom domain**.
