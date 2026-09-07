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

