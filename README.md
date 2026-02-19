# homebrew-casedev

Official Homebrew tap for the [case.dev CLI](https://github.com/CaseMark/casedev-cli).

## Install with Homebrew (cask only)

```bash
brew tap CaseMark/casedev
brew install --cask CaseMark/casedev/casedev
```

## Upgrade

```bash
brew update
brew upgrade --cask CaseMark/casedev/casedev
```

## Verify installation

```bash
casedev --version
```

## Download without Homebrew

Download prebuilt binaries from the CLI releases:

https://github.com/CaseMark/casedev-cli/releases

Example (macOS arm64):

```bash
gh release download v0.1.1 --repo CaseMark/casedev-cli --pattern 'casedev_0.1.1_macos_arm64.zip'
unzip casedev_0.1.1_macos_arm64.zip
chmod +x casedev
./casedev --version
```

## How updates work

`Casks/casedev.rb` is auto-generated and pushed by the `Publish Release` workflow in `CaseMark/casedev-cli` via GoReleaser. Do not edit it manually.
