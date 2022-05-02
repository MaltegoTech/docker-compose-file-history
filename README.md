# Maltego Server Docker compose file history
This repository contains a history of Docker compose files for the iTDS and MST Onprem which can be used to deploy older versions of the servers.

## Instructions
Follow these steps to deploy an older version of a server.

1. Download the version you would like to deploy. The files are named in the following convention `<server_name>_<version>.yml`
2. In the files there are placeholder values for secrets that need to be replaced with actual values. Information on the environmental variables and secrets used can be found [here](https://docs.maltego.com/support/solutions/articles/15000017587-deploying-the-itds-with-docker#introduction-0-0).
3. From your terminal in the directory of the file you downloaded, run `docker-compoes -f <server_name>_<version>.yml up`

The containers will be pulled from our registry and start running.

For further instructions on deploying Maltego servers, have a look at the following links: [iTDS](https://docs.maltego.com/support/solutions/articles/15000017587-deploying-the-itds-with-docker), [MST Onprem](https://docs.maltego.com/support/solutions/articles/15000034188-deploying-with-docker).

