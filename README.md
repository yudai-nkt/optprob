The `optprob` package
---
[![Build Status]( 	https://img.shields.io/travis/yudai-nkt/optprob/master.svg)](https://travis-ci.org/yudai-nkt/optprob)
[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](./LICENSE.md)

A LaTeX package that helps you denote optimization problems.

### Overview
The author says in the package documentation,
> the `optprob` package provides an elegant and semantic syntax for optimization problems.

See [the documentation](http://yudai-nkt.github.io/optprob/optprob.pdf) for further information.

### Requirements
#### TeX system
* Engine: TeX, pdfTeX, XeTeX, LuaTeX, pTeX and upTeX
* Format: LaTeX2e

#### Packages to use `optprob.sty`
You need these packages to make use of the package:

* `mathtools`
* `pgfopts`

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
Download the archive from the [Releases](https://github.com/yudai-nkt/optprob/releases/latest).
Unzip the archive in either `TEXMFLOCAL` or `TEXMFHOME`.

```sh
curl -O https://github.com/yudai-nkt/optprob/releases/download/v0.2.0/optprob.tds.zip
unzip optprob.tds.zip -d $(kpsewhich -var-value TEXMFHOME) # Use TEXMFLOCAL instead if you install there
```

Don't forget to run `mktexlsr` if necessary.

### Contribution
Contributions are highly welcome. Feel free to report an [issue](https://github.com/yudai-nkt/optprob/issues) or create a [pull request](https://github.com/yudai-nkt/optprob/pulls).

### License
This package is distributed under the MIT License.
See [LICENSE.md](./LICENSE.md) for details.

---
Copyright (c) 2016 Yudai NAKATA
