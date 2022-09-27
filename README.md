# helmrepo-awx Helm charts for awx-operator

## Background

Due to the [official]() helm repo only keeping the latest version of the Chart i have created a simple mirror that only provides a complete index file nothing else.

## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

```bash
helm repo add awx-operator https://janorn.github.io/helmrepo-awx/
```

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
awx-operator` to see the charts.

To install the `awx-operator` chart:

```bash
helm install my-awx-operator awx-operator/awx-operator
```

To uninstall the chart:

```bash
helm delete my-awx-operator
```