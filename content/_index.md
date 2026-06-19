---
# Leave the homepage title empty to use the site title
title: ''
summary: ''
date: 2026-06-01
type: landing

sections:
  - block: resume-biography-3
    id: home
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: me
      text: ''
      # Show a call-to-action button under your biography? (optional)
      #button:
      #  text: Download CV
      #  url: uploads/resume.pdf
      headings:
        about: ' $\,$'
        education: ''
        interests: 'Research Interests'
    design:
      background:
        gradient_mesh:
          enable: false

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    id: articles
    content:
      title: Articles
      text: |
        ### Publications

        **[Infinite-Dimensional Generative Diffusions via Doob's h-Transform](https://arxiv.org/abs/2602.06621)**
        Thorben Pieper-Sethmacher, Daniel Paulin. 
        *International Conference on Machine Learning (ICML)*, 2026. 
       

        **[Simulation of infinite-dimensional diffusion bridges](https://arxiv.org/abs/2503.13177)**
        Thorben Pieper-Sethmacher, Frank van der Meulen, Aad van der Vaart. 
        *To appear in Annals of Applied Probability*, 2026. 


        **[On a class of exponential changes of measure for stochastic PDEs](https://www.sciencedirect.com/science/article/pii/S0304414925000717)**
        Thorben Pieper-Sethmacher, Frank van der Meulen, Aad van der Vaart. 
        *Stochastic Processes and their Applications*, 2025. 

        ---
        ### Preprints

        **[Guided filtering and smoothing for infinite-dimensional diffusions](https://arxiv.org/abs/2507.06786)**
        Thorben Pieper-Sethmacher, Daniele Avitabile, Frank van der Meulen.
        *arXiv*, 2025.
    design:
      columns: '1'
  - block: markdown
    id: presentations
    content:
      title: Selected Presentations # **Title of presentation** *occasion, host* (host either the institution, else the place)
      text: |
        **July 2026** | **Infinite-Dimensional Generative Diffusions via Doob's h-Transform** *International Conference on Machine Learning (ICML) 2026, Seoul, South Korea*. Poster Presentation.

        **June 2024** | **Bayesian Inference for Discretely Observed Stochastic Partial Differential Equations** *Stochastic Morphometry Workshop 2024, University of Copenhagen*. Invited Talk.

        **May 2024** | **Simulation of Infinite Dimensional Diffusion Bridges** *SMC 2024 - 6th Workshop on Sequential Monte Carlo Methods,  ICMS Edinburgh*. Poster Presentation.

        **June 2023** | **Bayesian Computation for Discretely Observed Stochastic Partial Differential Equations** *NORDSTAT 2023, Chalmers University of Technology and the University of Gothenburg*. Contributed Talk.

        **March 2023** | **Bayesian Computation for Discretely Observed Stochastic Partial Differential Equations** *DYNSTOCH 2023 - Workshop on Statistical Methods for Dynamical Stochastic Models, Imperical College London*. Contributed Talk.


    design:
      columns: '1'
  - block: markdown
    id: cv
    content:
      title: CV 
      text: |
        **Nov 2025 – Present** | **Postdoctoral Researcher** *Nanyang Technological University, College of Computing and Data Science*. Advisor: A/Prof. Daniel Paulin.

        **Sep 2021 – Sep 2025** | **PhD in Mathematics & Statistics** *Delft University of Technology*. Advisors: Prof. Frank van der Meulen, Prof. Aad van der Vaart.

        **April 2020 – May 2021** | **Guest Researcher** *Centre for Translational Data Science, University of Sydney*. 

        **Aug 2018 – May 2021** | **MSc in Applied Mathematics, cum laude** *Delft University of Technology*. Advisors: Prof. Frank van der Meulen, Prof. Sally Cripps.

        **Oct 2015 – Jul 2018** | **BSc in Mathematics, cum laude** *Westfälische Wilhelms-Universität Münster*. Advisor: Prof. Siegfried Echterhoff.
    design:
      columns: '1'
---
