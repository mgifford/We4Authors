# We4Authors – History & References

Publicly available references on **We4Authors** (“Pilot on web accessibility for web authoring tools producers and communities”), related follow-on projects, and downstream adoption notes.

## 2018–2019: We4Authors pilot (Funka)

- Scope: European pilot to make accessibility features the default option in authoring tools, spanning licensed and open-source CMSs used by public-sector bodies.
- Duration & budget: May 2018–November 2019; €150,000. Partners named: Funka (leader), CTIC-W3C Spain (partner), with liaisons to EDF, ANEC, ERRIN.
- References:
	- What is We4Authors (budget, dates): https://www.funka.com/en/projekt/we4authors/what-is-we4authors/
	- Main objectives: https://www.funka.com/en/projekt/we4authors/what-is-we4authors/we4authors-main-objectives/
	- Partnership: https://www.funka.com/en/projekt/we4authors/what-is-we4authors/the-we4authors-partnership/

### October 2019: stakeholder workshops (Brussels)

- Three workshops for end users, web authors, and industry, run with EDF, ANEC, ERRIN.
- References: 
	- Workshops overview: https://www.funka.com/en/projekt/we4authors/we4authors-main-activities-and-results/workshops-on-accessible-content-management-systems/
	- Workshop presentations/outcomes: https://www.funka.com/en/projekt/we4authors/we4authors-main-activities-and-results/workshops-on-accessible-content-management-systems/workshops/

## 2019–2020: published outputs

### Market analysis and benchmarking
- Landing page with methodology, PDFs, and dataset: https://www.funka.com/en/projekt/we4authors/we4authors-main-activities-and-results/market-analysis-and-benchmarking-process-of-existing-cms/
- Methodology (PDF): https://www.funka.com/contentassets/5d9a29d756c9483998b00dc2e612510a/methodology_for_market_analysis.pdf
- “Most spread authoring tools in public sector in EU” (PDF): https://www.funka.com/contentassets/5d9a29d756c9483998b00dc2e612510a/most_spread_authoring_tools_in_public_sector_in_eu.pdf

### Collaboration with authoring tool producers
- Prototypes and bilateral discussions; results fed into FEAT and Cluster: https://www.funka.com/en/projekt/we4authors/we4authors-main-activities-and-results/collaboration-with-tool-producers-elaboration-of-prototypes-and-testing/

### Accessibility guidelines (three audiences)
- Landing: https://www.funka.com/en/projekt/we4authors/we4authors-main-activities-and-results/accessibility-guidelines-for-the-cms-community-suppliers-and-public-governments/
- Funka-hosted PDF: Public sector authorities: https://www.funka.com/contentassets/c43f6521e7354c9a8f82e62402f10aad/guidelines_for_public_sector_authorities.pdf
- EC “newsroom” mirrors:
	- Public sector authorities: https://ec.europa.eu/information_society/newsroom/image/document/2020-49/we4author_guidelines_for_public_sector_authorities_F8492051-BFDD-6B4C-96985A0D3CABAA1D_71395.pdf
	- Authoring tools producers: https://ec.europa.eu/information_society/newsroom/image/document/2020-49/we4author_guidelines_for_authoring_tools_producers_F8459C35-D2B3-3F2A-0596D6A1A3BA459E_71393.pdf
	- ICT suppliers: https://ec.europa.eu/information_society/newsroom/image/document/2020-49/we4author_guidelines_for_ict_suppliers_F847638D-0BB4-FB50-34E0ED25020E5481_71394.pdf

### April 2, 2020: third-party announcement
- ERRIN news item on published market analysis and guidelines: https://errin.eu/news/we4authours-publish-results-market-analysis-stakeholder-workshops

## 2020–2021: follow-on projects referencing We4Authors

### FEAT (Features for accessibility through templates)
- Period: March 2020–July 2021; funded by the European Parliament; Episerver used as model CMS; reusable templates for built-in accessibility.
- Reference: https://www.funka.com/en/research-and-innovation/archive-research-projects/built-in-accessibility-offers-support-to-web-authors/

### We4Authors Cluster (cross-CMS prototypes)
- Ten accessibility-by-default features prototyped and user-tested. User tests ran December 2020–31 January 2021.
- Reference (user testing site): https://www.funka.com/en/projekt/cluster-feature-testing/
- DrupalCon Europe 2020 session (10 Dec 2020) describing collaboration across Drupal, Plone, SiteVision, TinyMCE: https://events.drupal.org/europe2020/sessions/top-cms-tools-are-working-together-build-more-inclusive-world.html

