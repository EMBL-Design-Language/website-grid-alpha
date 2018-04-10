# website-grid-alpha
For CD-Sprint-4, a conceptual take on an EMBL corporate webpage with a strong grid.

## View it
- https://embl-website-grid-alpha.surge.sh + [Add URL patterns here]
- https://embl-website-grid-alpha.surge.sh
- https://embl-website-grid-alpha.surge.sh/grid.html

## Technical plumbing

- Content:
  - simple static html
- Styling:
  - uses the draft [EMBL-Design-Language/Framework-for-Websites](https://github.com/EMBL-Design-Language/Framework-for-Websites)
  - local overrides `css/app.css`
- Deployment
  - travis + surge

### Deploying
`surge --domain embl-website-grid-alpha.surge.sh .`
