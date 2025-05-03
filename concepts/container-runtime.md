The Container Runtime is the software that is responsible for "running" containers on a Kubernetes node. Operations such as creating, starting, and stopping containers is the responsibility of the Container Runtime. The complete specification of the Container Runtime is defined in the [Container Runtime Interface (CRI)](https://github.com/kubernetes/cri-api/blob/c75ef5b473bbe2d0a4fc92f82235efd665ea8e9f/pkg/apis/runtime/v1/api.proto). 

The CRI is a plugin interface which enables the kubelet to use a wide variety of container runtimes, without having a need to recompile the cluster components. The CRI is the main protocol for the communication between the kubelet and Container Runtime.

![](../images/container-runtime-high-level.png)

Common Container Runtime listed by Kubernetes are:
- [containerd](https://containerd.io/)
- [CRI-O](https://cri-o.io/)
- [Docker Engine](https://docs.docker.com/engine/)

# References
- https://kubernetes.io/docs/concepts/architecture/cri/
- https://kubernetes.io/docs/setup/production-environment/container-runtimes/
- https://kubernetes.io/blog/2016/12/container-runtime-interface-cri-in-kubernetes/