---
layout: default
title: Privacy Policy
---
# FlickBox Privacy Policy

**Last updated:** October 10, 2026

**Developer:** Bounty LLC

**Contact:** [support@bountyapps.com](mailto:support@bountyapps.com)

FlickBox helps you identify movies and series from Instagram discoveries and save them to a personal library. This policy explains what stays on your device and what is processed online when you choose to use identification.

## Your library

Saved links, confirmed movies and series, favorites, and watch status are stored on your device. The main app and Share Extension exchange saved discoveries through protected shared storage. We do not synchronize your library to an account on our servers. Device backups may contain app data according to your Apple settings.

## Online identification

On first launch, you can read a short introduction and review the Terms and privacy disclosure. Online identification starts only after you select the agreement checkbox and tap Agree and continue. You can instead choose Use library only. When you enable it and request identification, we process:

- The Instagram Reel or post link you share, including its post identifier.
- Caption text and source metadata retrieved for that link, which can include hashtags, mentions, post identifiers and a preview-image URL.
- Titles you type, candidate titles, catalog results, your selected catalog result, and technical records such as request status, errors and processing time.
- An installation identifier and hashed access credential that associate requests with your installation and help enforce limits.

Our current identification pipeline reads captions; it does not analyze video, audio or comments. Do not submit sensitive personal information or content you are not permitted to share. Captions may contain information about their authors or other people.

## Service providers

Our backend runs on **Cloudflare**, which processes requests and stores recognition history in its database. **ScrapeCreators** receives the Instagram link to retrieve source metadata. **OpenAI** receives caption text and candidate/catalog context to identify possible titles and compare catalog matches. **PoiskKino** receives title searches and catalog-detail requests. Typed-title searches also use online services.

We do not intentionally include your installation identifier or access credential in OpenAI prompts. Artwork and cast images load from catalog image hosts, which receive ordinary network requests from your device. Providers may process network information and retain data under their applicable policies and service agreements. Processing may occur outside your country.

We use these services to provide identification, secure access, prevent abuse, and investigate failures. We do not sell your personal information or use it for targeted advertising. This version contains no advertising or third-party analytics SDK.

## Installation security

The app uses **Apple App Attest** to verify a supported installation. Apple receives an attestation request; our backend receives cryptographic evidence and stores a key identifier and public key. Access credentials stay in the device Keychain and are shared with the extension. Our backend stores their hashes rather than the credentials themselves.

Cloudflare processes network metadata such as IP addresses to deliver and protect requests. Registration rate limits use a hashed IP address, request timestamps and temporary challenges. These identifiers are pseudonymous; they are not a claim that online processing is anonymous.

## Retention and deletion

Your library stays on your device until you delete its entries or remove the app, subject to device backups. Deleting a library entry does **not** delete its recognition history from our backend.

Recognition history, installation records and registration security records are currently retained without an automatic expiration schedule. We retain them to support request recovery, investigate failures and enforce access controls. To request deletion of backend records associated with your installation, email [support@bountyapps.com](mailto:support@bountyapps.com) with the support reference shown in Settings. Do not send your access credential. We may need to verify the request and may retain records where required for legal or security purposes. Provider-side data and backups may follow separate retention schedules.

## Your choices

You may save links and use your existing library without enabling online identification. Turn off **Allow online identification** in Settings to stop new identification requests. Turning it off does not recall requests already submitted or delete existing backend history; contact support to request deletion.

Depending on your location, you may have rights to access, correct or delete personal information, restrict processing, object to processing, or withdraw consent. Contact us to exercise these rights. Withdrawing consent does not affect processing that has already occurred. Where applicable, you may also contact your local data-protection authority.

## Support and children

If you contact support, we receive your email address, message and any information you choose to attach. Please avoid including sensitive data or private screenshots. FlickBox is not directed at children under 13, and we do not knowingly collect their personal information. Contact us if you believe a child has provided personal information.

## Changes and contact

We will update this page when our practices change and seek new consent where needed for a material change to online processing. Questions and privacy requests: [support@bountyapps.com](mailto:support@bountyapps.com).
