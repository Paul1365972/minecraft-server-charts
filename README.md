# minecraft-server-charts

[![](https://github.com/paul1365972/minecraft-server-charts/workflows/Release%20Charts/badge.svg?branch=master)](https://github.com/paul1365972/minecraft-server-charts/actions)

## Usage

[Helm](https://helm.sh) must be installed to use the charts.
Please refer to Helm's [documentation](https://helm.sh/docs/) to get started.

Once Helm is set up properly, add the repo as follows:

```console
helm repo add paul1365972-mc https://paul1365972.github.io/minecraft-server-charts/
```

You can then run `helm search repo paul1365972-mc` to see the charts.

## Charts
tt
* [minecraft](https://github.com/paul1365972/minecraft-server-charts/tree/master/charts/minecraft)
* [minecraft-bedrock](https://github.com/paul1365972/minecraft-server-charts/tree/master/charts/minecraft-bedrock)

```bash
helm install --name your-release paul1365972-mc/minecraft
```

Also see [helm hub](https://hub.helm.sh/charts/paul1365972-mc) for a complete list.
