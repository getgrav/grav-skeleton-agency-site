---
title: 'contact'
cache_enable: false

form:
    name: contact
    action: /home#contact
    fields:
        - name: name
          label: Name
          classes: form-control
          placeholder: Enter your name
          autofocus: off
          autocomplete: on
          type: text
          position: left
          validate:
            required: true

        - name: email
          label: Email
          classes: form-control
          placeholder: Enter your email address
          type: email
          position: left
          validate:
            required: true

        - name: message
          label: Message
          placeholder: Enter your message
          type: textarea
          classes: form-control
          position: right
          validate:
            required: true

    buttons:
        - type: submit
          classes: "btn btn-primary btn-lg"
          value: Submit
        
    process:
        - message: Thank you for getting in touch!
---

## CONTACT US
### Lorem ipsum dolor sit amet consectetur.
