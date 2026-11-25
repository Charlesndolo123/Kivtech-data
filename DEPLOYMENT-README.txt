KIVTECH DATA SOLUTIONS — REDESIGN UPDATE
=======================================

This update refreshes the existing KivTech homepage while preserving the
package catalogue, existing price/validity values, category filters, purchase
instructions, M-PESA Till number, WhatsApp support link, SEO pages and logo.

WHAT CHANGED
------------
- Refreshed the homepage styling with a deep navy and emerald-green palette.
- Improved mobile spacing, buttons, cards and catalogue presentation.
- Added package search alongside the existing category filters.
- Added a rotating three-message promotional hero banner with manual slide controls.
- Added a rotating "Offer Spotlight" notification that promotes packages
  already present in the catalogue.
- Added recipient Safaricom number and M-PESA transaction-code fields to the
  purchase instructions. The confirmation button opens WhatsApp with a
  pre-filled message for the customer to review and send.
- Updated payment copy to reflect manual M-PESA verification and manual
  bundle processing.
- Harmonized the About page colors with the homepage.

IMPORTANT ABOUT CUSTOMER PURCHASE POP-UPS
-----------------------------------------
The supplied project is a static website. It contains no orders database,
checkout webhook, payment API, or verified transaction feed. Therefore this
update does NOT invent customer names, locations, or purchases. The current
notification promotes real catalogue offers. To show genuine messages such as
"Customer from Nairobi purchased 1GB", KivTech must connect a trusted source
of verified orders/transactions. Do not publish fabricated social-proof
notifications as if they were real purchases.

PAYMENT FLOW
------------
1. Customer chooses a package.
2. Customer enters the M-PESA Buy Goods Till number 5797885 in M-PESA and
   pays the exact displayed amount.
3. Customer enters the receiving Safaricom number and M-PESA transaction code
   in the website modal.
4. The website opens WhatsApp with the details pre-filled to 254715024923.
   The customer reviews and sends the message.
5. KivTech verifies the payment and manually processes the bundle.

The website does not collect or store M-PESA PINs. Never ask customers to
share their M-PESA PIN.

DEPLOYMENT
----------
1. Download and extract this ZIP.
2. Open the extracted Kivtech-data-main folder.
3. Upload/commit the CONTENTS of that folder to the root of the existing
   GitHub repository (not the enclosing folder).
4. Commit to the branch connected to Vercel (usually main).
5. Wait for the Vercel deployment to finish, then test the live homepage and
   purchase flow on mobile and desktop.

PROJECT CONTENTS / LIMITATION
-----------------------------
The uploaded ZIP contained index.html, index-old.html, about.html, blogs.html,
privacy.html, terms.html, robots.txt, sitemap.xml, the logo and this README.
It did not contain a /blog/ directory, even though blogs.html redirects to
/blog/. If the blog is still hosted separately or in another branch, preserve
that content when deploying. Do not delete an existing /blog/ directory from
the live repository.

Before publishing, verify the current offer prices and validity periods
against your latest official offer list. The redesign has retained the values
already present in the uploaded index.html.
