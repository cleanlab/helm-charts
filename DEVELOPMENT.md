# Contributing

All Helm charts are kept in the `charts` directory. To add a new chart, create a new subfolder with the name of your chart and then use Helm's [expected file structure](https://helm.sh/docs/topics/charts/#the-chart-file-structure).

Use pull requests for any changes to `main`. You do not need to modify the `gh-pages` branch directly; any changes within `charts` will be pushed via Helm's [Chart Releaser action](https://helm.sh/docs/howto/chart_releaser_action/). Note that those changes may be force-pushed, so be careful if adding branch protections to `gh-pages`.
