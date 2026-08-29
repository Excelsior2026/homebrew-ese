# homebrew-ese

_A BagelTech project._

Homebrew tap for Ensemble Software Engineering.

Install:

```bash
brew tap Excelsior2026/ese https://github.com/Excelsior2026/homebrew-ese
brew install ese-cli
```

To install the latest code from `main` instead of the latest published package:

```bash
brew reinstall --HEAD ese-cli
```

If you previously installed the older `excelsior2026/tap/ese` formula, remove or unlink it first:

```bash
brew uninstall ese
```

Optional local model runtime:

```bash
brew install ollama
brew services start ollama
```
