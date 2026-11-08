
# Contributing to Skylark

## Agile Workflow

We use GitHub Issues to track development work.

- 1 story point = 4 estimated hours.
- No issue should exceed 2 story points.
- Sprint duration: 2 weeks.
- Each issue must have acceptance criteria.

## Branch Naming

Format:

`type/issue-number-short-description`

Types:
- `feat`: New functionality
- `fix`: Bug fixes
- `docs`: Documentation
- `test`: Tests
- `chore`: Tooling or maintenance
- `refactor`: Structural changes without behavior changes

Example:

`docs/issue-1-repository-conventions`

## Commit Messages

Use descriptive commits.

Examples:

`docs: add repository structure and contribution guide`

`feat: add trip creation form`

`fix: validate trip date ranges`

## Pull Requests

Every pull request must:

1. Link the associated GitHub issue.
2. Explain the change.
3. Describe how it was tested.
4. Pass applicable automated checks.
5. Receive review from at least one teammate before merging.

Use `Closes #123` in the PR description when the PR fully resolves that issue.

Do not push directly to `main` for normal development work.

## Definition of Done

- All acceptance criteria are satisfied.
- Changes are committed through a reviewed PR.
- Relevant lint, type checks, and automated tests pass.
- Errors and edge cases are handled.
- No secrets or credentials are committed.
- Documentation is updated where necessary.
- The completed behavior can be demonstrated.

## Environment and Security

Never commit `.env` files, API keys, tokens, or passwords.

Provide `.env.example` files with placeholder values when configuration is needed.

## Code Reviews

Reviewers should check correctness, readability, tests, security, and consistency with the issue requirements.

Request changes when acceptance criteria have not been met.
