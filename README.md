# Homebrew tap for bezzad

A [Homebrew](https://brew.sh) tap with casks for my apps.

## Downloader Desktop

A fast, cross-platform multi-connection download manager — see
[bezzad/Downloader.Desktop](https://github.com/bezzad/Downloader.Desktop).

```bash
brew tap bezzad/tap
brew install --cask downloader
```

> Not notarized yet. On first launch macOS may block it: right-click the app and
> choose **Open**, or run `xattr -dr com.apple.quarantine "$(brew --prefix)/bin/Downloader"`.
