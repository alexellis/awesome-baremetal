# awesome-baremetal

Bare-metal is awesome. Let's share our favourite tools. 

## Rules

* Ordered alphabetically (eventually consistent)
* Recent development or release (within the last 6 months) - or deemed relevant by curator
* No defunct or abandoned projects
* Must show signs of traction or corporate use, no "my scripts for my homelab that only I use" submissions.
* No advertisements
* Format: `link to GitHub or website - "quote from GitHub repo or website"`

Curator: [Alex Ellis](https://www.alexellis.io) - CNCF Ambassador, [OpenFaaS](https://openfaas.com/) & [Inlets](https://docs.inlets.dev/) Founder.

## Self-hosted

* [cobbler](https://github.com/cobbler/cobbler) - "Cobbler is a Linux installation server that allows for rapid setup of network installation environments"
* [Digital Rebar](https://rebar.digital) - "Digital Rebar is the data center automation, provisioning and infrastructure as code (IaC) platform designed with a cloud native architecture replacing Cobbler, Foreman, MaaS or similar technologies"
* [foreman](https://github.com/theforeman/foreman) - "From provisioning and configuration to orchestration and monitoring, Foreman integrates with your existing infrastructure to make operations easier"
* [ironic](https://github.com/openstack/ironic) "A service for managing and provisioning Bare Metal servers" - from OpenStack Foundation
* [LinuxKit](https://github.com/linuxkit/linuxkit) - "A toolkit for building secure, portable and lean operating systems for containers" - PXE support, focus on immutable infrastructure.
* [Lokomotive](https://github.com/kinvolk/lokomotive-kubernetes) - "Lokomotive is a 100% open-source Kubernetes distribution from the folks at Kinvolk"
* [MaaS](https://maas.io) - "Metal as a Service" by Canonnical
* [Matchbox](https://matchbox.psdn.io) - "Matchbox is a service that matches bare-metal machines to profiles that PXE boot and provision clusters"
* [Metal Stack](https://metal-stack.io) - "we believe kubernetes runs best on bare metal. we build an api to manage bare metal hardware and kubernetes on top of that." - uses Ironic
* [Metal³](https://github.com/metal3-io) - "Bare Metal Host Provisioning for Kubernetes" - with ClusterAPI support
* [mr-provisioner](https://github.com/mr-provisioner/mr-provisioner) - "Bare metal provisioning tool"
* [netboot.xyz](https://netboot.xyz) - "a way to PXE boot various operating system installers or utilities from one place within the BIOS without the need of having to go retrieve the media to run the tool."
* [pixiecore](https://github.com/danderson/netboot/tree/master/pixiecore) "Pixiecore is an tool to manage network booting of machines" by Dave Anderson
* [plundr](https://github.com/plunder-app/plunder) - "Plunder is a single-binary server that is all designed in order to make the provisioning of servers, platforms and applications easier." - with ClusterAPI support
* [RackHD](https://rackhd.readthedocs.io/en/latest/) - "a technology stack for enabling automated hardware management and orchestration through cohesive APIs. It serves as an abstraction layer between other management layers and the underlying, vendor-specific physical hardware."
* [Talos Systems](https://www.talos-systems.com/blog/building-arges-part-one-a-new-tool-for-datacenter-management/) - "A New Tool for Kubernetes Bare Metal" - with ClusterAPI support
* [Tinkerbell](https://tinkerbell.org) - "Tinkerbell is a bare metal provisioning engine. It’s built and maintained with love by the team at Packet."
* [Proxmox VE](https://www.proxmox.com/en/proxmox-ve) - full featured, easy to install Open-Source Virtualization Platform, comparable to VMWare VSphere. Compute, network and storage in a single solution. Ideal to set up a small (single node) to large (many nodes) virtualization environment on bare-metal servers. Also supports cloud-init so that VMs can be easily spun up from cloud images via the webinterface (similar to Droplets on Digital Ocean).

## Networking for bare-metal cloud

* [HAProxy](http://www.haproxy.org) - "The Reliable, High Performance TCP/HTTP Load Balancer" - often used in place of hardware LB.
* [inlets PRO](https://github.com/inlets/inlets-pro) - "inlets-pro is a Cloud Native Tunnel for L4 TCP traffic with built-in link encryption"
* [inlets-operator](https://github.com/inlets/inlets-operator) - "Public IPs for your private Kubernetes Services using inlets or inlets PRO"
* [inlets](https://docs.inlets.dev/#/) - "Cloud Native Tunnel written in Go." - HTTP tunnel
* [kube-vip](https://github.com/plunder-app/kube-vip) - "Kubernetes Control Plane Virtual IP and Load-Balancer"
* [MetalLB](https://metallb.universe.tf) - "MetalLB is a load-balancer implementation for bare metal Kubernetes clusters, using standard routing protocols."
* [Squid](http://www.squid-cache.org) - "a caching proxy for the Web supporting HTTP, HTTPS, FTP, and more. It reduces bandwidth and improves response times by caching and reusing frequently-requested web pages." - used with bare-metal to cache packages and ISO 
images.

## Bare-metal cloud

* [AWS bare metal](https://aws.amazon.com/blogs/aws/category/compute/amazon-ec2-bare-metal/)  - `x86_64` & `arm64`
* [cherryservers.com](https://www.cherryservers.com) - `x86_64`
* [Packet bare metal infrastructure](https://www.packet.com) - `x86_64` & `arm64`
* [Scaleway.com](https://www.scaleway.com) - `x86_64` & `arm64`
* [Vultr.com](https://www.vultr.com/products/bare-metal/) - `x86_64`

## Appendix

Sorting sections:

```bash
cat | sort -f
# Copy / paste

# Control + D
```
