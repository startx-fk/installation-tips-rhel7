# PIP installation for Python 2.7

Enable the RHSCL (Red Hat Software Collections) repository with subscription-manager
`subscription-manager repos --enable rhel-server-rhscl-7-rpms`

Install Python and PIP
`yum install python27 python27-python-pip`

Create profile file for auto execute the scl_source script
```
$> cat /etc/profile.d/enable-python27.sh

#!/bin/bash
source scl_source enable python27
```

More informations about RHSCL : https://access.redhat.com/solutions/472793
