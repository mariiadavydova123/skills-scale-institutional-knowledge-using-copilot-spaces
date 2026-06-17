# PR Checklist

A short checklist to help authors and reviewers validate a PR is ready to merge.

- Documentation
  - [ ] docs/ updated (or a clear reason why not)
  - [ ] Release notes or changelog updated if user-visible change
- Tests
  - [ ] Unit/integration tests added or existing tests updated
  - [ ] Test instructions included in PR or docs
- Quality
  - [ ] No large commented blocks of dead code
  - [ ] Linting and formatting passes
- Backwards compatibility & Migrations
  - [ ] Migration plan included (if schema/data changes)
  - [ ] Feature flags added if needed
- Security & Compliance
  - [ ] Security review required? (Yes/No) If yes, link to review ticket
  - [ ] Sensitive data handling considered
- Operations
  - [ ] Runbooks or support notes added (if relevant)
  - [ ] Rollback instructions included (if releasable change)

Use this checklist in tandem with the repository's PR template.
