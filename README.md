# My own tap for Homebrew Casks

[Homebrew](https://brew.sh/) is The Missing Package Manager for macOS (or Linux).

As Jonathan Chang — one of Homebrew maintainers — [said](https://jonathanchang.org/blog/maintain-your-own-homebrew-repository-with-binary-bottles/), "Homebrew does not package everything. Many things are too niche, specialized, or complicated for the Homebrew maintainers to build and distribute."

For example, they removed [Subsmarine](https://www.cocoawithchurros.com/subsmarine.php) because there were ["too few downloads"]](https://github.com/Homebrew/homebrew-cask/commit/19ad2b9e10417f95ccab12ee8031e2bea96ec13e).

That's why I created my own tap, right here.

## Add the tap

```bash
brew tap nhoizey/cask
```

## Install one of the available formula

```bash
brew cask install subsmarine
```

## Currently available

Look inside [the `Casks` folder](./Casks/).
