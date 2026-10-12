RecruiterPro website - Vercel deployment

FILES
  index.html   the website
  favicon.svg  browser tab icon
  robots.txt   search engine rules
  sitemap.xml  page list for Google
  vercel.json  Vercel settings

BEFORE YOU DEPLOY
  Replace YOUR-DOMAIN.co.uk with the real domain in:
  index.html (2 places), robots.txt, sitemap.xml

DEPLOY (no coding)
  1. Unzip this folder.
  2. Go to vercel.com, sign in, click Add New > Project.
  3. Drag the unzipped recruiterpro-site folder onto the page
     (or push it to a GitHub repo and import that repo).
  4. Framework preset: Other. No build command. Output directory: leave blank.
  5. Click Deploy.
  6. Settings > Domains: add the client's domain and follow the DNS steps.

DEPLOY (command line)
  npm i -g vercel
  cd recruiterpro-site
  vercel --prod

AFTER GOING LIVE
  - Add the site to Google Search Console and submit /sitemap.xml
  - Create a Google Business Profile for Leicester
  - Connect the contact form (e.g. Formspree) - it does not send yet
