# Ziyu Peng — Academic Homepage

Personal academic homepage of **Ziyu Peng**, an undergraduate student in Statistics and Data Science at the **University of Colorado Boulder**, previously at Xi'an Jiaotong-Liverpool University.

[Homepage](https://pzy54154631-hub.github.io/homepage/) · [Honors & recognition](https://pzy54154631-hub.github.io/homepage/#honors) · [Curriculum vitae](https://pzy54154631-hub.github.io/homepage/cv.html) · [中文说明](README.zh-CN.md)

## Research and selected work

My interests include statistical learning, model evaluation, and reliable AI systems. The homepage presents work on:

- Equity return prediction and low-turnover stock selection.
- Ambiguity-aware visual question answering.
- Precision-weighted object-file predictive coding for abstract visual reasoning.
- Corridor Wealth, an auditable AI wealth-advisory prototype.

See the [selected work section](https://pzy54154631-hub.github.io/homepage/#work) for project descriptions and available code.

I am seeking undergraduate research opportunities under faculty supervision.

## Honors & recognition

Competition status as of October 2026:

| Recognition | Details |
| --- | --- |
| 2026 Shenzhen International FinTech Competition (FinTechathon) | **Data Analytics Track: Top 25 (top 10%), semifinal in progress.** Separately participating in the **International AI Track**. |
| CU Boulder Transfer Excellence Scholarship | 2026 · $12,000 total |
| XJTLU Academic Scholarship | 2026/27 |
| Third Prize, XJTLU Biostatistics Competition | 2026 |

The Top 25 / top 10% result belongs to the **Data Analytics Track**. The **International AI Track** entry is listed as participation. These details are also in [the homepage source](index.html) and [the CV source](cv.html).

## Source and deployment

This repository contains the source for [pzy54154631-hub.github.io/homepage](https://pzy54154631-hub.github.io/homepage/).

- **Deployment source:** `main` branch, `/ (root)`, using GitHub Pages' **Deploy from a branch** setting.
- **Homepage:** [`index.html`](index.html), including the `#honors` section.
- **Current CV:** [`cv.html`](cv.html), with a browser Print / Save as PDF button.
- **Repository overview:** `README.md` and `README.zh-CN.md`, displayed on GitHub.

Changes to the website must be committed and pushed to `main`. GitHub Pages then builds and publishes that commit; progress is available in [Actions](https://github.com/pzy54154631-hub/homepage/actions). To verify a release, check that the successful Pages run references the intended commit, then inspect the live page.

The site uses static HTML with styles embedded in `index.html` and `cv.html`; no application build step or package installation is needed.

## Files

```text
.
├── index.html          # Homepage, selected work, education, and honors
├── cv.html             # Current printable CV
├── README.md           # English repository overview
├── README.zh-CN.md      # Chinese repository overview
├── LICENSE.md
└── assets/
    ├── img/            # Profile photo, favicon, and other images
    ├── cv/             # Earlier PDF and TeX CV assets
    ├── css/            # Retained template styles
    └── js/             # Retained template scripts
```

When updating recognition details, keep `index.html`, `cv.html`, and both README files consistent.

## Attribution and license

Originally based on [Luka Homepage Template](https://github.com/wzsyyh/luka-homepage-template) by Yuheng Yang, subsequently customized for Ziyu Peng. See [LICENSE.md](LICENSE.md) for the existing MIT license and copyright notice.
