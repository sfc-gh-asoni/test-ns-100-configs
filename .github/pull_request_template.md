# Overview

<!--
Why is this review being requested?  The full details should be in the JIRA, but the review should focus on the fix/change being implemented.
If there are multiple steps in the Jira, which step is this?
-->

## Pre-review checklist
- [ ] I attest that this change meets the bar for low risk without security requirements as defined in the [Accelerated Risk Assessment Criteria](https://developer-handbook.c1.us-west-2.aws-dev.app.snowflake.com/docs/reference/security-review/accelerated-risk-assessment/#eligibility) and I have taken the [Risk Assessment Training in Mindtickle](https://snowflake.mindtickle.com/#/course/1371570621740898697?series=1195098750318696960).
    - Checking this checkbox is mandatory if using the [Accelerated Risk Assessment](https://developer-handbook.c1.us-west-2.aws-dev.app.snowflake.com/docs/reference/security-review/accelerated-risk-assessment/) to risk assess the changes in this Pull Request.
    - If this change does not meet the bar for low risk without security requirements (as confirmed by the peer reviewers of this pull request) then a [formal Risk Assessment](https://developer-handbook.c1.us-west-2.aws-dev.app.snowflake.com/docs/reference/security-review/risk-assessment/) must be completed. Please note that a formal Risk Assessment will require you to spend extra time performing a security review for this change. Please account for this extra time earlier rather than later to avoid unnecessary delays in the release process.
- [ ] This change is TEST-ONLY
- [ ] This change has code coverage for the new code added
