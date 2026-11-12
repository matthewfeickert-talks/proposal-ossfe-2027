# proposal-ossfe-2027

Talk proposal for Open Source Software for Fusion Energy (OSSFE) 2027

## Area

Software Engineering

## Type

Talk

## Title

Maintaining the forge: Distributing the fusion energy software ecosystem on conda-forge

## Abstract

Scientific researchers need robust and reproducible software environments that run across heterogeneous computing platforms.
As the fusion energy software community grows and matures, and as AI/ML tools and techniques become a standard part of a researcher's toolbox, reliable multi-platform distribution of complex, often hardware-accelerated, software becomes essential.
With modern technological improvements and new open source tools, such as [rattler-build](https://rattler-build.prefix.dev/latest/) and [Pixi](https://pixi.prefix.dev/), the [conda-forge](https://conda-forge.org/) software ecosystem now provides pathways to accelerating scientific research across the broader fusion energy open source community.

Drawing on lessons from supporting multi-platform builds for the [OpenMC](https://github.com/conda-forge/openmc-feedstock), [DAGMC](https://github.com/conda-forge/dagmc-feedstock), [SFINCS](https://github.com/conda-forge/sfincs-feedstock), and [Trinity3D](https://github.com/conda-forge/t3d-feedstock) conda-forge feedstocks, as well as all of the software in the [Driftless Star project](https://github.com/driftless-star/driftless-star) ecosystem, this talk will give a practical overview of maintaining fusion energy software on conda-forge.
This will include the benefits of providing binary distributions of scientific software for multiple computing platforms (e.g., Linux and macOS on x86_64 and ARM64), the challenges and boons of building fusion energy software as conda packages on conda-forge, and a pragmatic overview of the conda-forge ecosystem aimed at both scientific researchers and software maintainers.
The talk will also cover future opportunities for broader collaboration and coordination across the community and routes towards improved distribution of hardware-accelerated software.
Attendees will learn how to get their software onto conda-forge and what it takes to maintain it there.

## Notes

Matthew Feickert is a maintainer of the [staged-recipes](https://github.com/conda-forge/staged-recipes) repository for the conda-forge ecosystem and has expertise in research software design and building in multiple scientific domains. Beyond the fusion energy research community, Matthew maintains conda-forge distributions for over 100 software projects for the high energy physics community as part of the [HEP Packaging Coordination community project](https://hep-packaging-coordination.github.io/.github/).
