---
title: Contacto
sections:
  - section_id: Contacto
    type: section_contact
    background: gray
    title: Contacto
    content: >-
      ¿Tienes alguna duda? ¿Estás interesado en alguno de nuestros servicios? ¿Quieres más información sobre algún servicio? <br/>
      Rellena el siguiente formulario y nos pondremos en contacto contigo lo antes posible.
    form_id: contactForm
    form_action: https://formspree.io/f/meqvjvev
    form_fields:
      - input_type: text
        name: name
        label: Nombre
        is_required: true
      - input_type: email
        name: email
        label: Correo electrónico
        is_required: true
      - input_type: select
        name: subject
        label: Motivo
        default_value: Seleccione uno
        options:
          - Amazon Alexa
          - Google Action
          - Chatbot
          - Otro
      - input_type: textarea
        name: message
        label: Mensaje
      - input_type: checkbox
        name: Consentimiento
        label: >-
          Entiendo que este formulario almacena la información enviada, por lo que
          puedo ser contactado.
        is_required: true
    submit_label: Enviar
seo:
  title: Contacto
  description: Página de contacto
  extra:
    - name: 'og:type'
      value: website
      keyName: property
    - name: 'og:title'
      value: Contacto
      keyName: property
    - name: 'og:description'
      value: Página de contacto
      keyName: property
    - name: 'twitter:card'
      value: summary_large_image
    - name: 'twitter:title'
      value: Contacto
    - name: 'twitter:description'
      value: Página de contacto
layout: landing
---
