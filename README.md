# Name Runner releases

Public release assets for [Name Runner](https://namerunner.app): installers, `latest.json`, and updater signatures.

- **No application source** lives here. The private development repository builds the app; GitHub Actions uploads drafts to this repository.
- The in-app updater reads:  
  `https://github.com/uvcat-coder/name-runner-releases/releases/latest/download/latest.json`
- Releases are created as **drafts** first, then published by hand. Tags are never marked as GitHub prereleases (including `-beta.N`), so `releases/latest` stays usable.
- Support: `support@namerunner.app` (not Issues on this repository).
