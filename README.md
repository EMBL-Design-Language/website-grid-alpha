# website-grid-alpha
For CD-Sprint-4, a conceptual take on an EMBL corporate webpage with a strong grid.

## View it

Commits and tags are published to Surge.sh through Travis CI; the pattern:
- Latest commit:
https://master-branch-website-grid-alpha-embl-design-language.surge.sh/
- Latest tag: https://latest-website-grid-alpha-embl-design-language.surge.sh
- Tags (example shown is for v0.0.7):  https://v0-0-7-tag-website-grid-alpha-EMBL-Design-Language.surge.sh

## Tools

- Show the grid by adding a parent class of `show-grid`

## Develop with it

- install `npm install`
- develop locally `gulp`
- deploy `surge --domain embl-website-grid-alpha.surge.sh .`

## Technical plumbing

- Content:
  - simple static html
- Styling:
  - uses the draft [EMBL-Design-Language/Framework-for-Websites](https://github.com/EMBL-Design-Language/Framework-for-Websites)
  - local overrides `css/app.css`
- Deployment
  - travis + surge

### Deploying
