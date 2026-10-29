# Homebrew Tap

Install [Osoko](https://github.com/lostmusician/osoko), a floating screenshot shelf for macOS:

```bash
brew install --cask lostmusician/tap/osoko
```

Requires Apple Silicon and macOS Sonoma (14) or later.

To update:

```bash
brew update
brew upgrade --cask osoko
```

## Maintenance

After publishing an Osoko release, run `scripts/update-cask.sh <version> /path/to/homebrew-tap/Casks/osoko.rb` from the Osoko source repository. The script hashes the published DMG. Commit and push the updated cask to this repository.

Report app issues at [lostmusician/osoko](https://github.com/lostmusician/osoko/issues).
