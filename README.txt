CrateX website (multi-page, with photos)
===========================
Upload everything in this folder to the root of your site (public_html, www, or your host's upload area).
index.html is the whole site; the img/ folder holds the photos and must be uploaded with it. Pages: #home, #industries, #pricing, #hardware, #switch, #contact, #privacy, #terms.

FILL IN YOUR DETAILS
Open index.html in any text editor and search for "CONFIG". Replace each null with your real value:
  email, phone, hours      contact page and footer
  loginUrl                 shows a "Log in" link in the menu
  formEndpoint             where the demo form sends (e.g. a Formspree or Basin form URL)
  pricing.monthly          software price per location per month
  pricing.ratePct          card processing %, and perTxCents for the fixed fee
  answers.*                your answers on the "Switch to CrateX" page
  hardware.*               supported models on the Hardware page
Anything left as null shows "coming soon" or "Ask us" instead of a made-up number.

BEFORE GOING LIVE
- Connect the demo form (formEndpoint). Until then it tells visitors nothing was sent.
- Feature lists on Home and Industries are draft copy. Remove anything CrateX doesn't do yet.
- Privacy and Terms pages are placeholders. Add real ones before launch.
- Fonts load from Google Fonts, so the page needs internet to show the right typefaces.

PHOTOS
The photos in img/ are AI-generated sample images (no real store or brand). Swap in your own photos of Cravin Crispy and real customers by replacing the files with the same names.
