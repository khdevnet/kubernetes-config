### Debug Services
```
$ iptables-save | grep <service name>                                   # service ip rules
$ kubectl run -it --rm --restart=Never busybox --image=busybox sh       # check service by request $ wget -hO- servicename  
```
