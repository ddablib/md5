# MD5 Message Digest Unit

## Description

This unit contains an implementation of the MD5 message digest algorithm. It is implemented as a Delphi Class named _TPJMD5_.

The code is developed from scratch based on the algorithm presented in [RFC 1321](https://www.rfc-editor.org/rfc/rfc1321.html). Portions of the code are translated from the reference C code supplied in the RFC. However the code is not a literal translation into Pascal from the reference code.

The algorithm and reference code are copyright © 1991-2, RSA Data Security, Inc. Created 1991. All rights reserved.

For full details please see the [online documentation](https://delphidabbler.com/url/md5-docs).

## Compatibility

The unit requires Delphi 2009 and later. It has been tested with each version of Delphi 2009 to XE4.

Both the Delphi 32 bit and 64 bit Windows compilers are supported.

The code is compatible with VCL and FireMonkey 2 applications.

## Installation

The MD5 Message Digest Unit, documentation and test suite are supplied in a zip file. Before installing you need to extract all the files, preserving the directory structure. The following files will be extracted:

* **`PJMD5.pas`** – The source code.
* `README.md` – The unit's read-me file.
* `CHANGELOG.md` – The unit's change log.
* `Documentation.URL` – Short-cut to the online documentation.
* `LICENSE` – The project's license.
* `MPL-2.txt` – Mozilla Public License v2.0.
* `MD5-Notice.txt` – MD5 algorithm licensing notice.

In addition to the above files you will find the _DUnit_ tests for `PJMD5.pas` in the `Test` sub-directory.

There are four possible ways to use the unit.

1. The simplest way is to add `PJMD5.pas` to your projects as you need it.
2. To make the unit easier to re-use you can either copy it to a folder on your Delphi search path, or add the folder where you extracted the unit to the Delphi Search path. You then simply use the unit as required without needing to add it to your project.
3. For maximum portability you can add the unit to a Delphi 32 bit or 64 bit Windows package. If you need help doing this [see here](https://delphidabbler.com/url/install-comp).
4. If you use Git you can add the [`ddablib/md5`](https://github.com/ddablib/md5) GitHub repository as a Git submodule and add it to your project. Obviously, it's safer if you fork the repo and use your copy, just in case `ddablib/md5` ever goes away.

## Update History

A complete change log is provided in [`CHANGELOG.md`](https://github.com/ddablib/md5/blob/main/CHANGELOG.md) that is included in the download.

## License and Acknowledgements

Please see the file [`LICENSE`](https://raw.githubusercontent.com/ddablib/md5/main/LICENSE) for details.

## Bugs and Feature Requests

Bugs can be reported or new features requested via the project's [Issue Tracker](https://github.com/ddablib/md5/issues). A GitHub account is required.

Please check if an issue has already been created for a similar report or request. If so then please add a comment containing as much information as you can to the existing issue, or if you've nothing to add, just add a :+1: (`:+1:`) comment. If there is no suitable existing issue then please add a new issue and give as much information as possible.

## About the Author

I'm Peter Johnson – a hobbyist programmer living in Ceredigion in West Wales, UK, writing mainly in Delphi. My programs and other library code are available from: [https://delphidabbler.com/](https://delphidabbler.com/).

This document is copyright © 2010-2022, [P D Johnson](https://gravatar.com/delphidabbler).
