laptop-build
============

This is an ansible playbook for setting up laptops or some development environment.


usage
=====

```sh
# git clone
$ git clone https://github.com/momota/laptop-build
$ cd laptop-build

# dry run
$ ansible-playbook -i centos/hosts centos/site.yml -K --check

# execute
$ ansible-playbook -i centos/hosts centos/site.yml -K
```

