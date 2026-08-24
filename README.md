<div align="center">

<a href="https://digitalpublicgoods.net/registry"><img src="https://raw.githubusercontent.com/DPGAlliance/dpg-resources/main/docs/assets/dpg-badge/dpg-badge.png" width="100" alt="Digital Public Goods Badge"></a>

This repository hosts public letters and concept notes written by product owners of [digital public goods](https://digitalpublicgoods.net/registry).

</div>

---

## Current Letters

| Name | Source |
| ---- | ------ |
| [DPG Sustainability Public Support Letter](https://dpgalliance.github.io/dpg-public-letters/dpg-sustainability/) | [/dpg-sustainability](/dpg-sustainability/) |
| [Best Practices for Preventing AI Exploitation of Open Content and Open Data DPGs](https://dpgalliance.github.io/dpg-public-letters/dpg-open-content-data/) | [/dpg-open-content-data](/dpg-open-content-data/) |

## Contributing Guide

1. Find the folder of the repo you want to translate (the folders are usually prefixed with `dpg-` as seen in the table above). The English version will be an `en.md` file.
2. In the folder, create a new Markdown file with the ISO language code (e.g., `es.md` for Spanish and `fr.md` for French).
3. Include the starting YAML frontmatter and Liquid shared variables as seen below, and update the title and permalink to match


```
---
layout: default
title: Carta Pública de Apoio à Sustentabilidade dos DPGs
permalink: /dpg-sustainability/pt/
---

# {{ page.title }}

---
```

4. Now you can translate every other section of the main body text following the same format as the `en.md` version.
5. Next, update the `index.md` file in the letter folder to link the new translation page in the live deployment like so:

```
---
layout: default
title: DPG Sustainability Public Support Letter
permalink: /dpg-sustainability/
---

# {{ page.title }}

Choose your language:

- [English](en/)
- [Português](pt/)
- [Insert New Language](nl/)
```

6. The references section will always be in `_includes/references` and imported into the document as seen below (there's no need to update this; it will remain in English).

```
{% include references/dpg-sustainability/references.md %}
```

7. Submit a new pull request with your changes, and someone will review and provide feedback. Thank you!
