[![Waffle.io - Columns and their card count](https://badge.waffle.io/IFRCGo/go-infrastructure.svg?columns=all)](https://waffle.io/IFRCGo/go-infrastructure)

# Go Functions

This repo contains the IFRC GO functions app, which houses individual serverless functions for tasks like database syncing and http redirects.

[Azure functions reference](https://docs.microsoft.com/en-us/azure/azure-functions/functions-reference).

## Deployment

Currently, this repo gets deployed everytime https://github.com/IFRCGo/go-infrastructure deploys, so [making code changes here will not automatically deploy](https://github.com/IFRCGo/go-functions/issues/3).

Note, the deployment branch is hardcoded to master, so don't change the default branch in this repo.
