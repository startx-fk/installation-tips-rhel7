# PIP installation for Python 2.7

```
subscription-manager repos --enable rhel-server-rhscl-7-rpms
yum install python27 python27-python-pip
```

```
$> cat /etc/profile.d/enable-python27.sh

#!/bin/bash
source scl_source enable python27
```
