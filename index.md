---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
header:
  image: assets/images/brain_wires.png

summary:
  - image_path: /assets/images/fig1.svg
    title: "Mission Statement"
    excerpt: "NMIND is a collaborative dedicated to responding to the growing frustration about redundancies in effort and reproducibility in neuroimaging. NMIND seeks to build a community which advances the development of standards in software development, nomenclature, and testing, to ultimately harmonize advancements in neuroscience."
    url: "https://docs.google.com/document/d/19RqNJoLbA_NqsP3Wb5wKsQ697FJ7Z5jH/edit?usp=sharing&ouid=103813228521985061352&rtpof=true&sd=true"
    btn_label: "&#187; Read our whitepaper"

pillars:
  - image_path: /assets/images/align.png
    excerpt: "Grassroots standards for data analysis. Explore where the community is headed and share your perspective!"
    url: "/alignment"
    btn_label: "&#187; Give Input"
  - image_path: /assets/images/certify.png
    excerpt: "Accessible and automated tool evaluation at your finger tips. Learn about the standards and how to register your tool!"
    url: "/certification"
    btn_label: "&#187; Get Certified"
  - image_path: /assets/images/engage.png
    excerpt: "NMIND relies upon the participation and contribution of community members. Find out how you can join in!"
    url: "/engagement"
    btn_label: "&#187; Get Involved"

---

{% include feature_row id="summary" type="left" %}

{% include feature_row id="pillars" %}

