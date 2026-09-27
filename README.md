<p align="center"><img src="assets/banner.svg" alt="Life From Water — donation platform — Donations and impact you can check, for a water-access NGO in rural Egypt" width="100%"></p>

<p align="center"><b>Status:</b> Prototype live · donations switched on at launch &nbsp;·&nbsp; <b>Built by</b> <a href="https://github.com/Mohanad1st">Mohannad Hesham</a> &nbsp;·&nbsp; <b>Source:</b> private</p>

<p align="center" dir="rtl" lang="ar">منصة تبرع وشفافية أثر لمؤسسة من الماء حياة</p>

> **This is a showcase, not the code.** The source is private because the system handles real operations for real people. Nothing here is needed to run it, and nothing here reveals how it is secured. A live walkthrough is available on request.

## The problem

Donors are asked to trust a PDF report. Life From Water connects households in rural Egypt to clean water, and every connection has a place and a year. This platform lets a donor give in a few steps with local payment methods, get a receipt automatically, and see on a public map where funded work actually happened.

## What it does

- Arabic-first editorial pages for projects, programmes, partners, media and annual reports
- A public impact map of every funded site, with years and beneficiary counts
- One-time and recurring donations through Egyptian cards and wallets, with automatic receipts
- Donor accounts to see past gifts and manage recurring ones
- Memorial gifts with a dedication card
- A staff console for publishing bilingual updates

## See it

**[View the prototype →](https://lfw-mockup.vercel.app)**

<p align="center"><img src="assets/screen-1.png" alt="Homepage (Arabic)" width="92%"><br><sub>Homepage (Arabic)</sub></p>

<p align="center"><img src="assets/screen-2.png" alt="Public impact map of funded sites" width="92%"><br><sub>Public impact map of funded sites</sub></p>

<sub>All screens show demo data or public pages only.</sub>

## Built with

Next.js · TypeScript · Tailwind CSS · PostgreSQL with maps · local payment gateway · transactional email · bot protection

## Built responsibly

- Row-level security on every table; money and personal data can only be written by the server
- A receipt can't be opened with its reference number alone
- Bot protection and rate limits on donation and contact forms
- Staff sign-in uses one-time codes with attempt limits
- Independent security review rounds before launch, with every fix checked against the live system
- No secrets in source control, checked across the full history

## What it deliberately doesn't do

- The public prototype runs with payments and accounts switched off, on purpose, until launch sign-off.

## More from Life From Water

- [Ameen](https://github.com/Mohanad1st/ameen-showcase) — A finance desk you talk to — and that won't let donation money go astray
- [LFW HR System](https://github.com/Mohanad1st/lfw-hr-system-showcase) — Attendance, leave, overtime and approvals for a field NGO, in Arabic and English
- [Opportunity Studio](https://github.com/Mohanad1st/opportunity-studio-showcase) — An evidence-first pipeline for grants, fellowships and tenders

---

<sub>© 2026 Mohannad Hesham. Showcase text and images only — no source code is published or licensed here. See all my work on <a href="https://github.com/Mohanad1st">my GitHub profile</a> · <a href="https://www.linkedin.com/in/mohannadhesham/">LinkedIn</a>.</sub>
