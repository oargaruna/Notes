# Videos

_Schedule (North America): https://kccncna2024.sched.com/overview/type_
_Schedule (Europe): https://events.linuxfoundation.org/kubecon-cloudnativecon-europe/program/schedule/_

## Automated Multi-Cloud Large Scale K8s Cluster Lifecycle Management - Sourav Khandelwal, Databricks
*YouTube: https://www.youtube.com/watch?v=9E7lenP6pFc*
*KubeCon: https://kccncna2024.sched.com/event/1i7km/*

- Adopted spec-status / reconciler pattern from Kubernetes.
    - Same as COSMIC Management Plane.
    - Another attendee remarked that they are also using the same pattern.
- Rolling updates are done by creating a new Cluster and "draining" pods to the new one.
    - No details about how the drain is actually performed, and how availability of the customer's service is maintained.
## Automated Multi-Cloud, Multi-Flavor Kubernetes Cluster Upgrades Using Operators - Ziyuan Chen, Databricks
*YouTube: https://www.youtube.com/watch?v=LldZE-nNNj0*
*KubeCon: https://kccncna2024.sched.com/event/1i7kt*

- [Blob Post](https://www.databricks.com/blog/scalable-kubernetes-upgrade-using-operators)