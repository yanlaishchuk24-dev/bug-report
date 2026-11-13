---
name: Bug report
about: Create a report to help us improve
title: ''
labels: ''
assignees: ''

---

name: Bug Report
description: баг репорт на SauceDemo
title: "[BUG] "
labels: ["bug"]
body:
  - type: input
    id: summary
    attributes:
      label: Summary
      description: Коротка назва дефекту
    validations:
      required: true
  - type: textarea
    id: preconditions
    attributes:
      label: Pre-conditions
      description: Передумови для відтворення
    validations:
      required: true
  - type: textarea
    id: steps
    attributes:
      label: Steps to reproduce
      description: Покроковий опис дій
    validations:
      required: true
  - type: textarea
    id: expected
    attributes:
      label: Expected result
      description: Очікуваний результат
    validations:
      required: true
  - type: textarea
    id: actual
    attributes:
      label: Actual result
      description: Фактичний результат
    validations:
      required: true
  - type: input
    id: environment
    attributes:
      label: Environment
      description: ОС і браузер
      value: " Windows 11, Google Chrome"
    validations:
      required: true
  - type: dropdown
    id: severity
    attributes:
      label: Severity
      description: Серйозність дефекту
      options:
        - Blocker
        - Critical
        - Major
        - Minor
        - Trivial
    validations:
      required: true
  - type: dropdown
    id: priority
    attributes:
      label: Priority
      description: Пріоритет виправлення
      options:
        - High
        - Medium
        - Low
    validations:
      required: true
  - type: textarea
    id: attachment
    attributes:
      label: Attachment
      description:
