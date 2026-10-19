description: Respond to a workshop issue with a bounded triage comment.
on:
  slash_command:
    name: issue-helper
safe-outputs:
  add-comment:
    max: 1
  create-issue:
    title-prefix: "[follow-up] "
    max: 1