### Procurement-focused summary (Futurium, 23 Aug 2021)
- FEAT and Cluster framed as parallel EU-funded projects; stresses procurement as lever for adoption; tools cited include Drupal, Joomla, Umbraco, Plone, SiteVision, TinyMCE.
- Reference: https://futurium.ec.europa.eu/en/digital-compass/digital-public-services/best-practice/eu-funded-projects-feat-and-cluster-push-better-procurement-achieve-accessibility-web-authoring

## Media, mirrors, and archived copies

- EC Web Accessibility Expert Group page listing We4Authors outputs: https://digital-strategy.ec.europa.eu/en/library/seventh-meeting-web-accessibility-expert-group
- Repo mirrors:
	- Funka subtree captured 2026-01-20: [archive/funka.com_20260120/README.md](archive/funka.com_20260120/README.md)
	- accessibilitycluster.com Gatsby export 2022-06-01: [archive/accessibilitycluster.com_20220601](archive/accessibilitycluster.com_20220601)
	- accessibilitycluster.com snapshot 2024-03-03 (with technical specification PDFs linked locally): [archive/accessibilitycluster.com_20240303](archive/accessibilitycluster.com_20240303)

### Archived “main results” summaries (local mirrors)

- 2022-06-01 export (Gatsby): preserved main-results pages (user needs, selection of features, user testing, demonstration event) and imagery; used as baseline transcription for Jekyll pages.
- 2024-03-03 snapshot: adds the ten feature presentation pages with embedded video placeholders and outbound Dropbox links to technical specs; PDFs are mirrored locally under /archive and linked from the Jekyll feature pages.

## Developer adoption and issue references (sample)

- Plone Classic: ALT-text handling (#2837): https://github.com/plone/Products.CMFPlone/issues/2837
- Volto: Improve image ALT handling (#1503): https://github.com/plone/volto/issues/1503
- CKEditor 5: Replace table editor with We4Authors model (#9782): https://github.com/ckeditor/ckeditor5/issues/9782
- CKEditor 5: Implement A11yFirst practices (references We4Authors) (#13844): https://github.com/ckeditor/ckeditor5/issues/13844
- CKEditor 5: Table headers UX aligned with We4Authors guidance (#5584): https://github.com/ckeditor/ckeditor5/issues/5584
- CKEditor 5: Accessibility checker feature mentions Cluster (#1941): https://github.com/ckeditor/ckeditor5/issues/1941
- CKEditor editor-recommendations: Headers in tables (#65): https://github.com/ckeditor/editor-recommendations/issues/65
- Umbraco CMS Accessibility: Testing documents (#79): https://github.com/umbraco/Umbraco-CMS.Accessibility.Issues/issues/79
- Umbraco CMS Accessibility: Video and audio (#83): https://github.com/umbraco/Umbraco-CMS.Accessibility.Issues/issues/83
- W3C WCAG: Challenges – We Aren't Striking at the Root (cites Cluster) (#1170): https://github.com/w3c/wcag/issues/1170

## Alt-text implementation notes (Volto/Plone)

- 2020-05-20: Volto issue opened to improve image ALT handling, framed in We4Authors context: https://github.com/plone/volto/issues/1503
- 2020-09: Block uploads auto-filled ALT with IDs; manual uploads used image title. Consensus: reuse existing image ALT as fallback; avoid ID-based ALT.
- 2021-06: Related Plone Classic issues for parity: https://github.com/plone/Products.CMFPlone/issues/2837 (and linked 2836/2834).
- 2021-10: Proposed UX copy aligned with W3C image decision tree (allow decorative images; add guidance; remove auto-fill). Guidance: https://www.w3.org/WAI/tutorials/images/decision-tree/
- 2021-11-01: Fix merged in Volto PR #2789: https://github.com/plone/volto/pull/2789

## AccessibilityCluster.com status

- Live domain currently shows a directory index only: https://accessibilitycluster.com/
- Wayback captures span July 2020–March 2025 (example homepage with AXSChat link: https://web.archive.org/web/20200721005354/https://accessibilitycluster.com/).

## Notes and limitations

- Cluster “main results” pages cited in some GitHub issues were transient; the repo mirrors (2022 and 2024 snapshots) hold the most complete publicly accessible copies now.
- Key takeaway for authoring tools: avoid auto-filling ALT with filenames/IDs; allow empty ALT for decorative images; prefer author-provided, context-specific ALT; keep consistent handling across uploads and embeds.
