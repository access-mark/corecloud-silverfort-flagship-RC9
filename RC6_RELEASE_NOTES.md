# CoreCloud RC6 — release candidate for staging (NOT production certified)

## Completed
- Navigation styling rebuilt around original CoreCloud restraint, no permanent pill/dot, with one clear active-state underline.
- One navigation controller for desktop dropdowns and keyboard interactions.
- All assessment result capture forms use native FormSubmit POST; assessment score, classification, and all question/answer text included.
- Removed Google Apps Script and local-only lead-capture code and configuration.
- Guide form redirect normalised to thank-you page (FormSubmit delivery still requires real-world testing).
- Rebuilt sitemap with all intended indexable pages; excluded 404 and thank-you, marked those noindex.
- Removed old nav JS files. No production CNAME.

## Production gates (must not be marked PASS without evidence)
1. Verify FormSubmit recipient activation, real delivery to sales@corecloudza.com, guide fulfillment, and all redirects.
2. Visual regression on live staging at mobile/tablet/desktop/ultrawide including navigation and cards.
3. Official Silverfort, LSD Open and ReWorks brand assets pending.
4. External links and third-party availability; PageSpeed Insights / Lighthouse / real Core Web Vitals measurement.
5. Google Search Console verification, sitemap submission, and production indexing review after deployment.

## Note
This is a static-site source remediation, not an assertion that search traffic or rankings are guaranteed.
