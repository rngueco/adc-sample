---
description: "Instructions for writing git commit messages"
---
# Commit Message Guidelines

- The commit header should start with the Linear ticket ID and a short summary of the changes, or if a commit is not related to any Linear ticket ID then use `RIW-00` by default
- If there are more changes that cannot be summarized into a few words, then outline the changes in bullets after a new line below the commit header
    
## Commit Message Examples

### Single line commit message with Linear ticket ID

`RIW-10 update readme`

### Single line commit message without Linear ticket ID

`RIW-00 documentation cleanup`

### Multi-line commit message

```
RIW-12 create tmdb api wrapper

- updated readme with API documentation
- updated .env.sample
```
