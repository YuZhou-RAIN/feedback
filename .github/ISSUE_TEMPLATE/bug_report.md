---
name: Bug Report
description: Report a problem you encountered
title: "[Bug] "
labels: ["bug"]
body:
  - type: markdown
    attributes:
      value: |
        Thanks for taking the time to report this bug! Please check if an issue about this already exists before submitting.
  - type: textarea
    id: description
    attributes:
      label: Problem Description
      description: What went wrong? What did you expect to happen instead?
      placeholder: "Describe what happened..."
    validations:
      required: true
  - type: textarea
    id: steps
    attributes:
      label: Steps to Reproduce
      description: How can we reproduce this? Be as detailed as possible.
      placeholder: |
        1. Do this
        2. Then do that
        3. This happened
    validations:
      required: true
  - type: textarea
    id: media
    attributes:
      label: Screenshots / Screen Recordings
      description: Drag and drop images or videos here to help us understand the problem.
      placeholder: "Paste screenshots or recordings here (optional)"
  - type: checkboxes
    id: checklist
    attributes:
      label: Checklist
      options:
        - label: I searched for existing issues about this problem
          required: true
        - label: I filled in all required fields
          required: true
