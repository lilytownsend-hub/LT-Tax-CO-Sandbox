LT TAX CO. — SEARCH DISCOVERABILITY PACKET (2026-11-20)

FILES READY TO UPLOAD TO GITHUB REPOSITORY lilytownsend-hub/TaxCo, BRANCH main:
  robots.txt
  sitemap.xml

HOW TO UPLOAD
1. Open https://github.com/lilytownsend-hub/TaxCo
2. On the Code tab, choose Add file > Upload files.
3. Upload robots.txt and sitemap.xml (NOT the ZIP or README) to the repository ROOT, beside index.html and CNAME.
4. Commit directly to main.
5. After GitHub Pages deploys, visit:
   https://lttaxco.com/robots.txt
   https://lttaxco.com/sitemap.xml
   Both should show text/XML instead of a 404.

NEXT TASKS (NOT DONE BY THESE TWO FILES)
- Add page-specific meta descriptions, canonical tags, and appropriate JSON-LD structured data.
- Add service pages for any services that are genuinely offered (e.g. payroll) and link them from the homepage.
- Verify site ownership in Google Search Console and Bing Webmaster Tools; submit https://lttaxco.com/sitemap.xml.
- Check URL Inspection and indexing reports. A sitemap does not guarantee indexing or AI recommendations.

CAUTION
The sitemap contains only HTML pages confirmed to exist in the production repository. If any are intentionally private, unpublished, or not suitable for indexing, remove their <url> entry before upload. The robots file allows public crawler access; it does not force bots to crawl, index, or recommend the site. Do not put sensitive client data in this repository.
