---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
header:
  image: assets/images/brain_wires.png

summary_row:
  - image_path: /assets/images/fig1.svg
    title: "Mission Statement"
    excerpt: "NMIND is a grassroots collaborative dedicated to responding to the growing frustration about redundancies in effort and reproducibility in neuroimaging. NMIND seeks to build a community which advances the development of standards in software development, nomenclature, and testing, to ultimately harmonize advancements in neuroscience."
    url: "https://docs.google.com/document/d/19RqNJoLbA_NqsP3Wb5wKsQ697FJ7Z5jH/edit?usp=sharing&ouid=103813228521985061352&rtpof=true&sd=true"
    btn_label: "Read our whitepaper"

guiding_principals_row:
  - image_path: /assets/images/alignment.png
    title: "Align"
    excerpt: "Everything from the menus, sidebars, comments, and more can be configured or set with YAML Front Matter."
    url: "/docs/configuration/"
    btn_label: "Learn More"
  - image_path: /assets/images/badge.png
    alt: "fully responsive"
    title: "Certify"
    excerpt: "Built on HTML5 + CSS3. All layouts are fully responsive with helpers to augment your content."
    url: "/docs/layouts/"
    btn_label: "Learn More"
  - image_path: /assets/images/community.png
    title: "Engage"
    excerpt: "NMIND relies upon the participation and contribution of community members. Find out how you can join in!"
    url: "/engagement"
    btn_label: "Get Involved"

guiding_principals:
  - excerpt: "### 1. Alignment

Development and adoption of standards for critical components of data analysis pipelines. These include, but are not limited to:

- **Coding** standards to promote the adoption of industry standards in academic software, and facilitate code review, collaboration and reuse.

- **Testing** standards to promote reproducibility and efficiency across differing computational environments and use cases.

- **Data performance** standards to promote reproducibility and efficiency of performance across diverse benchmark datasets (e.g. data quality, developmental status, species, clinical populations).

- **Terminology** standards to promote reliable and efficient communication across data analysts and packages."
  - excerpt: "### 2. Certification

Accessible and automated mechanisms for certifying the compliance of tools with the NMIND standards. Tool contributors will be able to interact with these mechanisms through a web-based public interface and programmatic toolkits, each facilitating the logging, debugging, and communication of their status."

---

{% include feature_row id="summary_row" type="left" %}

{% include feature_row id="guiding_principals_row" %}

{% include feature_row id="guiding_principals" %}

{% include feature_row id="get_involved" %}
