# kubernetes
hostpath: 
Kubernetes supports hostPath for development and testing on a single-node cluster. A hostPath PersistentVolume uses a file or directory on the Node to emulate network-attached storage.
#Data is stored at Node level. If the Pod is deleted data remains at the node level.
#Data is shared to all containers within Pod.
#Data is Not shared across Nodes(local to node only)

#local
#End