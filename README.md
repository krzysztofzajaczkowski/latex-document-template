[![LinkedIn][linkedin-shield-zajaczkowski]][linkedin-url-zajaczkowski] [![Download document](https://img.shields.io/badge/artifact-download%20document-blue?logo=files&logoColor=white)
](https://krzysztofzajaczkowski.github.io/git-artifacts/#/artifacts/krzysztofzajaczkowski/latex-document-template/master/Document)


# LaTeX document template
This repository is a template for creating a document using LaTeX. Stub document shows how sections could be divided into separate files and compiled. As a result, images and text can be semantically separated and/or grouped. Apart from more comprehensible and organized structure, this solution makes it easier to cooperate and promotes asynchronous, simultaneous work across the team. Thanks to GitHub, version control and history are available throughout development and ready, compiled document is easy to access through CI/CD build.

## CI/CD
Every time changes are pushed to origin or pull request is created, build workflow is ran using GitHub Actions. `build` job produces an artifact (document compiled as PDF file) that is published to the repository. All runs (and their artifacts) are available for inspection in `Actions` tab. Badge on top of [README.md](https://github.com/krzysztofzajaczkowski/latex-document-template/blob/master/README.md) file downloads latest artifact from master branch.

# How to use
* Create new repository using this template
* Update links in [README.md](https://github.com/krzysztofzajaczkowski/latex-document-template/blob/master/README.md) file
* Compile`document.tex` to create PDF document that contains all chapters and meta.

# Author
Krzysztof Zajączkowski - [krzysztof.m.zajaczkowski@gmail.com](mailto:krzysztof.m.zajaczkowski@gmail.com)

[linkedin-shield-zajaczkowski]: https://img.shields.io/badge/LinkedIn-Zajączkowski-blue?logo=linkedin
[linkedin-url-zajaczkowski]: https://www.linkedin.com/in/krzysztof-m-zajaczkowski/