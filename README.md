# 🏠 Homelab
I have had a homelab for a while now, which I used to test different technologies using a combination of old laptops, desktops, and a Raspberry Pi, from trying operating systems to trying and testing tools to hosting open source applications or my applications. My current setup has, for a while, been Docker, Nginx Proxy Manager (NPM), and Portainer. It's time to evolve my homelab to Kubernetes and a GitOps workflow. 
I will use this project to continue learning Kubernetes and GitOps.

## Introduction
The purpose of my homelab is to learn and to have fun. My homelab is where I can try out and learn new things. On the same token, I can also self-host applications, which can be open source or my own. The project drives me to be responsible for the entire process of deploying and maintaining an application. It forces me to think about backup strategies, security, scalability, and the ease of deployment and maintenance.

## :computer: Hardware

### Nodes
I use a combination of Raspberry Pi, laptops, desktops, virtual machines (VMs), with the new addition of an Orange Pi 5 (16 GB) to replace my Raspberry Pi 3 (1GB). I chose the Orange Pi to have it on all the time.

### Storage

I am using the local storage on the Orange Pi 5, which is an NVMe SSD. I'll be upgrading to a QNAP NAS and use a CSI driver to provision Persistent Volumes for the cluster.
