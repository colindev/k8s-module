### nginx

```bash
$ make -C examples/nginx/ # create self signature certificate
$ kubectl apply -k examples/nginx # deploy nginx & tcp loadbalancer
```
