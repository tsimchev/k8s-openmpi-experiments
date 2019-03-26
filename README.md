# k8s-openmpi-experiments
Contains experiments executed on top of the k8s-openmpi repository

# GCE Small MPI Cluster Setup
Cluster size = 3 Nodes
Node version = 1.11.7-gke.12
Node image = Container Optimized OS (cos)
Node type = n1-standard-1 (1vCPU, 3.75 GB of memory)
Node disk = 100G
 

# GCE Medium MPI Cluster Setup
Cluster size = 6 Nodes
Node version = 1.11.7-gke.12
Node image = Container Optimized OS (cos)
Node type = n1-standard-1 (1vCPU, 3.75 GB of memory)
Node disk = 100G

# Experiments
* Small Cluster Anti-Affinity Experiment – execute MPI Benchmarks Target of Measurement on the Small Cluster (3 nodes) with anti-affinity rule of type one container (pod) per cluster node.
* Medium Cluster Container Overlapping – execute MPI Benchmarks Target of Measurement on the Medium Cluster (6 nodes) without any affinity rules, where the size of the MPI cluster is 10 containers, on average two containers (pods) per cluster node.
