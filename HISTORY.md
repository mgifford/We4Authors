# We4Authors – History & References

## Volto/Plone accessibility work (ALT text)
- 2020-05-20: Volto issue opened to improve image ALT handling, framed as part of the we4authors cluster: https://github.com/plone/volto/issues/1503
- 2020-09: Discussion noted block-based uploads auto-filled ALT with IDs; manual uploads used the image title; consensus to reuse image ALT as fallback and avoid ID-based ALT text.
- 2021-06: Related discussions in Plone Classic referenced for parity: https://github.com/plone/Products.CMFPlone/issues/2837 and linked issues 2836/2834.
- 2021-10: Proposed UX copy aligned with W3C Image decision tree (decorative images allowed, guidance text added; removal of auto-fill). Reference: https://www.w3.org/WAI/tutorials/images/decision-tree/
- 2021-11-01: Fix merged in Volto PR #2789 resolving the issue: https://github.com/plone/volto/pull/2789

## We4Authors project (Funka)
- Project home: https://www.funka.com/en/projekt/we4authors/ (EU pilot led by Funka on accessibility in authoring tools)
- Main objectives: https://www.funka.com/en/projekt/we4authors/what-is-we4authors/we4authors-main-objectives/
- Main activities and published results: https://www.funka.com/en/projekt/we4authors/we4authors-main-activities-and-results/
- Market analysis and benchmarking of CMS usage in EU public sector: https://www.funka.com/en/projekt/we4authors/we4authors-main-activities-and-results/market-analysis-and-benchmarking-process-of-existing-cms/
- Workshops on accessible CMS with public sector, vendors, standard bodies, and users: https://www.funka.com/en/projekt/we4authors/we4authors-main-activities-and-results/workshops-on-accessible-content-management-systems/
- Accessibility guidelines for CMS community, suppliers, and governments: https://www.funka.com/en/projekt/we4authors/we4authors-main-activities-and-results/accessibility-guidelines-for-the-cms-community-suppliers-and-public-governments/

## GitHub issues mentioning We4Authors (sample)
- Plone Classic: Allow/require ALT text on images (#2837): https://github.com/plone/Products.CMFPlone/issues/2837
- Volto: Improve image ALT handling (we4authors cluster) (#1503): https://github.com/plone/volto/issues/1503
- CKEditor 5: Replace table editor with We4Authors model (#9782): https://github.com/ckeditor/ckeditor5/issues/9782
- CKEditor 5: Implement best practices from A11yFirst (references We4Authors) (#13844): https://github.com/ckeditor/ckeditor5/issues/13844
- CKEditor 5: Table headers UX, alignment with We4Authors table guidance (#5584): https://github.com/ckeditor/ckeditor5/issues/5584
- CKEditor 5: Accessibility checker feature (mentions cluster outcomes) (#1941): https://github.com/ckeditor/ckeditor5/issues/1941
- CKEditor editor-recommendations: Headers in tables (#65): https://github.com/ckeditor/editor-recommendations/issues/65
- Umbraco CMS Accessibility: Testing documents (ATAG feature, We4Authors context) (#79): https://github.com/umbraco/Umbraco-CMS.Accessibility.Issues/issues/79
- Umbraco CMS Accessibility: Video and audio (mentions We4Authors) (#83): https://github.com/umbraco/Umbraco-CMS.Accessibility.Issues/issues/83
- W3C WCAG: Challenges – We Aren't Striking at the Root (references We4Authors cluster) (#1170): https://github.com/w3c/wcag/issues/1170

## Additional context
- WAI guidance on ALT text decision-making: https://www.w3.org/WAI/tutorials/images/decision-tree/
- Accessibility cluster summary cited in the issue: https://accessibilitycluster.com/main-results/text-alternative-feature-%E2%80%93-presentation

## AccessibilityCluster.com status
- Main domain currently serves only a directory index (no content pages available): https://accessibilitycluster.com/
- Consider recovering past content via the Internet Archive or other caches before reproducing it in GitHub.
- Archived copies exist in the Wayback Machine (67 captures between Jul 2020 and Mar 2025). Example snapshot with full homepage text and AXSChat video link: https://web.archive.org/web/20200721005354/https://accessibilitycluster.com/

## Notes
- Key takeaway: avoid auto-filling ALT with filenames/IDs; allow decorative images with empty ALT; prefer editor-provided, context-specific ALT while keeping consistent handling between embedded and uploaded images.
