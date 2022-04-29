# Docker compose file history
This repository contains a history of Docker compose files for the iTDS and can be used to deploy an older version of the server.

### Instructions
Follow these steps to deploy an older version of the server.

1. Download the version you would like to deploy. The files are named in the following convention itds_<version>.yml
2. There are placeholder values for secrets that need to be replaced with actual values. Information on the environmental variables used can be found [here]: https://docs.maltego.com/support/solutions/articles/15000017587-deploying-the-itds-with-docker#introduction-0-0
3. From your terminal in the directory of the file you downloaded, run `docker-compoes -f itds_<version>.yml up`

The containers will be pulled from our registry and start running.

For further instructions on deploying Maltego servers, have a look at our documentation [here]: https://docs.maltego.com/support/solutions/articles/15000017587-deploying-the-itds-with-docker

