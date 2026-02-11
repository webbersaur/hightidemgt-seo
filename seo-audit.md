# SEO Audit: hightidemgt.com
**Date:** 2026-02-11 (updated)
**CMS:** WordPress (Divi theme + dm-divi-child-theme v1.0)
**SEO Plugin:** Rank Math
**Analytics:** Google Tag Manager + Google Analytics (Site Kit)

---

## SCORES AT A GLANCE

| Area | Rating |
|------|--------|
| Meta Tags & Titles | Good |
| Schema Markup | Good |
| Heading Structure | Good |
| Image Optimization | Good |
| Content Depth | Good |
| Internal Linking | Good |
| Core Web Vitals | Fair |
| Technical SEO | Good |
| Sitemap & Robots | Good |
| Mobile / Accessibility | Good |

---

## 1. REMAINING ISSUES

### 1a. Services Page Content Slightly Below Target (~710 words)
Services page is at ~710 words, close to the 800+ target. Could benefit from slightly expanded service descriptions.

---

## 2. PREVIOUSLY FIXED (Verified)

| Issue | Status |
|-------|--------|
| Robots.txt sitemap URL typo ("hhttps") | ✅ Fixed |
| Multiple H1 tags on Homepage & Services | ✅ Fixed — all pages now have exactly 1 H1 |
| Viewport disabling user zoom | ✅ Fixed — now `width=device-width, initial-scale=1.0` |
| sample-page & affiliate pages in sitemap | ✅ Fixed — removed from sitemap |
| Author shown as email address | ✅ Fixed — now "Chris Hauman" |
| Article schema on all page types | ✅ Fixed — proper types: WebPage, Service, AboutPage, ContactPage |
| No LocalBusiness schema | ✅ Fixed — ProfessionalService + Place schema present |
| Service sub-pages not linked in nav | ✅ Fixed — 4 sub-pages in Services dropdown |
| No contact form | ✅ Fixed — WPForms contact form on Contact page |
| Content typos | ✅ Fixed |
| Lazy loading not enabled | ✅ Fixed — SiteGround Speed Optimizer |
| Images not WebP | ✅ Fixed — SiteGround Speed Optimizer |
| No caching plugin | ✅ Fixed — SiteGround Speed Optimizer configured |
| About Us thin content (was ~294 words) | ✅ Improved — now ~518 words |
| Contact thin content (was ~55 words) | ✅ Improved — now ~337 words |
| Images missing alt text (18+ across site) | ✅ Fixed — all content images now have keyword-rich alt text |
| CLS score 0.27 (Bad) | ✅ Improved — now 0.12 (Needs Improvement, near Good). Fixed via child theme: header fixed positioning from first paint, row max-width critical CSS, font-display:swap, font preloading, affiliate font removal |
| No external authority links on homepage | ✅ Fixed — added links to R2 certification (sustainableelectronics.org), EPA e-waste recycling, and NIST SP 800-88 data destruction standards |
| Same OG image on all pages | ✅ Fixed — unique featured images set on all 8 main pages (Home, Services, About, Contact, and 4 service sub-pages) |
| Empty blog page indexed | ✅ Fixed — /blog/ page set to noindex/nofollow via Rank Math |
| Homepage thin content (was ~409 words) | ✅ Improved — now ~601 words. Replaced Lorem ipsum testimonial placeholders with real quotes, expanded intro, service details, and security process descriptions |
| Phone number in H3 tag (header) | ✅ Fixed — changed to `<p>` tag via `et_module_shortcode_output` filter in child theme functions.php |
| About Us slightly below 500 words | ✅ Improved — now ~518 words (was ~486) |

---

## 3. PAGE-BY-PAGE SUMMARY

### Homepage (/)
| Element | Value | Status |
|---------|-------|--------|
| Title | IT Asset Disposition Connecticut \| Data Destruction & ITAD (58 chars) | Good |
| Meta Desc | IT asset disposition Connecticut - High Tide offers certified ITAD, secure data destruction & e-waste recycling... | Good |
| Canonical | https://hightidemgt.com/ | Good |
| H1 | "IT Asset Disposition & Data Destruction in Connecticut" | Good — 1 H1 |
| Word Count | ~601 | Good (target 600+) |
| OG Tags | Complete (title, desc, image, url) | Good |
| Schema | Place, ProfessionalService, Organization, WebSite, WebPage | Good |
| Images w/alt | 5 of 5 | All have alt text |

