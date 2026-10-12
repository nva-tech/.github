# .github

Organization-wide defaults for nva-tech repositories.

`pull_request_template.md` is the default PR description. GitHub pre-fills it in every nva-tech repo that has no template of its own, and the dogfiles `pr-description` skill drafts PR bodies from it. A repo's own template replaces this one entirely, so repos keep no copy.

GitHub reads org defaults only from a public repo named `.github`, so this repo is public. Commit nothing here that can't be public, and change it through a reviewed PR.

Keep the facts line names stable. Agent tooling reads them, the `Risk` line among them, so renaming one needs a matching dogfiles change.
