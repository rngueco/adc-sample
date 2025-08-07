---
mode: "agent"
model: Claude Sonnet 3.5
tools: ['codebase', 'changes', 'editFiles', 'findTestFiles', 'runCommands', 'create_pull_request', 'push_files', 'update_pull_request', 'context7', 'sequentialthinking', 'get_issue']
description: "Work on a Linear issue"
---
# Work on a Linear Issue

Your goal is to work on Linear issue ID ${input:issueId}. If the issue ID is not given, prompt the user then fetch the issue details from Linear.

## Things to Remember

- Make sure that the current git branch is branching off of the latest main branch
- If the current branch is not related to the Linear issue, then run a git command to create a new local branch for the feature before working on it
