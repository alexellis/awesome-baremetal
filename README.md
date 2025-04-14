# awesome-baremetal

Bare-metal is awesome. Let's share our favourite tools.

## Rules

* Ordered alphabetically (eventually consistent)
* Recent development or release (within the last 6 months) - or deemed relevant by curator
* No defunct or abandoned projects
* Must show signs of traction or corporate use
 * No "my scripts for my homelab that only I use" submissions.
 * This list is curated and not a museum, so the project should be active and relevant
* Format: `link to GitHub or website - "quote from GitHub repo or website"`

🏆 Commercial products will require [a sponsorship](https://github.com/sponsors/alexellis) and are added with (sponsored) in brackets in the relevant category.

Sponsorship [tiers](https://github.com/sponsors/alexellis):

* "Top of rack" - featured at the top of this repository
* "1U" - a link in the relevant section plus the text "(sponsored)"

Curator: [Alex Ellis](https://www.alexellis.io) - founder of [OpenFaaS](https://openfaas.com/), [actuated.dev](https://actuated.dev) & [Inlets](https://docs.inlets.dev/).

## Self-hosted tools for bare-metal management

* [bmc-toolbox](https://github.com/bmc-toolbox) - "bmc-toolbox is bunch of tools to ease BMC management"
* [cobbler](https://github.com/cobbler/cobbler) - "Cobbler is a Linux installation server that allows for rapid setup of network installation environments"
* [Collins](https://tumblr.github.io/collins/) - "CMDB / state machine for infrastructure automation"
* [confluent](https://github.com/lenovo/confluent) - "Service for onboarding and management of baremetal server BMCs and PXE"
* [foreman](https://github.com/theforeman/foreman) - "From provisioning and configuration to orchestration and monitoring, Foreman integrates with your existing infrastructure to make operations easier"
* [iDRAC 6 dockerized](https://github.com/DomiStyle/docker-idrac6) "Allows access to the iDRAC 6 console without installing Java or messing with Java Web Start." by DomiStyle
* [ironic](https://github.com/openstack/ironic) "A service for managing and provisioning Bare Metal servers" - from OpenStack Foundation
* [LinuxKit](https://github.com/linuxkit/linuxkit) - "A toolkit for building secure, portable and lean operating systems for containers" - PXE support, focus on immutable infrastructure.
* [Typhoon](https://github.com/poseidon/typhoon/) - "A minimal and free Kubernetes distribution with Terraform backed by Fedora CoreOS or Flatcar Linux"
* [MAAS](https://maas.io) - "Metal as a Service" by Canonical
* [Matchbox](https://matchbox.psdn.io) - "Matchbox is a service that matches bare-metal machines to profiles that PXE boot and provision clusters"
* [metalk8s](https://github.com/scality/metalk8s) - "MetalK8s was launched to make it easier to run Kubernetes (K8s) on bare-metal servers that need persistent storage" by Scality
* [Metal Stack](https://metal-stack.io) - "we believe kubernetes runs best on bare metal. we build an api to manage bare metal hardware and kubernetes on top of that."
* [Metal³](https://github.com/metal3-io) - "Bare Metal Host Provisioning for Kubernetes" - with ClusterAPI support and built with Ironic
* [mr-provisioner](https://github.com/mr-provisioner/mr-provisioner) - "Bare metal provisioning tool"
* [netboot.xyz](https://netboot.xyz) - "a way to PXE boot various operating system installers or utilities from one place within the BIOS without the need of having to go retrieve the media to run the tool."
* [pixiecore](https://github.com/danderson/netboot/tree/master/pixiecore) "Pixiecore is an tool to manage network booting of machines" by Dave Anderson
* [RackHD](https://rackhd.readthedocs.io/en/latest/) - "a technology stack for enabling automated hardware management and orchestration through cohesive APIs. It serves as an abstraction layer between other management layers and the underlying, vendor-specific physical hardware."
* [Sidero Labs](https://www.siderolabs.com/platform/bare-metal-kubernetes-sidero/) - (Formerly known as Talos Systems) "A New Tool for Kubernetes Bare Metal" - with ClusterAPI support
* [Tinkerbell](https://tinkerbell.org) - "Tinkerbell is a bare metal provisioning engine. It’s built and maintained with love by the team at Equinix Metal."
* [Warewulf](https://github.com/warewulf/warewulf) - "Warewulf is a stateless and diskless container operating system provisioning system for large clusters of bare metal and/or virtual systems."

### Inactive projects

These projects may be archived but are useful for learning and inspiration.

* [Razor](https://github.com/puppetlabs/razor-server) (archived) - "Razor is next generation provisioning software that handles bare metal hardware and virtual server provisioning"
* [plundr](https://github.com/plunder-app/plunder) (inactive on GitHub - 4yrs) - "Plunder is a single-binary server that is all designed in order to make the provisioning of servers, platforms and applications easier." - with ClusterAPI support

## Networking for bare-metal cloud

Tools often used with bare-metal tooling:

* [dnsmasq](http://www.thekelleys.org.uk/dnsmasq/doc.html) - "Dnsmasq provides network infrastructure for small networks: DNS, DHCP, router advertisement and network boot."
* [HAProxy](http://www.haproxy.org) - "The Reliable, High Performance TCP/HTTP Load Balancer" - often used in place of hardware LB.
* [inlets](https://github.com/inlets/inlets-pro) - "A Cloud Native Tunnel for L4 TCP and L7 HTTPS" (sponsored)
* [inlets-operator](https://github.com/inlets/inlets-operator) - "Public IPs for your private Kubernetes Services using inlets"
* [kube-vip](https://github.com/plunder-app/kube-vip) - "Kubernetes Control Plane Virtual IP and Load-Balancer"
* [MetalLB](https://metallb.universe.tf) - "MetalLB is a load-balancer implementation for bare metal Kubernetes clusters, using standard routing protocols."
* [PorterLB](https://github.com/kubesphere/porterlb) - "PorterLB is an open-source load balancer implementation designed for bare-metal Kubernetes clusters."
* [Squid](http://www.squid-cache.org) - "a caching proxy for the Web supporting HTTP, HTTPS, FTP, and more. It reduces bandwidth and improves response times by caching and reusing frequently-requested web pages." - used with bare-metal to cache packages and ISO images
* [Varnish-Cache](https://github.com/varnishcache/varnish-cache) Varnish Cache, the high-performance HTTP accelerator

## Bare-metal cloud

Rent bare-metal from a cloud vendor on an hourly, monthly, or longer term commitment.

For a more comprehensive list see the actuated docs: [Provision a Server](https://docs.actuated.com/provision-server/). [Actuated](https://actuated.com) runs CI in ephemeral microVMs using Firecracker so requires bare-metal or nested virtualisation.

`x86_64` and / or arm64:

* [AlibabaCloud bare metal](https://www.alibabacloud.com/product/ebm) - `x86_64` & `arm64`
* [AWS Bare Metal](https://aws.amazon.com/blogs/aws/category/compute/amazon-ec2-bare-metal/)  - `x86_64` & `arm64`
* [Equinix Metal bare-metal infrastructure](https://metal.equinix.com/) - `x86_64` & `arm64` (End of Life)
* [Hetzner](https://hetzner.com) - `x86_64` and `arm64` (Best value for money, Europe region only)

The Raspberry Pi 4B and 5 provide arm64 support with several operating systems like Ubuntu LTS being available. An NVMe can be plugged in over USB-C or PCIe, see also: [Upgrade your Raspberry Pi 4 with a NVMe boot drive](https://alexellisuk.medium.com/upgrade-your-raspberry-pi-4-with-a-nvme-boot-drive-d9ab4e8aa3c2) and [Booting the Raspberry Pi 5 from NVMe](https://blog.alexellis.io/booting-the-raspberry-pi-5-from-nvme/)

The Mac Mini M1 and Mac Mini M2 can be installed with [Asahi Linux](https://asahilinux.org), which then provides one of the fastest CPU/storage options for a self-hosted local Arm64 Linux host.

`x86_x64` only:

* [cherryservers.com](https://www.cherryservers.com) - `x86_64` only
* [FastHosts bare metal](https://www.fasthosts.co.uk/dedicated-servers) - `x86_x64`
* [hivelocity](https://www.hivelocity.net) - `x86_64` only
* [IBM Cloud](https://www.ibm.com/uk-en/cloud/bare-metal-servers) - `x86_64` only
* [Ionos](https://ionos.co.uk) - `x86_64` only
* [latitude.sh](https://latitude.sh) - `x86_64`
* [Oracle Cloud Infrastructure (OCI)](https://www.oracle.com/cloud/compute/arm/) - `arm64` only
* [OVHcloud bare metal](https://www.ovh.com/world/dedicated-servers) - `x86_64`
* [phoenixnap NAP](https://phoenixnap.com/bare-metal-cloud/instances)
* [Scaleway.com](https://www.scaleway.com) - `x86_64` [`arm64` is now EOL]( https://www.theregister.com/2020/04/21/scaleway_arm64_cloud_end_of_life/)
* [Vultr.com](https://www.vultr.com/products/bare-metal/) - `x86_64` only
* [InterServer.com](https://www.interserver.net/dedicated/) - `x86_64` only

## Open Source Virtualization

Orchestration of Virtual Machines (VMs) using KVM.

* [Firecracker](https://firecracker-microvm.github.io/)
* [Cloud Hypervisor](https://github.com/cloud-hypervisor/cloud-hypervisor)
* [QEMU](https://www.qemu.org/) - QEMU is the traditional hypervisor, which now contains a ["microvm" profile](https://www.qemu.org/docs/master/system/i386/microvm.html)
* [oVirt](https://www.ovirt.org/) - "oVirt is an open-source distributed virtualization solution, designed to manage your entire enterprise infrastructure. oVirt uses the trusted KVM hypervisor and is built upon several other community projects, including libvirt, Gluster, PatternFly, and Ansible."
* [Ganeti](https://github.com/ganeti/ganeti) - "Open source hyperconverged VM platform that scales from several to thousands of bare metal servers. Originally written for internal use at Google."
* [Proxmox VE](https://www.proxmox.com/en/proxmox-ve/get-started) - "Proxmox VE is a complete open-source platform for all-inclusive enterprise virtualization that tightly integrates KVM hypervisor and LXC containers, software-defined storage and networking functionality on a single platform"
* [actuated.dev](https://actuated.dev) - blazing fast CI for GitHub Actions using Firecracker (sponsored)

## Storage for bare-metal

* [OpenEBS](https://openebs.io/) - "Open Source Container Attached Storage, simplifies running Stateful Applications on Kubernetes.
* [Rook](https://rook.io/) - "Open-Source, Cloud-Native Storage Orchestrator for Kubernetes"
* [SeaweedFS](https://github.com/seaweedfs/seaweedfs) - Apache 2.0 - "SeaweedFS is a fast distributed storage system for blobs, objects, files, and data lake, for billions of files"
* [Minio](https://min.io/) - AGPLv3 and commercial license for Object Storage.

## Appendix

### Sorting sections

Each section should be sorted after it's been updated, here's how you can do that with bash.

```bash
cat | sort --ignore-case
# Copy / paste

# Control + D
```

Then paste the output back into the document.
