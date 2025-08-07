---
mode: "agent"
model: Claude Sonnet 3.5
tools: ['codebase', 'editFiles', 'runCommands', 'push_files', 'update_pull_request', 'codacy_list_pull_request_issues']
description: "Resolve Codacy issues in this pull request"
---
# Resolve Issues

Your goal is to resolve the issues found by Codacy in pull request ${input:pullRequestNumber}. If the pull request number is not given, prompt the user for a pull request number and fetch the existing Codacy issues in that pull request.

## Things to remember

- Use the codacy tool to get context about existing issues in the codebase. Do not analyze the codebase yourself.
- Make the necessary changes in the relevant files, but do not push your changes yet. Let me review your changes before pushing anything to the remote or upstream.
