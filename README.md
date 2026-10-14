# Article diagrams

Figures for the **Production Systems on Google Cloud** series by
[Abhishek Sharma](https://github.com/abhisheksharma2411) — 85 images across 22
articles, one folder per article.

Every figure is hand-authored SVG rendered to PNG through Chrome at device
scale 2. The SVG sources live with their articles, not here.

## Why this repository exists

Medium cannot fetch a local file path, but it *does* download and rehost an
image referenced by a public URL when the HTML is pasted into its editor. This
repository exists to give those images a public URL for the duration of that
paste.

**It is therefore disposable.** Once Medium has rehosted the images to its own
CDN, the published stories no longer reference this repository and it can be
deleted without affecting them.

That is not true of the code repositories the articles link to
(`gcp-transaction-correctness-lab`, `gcp-failure-driven-operations-lab`,
`gcp-secure-decision-systems-lab`, `gcp-payment-platform-reference`). Those are
hyperlinks in the article text, Medium does not rehost them, and deleting any
of them would break every article in the series.

## Licence

The diagrams are Apache-2.0, the same licence as the code they illustrate.
