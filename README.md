# Major Cloud Provider K8S Versions.
## Last Updated: December 5, 2018
An updated chart showcasing all the current cloud provider (AWS, Azure, GCE, Alibaba) K8S versions. Adding OpenShift as well cause it's awesome.

As of today: December 5, 2018 the current K8S versions out on the major public clouds are as follows:

Stable version of Kubernetes is: [v1.13](https://kubernetes.io/docs/setup/release/notes/)
 
| Provider | Product | K8S Version | Notes |
| -------- | ------- | ----------- | ----- |
| AWS      | EKS     | 1.10 (Patch 1.10.11) | [AWS Documentation](https://docs.aws.amazon.com/eks/latest/userguide/platform-versions.html) |
| Azure    | AKS     | 1.10.10 to 1.11.5 (3) | [Azure Patch Documentation](https://azure.microsoft.com/en-us/updates/aks-clusters-patched-for-kubernetes-vulnerability/) <br> [Azure Documentation](https://docs.microsoft.com/en-us/azure/aks/supported-kubernetes-versions) <br><br>From AZ CLI: `az aks get-versions --output table` |
| GCE      | GKE     | 1.9.7-gke.11 (default), 1.11.3-gke.18 | [Google Documentation](https://cloud.google.com/kubernetes-engine/versioning-and-upgrades) |
| Alibaba  |         |  |

# Major K8S Product Versions (both Cloud and On-Prem solutions)

| Non-Cloud Platforms | Product | K8S Version | Notes |
| ------------------- | ------- | ----------- | ----- |
| RedHat   | OpenShift | 1.11 | |
| Docker   | EE | | |
| Rancher  | | | |
| Platform 9 | | | |



Reference links:

	• https://blog.hasura.io/gke-vs-aks-vs-eks-411f080640dc

***Please feel free to do a PR! I cannot possibly manage every major K8S distro out there so if you have data that would be a great fit for this chart then by all means contribute!***