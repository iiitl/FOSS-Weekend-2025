# Maintainer Guide

## PR Point System

As a maintainer, you are responsible for evaluating and assigning points to Pull Requests (PRs) based on the following system:

### Base Points:
- **Mandatory PR Submission**: 5 pts
- **Easy Issue PR**: 10 pts
- **Medium Issue PR**: 20 pts
- **Hard Issue PR**: 30 pts
- **Valid Issue Raised**: 5 pts (If a contributor raises a valid issue, even if they don't submit a PR, they receive 5 points if the issue is valid)

### For Stundent-Hub, MessEase , SequriQuest only
- **As these repos has a proper future, and will be used by students so contributing to these will give additional special repo status points to the contributor**
- **Special Repository PR**: Up to 10 additional pts (Only on medium and hard issues)

### Quality Bonus (Up to 10 pts):
Additional points can be awarded based on PR quality:
- **PR Description**: 2 pts (Clear and informative description)
- **Quality of PR**: 4 pts (Well-structured, clean code, proper formatting, and follows best practices)
- **Commit Message**: 2 pts (Meaningful and concise commit messages)
- **Commit History is Clear**: 2 pts (No unnecessary commits, properly squashed commits when needed)

## Repositories
Repositories will be divided into two categories:
1. **Multiple PRs Allowed on a Single Issue**:
   - Multiple contributors can submit PRs for the same issue.
   - PRs will be closed after review, and points will be given accordingly.
   - **No assignment is required** in this type of repository.

2. **Single PR Per Issue**:
   - Only one PR is allowed per issue.
   - The PR will be merged after review, and points will be assigned.
   - The bot will be active here, and **assignment is required** for contributors to work on an issue.

## Issue Assignment System
- Contributors can assign themselves an issue by commenting `/assign`.
- To unassign an issue, contributors can comment `/unassign`.
- The time limit for completing an issue depends on its difficulty label:
  - **Easy Issue**: 1.5 hours
  - **Medium Issue**: 3 hours
  - **Hard Issue**: 5 hours
  - **No label**: Considered **Medium Issue** (3 hours)
- If the maintainer finds that a contributor has done good work and needs more time, they can extend the deadline by commenting `/extend-'time in hrs here'` (e.g., `/extend-2`).
- **Note**: Extend time only when necessary.

## Leaderboard System
- The leaderboard is maintained by tags.
- Once a PR is accepted, the maintainer **must** add a label in the format: `accepted-'points here'` (e.g., `accepted-30`).
- The label must be in **lowercase** so that the leaderboard bot can pick it up correctly.

## Maintainer Responsibilities:
1. **Review PRs Promptly**: Ensure PRs are reviewed in a timely manner.
2. **Provide Constructive Feedback**: If a PR needs improvement, leave clear and actionable feedback.
3. **Assign Points Fairly**: Use the point system above to evaluate contributions objectively.
4. **Enforce Contribution Guidelines**: Make sure contributors follow coding standards and project rules.
5. **Merge PRs Appropriately**: Ensure PRs are tested and meet quality standards before merging.
6. **Add the Acceptance Label**: Always tag accepted PRs with `accepted-'points here'` to update the leaderboard correctly.

## Additional Notes:
- If a PR does not meet minimum quality requirements, maintainers may request changes before assigning points.
- For edge cases, maintainers can discuss and decide on point allocation based on the overall effort involved.
- If a contributor disputes the points assigned, maintainers should review and justify their decision.

Maintainers play a crucial role in keeping the project organized and ensuring high-quality contributions. Thank you for your efforts in maintaining the repository!

## Setup Guidelines
- Ensure the repository has a proper **README** with a setup guide.
- If environment variables are needed, include a `.env.example` file to guide contributors on necessary configurations.

For further assistance, contact **FOSS-Wing@Axios**.
