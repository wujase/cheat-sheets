# Overview

- [kubectl](https://kubernetes.io/docs/reference/kubectl/)

# Cheat Sheets

| Command                                                                                | Description                                    | Note |
|----------------------------------------------------------------------------------------|------------------------------------------------|------|
| `kubectl help`                                                                         |                                                |      |
| `kubectl --help`                                                                       |                                                |      |
| `kubectl [command] --help`                                                             |                                                |      |
| &nbsp;                                                                                 |                                                |      |
| `kubectl annotate [resource-type]/[resource-name] [annotation-key]=[annotation-value]` | Annotate a resource.                           |      |
| `kubectl config current-context`                                                       | Display current context.                       |      |
| `kubectl config get-contexts`                                                          | Display all contexts.                          |      |
| `kubectl config rename-context [old-context-name] [new-context-name]`                  | Rename a context.                              |      |
| `kubectl config set-context [context-name] --namespace [namespace-name]`               | Set a context.                                 |      |
| `kubectl config use-context [context-name]`                                            | Use a context.                                 |      |
| `kubectl config view`                                                                  | Display all configurations.                    |      |
| `kubectl edit [resource-type]/[resource-name]`                                         | Edit a resource.                               |      |
| `kubectl exec pod/[pod-name] -- command`                                               | Execute a command in a pod.                    |      |
| `kubectl exec pod/[pod-name] --container [container-name] -- command`                  | Execute a command in a container.              |      |
| `kubectl exec pod/[pod-name] --std --tty -- /bin/bash`                                 | Interactive shell access in a pod.             |      |
| `kubectl explain [resource-type]`                                                      | Explain a resource type.                       |      |
| `kubectl delete [resource-type]/[resource-name]`                                       | Delete a resource.                             |      |
| `kubectl describe [resource-type]`                                                     | Describe a resource type.                      |      |
| `kubectl describe [resource-type]/[resource-name]`                                     | Describe a resource.                           |      |
| `kubectl get [resource-type]`                                                          | Display a resource type.                       |      |
| `kubectl get [resource-type]/[resource-name]`                                          | Display a resource.                            |      |
| `kubectl label [resource-type]/[resource-name] [label-key]=[label-value]`              | Label a resource.                              |      |
| `kubectl logs pod/[pod-name]`                                                          | Display all logs of a pod.                     |      |
| `kubectl logs pod/[pod-name] --container [container-name]`                             | Display all logs of a container.               |      |
| `kubectl logs pod/[pod-name] --follow`                                                 | Stream all logs of a pod.                      |      |
| `kubectl logs pod/[pod-name] --previous`                                               | Display all logs of a previous pod.            |      |
| `kubectl port-forward pod/[pod-name] X:Y`                                              | Port-forward a pod to the local port X.        |      |
| `kubectl port-forward service/[pod-name] X:Y`                                          | Port-forward a service to the local port X.    |      |
| `kubectl scale [resource-type]/[resource-name] --replicas=N`                           | Scale a resource.                              |      |
| `kubectl top node`                                                                     | Display the CPU and Memory usage of all nodes. |      |
| `kubectl top node [node-name]`                                                         | Display the CPU and Memory usage of a node.    |      |
| `kubectl top pod`                                                                      | Display the CPU and Memory usage of all pods.  |      |
| `kubectl top pod [pod-name]`                                                           | Display the CPU and Memory usage of a pod.     |      |
| `kubectl version`                                                                      | Display the kubectl version.                   |
