%title: Kubernetes 
%author: xavki

# HELM : Commandes et Révisions


<br>
* list :

```
helm list --kubeconfig /etc/rancher/k3s/k3s.yaml
```

<br>
* historique :

```
helm history --kubeconfig /etc/rancher/k3s/k3s.yaml hello-xavki
```

<br>
* détails (variables)

```
helm show --kubeconfig /etc/rancher/k3s/k3s.yaml all hello-xavki
```

<br>
* upgrade

```
helm upgrade --kubeconfig /etc/rancher/k3s/k3s.yaml hello-xavki ./hello-xavki/
```

<br>
* rollback

```
helm rollback --kubeconfig /etc/rancher/k3s/k3s.yaml hello-xavki
```

