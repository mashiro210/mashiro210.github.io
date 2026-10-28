---
title: ''
date: 2026-10-28
type: landing

design:
  spacing: '5rem'

sections:
  - block: resume-biography-3
    id: about
    content:
      username: admin
      text: ''
      headings:
        about: About
        education: Education
        interests: Research interests
    design:
      css_class: hbx-bg-gradient mashiro-hero
      avatar:
        size: large
        shape: rounded

  - block: markdown
    id: research
    content:
      title: Research
      subtitle: Turning field observations into decisions
      text: |-
        I develop field-phenomics workflows that connect **UAV and ground-based sensing**, **computer vision**, and **crop growth models**. My goal is to transform complex field data into useful evidence for plant breeding and more sustainable crop management.

        ### From images to phenotypes

        I build reproducible pipelines for extracting biomass, canopy structure, and other crop traits from RGB, multispectral, and 3D observations.

        ### From phenotypes to mechanisms

        I combine quantitative genetics and statistical modeling to understand how crop traits vary across genotypes, environments, and time.

        ### From models to management

        My current work explores crop and forest digital twins, field light environments, and the integration of phenotyping with agricultural robotics and AI systems.
    design:
      columns: '1'
      css_class: research-overview

  - block: collection
    id: publications
    content:
      title: Selected Publications
      subtitle: Peer-reviewed research in plant phenomics and data-driven biology
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation

  - block: markdown
    id: updates
    content:
      title: Latest Updates
      subtitle: Recent and upcoming research activities
      text: |-
        ### Upcoming · November 2026

        P. Sanghera, **M. Okada**, J. Burridge, S. Kimura, H. Iwata, and W. Guo. _Plant Detection and Position Assignment in Mixed-Genotype Soybean Stands._ Oral presentation at the 16th International Conference of Asia-Pacific Federation for Information Technology in Agriculture (APFITA 2026), Taipei, Taiwan.

        C. C. Chiang, Y. Imachi, **M. Okada**, S. Kamikawa, K. Tanaka, M. Miyauchi, K. Miyamoto, H. Iwata, J. Burridge, and W. Guo. _Potato Stem Counting from UAV and Ground-Level Images and Its Relationship with Tuber-Size Distribution._ Oral presentation at the 16th International Conference of Asia-Pacific Federation for Information Technology in Agriculture (APFITA 2026), Taipei, Taiwan.

        ### September 2026

        Presented _UAV Field Phenotyping Protocol: Toward Next-Generation Phenotyping from Field Mapping to Adaptive Observation_ at the 150th Meeting of the Japanese Society of Breeding in Fukui.

        ### August 2026

        Co-instructor for a technical training session on AI tools and techniques for developing a database of medicinal plants with antimicrobial activity, organized by HEPHN.

        ### June 2026

        Presented research on high-resolution sub-canopy PAR estimation at the CIGR-EurAgEng World Congress in Turin and chaired the session **AI-Driven Crop Phenotyping & Digital Twins**.

        [View all updates →](/updates/) · [See all conference presentations →](/presentations/)
    design:
      columns: '1'
      css_class: latest-updates

  - block: resume-experience
    id: experience
    content:
      title: Professional Experience
      username: admin
    design:
      date_format: 'Jan 2006'
      is_education_first: false

  - block: resume-awards
    id: awards
    content:
      title: Awards & Scholarships
      username: admin

  - block: markdown
    id: contact
    content:
      title: Let’s work together
      subtitle: Collaboration, research, and applied field-phenomics projects
      text: |-
        I welcome conversations about crop phenotyping, UAV remote sensing, computer vision, growth modeling, and their use in breeding or farm management.

        [Download CV (PDF)](/files/mashiro_okada_academic_cv.pdf) · [Email me](mailto:mashiro@fieldphenomics.com) · [GitHub](https://github.com/mashiro210) · [Google Scholar](https://scholar.google.com/citations?user=7yW6TG8AAAAJ) · [ORCID](https://orcid.org/0000-0002-4286-9076)
    design:
      columns: '1'
      css_class: contact-panel
---
