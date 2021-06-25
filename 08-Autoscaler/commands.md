```
kubectl run -it --rm load-generator2 --image=busybox /bin/sh
```
```
while true; do wget -q -O- http://sqrt-service; done
```