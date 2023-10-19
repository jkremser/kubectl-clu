# log2rbac kubectl plugin

Simple TUI based shell script for templating the GiantSwarm clusters.


## Quick start

```bash
sudo ln -s $PWD/kubectl-clu /usr/local/bin/kubectl-clu
kubectl clu
```

or install the latest released version using Krew

```bash
λ kubectl krew install --manifest-url=https://raw.githubusercontent.com/jkremser/log2rbac-operator/master/kubectl-plugin/log2rbac.yaml
Installing plugin: log2rbac
Installed plugin: log2rbac
\
 | Use this plugin:
 | 	kubectl log2rbac
 | Documentation:
 | 	https://github.com/jkremser/log2rbac-operator/tree/master/kubectl-plugin
/
```