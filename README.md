# ELSHA — Bangladesh Fashion Store

A responsive front-end storefront concept for ELSHA, a women's fashion and handmade crochet clothing brand serving Bangladesh.

## Features

- Minimal, mobile-responsive fashion storefront
- Dresses, occasion wear and handmade crochet collections
- Product cards and demo shopping bag
- Checkout form with Bangladesh phone number validation
- BDT (৳) price display
- Sample Dhaka / outside-Dhaka delivery fee calculation
- Cash on Delivery demo flow
- bKash, Nagad and Rocket payment selection placeholders

## Live preview with GitHub Pages

After uploading these files to a GitHub repository:

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Select branch **main** and folder **/(root)**.
5. Click **Save**.
6. Wait for GitHub Pages to publish. Your site URL will look like:
   `https://YOUR-GITHUB-USERNAME.github.io/REPOSITORY-NAME/`

If the repository is named `YOUR-GITHUB-USERNAME.github.io`, the URL will instead be:
`https://YOUR-GITHUB-USERNAME.github.io/`

## Upload using GitHub website (no coding required)

1. Sign in at https://github.com/
2. Click **New repository**.
3. Name it `elsha`.
4. Choose **Public** (GitHub Pages is available for public repositories on GitHub Free).
5. Create the repository.
6. Click **Add file → Upload files**.
7. Upload `index.html`, `script.js`, `README.md`, `.gitignore`, and `.nojekyll`.
8. Click **Commit changes**.
9. Follow the GitHub Pages steps above.

## Important: demo only, not ready for live sales

This is a static front-end prototype. It does not:
- Save orders to a server or database
- Send order notifications to the shop owner
- Process real bKash, Nagad, Rocket, card or other online payments
- Manage stock, customer accounts or courier bookings

The checkout demo only displays a confirmation in the visitor's browser. Do not treat it as a real order.

Before accepting real customers, connect a secure backend/database, admin dashboard, order notifications, courier service and an approved merchant payment gateway. Never place secret API keys in `script.js` or other browser-side files.

## Before launch

- Replace sample product names, prices, sizes and photos with real inventory.
- Use product photos you own or are licensed to use.
- Confirm delivery rates with your courier; current rates are sample values only.
- Add shipping, returns, privacy and terms pages.
- Add your business contact details and social links.
- Connect your custom domain after GitHub Pages is working.

## Local preview

Open `index.html` in a modern browser. For a local development server, you can use VS Code's Live Server extension.
