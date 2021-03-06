---
# Edit theme's home layout instead if you wanna make some changes
# See: https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: home
---
# Apache Quickstep (Incubating)

Quickstep is a high performance database engine. We currently support a SQL interface with plans to support advanced machine learning operations.

Quickstep's design starts with an underlying relational kernel core. The key design philosophy is to ensure that these kernels - and compositions of these kernels - can exploit the full potential of the underlying hardware. We call this design principle running at *bare-metal speed*. Bare-metal means to fully exploit the latest hardware trends including large main memories, fast on-die CPU caches, highly parallel multi-core CPUs, and NVRAM storage technologies.

For the hardware available in the future, we aim to co-design hardware and software primitives that will allow the data processing kernels to work on increasing amounts of data economically - both from the raw performance perspective, and from the perspective of the energy consumed by the data processing kernels and the applications running on the platform.

## Getting Started
Quickstep is easy to get set up. It currently runs on a single node and supports a SQL front-end, and doesn't require tuning parameters. To get started, follow the [quickstart guide][start-guide].

## Community
Quickstep is an Apache (incubating) project. If you want to learn more about the community, follow the dev conversation at <dev@quickstep.incubator.apache.org>. Send a blank email to this address for subscribe instructions. You can also view the [mail archive][mail-archive].

## Roadmap

The current roadmap is to produce a platform that can run relational database applications using SQL as the interface. The longer-term roadmap is to cover a broader class of analytics.

## Blog

The link to our blog is [here](/blog).

[start-guide]: https://github.com/apache/incubator-quickstep/blob/master/README.md
[mail-archive]: https://www.mail-archive.com/dev@quickstep.incubator.apache.org/