---
title: Dagrapportage Vulploeg
slug: /
sections:
  - type: GenericSection
    title:
      text: Dagrapportage voor de Albert Heijn vulploeg
      color: text-dark
      type: TitleBlock
    subtitle: Vul na je dienst kort in wat je hebt gedaan en waar je bent gebleven.
    text: >-
      Met dit formulier houdt de teamleider overzicht over gevulde schappen,
      restpunten en bijzonderheden. Je rapportage is direct zichtbaar voor de
      volgende ploeg.
    actions:
      - label: Naar het formulier
        altText: ''
        url: '#vulploeg-formulier'
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    media:
      url: /images/main-hero.svg
      altText: Overzicht van dagrapportage voor vulploegers
      elementId: ''
      type: ImageBlock
    badge:
      label: Voor teamleiders & vulploegers
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
  - type: FeaturedItemsSection
    title:
      text: Zo werkt het
      color: text-dark
      styles:
        self:
          textAlign: center
      type: TitleBlock
    subtitle: Binnen één minuut je dienst vastleggen
    items:
      - type: FeaturedItem
        title: 1
        subtitle: Check-in
        text: Noteer je naam, datum en diensttijd zodat we weten wie er werkte.
        actions: []
        elementId: null
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            justifyContent: center
            textAlign: left
        image:
          type: ImageBlock
          altText: Kalender pictogram
          elementId: ''
          url: /images/icon1.svg
          styles:
            self:
              borderRadius: x-large
      - type: FeaturedItem
        title: 2
        subtitle: Wat heb je gedaan
        text: Geef aan welke gangen of afdelingen je hebt gevuld en wat nog openstaat.
        image:
          url: /images/icon2.svg
          altText: Takenlijst pictogram
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
            textAlign: left
            justifyContent: center
      - type: FeaturedItem
        title: 3
        subtitle: Bijzonderheden
        text: Meld tekorten, beschadigingen of vragen voor de volgende ploeg.
        image:
          url: /images/icon3.svg
          altText: Notitie pictogram
          elementId: ''
          type: ImageBlock
        actions: []
        colors: bg-neutralAlt-fg-dark
        styles:
          self:
            padding:
              - pt-8
              - pl-8
              - pb-8
              - pr-8
            borderRadius: x-large
            flexDirection: row
    actions:
      - label: Vul rapport in
        altText: ''
        url: '#vulploeg-formulier'
        showIcon: false
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: ''
        type: Button
    badge:
      label: Snelle terugkoppeling
      color: text-primary
      styles:
        self:
          textAlign: center
      type: Badge
    elementId: ''
    variant: three-col-grid
    colors: bg-neutral-fg-dark
    styles:
      self:
        padding:
          - pb-16
          - pt-16
          - pl-16
          - pr-16
        justifyContent: center
      subtitle:
        textAlign: center
  - title:
      text: Dienstoverzicht invullen
      color: text-dark
      type: TitleBlock
    subtitle: Deel in één keer alle belangrijke info met de teamleider.
    text: |-
      Vul de velden zo volledig mogelijk in. Zo weten collega’s precies wat er
      al gedaan is en wat nog moet gebeuren.
    media:
      fields:
        - name: medewerker
          label: Naam medewerker
          hideLabel: false
          placeholder: Je naam
          isRequired: true
          width: full
          type: TextFormControl
        - name: dienst_datum
          label: Datum dienst
          hideLabel: false
          placeholder: 12-03-2024
          isRequired: true
          width: full
          type: TextFormControl
        - name: dienst_tijd
          label: Diensttijd
          hideLabel: false
          placeholder: Ochtend / Middag / Avond
          isRequired: true
          width: full
          type: TextFormControl
        - name: afdeling
          label: Afdeling
          hideLabel: false
          defaultValue: Kies afdeling
          options:
            - Koeling
            - Vers
            - Drogisterij
            - Vakkenvulling algemeen
            - Kassa
          isRequired: true
          width: full
          type: SelectFormControl
        - name: restpunten
          label: Openstaande restpunten
          hideLabel: false
          placeholder: Wat moet er nog gebeuren?
          width: full
          type: TextareaFormControl
        - name: tekorten
          label: Tekorten of beschadigingen
          hideLabel: false
          placeholder: Noteer tekorten, beschadigde producten of kapotte spullen.
          width: full
          type: TextareaFormControl
        - name: schapcontroleronde
          label: Schapcontroleronde gelopen
          isRequired: false
          width: full
          type: CheckboxFormControl
        - name: koeling_gemonteerd
          label: Koeling gevuld en gecontroleerd
          isRequired: false
          width: full
          type: CheckboxFormControl
      elementId: vulploeg-formulier
      styles:
        self:
          padding:
            - pt-6
            - pb-6
            - pl-6
            - pr-6
          borderColor: border-dark
          borderStyle: solid
          borderWidth: 1
          borderRadius: large
      type: FormBlock
      submitButton:
        type: SubmitButtonFormControl
        label: Rapport verzenden
        showIcon: true
        icon: arrowRight
        iconPosition: right
        style: primary
        elementId: null
    badge:
      label: Rapportage formulier
      color: text-primary
      type: Badge
    colors: bg-light-fg-dark
    type: GenericSection
seo:
  metaTitle: Dagrapportage Vulploeg
  metaDescription: Laat vulploegers snel invullen wat ze hebben gedaan tijdens hun dienst.
  socialImage: /images/main-hero.jpg
  type: Seo
type: PageLayout
---
