# Contributing to Discord-Dashboard

Thanks for helping out. This guide applies to every repository in the
Discord-Dashboard organization. A repository can add its own CONTRIBUTING.md
with setup steps; Core's covers the monorepo and releases.

## Finding something to work on

- Planned work lives on the [Discord-Dashboard v3 project](https://github.com/orgs/Discord-Dashboard/projects/2).
  Each item has an area, a priority and a size.
- Issues labelled `good first issue` are small and self-contained.
  `help wanted` means we would welcome a pull request.
- Comment on an issue before you start, so nobody does the same work twice.
  Items marked `needs decision` wait on the maintainers; ask before building them.

## Pull requests

- Branch from the repository's default branch (for Core v3 work, `v3`).
- Keep each pull request focused on one change, and link the issue with
  `Closes #123`.
- Add or update tests where it makes sense, and run the repository's checks
  before you push.
- Mark breaking changes clearly in the description and the changelog.
- CI must be green before a pull request is merged.

## Reporting bugs and ideas

Use the issue forms. They ask for the package version, platform and mode,
which saves a round of questions. Security problems are the exception: see
[SECURITY.md](SECURITY.md).

## Licensing

The open source packages are MIT licensed, and contributions are accepted
under the same license. The private `pro` and `license-server` repositories
are not open to outside contributions.

## Conduct

Everyone taking part is expected to follow the
[code of conduct](CODE_OF_CONDUCT.md).
