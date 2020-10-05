
Problem-01
===========
```
Host key verification failed' SSH Error
```


**Solution**

```
$ sudo ssh-keygen -R 192.168.X.X
```
which will update an old key in known host.
