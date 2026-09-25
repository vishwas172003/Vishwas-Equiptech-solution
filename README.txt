VISHWAS EQUIPTECH SOLUTIONS - WEBSITE
=====================================

DEPLOY ON VERCEL
1. Upload everything in this folder to your GitHub repository
   (replace the old files and delete the old assets folder first).
2. Vercel redeploys automatically. Your domain settings stay the same.

To preview on your computer: extract the ZIP, then open index.html.
(Videos and photos need the extracted folder, not the ZIP itself.)


EASY THINGS TO CHANGE (all at the bottom of index.html, under "SETTINGS YOU CAN EDIT")
- phones ............ numbers shown when someone taps Call or WhatsApp
- whatsappTo ........ number that receives enquiry-form and feedback messages
- email ............. address that receives "Send by email" enquiries
- googleReviewUrl ... paste your Google Business review link to show a
                      "Review us on Google" button
- gstin ............. your GSTIN, shown in the footer when filled in
- REVIEWS ........... add real customer reviews (with their permission);
                      the review cards only appear once this list has entries


ADDING A PROJECT PHOTO
1. Save two copies of the photo as .webp:
   - full size (about 1600 px wide) in  assets/images/gallery/
   - small copy (about 560 px tall) in  assets/images/gallery/thumbs/
2. In index.html, find the "gallery" section, copy one line that starts with
   <a class="tile" and change the file names and the description.
   data-cat is the filter: air, workshop or oil.
   --ar is width divided by height (for example 1600 x 1200 = 1.333).


WEBSITE ADDRESS
The page, sitemap.xml and robots.txt use https://vishwasenterprises.in
If your live address is different, search-and-replace it in index.html,
sitemap.xml and robots.txt.


FOLDERS
assets/brand    logo, favicon, app icons
assets/brands   partner brand logos
assets/fonts    Barlow fonts (hosted with the site)
assets/images   hero photo, link-preview image, project gallery
assets/thumbs   video cover images
assets/videos   project videos (compressed for faster playback)
