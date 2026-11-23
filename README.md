# FeedGuard: public files

Files the FeedGuard app downloads. Nothing here is about any user.

- `rules/rules.json` and `rules/rules.json.sig`: detection rules, signed with FeedGuard's
  rule key. The app checks the signature and ignores anything not signed with it.
  Published from the main project with `gradlew :core:signRules` (dist/rules).
