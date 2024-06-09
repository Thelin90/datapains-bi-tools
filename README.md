# datapains-bi-tools

In this repository I will keep different BI tools I use in my datapains series.

## Setup

Please head out to https://github.com/Thelin90/datapains-argo-cd-k8s to see how I deploy this.

However before we do that, we do need to add the helm chart.

```bash
helm repo add superset http://apache.github.io/superset/
```

At time of writing `0.12.11`.

`List version`

```bash
helm search repo superset
```
