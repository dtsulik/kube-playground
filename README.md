# For all things Kubernetes

This repo will host various deployments and experiments with kubernetes. Idea is to play with more complex things and try to break them in various stages and learn.

Please feel free to contribute and open any issues for suggestions or bugs.

## List of apps
### [simple get-pods](https://github.com/dtsulik/app-playground/tree/master/01-simple-get-pods)
Idea of this app is to demonstrate how apps that are designed to work inside cloud are different from classical apps. I.E. exploring what cloud native is from dev perspective.
### [simple-logger](https://github.com/dtsulik/app-playground/tree/master/02-simple-logger)
This app will be used to mess with various ways for log collection in cluster (sidecar/cluster-wide/...)

## NOTE: Registry
For now I will be using local registry for all images. Once I am done experimenting with the app, it will be pushed to dockerhub and the deployments will be updated accordingly.
