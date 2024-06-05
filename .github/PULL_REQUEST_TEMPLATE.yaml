name: 🛠️ Pull Request
description: Submit your code changes for review

body:
- type: markdown
  atttributes:
    values: >
      ### What changes were proposed in this pull request?
      <!--
      Please clarify what changes you are proposing. The purpose of this section is to outline the changes and how this PR fixes the issue. 
      If possible, please consider writing useful notes for better and faster reviews in your PR. See the examples below.
        1. If you refactor some codes with changing classes, showing the class hierarchy will help reviewers.
        2. If you fix some SQL features, you can provide some references of other DBMSes.
        3. If there is design documentation, please add the link.
        4. If there is a discussion in the mailing list, please add the link.
      -->


      ### Why are the changes needed?
      <!--
      Please clarify why the changes are needed. For instance,
        1. If you propose a new API, clarify the use case for a new API.
        2. If you fix a bug, you can clarify why it is a bug.
      -->

- type: markdown
  attributes:
    value: >
      The core Triton team is small, and we appreciate your contributions!
      To help us review your code more efficiently, please include this checklist in your PR description if you are a new contributor (less than 3 PRs merged).
- type: checkboxes
  attributes:
    label: 🗸 Checklist
    description: Please replace `[ ]` with `[x]` to check items.
    options:
      - label: "I am not making a trivial change, such as fixing a typo in a comment."
        required: true
      - label: "I have written a PR description following these [rules](https://cbea.ms/git-commit/#why-not-how)."
        required: true
      - label: "I have used an LLM to copyedit my PR description and code comments."
        required: true
      - label: "I have run `pre-commit run --from-ref origin/main --to-ref HEAD`."
        required: true
- type: dropdown
  attributes:
    label: 🔍 Tests
    description: Select one of the following options for adding tests.
    options:
      - label: "I have added tests."
        description: "/test for `lit` tests /unittest for C++ tests /python/test for end-to-end tests"
      - label: "This PR does not need a test because `FILL THIS IN`."
- type: dropdown
  attributes:
    label: 🧪 Lit Tests
    description: Select one of the following options regarding `lit` tests.
    options:
      - label: "I have not added any `lit` tests."
      - label: "The `lit` tests I have added are minimal and contain only the necessary instructions to exercise the bug."
- type: textarea
  attributes:
    label: Additional context
    description: >
      Add any other context or information that might be helpful for reviewing your pull request.
  validations:
    required: true
- type: markdown
  attributes:
    value: >
      Thanks for contributing! 🎉
