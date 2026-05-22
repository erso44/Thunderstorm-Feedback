# Thunderstorm — Alpha Testing Guide for Creators

Welcome to the Thunderstorm alpha test! You are among the very first creators invited to explore the platform, and your feedback will directly shape the product before public launch. Thank you for taking the time — every bug you find and every impression you share makes a real difference.

**Status**: Alpha | **Started**: May 2026 | **Version**: 2.0

> **ALPHA DISCLAIMER** — Thunderstorm is in active development. Features may change, data may be reset, and some functionality is incomplete. Please do not use the platform for real business operations during the alpha period, and use test payment data only (see [Section 7](#7-payment-testing)).

---

## Quick Start (2 Minutes)

1. **Open**: [https://ek-thunderstorm.com](https://ek-thunderstorm.com)
2. **Register as a Creator**: go to `https://ek-thunderstorm.com/registration/customer` and follow the 4-step sign-up.
3. **Set up your store**: after registering you are guided through the onboarding wizard — profile, store details, payment setup, and your first product.
4. **Explore**: visit your **Dashboard**, open your **Shop**, browse the **Forum**, and check the **Live** area.
5. **Found a bug?** Report it on [GitHub Issues](https://github.com/erso44/Thunderstorm-Feedback/issues/new/choose) using the templates provided.

> **Note**: The platform interface is in **German**. See the [German Glossary](#3-platform-navigation--german-glossary) for translations of common terms.

---

## What's New

| Date | Update |
|------|--------|
| May 2026 | Alpha testing guide v2.0 — refocused for creators. Alpha opens to the first invited creators. |

*This section will be updated as we ship fixes and features based on your feedback.*

---

## Table of Contents

1. [Welcome](#1-welcome)
2. [Getting Started](#2-getting-started)
3. [Platform Navigation & German Glossary](#3-platform-navigation--german-glossary)
4. [Features & Test Scenarios](#4-features--test-scenarios)
5. [User Roles](#5-user-roles)
6. [Subscription Plans](#6-subscription-plans)
7. [Payment Testing](#7-payment-testing)
8. [Your Data & Privacy](#8-your-data--privacy)
9. [Alpha Tester Code of Conduct](#9-alpha-tester-code-of-conduct)
10. [How to Report Issues](#10-how-to-report-issues)
11. [Troubleshooting](#11-troubleshooting)
12. [Sharing Your Experience](#12-sharing-your-experience)
13. [FAQ](#13-faq)
14. [Contact](#14-contact)

---

## 1. Welcome

**Thunderstorm is the live-commerce platform for creators in Germany.** It brings live shopping, community, and your own online storefront together in one place — go live, sell products, build a community, and keep both your audience and your revenue. It is built EU-native: hosted in Germany, DSGVO (GDPR) and BGB compliant by design, with daily EUR payouts via Stripe Connect.

As a creator you can build a community, run a shop, manage inventory, broadcast live, and see your analytics — all from one dashboard. Members join your community, take part in the forum, browse your shop, and watch your streams.

**What is alpha testing?** You are among the first external creators to explore Thunderstorm. The platform is far enough along to run real creator workflows end to end — registration, building a community, listing products, going live — but it is pre-launch software. Expect rough edges, and expect us to ship fixes quickly based on what you report.

### What We Ask

- **Initial session**: spend 30–60 minutes exploring the platform, following the [test scenarios](#4-features--test-scenarios).
- **Come back**: after we ship updates based on your feedback, we may invite you to re-test. Revisits help us confirm that fixes actually work.
- **Report issues**: use the [issue templates](#10-how-to-report-issues) — the more detail, the faster we can fix it.
- **Be responsive**: if we follow up on something you reported, a quick reply helps us resolve it.
- **Be honest**: critical feedback is the most valuable kind.

### What We Especially Want to Learn

- Is the registration and creator-onboarding flow clear and smooth?
- Can you navigate the platform comfortably despite the German interface?
- Does setting up a shop and listing a product feel intuitive?
- Are there any confusing, broken, or dead-end screens?

### Alpha Timeline

| Phase | Timeframe | What Happens |
|-------|-----------|--------------|
| **Alpha** (current) | May 2026 | First invited creators explore the platform, report bugs, and share feedback. |
| **Fixes & Iteration** | Ongoing | We fix reported issues and ship updates. |
| **Beta** | To be announced | Broader testing with more users and more features. |
| **Public Launch** | To be announced | The platform opens to the public. |

### Tester Recognition

Creators who actively participate and provide quality feedback will be recognized in our launch credits, and will receive early access to new features before they go live for the public.

---

## 2. Getting Started

### Platform URL

**[https://ek-thunderstorm.com](https://ek-thunderstorm.com)**

### Supported Environments

| Browser | Status | Notes |
|---------|--------|-------|
| Google Chrome (latest) | Recommended | Primary testing browser |
| Mozilla Firefox (latest) | Supported | Fully functional |
| Microsoft Edge (latest) | Should work | Not actively tested |
| Safari (latest) | Should work | Not actively tested |

**Platform**: designed for desktop browsers. Mobile responsiveness may vary during alpha.

**Language**: the interface is in **German**. A language switcher is available in the navigation area. See [Section 3](#3-platform-navigation--german-glossary) for a glossary of common terms.

### Register as a Creator

Creator accounts can manage a community, run a shop, sell products, broadcast live, manage inventory, and view analytics.

1. Go to `https://ek-thunderstorm.com/registration/customer`.
2. Complete the 4-step sign-up wizard:
   - **Los geht's (Get started)** — enter your email address to begin.
   - **Community** — choose your community name, type, and visibility.
   - **Konto (Account)** — choose your username and password.
   - **Plan** — choose a subscription plan (see [Section 6](#6-subscription-plans)).
3. You are then taken into the **creator onboarding wizard** to finish setting up your store (see below).

### Creator Onboarding

After registration, the onboarding wizard guides you through setting up your store. It has several steps:

1. **Set up your profile**
2. **Trader declaration** — your seller status
3. **Packaging registration (LUCID)** — for commercial sellers
4. **Authorised representative** — for commercial sellers
5. **Payment setup (Stripe Connect)** — connect a payout account
6. **Legal & tax details**
7. **Choose your username**
8. **Add your first product**
9. **Publish your store**

> **Tip for testers**: when asked for your **seller status**, choose **Consumer / private seller** (*Privatverkäufer*) if you are just testing. The business-only compliance steps (packaging registration, authorised representative) then skip automatically — they require real registration numbers you will not have for a test account.

> **Payment setup matters**: your shop's checkout only works once **Stripe Connect** payment setup is complete. Use test data for this step — see [Section 7](#7-payment-testing).

> **Region**: creator/seller onboarding currently supports **Germany only**. If you are testing from outside Germany, you will need to use a German address and German test bank details for the payment-setup step.

### Register as a Member (optional)

You can also create a **Member** account to test the platform from the buyer's side — browsing communities, taking part in forums, shopping, and watching streams. A Member account is created by **joining an existing community**:

1. Go to `https://ek-thunderstorm.com/registration/user`.
2. Choose a community to join, then enter your email address.

To test both perspectives, create one Creator account and one Member account, each with a different email address.

### Password Requirements

| Requirement | Rule |
|-------------|------|
| Length | 12–128 characters |
| Uppercase letter | At least 1 (A–Z) |
| Lowercase letter | At least 1 (a–z) |
| Digit | At least 1 (0–9) |
| Special character | At least 1 (for example `! @ # $ % & *`) |

### Multiple Accounts

You can create both a Creator and a Member account to test both experiences. Each account requires a **different email address**.

### Session

Your login session stays active and refreshes automatically for up to about a week. If it expires, simply log in again at the platform's login page.

---

## 3. Platform Navigation & German Glossary

The platform interface is in German. This glossary translates the terms you will encounter most often.

### Main Navigation Tabs

| German Label | English | What It Does | Who Can See It |
|--------------|---------|--------------|----------------|
| **Dashboard** | Dashboard | Overview with stats and quick actions | Creators only |
| **Forum** | Forum | Community discussions and posts | Everyone |
| **Shop** | Shop | Browse and buy products | Everyone |
| **Live** | Live | Live streaming sessions | Everyone |
| **Inventar** | Inventory | Stock levels, transfers, alerts | Creators only |
| **Lager** | Warehouse | Warehouse management | Creators only |
| **Analytik** | Analytics | Community and shop metrics | Creators only |

### Common UI Elements

| German Label | English |
|--------------|---------|
| **Warenkorb** | Shopping Cart |
| **Benachrichtigungen** | Notifications |
| **Einstellungen** | Settings |
| **Sammlungen** | Collections / Wishlists |
| **Kasse** | Checkout |
| **Meine Bestellungen** | My Orders |
| **Entdecken** | Discover |

### Button Labels

| German | English | | German | English |
|--------|---------|---|--------|---------|
| Erstellen | Create | | Speichern | Save |
| Bearbeiten | Edit | | Löschen | Delete |
| Abbrechen | Cancel | | Bestätigen | Confirm |
| Weiter | Next | | Zurück | Back |
| Schließen | Close | | Suchen | Search |
| Filtern | Filter | | Absenden | Submit |
| Anmelden | Sign In | | Abmelden | Sign Out |
| Registrieren | Register | | Änderungen speichern | Save Changes |
| Bild hochladen | Upload Image | | Entwurf speichern | Save Draft |

### Form Fields

| German | English | | German | English |
|--------|---------|---|--------|---------|
| E-Mail-Adresse | Email Address | | Benutzername | Username |
| Passwort | Password | | Vorname | First Name |
| Nachname | Last Name | | Beschreibung | Description |
| Titel | Title | | Telefonnummer | Phone Number |
| Land | Country | | Stadt | City |
| Postleitzahl | Postal Code | | Vollständiger Name | Full Name |

### Status Messages

| German | English | | German | English |
|--------|---------|---|--------|---------|
| Erfolgreich | Success | | Fehler | Error |
| Wird geladen... | Loading... | | Fehlgeschlagen | Failed |
| Ausstehend | Pending | | Aktiv | Active |
| Bestätigt | Confirmed | | Abgelehnt | Rejected |
| Genehmigt | Approved | | Inaktiv | Inactive |

### Common Nouns

| German | English | | German | English |
|--------|---------|---|--------|---------|
| Produkt | Product | | Bestellung | Order |
| Beitrag | Post | | Kategorie | Category |
| Mitglied | Member | | Mitglieder | Members |
| Nachricht | Message | | Kommentar | Comment |
| Community | Community | | Stream | Stream |

---

## 4. Features & Test Scenarios

Each feature below includes a guided test scenario. Follow the steps and note the expected result. If what you see differs from the expected result, report it as an issue.

### 4.1 Your Community

Your community is your home base — created during registration.

**Test Scenario: Review your community**
1. Open your **Dashboard**.
2. Confirm your community name and details are correct.
3. Open the **Entdecken** (Discover) area and find your community in the creator list.
4. **Expected**: your community appears with its name, description, and member count.

### 4.2 Shop & Products

Set up and browse your shop.

**Test Scenario: List and view a product**
1. During onboarding you add a first product — or open your **Shop** and create another.
2. Fill in a product name, description, price (in EUR), and image.
3. Save the product, then open your **Shop** as a visitor would.
4. **Expected**: your product appears in the shop with its price in EUR and a product detail page.

### 4.3 Inventory Management

Track stock levels for your products.

**Test Scenario: Browse inventory**
1. Open the **Inventar** (Inventory) tab.
2. **Expected**: the inventory dashboard lists your products with their stock quantities and any alerts.

### 4.4 Analytics

See how your community and shop are performing.

**Test Scenario: View analytics**
1. Open the **Analytik** (Analytics) tab.
2. **Expected**: the dashboard loads KPI cards with community and shop metrics.
3. Try the time-filter options and the **Exportieren** (Export) button.

### 4.5 Live Streaming

Explore the live streaming area.

**Test Scenario: Browse the Live area**
1. Open the **Live** tab.
2. **Expected**: the page loads with search, sort, and status filters. If no creators are currently streaming, the list is empty — this is normal.

### 4.6 Forum / Discussions

Run and take part in community discussions.

**Test Scenario: Create a forum post**
1. Open the **Forum** tab within your community.
2. Choose a category and click **Neuer Beitrag** (New Post).
3. Enter a title and body text. Try the editor tools (**Fett**/Bold, **Kursiv**/Italic, lists).
4. Click **Absenden** (Submit).
5. **Expected**: your post appears in the category, and you can view and reply to it.

### 4.7 Settings & Profile

Update your account settings.

**Test Scenario: Update your profile**
1. Open **Einstellungen** (Settings) from your profile menu.
2. Update your profile information (bio, display name).
3. Click **Änderungen speichern** (Save Changes).
4. **Expected**: the changes are saved and a success message appears.

### 4.8 Subscription Payment

Test the subscription payment during creator registration.

**Test Scenario: Complete a subscription payment**
1. During the **Plan** step of registration, choose a **paid plan** (Pro or Business) — the free Starter plan has no payment step.
2. Enter the test card number `4242 4242 4242 4242` (see [Section 7](#7-payment-testing)).
3. Complete the payment.
4. **Expected**: the payment succeeds and you continue into creator onboarding.

---

## 5. User Roles

| Role | Description | Can Access |
|------|-------------|------------|
| **Owner** | Community creator with full control | Everything — Dashboard, Forum, Shop, Inventory, Warehouse, Analytics, Live, Settings |
| **Admin** | Elevated management access | Dashboard, Forum, Shop, Inventory, Analytics, Settings |
| **Moderator** | Content moderation | Forum moderation tools, basic platform access |
| **User** | Standard member | Forum, Shop, Live, Profile, Settings |

**For alpha testing**, we recommend registering as an **Owner** (via `/registration/customer`) to test the full creator experience. You can additionally register as a **User** (via `/registration/user`) to see the member experience.

---

## 6. Subscription Plans

When registering as a Creator, you choose one of these plans:

| Feature | Starter | Pro | Business |
|---------|---------|-----|----------|
| **Monthly price** | Free | €29.99 | €59.99 |
| **Annual price** | Free | €287.99 | €575.99 |
| Community members | 500 | 2,000 | 15,000 |
| Product listings | 50 | 250 | 3,000 |
| Storage | 2 GB | 15 GB | 20 GB |
| Live streaming | 720p · 15 hrs/mo | 1080p · 80 hrs/mo | 1080p · 150 hrs/mo |
| Concurrent streams | 1 | 2 | 3 |
| Viewers per stream | 50 | 200 | 500 |
| Forum categories | 10 | 25 | 100 |
| Moderators | 3 | 10 | 25 |
| Replay / VOD retention | 14 days | 30 days | 45 days |
| Live commerce (sell in streams) | — | Yes | Yes |
| Warehouse management (WMS) | — | — | Yes |
| Analytics | — | Basic | Full |
| Custom domain | — | — | Yes |
| API access | — | Read-only | Full |

**For alpha testing**: all plans work with test payment cards — no real charges are made. The free Starter plan has no payment step; choose Pro or Business if you want to test the subscription payment flow. The current published plan details are always shown on the platform's Pricing page.

---

## 7. Payment Testing

Thunderstorm uses Stripe in **sandbox (test) mode** for the alpha. No real money is charged.

> ⚠️ **Never enter real payment data.** Do not enter a real credit/debit card, real IBAN, or real bank account details anywhere on the platform — neither at subscription checkout nor during Stripe Connect payment setup. Use only the test data below.

### Subscription Test Cards

| Card Number | Result |
|-------------|--------|
| `4242 4242 4242 4242` | Payment succeeds |
| `4000 0000 0000 0002` | Payment is declined |

For all test cards:
- **Expiry**: any future date (for example `12/30`)
- **CVC**: any 3 digits (for example `123`)
- **Postal code**: any 5 digits (for example `12345`)

### Stripe Connect Onboarding (Payment Setup)

During creator onboarding, the **Payment setup** step opens Stripe's secure onboarding form so you can connect a payout account. In test mode, Stripe expects **test data** — never real personal or banking details. Typical Stripe test values:

- **Phone**: `000 000 0000`
- **Date of birth**: any date that makes you over 18 (for example `01/01/1990`)
- **Test German IBAN**: `DE89 3704 0044 0532 0130 00`

> If a field rejects these values, check Stripe's current testing documentation for the latest test data — Stripe occasionally updates it. Remember: creator/seller onboarding currently supports **Germany only**.

All prices on the platform are shown in **EUR**.

---

## 8. Your Data & Privacy

This is a short summary for alpha testers. The full, authoritative document is the **Privacy Policy** at [https://ek-thunderstorm.com/privacy-terms](https://ek-thunderstorm.com/privacy-terms).

**Data controller.** ThunderLabs UG, Baumensteinstr. 2, 89134 Blaustein, Germany — the controller under Art. 4 No. 7 GDPR. Full company details are in the Impressum at [https://ek-thunderstorm.com/legal-notice](https://ek-thunderstorm.com/legal-notice).

**What we process during the alpha.**
- **Account data** — your email address, username, and password. Your password is never stored in plaintext; it is kept only as a salted hash.
- **Activity data** — how you use the platform, for testing and improvement purposes.
- **Content** — any communities, posts, comments, or products you create.

**Legal bases.** Processing for your participation in the alpha test rests on performance of the testing arrangement; activity/usage data is processed on the basis of our legitimate interest in operating, securing, and improving the platform; where the law requires it (for example non-essential cookies), we rely on your consent.

**Payment processing.** Card and payout details you enter are handled by **Stripe**, our payment processor, in test mode during the alpha.

**Retention.** Account data is retained for the lifetime of your account and for 30 days after a deletion request. Usage and analytics data is aggregated or de-identified within 90 days. Tax-relevant records are retained for 10 years where the law requires (§147 AO). We will contact all testers before any data changes are made at the end of the alpha.

**Your rights.** Under the GDPR you have the right to access, rectification, erasure, restriction, data portability, and to object to processing. You also have the right to lodge a complaint with the competent supervisory authority — for ThunderLabs UG this is the *Landesbeauftragte für den Datenschutz und die Informationsfreiheit Baden-Württemberg* (LfDI Baden-Württemberg). To exercise any of these rights, or to request deletion of your account, contact **ekthunderstorminfo@gmail.com**.

By participating in this alpha test, you acknowledge this summary and the full Privacy Policy.

---

## 9. Alpha Tester Code of Conduct

By participating in this alpha test, you agree to:

1. **Use test data for sensitive fields.** A real email address is required to register and will be processed as described in [Section 8](#8-your-data--privacy). For optional free-text fields (such as bios or addresses), avoid entering sensitive personal data. **Never enter real payment card, IBAN, or bank details** — Stripe is in test mode; use the test data in [Section 7](#7-payment-testing). Never enter another real person's data.
2. **Keep it appropriate.** Do not post offensive, harmful, or inappropriate content in forums, communities, or product listings.
3. **Hold public takes until launch.** Filing bug reports and feedback in this repository is exactly what we want — please do. What we ask you to hold back is posting public reviews, ratings, or social-media takes about the platform: it is pre-launch and changing fast, and we would love your public verdict once we are ready.
4. **No automated testing.** Do not perform automated scanning, load testing, penetration testing, or API fuzzing.
5. **Report security issues privately.** If you discover a security vulnerability, email it directly to us (see [Section 14](#14-contact)) — do not post it in a public issue, and do not attempt to exploit it or share it with others. Good-faith reports of issues you come across through normal use of the platform are welcome and will never be held against you; the restriction is only on *active* exploitation or scanning.
6. **Respect other testers.** Do not access, modify, or delete other testers' accounts, communities, or content.
7. **Stay responsive.** If we follow up on a report you filed, please reply when you can — it helps us resolve issues faster.

---

## 10. How to Report Issues

Found something broken, confusing, or unexpected? Please report it!

### Where to Report

Go to [**New Issue**](https://github.com/erso44/Thunderstorm-Feedback/issues/new/choose) and choose the template that fits:

| Template | When to Use |
|----------|-------------|
| **Bug Report** | Something isn't working correctly |
| **Feature Request** | An improvement or new idea |
| **General Feedback** | Your overall experience or thoughts |
| **Security Concern** | Non-sensitive security UX issues (for vulnerabilities, email us directly) |

**Response time**: we acknowledge all reports within **48 hours**.

### Bug Report Template

If you prefer to write your own report, please include:

```
**Title**: [Short description of the issue]

**Steps to Reproduce**:
1. [First step]
2. [Second step]
3. [What happened]

**Expected Result**: [What should have happened]

**Actual Result**: [What actually happened]

**Browser & Device**: [e.g., Chrome 122 on Windows 11]

**Screenshot**: [Attach if possible]

**Your Username**: [Optional — helps us check server logs. If you'd rather not post it publicly, email it to us instead.]
```

### Severity Guide

| Severity | When to Use | Example |
|----------|-------------|---------|
| **Critical** | Cannot use a core feature at all | Cannot register, cannot log in, page crashes |
| **Major** | Feature is broken but a workaround exists | Cannot filter products, but can scroll to find them |
| **Minor** | Cosmetic or non-blocking issue | Misaligned button, untranslated label, slow loading |
| **Suggestion** | Idea or improvement | "It would be nice if..." |

---

## 11. Troubleshooting

Before reporting an issue, try these quick fixes:

| Problem | Try This |
|---------|----------|
| **Page looks broken or outdated** | Hard refresh: `Ctrl + Shift + R` (Windows/Linux) or `Cmd + Shift + R` (Mac) |
| **Cannot log in** | Check your username spelling (case-sensitive). Try clearing cookies for `ek-thunderstorm.com`. |
| **Session expired unexpectedly** | Log in again. Sessions refresh automatically for up to about a week. |
| **Buttons don't respond** | Try a different browser (Chrome or Firefox recommended). Disable browser extensions that might interfere. |
| **Page loads but shows no content** | Wait a few seconds — some data loads asynchronously. If still empty after about 10 seconds, report it. |
| **Error after an update** | We ship fixes regularly. Clear your browser cache or do a hard refresh to get the latest version. |

If none of these help, please [report the issue](#10-how-to-report-issues).

---

## 12. Sharing Your Experience

Beyond bug reports, we want to hear about your overall experience — you don't need to find a "bug" to give us valuable feedback.

Open a [**General Feedback**](https://github.com/erso44/Thunderstorm-Feedback/issues/new/choose) issue and share your thoughts. Some prompts to get you started:

- **What was the most confusing part** of using the platform?
- **What felt intuitive or well-designed?** What worked the way you expected?
- **What feature would you most want improved** before public launch?
- **How was the registration and onboarding experience?** Smooth? Confusing? Too many steps?
- **Would you recommend this platform to another creator?** Why or why not?
- **Any features you expected as a creator but didn't find?**

Every piece of feedback — positive or critical — helps us prioritize what to work on next.

---

## 13. FAQ

**Q: Will I be charged real money?**
A: No. Stripe is in test mode for the alpha. As long as you use the test data in [Section 7](#7-payment-testing), no real transaction occurs.

**Q: Why is everything in German?**
A: Thunderstorm targets the German-speaking market. A language switcher is available in the navigation area. See the [German Glossary](#3-platform-navigation--german-glossary) for translations of common terms.

**Q: I cannot see the Dashboard, Analytics, or Inventory tabs.**
A: These are only visible to Creator/Owner accounts. Register via `/registration/customer` to access them.

**Q: My shop checkout isn't working.**
A: Your shop's checkout only works once you have completed **Stripe Connect** payment setup during creator onboarding. See [Section 2](#2-getting-started).

**Q: Can I test from outside Germany?**
A: You can browse the platform from anywhere, but creator/seller onboarding currently supports **Germany only** — you will need a German address and German test bank details for the payment-setup step.

**Q: What happens to my data after the alpha?**
A: After the alpha period you can choose to keep your account and data or request full deletion. We will contact all testers before any changes are made. See [Section 8](#8-your-data--privacy).

**Q: Can I use the platform on my phone?**
A: The platform is designed for desktop browsers. Mobile responsiveness may vary during alpha.

**Q: How will I know when updates are shipped?**
A: We will update the [What's New](#whats-new) section at the top of this page and may reach out by email for major changes.

---

## 14. Contact

For questions, issues, or feedback:

- **GitHub Issues**: [erso44/Thunderstorm-Feedback](https://github.com/erso44/Thunderstorm-Feedback/issues) — for bugs, feedback, and feature requests.
- **Email**: ekthunderstorminfo@gmail.com — for security reports, account deletion, privacy requests, or questions outside GitHub.
- **Response time**: within 48 hours.

---

Thank you for being part of the Thunderstorm alpha! Your time and feedback are genuinely appreciated. Every report you file, every suggestion you make, and every impression you share helps us build a better platform for creators and their communities.
