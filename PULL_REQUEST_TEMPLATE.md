:mega: **Instructions**

- Begin with a **DRAFT** pull request.
- Follow _italicized instructions_ to add detail to assist the reviewers.
- Complete **Author's Checklist** items before requesting review.

---

### :pushpin: Change Summary

_AUTHOR: Describe the changes included in this pull request. Link to the associated [GitHub](https://docs.github.com/en/issues/tracking-your-work-with-issues/using-issues/linking-a-pull-request-to-an-issue#linking-a-pull-request-to-an-issue-using-a-keyword) or Jira issue(s)._

- see #1234
- Added the [...]
- Updated the [...]
- Fixed the [...]

### :pushpin: Author's Checklist

_AUTHOR: Complete the following tasks before marking the PR as **READY FOR REVIEW**._

- [ ] Complete a self-review of changes
- [ ] Unit tests have been created or updated and all pass locally
- [ ] The code is free of [new] lint errors and warnings
- [ ] Documentation has been updated as needed: README, /docs, code comments, JSDoc, etc.
- [ ] All CI/CD checks pass

### :pushpin Testing Instructions

_AUTHOR: Describe the process to verify and test the changes in this pull request. Include steps for both happy path and edge cases._

- [...Describe any setup required]

1. Go to [...]
2. Click on [...]
3. Verify that [...]

### :pushpin: Additional Information

_AUTHOR: Optionally, provide additional details, screenshots, screen recordings, or URLs that may assist the reviewer._

- [Screenshot or recording of the change in action]
- [Link to related documentation or design]
- [Any known limitations or future considerations]
- [Dependencies or related PRs]

---

### :mag: Reviewer's Checklist

_REVIEWERS: Complete the following tasks before approving the PR._

**Code Quality:**

- [ ] Code changes are clear, maintainable, and follow project conventions
- [ ] Error handling and edge cases are appropriately covered
- [ ] All unit tests pass and test coverage is adequate
- [ ] Integration tests (if applicable) pass
- [ ] Code is free of [new] lint errors and warnings

**Testing:**

- [ ] The fix or feature works as intended per the story description and acceptance criteria
- [ ] Tests have been executed locally per the steps outlined below
- [ ] No regressions detected in related functionality

**Security:**

- [ ] No security vulnerabilities or hardcoded sensitive data introduced
- [ ] No external dependencies added without team discussion

**Documentation:**

- [ ] Documentation has been updated as needed: README, /docs, code comments, etc.
