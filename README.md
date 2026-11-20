# docker-OpenMS

Docker image for [OpenMS](https://www.openms.de/), an open-source platform for
LC-MS data management and analysis.

This image is maintained by the Boutros Lab and installs the OpenMS command-line
tools in a dedicated Miniforge/Conda environment on an Ubuntu runtime image. It
intentionally installs the Bioconda `openms` package without the optional
`openms-thirdparty` tool collection.

## Version

| Component | Version |
|-----------|---------|
| OpenMS | 3.6.0 |
| Miniforge | 26.1.1-2 |
| Ubuntu | 24.04 |

---

## Discussions

- [Issue tracker](https://github.com/TheBoutrosLab/docker-OpenMS/issues) to report errors and enhancement ideas.
- Discussions can take place in [docker-OpenMS Discussions](https://github.com/TheBoutrosLab/docker-OpenMS/discussions).
- [docker-OpenMS pull requests](https://github.com/TheBoutrosLab/docker-OpenMS/pulls) are also open for discussion.

## Contributors

Please see the list of [Contributors](https://github.com/TheBoutrosLab/docker-OpenMS/graphs/contributors) at GitHub.

## References

1. Röst HL, Sachsenberg T, Aiche S, et al. OpenMS: a flexible open-source software platform for mass spectrometry data analysis. *Nature Methods*. 2016;13:741-748. doi: [10.1038/nmeth.3959](https://doi.org/10.1038/nmeth.3959)
2. OpenMS project documentation: <https://openms.readthedocs.io/>

## License

Author: Chenghao Zhu

The code and container recipes in docker-OpenMS are licensed under the
BSD 3-Clause License (`BSD-3-Clause`). See [LICENSE](LICENSE) for the terms.

Bundled software retains its respective upstream license.

Copyright (C) 2026 Sanford Burnham Prebys Medical Discovery Institute ("Boutros Lab")
