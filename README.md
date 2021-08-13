### nginx usage

```bash
$ git clone https://github.com/colindev/k8s-module.git
$ cd k8s-module
$ make -C examples/nginx/ # create self signature certificate
$ kubectl create ns test
$ kubectl apply -k examples/nginx # deploy nginx & tcp loadbalancer
```
