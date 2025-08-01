---
title: Libraries and tools
weight: 1300
description: A listing of etcd tools and client libraries
---

Note that third-party libraries and tools (not hosted on [etcd-io main repository](https://github.com/etcd-io)) mentioned below are not tested or maintained by the etcd team. Before using them, users are recommended to read and investigate them.

## Tools

- [etcdctl](https://github.com/etcd-io/etcd/tree/master/etcdctl) - A command line client for etcd
- [etcd-dump](https://npmjs.org/package/etcd-dump) - Command line utility for dumping/restoring etcd.
- [etcd-fs](https://github.com/xetorthio/etcd-fs) - FUSE filesystem for etcd
- [etcddir](https://github.com/rekby/etcddir) - Realtime sync etcd and local directory. Work with windows and linux.
- [etcd-browser](https://github.com/henszey/etcd-browser) - A web-based key/value editor for etcd using AngularJS
- [etcd-lock](https://github.com/datawisesystems/etcd-lock) - Master election & distributed r/w lock implementation using etcd - Supports v2
- [etcd-console](https://github.com/matishsiao/etcd-console) - A web-base key/value editor for etcd using PHP
- [etcd-viewer](https://github.com/nikfoundas/etcd-viewer) - An etcd key-value store editor/viewer written in Java
- [etcdtool](https://github.com/mickep76/etcdtool) - Export/Import/Edit etcd directory as JSON/YAML/TOML and Validate directory using JSON schema
- [etcdloadtest](https://github.com/sinsharat/etcdloadtest) - A command line load test client for etcd version 3.0 and above.
- [lucas](https://github.com/ringtail/lucas) - A web-based key-value viewer for kubernetes etcd3.0+ cluster.
- [etcd-manager](https://etcdmanager.io) - A modern, efficient, multi-platform and free etcd 3.x GUI & client tool. Available for Windows, Linux and Mac.
- [etcd-backup-restore](https://github.com/gardener/etcd-backup-restore) - Utility to periodically and incrementally backup and restore the etcd.
- [etcd-druid](https://github.com/gardener/etcd-druid) - A Kubernetes operator to deploy etcd clusters and manage day-2 operations.
- [etcdadm](https://github.com/kubernetes-sigs/etcdadm) - A command-line tool for operating an etcd cluster.
- [etcd-defrag](https://github.com/ahrtr/etcd-defrag) - An easier to use and smarter etcd defragmentation tool.
- [etcdhelper](https://github.com/tsonglew/intellij-etcdhelper) - An intellij platform plugin for etcd.
- [etcd-workbench](https://github.com/tzfun/etcd-workbench) - A free and powerful ui client for etcd v3. Provides desktop application and web packages.

## Libraries

The sections below list etcd client libraries by language.

### Go

- [etcd/client/v3](https://github.com/etcd-io/etcd/tree/main/client/v3) - the officially maintained Go client for v3
- [etcd/client/v2](https://github.com/etcd-io/etcd/tree/release-3.5/client/v2) - the officially maintained Go client for v2
- [go-etcd](https://github.com/coreos/go-etcd) - the deprecated official client. May be useful for older (<2.0.0) versions of etcd.
- [encWrapper](https://github.com/lumjjb/etcd/tree/enc_wrapper/clientwrap/encwrapper) - encWrapper is an encryption wrapper for the etcd client Keys API/KV.

### Java

- [coreos/jetcd](https://github.com/etcd-io/jetcd) - Supports v3
- [boonproject/etcd](https://github.com/boonproject/boon/blob/master/etcd/README.md) - Supports v2, Async/Sync and waits
- [justinsb/jetcd](https://github.com/justinsb/jetcd)
- [diwakergupta/jetcd](https://github.com/diwakergupta/jetcd) - Supports v2
- [jurmous/etcd4j](https://github.com/jurmous/etcd4j) - Supports v2, Async/Sync, waits and SSL
- [AdoHe/etcd4j](http://github.com/AdoHe/etcd4j) - Supports v2 (enhance for real production cluster)
- [cdancy/etcd-rest](https://github.com/cdancy/etcd-rest) - Uses jclouds to provide a complete implementation of v2 API.
- [IBM/etcd-java](https://github.com/IBM/etcd-java)

### Scala

- [maciej/etcd-client](https://github.com/maciej/etcd-client) - Supports v2. Akka HTTP-based fully async client
- [eiipii/etcdhttpclient](https://bitbucket.org/eiipii/etcdhttpclient) - Supports v2. Async HTTP client based on Netty and Scala Futures.
- [mingchuno/etcd4s](https://github.com/mingchuno/etcd4s) - Supports v3 using gRPC with optional Akka Stream support.

### Perl

- [hexfusion/perl-net-etcd](https://github.com/hexfusion/perl-net-etcd) - Supports v3 grpc gateway HTTP API
- [robn/p5-etcd](https://github.com/robn/p5-etcd) - Supports v2

### Python

- [kragniz/python-etcd3](https://github.com/kragniz/python-etcd3) - Client for v3
- [jplana/python-etcd](https://github.com/jplana/python-etcd) - Supports v2
- [russellhaering/txetcd](https://github.com/russellhaering/txetcd) - a Twisted Python library
- [cholcombe973/autodock](https://github.com/cholcombe973/autodock) - A docker deployment automation tool
- [lisael/aioetcd](https://github.com/lisael/aioetcd) - (Python 3.4+) Asyncio coroutines client (Supports v2)
- [txaio-etcd](https://github.com/crossbario/txaio-etcd) - Asynchronous etcd v3-only client library for Twisted (today) and asyncio (future)
- [aioetcd3](https://github.com/gaopeiliang/aioetcd3) - (Python 3.6+) etcd v3 API for asyncio
- [Revolution1/etcd3-py](https://github.com/Revolution1/etcd3-py) - (python2.7 and python3.5+) Python client for etcd v3, using gRPC-JSON-Gateway

### Node

- [mixer/etcd3](https://github.com/mixer/etcd3) - Supports v3
- [stianeikeland/node-etcd](https://github.com/stianeikeland/node-etcd) - Supports v2 (w Coffeescript)
- [lavagetto/nodejs-etcd](https://github.com/lavagetto/nodejs-etcd) - Supports v2
- [deedubs/node-etcd-config](https://github.com/deedubs/node-etcd-config) - Supports v2

### Ruby

- [iconara/etcd-rb](https://github.com/iconara/etcd-rb)
- [jpfuentes2/etcd-ruby](https://github.com/jpfuentes2/etcd-ruby)
- [ranjib/etcd-ruby](https://github.com/ranjib/etcd-ruby) - Supports v2
- [davissp14/etcdv3-ruby](https://github.com/davissp14/etcdv3-ruby) - Supports v3

### C

- [apache/celix/etcdlib](https://github.com/apache/celix/tree/master/libs/etcdlib) - Supports v2
- [jdarcy/etcd-api](https://github.com/jdarcy/etcd-api) - Supports v2
- [shafreeck/cetcd](https://github.com/shafreeck/cetcd) - Supports v2

### C++

- [edwardcapriolo/etcdcpp](https://github.com/edwardcapriolo/etcdcpp) - Supports v2
- [suryanathan/etcdcpp](https://github.com/suryanathan/etcdcpp) - Supports v2 (with waits)
- [nokia/etcd-cpp-api](https://github.com/nokia/etcd-cpp-api) - Supports v2
- [nokia/etcd-cpp-apiv3](https://github.com/nokia/etcd-cpp-apiv3) - Supports v3

### Clojure

- [aterreno/etcd-clojure](https://github.com/aterreno/etcd-clojure)
- [dwwoelfel/cetcd](https://github.com/dwwoelfel/cetcd) - Supports v2
- [rthomas/clj-etcd](https://github.com/rthomas/clj-etcd) - Supports v2

### Erlang

- [marshall-lee/etcd.erl](https://github.com/marshall-lee/etcd.erl) - Supports v2
- [zhongwencool/eetcd](https://github.com/zhongwencool/eetcd) - Supports v3+ (GRPC only)

### Elixir

- [team-telnyx/etcdex](https://github.com/team-telnyx/etcdex) - Supports v3+ (GRPC only)

### .NET

- [wangjia184/etcdnet](https://github.com/wangjia184/etcdnet) - Supports v2
- [drusellers/etcetera](https://github.com/drusellers/etcetera)
- [shubhamranjan/dotnet-etcd](https://github.com/shubhamranjan/dotnet-etcd) - Supports v3+ (GRPC only)
- [SimplifyNet/Etcd.Microsoft.Extensions.Configuration](https://github.com/SimplifyNet/Etcd.Microsoft.Extensions.Configuration)

### PHP

- [linkorb/etcd-php](https://github.com/linkorb/etcd-php)
- [activecollab/etcd](https://github.com/activecollab/etcd)
- [ouqiang/etcd-php](https://github.com/ouqiang/etcd-php) - Client for v3 gRPC gateway

### Haskell

- [wereHamster/etcd-hs](https://github.com/wereHamster/etcd-hs)

### R

- [ropensci/etseed](https://github.com/ropensci/etseed)

### Nim

- [etcd_client](https://github.com/FedericoCeratto/nim-etcd-client)

### Tcl

- [efrecon/etcd-tcl](https://github.com/efrecon/etcd-tcl) - Supports v2, except wait.

### Rust

- [jimmycuadra/rust-etcd](https://github.com/jimmycuadra/rust-etcd) - Supports v2

### Gradle

- [gradle-etcd-rest-plugin](https://github.com/cdancy/gradle-etcd-rest-plugin) - Supports v2

### Lua

- [api7/lua-resty-etcd](https://github.com/api7/lua-resty-etcd) - Supports v2 and v3 (grpc gateway HTTP API)

## Deployment tools

### Chef integrations

- [coderanger/etcd-chef](https://github.com/coderanger/etcd-chef)

### Chef cookbooks

- [spheromak/etcd-cookbook](https://github.com/spheromak/etcd-cookbook)

### BOSH releases

- [cloudfoundry-community/etcd-boshrelease](https://github.com/cloudfoundry-community/etcd-boshrelease)
- [cloudfoundry/cf-release](https://github.com/cloudfoundry/cf-release/tree/master/jobs/etcd)

## Projects using etcd

- [etcd Raft users](https://github.com/etcd-io/etcd/blob/master/raft/README.md#notable-users) - projects using etcd's raft library implementation.
- [apache/celix](https://github.com/apache/celix) - an implementation of the OSGi specification adapted to C and C++
- [binocarlos/yoda](https://github.com/binocarlos/yoda) - etcd + ZeroMQ
- [blox/blox](https://github.com/blox/blox) - a collection of open source projects for container management and orchestration with AWS ECS
- [calavera/active-proxy](https://github.com/calavera/active-proxy) - HTTP Proxy configured with etcd
- [chain/chain](https://github.com/chain/chain) - software designed to operate and connect to highly scalable permissioned blockchain networks
- [derekchiang/etcdplus](https://github.com/derekchiang/etcdplus) - A set of distributed synchronization primitives built upon etcd
- [go-discover](https://github.com/flynn/go-discover) - service discovery in Go
- [gleicon/goreman](https://github.com/gleicon/goreman/tree/etcd) - Branch of the Go Foreman clone with etcd support
- [garethr/hiera-etcd](https://github.com/garethr/hiera-etcd) - Puppet hiera backend using etcd
- [mattn/etcd-vim](https://github.com/mattn/etcd-vim) - SET and GET keys from inside vim
- [mattn/etcdenv](https://github.com/mattn/etcdenv) - "env" shebang with etcd integration
- [kelseyhightower/confd](https://github.com/kelseyhightower/confd) - Manage local app config files using templates and data from etcd
- [configdb](https://git.autistici.org/ai/configdb/tree/master) - A REST relational abstraction on top of arbitrary database backends, aimed at storing configs and inventories.
- [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) - Container cluster manager introduced by Google.
- [mailgun/vulcand](https://github.com/mailgun/vulcand) - HTTP proxy that uses etcd as a configuration backend.
- [duedil-ltd/discodns](https://github.com/duedil-ltd/discodns) - Simple DNS nameserver using etcd as a database for names and records.
- [skynetservices/skydns](https://github.com/skynetservices/skydns) - RFC compliant DNS server
- [xordataexchange/crypt](https://github.com/xordataexchange/crypt) - Securely store values in etcd using GPG encryption
- [spf13/viper](https://github.com/spf13/viper) - Go configuration library, reads values from ENV, pflags, files, and etcd with optional encryption
- [lytics/metafora](https://github.com/lytics/metafora) - Go distributed task library
- [ryandoyle/nss-etcd](https://github.com/ryandoyle/nss-etcd) - A GNU libc NSS module for resolving names from etcd.
- [Gru](https://github.com/dnaeon/gru) - Orchestration made easy with Go
- [Vitess](http://vitess.io/) - Vitess is a database clustering system for horizontal scaling of MySQL.
- [lclarkmichalek/etcdhcp](https://github.com/lclarkmichalek/etcdhcp) - DHCP server that uses etcd for persistence and coordination.
- [openstack/networking-vpp](https://github.com/openstack/networking-vpp) - A networking driver that programs the [FD.io VPP dataplane](https://wiki.fd.io/view/VPP) to provide [OpenStack](https://www.openstack.org/) cloud virtual networking
- [OpenStack](https://github.com/openstack/governance/blob/master/reference/base-services.rst) - OpenStack services can rely on etcd as a base service.
- [CoreDNS](https://github.com/coredns/coredns/tree/master/plugin/etcd) - CoreDNS is a DNS server that chains plugins, part of CNCF and Kubernetes
- [Uber M3](https://github.com/m3db/m3) - M3: Uber’s Open Source, Large-scale Metrics Platform for Prometheus
- [Rook](https://github.com/rook/rook) - Storage Orchestration for Kubernetes
- [Patroni](https://github.com/zalando/patroni) - A template for PostgreSQL High Availability with ZooKeeper, etcd, or Consul
- [Trillian](https://github.com/google/trillian) - Trillian implements a Merkle tree whose contents are served from a data storage layer, to allow scalability to extremely large trees.
- [Apache APISIX](https://github.com/apache/apisix) - Apache APISIX is a dynamic, real-time, high-performance API gateway.
- [purpleidea/mgmt](https://github.com/purpleidea/mgmt) - Next generation distributed, event-driven, parallel config management!
- [Portworx/kvdb](https://docs.portworx.com/concepts/internal-kvdb/) - The internal kvdb for storing Portworx cluster configuration.
- [Apache Pulsar](https://pulsar.apache.org/) - Apache Pulsar is an open-source, distributed messaging and streaming platform built for the cloud.
