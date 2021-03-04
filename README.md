# docker-sfdx-cli
Dockerfile for sfdx projects

This project will try to cover any pre-requisite for the tools and environment you might need in order to build a CI/CD process with Salesforce development.

## What you can find currently in this image:

- Commitlint: Try semantic convetion to improve the way you document your changes in your git log.
- SFDX installation: All the power of this CLI ready to be used.
- SFDX scanner **static analysis code**
- Jest: LWC testing will be your ally in your journey.

Image on docker hub: https://hub.docker.com/r/gauravtrivedi/node-sfdx-cli/

[![Docker Automated build](https://img.shields.io/docker/automated/gauravtrivedi/node-sfdx-cli.svg?style=plastic)](https://hub.docker.com/r/gauravtrivedi/node-sfdx-cli/builds/)
## In what is based this image?

This image currently use openjdk as its main core and has Node.js, so you can add `npm / yarn` instructions to your pipeline.
