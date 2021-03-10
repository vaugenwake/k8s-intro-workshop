# k8s-intro-workshop
Kubernetes into workshop

### Adding a new kube config to kubectl
```
KUBECONFIG= $HOME/.kube/config:/path/to/another/config kubectl config view --merge --flatten > \
~/.kube/merged_kubeconfig && mv ~/.kube/merged_kubeconfig ~/.kube/config
```