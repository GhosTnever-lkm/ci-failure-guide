# CI Failure Guide

> Practical, evidence-backed triage for CI, build, and test failures.

## Install in Codex

Add this repository as a plugin marketplace, then install the plugin:

```powershell
codex plugin marketplace add GhosTnever-lkm/ci-failure-guide@v1.0.3
codex plugin add ci-failure-guide --marketplace ci-failure-guide
```

The marketplace source is pinned to `v1.0.3`, so installation uses the matching tagged plugin instead of whatever is currently on the default branch. Codex may ask you to restart or reload plugins before the skill becomes available.

## Use it

Start a Codex task that matches the skill's purpose. The plugin instructions live in `skills/` and are included in the marketplace source for inspection.

## Scope

This is a focused Codex skill. It has no external service, background process, or credential requirement. See the skill file for its workflow and limits.

## ☕ Support / Pro Version

CI Failure Guide is free and open source. There is no paid Pro edition at this time. You can support GhosTnever on [Boosty](https://boosty.to/azizazimov) or [Buy Me a Coffee](https://www.buymeacoffee.com/azizazimov8).

## License

MIT. See [LICENSE](LICENSE).

## Development

The repository includes a dependency-free consistency check (Node.js 20 or newer):

```sh
node scripts/validate.mjs   # VERSION, manifest, skills, marketplace, README pin, CHANGELOG, LICENSE
node --test test/           # validator tests
```

CI runs both commands on Ubuntu and Windows for every push, tag, and pull request.
