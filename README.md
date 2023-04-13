# pants-ansible
A ansible wrapper using Pants.

## Install Pants and Python
1. Install Pants: https://www.pantsbuild.org/docs/installation
2. Install Python 3.10.x
   + Because in [pants.toml](pants.toml), we set the intepreter to Python 3.10.x
   + Because on Ubuntu 22.04, the default Python is Python 3.10.x
3. No Python Virtual Environment needed

Here is a recommended way to install Python 3.10.x:
```
bin/install_python
```

## Get Started
```
# ansible localhost -m ping
bin/ansible localhost -m ping
```
