# Project Codeflare

## About

Project Codeflare provides a simple, user-friendly abstraction for scaling, queuing and resource management of distributed AI/ML and Python workloads. On OpenShift Container Platform.

Project Codeflare consists of the following components:

**[CodeFlare SDK][codeflare-sdk] and [CLI][codeflare-cli]** to define and control remote distributed compute jobs and infrastructure from a python-based environment or terminal

**[Multi-Cluster Application Dispatcher (MCAD)][mcad]** for management of batch jobs

**[Instascale][instascale]** for on-demand scaling of a Kubernetes cluster

**[Codeflare Operator][codeflare-operator]** for automating deployment and configuration of the Project Codeflare stack

## Project Codeflare Ecosystem

In addition to running standalone, Project Codeflare is deployed as part of and integrated with the [Open Data Hub][distributed-workloads].

## Quick Start

To get started using the Project Codeflare stack, try this [end-to-end example][quickstart]! 

## Development

### Architecture

We attempt to document all architectural decisions in our [ADR documents][adr]. Start here to understand the architectural details of Project Codeflare.

### Getting Involved

Join our [Slack community][slack] to get involved or ask questions.

### License

Unless otherwise noted at a per-component level, this Project Codeflare is licensed under the Apache-2.0 License.

[codeflare-sdk]: https://github.com/project-codeflare/codeflare-sdk
[codeflare-cli]: https://github.com/project-codeflare/codeflare-cli
[mcad]: https://github.com/project-codeflare/multi-cluster-app-dispatcher
[instascale]: https://github.com/project-codeflare/instascale
[codeflare-operator]: https://github.com/project-codeflare/codeflare-operator
[distributed-workloads]: https://github.com/opendatahub-io/distributed-workloads
[quickstart]: https://github.com/opendatahub-io/distributed-workloads/blob/main/Quick-Start.md
[slack]: https://invite.playplay.io/invite?team_id=T04KQQBTDN3
[adr]: https://github.com/project-codeflare/adr