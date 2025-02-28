---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: ''
      color: text-dark
      type: TitleBlock
    subtitle: El corazón de Centroamérica
    text: >+
      Nicaragua, conocida como la "Tierra de Lagos y Volcanes", es un país lleno
      de contrastes y belleza natural. Ubicado en el istmo centroamericano,
      ofrece una mezcla única de playas vírgenes en el Pacífico y el Caribe,
      imponentes volcanes, selvas exuberantes y el majestuoso Lago de Nicaragua,
      el más grande de Centroamérica.

    actions:
      - label: Conoce más
        altText: ''
        url: /
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: secondary
        elementId: ''
        type: Button
      - label: imágenes
        altText: ''
        url: /
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    media:
      url: /images/map-nicaragua.png
      altText: Unblock your team boost your time to production preview
      elementId: ''
      type: ImageBlock
    badge:
      label: 'Nicaragua, un país de colores y sabores'
      color: text-primary
      type: Badge
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        alignItems: center
        flexDirection: row
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
  - subtitle: Award winning enterprises trust us
    images:
      - url: /images/istockphoto-928438734-1024x1024.jpg
        altText: Empathy logo
        type: ImageBlock
      - url: /images/istockphoto-155350183-1024x1024.jpg
        altText: Wellster logo
        type: ImageBlock
      - url: /images/istockphoto-1380971891-1024x1024.jpg
        altText: Vise logo
        type: ImageBlock
      - url: /images/istockphoto-928438734-1024x1024.jpg
        altText: Telus logo
        type: ImageBlock
      - url: /images/istockphoto-885533952-1024x1024.jpg
        altText: Contentful logo
        type: ImageBlock
      - url: /images/sanity-logo.svg
        altText: Sanity logo
        type: ImageBlock
      - url: /images/rangle-logo.svg
        altText: Rangle logo
        type: ImageBlock
    motion: move-to-left
    colors: bg-light-fg-dark
    styles:
      self:
        justifyContent: center
      subtitle:
        textAlign: center
    type: ImageGallerySection
  - posts:
      - content/pages/blog/case-study-1.md
      - content/pages/blog/case-study-2.md
      - content/pages/blog/case-study-3.md
    showThumbnail: true
    showDate: true
    showAuthor: true
    variant: three-col-grid
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
    type: FeaturedPostsSection
    hoverEffect: move-up
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title: Divider
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-7
          - pl-7
          - pb-7
          - pr-7
    type: DividerSection
  - title:
      text: ACTIVIDADES
      color: text-primary
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: >-
      "Nicaragua, tierra de lagos y volcanes, donde la cultura late al ritmo de
      la marimba y los sabores ancestrales conquistan paladares."
    items:
      - title: ''
        tagline: ADIVINA
        subtitle: ''
        text: ''
        image:
          url: /images/hero2.svg
          altText: Placeholder Image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
        actions:
          - type: Button
            label: JUEGO
            altText: ''
            url: >-
              /https://view.genially.com/67bdd90af829f35be0e7ee1a/interactive-content-adivina-los-personajes-nicaraguenses
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
      - title: ''
        tagline: TRIVIA
        subtitle: ''
        text: ''
        image:
          url: /images/hero2.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
        actions:
          - type: Button
            label: JUEGO
            altText: ''
            url: >-
              /https://view.genially.com/67bcfd96b54a23ecb6c88dc7/interactive-content-trivia-nicaragua
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
      - title: ''
        tagline: ESCAPE ROOM
        subtitle: ''
        text: ''
        image:
          url: /images/hero3.svg
          altText: Placeholder image
          styles:
            self:
              borderRadius: x-large
          type: ImageBlock
        colors: bg-light-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: col
        type: FeaturedItem
        actions:
          - type: Button
            label: JUEGO
            altText: ''
            url: >-
              /https://view.genially.com/67bde33691b931b8f8a2a0c6/interactive-content-escape-room-nicaragua
            showIcon: false
            icon: arrowRight
            iconPosition: right
            style: primary
            elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pt-16
          - pl-8
          - pb-16
          - pr-8
        justifyContent: center
      subtitle:
        textAlign: center
    type: FeaturedItemsSection
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
