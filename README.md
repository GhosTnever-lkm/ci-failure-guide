# CI Failure Guide

> Trace a failed build or test to the smallest evidence-backed root cause and next step.

## Install

In Codex, add the [GhosTnever Codex Toolkit](https://github.com/GhosTnever-lkm/ghosTnever-codex-toolkit) marketplace, then install **CI Failure Guide**.

You can also clone this repository and add it as a local marketplace:

```text
codex plugin marketplace add .\path\to\ghosTnever-codex-toolkit
codex plugin add ci-failure-guide --marketplace ghosTnever-codex-toolkit
```

## Try it

- "Explain why this CI job failed and what to try next."
- "Find the first meaningful error in this build log."
- "Compare this failing test with the CI workflow setup."

## Scope

This plugin contains a focused Codex skill. It does not install external services or run background processes. Review repository guidance and user authorization before taking actions.

## License

MIT. See [LICENSE](LICENSE).

