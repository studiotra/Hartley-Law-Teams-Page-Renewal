# Team-page references for Hartley Law Group

Prepared 2026-10-01 (MT) for Petra R. Companion to the Team page section of `hartley-ux-evaluation.docx`.

**How to read this.** Every URL below was either opened during this research (marked **Opened**) or appeared in a search result (marked **Search result only**). "What we saw" is limited to what was on the page or in the snippet. No prices, ratings or sales figures are listed unless they appeared on a page I saw. Nothing here is a claim about the firms' results; several of these sites show awards or case figures that we should **not** imitate unless Hartley can verify equivalents.

**Drafts:** A = `draft-a-editorial.html` (large editorial profile blocks), B = `draft-b-grid-filter.html` (card grid, filter chips, hover reveal), C = `draft-c-roster-profile.html` (compact roster + sticky profile panel).

---

## Part 1. Live law-firm and professional-services team pages (12)

| # | Name | URL | Status |
|---|------|-----|--------|
| 1 | Valken (Swiss law firm) | https://valken.legal/team | Opened |
| 2 | Gerstein Harrow LLP | https://gerstein-harrow.com/index.html | Opened |
| 3 | Samfiru Tumarkin LLP | https://stlawyers.ca/team/ | Opened |
| 4 | Cole Schotz | https://www.coleschotz.com/professionals/ | Opened (HTML via curl; also described in a designer case study, #4b) |
| 5 | McMillan LLP | https://mcmillan.ca/people/ | Opened |
| 6 | Burke, Williams & Sorensen | https://www.bwslaw.com/meet-our-people/ | Opened |
| 7 | Bishop & McKenzie LLP | https://bmllp.ca/lawyers/ | Opened |
| 8 | Schropp Law Firm (Tampa) | https://www.schropplaw.com/ | Opened |
| 9 | Rackohn & Rackohn | https://rackohn.com/ | Opened |
| 10 | Arnold & Itkin LLP | https://www.arnolditkin.com/meet-our-attorneys/ | Opened with curl (the fetch tool was blocked by Cloudflare); quote text from search snippet |
| 11 | COGENT Executive (consultancy) | https://cogentexecutive.com/our-people/ | Opened |
| 12 | Sladen Consulting | https://www.sladenconsulting.com/our-dna/our-people | Opened |

### 1. Valken: https://valken.legal/team
- **What we saw:** A stat strip at the top of the team page (team size, bar admissions, languages spoken, average response time), then two tiers ("Partners & senior counsel", "Associates, counsel & desk leads"). Each person has title, language codes, a 2–3 line bio and 2–3 focus tags. Closes with a "Small firm. Senior hands. Every file." three-point section and contact block.
- **Learn:** Tiering by role with a short sentence explaining each tier; a *proof strip made of operational facts* (not awards); focus tags as small chips; a closing "how we work" argument that suits a small boutique.
- **Caution:** Its figures are the firm's own and we cannot verify them; Hartley's strip must only carry facts the firm confirms.
- **Informs:** **A** (intro paragraph + tier headings), **proof strip in all drafts**, **B/C** (tags).

### 2. Gerstein Harrow: https://gerstein-harrow.com/index.html
- **What we saw:** A small litigation boutique (six lawyers shown) with a single-page layout: confident headline ("Small firm. Big cases."), practice themes, then each lawyer as a short narrative paragraph with role (Partner / Associate), then "Contact the Firm".
- **Learn:** For a three-lawyer litigation firm, short narrative bios in a calm single column are enough; role label sits directly under the name; plain-language voice.
- **Informs:** **A** (restrained, text-led profile blocks).

### 3. Samfiru Tumarkin LLP: https://stlawyers.ca/team/
- **What we saw:** Team grid headed "Your legal team at…", with **All Locations** and **Practice Areas** filter controls above a long grid of headshots with name and title. Practice-area options: Employment Law, Disability Insurance Law, Personal Injury Law.
- **Learn:** Filter bar placed *above* the grid, location + practice as two dropdowns; every card is name + title only (fast scanning); image alt text carries role and city.
- **Caution:** At ~60 people, filters earn their place. At three attorneys they do not (see the evaluation, section 4.3), which is why Draft B labels the filter as a demonstration.
- **Informs:** **B** (filter placement and card minimalism).

