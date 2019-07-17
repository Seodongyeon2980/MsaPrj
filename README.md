# MsaPrj
Kubernetes Project for MSA

## info
- 목적: 도커빌드 &쿠버네티스 빌드
- 구성요소 : nginx/htmlcode
- 요건: 도커빌드 와 쿠버네티스 배포 스크립트

## Folder Architecture
* DpclerScript :./docker
* KubernetesScript: ./kubernetes

## Usage

* Docker Build
```
cd ./docker
. build.sh
```

* Dock Hub push
```
cd ./docker
. push.sh
```

* kubernetes Provisioning

```
cd ./kubernetes
. kubProvsion.sh
```


