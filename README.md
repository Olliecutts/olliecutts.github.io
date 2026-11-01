# King Chilli Comment Starter — private application information

This repository publishes the independent, static, informational GitHub Pages website for the privately operated **King Chilli Comment Starter** YouTube comment-reply tool. It does **not** host the automation, its OAuth credentials, its private comment ledger, its runtime configuration or live API endpoints.

## Live pages

- Homepage: https://olliecutts.github.io/
- Privacy: https://olliecutts.github.io/privacy/
- Terms: https://olliecutts.github.io/terms/

These URLs are intended as app identity/privacy links for the existing Google OAuth client. They are not hosted on `kingchillithepug.com`, and do not alter that public website or the CORE application.

## Google OAuth branding checklist

1. Confirm that the **exact existing King Chilli YouTube OAuth client** is associated with the selected Google Cloud project. Do not guess the project from an email or app name alone.
2. Verify ownership of `https://olliecutts.github.io/` through Google Search Console using its **URL-prefix** verification method (HTML tag in this repository's root `index.html` or the exact verification HTML file supplied by Search Console). Do not insert an invented verification token or expose OAuth secrets.
3. In the matched Google Auth Platform project, register the authorized top private domain `olliecutts.github.io` (subject to acceptance by the Google console), and use the three live URLs above in Branding.
4. Confirm the real app links and data practices are correct. Only then use Ollie's already-approved `Publish app` action to change the existing app from Testing to In production, and independently verify the status.
5. A published branding page **does not qualify** the separate private OAuth refresh, channel identity, project quota, YouTube canary or automatic runtime. Those gates remain under accepted CORE TISSUE #671.

**Important:** This website makes no claim that the YouTube automation is currently enabled, or that the existing durable ledger implements an automatic API-data deletion schedule. Before production activation, the operator must verify retention/revocation/deletion compliance with the [YouTube API Services Developer Policies](https://developers.google.com/youtube/terms/developer-policies).

## Maintenance

The content consists of `index.html`, `privacy/index.html`, `terms/index.html` and `assets/site.css`. It uses no third-party scripts, cookies, analytics or backend server. Update policy text when the actual implementation or data handling changes. The pages can be published from the `main` branch's root through GitHub Pages.

Contact: hello@kingchillithepug.com.
