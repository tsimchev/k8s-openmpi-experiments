# k8s-openmpi-experiments
Data from experiments executed on top of the k8s-openmpi repository code.

# Experiments
* Running Container-Based MPI Cluster on shared hosts – the MPI cluster consist of four container nodes each running in compliance with host-bound anti-affinity rule guaranteeing that the Kubernetes scheduler will place and maintain each one of the nodes on a separate container platform host.
* Running Container-Based MPI Cluster on exclusive hosts - the MPI cluster consist of four container nodes running in compliance with host-bound affinity rule guaranteeing that the Kubernetes scheduler will place and maintain every two of the nodes on a same container platform host.

# GCE MPI Cluster Properties
* Four Nodes Cluster deployed on Two Hosts
    * Host version = 1.11.7-gke.12
    * Host image = Container Optimized OS (cos)
    * Host type = n1-standard-1 (2vCPU, 4 GB of memory)
    * Host disk = 100G
* Four Nodes Cluster deployed on Four Hosts
    * Host version = 1.11.7-gke.12
    * Host image = Container Optimized OS (cos)
    * Host type = n1-standard-1 (2vCPU, 4 GB of memory)
    * Host disk = 100G
* Three Nodes Cluster deployed on Three Hosts
    * Host version = 1.11.7-gke.12
    * Host image = Container Optimized OS (cos)
    * Host type = n1-standard-1 (1vCPU, 3.75 GB of memory)
    * Host disk = 100G
* Ten Nodes Cluster deployed on Six Hosts
    * Host version = 1.11.7-gke.12
    * Host image = Container Optimized OS (cos)
    * Host type = n1-standard-1 (1vCPU, 3.75 GB of memory)
    * Host disk = 100G