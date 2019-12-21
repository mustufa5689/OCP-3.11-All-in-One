Install OpenShift Container Platform 3.11 on your server.

This repository is a set of scripts that will allow you easily install the latest version (3.11) in a single node fashion.  What that means is that all of the services required for OCP to function (master, node, etcd, etc.) will all be installed on a single host.  The script supports a custom hostname which you can provide using the interactive mode.

## Installation

1. Create a machine with two block devices, the second one unused - this will be used for Docker storage

2. Install RHEL and subscribe it to RHSM for the correct products 

3. Clone this repo

```
got clone https://github.com/mustufa5689/OCP-3.11-All-in-One
```

4. Execute the installation script

```
cd OCP-3.11-All-in-One
./install-openshift.sh
```

