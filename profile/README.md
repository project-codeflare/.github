# Project Codeflare

## About

Project Codeflare provides a simple, user-friendly abstraction for developing, resource-scaling, queuing, and management of distributed AI/ML and Python workloads on OpenShift Container Platform.

Project Codeflare consists of the following components:

**[CodeFlare SDK][codeflare-sdk] and [CLI][codeflare-cli]** to define, develop, and control remote distributed compute jobs and infrastructure from either a python-based environment or command-line interface

**[Multi-Cluster Application Dispatcher (MCAD)][mcad]** for queueing, resource quotas, and management of batch jobs

**[Instascale][instascale]** for on-demand resource scaling of an OpenShift cluster

**[Codeflare Operator][codeflare-operator]** for automating deployment and configuration of the Project Codeflare stack

## Project Codeflare Ecosystem

In addition to running standalone, Project Codeflare is deployed as part of and integrated with the [Open Data Hub][distributed-workloads].

## Quick Start

To get started using the Project Codeflare stack, try this [end-to-end example][quickstart]!

For more basic walk-throughs and in-depth tutorials, see our [demo notebooks][demos]!

## Development

See more details in any of the component repos linked above, or get started by taking a look at the [project board][board] for open tasks/issues!

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
[demos]: https://github.com/project-codeflare/codeflare-sdk/tree/main/demo-notebooks/guided-demos
[board]: https://github.com/orgs/project-codeflare/projects/8
