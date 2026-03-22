TOWN & COUNTRY PLANNING LTD — Website Package
=============================================
townandcountryplanningltd.co.uk | March 2026

FILES INCLUDED
--------------
index.html      — Homepage
about.html      — About page (includes all 10 testimonials)
services.html   — Services page
gallery.html    — Project gallery (filterable, with lightbox)
faq.html        — FAQ page (accordion)
contact.html    — Contact page (with enquiry form)
css/style.css   — Shared stylesheet (all pages link to this)
README.txt      — This file

HOW TO PUT THIS LIVE ON GITHUB PAGES (step by step)
----------------------------------------------------

STEP 1 — Create a free GitHub account
  Go to: https://github.com
  Click "Sign up" and follow the steps.
  Use any email address you like.

STEP 2 — Create a new repository
  Once logged in, click the green "New" button (top left).
  Repository name: townandcountryplanningltd.co.uk
    (or any name you like — e.g. "tcpl-website")
  Set to: Public
  Tick: "Add a README file"
  Click: "Create repository"

STEP 3 — Upload the files
  Inside your new repository, click "Add file" > "Upload files"
  Drag ALL the files from this folder into the upload area:
    - index.html
    - about.html
    - services.html
    - gallery.html
    - faq.html
    - contact.html
    - css/  (the whole folder — drag it in)
  Click "Commit changes"

STEP 4 — Turn on GitHub Pages
  Click "Settings" (top of the repository page)
  Click "Pages" in the left sidebar
  Under "Branch", select "main" and click Save
  After a minute, you will see a green banner with your site URL.
  It will be something like:
    https://yourusername.github.io/tcpl-website/

STEP 5 — Point your domain at GitHub Pages
  This step requires access to your domain's DNS settings
  (usually with your domain registrar — e.g. 123-reg, GoDaddy, Namecheap).

  a) In your domain registrar's DNS settings, add these A records:
       185.199.108.153
       185.199.109.153
       185.199.110.153
       185.199.111.153

  b) Add a CNAME record:
       Name:  www
       Value: yourusername.github.io

  c) In GitHub Pages settings, enter your custom domain:
       townandcountryplanningltd.co.uk
     Tick "Enforce HTTPS"

  DNS changes can take up to 48 hours to propagate.
  GitHub will automatically issue a free SSL certificate.

THINGS TO DO AFTER GOING LIVE
------------------------------
1. CONTACT FORM
   The contact form currently uses a placeholder action URL.
   Sign up free at https://formspree.io
   Create a new form, copy your form ID, and replace
   "YOUR_FORM_ID" in contact.html with your actual ID.
   Alternatively, if hosting on Netlify, add data-netlify="true"
   to the <form> tag and Netlify handles form submissions for free.

2. GOOGLE MAP
   In contact.html, replace the Google Maps iframe src with
   your actual embed URL. Go to maps.google.com, search
   "13 Evelyn Road Cockfosters EN4 9JT", click Share >
   Embed a map, copy the iframe src.

3. LOGO IMAGE
   Currently the site uses a "TC" text mark.
   To add your actual logo, replace the .nav-logo-mark div
   in each HTML file with:
   <img src="images/logo.png" alt="TCPL" style="height:38px;width:auto">
   Upload your logo file to an "images/" folder.

4. YOUR EMAIL ADDRESS
   Add your email to the contact page if you wish.

5. GOOGLE ANALYTICS (optional)
   To track visitor numbers, sign up at analytics.google.com
   and add the tracking snippet to the <head> of each page.

NEED HELP?
----------
Call Martin: 07843 561129
