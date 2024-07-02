# What's new
Each release offers new functions and improvements. IBM is constantly updating the infrastructure, security, and stability of IBM Storage Fusion HCI to improve your
experience. Review this information for a high-level summary of the new features and changes in each release.
# What is new in 2.8.0
IBM Storage Fusion HCI System 2.8.0 includes new features in the following areas:
* Multi-cluster IBM Storage Fusion HCI System with Data Foundation storage
* IBM Storage Fusion HCI System appliance enhancements
* Storage
* Backup & Restore
* Data Cataloging
* Operations
* Currency support

**Multi-cluster IBM Storage Fusion HCI System with Data Foundation storage** 

**Production ready Multi-cluster IBM Storage Fusion HCI System with Data Foundation storage** 

The capability of IBM Storage Fusion HCI System to host multiple Red Hat® OpenShift® clusters in a single appliance is now extended to include production environments.
As workloads grow, you can easily scale out clusters to meet their needs. And when a cluster is no longer needed, you can easily delete it and reclaim the resources for
future cluster provisioning.

**Increased resilience with the new Red Hat Advanced Cluster Management for Kubernetes version support**

Resiliency is handled for your clusters automatically. Control pods are distributed across nodes to avoid single points of failure, and the virtual machines that host the
managed clusters are distributed intelligently so that the physical node failure has a minimum impact. Data Foundation running in the hub cluster distributes replicas so
that data is still available if hardware fails. Applications are further protected by backup up services that are hosted in the hub cluster.

**Ability to support different levels of Red Hat OpenShift Container Platform**
Provide your organization a platform that delivers a “private cloud in a box”, with the ability to spin up Red Hat OpenShift clusters on demand. Size each cluster based on
the desired node count, CPU, and RAM needed by the workloads it hosts, and even choose which version of Red Hat OpenShift for each cluster.

**Automatic configuration of data services in managed clusters**
Pick from a catalog of platform capabilities to provide to each hosted cluster. The storage add-on provides block, file, and object storage for workloads that run on hosted
clusters. The backup add-on enables backup and recovery capabilities for workloads in each cluster.

**Scale out across multiple racks**
IBM Storage Fusion HCI System 2.7.1 introduced the capability to host multiple clusters in a single appliance, and now you can combine up to three IBM Storage Fusion
HCI System racks together to grow your private cloud even larger. A single hub cluster provides data services to dozens of hosted clusters. Racks are tagged with
availability zones so that the storage and cluster placement takes into account potential domain failures.

**Red Hat Advanced Cluster Management for Kubernetes user interface enhancement**

Earlier, you had to use the command line to create clusters. From 2.8.0 version onwards, you can use the Red Hat Advanced Cluster Management for Kubernetes user
interface to easily create Red Hat OpenShift Virtualization clusters.ft Virtualization clusters.
