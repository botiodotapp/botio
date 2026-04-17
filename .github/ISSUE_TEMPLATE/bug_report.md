name: Bug Report
description: File a bug report to help us improve.
labels: ["bug"]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to fill out this bug report!
  - type: input
    id: contact
    attributes:
      label: Contact Information
      description: How can we get in touch with you?
      placeholder: ex. email@example.com
    validations:
      required: false
  - type: textarea
    id: reproduction
    attributes:
      label: Reproduction Steps
      description: How did you encounter this bug?
      placeholder: |
        1. Go to '...'
        2. Click on '....'
    validations:
      required: true
  - type: dropdown
    id: version
    attributes:
      label: Version
      options:
        - v1.0
        - v2.0
        - Other
    validations:
      required: true
