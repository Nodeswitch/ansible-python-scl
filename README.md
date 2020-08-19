# Python SCL

[![Build Status](https://travis-ci.org/angrox/ansible-python-scl.svg?branch=master)](https://travis-ci.org/angrox/ansible-python-scl)


This module has the following features:
* Installs/Enables Softwarecollections on CentOS and RHEL
* Installs a SCL python version
* Enables the python version globally


## Variables
scl_python_version: The version to use. Defaults to 38 (3.8.x). Possible values: 34, 35, 36 and 38.

## Usage
Example playbook:
```
- hosts: all
  roles:
    - role: angrox.python-scl
```
