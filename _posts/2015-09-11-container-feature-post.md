---
layout: post
title: "Container Camp London"
excerpt: "Container Camp London"
tags: [container post, london]
comments: true
image:
  feature: sample-image-4.jpg
  credit: WeGraphics
  creditlink: http://wegraphics.net/downloads/free-ultimate-blurred-background-pack/
---

# CCLDN 2015
My notes from Container Camp London 2015.

# Bryan Cantrill, [Joyent](https://www.joyent.com/)

# Towards a Containerized Future 
* chroot
* George Stevenson- Power of interface
* Docker Remote API-expressive, modern, robust
* Docker-future of containers
* [SmartOS](https://smartos.org/)-container-native since inception
* [Triton](http://www.joyent.com/?gclid=Cj0KEQjwj_SvBRC7k4DfkLHiuMABEiQAvPOaqSlpCg814EN5ezMOkXNWWv9qYro3BEl2PP1Lh-pwKGMaAvV98P8HAQ)-combines SmartOS and SmartDataCenter with a Docker Remote API endpoint
* open source
* Containers-future of application development
* Triton takes a modular approach
* Manta storage service-highly scalable, distributed object storage service

# Shannon Williams, [Rancher](http://rancher.com/)

# Introducing the Private Container Service
* Use cases
- more releases
- microservices
- accelerate the pace of innovation
- shorten environment provisioning
- high resiliency across different infrastructure
* orchestration systems-let teams decide what works for them
* Devops pipleine-develop, build, test deploy/upgrade
* Container service-constistent platform, public or private, users and teams get consistent infrastructure across multiple hosts and mulitple clouds-integrate with Devops
* Container Service includes: container orchestration, container infrastucture, container management (resources)

# Bryan Boreham, [Weaveworks](http://weave.works/)

# Distributed systems with (almost) no consensus 
* any system with more than one container is a distributed system
* products for distributed state-Etcd, Consul, Zookeeper
* use consensus algorithms Raft/Paxos
* Solution:CRDTS
* applied to IP allocation
* applied to DNS
* [Github](https://github.com/weaveworks)
* help@weave.works

# Mandy Waite, [Google](https://cloud.google.com/)

# Kubernetes: Changing the way that we think and talk about computing
* [Twitter](https://cloud.google.com/)
* [Bazel](http://bazel.io/)
* failures-preempt, machine shutdown, machine failure
* prod/non prod
* efficiency-limit,usage and reservation
* resource stranding
* bin packing
* [Kubernetes](http://kubernetes.io/)
* [Google Container Engine](https://cloud.google.com/container-engine/) 
* GA

# Stéphane Graber, [LXD](https://linuxcontainers.org/lxd/)

# An introduction to LXD, the container lighter-visor
* core of LXD is a daemon which offers a REST API to drive full system containers
* simple, fast, secure, scalable
* aimed running OS/system in container not app containers

# Arjan Schaff, [Luminis Technology](http://luminis-technologies.com/)

# Docker network performance in the public cloud.
* Cloud RTI
* Native networking test setup
* Qperf
* iperf3
* SDN to connect to your Docker cluster nodes
* Weave
* Flannel
* Calico
* Docker libnetwork
* best was Flannel VXLAN

# Alissa Bonas, [Red Hat](http://www.redhat.com/en)

# Managing Kubernetes and OpenShift with ManageIQ 
* Kubernetes
* OpenShift-PaaS for building and running applications
* [ManageIQ](http://manageiq.org/)
* open source cloud management platform
* replicators
* future-new dashboard, smart state analysis

# Miek Gieben, [Improbable](http://improbable.io/)

# Leveraging the DNS for fun and profit
* reactive infrastructure
* [Prometheus](http://prometheus.io/)-monitoring
* ELK
* [SkyDNS](https://github.com/skynetservices/skydns)-service discovery
* loadbalancing
* [Flagz](https://github.com/mwitkow-io/go-flagz)-monitoring

# Ben Hall, [Ocelot Uproar](https://twitter.com/ocelotuproar)

# Lessons from running potentially malicious code inside containers
* [Scrapbook](http://www.joinscrapbook.com/)
* docker diff
* future-the Warden-checking tool

# Diogo Mónica, [Docker](http://www.docker.com/)

# A Docker image walks into a Notary
* Security and Docker
* [TUF](http://theupdateframework.com/)
* [Docker Content Trust](https://blog.docker.com/2015/08/content-trust-docker-1-8/)
* [Notary](https://github.com/docker/notary)-validating publishing of content

# Loris Degioanni, [Sysdig](http://www.sysdig.org/)

# The Dark Art of Container Monitoring 
* Monitoring and troubleshooting-inspecting containers is not easy
* Htop
* Sysdig cloud

# Juan Batiz-Benet, [Protocol Labs](http://ipn.io/)

# Containers at Hyperspeed
* [IPFS](http://ipfs.io/)
+ Starship-containers and IPFS


