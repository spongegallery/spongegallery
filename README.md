# Sponge Gallery — GitHub Pages website

## Included
Menus: Artists, Exhibitions, Artfair, News, Shop, About, Contact.
Artist directory supports list/grid views. Profiles include biography, CV links, selected artworks, related exhibitions, and press. Exhibitions and fairs have All, Current, Upcoming, and Past filters. Detail pages include dates, overview, installation views, artwork galleries, and related artists. Shop supports purchase inquiries, not online checkout.

The page structure takes inspiration from Pilar Corrias. The styling is a simple temporary black-and-white gallery layout. Real artists, exhibitions, artworks, dates, addresses, and images have not been invented or copied. Empty states appear until your information is added.

## Preview
Extract this ZIP. Open index.html in your browser. No installation, paid service, or build command is required.

## Edit your content
Open content.js in a text editor. Edit contact details and About wording. Add entries to the artists, exhibitions, fairs, news, and shop arrays. Complete examples are included in the comment at the bottom of content.js. These are examples only; replace them with actual information before making entries visible.

Use unique IDs such as artist-name or exhibition-title. A profile opens at artist.html?id=artist-name. Link exhibitions to artist profiles using artistIds. Dates must use YYYY-MM-DD. Dates determine current/upcoming/past categories. Include a start and end date for each event. Link CV files using paths such as assets/artist-cv.pdf.

Put pictures into assets/ and reference them as assets/your-picture.jpg. Text fields accept plain text, not HTML. New lines are supported in biography and description fields. Replace colors, typography, and layout in style.css.

## Inquiries
Set email in content.js to your actual gallery email. Enquire opens a form, then prepares an email in the visitor's email application. The visitor reviews and sends it themselves. There is no server, message database, or automated delivery service. Without a configured gallery email, the form clearly states that no inquiry can be sent.

## Publish free with GitHub Pages
1. Create a public GitHub repository called sponge-gallery.
2. Upload the contents of this ZIP directly into the repository root, including the assets folder. Do not upload the ZIP itself or put everything inside an additional enclosing folder.
3. Go to repository Settings > Pages. Under Build and deployment, choose Deploy from a branch, main, /(root), then Save.
4. GitHub supplies the live URL. No build workflow is needed.

## Your domain
This package intentionally has no active CNAME file, so uploading it does not immediately redirect the GitHub preview to spongegallery.com. When you are ready to move your domain from its current host, set spongegallery.com under repository Settings > Pages > Custom domain before changing DNS. GitHub will create the CNAME file when using branch deployment.

Official custom-domain guide:
https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site/managing-a-custom-domain-for-your-github-pages-site

## Update existing Cloudflare Pages instead
This same ZIP also works with Cloudflare Pages direct upload. Upload a new production deployment in your existing project to keep your current domain connection. No GitHub account is required for that approach.

## File map
index.html — homepage
artists.html / artist.html — directory and individual profile
exhibitions.html / exhibition.html — exhibition listing and detail
artfair.html / fair.html — fair listing and detail
news.html / article.html — news listing and article
shop.html / item.html — shop listing and item
about.html / contact.html — gallery and visitor information
content.js — all content and contact settings
app.js — interactions and page rendering
style.css — design
assets/ — your photos and PDFs
favicon.svg — temporary gallery icon
.nojekyll — disables GitHub's Jekyll processing

## Status
Prepared for upload. This package has not been published and makes no changes to your existing live site or DNS.
