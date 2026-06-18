# fianulabs/homebrew-tap

Homebrew tap for the [Fianu](https://fianu.io) CLI.

```sh
brew install fianulabs/tap/fianu
fianu version
```

The `fianu` formula and its binary release assets are published automatically by
the `fianulabs/cli` CI pipeline (`publish-homebrew` job → `repository_dispatch` →
`update-formula` workflow here). Do not edit `Formula/fianu.rb` by hand.
