# website-grid-alpha
For CD-Sprint-4, a conceptual take on an EMBL corporate webpage with a strong grid.

This uses a 12-column grid of up to 72 rem in width. 12 columns are used as this is a very strong web convention, 9 columns is technically easy but would impose a large technical burden on ongoing work and translating existing sites.

## This branch

Use this branch as a minimal boilerplate to create something and have the commits published

## View it

Commits and tags are published to Surge.sh through Travis CI; the pattern:

- Latest commit:
https://boilerplate-branch-website-grid-alpha-embl-design-language.surge.sh/
- Latest tag: https://latest-website-grid-alpha-embl-design-language.surge.sh
- Tags (example shown is for v0.0.7):  https://v0-0-7-tag-website-grid-alpha-EMBL-Design-Language.surge.sh

## Tools

- Show the grid by adding a parent class of `show-grid` to a parent element.

## Technical plumbing

- Content:
  - simple static html
- Styling:
  - uses the draft [EMBL-Design-Language/Framework-for-Websites](https://github.com/EMBL-Design-Language/Framework-for-Websites)
  - sass for styles
  - local overrides `css/app.scss`
- Deployment
  - travis + surge

## Develop with it

- Setup
  - `npm install`
- Layout:
  - edit `index.html`
- Style:
  - edit `css/app.scss`
  - `gulp sass`
- Deploy:
  - commits and tags are automatically deployed:
  - manual: `surge --domain embl-website-grid-alpha.surge.sh .`
