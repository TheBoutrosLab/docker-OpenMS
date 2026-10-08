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
| OpenMS | 3.5.0 |
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

docker-OpenMS is licensed under the GNU General Public License version 2. See
the file [LICENSE](LICENSE) for the terms of the GNU GPL license.

docker-OpenMS provides a containerized OpenMS runtime for LC-MS data analysis.

Copyright (C) 2026 Sanford Burnham Prebys Medical Discovery Institute
("Boutros Lab") All rights reserved.

This program is free software; you can redistribute it and/or modify it under
the terms of the GNU General Public License as published by the Free Software
Foundation; either version 2 of the License, or (at your option) any later
version.

This program is distributed in the hope that it will be useful, but WITHOUT
ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS
FOR A PARTICULAR PURPOSE. See the GNU General Public License for more details.
