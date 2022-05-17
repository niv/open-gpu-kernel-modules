name: 🐞 Report Bug 🐞
description: Please do not ask questions, request features, or report confidential security issues here; read on below for all of those! Also, before submitting a new ticket, check if someone else may already have reported it. CONTRIBUTING.md is worth a read for the current guidelines.
labels: bug
body:
- type: input
  id: sw_driver_version
  attributes:
    label: NVIDIA OpenRM Driver version
    description: Which OpenRM driver version are you running?
  validations:
    required: true
