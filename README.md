# FaceRituals by Aamy

Public website for FaceRituals by Aamy, a home permanent makeup (PMU) and skin studio in Huizen, Het Gooi, the Netherlands.

Live site: https://vineethvijay.github.io/facerituals-site/

## How to edit

The site is one file, `index.html`, including its styles and script. Google Fonts is the only external dependency. Edit that file, then push to `main`. GitHub Actions publishes the repository root.

Navigation uses same-page anchors: `#services`, `#results`, `#about`, `#hours`, `#faq`, `#book`, and `#consult`. Those links stay on this page, so they keep working at `/facerituals-site/`. Keep internal links as hashes on this page.

## Placeholders

Treatment prices, the email address, the KvK number, client reviews, and the booking, Instagram, and NL links are placeholders. This repository does not include a street address or a phone number. The studio address is shared after a booking.

## Deploy

Pushes to `main` run `.github/workflows/pages.yml`. In the repository, Settings, Pages, the source must be GitHub Actions.
