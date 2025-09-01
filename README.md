# QBridges Website Starter (GitHub Pages)

This starter is ready to upload to a GitHub repository and publish via GitHub Pages.

## Structure
- `/en` English pages
- `/zh` Chinese pages
- `/assets` CSS/JS/images
- Root `index.html` redirects to `/en/`

## Customize
1. Replace the email/phone in `en/contact.html` and `zh/contact.html`.
2. Update prices in `en/courses.html` and `zh/courses.html`.
3. Create a Google Form and paste its embed URL into `en/register.html` and `zh/register.html`.
4. Configure payment:
   - PayPal: replace `YOUR_CLIENT_ID` and amounts in `en/payment.html` and `zh/payment.html`.
   - Stripe: create a Checkout link in your Stripe dashboard and paste into the pages.

## Publish (GitHub Pages)
1. Create a public GitHub repository (e.g., `qbridges-website`).
2. Upload all files/folders from this starter.
3. Go to **Settings → Pages** and set "Deploy from branch" to `main` / root.
4. Your site will be available at `https://<username>.github.io/<repo>/`.
5. Optional: connect a custom domain via **Settings → Pages → Custom domain** and follow the DNS instructions shown there.