### 4. Cole Schotz: https://www.coleschotz.com/professionals/
- **What we saw (HTML):** Page title "Professionals Archive"; search by name; **Practice**, **Industry** and **Location** selects; an A–Z letter index. Practice options include Litigation. A designer's case study (4b below) describes the same page as a searchable grid with location filters and black-and-white portrait styling, each card linking to a skimmable profile.
- **Learn:** Combine name search + facets + alphabet; consistent monochrome portraits make mixed-quality photography look intentional (relevant while Hartley has mixed or missing portraits).
- **Informs:** **B** (filter pattern), **photo direction**.
- 4b. Case study: https://www.andrewkondratiuk.com/portfolio/cole (Opened). Also states that bios were reworked "with filters and direct contact" and mobile filters were redesigned to be thumb-friendly. (The page reports a time-on-site change; I have not reproduced it because it is the designer's own claim.)

### 5. McMillan LLP: https://mcmillan.ca/people/
- **What we saw:** "Our People" with an A–Z last-name index, Practices dropdown, and a list where each row is name, "Partner, [practice]", city, email and phone.
- **Learn:** Role + practice on one line, contact details on the row; a list is faster than cards when the visitor already has a name.
- **Informs:** **C** (roster row anatomy).

### 6. Burke, Williams & Sorensen: https://www.bwslaw.com/meet-our-people/
- **What we saw:** Filter People By **Practice** (includes Insurance Coverage and Litigation, Tort Claims and Products Liability) and By **Title** (Associate, Partner, Managing Partner, Of Counsel…); each entry shows role, office, direct phone and a vCard link.
- **Learn:** Filtering by *title* as well as practice; a "vCard" action is a low-cost trust/utility signal.
- **Informs:** **B** (secondary filter idea), **C** (profile panel actions).

### 7. Bishop & McKenzie LLP: https://bmllp.ca/lawyers/
- **What we saw:** A Canadian (Alberta) firm: each lawyer is name, "Partner | edmonton", email, then a bulleted practice-area list. No filter UI.
- **Learn:** Practice areas as plain lists work on a small scale and are very accessible; role | office pattern.
- **Informs:** **C** (practice focus list in the profile panel).

### 8. Schropp Law Firm, Tampa: https://www.schropplaw.com/
- **What we saw:** A Tampa Bay civil-litigation and appellate boutique that handles policyholder coverage matters. Home page leads with three practice cards (Insurance Coverage, Appeals, Civil Litigation), then an "Attorney Profiles" block with two attorneys and short teasers; address and phone in the footer.
- **Learn:** The *local peer set* Hartley is compared with: appeals and coverage are presented as separate, named strengths, which supports the tag set in our cards. Teaser + "read more" is the common local pattern, so a richer profile page is a differentiator.
- **Caution:** The site cites rankings and ratings; we do not reproduce those patterns without Hartley's own verified equivalents.
- **Informs:** **A/B** (practice tags), competitive context.

### 9. Rackohn & Rackohn: https://rackohn.com/
- **What we saw:** A two-partner insurance bad-faith boutique. Each partner has a short bio paragraph, then three bullets (e.g. bar membership, role, experience), then testimonials, and a consultation request link.
- **Learn:** Bar membership as a *bulleted fact*, not buried in prose: the pattern for our "At a glance" and admissions placeholders. Closing consultation prompt after the bios.
- **Informs:** **A** (glance grid), **C** (admissions list).

