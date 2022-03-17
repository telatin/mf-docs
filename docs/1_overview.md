---
sort: 1
permalink: /overview
---

# Overview

## What is it

A reads to report workflow for metavirome analysis:

* Raw reads cleanup and profiling with Kraken
* Assembly with SPAdes or Megahit (overview with MetaQuast)
* Phage mining with:
  * VirFinder
  * VirSorter
  * Phigaro
  * Vibrant
* Consensus (cd-hit) and backmapping (bowtie2), and quantification (bamtocov)
* Genefinding and viral taxonomy (vContact2)
* Comprehensive report

## Workflow manager

The workflow is written in [Nextflow](https://nextflow.io/), a DSL and task
orchestrator that allows the reproducible execution and scale up from:
* local execution (e.g. virtual machine)
* HPC (Slurm, PBS...)
* Cloud (Amazon, Google,...)

The dependencies can be easily installed, via:
* Docker
* Singularity
* Conda environment

## To get started

A complex pipeline requires a lot of dependencies and the appropriate resources 
to parallelize the execution of concurrent tasks.

[Nextflow](https://nextflow.io/) allows the user to have a custom configuration specifying how to execute the
tasks (locally, in a cluster, on the cloud) and where to find the packages (Singularity, Docker).

Finally, MetaPhage needs a set of databases that can be easily downloaded with a script provided 
in the repository.

## The workflow


![MetaPhage Schematics]({{ site.baseurl }}{% link imgs/workflow.svg %})


