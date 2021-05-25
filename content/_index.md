---
title: Home
sections:
  - title: Mon Blogue
    subtitle: J'en apprends sur l'environnement
    content: >
      ## Lorem ipsum


      Lorem ipsum dolor sit amet, **consectetur adipiscing elit**, sed do
      eiusmod tempor incididunt ut labore et dolore magna aliqua
    actions: []
    image_alt: lorem-ipsum
    media_position: left
    media_width: fifty
    align: right
    padding_top: medium
    padding_bottom: medium
    has_border: false
    background_color: primary
    background_image_opacity: 0
    background_image_size: cover
    background_image_position: center center
    background_image_repeat: no-repeat
    type: hero_section
    image: /images/Nouvelle branche - 1000x1000.png
  - type: features_section
    title: Ma démarche
    subtitle: C'est quoi le plan avec ça?
    features:
      - type: feature
        title: Recherche
        subtitle: Comment ça marche?
        content: >
          Je pars du début, ou presque. Je fais mes recherches et je parle avec
          les experts du domaine.
        actions:
          - type: action
            label: Learn More
            url: /style-guide
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/classic/feature-1.png
        image_alt: Feature 1 placeholder image
        media_position: right
        media_width: fifty
      - type: feature
        title: Vulgarisation de mes découvertes
        content: >
          Super j'ai plein d'information, mais j'ai besoin de la consolider pour
          bien la comprendre! Et encore plus pour bien la vulgariser. C'est ce
          que j'essaie de faire dans mes articles de blogue.
        actions:
          - type: action
            label: Lire les articles
            url: /style-guide
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/classic/feature-2.png
        image_alt: Feature 2 placeholder image
        media_position: left
        media_width: fifty
      - type: feature
        title: Discussion
        subtitle: Est-ce que j'ai trouvé n'importe quoi?
        content: >
          La discussion est ouverte! Est-ce que j'ai oublié de couvrir une
          portion du sujet? Est-ce qu'il y a un autre angle pour voir le tout? 
        actions:
          - type: action
            label: Learn More
            url: /style-guide
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
        image: images/classic/feature-3.png
        image_alt: Feature 3 placeholder image
        media_position: right
        media_width: fifty
    feature_padding_vert: large
    align: center
    background_color: secondary
  - type: features_section
    features:
      - type: feature
        title: C'est moi!
        subtitle: Alexis Grenon
        image: /images/brandon-guidelines.png
        image_alt: Brandon Guidelines
        media_position: right
        media_width: thirty-three
    feature_padding_vert: small
    background_color: primary
  - type: blog_feed_section
    title: Mes dernières publications
    subtitle: Le blogue
    actions:
      - type: action
        label: Voit tout
        url: /blog
        style: primary
    blog_feed_cols: three
    enable_cards: true
    show_recent: true
    recent_count: 3
    show_date: true
    show_categories: true
    show_author: true
    show_excerpt: false
    show_image: true
    align: center
    padding_top: medium
    padding_bottom: medium
    has_border: false
    background_color: none
  - type: grid_section
    title: Cards Grid Section
    subtitle: Grid Section Example
    grid_items:
      - type: grid_item
        title: Section Item 1
        title_align: left
        content: >-
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
          ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
          fringilla, fringilla.
        content_align: left
        actions:
          - type: action
            label: Learn More
            url: /style-guide
            style: link
            has_icon: true
            icon: arrow-right
            icon_position: center
        actions_align: left
        image: images/classic/icon-1.svg
        image_alt: Section item 1 icon
        image_position: top
        image_align: left
        image_has_padding: true
      - type: grid_item
        title: Section Item 2
        title_align: left
        content: >-
          Ac felis donec et odio pellentesque. Sagittis vitae et leo duis ut
          diam quam nulla. Ullamcorper a lacus vestibulum sed arcu non odio
          euismod lacinia.
        content_align: left
        actions:
          - type: action
            label: Learn More
            url: /style-guide
            style: link
            has_icon: true
            icon: arrow-right
            icon_position: center
        actions_align: left
        image: images/classic/icon-2.svg
        image_alt: Section item 2 icon
        image_position: top
        image_align: left
        image_has_padding: true
      - type: grid_item
        title: Section Item 3
        title_align: left
        content: >-
          Ac felis donec et odio pellentesque. Sagittis vitae et leo duis ut
          diam quam nulla. Ullamcorper a lacus vestibulum sed arcu non odio
          euismod lacinia.
        content_align: left
        actions:
          - type: action
            label: Learn More
            url: /style-guide
            style: link
            has_icon: true
            icon: arrow-right
            icon_position: center
        actions_align: left
        image: images/classic/icon-3.svg
        image_alt: Section item 3 icon
        image_position: top
        image_align: left
        image_has_padding: true
    grid_cols: three
    grid_gap_vert: small
    grid_gap_horiz: medium
    enable_cards: true
    align: center
    background_color: none
  - type: cta_section
    title: Inscription à l'infolettre
    content: |
      J'y publie mes derniers articles et j'y pose mes prochaines questions!
    actions:
      - type: action
        label: M'inscrire
        url: /pricing
        style: primary
    actions_position: bottom
    align: center
    padding_top: large
    padding_bottom: large
    background_color: secondary
seo:
  type: stackbit_page_meta
  title: Stackbit DIY Theme
  description: The preview of the DIY theme
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Stackbit DIY Theme
      keyName: property
    - name: 'og:description'
      value: The preview of the DIY theme
      keyName: property
    - name: 'og:image'
      value: images/diy-preview.png
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Stackbit DIY Theme
    - name: 'twitter:description'
      value: The preview of the DIY theme
    - name: 'twitter:image'
      value: images/diy-preview.png
      relativeUrl: true
layout: advanced
---
