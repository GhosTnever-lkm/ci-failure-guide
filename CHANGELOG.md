# Changelog

## v1.0.3

- Add a dependency-free `scripts/validate.mjs` check for VERSION, plugin manifest, skill frontmatter, marketplace entry, README install pin, CHANGELOG entry, and full MIT license text.
- Add 7 Node.js tests for the validator, including version drift, missing or escaping skill paths, invalid JSON, and truncated licenses.
- Add CI on Ubuntu and Windows (Node.js 22) for pushes, tags, and pull requests, using `node --test` auto-discovery so it works on Node.js 20 and 22.
- Pin the marketplace installation instructions to v1.0.3.

## v1.0.2

- Pin the marketplace installation instructions to the matching v1.0.2 release.

## v1.0.1

- Restore the complete standard MIT license, including its limitation-of-liability clause.
- Pin the installation instructions to the v1.0.1 release.

## v1.0.0

- Initial release of the CI Failure Guide Codex plugin.
