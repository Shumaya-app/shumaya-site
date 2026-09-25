# Shumaya waiting list

Served at https://waitinglist.shumaya.app. Sign-up buttons open the Tally forms on waitlist.shumaya.app.

## Files

    index.html                    landing page (tradesperson + customer views)
    thank-you/provider/           Tally redirect after the /champion form
    thank-you/customer/           Tally redirect after the /customer form
    privacy/                      privacy policy
    404.html                      not-found page
    favicon-32.png, favicon.png, apple-touch-icon.png, icon-192.png, icon-512.png
    og-image.png                  1200x630 social preview
    site.webmanifest, robots.txt, sitemap.xml, CNAME, .nojekyll

## Deploy (GitHub Pages)

1. Upload everything in this folder to the root of a public repo, including the hidden .nojekyll file.
2. Settings → Pages → Deploy from branch → main / root. Custom domain: waitinglist.shumaya.app.
3. DNS: CNAME record, host waitinglist, value <github-username>.github.io.
4. Once the check passes, tick Enforce HTTPS.

## Tally

In each form: Settings → Redirect on completion
- champion form → https://waitinglist.shumaya.app/thank-you/provider/
- customer form → https://waitinglist.shumaya.app/thank-you/customer/

## After launch

Add the site in Google Search Console (DNS verification) and submit https://waitinglist.shumaya.app/sitemap.xml.
