---
type: PageLayout
title: Home
colors: colors-a
backgroundImage:
  type: BackgroundImage
  url: /images/bg1.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 75
sections:
  - elementId: ''
    colors: colors-f
    backgroundSize: full
    title: Pure Computers (PuCo)
    subtitle: >-
      From custom gaming rigs to Commercial. it deployments. such as POS systems
      CCTV digital signage, Whether it's a small issue that you need some Tech
      support for we can remotely connect to your computer. Just let us know
      what your needs are and we'd be happy to give you a introductory free
      estimate
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-36
          - pb-48
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row-reverse
      title:
        textAlign: center
        fontWeight: 400
        textDecoration: underline
        fontStyle: italic
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions:
      - type: Button
        label: MAIN SITE
        altText: 'CLICK ME :)'
        url: 'https://www.PureComp.Net'
        showIcon: true
        icon: chevronRight
        iconPosition: left
        style: secondary
        elementId: ''
      - type: Button
        label: Facebook
        altText: '@purecompr'
        url: 'https://facebook.com/purecompr'
        showIcon: true
        icon: facebook
        iconPosition: left
        style: secondary
        elementId: ''
    text: "Hey there, tech-savvy enthusiasts! \U0001F3AE\U0001F4BB Looking for top-notch custom gaming builds, expert repair services, efficient IT networking solutions, and a wide range of computer sales, repairs, and upgrades? Look no further! \n\n\U0001F31FWhether you're a residential user or a commercial business, we've got you covered. Our team is here to make your life easier and get you back on track in no time. Plus, guess what?\n\n You can kickstart your journey with us by getting a FREE consultation or service estimate today!\n\n \U0001F680No task is too small or too large for us—we're here to cater to all your needs. So why wait? Reach out to us, let our knowledgeable experts guide you in the right direction, and let's elevate your tech experience together. Let's chat soon!\_\n\n"
    media:
      type: VideoBlock
      title: Title of the video
      url: 'https://youtu.be/BD-YliszGkA'
      elementId: ''
      autoplay: false
      loop: true
      muted: false
      controls: true
      aspectRatio: '4:3'
  - colors: colors-f
    type: FeaturedProjectsSection
    elementId: ''
    actions:
      - type: Link
        label: See all projects
        url: /projects
    showDate: false
    showDescription: true
    showFeaturedImage: true
    showReadMoreLink: true
    variant: variant-b
    projects:
      - content/pages/projects/project-two.md
      - content/pages/projects/project-three.md
      - content/pages/projects/project-one.md
    styles:
      self:
        height: auto
        width: wide
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pl-4
          - pr-4
        justifyContent: center
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
    subtitle: Projects
  - type: FeaturedPostsSection
    elementId: ''
    colors: colors-f
    variant: variant-d
    subtitle: Featured Posts
    showFeaturedImage: false
    actions:
      - type: Link
        label: See all posts
        url: /blog
    posts:
      - content/pages/blog/post-six.md
      - content/pages/blog/post-four.md
      - content/pages/blog/post-three.md
    showDate: true
    showExcerpt: true
    showReadMoreLink: true
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-28
          - pb-48
          - pl-4
          - pr-4
        justifyContent: center
        borderRadius: none
        borderWidth: 0
        borderStyle: none
        borderColor: border-dark
      title:
        textAlign: left
      subtitle:
        textAlign: left
      actions:
        justifyContent: flex-end
  - type: ContactSection
    colors: colors-f
    backgroundSize: full
    title: "Got an interesting project? Tell me more...\U0001F4AC"
    form:
      type: FormBlock
      elementId: sign-up-form
      fields:
        - name: firstName
          label: First Name
          hideLabel: true
          placeholder: First Name
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: lastName
          label: Last Name
          hideLabel: true
          placeholder: Last Name
          isRequired: false
          width: 1/2
          type: TextFormControl
        - name: email
          label: Email
          hideLabel: true
          placeholder: Email
          isRequired: true
          width: 1/2
          type: EmailFormControl
        - name: address
          label: Address
          hideLabel: true
          placeholder: Address
          isRequired: true
          width: 1/2
          type: TextFormControl
        - name: updatesConsent
          label: Sign me up to recieve updates
          isRequired: false
          width: full
          type: CheckboxFormControl
      submitLabel: "Submit \U0001F680"
      styles:
        submitLabel:
          textAlign: center
    styles:
      self:
        height: auto
        width: narrow
        margin:
          - mt-0
          - mb-0
          - ml-0
          - mr-0
        padding:
          - pt-24
          - pb-24
          - pr-4
          - pl-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: left
      text:
        textAlign: left
metaTitle: Pure Computers
metaDescription: >-
  Computers, Repair, Rochester, NY, Tech, Support, cheap, fast, local, free,
  Estimate
addTitleSuffix: true
socialImage: /images/gallery-1.jpg
metaTags:
  - type: MetaTag
    property: 'og:title'
    content: ''
---
