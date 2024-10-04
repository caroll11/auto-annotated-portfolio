---
type: PageLayout
title: Home
colors: colors-d
backgroundImage:
  type: BackgroundImage
  url: /images/pexels-tirachard-kumtanom-112571-450055.jpg
  backgroundSize: cover
  backgroundPosition: center
  backgroundRepeat: no-repeat
  opacity: 71
sections:
  - elementId: ''
    colors: colors-c
    backgroundSize: full
    title: carolina pereira
    subtitle: >-
      Olá, Sou a Carolina, tenho 17 anos e resido na Trofa. Sou estudante do 3º
      ano do curso de Técnico de Gestão de Sistemas Informáticos.
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
        textAlign: left
        fontWeight: 400
      subtitle:
        textAlign: left
      text:
        textAlign: left
      actions:
        justifyContent: flex-start
    type: HeroSection
    actions: []
    media:
      type: ImageBlock
      url: /images/VIT_2990.jpg
      altText: altText of the image
      caption: Caption of the image
      elementId: ''
  - type: LabelsSection
    title: competências técnicas
    subtitle: ''
    items:
      - type: Label
        label: PHP
        url: ''
      - type: Label
        label: HTML e CSS
        url: ''
      - type: Label
        label: Photoshop
        url: ''
      - type: Label
        label: 3DS MAX
        url: ''
      - type: Label
        label: C++
        url: ''
    colors: colors-f
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-36
          - pb-36
          - pl-4
          - pr-0
        justifyContent: center
        margin:
          - mr-0
          - ml-96
      title:
        textAlign: left
      subtitle:
        textAlign: left
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
    subtitle: Projetos realizados
  - type: ContactSection
    title: Contate-me
    text: ''
    form:
      type: FormBlock
      title: Title of the form
      fields:
        - type: TextFormControl
          name: name
          label: Nome
          hideLabel: true
          placeholder: Your name
          width: 1/2
          isRequired: 'true'
        - type: EmailFormControl
          name: email
          label: Name
          hideLabel: true
          placeholder: Your email
          width: 1/2
          isRequired: 'true'
        - type: TextareaFormControl
          name: message
          label: Fale-me sobre seu projeto
          hideLabel: true
          placeholder: Tell me about your project
          width: full
          isRequired: true
        - type: CheckboxFormControl
          name: updates
          label: Receber notificação
          width: full
          isRequired: 'false'
      submitLabel: Mandar Mensagem
      elementId: contact-form
      styles:
        submitLabel:
          textAlign: left
    colors: colors-f
    backgroundSize: full
    elementId: ''
    styles:
      self:
        height: auto
        width: narrow
        padding:
          - pt-28
          - pb-36
          - pl-4
          - pr-4
        alignItems: center
        justifyContent: center
        flexDirection: row
      title:
        textAlign: center
      text:
        textAlign: center
---
