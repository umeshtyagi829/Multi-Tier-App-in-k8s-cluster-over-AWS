# kubernetes-multi-node-cluster-over-aws
### If we running kubernetes that means we have use kubenetes cluster that's why `<Cluster>` is a heart of the kubernetes. Kubernetes cluster  have one control-plane(master) and one node at minimum in maximum we have as we want. Control-plane manage the user's request and node manage the workload of the resources or provide resources to the user's.

### Kubernetes cluster provides the organization more scalablity, availabilty, etc. 

### At the learning stage we use the product `<minikube>` that gives the facilities of kubernetes cluster. 

## Making own kubernetes cluster over AWS cloud using Ansible
### I have created three ansible role for master `<kube-master>`, node `<kube-nodes>`, and ec2-instance `<ec2-instance>`.

### `<calling-role>` it have two yml files. 
### `<ec2.yml>` in this file i have call ec-instace role. Simillary `<k8s-cluster.yml>` in which i have call two more remain roles.

## Run all the yml file in this manner: 
1. ec2.yml
2. k8s-cluster.yml



