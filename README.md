
# :chart_with_upwards_trend: :coffee: Background on [dataviz.cafe](https://dataviz.cafe/) 

<img src="https://res.cloudinary.com/dzu5qhcon/image/upload/f_auto,q_auto:eco/v1567608353/logo/dataviz_cafe_logo_block.png" alt="dataviz.cafe logo" />

```
A free public resource curated by IQT Labs for anyone interested using open-source software for data visualization
```

With over 700 libraries/frameworks catalogued in this latest release, [dataviz.cafe](https://dataviz.cafe/) was built to help creative coders, data scientists, and visualization designers to do their jobs more effectively. Our goal is to help practitioners find high quality, low-cost visualization resources to support a wide variety of use-cases.

From general-purpose frameworks to specialized libraries for visualizing brain structures, satellite orbits, and electrical grids (to name just a few), each tool in the collection is summarized, illustrated with a screenshot, and systematically tagged by data type, programming language, and content domain,  if applicable. We invite you to explore the collection, discover new tools, and help update/maintain listings [via GitHub pull request](https://github.com/dataviz-cafe/contribute/pulls).

## Submitting new entries via PR in YAML

We're always looking to keep the collection current. If you believe a certain open source visualization tool should be included, please check [https://dataviz.cafe](https://dataviz.cafe/) first and then open a pull request to add it to [newentry.yml](new_entry.yml).

```yaml
---
dataviz.cafe tool entry

dataType: 'Network' [pick one of five: 'Geospatial', 'Network', 'Quantitative', 'Text', 'Miscellaneous']
toolName: 'CRviz'
toolURL: 'https://cyberreboot.github.io/CRviz'
toolSourceCodeRepo: 'https://github.com/CyberReboot/CRviz' [or 'None']
toolScreenshot: 'https://cdn-images-1.medium.com/max/2600/1*ayqvpmeOWBBaALqHGMcOCQ.png'
toolDescription: 'CRviz is a browser-based visualization tool that uses JSON and an interactive enclosure diagram to visualize networks, utilizing circle-packing methods to show 10,000+ nodes.' [ideally ±25 words or ±175 chars.]
toolProgrammingLanguage: 'JavaScript' [or 'Python', 'R', etc.]
toolSPDXLicenseTerms: 'Apache-2.0' [or 'MIT', etc.]
toolCost: 'Free' [or 'Paid' or 'Freemium']
---
```
