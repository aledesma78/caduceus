# caduceus

[![Build Status](https://travis-ci.org/Comcast/caduceus.svg?branch=master)](https://travis-ci.org/Comcast/caduceus) 
[![codecov.io](http://codecov.io/github/Comcast/caduceus/coverage.svg?branch=master)](http://codecov.io/github/Comcast/caduceus?branch=master)
[![Code Climate](https://codeclimate.com/github/Comcast/caduceus/badges/gpa.svg)](https://codeclimate.com/github/Comcast/caduceus)
[![Issue Count](https://codeclimate.com/github/Comcast/caduceus/badges/issue_count.svg)](https://codeclimate.com/github/Comcast/caduceus)
[![Go Report Card](https://goreportcard.com/badge/github.com/Comcast/caduceus)](https://goreportcard.com/report/github.com/Comcast/caduceus)
[![Apache V2 License](http://img.shields.io/badge/license-Apache%20V2-blue.svg)](https://github.com/Comcast/caduceus/blob/master/LICENSE)
[![GitHub release](https://img.shields.io/github/release/Comcast/caduceus.svg)](CHANGELOG.md)

The Xmidt server for delivering events written in Go.

# How to Install

## Centos 6

1. Import the public GPG key (replace `0.0.1-65` with the release you want)

```
rpm --import https://github.com/Comcast/caduceus/releases/download/0.0.1-65/RPM-GPG-KEY-comcast-xmidt
```

2. Install the rpm with yum (so it installs any/all dependencies for you)

```
yum install https://github.com/Comcast/caduceus/releases/download/0.0.1-65/caduceus-0.0.1-65.el6.x86_64.rpm
```
