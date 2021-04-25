# awesome-baremetal

Bare-metal is awesome. Let's share our favourite tools.

## Rules

* Ordered alphabetically (eventually consistent)
* Recent development or release (within the last 6 months) - or deemed relevant by curator
* No defunct or abandoned projects
* Must show signs of traction or corporate use
 * No "my scripts for my homelab that only I use" submissions.
 * This list is curated and not a museum, so the project should be active and relevant
* No advertisements
* Format: `link to GitHub or website - "quote from GitHub repo or website"`

Curator: [Alex Ellis](https://www.alexellis.io) - CNCF Ambassador, [OpenFaaS](https://openfaas.com/) & [Inlets](https://docs.inlets.dev/) Founder.

## Self-hosted

* [bmc-toolbox](https://github.com/bmc-toolbox) - "bmc-toolbox is bunch of tools to ease BMC management"
* [cobbler](https://github.com/cobbler/cobbler) - "Cobbler is a Linux installation server that allows for rapid setup of network installation environments"
* [Collins](https://tumblr.github.io/collins/) - "CMDB / state machine for infrastructure automation"
* [confluent](https://github.com/lenovo/confluent) - "Service for onboarding and management of baremetal server BMCs and PXE"
* [Digital Rebar](https://rebar.digital) - "Digital Rebar is the data center automation, provisioning and infrastructure as code (IaC) platform designed with a cloud native architecture replacing Cobbler, Foreman, MaaS or similar technologies"
* [foreman](https://github.com/theforeman/foreman) - "From provisioning and configuration to orchestration and monitoring, Foreman integrates with your existing infrastructure to make operations easier"
* [ironic](https://github.com/openstack/ironic) "A service for managing and provisioning Bare Metal servers" - from OpenStack Foundation
* [LinuxKit](https://github.com/linuxkit/linuxkit) - "A toolkit for building secure, portable and lean operating systems for containers" - PXE support, focus on immutable infrastructure.
* [Lokomotive](https://github.com/kinvolk/lokomotive-kubernetes) - "Lokomotive is a 100% open-source Kubernetes distribution from the folks at Kinvolk"
* [MaaS](https://maas.io) - "Metal as a Service" by Canonical
* [Matchbox](https://matchbox.psdn.io) - "Matchbox is a service that matches bare-metal machines to profiles that PXE boot and provision clusters"
* [metalk8s](https://github.com/scality/metalk8s) - "MetalK8s was launched to make it easier to run Kubernetes (K8s) on bare-metal servers that need persistent storage" by Scality
* [MetalSoft](https://metalsoft.io) - "Intelligent bare metal automation software platform that facilitates the building and operations of cloud-native infrastructures spanning from the core to the edge."
* [Metal Stack](https://metal-stack.io) - "we believe kubernetes runs best on bare metal. we build an api to manage bare metal hardware and kubernetes on top of that."
* [Metal³](https://github.com/metal3-io) - "Bare Metal Host Provisioning for Kubernetes" - with ClusterAPI support and built with Ironic
* [mr-provisioner](https://github.com/mr-provisioner/mr-provisioner) - "Bare metal provisioning tool"
* [netboot.xyz](https://netboot.xyz) - "a way to PXE boot various operating system installers or utilities from one place within the BIOS without the need of having to go retrieve the media to run the tool."
* [pixiecore](https://github.com/danderson/netboot/tree/master/pixiecore) "Pixiecore is an tool to manage network booting of machines" by Dave Anderson
* [plundr](https://github.com/plunder-app/plunder) - "Plunder is a single-binary server that is all designed in order to make the provisioning of servers, platforms and applications easier." - with ClusterAPI support
* [RackHD](https://rackhd.readthedocs.io/en/latest/) - "a technology stack for enabling automated hardware management and orchestration through cohesive APIs. It serves as an abstraction layer between other management layers and the underlying, vendor-specific physical hardware."
* [Razor](https://github.com/puppetlabs/razor-server) - "Razor is next generation provisioning software that handles bare metal hardware and virtual server provisioning"
* [Sidero](https://www.sidero.dev/) - "Bare Metal lifecycle management for Kubernetes clusters" - with ClusterAPI support
* [Talos Systems](https://www.talos-systems.com/blog/building-arges-part-one-a-new-tool-for-datacenter-management/) - "A New Tool for Kubernetes Bare Metal" - with ClusterAPI support
* [Tinkerbell](https://tinkerbell.org) - "Tinkerbell is a bare metal provisioning engine. It’s built and maintained with love by the team at Equinix Metal."
* [Uyuni Project](https://www.uyuni-project.org/) - "The best systems management solution for your enterprise Linux. From provisioning bare-metal on-premise to managing clusters on the cloud, from tens of managed systems to tens of thousands. Powered by Salt."

## Networking for bare-metal cloud

* [dnsmasq](http://www.thekelleys.org.uk/dnsmasq/doc.html) - "Dnsmasq provides network infrastructure for small networks: DNS, DHCP, router advertisement and network boot."
* [HAProxy](http://www.haproxy.org) - "The Reliable, High Performance TCP/HTTP Load Balancer" - often used in place of hardware LB.
* [inlets PRO](https://github.com/inlets/inlets-pro) - "inlets-pro is a Cloud Native Tunnel for L4 TCP traffic with built-in link encryption"
* [inlets-operator](https://github.com/inlets/inlets-operator) - "Public IPs for your private Kubernetes Services using inlets or inlets PRO"
* [inlets](https://docs.inlets.dev/#/) - "Cloud Native Tunnel written in Go." - HTTP tunnel
* [kube-vip](https://github.com/plunder-app/kube-vip) - "Kubernetes Control Plane Virtual IP and Load-Balancer"
* [MetalLB](https://metallb.universe.tf) - "MetalLB is a load-balancer implementation for bare metal Kubernetes clusters, using standard routing protocols."
* [PorterLB](https://github.com/kubesphere/porterlb) - "PorterLB is an open-source load balancer implementation designed for bare-metal Kubernetes clusters."
* [Squid](http://www.squid-cache.org) - "a caching proxy for the Web supporting HTTP, HTTPS, FTP, and more. It reduces bandwidth and improves response times by caching and reusing frequently-requested web pages." - used with bare-metal to cache packages and ISO images
* [Varnish-Cache](https://github.com/varnishcache/varnish-cache) Varnish Cache, the high-performance HTTP accelerator
images.

## Bare-metal cloud

* [AlibabaCloud bare metal](https://www.alibabacloud.com/product/ebm) - `x86_64` & `arm64`
* [AWS bare metal](https://aws.amazon.com/blogs/aws/category/compute/amazon-ec2-bare-metal/)  - `x86_64` & `arm64`
* [Bigstep Metal Cloud](https://bigstep.com/uk/products/bare-metal-cloud) - `x86_64`
* [cherryservers.com](https://www.cherryservers.com) - `x86_64`
* [DedicatedServer.io](https://www.dedicatedserver.io)  - `x86_64` & `arm64`
* [Equinix Metal](https://metal.equinix.com/) - `x86_64` & `arm64` - (Acquired from Packet)
* [FastHosts bare metal](https://www.fasthosts.co.uk/dedicated-servers) - `x86_x64`
* [Maxihost.com](https://www.maxihost.com) - `x86_64` & `arm64`
* [Mirantis Cloud Platform](https://www.mirantis.com/software/mcp/) - `x86_64`
* [OVHcloud bare metal](https://www.ovh.com/world/dedicated-servers) - `x86_64`
* [Packet bare metal infrastructure](https://www.packet.com) - `x86_64` & `arm64`
* [Rackspace OnMetal](https://www.rackspace.com/openstack/public/servers/onmetal) - `x86_64`
* [Scaleway.com](https://www.scaleway.com) - `x86_64`
* [Vultr.com](https://www.vultr.com/products/bare-metal/) - `x86_64`

## Open Source Virtualization

This section is for projects like Proxmox, for where the community feel strongly, but their submission doesn't fit into the bare-metal category.

* [oVirt](https://www.ovirt.org/) - "oVirt is an open-source distributed virtualization solution, designed to manage your entire enterprise infrastructure. oVirt uses the trusted KVM hypervisor and is built upon several other community projects, including libvirt, Gluster, PatternFly, and Ansible."
* [Ganeti](https://github.com/ganeti/ganeti) - "Open source hyperconverged VM platform that scales from several to thousands of bare metal servers. Originally written for internal use at Google."
* [Proxmox VE](https://www.proxmox.com/en/proxmox-ve/get-started) - "Proxmox VE is a complete open-source platform for all-inclusive enterprise virtualization that tightly integrates KVM hypervisor and LXC containers, software-defined storage and networking functionality on a single platform"

## Storage for bare-metal

* [OpenEBS](https://openebs.io/) - "Open Source Container Attached Storage, simplifies running Stateful Applications on Kubernetes.
* [Rook](https://rook.io/) - "Open-Source, Cloud-Native Storage Orchestrator for Kubernetes"
* [Longhorn](https://github.com/longhorn/longhorn) - "Rancher Longhorn distributed block storage system for Kubernetes"


## Appendix

### Sorting sections

Each section should be sorted after it's been updated, here's how you can do that with bash.

```bash
cat | sort -f
# Copy / paste

# Control + D
```

Then paste the output back into the document.
