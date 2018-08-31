# tiller

github addr [https://github.com/kubernets/tiller](https://github.com/kubernets/tiller)

docker hub addr [https://hub.docker.com/u/kubernets](https://hub.docker.com/u/kubernets)

use shell script to pull docker image and replace origin tag

> wget https://github.com/kubernets/tiller/raw/master/get-tiller-image.sh

## Arch and Version

- [**all** v2.10.0](https://hub.docker.com/r/kubernets/tiller)

    > docker pull kubernets/tiller:v2.10.0

    > docker tag kubernets/tiller:v2.10.0 gcr.io/kubernetes-helm/tiller:v2.10.0 

    > docker rmi kubernets/tiller:v2.10.0
