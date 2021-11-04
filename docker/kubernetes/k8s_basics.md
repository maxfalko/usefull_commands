# Basic info about Kubernetes

## Basic architecture

### At list minimum 1 Master and couple Worker nodes

#### On worker nodes started kubelet process


#### On master node started processes 
- API server 
    - comunicating with UI API CLI 
- Controlleer manager 
    - keeps track of whats happening in the cluster restart container if its dead
- Scheduler 
    - ensure Pods palacement e.g. on which node container should be startted
- etcd key value storadge
    - holds kubernetes current state
    - it has all configuration data status of cluster\node\container
    - restoring cluster from snapshots
- Virtual network