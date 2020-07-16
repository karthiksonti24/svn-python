# svn-python

Python Bindings for Subversion 1.10.6 - REDHAT/CENTOS 8.

## Getting Started

Support for Python2.x has come to end by Jan'2020 which leaves many of the applications to move immediately to python3.x which is a herculean task. Due to incompatibilities in the Subversion libraries used for supporting language bindings, Python3 bindings for Subversion are unavailable. As a consequence, applications that require Python3 bindings for Subversion are unsupported. These bindings are useful for providing pythonic interface for your svn repositories or applications using python2.7 on REDHAT/CENTOS 8. All you have to do is to place these folders under `/usr/lib/python2.7/site-packages/(for 32 bit)`or `/usr/lib/python2.7/site-packages/(for 64 bit)`.

### Usage

Download the ZIP or Clone the repository.

1.`unzip svn-python-master.zip`

2.`cd svn-python-master`

3.For 32-bit `mv * /usr/lib/python2.7/site-packages/` 
  For 64-bit `mv * /usr/lib64/python2.7/site-packages/`
  
### Notes
  
These bindings will be useful for python 2.7 on REDHAT/CENTOS 8. Python3 support for subversion is available from subversion-1.14.0 release.
