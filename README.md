# Ferjo website

This independent repository contains the static GitHub Pages website for Ferjo, an iOS ferry timetable app for supported routes in Vestland and Rogaland. It contains no iOS application code and has no build-time dependency on the app repository.

- `index.md`: introduction in English and Norwegian Nynorsk.
- `privacy.md`: both privacy-policy drafts, adapted from the existing Ferjo compliance drafts, plus the GitHub Pages hosting disclosure.
- `support.md`: reporting guidance in both languages.
- `_layouts/default.html`: a small shared layout using system fonts and inline CSS. No JavaScript, external assets, analytics, tracking, cookies or added packages.

## Publication is blocked

The working content is not a final privacy policy. Do not commit/push the unfinished contact notices to the publishing branch. Supply and review:

- Developer/controller’s legal name and privacy contact.
- Real support email address and support-message retention policy.
- Privacy-policy effective date and applicable legal bases.
- Provider processing/retention details as needed for the final legal review. GitHub Pages logs visitor IP addresses for security; do not describe the website as collecting no data.

Replace the explicit draft and missing-contact notices in both languages only after these details are available. No invented address or nonworking mail link is included.

## GitHub Pages

Use the repository’s existing Pages publishing configuration. The Markdown files have YAML front matter and use the built-in Jekyll/Kramdown renderer and the local layout. No dependency installation or custom workflow is required for standard branch-based Pages publishing. If Pages uses a custom workflow, confirm that it runs Jekyll rather than copying Markdown unchanged.

Expected URLs, subject to the actual Pages configuration:

- https://fjusq.github.io/Ferjo-site/
- https://fjusq.github.io/Ferjo-site/privacy.html
- https://fjusq.github.io/Ferjo-site/support.html

Relative `.html` links work under the project-site path and a custom domain. Each content page has `#english` and `#nynorsk` language anchors. Language sections carry `lang` attributes for assistive technology.

Before publication, preview the rendered pages, follow navigation and language links, check external provider links, and review both languages. After an authorised deployment, verify all three live URLs and confirm the intended revision is served. Check that no unwanted theme scripts, cookies or analytics are introduced by deployment configuration. Publishing a policy does not configure the iOS app’s links or App Store Connect metadata.

Provider references are linked in `privacy.md`. The app data-handling text was sourced from `PrivacyPolicy-en.html` and `PrivacyPolicy-nn.html` during the compliance task; copies or access to those files are not needed to build this website.
