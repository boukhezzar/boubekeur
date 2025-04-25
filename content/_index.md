---
# Leave the homepage title empty to use the site title
title: ''
date: 2022-10-24
type: landing

sections:
  # BIO
  - block: about.biography
    id: about
    content:
      title: About
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: admin 
  # PUBLICATIONS
  - block: collection
    id: publications
    content:
      title: Publications
      text: |-
        {{% callout note %}}
        Quickly discover relevant content by [filtering publications](./publication/).
        {{% /callout %}}
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      columns: '2'
      view: citation         
  # POSTS
  - block: collection
    id: posts
    content:
      title: Recent Posts
      subtitle: ''
      text: ''
      # Choose how many pages you would like to display (0 = all pages)
      count: 5
      # Filter on criteria
      filters:
        folders:
          - post
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
  # MEDIA GALLERY
  - block: markdown
    id: gallery
    content:
      title: Gallery
      subtitle: ''
      text: |-
        {{< gallery album="demo" >}}
    design:
      columns: '1'
  - block: contact
    id: contact
    content:
      title: Contact
      subtitle:
      #text: |-
      #  Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nam mi diam, venenatis ut magna et, vehicula efficitur enim.
      # Contact (add or remove contact options as necessary)
      email: giacomod@uw.edu
      address:
        street: Wilson Ceramic Laboratory (WCL) 
        city: Seattle
        region: WA
        postcode: '98195'
        country: United States
        country_code: US
      directions: Urban Freight Lab, 1st floor, Room 111, 
      # Choose a map provider in `params.yaml` to show a map from these coordinates
      coordinates:
        latitude: '47.651672574911935'
        longitude: '-122.3048521753502'  
      #contact_links:
      #  - icon: twitter
      #    icon_pack: fab
      #    name: DM Me
      #    link: 'https://twitter.com/Twitter'
      # Automatically link email and phone or display as text?
      autolink: false
      # Email form provider
      #form:
      #  provider: netlify
      #  formspree:
      #    id:
      #  netlify:
      #    # Enable CAPTCHA challenge to reduce spam?
      #    captcha: false
    design:
      columns: '2'

 # - block: accomplishments
 #   content:
 #     # Note: `&shy;` is used to add a 'soft' hyphen in a long heading.
 #     title: 'Accomplish&shy;ments'
 #     subtitle:
 #     # Date format: https://docs.hugoblox.com/customization/#date-format
 #     date_format: Jan 2006
 #     # Accomplishments.
 #     #   Add/remove as many `item` blocks below as you like.
 #     #   `title`, `organization`, and `date_start` are the required parameters.
 #     #   Leave other parameters empty if not required.
 #     #   Begin multi-line descriptions with YAML's `|2-` multi-line prefix.
 #     items:
 #       - certificate_url: https://www.coursera.org
 #         date_end: ''
 #         date_start: '2021-01-25'
 #         description: ''
 #         icon: coursera
 #         organization: Coursera
 #         organization_url: https://www.coursera.org
 #         title: Neural Networks and Deep Learning
 #         url: ''
 #       - certificate_url: https://www.edx.org
 #         date_end: ''
 #         date_start: '2021-01-01'
 #         description: Formulated informed blockchain models, hypotheses, and use cases.
 #         icon: edx
 #         organization: edX
 #         organization_url: https://www.edx.org
 #         title: Blockchain Fundamentals
 #         url: https://www.edx.org/professional-certificate/uc-berkeleyx-blockchain-fundamentals
 #       - certificate_url: https://www.datacamp.com
 #         date_end: '2020-12-21'
 #         date_start: '2020-07-01'
 #         description: ''
 #         icon: datacamp
 #         organization: DataCamp
 #         organization_url: https://www.datacamp.com
 #         title: 'Object-Oriented Programming in R'
 #         url: ''
 #   design:
 #     columns: '2'

#  - block: collection
#    id: featured
#    content:
#      title: Featured Publications
#      filters:
#        folders:
#          - publication
#        featured_only: true
#    design:
#      columns: '2'
#      view: card


#  - block: collection
#    content:
#      title: Recent Publications
#      text: |-
#        {{% callout note %}}
#        Quickly discover relevant content by [filtering publications](./publication/).
#        {{% /callout %}}
#      filters:
#        folders:
#          - publication
#        exclude_featured: true
#    design:
#      columns: '2'
#      view: citation

# - block: collection
#    id: talks
#    content:
#      title: Recent & Upcoming Talks
#      filters:
#        folders:
#          - event
#    design:
#      columns: '2'
#      view: compact

---
