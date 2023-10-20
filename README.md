# log2rbac kubectl plugin

Simple TUI based shell script for templating the GiantSwarm clusters.


## Quick start

```bash
sudo ln -s $PWD/kubectl-clu /usr/local/bin/kubectl-clu
kubectl clu
```

or install the latest released version using Krew

```bash
kubectl krew install --manifest-url=https://raw.githubusercontent.com/jkremser/kubectl-clu/master/.krew.yaml
```

```bash
# output:
Installing plugin: clu
Installed plugin: clu
\
 | Use this plugin:
 | 	kubectl clu
 | Documentation:
 | 	https://github.com/jkremser/kubectl-clu
/
```
