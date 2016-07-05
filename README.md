The `optprob` package
---
A LaTeX package that helps you denote optimization problems.

### Overview
The author says in the package documentation,
> the `optprob` package provides an elegant and semantic syntax for optimization problems.

See the full documentation for further information.

### Requirements
#### TeX system
* Engine: TeX, pdfTeX, XeTeX, LuaTeX, pTeX and upTeX
* Format: LaTeX2e

#### Packages to use `optprob.sty`
You need these packages to make use of the package:

* `mathtools`
* `pgfkeys`

#### Packages to compile `optprob.tex`
You need these packages to generate the documentation:

* `fontenc`
* `geometry`
* `hologo`
* `lmodern`
* `ltxdockit`
* `minted`
* `multicol`

### Installation
Clone the repository or download the archive from the [Releases](https://github.com/yudai-nkt/optprob/releases/latest).
Put each file in the following directories.

* `optprob.sty`: `$TEXMF/tex/latex/optprob/`
* `optprob.(pdf|tex)`: `$TEXMF/doc/latex/optprob/`

Don't forget to run `mktexlsr` if necessary.

### Contribution
Contributions are highly welcome. Feel free to report an [issue](https://github.com/yudai-nkt/optprob/issues) or create a [pull request](https://github.com/yudai-nkt/optprob/pulls).

### License
This package is distributed under the MIT License.
See [LICENSE.md](./LICENSE.md) for details.

---
Copyright (c) 2016 Yudai NAKATA
