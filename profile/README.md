# Project CodeFlare

## About

Project CodeFlare provides a simple, user-friendly abstraction for developing, resource-scaling, queuing, and management of distributed AI/ML and Python workloads, whilst maximising the utilization of accelerators and compute resources, on OpenShift Container Platform.

Project CodeFlare consists of the following components:

**[CodeFlare SDK][codeflare-sdk]** to define, develop, and control remote distributed compute jobs and infrastructure from either a python-based environment or command-line interface

**[AppWrapper][appwrapper]** a flexible and workload-agnostic mechanism to enable Kueue to manage a group of Kubernetes resources as a single logical unit and to provide an additional level of automatic fault detection and recovery

**[CodeFlare Operator][codeflare-operator]** for automating deployment and configuration of the Project CodeFlare stack

## Project CodeFlare Ecosystem

In addition to running standalone, Project CodeFlare is deployed as part of and integrated with the [Open Data Hub][distributed-workloads].

## Getting Started

### Learning

Watch [this video][youtube-demo] for an introduction to Project CodeFlare and what the
stack can do. (Nov. 2022)

See [this video][summit-demo] as well for an updated demonstration of the basic stack functionality in-action. (Jun. 2023)

### Quick Start

To get started using the Project CodeFlare stack, try this [end-to-end example](https://github.com/opendatahub-io/distributed-workloads/tree/main/examples)!

For more basic walk-throughs and in-depth tutorials, see our [demo notebooks][demos]!

## Development

See more details in any of the component repos linked above, and go to their issues page for open tasks/issues!

### Architecture

We attempt to document all architectural decisions in our [ADR documents][adr]. Start here to understand the architectural details of Project CodeFlare.

### Getting Involved

Join our [Slack community][slack] to get involved or ask questions.

### License

Unless otherwise noted at a per-component level, this Project CodeFlare is licensed under the Apache-2.0 License.

[codeflare-sdk]: https://github.com/project-codeflare/codeflare-sdk
[codeflare-cli]: https://github.com/project-codeflare/codeflare-cli
[appwrapper]: https://github.com/project-codeflare/appwrapper
[instascale]: https://github.com/project-codeflare/instascale
[codeflare-operator]: https://github.com/project-codeflare/codeflare-operator
[distributed-workloads]: https://github.com/opendatahub-io/distributed-workloads
[quickstart]: https://github.com/opendatahub-io/distributed-workloads/blob/main/Quick-Start.md
[slack]: https://invite.playplay.io/invite?team_id=T04KQQBTDN3
[adr]: https://github.com/project-codeflare/adr
[demos]: https://github.com/project-codeflare/codeflare-sdk/tree/main/demo-notebooks/guided-demos
[board]: https://github.com/orgs/project-codeflare/projects/8
[youtube-demo]: https://www.youtube.com/watch?v=OAzFBFL5B0k
[summit-demo]: https://youtu.be/U76iIfd9EmE
