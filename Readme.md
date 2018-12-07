# Visidata Singularity Image

<!-- TOC depthFrom:2 -->

- [Building the Package](#building-the-package)
- [Usage](#usage)
- [Packages not included](#packages-not-included)

<!-- /TOC -->

[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/1985)

Provides [Visidata](https://github.com/saulpw/visidata) using Debian Stretch as Singularity Image.

## Building the Package

```bash
sudo singularity build visidata.simg Singularity
```

## Usage

```bash
singularity exec shub://paulklemm/visidata-singularity vd <yourfile>
```

## Packages not included

Due to installation errors, not all dependencies for Visidata are included. Not included are the following:

- `xpkt`
- `savReaderWriter`
