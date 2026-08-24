---
title: ''
date: 2026-08-24
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
    id: activities
    content:
      title: Recent Academic Activities
      subtitle: Presentations, service, and international exchange
      text: |-
        ### Upcoming · Sep 2026

        _UAV Field Phenotyping Protocol: Toward Next-Generation Phenotyping from Field Mapping to Adaptive Observation_ — Japanese Society of Breeding, 150th Meeting.

        ### Jun 2026

        _High Resolution Estimation of Sub-Canopy PAR for Low-Input Weed Management in Soybean_ — CIGR–EurAgEng World Congress, Turin. Session Chair for **AI-Driven Crop Phenotyping & Digital Twins**.

        ### Sep 2025

        _Spatio-Temporal Simulation of Canopy Light Environments in Soybean Fields Using UAV Remote Sensing and Ray Tracing_ — PhenomUK 3rd Annual Conference.

        ### Oct 2024

        _Construction of a soybean growth model to achieve efficient weed control_ — International Plant Phenotyping Symposium 8. Selected as a top-five poster in the AI, Models, and Algorithms for Phenomics session.

        ### Academic service

        Reviewer for _Breeding Science_, _The Plant Phenome Journal_, and _Plant Phenomics_.
    design:
      columns: '1'
      css_class: academic-activities

  - block: resume-experience
    id: experience
    content:
      title: Experience
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

        [Download CV (PDF)](/files/Mashiro_Okada_Academic_CV.pdf) · [Email me](mailto:mashiro@fieldphenomics.com) · [GitHub](https://github.com/mashiro210) · [Google Scholar](https://scholar.google.com/citations?user=7yW6TG8AAAAJ) · [ORCID](https://orcid.org/0000-0002-4286-9076)
    design:
      columns: '1'
      css_class: contact-panel
---
