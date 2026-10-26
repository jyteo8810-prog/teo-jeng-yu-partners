# TEO JENG YU & PARTNERS — Website V3

Static website ready for GitHub + Cloudflare Pages.

## Deploy
1. Upload this folder to a GitHub repository.
2. In Cloudflare Pages, connect the repository.
3. Framework preset: None / Static HTML.
4. Build command: leave blank.
5. Output directory: `/`.
6. Deploy.

## Before publishing
Replace/confirm the firm's address, lawyer biographies, logo, telephone, email and any case/experience descriptions. Review all publicity and article content against the current Legal Profession (Publicity) Rules 2025 and applicable Bar Council rules. Legal articles are educational material, not legal advice.

## Site structure (v6)
The site now has 28 pages:
- 9 root pages: Home, Firm, Practice, People, Industries, Experience, Insights, FAQ, Contact
- 7 practice-area detail pages in `practice/`, one per practice area, each cross-linked to relevant articles
- 12 articles in `articles/` (6 original + 6 new, covering all 7 practice areas)

Nav, mobile menu (tap "Menu" on small screens) and footer are shared across every page. The People page has one placeholder profile — replace it with a real biography and photo before publishing (see the note on that page).

## Photography (v4)
Four photos were added (hero, "how we work" band, construction/development band, "behind the matters" band) to give the site a more corporate, professional feel. All are sourced from Unsplash and used under the Unsplash License (free for commercial use, no attribution required): https://unsplash.com/license. They're hotlinked to images.unsplash.com, so no image files need to be uploaded to the repo — if you'd rather self-host them, download the files and update the `src` paths.

These are atmospheric/stock images (skyline, office facade, boardroom, construction site) — not photos of the actual firm, office or lawyers. For the strongest impression on corporate and institutional clients, swap them out for real photography of the office, the partners and any signature matters as soon as it's available.

## Practice area photos, full case list, expanded FAQ (v7)
- Each of the 7 practice-area pages now has a themed photo banner (contract signing, construction site, boardroom, financial chart, invoice/calculator, property keys, gavel/law book), taking the same visual cue as the firm profile deck. All photos are from Unsplash, free for commercial use under the Unsplash License, hotlinked (no files to host).
- Selected Experience (`experience.html`) now lists all 12 reported cases from the firm profile, not just 4.
- The FAQ page now has 25 questions grouped into 8 categories (general, and one per practice area) instead of 4.

## Experience page temporarily removed (v8)
The Selected Experience page has been taken down at the client's request, for the time being. All nav/footer links and cross-page CTAs that pointed to it have been removed or rerouted (industries.html now leads straight to insights.html instead). The case list content isn't lost — it was removed from the live site only. If you want it added back later, just ask.
