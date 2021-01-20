---
title: Contact
hide_title: false
sections:
  - section_id: contact-form
    type: section_form
    content: |+
      Para entrar em contato preencha o formulário abaixo.

    form_id: contactForm
    form_action: /thank-you
    form_fields:
      - input_type: text
        name: name
        label: Name
        default_value: Your name
        is_required: true
      - input_type: email
        name: email
        label: Email
        default_value: Your email address
        is_required: true
      - input_type: select
        name: subject
        label: Subject
        default_value: Please select
        options:
          - Error on the site
          - Sponsorship
          - Other
      - input_type: textarea
        name: message
        label: Message
        default_value: Sua mensagem
      - input_type: checkbox
        name: consent
        label: >-
          Eu entendo que este formulário está armazenando minhas informações
          enviadas para que eu possa ser contatado.
    submit_label: Send Message
template: advanced
---
