laptop-build
============

This is an ansible playbook for setting up laptops or some development environment.


usage
=====

First, clone this repo.

```sh
$ git clone https://github.com/momota/laptop-build
$ cd laptop-build
```

CentOS
------

```sh
# dry run
$ ansible-playbook -i hosts centos/site.yml -K --check

# execute
$ ansible-playbook -i hosts centos/site.yml -vv -K
```

MacOSX
------

```sh
# execute
$ HOMEBREW_CASK_OPTS="--appdir=/Applications" ansible-playbook -i hosts mac/site.yml -vv -K
```
