---
# An instance of the Experience widget.
# Documentation: https://wowchemy.com/docs/page-builder/
widget: experience

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 40

title: Experience
subtitle:

# Date format for experience
#   Refer to https://wowchemy.com/docs/customization/#date-format
date_format: Jan 2006

# Experiences.
#   Add/remove as many `experience` items below as you like.
#   Required fields are `title`, `company`, and `date_start`.
#   Leave `date_end` empty if it's your current employer.
#   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
experience:
  - title: PhD Student
    company: CEA & Inria
    location: Paris, France
    date_start: '2019-02-12'
    date_end: ''
    description: |2-
        * Analyzed and benchmarked the state-of-the-art in Deep Learning for MRI reconstruction.
        * Designed and implemented new models for MRI reconstruction which allowed to me to secure the [**2nd spot in the fastMRI 2020 reconstruction challenge**](https://fastmri.org/leaderboards/challenge/) organized by Facebook and NYU. This result was featured in 2 articles in the specialized press ([CEA mag'](https://www.cea.fr/presse/Pages/actualites-communiques/sante-sciences-du-vivant/innovations-technologiques-IRM.aspx) and [Contact](https://issuu.com/ska_telescope/docs/contact_7_-_ska_magazine__pages_)).
        * Used the [public HPC Jean Zay](http://www.idris.fr/) for training neural networks in a distributed fashion. Also participated in creating a [user's collaborative documentation](https://jean-zay-doc.readthedocs.io/en/latest/).
        * Was the co-founder of and animated a lecture group focused on Deep Learning for students at Neurospin.
        * Co-supervised 2 interns: Sophie Starck on the topic of GANs for reconstruction, and Kevin Michalewicz on the follow-up of my work on Learnlets.
        * Peer-reviewed submissions for a number of scientific conferences and journals.

  - title: Data Scientist
    company: xbird
    company_url: 'https://xbird.io/'
    # company_logo: org-x
    location: Berlin, Germany
    date_start: '2017-10-10'
    date_end: '2018-12-25'
    description: |2-
          * Built data pipelines for smartphone and wearable data.
          * Modeled, implemented, deployed and maintained ad-hoc machine learning models for human activity detection.
          * Presented research results to technical and non-technical teams.

  - title: Research Intern
    company: BioSerenity
    company_url: 'https://www.bioserenity.com/'
    location: Paris, France
    date_start: '2017-04-01'
    date_end: '2017-08-01'
    description: |2-
          * Benchmarked and implemented deep learning algorithms for epilepsy detection in EEG signals.

  - title: Data engineer and Data science Intern
    company: Celmatix
    company_url: 'https://www.celmatix.com/'
    location: New-York, USA
    date_start: '2016-03-13'
    date_end: '2016-09-01'
    description: |2-
          * Implemented and maintained data pipelines for litterature meta-analysis.
          * Developped a blood hormone level model.

  - title: Data science Intern
    company: Ekimetrics
    company_url: 'https://ekimetrics.com/'
    location: Paris, France
    date_start: '2015-08-24'
    date_end: '2016-02-23'
    description: |2-
          * Developped the full stack for web applications.
          * Performed data analysis on the use of these web applications as well as on social media data.

design:
  columns: '2'
---
