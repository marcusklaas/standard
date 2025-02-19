# Standard for Public Code

![version 0.1.3](https://img.shields.io/badge/version-0.1.3-red.svg)

Request for contributions

We believe public policy and software should be inclusive, usable, open, legible, accountable, accessible and sustainable. This means we need a new way of designing, developing and procuring both the source code and policy documentation.

This standard sets a quality level for codebases that meets the needs of public organizations, institutions and administrations as well as other critical infrastructural services.

The standard lives at [standard.publiccode.net](https://standard.publiccode.net/), and for an overview of all content see [`index.md`](index.md).

## Help improve this standard

We are looking for people like you to [contribute](CONTRIBUTING.md) to this project by suggesting improvements and helping develop it. 😊 Get started by reading our [contributors guide](CONTRIBUTING.md). Since it is such a core document we will accept contribution when they add significant value. We've described how we govern the standard in the [governance statement](GOVERNANCE.md).

Please note that this project is released with a [contributor code of conduct](CODE_OF_CONDUCT.md). By participating in this project you agree to abide by its terms. Please be lovely to all other community members.

## Preview, build and deploy

The repository builds to a static site deployed at [standard.publiccode.net](https://standard.publiccode.net/). It is built with [GitHub pages](https://pages.github.com) and [Jekyll](https://jekyllrb.com/).

See the scripts in the `script` folder.

## Generating a PDF out of the document

Using [Weasyprint](https://weasyprint.org/) the file `print.html` can be converted to a nice looking PDF.

```bash
weasyprint http://localhost:4000/print.html standard.pdf
```

## Releasing a new version

1. Create a release branch
2. Update the new release
    - [ ] Update version number
    - [ ] Update release log
    - [ ] Create new cover for print
    - [ ] Create new cover for web PDF
    - [ ] Generate new PDF of the document
    - [ ] Create PDF with Illustrations pasted in
    - [ ] Create PDF for GitHub release with front and back cover included
3. Send the files for print to the printer
    - [ ] Cover file
    - [ ] Inside pages PDF
4. Create GitHub release with the release notes and version number

## license

© [The authors and contributors](AUTHORS.md)

licensed under the CC-0, including all illustrations and documentation. This means anyone can do anything with it. If you contribute you also grant these rights to others.
You can read more about how to help in the [contributing guide](CONTRIBUTING.md)
