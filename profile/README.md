# The Gamine project <a href="https://github.com/gamineproject"><img align="right" id="icon-gamine" src="https://raw.githubusercontent.com/gamineproject/.github/main/favicon.png"></img></a>
Group of contributors of the Gamine runtime and `gpm`.

## FAQ
### *1*:
**A**: How do i use Gamine properly?

**B**: Gamine is a JS runtime, so you simply run `gam index.js`.

### *2*:

**A**: How do i use `gpm`?

**B**: `gpm` is a package manager with the acronym of `gamine package manager`, so basically npm but better.

`gpm` is written in C++ and not in JS, so it might have some more I/O operations.
`gpm` uses `libcurl` (from the curl command) to get packages, while also `gpm` uses `libarchive` to unzip TARs.
