name: Bug Report
description: Report a bug or gameplay issue
title: "[BUG]: "
labels:
  - bug

body:
  - type: textarea
    id: description
    attributes:
      label: Bug Description
      description: Describe the issue in detail.
      placeholder: What happened?
    validations:
      required: true

  - type: textarea
    id: expected
    attributes:
      label: Expected Behavior
      description: What should happen instead?
    validations:
      required: true

  - type: textarea
    id: reproduce
    attributes:
      label: Steps to Reproduce
      description: List the steps required to reproduce the issue.
      placeholder: |
        1. Join server
        2. Spawn vehicle
        3. Drive to depot
        4. Observe issue
    validations:
      required: true

  - type: input
    id: map
    attributes:
      label: Map
      placeholder: Everon

  - type: dropdown
    id: faction
    attributes:
      label: Faction
      options:
        - US
        - Russia
        - FIA
        - Other

  - type: input
    id: version
    attributes:
      label: Game Version
      placeholder: 1.0.0

  - type: textarea
    id: evidence
    attributes:
      label: Screenshots / Videos / Logs
      description: Paste links or upload files.

  - type: textarea
    id: additional
    attributes:
      label: Additional Information
      description: Any extra details that may help.
