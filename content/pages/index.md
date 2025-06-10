---
title: Home
slug: /
sections:
  - type: GenericSection
    title:
      text: Pinterpedia.com
      color: text-dark
      type: TitleBlock
    subtitle: Index Link
    text: "Selamat datang di\_**Pinterpedia**, platform digital kekinian yang didedikasikan untuk berbagi informasi ensiklopedia, sejarah, budaya, pengetahuan, gaya hidup, hiburan, teknologi, dan inspirasi sehari-hari. Kami hadir untuk menyajikan konten yang ringan namun berbobot, memberikan wawasan baru, dan menginspirasi pembaca dalam berbagai aspek kehidupan.\n"
    actions:
      - label: Pengetahuan
        altText: ''
        url: 'https://pinterpedia.com/category/pengetahuan/'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Link
    badge:
      label: Website update terbaru setiap hari
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
  - type: FeaturedPostsSection
    title:
      type: TitleBlock
      text: Featured posts
      color: text-dark
      styles:
        self:
          textAlign: center
    posts:
      - content/pages/blog/life-of-our-development-team.md
      - content/pages/blog/surround-yourself-with-right-people.md
      - content/pages/blog/top-twenty-ways-to-save-time.md
    showThumbnail: true
    showExcerpt: true
    showDate: true
    showAuthor: true
    actions: []
    elementId: ''
    variant: three-col-grid
    colors: bg-light-fg-dark
    hoverEffect: thin-underline
    styles:
      self:
        padding:
          - pt-16
          - pl-16
          - pb-16
          - pr-16
        justifyContent: center
  - type: DividerSection
    title: Divider
    elementId: ''
    colors: bg-light-fg-dark
    styles:
      self:
        padding:
          - pt-20
          - pl-20
          - pb-20
          - pr-20
seo:
  metaTitle: Home - Demo site
  metaDescription: This demo site is built with Netlify Create.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