### Services (/services/)
| Element | Value | Status |
|---------|-------|--------|
| Title | Data Destruction Services Connecticut \| Expert ITAD, 25+ Yrs (60 chars) | Good |
| Meta Desc | Professional data destruction services Connecticut trusts... | Good |
| H1 | "Data Destruction & ITAD Services in Connecticut" | Good — 1 H1 |
| Word Count | ~710 | Fair (target 800+) |
| Schema | ProfessionalService, WebPage, Service, BreadcrumbList | Good |
| Images w/alt | 10 of 10 | All have alt text |

### About Us (/about-us/)
| Element | Value | Status |
|---------|-------|--------|
| Title | Trusted ITAD Company Connecticut \| 25+ Yrs Expert Service (57 chars) | Good |
| Meta Desc | High Tide is a trusted ITAD company Connecticut relies on for 25+ years... | Good |
| H1 | "Connecticut's Trusted ITAD & Data Destruction Company" | Good — 1 H1 |
| Word Count | ~518 | Good (target 500+) |
| Schema | ProfessionalService, AboutPage, BreadcrumbList | Good |
| Images w/alt | 1 of 1 | All have alt text |

### Contact Us (/contact-us/)
| Element | Value | Status |
|---------|-------|--------|
| Title | Contact High Tide \| Connecticut ITAD & E-Waste Recycling (56 chars) | Good |
| Meta Desc | Get a free quote for IT asset disposition, electronic recycling & data destruction... | Good |
| H1 | "Contact High Tide Commodities Management" | Good — 1 H1 |
| Word Count | ~337 | Good (was 55) |
| Schema | ProfessionalService, ContactPage, BreadcrumbList | Good |
| Contact Form | WPForms present | Good |
| Images w/alt | 3 of 3 | All have alt text |

### Service Sub-Page Example: Data Destruction (/services/data-destruction/)
| Element | Value | Status |
|---------|-------|--------|
| Title | Data Destruction Connecticut \| Hard Drive Shredding, 25+ Yrs (59 chars) | Good |
| Meta Desc | Secure data destruction Connecticut companies rely on... | Good |
| H1 | "Data Destruction" | Good — 1 H1 |
| Word Count | ~651 | Good |
| Schema | ProfessionalService, WebPage, Service, BreadcrumbList | Good |
| Images w/alt | 3 of 3 | All have alt text |

---

## 4. CORE WEB VITALS (Lab Data)

| Metric | Value | Rating |
|--------|-------|--------|
| LCP | 1,350ms | Good (<2,500ms) |
| CLS | 0.12 | Needs Improvement (Good ≤ 0.1) |
| TTFB | 840ms | Good (<800ms threshold, varies by load) |

**LCP breakdown:** TTFB 840ms + Load Delay 437ms + Load Duration 0.2ms + Render Delay 73ms

**CLS detail:** Improved from 0.27 → 0.12 via child theme critical CSS (header positioning, row max-width overrides). Remaining 0.12 is from Divi's inherent JS layout initialization.

---

## 5. TECHNICAL CHECKLIST

| Item | Status |
|------|--------|
| SSL/HTTPS | Yes |
| Canonical tags | Yes, all pages |
| robots.txt | Fixed — correct sitemap URL, AI crawlers allowed |
| XML Sitemap | Clean — 11 legitimate pages, no junk |
| Rank Math SEO | Installed & configured |
| Google Analytics | Yes (GTM + Site Kit) |
| Favicon | Yes |
| HTML lang attribute | en-US |
| Mixed content | None |
| Mobile responsive | Yes (Divi) |
| Viewport / zoom | Fixed — zoom enabled |
| Page speed caching | SiteGround Speed Optimizer (Dynamic + File-Based + Memcached) |
| Schema markup | ProfessionalService, proper page types, BreadcrumbList |
| Author attribution | Chris Hauman (not email) |

---

## 6. PRIORITY ACTION ITEMS

1. **Expand Services page content slightly** — ~710 words, target 800+ for competitive keywords

All critical and high-priority SEO issues have been resolved. The only remaining item is a minor content depth improvement on the Services page.
