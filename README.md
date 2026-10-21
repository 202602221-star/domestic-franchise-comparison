# Guide to Comparing Domestic Franchises

**Creator:** Student project  
**Project:** Compare three South Korean fried-chicken franchise brands using one consistent metric.

## About
This responsive, single-file website compares BBQ, bhc, and Kyochon Chicken. It includes English, Nepali, Uzbek, Filipino, and Vietnamese language options, comparison criteria, a sortable table, four Google search-query examples, and source links. All CSS and JavaScript are embedded in `index.html`; no external API is required.

## Comparison year and data quality
The requested base year is **2025**. The sources checked for this update did not establish a consistently verified set of 2025 year-end franchise-location counts for all three brands. Therefore, the 2025 table marks all three values **Unverified** rather than relabeling 2024 data as 2025. Sorting is intentionally disabled unless all rows contain comparable numeric values.

A news report dated 16 April 2026 says the figures 2,316 (BBQ), 2,228 (bhc), and 1,361 (Kyochon Chicken) are based on 2024 data, so they should not be presented as 2025 counts: [Money Today report](https://www.mt.co.kr/amp/living/2026/04/16/2026041519583922958).

## Tools used
- ChatGPT for drafting and organizing the comparison page
- HTML, CSS, and JavaScript
- Google search query operators for research practice
- Korea Fair Trade Commission (KFTC) source pages

## Research sources
1. [KFTC franchise disclosure comparison portal](https://franchise.ftc.go.kr/firHope/comparePopup.do)
2. [KFTC franchise business statistics announcement](https://www.ftc.go.kr/www/selectBbsNttView.do?bordCd=3&key=12&nttSn=45987&pageIndex=1&pageUnit=10&rltnNttSn=43749&searchCnd=all&searchCtgry=01%2C02&searchViolt=13)
3. [Franchise statistics summary PDF hosted by a university](https://ipsi.u1.ac.kr/u1job/community/notice.do?articleNo=76294&attachNo=51263&mode=download)
4. [KFTC public information and franchise-related statistics](https://www.ftc.go.kr/www/contents.do?key=267)
5. [Money Today report clarifying the available comparison figures are 2024-based](https://www.mt.co.kr/amp/living/2026/04/16/2026041519583922958)

## Three details to personally verify or modify before submission
1. Open the KFTC disclosure comparison portal and confirm the 2025 year-end franchise count for each brand; update the table only when all three counts use the same definition and base year.
2. Record both the publication date of each source and the base year covered by its figures.
3. Test the language selector, sort buttons, reset control, and source links in a desktop browser and on a smartphone. The sort buttons should not reorder rows while values are unverified.

## How to run
Open `index.html` in a browser. No build step or external API is needed.
