# Memo

## Sync to qmk

```sh
git checkout master
git pull upstream master
git push origin master
```

## Checkout my branch

```sh
git checkout takelushi
```

## Update my branch

```sh
git add .
git commit -m 'Update.'
git push origin takelushi
```

## Build with docker

* `getting_started_docker.md`

```sh
util/docker_build.sh crkbd/rev1:default
```
