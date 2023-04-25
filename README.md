# Sonarqube

## A Sonarqube server and scanner running on docker

Before run the compose, run the commands below on the host and change the ``.env`` variables.

``` 
# sysctl -w vm.max_map_count=524288
# sysctl -w fs.file-max=131072
# ulimit -n 131072
# ulimit -u 8192
```