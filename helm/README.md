# Overview

- [helm](https://helm.sh/)

# Cheat Sheets

| Command                                              | Description                                | Note                                                       |
|------------------------------------------------------|--------------------------------------------|------------------------------------------------------------|
| `helm help`                                          |                                            |                                                            |
| `helm --help`                                        |                                            |                                                            |
| `helm [command] --help`                              |                                            |                                                            |
| &nbsp;                                               |                                            |                                                            |
| `helm create [chart-name]`                           | Create a helm chart.                       |                                                            |
| `helm env`                                           | Display all environment information.       |                                                            |
| `helm get all [release-name]`                        | Display all information of a helm release. |                                                            |
| `helm get manifest [release-name]`                   | Display the manifest of a helm release.    |                                                            |
| `helm get values [release-name]`                     | Display all values of a helm release.      |                                                            |
| `helm install [release-name] [chart-path] [options]` | Install a helm chart.                      | [options](https://helm.sh/docs/helm/helm_install/#options) |
| `helm lint [chart-path]`                             | Verify a helm chart.                       |                                                            |
| `helm list`                                          | List all helm releases.                    |                                                            |
| `helm pull [chart]`                                  | Pull a helm chart.                         |                                                            |
| `helm repo add [repo-name] [repo-url]`               | Add a helm repository to local.            |                                                            |
| `helm repo list`                                     | List all helm repositories.                |                                                            |
| `helm repo remove [repo-name]`                       | Remove a helm repository from local.       |                                                            |
| `helm repo update`                                   | Update all helm repositories in local.     |                                                            |
| `helm show all [chart]`                              | Display all information of a chart.        |                                                            |
| `helm show chart [chart]`                            | Display the definition of a chart.         |                                                            |
| `helm show values [chart]`                           | Display all values of a chart.             |                                                            |
| `helm uninstall [release-name]`                      | Uninstall a helm release.                  |                                                            |
| `helm upgrade [release-name] [chart-path] [options]` | Upgrade a helm release.                    | [options](https://helm.sh/docs/helm/helm_upgrade/#options) |
| `helm version`                                       | Display the helm version.                  |                                                            |
