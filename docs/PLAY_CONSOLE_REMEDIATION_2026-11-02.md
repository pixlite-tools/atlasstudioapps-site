# Account remediation — 2 November 2026

## Completed in this website change

- Retain the existing domain, app-ads.txt publisher record and support email.
- Use Atlasova Studio consistently in the new site shell; explain the legacy Atlas Studio Apps name.
- Add accurate release-status pages for PixLite, RedBal and Atlas: Moroccan Darija. No public download, fabricated enrollment form or payment is advertised.
- Publish the existing RedBal source privacy notice at `/redbal/privacy-policy.html`, with the same substance and the updated canonical policy URL. Source: RedBal QA8 head 4fd12690ac74239361656a54121fc385677bc3c9, PRIVACY_POLICY.md. Health functionality is disclosed; advertisements and purchases remain described as disabled in builds 8/9.
- Retain the original August 18 general PixLite/Atlas notice under `/privacy-policy.html#existing-notice`. Its continued presence is not a certification that it is sufficient for a new release.
- Add support guidance, testing-interest email routes and unchanged real native screenshot sources.
- Website uses local CSS, no JavaScript, no embedded analytics/advertising, no third-party fonts, no form, and a restrictive meta CSP. Hosting and voluntarily emailed support information are disclosed.

## Verification

Static validation: seven HTML pages, one H1 each, internal URLs and anchors resolve, CNAME and publisher ID preserved, RedBal release scope checked. Local Chromium QA could not run: this execution environment denied the browser process socket. Do not describe local responsive/browser QA as passed. Follow up with a live browser check at mobile and desktop sizes after deployment; record actual results in this document.

## Console follow-through

After the live RedBal policy returns HTTP 200 without login and its content is verified, replace only the RedBal privacy URL in Play Console. Save as a pending change if supported; do not send the app for review or publish as part of the URL repair. Add the existing site URL to the personal developer profile if the editor does not require new legal declarations or identity/ownership actions.

## Decisions and gates still open

1. Trader classification approved by owner: individual, no registered entity, EEA/UK markets planned. A Trader form was not found in inspected pages. No official declaration submitted; do not mark Personal as equivalent to Trader.
2. RedBal health scope: the code includes medication schedules. Determine compliant account/release scope with the owner before public release. Do not change the declaration to “no health features” while retaining the features.
3. Data Safety: derive answers from the exact signed release and SDKs, including Google scanner diagnostics. Do not infer absence of collection from local record storage alone.
4. PixLite: production candidate includes Google Mobile Ads. QA used disabled ads; QA does not certify consent or production data disclosures. Review final SDK/permission inventory before replacing its general privacy notice.
5. Release signing, uploads, app-content submission, merchant onboarding, subscription products, distribution countries and closed-test enrollment remain separate gates. Do not create or accept any financial/legal setup automatically.
6. Closed test channels were inactive with no countries in the last read. Launch requires prepared release + correct setup, then at least 12 continuously opted-in testers for 14 days when this account's production gate applies. Do not replace real testing with simulated opt-ins.
7. Latest accepted QA resume points: PixLite PR5 (528e23f), RedBal PR3 (4fd1269). Preserve those results and coordinate before changing mobile release branches.

## Next launch work

- Finish release-specific policies, terms drafts, app-content answers and store assets from the final build.
- Decide health scope; finish real-device acceptance remaining in each QA PR.
- Prepare legitimate closed testing and clear feedback collection.
- Set up Google Play merchant products only when paid launch is approved; RedBal V1 currently keeps purchases and ads off.
