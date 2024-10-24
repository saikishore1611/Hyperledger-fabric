# Hyperledger Fabric

[![OpenSSF Scorecard](https://api.scorecard.dev/projects/github.com/hyperledger/fabric/badge)](https://scorecard.dev/viewer/?uri=github.com/hyperledger/fabric)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/955/badge)](https://bestpractices.coreinfrastructure.org/projects/955)
[![Go Report Card](https://goreportcard.com/badge/github.com/hyperledger/fabric)](https://goreportcard.com/report/github.com/hyperledger/fabric)
[![GoDoc](https://godoc.org/github.com/hyperledger/fabric?status.svg)](https://godoc.org/github.com/hyperledger/fabric)
[![Documentation Status](https://readthedocs.org/projects/hyperledger-fabric/badge/?version=latest)](http://hyperledger-fabric.readthedocs.io/en/latest)
[![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/hyperledger/fabric/verify-build.yml?branch=main&label=build%20-%20main)](https://github.com/hyperledger/fabric/actions/workflows/verify-build.yml)
[![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/hyperledger/fabric/verify-build.yml?branch=release-2.5&label=build%20-%20release-2.5)](https://github.com/hyperledger/fabric/actions/workflows/verify-build.yml)
[![Security vulnerability scan](https://github.com/hyperledger/fabric/actions/workflows/vulnerability-scan.yml/badge.svg?branch=main)](https://github.com/hyperledger/fabric/actions/workflows/vulnerability-scan.yml)
[![GitHub go.mod Go version](https://img.shields.io/github/go-mod/go-version/hyperledger/fabric)](https://github.com/hyperledger/fabric/blob/main/go.mod)
[![GitHub Release](https://img.shields.io/github/v/release/hyperledger/fabric)](https://github.com/hyperledger/fabric/releases)

## Overview

**Hyperledger Fabric** is a **Graduated** project under the Hyperledger umbrella, designed for distributed ledger solutions. Its modular architecture provides high levels of confidentiality, resiliency, flexibility, and scalability. Hyperledger Fabric allows for pluggable implementations of various components, accommodating the complexities of different economic ecosystems.

This platform offers a uniquely elastic and extensible architecture, setting it apart from other blockchain solutions. Building on a fully-vetted, open-source framework, Hyperledger Fabric is an ideal starting point for enterprise blockchain initiatives.

Hyperledger Fabric is an open-source enterprise-grade distributed ledger technology (DLT) platform designed for developing blockchain-based applications and solutions. It provides a modular architecture, allowing customization of components such as consensus, membership services, and smart contracts (chaincode), making it highly flexible and adaptable to different use cases.

## Key features include:

Permissioned Network: Fabric supports permissioned networks, ensuring that only authorized participants can access the network, enhancing privacy and security.
Modular Architecture: Its plug-and-play modular design allows organizations to tailor the network to their specific requirements, including consensus algorithms, identity management, and data privacy.
Chaincode: Smart contracts in Fabric are known as chaincode and can be written in general-purpose programming languages like Go, Java, and JavaScript.
Channels: Fabric introduces channels to provide private communication paths for a subset of network participants, ensuring transaction confidentiality.
Pluggable Consensus: Organizations can choose the consensus mechanism that best suits their needs, enabling scalability and resilience.
Hyperledger Fabric is widely adopted in various industries such as supply chain management, finance, healthcare, and more, due to its flexibility, security, and ability to operate in a decentralized yet controlled environment.

## Releases

Hyperledger Fabric provides periodic releases with new features and improvements. Certain releases are designated as **Long-Term Support (LTS)**, ensuring that important fixes are backported during overlap periods.

### Current LTS Release:
- **[v2.5.x](https://hyperledger-fabric.readthedocs.io/en/release-2.5/whatsnew.html)**

### Historic LTS Releases:
- **[v2.2.x](https://hyperledger-fabric.readthedocs.io/en/release-2.2/whatsnew.html)** (maintenance ended February 2024)
- **[v1.4.x](https://hyperledger-fabric.readthedocs.io/en/release-1.4/whatsnew.html)** (maintenance ended April 2021)

For complete release notes, visit the **[GitHub releases page](https://github.com/hyperledger/fabric/releases)**.

## Documentation and Getting Started

To familiarize yourself with Hyperledger Fabric, visit our comprehensive online documentation:
- **[Getting Started with v2.5](http://hyperledger-fabric.readthedocs.io/en/release-2.5/)**
- **[Previous Versions](http://hyperledger-fabric.readthedocs.io/en/release-2.4/)**

We recommend that first-time users start with the **Getting Started** section to understand the components and basic transaction flow.

## Contributing

We welcome contributions to Hyperledger Fabric in various forms. There’s always plenty to do! Check our [contribution guidelines](http://hyperledger-fabric.readthedocs.io/en/latest/CONTRIBUTING.html) for more details on how to get involved.

## Community

Engage with the Hyperledger community:
- **[Hyperledger Community Meetup](https://www.meetup.com/pro/hyperledger/)**
- **[Mailing Lists and Archives](http://lists.hyperledger.org/)**
- **[Discord Chat](https://discord.com/invite/hyperledger)**
- **[Issue Tracking](https://github.com/hyperledger/fabric/issues)**

## License

Hyperledger Fabric source code is available under the **Apache License, Version 2.0 (Apache-2.0)**, and documentation files are under the **Creative Commons Attribution 4.0 International License (CC-BY-4.0)**.
