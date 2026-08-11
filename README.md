# Homebrew tap for mac-stats

Apple Silicon menu-bar monitor (optional local AI). **Not** in the official Homebrew cask repo.

## Install

```bash
curl -fsSL https://raw.githubusercontent.com/raro42/mac-stats/main/install.sh | bash
```

Or with Homebrew 6+:

```bash
brew tap raro42/mac-stats
brew trust --cask raro42/mac-stats/mac-stats
brew install --cask mac-stats
```

Do **not** run only `brew install --cask mac-stats` — that looks in Homebrew’s core casks and fails with “No Cask with this name exists” (and may suggest unrelated `mac-sai`).

App repo: https://github.com/raro42/mac-stats
