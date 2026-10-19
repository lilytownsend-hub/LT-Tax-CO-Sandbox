VANESSA 2.0 — LT TAX CO.

Files:
  vanessa.js — self-contained chat widget; inject once near the closing </body> of every site page.
  index.html — standalone test page.

Installation on LT Tax Co website:
  1. Upload vanessa.js to a public path on the website (e.g. /assets/vanessa.js).
  2. Before loading the script, set the verified site routes, e.g.:
     <script>
     window.LT_VANESSA_CONFIG = {
       freeResources:'/free-resources', contact:'/contact',
       bookkeeping:'/bookkeeping', consultations:'/tax-consultations',
       reviews:'VERIFIED_GOOGLE_REVIEW_URL',
       states:{'Wisconsin':'VERIFIED_OFFICIAL_WI_REFUND_TRACKER'}
     };
     </script>
     <script src="/assets/vanessa.js"></script>
  3. Do not copy the example route values without verifying them against the actual website.

Verified links already embedded:
  Booking: https://bookings.cloud.microsoft/book/LTTaxCo2@lttaxco.com/?ismsaljsauthenabled
  Client portal: https://taxestogo.com/App/Download/71228
  Federal refund: https://www.irs.gov/wheres-my-refund

Limitations before live deployment:
  - Missing internal route URLs, Google review URL and official state trackers must be verified and connected.
  - Approved mascot artwork was not changed or recreated; it must be separated from the approved reference artwork and added to the UI.
  - Navigation persistence requires integration with the actual website router; default widget fires 'lt-vanessa-navigate'.
  - The Back control is an initial implementation and needs more testing for nested branches.
  - No server-side staff contact capture, email notifications or redacted transcript delivery has been implemented; contact page is used instead.
  - Browser refresh intentionally resets chat.
  - Full production QA and security/accessibility review remain necessary.
