---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  - block: about.biography
    id: about
    content:
      title: 
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
  - block: collection
    id: publications
    content:
      title: Selected Publications
      count: 6
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: markdown
    id: research
    content:
      title: Research
      subtitle: ''
      text: |-
        My research is organised around four connected agendas:

        1. **Social movements and political parties** — mobilisation, party–movement relations, and backstage politics.
        2. **Housing and political participation** — urban movements, contention, and democratic engagement.
        3. **Environmental and climate activism** — the emergence, diffusion, and organisation of climate mobilisation.
        4. **Protest and engagement event analysis** — methods for studying public protest and less visible forms of collective action.
    design:
      columns: '2'
  - block: markdown
    id: projects
    content:
      title: Current Projects
      subtitle: ''
      text: |-
        - **Party in the Movement** (2022–2028) — research on party–movement relations and the role of political parties in contentious politics.
        - **e-Health: Supporting Esports Players Towards an Active and Healthy Lifestyle** (2024–2026) — Erasmus+ collaborative project.
    design:
      columns: '2'
  - block: markdown
    id: service
    content:
      title: Leadership & Academic Service
      subtitle: ''
      text: |-
        - **Team Leader and R2 representative**, Iscte HRS4R Working Group (since July 2025).
        - **President of the Fiscal Council**, Portuguese Association of Political Economy (since 2025).
        - **Co-chair**, Council for European Studies Social Movements Research Network (2022–2025).
        - **Scientific evaluator**, FCT PhD Studentships Panel (2024) and ANPOCS (2025).
    design:
      columns: '2'
  - block: collection
    id: data
    content:
      title: Research Data
      count: 3
      filters:
        folders:
          - dataset
    design:
      columns: '2'
      view: citation
  - block: markdown
    id: engagement
    content:
      title: Public Engagement
      subtitle: ''
      text: |-
        Selected media commentary:

        - [“Greves caem quase 27% no primeiro ano do Governo de Luís Montenegro”](https://eco.sapo.pt/2025/02/21/greves-caem-quase-27-no-primeiro-ano-do-governo-de-luis-montenegro/), *ECO* (2025).
        - [“Greves diminuem nos primeiros nove meses do ano à boleia das eleições e acordos setoriais”](https://eco.sapo.pt/2024/11/11/greves-diminuem-nos-primeiros-nove-meses-do-ano-a-boleia-das-eleicoes-e-acordos-setoriais/), *ECO* (2024).
        - [“Vem aí um trimestre repleto de greves”](https://eco.sapo.pt/2023/10/27/vem-ai-um-trimestre-repleto-de-greves-tem-tudo-para-ser-um-periodo-caotico/), *ECO* (2023).

        [See the full media record on Ciência-Iscte](https://ciencia.iscte-iul.pt/authors/tiago-carvalho/media).
    design:
      columns: '2'
  - block: contact
    id: contact
    content:
      title: Contact
      # Contact (add or remove contact options as necessary)
      email: tmlco@iscte-iul.pt
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---

