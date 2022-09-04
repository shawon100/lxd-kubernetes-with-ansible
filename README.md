## Clone this github repo:

```
git clone https://github.com/shawon100/lxd-kubernetes-with-ansible

```

## Set up Kubernetes cluster

```
ansible-playbook playbook.yml

```

Exec to k8s-master

```
lxc exec k8s-master bash

```

You can verify the cluster by checking the nodes. Run the following command to list all the connected nodes:

```
[root@k8s-master ~]# kubectl get nodes -o wide

```

Access kubernetes metrics server

```
kubectl top nodes

```

Credits and Reference 

```
https://github.com/sayems/lxc.resources

```