### 10. Arnold & Itkin: https://www.arnolditkin.com/meet-our-attorneys/
- **What we saw:** Headed "Meet Our Team of Attorneys", grouped into **Partners** and **The Team**; a search snippet shows a one-line personal quote per attorney and a "Meet [First name]" link.
- **Learn:** First-name "Meet Josh" link wording (friendly, specific); one-sentence personal quote (we mirrored this as an "Approach" placeholder: the lawyer's own words, firm to supply).
- **Caution:** A large plaintiffs' firm with a loud tone; borrow the interaction wording, not the voice.
- **Informs:** **A/B** (link wording, approach line).

### 11. COGENT Executive: https://cogentexecutive.com/our-people/
- **What we saw:** Leadership profiles each with a visible **"Tap for Bio"** control; bios of different lengths.
- **Learn:** An explicit tap affordance on touch devices rather than hover-only reveals.
- **Informs:** **B** (our hover reveal is always visible on touch via `@media (hover:none)` and the whole card is a link).

### 12. Sladen Consulting: https://www.sladenconsulting.com/our-dna/our-people
- **What we saw:** "Hover over the profiles below to discover the passions and interests that shape our people." Leadership trio first, then a wider network listing.
- **Learn:** Hover reveals add personality, but hover-only content is risky; keep critical facts visible and treat the reveal as bonus.
- **Informs:** **B** (reveal restraint).

**Also opened, lower relevance:** Tonkon Torp https://tonkon.com/attorneys/ (filter options show result counts next to each practice, e.g. "Appeals (5)", a pattern worth copying when the team grows; row = role, name, phone, email). Lavery https://www.lavery.ca/en/team.html?afficherTout=1 (very long list; shows the pattern to avoid at small scale).

**Search result only (not successfully opened):** Fried Frank https://www.friedfrank.com/our-people (filters Office / Service / Position); Gilbert + Tobin https://www.gtlaw.com.au/people (expertise / role / location filters; cards show contact details; the site blocked the fetch tool). Roundups consulted for context, not as team-page examples: Clio https://www.clio.com/blog/best-law-firm-websites/ and Magier https://www.magier.com/blog/best-law-firm-website-designs (the latter reports YLaw's "Book Your Consultation Now" button attached to each attorney; I did not independently see that on YLaw's home page https://ylaw.ca/).

---

## Part 2. Marketplace templates with strong team / attorney layouts (10)

**Access note:** ThemeForest pages return a Cloudflare check to the fetch tool, so ThemeForest entries are based on **search-result snippets** (text visible in the result) unless stated. I could not check ratings, sales counts or current prices on those listings, so none are given except where noted. Please open each listing in a browser before shortlisting. Demo pages that I did open are marked **Opened**.

| # | Template | URL | Stack | Seen how |
|---|----------|-----|-------|----------|
| T1 | Legal Business (cmsmasters) | https://themeforest.net/item/legal-business-attorney-lawyer-wordpress-theme/48998546 | WordPress + Elementor | Search result only |
| T2 | Justico (themelexus) | https://themeforest.net/item/justico-attorney-law-firm-wordpress-theme/61058954 | WordPress | Search result only |
| T3 | Lawfic (peacefulqode) | https://themeforest.net/item/lawfic-attorney-and-lawyer-wordpress-theme/47533332 | WordPress + Elementor | Search result only |
| T4 | Leolex (mototeam) | https://themeforest.net/item/law-firm-wordpress-theme-leolex/53511444 | WordPress + booking plugin | Search result only |
| T5 | Lawfinity (designingmedia) | https://themeforest.net/item/lawfinity-law-and-attorney-wordpress-theme/52005190 | WordPress (Bootstrap 4); HTML version also exists | Search result only |
| T6 | Lawsera (TogoTheme) | https://themeforest.net/item/lawsera-lawyer-attorney-law-firm-html5-template/62115645 | HTML5 / Bootstrap 5 | Search result + mirror page https://prowebthemes.com/themes/lawsera-lawyer-attorney-law-firm-html5-template/62115645 (Opened) |
| T7 | The Legato (webstrot) | https://themeforest.net/item/the-legato-lawyer-html-template/29655367 | HTML | Search result only |
| T8 | Regalis (designesia) | https://themeforest.net/item/regalis-lawyer-attorney-and-law-firms-html-template/62270751 | HTML; a separate WordPress version has the demo below | Search result; WP demo **Opened**: https://reactheme.com/products/wordpress/regalis/team-single/ |
| T9 | Lawyer Firm (Yves Adrales) | https://webflow.com/templates/html/lawyerfirm-law-firm-website-template | Webflow | **Opened** (listing + demo https://law-office-webflow-template.webflow.io/lawyers) |
| T10 | Jurid (Pilgrims) and Juristic | https://webflow.com/templates/html/jurid-law-firm-website-template ; demo https://juristic-template.webflow.io/attorneys | Webflow | Both **Opened** |

### T1. Legal Business: strongest fit for an Elementor site
- **Saw (snippet):** "Custom post types for attorney and team Profiles", emphasising qualifications, experience, specialties; Elementor with a bundled addon and ready templates for single post types and archives; four demos.
- **Learn:** The agency already builds in Elementor (per our evaluation), so a profile CPT + archive template is the realistic implementation route for `/team/` and `/team/{name}/`.
- **Informs:** all drafts, especially **C** (profile template as a CPT).

### T2. Justico
- **Saw (snippet):** "Attorneys Listing & Profile Pages": portrait & personal info, biography, areas of expertise, contact details, plus a "success rate & featured cases" block. Changelog line mentions a "team-list safari css" fix.
- **Learn:** Structured profile fields (portrait, bio, expertise, contact) are the data model we want. Skip the "success rate" block: no verified figures exist for Hartley.
- **Informs:** **C**, **A**.

### T3. Lawfic
- **Saw (snippet):** "Attorney & team pages to introduce lawyers, qualifications, experience and achievements"; "consultation-focused design with clear call-to-action sections for 'Request a Consultation'"; Elementor.
- **Learn:** CTA band language that matches our "Request a Consultation" button.
- **Informs:** CTA band (all drafts).

### T4. Leolex
- **Saw (snippet):** Team members and attorney profiles plus a bundled appointment-booking plugin with per-attorney availability. The search result showed **$49**; I did not confirm it on the listing.
- **Learn:** If the firm wants *booking* rather than a form, per-attorney scheduling is a natural extension of the per-attorney CTA.
- **Informs:** **C** (profile CTA).

### T5. Lawfinity
- **Saw (snippet):** "Team pages styles", "Attorney Practice law Custom Post Types", multiple styles for about/practice/team pages.
- **Learn:** Offering several team-page styles per theme shows how common the three patterns in our drafts are (editorial, grid, list).
- **Informs:** **A/B/C**.

### T6. Lawsera
- **Saw (mirror page, Opened):** 22 HTML pages including **team and team details**; charcoal + gold (#CD974E) palette; GSAP ScrollTrigger reveals; "respects prefers-reduced-motion"; Swiper team slider; sticky layouts and attorney profiles. Mirror page showed "$ 7"; I did not verify this on ThemeForest.
- **Learn:** Charcoal + gold is the same family as Hartley's navy/gold, but #CD974E is lighter than our #AE965C, so contrast rules still apply. Our reveal motion achieves the same effect with ~1 KB of vanilla JS instead of GSAP.
- **Informs:** motion plan (all drafts), **B**.

### T7. The Legato
- **Saw (snippet):** Attorney-specific pages and multi-column attorney listings; listing reports version 5.0, updated May 26, 2025, 53+ pages, 8+ homepage styles.
- **Learn:** Multi-column listing variants to compare against our 3-column card grid.
- **Informs:** **B**.

### T8. Regalis
- **Saw (snippet):** 10 homepage variations, attorney profiles, scroll animations, RTL support. The WordPress demo's *Team Single* page (Opened) shows a role headline, intro, a **numbered "Experiences" timeline** (dates + role + one sentence), and a repeated name/title block.
- **Learn:** A numbered experience list is a good way to structure the "Full background" section once Hartley supplies career history.
- **Informs:** **C** (profile sections), **A**.

### T9. Lawyer Firm (Webflow)
- **Saw (Opened):** Pages include **Lawyers (CMS)** and **Lawyer Single (CMS)**, Practice Areas, Case Results, Contact, Terms and Privacy; interactions included; single-use licence. Demo lists lawyers as name, title, email. Price not visible on the page text I received.
- **Learn:** The minimal list-style "Meet our Lawyers" page and the CMS split between listing and single page.
- **Informs:** **C**, IA (`/team/` + single).

### T10. Jurid and Juristic (Webflow)
- **Saw (Opened):** Jurid: a dedicated attorney list page; profile pages with bio, areas of practice, qualifications, contact; **multi-reference practice areas** and per-attorney contact forms. Juristic demo attorneys page groups people under Senior Partner / Partner / Associate.
- **Learn:** Practice areas as references (so the area page can list its attorneys, as our IA requires: "practice-area pages list their attorneys"); a contact form on each profile (our hidden-field attribution idea).
- **Informs:** **C**, **B** (tags as linked references), IA cross-links.

---

## Top picks

1. **Valken** (https://valken.legal/team): best model for tiering, a facts-only proof strip and a "small firm, senior hands" argument. → A and the proof strip.
2. **Samfiru Tumarkin** (https://stlawyers.ca/team/) and **Cole Schotz** (https://www.coleschotz.com/professionals/): the filter-bar-above-grid pattern for when the team grows. → B.
3. **Rackohn & Rackohn** (https://rackohn.com/) and **Gerstein Harrow** (https://gerstein-harrow.com/index.html): the right scale and tone for a 2–6 lawyer litigation boutique. → A and C.
4. **Bishop & McKenzie** (https://bmllp.ca/lawyers/) and **McMillan** (https://mcmillan.ca/people/): compact roster rows (role, practice, contact). → C.
5. **Legal Business** (cmsmasters, T1) and **Jurid** (Webflow, T10): the most realistic implementation paths (Elementor attorney CPT; Webflow CMS with multi-reference practice areas).

## What not to copy
- Hourly rates and emails on the team list (YLaw home page lists these), "success rate" blocks, unverified award badges, hover-only content, and any statistic the firm has not confirmed.

## Not verified
- ThemeForest ratings, sales, current prices and update dates (listings blocked the fetch tool; only search snippets were seen).
- Arnold & Itkin's hover behaviour and Cole Schotz's rendered grid (read from HTML / third-party description, not viewed in a browser).
- Gilbert + Tobin and Fried Frank (search snippets only).
