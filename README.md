# bibliomap-harvester

Monitors and harvests ezproxy log files for [bibliomap](https://github.com/ezpaarse-project/bibliomap) visualization.

## Architecture

<p align="center">
<img src="https://docs.google.com/drawings/d/1bkxEEBL1kLzH76dkIYFzspYHOVajDjQHCijU3mxJLnM/pub?w=694&h=519" />
</p>

## Prerequisites

  * Docker and docker-compose

## Installation and running

As a standalone script, bibliomap-harvester is not very usefull. Please have a look to [bibliomap](https://github.com/ezpaarse-project/bibliomap) docker-compose.yml to understand how it can be orchestrated with required modules: [bibliomap-enricher](https://github.com/ezpaarse-project/bibliomap-enricher) and [bibliomap-viewer](https://github.com/ezpaarse-project/bibliomap-viewer)

## Configuration

Env variable can be used to customize it:

  * BBH_...TODO...

Look at [config.json](hhttps://github.com/ezpaarse-project/bibliomap-harvester/blob/master/config.json) to see the default values.

## Developement

```
git clone git@github.com:ezpaarse-project/bibliomap-harvester.git
cd bibliomap-harvester
DEBUG=bibliomap* make run-debug
```

