---
title: GarBar Nation
sections:
  - type: hero_section
    actions:
      - label: Watch GarBar Videos
        url: /episodes/
        style: primary
        has_icon: true
        icon: youtube
        icon_position: left
        new_window: false
        no_follow: false
      - label: Listen to GarTalk Podcast
        url: /gartalk/subscribe/
        style: primary
        has_icon: true
        icon: arrow-right
        icon_position: right
        new_window: false
        no_follow: false
    image: /images/smiling-elm.png
    image_alt: 'John, Smitty, Joe, Phil'
    media_position: top
    media_width: fifty
    align: center
    padding_top: small
    padding_bottom: small
    background_color: none
    background_image_repeat: no-repeat
    background_image_size: cover
    background_image_opacity: 100
    has_border: false
    background_image: /images/hero-background-test.png
    background_image_position: left bottom
    title: Welcome to GarBar Nation
    subtitle: >-
      Spotlighting garage bar (#GarBar) renovations across the nation. <BR>Move
      your car, build a bar!
  - type: blog_feed_section
    title: Latest GarBars
    blog_feed_cols: three
    enable_cards: true
    show_recent: true
    recent_count: 6
    show_image: true
    show_date: false
    show_categories: true
    show_author: false
    show_excerpt: true
    align: center
    padding_top: medium
    padding_bottom: medium
    has_border: true
    background_color: none
    background_image_repeat: no-repeat
    background_image_size: cover
    background_image_opacity: 35
    subtitle: Take a Tour
    background_image: /images/AdobeStock_340935160-vert.png
  - type: grid_section
    title: Tune into GarTalk
    grid_items:
      - title: Spotify
        title_align: center
        content_align: center
        actions:
          - label: Tune In
            url: >-
              https://open.spotify.com/show/08kNlmCWZyvevIvdTWuCxo?si=XEJb_o40S-mtEq2veLSzZA&dl_branch=1
            style: primary
            has_icon: true
            icon: arrow-right
            icon_position: right
            new_window: true
        actions_align: center
        image: images/icon-2.svg
        image_alt: Spotify icon
        image_position: top
        image_align: center
        image_has_padding: false
      - title: Apple
        title_align: center
        content_align: center
        actions:
          - label: Coming Soon!
            url: '#'
            style: secondary
            has_icon: false
            icon: arrow-left
            icon_position: right
            new_window: false
            no_follow: true
        actions_align: center
        actions_width: auto
        image_alt: lorem-ipsum
        image_position: top
        image_width: fifty
        image_align: center
        image_has_padding: false
        image: /images/icon-1.svg
    grid_cols: two
    grid_gap_horiz: medium
    grid_gap_vert: medium
    enable_cards: true
    align: center
    padding_top: large
    padding_bottom: large
    has_border: true
    background_color: none
    background_image_repeat: no-repeat
    background_image_size: cover
    background_image_opacity: 0
    subtitle: Weekly interviews with GarBar owners across the Nation!
    background_image_position: left top
    background_image: /images/AdobeStock_340935160-vert2.png
  - type: grid_section
    title: The GarBar Buzz...
    subtitle: Look Who's Talking
    align: center
    grid_items:
      - image: /images/logo-ny-post-horizontal.png
        image_alt: New York Post
        image_align: center
        actions: []
      - image: /images/logo-sf-cronicle-vertical-225w.png
        image_alt: Netlify logo
        image_align: center
      - image: /images/logo-fox5-horizontal-175w.png
        image_alt: Sticker Mule logo
        image_align: center
      - image: /images/logo-cbs-horizontal-175w.png
        image_alt: GitHub logo
        image_align: center
      - image: /images/logo-the-star-ledger-225w.png
        image_alt: Gatsby logo
        image_align: center
      - image: /images/logo-punch-horizontal-225w.png
        image_alt: Twilio logo
        image_align: center
      - image_alt: Contentful logo
        image_align: center
      - image_alt: Forestry logo
        image_align: center
    grid_cols: four
    grid_gap_horiz: medium
    grid_gap_vert: medium
    has_border: true
    background_color: none
    background_image: /images/AdobeStock_340935160.png
    background_image_opacity: 25
    background_image_repeat: no-repeat
    background_image_size: cover
    actions:
      - label: View all the press here
        url: /press
        style: primary
        has_icon: true
        icon: arrow-right
        icon_position: right
        new_window: false
        no_follow: false
  - type: form_section
    content: >
      ## Join The GarBar Nation


      Join the Nation for insider access, discounts, and other GarBar related
      surprises.
    content_align: left
    form_position: right
    form_width: fifty
    form_layout: inline
    enable_card: false
    form_id: contact-form
    form_action: /thank-you
    form_fields:
      - input_type: email
        name: email
        label: Email
        default_value: Enter your email address
        is_required: true
      - input_type: text
        name: name
        label: Name
        default_value: Name
        is_required: false
      - input_type: textarea
        name: message
        label: Question
        default_value: Your question
      - input_type: checkbox
        name: consent
        label: >-
          I understand that this form is storing my submitted information so I
          can be contacted.
        is_required: true
    submit_label: Add Me
    align_vert: top
    padding_top: medium
    padding_bottom: medium
    background_color: none
    background_image: /images/AdobeStock_340935160-2.png
    background_image_repeat: no-repeat
    background_image_size: cover
    background_image_opacity: 30
seo:
  title: "Welcome to GarBar Nation! \U0001F37A"
  description: >-
    Spotlighting garage to bar conversions (#GarBar) and renovations across the
    nation. Move your car, build a bar!
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: "Welcome to GarBar Nation \U0001F37A"
      keyName: property
    - name: 'og:description'
      value: >-
        Spotlighting garage to bar conversions (#GarBar) and renovations across
        the nation. Move your car, build a bar!
      keyName: property
    - name: 'og:image'
      value: /images/garbar-nation-panel-four.jpg
      keyName: property
      relativeUrl: true
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: "Welcome to GarBar Nation\U0001F37A"
    - name: 'twitter:description'
      value: >-
        Spotlighting garage to bar conversions (#GarBar) and renovations across
        the nation. Move your car, build a bar!
    - name: 'twitter:image'
      value: /images/garbar-nation-panel-four.jpg
      relativeUrl: true
layout: advanced
---
