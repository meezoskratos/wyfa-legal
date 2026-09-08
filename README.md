# WYFA — public legal and support pages

The privacy policy and support page for the WYFA iOS app, hosted on GitHub Pages
because App Store Connect requires both as reachable URLs: a person deciding
whether to install the app has to be able to read the policy *before* installing
it, and someone who has deleted the app still needs a way to reach us.

This repository is public and deliberately holds nothing else. The app's source
is private.

| Page | URL |
| --- | --- |
| Support | `/` |
| Privacy Policy (English) | `/privacy.html` |
| Privacy Policy (Arabic) | `/privacy-ar.html` |

The English policy governs if the two versions ever differ.

The source of truth for the policy text is `docs/PRIVACY.md` in the app
repository, which derives it from what the database schema actually stores.
**Change it there first**, then update these pages in the same breath — a policy
that has drifted from the schema is worse than no policy.
