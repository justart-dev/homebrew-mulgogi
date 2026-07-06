# homebrew-mulgogi

Homebrew tap for [mulgogi](https://github.com/justart-dev/mulgogi), a fishing game in your terminal.

## Install

```bash
brew tap justart-dev/mulgogi
brew install mulgogi
mulgogi
```

## Updating the formula after a PyPI release

```bash
pip install homebrew-pypi-poet
poet mulgogi
```

Copy the generated resources into `Formula/mulgogi.rb`, update the `url` and `sha256`, and push.
