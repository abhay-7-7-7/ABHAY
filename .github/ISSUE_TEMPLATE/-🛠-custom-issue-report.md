---
name: " \U0001F6E0 Custom Issue Report"
about: Use this template for reporting general issues or requests.
title: ''
labels: ''
assignees: ''

---

name: 🛠 Custom Issue Report
description: Use this template for reporting general issues or requests.
title: "[Custom Issue] "
labels: ["custom", "needs-triage"]
assignees: ["yourusername"]
body:
  - type: markdown
    attributes:
      value: |
        ## 🛠 Custom Issue Report

        Please provide the details of your issue below. Be as specific as possible to help us understand and resolve the issue.

  - type: input
    id: issue-title
    attributes:
      label: Issue Title
      description: A brief title for your issue.
      placeholder: "Title of the issue"
    validations:
      required: true

  - type: textarea
    id: issue-description
    attributes:
      label: Issue Description
      description: A detailed description of the issue.
      placeholder: "Describe the issue in detail"
    validations:
      required: true

  - type: markdown
    attributes:
      value: |
        ### Environment Details

  - type: input
    id: os
    attributes:
      label: Operating System
      description: The operating system where the issue occurs.
      placeholder: "e.g., Windows, Linux, macOS"
  
  - type: input
    id: browser
    attributes:
      label: Browser
      description: The browser where the issue occurs.
      placeholder: "e.g., Chrome, Firefox"

  - type: markdown
    attributes:
      value: |
        ### Additional Information

  - type: textarea
    id: additional-context
    attributes:
      label: Additional Context
      description: Any other information that might help us understand the issue.
      placeholder: "Add any additional context here"
