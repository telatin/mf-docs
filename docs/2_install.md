---
sort: 2
permalink: /installation
---

# Installation

[Nextflow](https://nextflow.io/) allows to execute pipelines locally, in a cluster with a scheduler ([Slurm](https://slurm.schedmd.com/documentation.html), [PBS](https://www.openpbs.org/), ...) or on the cloud (AWS, Azure...).

The dependencies can be installed in a [Conda environment](https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html), or using a [Docker](https://www.docker.com/) or [Singularity](https://apptainer.org/) container.

## Prerequisites

The pipeline requires:

* A set of dependencies (Conda or Singularity)
* A Linux system capable of performing *de novo* assemblies (a single local machine or an HPC cluster)
* A set of databases (installable with a script provided in the repository)

## Installation with Conda in a local machine

:bulb: Ensure that Miniconda is already installed in the system.

1. Clone the repository:
   
```bash
git clone https://github.com/MattiaPandolfoVR/MetaPhage
```

2. Download the database (the default location can be `db/` inside the repository)

```bash

```

## Installation in a cluster using Singularity

:bulb: Ensure that Singularity is already installed in the system.

1. Clone the repository:
   
```bash
git clone https://github.com/MattiaPandolfoVR/MetaPhage
```