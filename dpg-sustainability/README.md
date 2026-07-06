<div align="center">

<a href="https://digitalpublicgoods.net/registry"><img src="https://raw.githubusercontent.com/DPGAlliance/dpg-resources/main/docs/assets/dpg-badge/dpg-badge.png" width="100" alt="Digital Public Goods Badge"></a>

# DPG Sustainability Public Support Letter

</div>

---

Given the recent changes to the international funding landscape impacting the DPG ecosystem, the DPGA Secretariat and UNDP have coordinated the drafting of a public group letter signed by [DPG product owners](https://www.digitalpublicgoods.net/registry), highlighting and reiterating the value of investing in the maintenance and support of digital public goods. This letter represents a shared language that DPG product owners will use as part of their advocacy efforts to reach funders and other relevant stakeholders, helping to underscore the global value of continuing to invest in DPGs. **If you would like to support DPGs, here are three (3) ways you can**:

1. Share the letter ([English](https://dpgalliance.github.io/dpg-public-letters/dpg-sustainability/en/) · [Português](https://dpgalliance.github.io/dpg-public-letters/dpg-sustainability/pt/)) with your network and across your organisation.
2. Endorse this letter with your name and organisation affiliation by following the [instructions below](#how-to-endorse).
3. If you fall into any of the groups below, kindly consider our request and circulate it across your organisation:

| Target Audience | Summary of Ask |
| - | - |
| Donors and Funders | Support countries by supporting the DPGs they rely on. Supporting the ongoing maintenance costs of DPG core functionalities, in addition to country implementations, helps ensure the long-term efficacy of your investments. Funding that goes beyond initial product development is essential for ongoing maintenance, security updates, and scalability, which in turn creates opportunities for non-traditional sustainability models and reduces dependencies on donor funding over time. Investing in the maintenance of our solutions is insurance for digital resilience, innovation, and equity across the globe. |
| Countries, Agencies, and Organisations | Look before you build or buy. DPGs provide you the ability to choose cost-effective, tailored solutions for your specific needs and contexts while maintaining ownership of your core infrastructure. We ask you to develop open-source-first policies and review your procurement processes and policies to help ensure our solutions are considered in procurement processes. |
| System Integrators and Hyperscalers | DPGs are reliable, open-source building blocks that enable rapid development and deployment. At the same time, they foster collaboration and shared innovation, saving time and resources. We encourage you to consider contributing a percentage of your gross profits back to the DPGs you assist your clients in implementing in order to assist with our own sustainability. |
| Advocates | The loss of DPGs would potentially disproportionately impact vulnerable populations, exacerbating existing inequalities. We ask you to continue to advocate for DPGs in your interactions with decision makers and relevant stakeholders. |


## How to Endorse

1. Edit the [/_data/dpg-sustainability/signatures.yml](https://github.com/DPGAlliance/dpg-public-letters/edit/main/_data/dpg-sustainability/signatures.yml) file.
2. Add your entry to the appropriate list:
    - **`dpg_sustainability.sincerely`** — if your product is listed in the [DPG registry](https://www.digitalpublicgoods.net/registry).
    - **`dpg_sustainability.supported_by`** — for all other endorsers and supporters.

    Use the exact indentation and YAML structure.

    **Example for `supported_by`:**

    ```yaml
    - name: Your Name
      role: Your Title
      organization:
        name: Your Organisation Name
        url: https://example.org # optional, can be left blank
    ```

    **Example for `sincerely` (DPG product owners):**

    ```yaml
    - name: Your Name
      role: Your Title
      organization:
        name: Your Organisation Name
        url: https://example.org # optional
      products: # optional
        - name: Product A
          url: https://www.digitalpublicgoods.net/r/product-a
        - name: Product B
          url: https://www.digitalpublicgoods.net/r/product-b
    ```
3. Submit your changes through a new pull request.
4. Someone will review your changes, make any necessary edits, and merge them.
5. Your name will be reflected on the letter in a few minutes!
