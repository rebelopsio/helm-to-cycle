# helm-to-cycle

## What

[Cylcle.io](https://cycle.io) is a platform that that has deviated from the beaten path of building on top of Kubernetes or Docker and has built a platform that leverages containers built with OCI specs and simplifies the management of infrastructure and deployment into a single platform. You can run your workloads in any of the major cloud providers, including multi cloud, and Cycle will easily help you scale and manage those workloads.

Since Cycle is built from the ground up and not built on top of Kubernetes or Docker, you may find that you'll need to convert some of your workloads to Cycle [stack spec](https://docs.cycle.io/reference/stacks/spec). Hopefully this tooling will be helpful if your workloads are currently managed with Helm.
