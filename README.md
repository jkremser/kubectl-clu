# kubectl-clu plugin

Simple TUI based shell script for templating the GiantSwarm clusters.


## Quick start

Having krew [installed](https://krew.sigs.k8s.io/docs/user-guide/setup/install/), just run:

```bash
kubectl krew install --manifest-url=https://github.com/jkremser/kubectl-clu/raw/main/.krew.yaml
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
### Usage

```bash
k clu create
```

### Requirements

This plugin requires couple of binaries to work properly.

Mac:
```bash
brew install bat curl figlet fzf yq jq
```

Linux:

```bash
yum install bat curl figlet fzf jq
```

or

```bash
apt-get install bat curl figlet fzf jq
```

and for `yq` consult the [readme](https://github.com/mikefarah/yq#install).
