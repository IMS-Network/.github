---
name: 'Question ❓ '
about: Got Any Questions For Us? Fill Free To Ask :)
title: "[QUESTION]"
labels: help wanted, question
assignees: ''
---
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to ask and wait for help!
  - type: input
    id: contact
    attributes:
      label: Contact Details
      description: How can we get in touch with you if we need more info?
      placeholder: ex. email@example.com
    validations:
      required: false
  - type: textarea
    id: the-question
    attributes:
      label: What Do You Want To Know?
      description: Ask Any Qusiton You Want About Any Thing
      placeholder: Tell us what you Want!
      value: "I Have A Qusiton About..."
    validations:
      required: true
  - type: dropdown
    id: version
    attributes:
      label: Related To
      description: What Is The Main Topic In Your Qusiton?
      options:
        - Alfine
        - Minecraft
        - Website
        - FiveM
        - Discord
        - GitHub
        - Documentation
        - Our Team
        - Legal
        - Management
    validations:
      required: true
  - type: checkboxes
    id: terms
    attributes:
      label: Legal Notice
      description: By submitting this question, you agree to respect our team and the given decision about your question, you also understand that all the information                    that is given to you isn't legally accurate.
      options:
        - label: I agree
          required: true


