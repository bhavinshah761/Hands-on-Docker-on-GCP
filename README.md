# Hands-on-Docker-on-GCP

I just completed an exercise in where we built a flask application written in python. This app contains a Dockerfile that creates a docker "image" which is a set of instructions for how a Docker container will be configured. Once configured, the app was pushed to the google container registry. Google Cloud Run then downloads and deploys the docker container from the google container registry (via a unique project id), producing a URL for the deployed app.

