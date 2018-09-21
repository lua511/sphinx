[TOC]

sphinx/README.md
====================

a docker image for init & generate sphinx-markdown site.

## create sphinx docker image

```
# create image
cd sphinx-docker
docker build -t sphinx .
```


### precheck

```
# check image exists
docker image list | grep "muddb-sphinx"
```

```
# delete an old image
docker image rm muddb-sphinx
```


## create from github

```
docker build -t sphinx https://github.com/lua511/sphinx.git
```

### create from github with branch

```
docker build -t sphinx https://github.com/lua511/sphinx.git#cn
```

