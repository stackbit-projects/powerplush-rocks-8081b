---
title: Home
sections:
  - type: hero_section
    title: '"Smth Cool" is out now!'
    subtitle: Check it out.
    actions:
      - label: Listen
        url: /pricing
        style: primary
    image: /images/cover_smthcool.jpg
    image_alt: Smth Cool Artwork
    media_position: top
    media_width: fourty
    align: left
    padding_top: large
    padding_bottom: large
    background_color: primary
  - type: grid_section
    title: Social Media
    align: center
    grid_items:
      - image: images/logo-1.svg
        image_alt: Contentful logo
        image_align: center
      - image: images/logo-2.svg
        image_alt: Netlify logo
        image_align: center
      - image: images/logo-3.svg
        image_alt: Gatsby logo
        image_align: center
      - image: images/logo-4.svg
        image_alt: Sanity logo
        image_align: center
      - image_alt: DatoCMS logo
        image_align: center
      - image_alt: Next.js logo
        image_align: center
      - image_alt: Gridsome logo
        image_align: center
      - image_alt: Git logo
        image_align: center
    grid_cols: four
    grid_gap_horiz: medium
    grid_gap_vert: medium
  - type: grid_section
    title: Team Section
    subtitle: Grid Section Example
    actions:
      - label: Join the team
        url: /style-guide
        style: primary
    grid_items:
      - title: Gustav Purpleson
        subtitle: Co-Founder & CEO
        title_align: center
        image: images/gustav-purpleson.jpg
        image_position: top
      - title: Dianne Ameter
        subtitle: Software Engineer
        title_align: center
        image: images/dianne-ameter.jpg
        image_position: top
      - title: Hugh Saturation
        subtitle: Developer Advocate
        title_align: center
        image: images/hugh-saturation.jpg
        image_position: top
      - title: Hilary Ouse
        subtitle: Operations Manager
        title_align: center
        image: images/hilary-ouse.jpg
        image_position: top
    grid_cols: four
    align: center
    background_color: secondary
  - type: blog_feed_section
    title: What's New
    subtitle: Blog Feed Section Example
    actions:
      - label: View All
        url: /blog
        style: primary
    blog_feed_cols: three
    enable_cards: true
    show_recent: true
    recent_count: 3
    show_image: true
    show_date: true
    show_categories: true
    show_author: true
    show_excerpt: false
    align: center
    padding_top: medium
    padding_bottom: medium
    has_border: false
    background_color: none
  - type: cta_section
    title: This is Call To Action Section In DIY Theme!
    content: >-
      Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec nisl
      ligula, cursus id molestie vel, maximus aliquet risus. Vivamus in nibh
      fringilla, fringilla.
    actions:
      - label: Button
        url: /pricing
        style: primary
    actions_position: bottom
    align: center
    padding_top: large
    padding_bottom: large
    background_color: secondary
seo:
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
