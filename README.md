# argo-cd-hello-world-app

* architecture
  * [hello-world application](main.go)
  * CI
    * ways
      * [Argo Workflow](.argo-ci/ci.yaml)
      * [Jenkins](Jenkinsfile)
      * [Travis CI](.travis.yml)
      * [Github Actions](.github/workflows/docker-publish.yml)

## how to configure the CI?
### Argo Workflow
TODO:
### Jenkins
TODO:
### Travis CI
TODO:
### Github Actions
* steps
  * | https://github.com/dancer1325/argo-cd-hello-world-app 
    * Settings > Actions > Repository secrets > add
      * `DOCKERHUB_TOKEN`
      * `DOCKERHUB_USERNAME`
      * `GH_PAT`
