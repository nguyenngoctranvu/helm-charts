# nguyenngoctranvu Helm Charts

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add mychart https://nguyenngoctranvu.github.io/helm-charts
```

You can then run `helm search repo mychart` to see the charts.

## Create an index
```
helm repo index --url https://nguyenngoctranvu.github.io/helm-charts/chart .
```

## Add new charts to an existing repository
```
helm repo index --url https://nguyenngoctranvu.github.io/helm-chart/chart --merge index.yaml .
```