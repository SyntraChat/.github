# Contributing

Use focused commits and a pull request describing the user-visible change, evidence,
and remaining limitations. Follow the affected repository's development guide. Run
Rust formatting, Clippy with warnings denied and tests; frontend changes also require
typecheck, lint, component tests and a production frontend build.

Never include real account credentials, browser profiles, tokens or signing keys.
Never expose native IPC to remote messaging pages. New dependencies need a reason,
license review and vulnerability audit. Test platform-specific behavior on that platform.

Use Conventional Commit prefixes (feat, fix, docs, test, ci, refactor). Record changes
under Unreleased in CHANGELOG.md, then move them to a SemVer release with its date.
Breaking metadata/release contract changes need an explicit schema version and migration.
No automatic stable releases from main. Required checks and signed artifact verification
must pass before publishing; prereleases must be marked accordingly.
