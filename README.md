# find

* Cat all files in a directory
```
find . -exec sh -c 'if [ -f {} ] && [ ! -x {} ];then echo "**************** {} **************"; cat {}; fi' \;

```
