# TEKTON CICD

### Install dependencies
#### Install tekon dependencies
* install tekton pipelines

    Latest official release: 

    `kubectl apply --filename https://storage.googleapis.com/tekton-releases/pipeline/latest/release.yaml`

* Install Tekton Dashboard

    `kubectl apply --filename https://storage.googleapis.com/tekton-releases/dashboard/latest/release.yaml`
    for read only or 

    `kubectl apply --filename https://storage.googleapis.com/tekton-releases/dashboard/latest/release-full.yaml` for  write previllages

* Install triggers and Interceptors 

    `kubectl apply --filename \
https://storage.googleapis.com/tekton-releases/triggers/latest/release.yaml
kubectl apply --filename \
https://storage.googleapis.com/tekton-releases/triggers/latest/interceptors.yaml` 

