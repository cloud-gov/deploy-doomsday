## Doomsday

This repository is a reference for deploying the Doomsday Project.

### Deploying

It's pretty simple, just copy and fill out the credential examples, then configure the pipeline with `fly set-pipeline -p doomsday -c ci/pipeline.yml -l ci/credentials.yml`.