---
name: "\U0001F4D6 User Story"
about: Template for creating a well-structured user story
title: ''
labels: ''
assignees: ''

---

title: "[Story]: "
labels: ["user-story"]
body:
  - type: markdown
    attributes:
      value: |
        ## User Story
        Please fill in all required fields to ensure consistent quality.

  - type: textarea
    id: story
    attributes:
      label: User Story
      description: Describe the story in As a / I want to / So that format
      placeholder: |
        As a [type of user],
        I want to [perform some action],
        So that [achieve some outcome].
    validations:
      required: true

  - type: textarea
    id: acceptance-criteria
    attributes:
      label: Acceptance Criteria
      description: List the conditions that must be met for this story to be considered complete
      placeholder: |
        - [ ] Criteria 1
        - [ ] Criteria 2
        - [ ] Criteria 3
    validations:
      required: true

  - type: textarea
    id: definition-of-ready
    attributes:
      label: Definition of Ready
      description: Confirm readiness before taking into sprint
      value: |
        - [ ] Acceptance criteria are clear
        - [ ] User story is estimated
        - [ ] Dependencies identified
        - [ ] Design/mockups attached (if needed)
    validations:
      required: true

  - type: textarea
    id: definition-of-done
    attributes:
      label: Definition of Done
      description: Confirm completion criteria
      value: |
        - [ ] Code review completed
        - [ ] Tests written and passing
        - [ ] Documentation updated (if needed)
    validations:
      required: true

  - type: textarea
    id: notes
    attributes:
      label: Additional Notes
      description: Any extra context, links, mockups, or technical details
      placeholder: Add any additional information here...
    validations:
      required: false
