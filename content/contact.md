---
title: Contatti
hide_title: false
sections:
- type: section_form
  template: section_form
  section_id: contact-form
  content: Completa questo modulo, e ti contatterò il prima possibile!
  form_id: contactForm
  form_action: "/thank-you"
  form_fields:
  - type: form_field
    template: form_field
    input_type: text
    name: 'nome:'
    label: Nome
    default_value: Come ti chiami?
    is_required: true
    options: []
  - type: form_field
    template: form_field
    input_type: email
    name: 'email:'
    label: Email
    default_value: Il tuo indirizzo mail
    is_required: true
    options: []
  - type: form_field
    template: form_field
    input_type: select
    name: 'oggetto:'
    label: Per cosa mi contatti?
    default_value: Scegli un'opzione
    options:
    - Ripetizione/Assistenza Tecnica
    - Offerta di Lavoro
    - Altro
    is_required: true
  - type: form_field
    template: form_field
    input_type: textarea
    name: 'messaggio:'
    label: Cosa Vuoi Dirmi?
    default_value: Dimmi tutto!
    options: []
    is_required: true
  - type: form_field
    template: form_field
    input_type: checkbox
    name: consent
    label: I understand that this form is storing my submitted information so I can
      be contacted.
    default_value: ''
    options: []
    is_required: false
  submit_label: Invia
  title: ''
layout: advanced
excerpt: ''

---
