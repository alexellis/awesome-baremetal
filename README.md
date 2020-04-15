# awesome-baremetal

Bare-metal is awesome. Let's share our favourite tools. 

## Rules

* Ordered alphabetically (eventually consistent)
* Recent development or release (within the last 6 months)
* No defunct or abandoned projects
* Must show signs of traction or corporate use, no "my scripts for my homelab that only I use" submissions.
* No advertisements
* Format: `link to GitHub or website - "quote from GitHub repo or website"`

## Self-hosted

* [cobber](https://github.com/cobbler/cobbler) - "Cobbler is a Linux installation server that allows for rapid setup of network installation environments"
* [Digital Rebar](https://rebar.digital) - "Digital Rebar is the data center automation, provisioning and infrastructure as code (IaC) platform designed with a cloud native architecture replacing Cobbler, Foreman, MaaS or similar technologies"
* [ironic](https://github.com/openstack/ironic) "A service for managing and provisioning Bare Metal servers" - from OpenStack Foundation
* [Lokomotiv](https://github.com/kinvolk/lokomotive-kubernetes) - "Lokomotive is a 100% open-source Kubernetes distribution from the folks at Kinvolk"
* [MaaS](https://maas.io) - "Metal as a Service" by Canonnical
* [Matchbox](https://matchbox.psdn.io) - "Matchbox is a service that matches bare-metal machines to profiles that PXE boot and provision clusters"
* [Metal Stack](https://metal-stack.io) - "we believe kubernetes runs best on bare metal. we build an api to manage bare metal hardware and kubernetes on top of that." - uses Ironic
* [Metal³](https://github.com/metal3-io) - "Bare Metal Host Provisioning for Kubernetes"
* [netboot.xyz](https://netboot.xyz) - "a way to PXE boot various operating system installers or utilities from one place within the BIOS without the need of having to go retrieve the media to run the tool."
* [pixiecore](https://github.com/danderson/netboot/tree/master/pixiecore) "Pixiecore is an tool to manage network booting of machines" by Dave Anderson
* [plundr](https://github.com/plunder-app/plunder) - "Plunder is a single-binary server that is all designed in order to make the provisioning of servers, platforms and applications easier."
* [Tinkerbell](https://tinkerbell.org) - "Tinkerbell is a bare metal provisioning engine. It’s built and maintained with love by the team at Packet."

## Networking for bare-metal cloud

* [MetalLB](https://metallb.universe.tf) - "MetalLB is a load-balancer implementation for bare metal Kubernetes clusters, using standard routing protocols."
* [inlets](https://docs.inlets.dev/#/) - "Cloud Native Tunnel written in Go." - HTTP tunnel
* [inlets PRO](https://github.com/inlets/inlets-pro) - "inlets-pro is a Cloud Native Tunnel for L4 TCP traffic"
* [inlets-operator](https://github.com/inlets/inlets-operator) - "Public IPs for your private Kubernetes Services"
* [kube-vip](https://github.com/plunder-app/kube-vip) - "Kubernetes Control Plane Virtual IP and Load-Balancer"

## Bare-metal cloud

* [AWS bare metal](https://aws.amazon.com/blogs/aws/category/compute/amazon-ec2-bare-metal/)  - `x86_64` & `arm64`
* [cherryservers.com](https://www.cherryservers.com) - `x86_64`
* [Packet bare metal infrastructure](https://www.packet.com) - `x86_64` & `arm64`
* [Scaleway.com](https://www.scaleway.com) - `x86_64` & `arm64`

## Appendix

Sorting sections:

```bash
cat | sort -f
# Copy / paste

# Control + D
```

Author: [Alex Ellis](https://www.alexellis.io) - CNCF Ambassador, OpenFaaS & Inlets Founder.