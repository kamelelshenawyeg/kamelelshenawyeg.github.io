# Portfolio page build plan (rest-of-site track, nothing live without Kamel's OK)
State: portfolio.html has 7 category buttons but only one "No work added yet" block -
the whole page is empty. Buttons only swap the heading (site.js). Items need real markup.

## His 8 services -> content mapping (all grounded in /memory/knowledge/facts/kamel-portfolio-clients.md)
1. Web Development: water-consult.com, remondshades.com, omegambbr.com.eg, archpix.ae, dishesnmore.com (site-*.svg previews exist in repo)
2. Performance Marketing: ads-*.svg, ga4-*.svg metrics (Dishes analytics)
3. Brand Identity: Omega, Heliopolis Coffee, Cupz, Aria AI, Peak, Remond, Faseel, Archpix (logo-*.svg / mark-*.webp exist)
4. Social Media Management: brand windows (cuphungry1, heliopoliscoffee, remondshades, peak.marketing.company, barduportcairo, luuma.eg, walm.eg, eyeoftheworldteam, archpix.dxb) - respect work windows; link to Highlights
5. PR Campaigns: Omega expo government coverage; Archpix TV ad (Abu Dhabi channel, Ramadan 2025); Damanhour documentary ad
6. SEO & GEO: Dishes SEO results (Analytics/Search Console screenshots); 3 SEO files STILL OWED BY HIM - flag the gap on the page or leave a slot
7. B2B Marketing: WEC (water-consult.com, expos, email campaigns; wec-*.png assets exist)
8. Event Management: ICRD Conference Nov 7 2023; Global Water Expo Sep 26 2024 + Apr 24-29 2024

## Page work
- Add PR Campaigns, B2B Marketing, Event Management categories (match his 8 services exactly).
- Reuse existing assets (site-*.svg, ads-*.svg, ga4-*.svg, logo-*.svg, wec-*.png - convert the 580K/576K wec PNGs to WebP).
- Keep the approved theme (paper.css/home.css patterns, same viewer modal via data-gallery).
- Rules: no invented metrics; windowed content only; "about a year" wording for Omega lines; mobile layout unchanged.
- Perf side-quest: remove dead highlights/v*.js (v1..v15, 2.2MB) IF unreferenced (grep first).
- Deliverable: local build + screenshots at 390/1440 per category, report to main, deploy only on his OK.
