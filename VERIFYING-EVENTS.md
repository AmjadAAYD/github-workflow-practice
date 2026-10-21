# Verify workflow events

Use the GitHub CLI to check a pull request separately from profile awards:

```powershell
gh pr view 1 --repo AmjadAAYD/github-workflow-practice --json state,mergedAt,mergeCommit
```

A merged state and a merge commit establish the PR outcome. They do not establish a badge award.

For Discussions, verify the accepted answer's author and the account that selected it. In this sandbox, Discussions #2 and #3 were opened by Amjad-AAYD and their answers by AmjadAAYD were selected by Amjad-AAYD.

The two accounts belong to the same person. This repository is a disclosed workflow and achievement-eligibility exercise.

Finally, inspect the main profile's Achievements section. Galaxy Brain was visibly present after the two public Q&A exercises on 2026-10-21; Pair Extraordinaire was not yet present when this note was prepared.
