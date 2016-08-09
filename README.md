laptop-build
============

This is an ansible playbook for setting up laptops or some development environment.


usage
=====

CentOS
------

```sh
# git clone
$ git clone https://github.com/momota/laptop-build
$ cd laptop-build

# dry run
$ ansible-playbook -i hosts centos/site.yml -K --check

# execute
$ ansible-playbook -i hosts centos/site.yml -vv -K
```

MacOSX
------

```sh
# git clone
$ git clone https://github.com/momota/laptop-build
$ cd laptop-build

# execute
$ HOMEBREW_CASK_OPTS="--appdir=/Applications" ansible-playbook -i hosts mac/site.yml -vv -K
```
