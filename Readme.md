# Visidata Singularity Image

[![https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg](https://www.singularity-hub.org/static/img/hosted-singularity--hub-%23e32929.svg)](https://singularity-hub.org/collections/1985)

Provides [Visidata](https://github.com/saulpw/visidata) using Debian Stretch as Singularity Image.

## Building the Package

```bash
sudo singularity build visidata.simg Singularity
```

## Usage

```
singularity exec shub://paulklemm/visidata-singularity vd <yourfile>
```
