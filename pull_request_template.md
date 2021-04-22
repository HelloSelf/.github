Fixes [Jira issue: HSP21-XXX](https://helloself.atlassian.net/browse/HSP21-XXX)

### Please label your commit using [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/)

i.e.
fix: HSP21-123 Buttons displaying as lime green
feat: HSP21-123 Changed all buttons to hot pink

# Description: What was changed and why?

Please include a summary of the change and which issue is fixed. Please also include relevant motivation and context. List any dependencies that are required for this change.

## Type of change

Please delete options that are not relevant.

-   [ ] Bug fix (non-breaking change which fixes an issue)
-   [ ] New feature (non-breaking change which adds functionality)
-   [ ] Breaking change (fix or feature that would cause existing functionality to not work as expected)
-   [ ] This change requires a documentation update

# How Has This Been Tested?

Please describe the tests that you ran to verify your changes. Provide instructions so we can reproduce.

-   [ ] Test A
-   [ ] Test B

# Front-end Checklist:

-   [ ] Are form validation errors correct?
-   [ ] Are API failure states handled?
-   [ ] Builds without warnings
-   [ ] Are there any console.log() in the code?
-   [ ] Does `yarn audit` flag any security issues?
-   [ ] Does the PR describe Acceptance Criteria? And does this ticket?
-   [ ] Appropriate tests?

# Back-end Checklist:

-   [ ] Is all response data tagged with appropriate permissions?
-   [ ] Do new endpoints make the correct permissions checks?
-   [ ] Does the PR describe Acceptance Criteria? And does this ticket?
-   [ ] New endpoints have been documented
-   [ ] Unit tests covering logic which could cause code to fail, especially when failure could go undetected.
-   [ ] Integration tests where appropriate
