---
description: "Instructions for writing Pull Request title and description"
---

# Pull Request Guidelines

- The Pull Request title should start with the corresponding Linear ticket ID and a short summary of the changes
- The Pull Request description should include a list of changes made and any special instruction on how to test the changes if necessary
- Before opening a pull request, make sure that you are on a branch other than main

## PR Title and Description Example

### PR Title Example

`RIW-20: Replace custom TMDB wrapper with @tdanks2000/tmdb-wrapper package`

### PR Description Example

```md
This PR implements the replacement of our custom TMDB API wrapper with the @tdanks2000/tmdb-wrapper package.

## Changes Made

- Removed the existing TMDB API wrapper (/api/tmdb/route.ts)
- Installed @tdanks2000/tmdb-wrapper package
- Created a new TMDB service in src/services/tmdb.ts that:
  - Uses the package's TMDB class
  - Is configured with the existing TMDB access token
  - Includes comprehensive documentation and examples
  - Re-exports commonly used types

## Testing Done

- Verified package installation
- Confirmed environment variable compatibility
- Checked type exports and documentation

## Documentation Updates

The new service includes extensive documentation with examples for:

- Getting popular movies and TV shows
- Searching for content
- Getting movie/show details
- Getting movie credits
- Getting trending content

## Dependencies

This change blocks RIW-17 (Create TMDB API Service)

## Additional Notes

The existing TMDB access token format is compatible with the new package, so no environment variable changes were needed.
```
