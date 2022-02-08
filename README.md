# deno-cloudrun

This repository is a simple web-server written in
the computer language [deno](https://deno.land/). The language was created by Ryan Dahl, who also created *node*. The program accepts a web connections on port
8080, and responds with the *user-agent* of the client.

## Google Cloud Run
Press the button below to deploy this application to Google Cloud Run.

[![Run on Google Cloud](https://deploy.cloud.run/button.svg)](https://deploy.cloud.run)

## How to run the code locally:
``` shell
deno run --allow-net main.ts
```

## Appendix
1. [Cloud Run Button Blog](https://cloud.google.com/blog/products/serverless/introducing-cloud-run-button-click-to-deploy-your-git-repos-to-google-cloud)
2. [Cloud Run Button Git Repo](https://github.com/GoogleCloudPlatform/cloud-run-button#add-the-cloud-run-button-to-your-repos-readme)
