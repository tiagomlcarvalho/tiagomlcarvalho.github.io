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
      title: Publications
      filters:
        folders:
          - publication
        exclude_featured: true
    design:
      columns: '2'
      view: citation
  - block: collection
    id: workingpapers
    content:
      title: Working Papers
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - wpapers
        author: ""
        category: ""
        tag: ""
        exclude_featured: false
        exclude_future: false
        exclude_past: false
        publication_type: ""
      # Choose how many pages you would like to offset by
      offset: 0
      # Page order: descending (desc) or ascending (asc) date.
      order: desc
    design:
      # Choose a layout view
      view: compact
      columns: '2'    
  - block: collection
    id: data
    content:
      title: Data
      filters:
        folders:
          - data
    design:
      columns: '2'
      view: compact
  - block: contact
    id: contact
    content:
      title: Contact
      # Contact (add or remove contact options as necessary)
      email: mariana.carmoduarte@ics.ulisboa.pt
      address:
        street: Av. Professor Aníbal de Bettencourt 9
        city: Lisbon
        region: 
        postcode: 1600-189
        country: Portugal
        country_code: PT
      directions: Office
      # Automatically link email and phone or display as text?
      autolink: true
    design:
      columns: '2'
---
