name: RFC Proposal
title: "[RFC] "
description: Propose a new RFC for the TWIN Foundation
labels: rfc, proposal
body:

- type: markdown
  attributes:
  value: |
  Thank you for proposing an RFC! Please fill out the following sections.
- type: input
  id: title
  attributes:
  label: Title
  description: Short, descriptive title for the RFC
  validations:
  required: true
- type: textarea
  id: summary
  attributes:
  label: Summary
  description: A short summary of the proposal
  validations:
  required: true
- type: textarea
  id: motivation
  attributes:
  label: Motivation
  description: Why is this change necessary? What problem does it solve?
  validations:
  required: true
- type: textarea
  id: design
  attributes:
  label: Detailed Design
  description: Describe the proposed change in detail
  validations:
  required: true
- type: textarea
  id: drawbacks
  attributes:
  label: Drawbacks
  description: What are the potential downsides?
  validations:
  required: false
- type: textarea
  id: alternatives
  attributes:
  label: Alternatives
  description: What other approaches were considered?
  validations:
  required: false
- type: textarea
  id: adoption
  attributes:
  label: Adoption Strategy
  description: How will this proposal be adopted?
  validations:
  required: false
- type: textarea
  id: unresolved
  attributes:
  label: Unresolved Questions
  description: What parts are still open for discussion?
  validations:
  required: false
