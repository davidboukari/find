# find

* Cat all files in a directory
```
find .   -exec sh -c 'if [ "$(echo {}|grep tfplan)" = "" ] &&  [ -f {} ] && [ ! -x {} ];then echo -e "\n**************** {} **************\n"; cat {}; fi' \; 

```
