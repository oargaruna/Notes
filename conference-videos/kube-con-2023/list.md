# Videos

_Schedule (North America): https://kccncna2023.sched.com/_
_Schedule (Europe): https://kccnceu2023.sched.com/_

## Tutorial: Getting Familiar with Security Observability Using eBPF & Cilium Tetragon - Holmes & Cooley
_YouTube: https://www.youtube.com/watch?v=kTGU-Nc2Db0_

- [Isovalent Tetragon Lab](https://isovalent.com/labs/tetragon-getting-started/)
- Seccomp policies are applied to an application before it starts. Any updates to the policy requires application restart to get applied.
- Since Tetragon uses eBPF the policy can change dynamically.

## Eraser: Cleaning up Vulnerable Images from Kubernetes Nodes - Peter Engelbert & Ashna Mehrotra
_YouTube: https://www.youtube.com/watch?v=LjDzn7qI5SE_

- [GitHub - eraser-dev/eraser](https://github.com/eraser-dev/eraser)
- [Documentation](https://eraser-dev.github.io/eraser/docs/quick-start)
- Ashna Mehrotra - asmehrotra@microsoft.com
- Peter Engelbert - pengelbert@microsoft.com
- Existing K8s garbage-collection runs only when there is disk-pressure. Default threshold is 85% and it stops at 80%.
- Why is it not enabled for Windows nodes?
- One pod per node - Can be run manually or on schedule.
- Each pod has three containers: collector, scanner, remover. They communicate through shared filesystem and named pipes.
- 