# darpanzope/homebrew-tap

Homebrew tap for [compliancekit](https://github.com/darpanzope/compliancekit).

## Install

```sh
brew install darpanzope/tap/compliancekit
```

## How this tap works

Formulas under `Formula/` are pushed automatically by the goreleaser
pipeline in [`darpanzope/compliancekit`](https://github.com/darpanzope/compliancekit)
on every `v*.*.*` tag. Do not edit them by hand -- changes get
overwritten on the next release.

To bump the formula to a newer compliancekit version, tag the main
repo, not this one.
