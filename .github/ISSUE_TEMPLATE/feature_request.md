---
name: Feature request
about: Have an idea you'd like to see in the mod? Submit it here!
title: ''
labels: ''
assignees: ''
type: Feature

---

name: Feature request
description: Suggest a new feature or an improvement.
labels: ["enhancement"]
body:
  - type: textarea
    id: idea
    attributes:
      label: What would you like to see?
      description: Describe the feature or change.
    validations:
      required: true

  - type: textarea
    id: use-case
    attributes:
      label: How would you use it?
      description: What would it help you build or do? your creativity makes a great example. :D
    validations:
      required: true

  - type: textarea
    id: extra
    attributes:
      label: Anything else?
      description: Do you have any other things about this idea I should know about?
    validations:
      required: false

  - type: checkboxes
    id: checks
    attributes:
      label: Before you submit
      options:
        - label: I searched the existing issues and this hasn't been suggested yet.
          required: true
