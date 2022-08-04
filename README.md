# workspaces-demo

## To work only on `service-one` 

```
git submodule init service-one shared-libs
git submodule update
```


## To work only on `service-two` 

```
git submodule init service-two shared-libs
git submodule update
```


## To work on all services

```
git submodule update --recursive --init
```
