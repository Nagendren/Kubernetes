```python
command: kubectl get nodes
Description: List all the nodes
```
```python
command: kubectl get pods
Description: List all the pods in default namespace
```
```python
command: kubectl get namespaces
Description: List all the namespaces in the cluster
```
```python
command: kubectl create namespace development
Description: creating new namespace called development
```
```python
command: kubectl get pods -n kube-system
Description: will list the pods under given namespace. kube-system contains pods related to system
```
```python
command: kubectl get pods -o wide -n kube-system
Description: will list the pods under given namespace with more info
```
```python
command: kubectl api-resources
Description: will list all the kind, versions, shortnames and namespace
```
```python
command: kubectl create -f <filename>.yaml
Description: will create the resources given in the yaml file
```
```python
command: kubectl describe pods <podname>
Description: will give detailed info about pod
```
```python
command: kubectl apply -f <filename>.yaml
Description: will apply the changes to exisitng pods
```
```python
command: kubectl delete -f <filename>.yaml
Description: will delete pods
```
```python
command: kubectl get pods -w
Description: will list pods with latest updates
```
```python
command: kubectl edit pod <pod name>
Description: Allows you to edit the pod directly
```
```python
command: kubectl exec --stdin --tty <pod name> -- <command to execute> /
Description: Allows you run commands inside the container
```
```python
command: kubectl exec -i -t my-pod --container main-app -- /bin/bash
Description: If we have multiple container running in pod, we can specify container name to execute commands
```
```python
command: kubectl describe node kworker-node1
Description: will show detailed node informations
```
```python
command: kubectl logs <pod name> or kubectl logs -f <pod name>
Description: will show pod logs
```
```python
command: kubectl cluster-info
Description: will show cluster informations
```
```python
command: kubectl explain <api-resources like pod, namespace, etc>
Description: will show detailed api-resources informations
```