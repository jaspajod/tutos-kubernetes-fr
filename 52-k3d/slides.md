%title: Kubernetes 
%author: xavki


# K3D


<br>
* k3d = k3s + docker

<br>
Doc : https://github.com/rancher/k3d

<br>
```
curl -s https://raw.githubusercontent.com/rancher/k3d/master/install.sh | bash
```

<br>
k3d create --api-port 6550 --publish 8081:80 --workers 2

<br>
export KUBECONFIG="$(k3d get-kubeconfig --name='k3s-default')"

kubectl cluster-info

kubectl get nodes
