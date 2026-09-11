# .github

Organisation level defaults for [teralisdev](https://github.com/teralisdev).

| Path | What it does |
|---|---|
| `profile/README.md` | The page shown at github.com/teralisdev. This repo has to stay public for it to render, which is the only reason it is |
| `.github/ISSUE_TEMPLATE/` | Issue forms inherited by every repo that has none of its own |
| `.github/pull_request_template.md` | Default PR body |
| `CONTRIBUTING.md` | Inherited by every repo without its own |
| `assets/` | The mark, referenced by absolute raw URL from `profile/README.md` because GitHub does not resolve relative image paths there |

Nothing here describes infrastructure, and nothing here should. That rule is in
the teralis repo's `AGENTS.md` and it applies to this public repo doubly.
