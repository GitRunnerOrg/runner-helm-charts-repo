## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

  helm repo add runner-helm-charts-repo https://github.com/GitRunnerOrg/runner-helm-charts-repo

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo runner-helm-charts-repo` to see the charts.

To install the action-runner-chart chart:

    helm install action-runner-chart runner-helm-charts-repo/action-runner-chart

To uninstall the chart:

    helm delete action-runner-chart
