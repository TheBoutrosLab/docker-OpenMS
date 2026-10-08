# Changelog

All notable changes to the OpenMS Docker image.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/).

This project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]

### Added

- Add an OpenMS 2.6.0 image built with Miniforge 26.1.1-2 and Ubuntu 24.04.
- Publish the image for `linux/amd64`, the architecture available for OpenMS
  2.6.0 in Bioconda.
- Install the core Bioconda `openms` package without the optional
  `openms-thirdparty` tool collection.
- Configure publication to the Boutros Lab GitHub Container Registry.
