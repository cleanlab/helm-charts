## Usage

[Helm](https://helm.sh) must be installed to use the charts.  Please refer to
Helm's [documentation](https://helm.sh/docs) to get started.

Once Helm has been set up correctly, add the repo as follows:

    helm repo add cleanlab https://github.com/cleanlab/helm-charts

If you had already added this repo earlier, run `helm repo update` to retrieve
the latest versions of the packages.  You can then run `helm search repo
cleanlab` to see the charts.

To install the `tlm` chart:

    helm install tlm cleanlab/tlm

To uninstall the chart:

    helm uninstall tlm
