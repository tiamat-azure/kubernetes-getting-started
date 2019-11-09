# Kubernetes tutorial

> This tutorial is based on Windows platform


## Links

- [Kubernetes Official doc](https://kubernetes.io/docs/tasks/tools/install-minikube/)
- [Katacoda online kubernetes tutorial](https://www.katacoda.com/courses/kubernetes)


## Install kubectl

Install kubectl with [chocolatey](https://chocolatey.org/)

    choco install kubernetes-cli


Check correct version of kubectl is installed

    kubectl version

    Client Version: version.Info{Major:"1", Minor:"16", GitVersion:"v1.16.2", GitCommit:"c97fe5036ef3df2967d086711e6c0c405941e14b", GitTreeState:"clean", BuildDate:"2019-10-15T19:18:23Z", GoVersion:"go1.12.10", Compiler:"gc", Platform:"windows/amd64"}
    Error from server (NotFound): the server could not find the requested resource

>You must use kubectl binary from chocolatey instead of the one installed with Docker Desktop (adapt the PATH environment variable if necessary)

Check the path

    which kubectl

    /c/Program Files/Docker/Docker/Resources/bin/kubectl

## Install minikube

Install minikube with [chocolatey](https://chocolatey.org/) with admin rights :

    choco install minikube

Check minikube version :

    $ minikube version

    minikube version: v1.5.2
    commit: 792dbf92a1de583fcee76f8791cff12e0c9440ad-dirty

Start minikube

    minikube start





