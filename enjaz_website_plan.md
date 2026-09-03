# Enjaz (إنجاز) — Services Website Plan

Company profile site for **إنجاز للمقاولات والتوريدات ونقل البضائع**
(Enjaz for Contracting, Supplies & Goods Transport)

---

## 1. Verified Business Details (from Commercial Registry)

| Field | Value |
|---|---|
| Trade name | إنجاز للمقاولات والتوريدات ونقل البضائع |
| Brand name | إنجاز (Enjaz) |
| Owner | Mohamed Sayed Ahmed Ghallab |
| Core activity | Other unclassified wholesale trade (code 469099) |
| Activity detail | General supplies (توريدات عمومية); domestic goods transport & shipping (نقل بضائع وشحن داخلي) — excludes computer supply/import-export, advertising materials, labor supply |
| Registered capital | 100,000 EGP |
| Address | 4 El-Tayaran St., in front of the Health Insurance Hospital, Office H2, Nasr City, Cairo |
| Activity/license start | 2026 |
| Commercial Registry No. | 130907 |

**⚠️ Privacy note:** National ID number and birth date appear in the registry document but must **never** be published on the public site — only business name, activity, address, and a business phone/WhatsApp (once provided) belong on a public page.

---

## 2. Scope: Services-Only Site

Client confirmed: **services/activities only** — no project photos or gallery. Single-purpose company profile page.

### Site sections

1. **Hero** — company name + tagline built from registered activity (general supplies + domestic goods transport & shipping)
2. **About/company strip** — short credibility line: registered commercial entity, based in Nasr City, Cairo. *(Registered capital is optional to display — include only if the client wants to project scale; otherwise leave out.)*
3. **Services**
   - **General Supplies (توريدات عمومية)** — needs specifics from client: what categories/goods does he actually supply?
   - **Domestic Goods Transport & Shipping (نقل بضائع وشحن داخلي)** — needs specifics: fleet size/type, coverage area/routes, capacity, if he wants to share
4. **Contact** — address (from registry), phone/WhatsApp (not in registry — need from client), optional simple contact form

No team directory, no engineer profiles, no projects gallery — this is a leaner scope than the contracting-company demo built earlier.

---

## 3. Content Gaps — Ask the Client

The registry confirms *what category* he's licensed for, not the day-to-day specifics that make the site feel real rather than generic:

- [ ] What does he actually supply — materials, goods, equipment? Any categories/brands worth naming?
- [ ] What does the transport side cover — routes, cities, cargo types, fleet size?
- [ ] Business phone number and/or WhatsApp
- [ ] Any notable clients or years of experience he wants to reference (without naming clients if confidentiality matters)
- [ ] Logo, if one exists
- [ ] Arabic only, or bilingual Arabic/English?

---

## 4. Hosting, Domain & Pricing

Same setup as previously discussed — reusable for this project too:

- **Hosting:** GitHub Pages (free)
- **Domain:** paid custom domain (~500–800 EGP/year)
- **Pricing:** this is a smaller scope than the earlier contracting-company demo (no projects gallery, no team directory), so it likely sits at the lower end — roughly **3,000–8,000 EGP** for a simple static services page, more if a contact form with backend handling or bilingual RTL support is added.

---

## 5. Reusable Prompt (for Claude Code / Cline / any AI coding tool)

```
Build a single-page static website for إنجاز (Enjaz), a supplies and
domestic goods transport company in Cairo, Egypt. Plain HTML/CSS/JS,
one file, no frameworks, fully responsive. [Arabic RTL / bilingual —
confirm with client].

Sections:
1. Hero — company name + tagline (general supplies & domestic goods
   transport/shipping)
2. About strip — short credibility line: registered commercial entity,
   based in Nasr City, Cairo
3. Services — two categories: General Supplies, and Domestic Goods
   Transport & Shipping, each with a short description
4. Contact — address (4 El-Tayaran St., Nasr City, Cairo), phone/WhatsApp,
   simple contact form or mailto link

Do NOT include any personal identifiers (no National ID, no birth date) —
business-level contact info only.

Design direction: avoid generic AI-template look — no cream background
with serif+terracotta combo, no black background with neon accent, no
identical rounded cards with matching drop shadows, no ALL-CAPS labels
or arrow (→) buttons. Keep it clean and functional — this is a
logistics/supplies company, not a design-forward brand, so prioritize
clarity and trust signals (registered business, real address, direct
contact) over visual flourish.
```

---

## Open Items

- [ ] Specific supply categories/goods
- [ ] Transport coverage area, fleet, cargo types
- [ ] Business phone / WhatsApp number
- [ ] Logo (if available)
- [ ] Arabic-only or bilingual
- [ ] Final agreed price with client
- [ ] Domain name choice
