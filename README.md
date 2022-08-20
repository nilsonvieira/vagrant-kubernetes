# Introduction
This article is to configure environment Kubernetes with Vagrant using only vagrantfile and shell scripts.

# Pre-Requisites
On my desktop i used:
- Linux Pop!_OS 22.04 LTS

## Aditional Packs
- Install Hascorp Vagrant 
- Pré config ssh keys (for add your personal key and vagrant key)
- VirtualBox 6.1
- Enable all IPs for VirtualBox in Host-Only Networking 
    - https://www.virtualbox.org/manual/ch06.html
        - Chapther (6.7. Host-Only Networking)

# Start Cluster K8s
Starting with Vagrant

```bash
vagrant up 
```


# References
https://devopscube.com/kubernetes-cluster-vagrant/