此目录下的文件是StatefulSets控制结合Volume创建有状态应用的示例——mysql主从
kubectl run mysql-client --image=mysql:5.7 -i -t --rm --restart=Never -- mysql  -h mysql-read
