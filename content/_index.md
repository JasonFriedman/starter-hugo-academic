---
# Leave the homepage title empty to use the site title
title: Jason Friedman
date: 2024-11-24
type: landing

sections:
  - block: resume-biography-3
    id: about
    content:
      title: Biography
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin
#  - block: collection
#    id: posts
#    content:
#      title: Recent Posts
#      subtitle: ''
#      text: ''
#      # Choose how many pages you would like to display (0 = all pages)
#      count: 5
#      # Filter on criteria
#      filters:
#        folders:
#          - post
#        author: ""
#        category: ""
#        tag: ""
#        exclude_featured: false
#        exclude_future: false
#        exclude_past: false
#        publication_type: ""
#      # Choose how many pages you would like to offset by
#      offset: 0
#      # Page order: descending (desc) or ascending (asc) date.
#      order: desc
#    design:
#      # Choose a layout view
#      view: compact
#      columns: '2'
#  - block: portfolio
  - block: collection
    id: projects
    content:
      title: Projects
      filters:
        folders:
          - project
      # Default filter index (e.g. 0 corresponds to the first `filter_button` instance below).
      default_button_index: 0
      # Filter toolbar (optional).
      # Add or remove as many filters (`filter_button` instances) as you like.
      # To show all items, set `tag` to "*".
      # To filter by a specific tag, set `tag` to an existing tag name.
      # To remove the toolbar, delete the entire `filter_button` block.
#      buttons:
#        - name: All
#          tag: '*'
#        - name: Deep Learning
#          tag: Deep Learning
#        - name: Other
#          tag: Demo
#    design:
#      # Choose how many columns the section has. Valid values: '1' or '2'.
#      columns: '1'
#      view: showcase
#      # For Showcase view, flip alternate rows?
#      flip_alt_rows: false
 # - block: markdown
 #   content:
 #     title: Gallery
 #     subtitle: ''
 #     text: |-
 #       {{< gallery album="demo" >}}
 #   design:
 #     columns: '1'
  - block: collection
    id: featured
    content:
      title: Featured Publications
      filters:
        folders:
          - publication
        featured_only: true
    design:
      columns: '2'
      view: card
  - block: collection
    content:
      title: Recent Publications
      # text: |-
      #  {{% callout note %}}
      #  Quickly discover relevant content by [filtering publications](./publication/).
      #  {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: true
      text: |-
            A full list of my publications can be found [here](https://curiousjason.com/journalpapers.html).
            A list of publications including citation counts can also be found on [Google scholar](https://scholar.google.com/citations?user=QIVliHQAAAAJ&hl=en), [Web of Science](https://www.webofscience.com/wos/author/rid/B-4690-2008), [ORCID](https://orcid.org/0000-0001-8845-5082), or [cris](https://cris.tau.ac.il/en/persons/jason-friedman).
    
    design:
      columns: '2'
      view: citation
  - block: collection
    id: talks
    content:
      title: Recent & Upcoming Talks
      filters:
        folders:
          - event
    design:
      columns: '2'
      view: compact
#  - block: tag_cloud
#    content:
#      title: Popular Topics
#    design:
#      columns: '2'

#  - block: contact
#  - block: collection
#    id: contact
#    content:
#      title: Contact
#      text: |-
#        Questions? Send me an email: jason@tauex.tau.ac.il
#      filters: 
#        folders:

#      subtitle:
#      autolink: true
      # Contact (add or remove contact options as necessary)
#      email: jason@tauex.tau.ac.il
#      address:
#        street: Health Professions Building, Room 317d
#        city: Tel Aviv University
#        postcode: '6997801'
#        country: Israel
#        country_code: IL
#      # Automatically link email and phone or display as text?
      # Email form provider
#      form:
#        provider: netlify
#        formspree:
#          id:
#        netlify:
#          # Enable CAPTCHA challenge to reduce spam?
#          captcha: true
#    design:
#      columns: '2'
---
