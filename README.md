# kubectl-luster plugin

Simple TUI based shell script for templating the GiantSwarm clusters.


[![Watch the full asciicast](./demo.gif)](https://asciinema.org/a/625434)
([pauseable demo](https://asciinema.org/a/625434))

## Quick start

Having krew [installed](https://krew.sigs.k8s.io/docs/user-guide/setup/install/), just run:

```bash
kubectl krew install --manifest-url=https://github.com/jkremser/kubectl-luster/raw/main/.krew.yaml
```

```bash
# output:
Installing plugin: luster
Installed plugin: luster
\
 | Use this plugin:
 | 	kubectl luster
 | Documentation:
 | 	https://github.com/jkremser/kubectl-luster
/
```
### Usage

```bash
k luster create
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

### Update

```
kubectl luster -v
kubectl krew uninstall luster && kubectl krew install --manifest-url=https://github.com/jkremser/kubectl-luster/raw/main/.krew.yaml
kubectl luster -v
```