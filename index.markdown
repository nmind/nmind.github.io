---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: splash
header:
  overlay_color: "#5e616c"
excerpt: >
  NMIND is a collaborative dedicated to accelerating scientific discovery in neuroimaging research that was formed in 2020 as a grassroots initiative - responding to the growing frustration about redundancies in effort, continuing questions about the reproducibility of code by independent teams, and challenges arising in the sharing of code between teams due to lack of consistent nomenclature and conventions.
guiding_principals_header:
  - excerpt: "## Guiding Principles

The NMIND solution has three guiding principles: Alignment, Certification, & Engagement."
guiding_principals:
  - excerpt: "### 1. Alignment

Development and adoption of standards for critical components of data analysis pipelines. These include, but are not limited to:

- **Coding** standards to promote the adoption of industry standards in academic software, and facilitate code review, collaboration and reuse.

- **Testing** standards to promote reproducibility and efficiency across differing computational environments and use cases.

- **Data performance** standards to promote reproducibility and efficiency of performance across diverse benchmark datasets (e.g. data quality, developmental status, species, clinical populations).

- **Terminology** standards to promote reliable and efficient communication across data analysts and packages."
  - excerpt: "### 2. Certification

Accessible and automated mechanisms for certifying the compliance of tools with the NMIND standards. Tool contributors will be able to interact with these mechanisms through a web-based public interface and programmatic toolkits, each facilitating the logging, debugging, and communication of their status."
  - excerpt: "### 3. Engagement

The widespread promotion and adoption of the NMIND collaborative standards and certification in the field, through the efforts of field influencers, educators and resource generators.  The end goal of NMIND is software engineering standards and a common code base that will unite the field, reduce redundant effort, and accelerate progress."
get_involved:
  - excerpt: "## Community

Join us in [Gather.town](https://www.google.com/url?q=https://gather.town/app/ESJPNXX7CVirKett/nmind) [the first Thursday of every month](/assets/calendar/NMIND monthly meeting.ics)."
  - excerpt: "## Coding projects

NMIND has the following GitHub projects

* [nmind.github.io](https://github.com/nmind/nmind.github.io) - The backing project for this website

* [coding-standards-certification](https://github.com/nmind/coding-standards-certification)

* [hackathon2021](https://github.com/nmind/hackathon2021) - Issues and notes for the May 2021 NMinD hackathon

* [nmind-coding-standards-action](https://github.com/nmind/nmind-coding-standards-action)
"
---
{% include feature_row id="guiding_principals_header" type="full-width" %}

{% include feature_row id="guiding_principals" %}

{% include feature_row id="get_involved" %}