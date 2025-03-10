# Hyperledger Fabric [![join the chat][rocketchat-image]][rocketchat-url]

[rocketchat-url]: https://chat.hyperledger.org/channel/fabric
[rocketchat-image]: https://open.rocket.chat/images/join-chat.svg

[![Build Status](https://dev.azure.com/Hyperledger/Fabric/_apis/build/status/Merge?branchName=main)](https://dev.azure.com/Hyperledger/Fabric/_build/latest?definitionId=51&branchName=main)
[![CII Best Practices](https://bestpractices.coreinfrastructure.org/projects/955/badge)](https://bestpractices.coreinfrastructure.org/projects/955)
[![Go Report Card](https://goreportcard.com/badge/github.com/hyperledger/fabric)](https://goreportcard.com/report/github.com/hyperledger/fabric)
[![GoDoc](https://godoc.org/github.com/hyperledger/fabric?status.svg)](https://godoc.org/github.com/hyperledger/fabric)
[![Documentation Status](https://readthedocs.org/projects/hyperledger-fabric/badge/?version=latest)](http://hyperledger-fabric.readthedocs.io/en/latest)

This project is an _Active_ Hyperledger project. For more information on the history of this project see the [Fabric wiki page](https://wiki.hyperledger.org/display/fabric). Information on what _Active_ entails can be found in
the [Hyperledger Project Lifecycle document](https://wiki.hyperledger.org/display/HYP/Project+Lifecycle).
Hyperledger Fabric is a platform for distributed ledger solutions, underpinned
by a modular architecture delivering high degrees of confidentiality,
resiliency, flexibility and scalability. It is designed to support pluggable
implementations of different components, and accommodate the complexity and
intricacies that exist across the economic ecosystem.

Hyperledger Fabric delivers a uniquely elastic and extensible architecture,
distinguishing it from alternative blockchain solutions. Planning for the
future of enterprise blockchain requires building on top of a fully-vetted,
open source architecture; Hyperledger Fabric is your starting point.

## Starting point (by Starlight...)

Blockchain claims to be immutable. Thats a fancy term for unchangeable, fixed, static, or concrete, perhaps.
Yet, when you dig into blockchain, you will find massive concern for security...because some actors
want to, and do find ways to change the technology for their benefit. So is blockchain really immutable?
Does it even matter? 

Can blockchain ensure the safety of the Mona Lisa vis a vis some chain of information? No. Blockchain cannot
increase safety in a risky world where the unexpected is daily news. So what can blockchain do that
makes the world a better place, besides convincing people with a lot of money to upgrade their systems
with a blockchain solution to make their business more efficient, thereby producing an ROI and perhaps more...?

Our goals are simply to make the world a better place with solutions that are beneficial for
the long term, for the present and for those that follow after us. To begin, the initial efforts of this
fork will be to create a system of self-taxation whereby people who drive electric cars can earn money 
and people who support clean transport can contribute to it with confidence of the outcome. 

The application to do this will need to run on a blockchain, be permissioned, and may involve a trusted
third party who can validate the EV owner's mileage so that disbursements from donations are warranted 
and earned, not just baseless claims. This system will take a lot of time to produce a reliable result.

With hard work and some creativity the payor's donation will be tax deductible and the payee's receipt
will be exempt from income. This capability can and will be facilitated in the solution...


## Releases

Fabric provides a release approximately once every four months with new features
and improvements. Additionally, certain releases are designated as long-term
support (LTS) releases. Important fixes will be backported to the most recent
LTS release, and to the prior LTS release during periods of LTS release overlap.
For more details see the [LTS strategy](https://github.com/hyperledger/fabric-rfcs/blob/main/text/0005-lts-release-strategy.md).

LTS releases:
- [v2.2.x](https://hyperledger-fabric.readthedocs.io/en/release-2.2/whatsnew.html) (current LTS release)
- [v1.4.x](https://hyperledger-fabric.readthedocs.io/en/release-1.4/whatsnew.html) (prior LTS release, maintained through April 2021)

Unless specified otherwise, all releases will be upgradable from the prior minor release.
Additionally, each LTS release is upgradable to the next LTS release.

Fabric releases and release notes can be found on the [GitHub releases page](https://github.com/hyperledger/fabric/releases).

Please visit the [Hyperledger Fabric Jira dashboard](https://jira.hyperledger.org/secure/Dashboard.jspa?selectPageId=10104) for our release roadmap.

Follow the release discussion on the [#fabric-release](https://chat.hyperledger.org/channel/fabric-release) channel in RocketChat.

## Documentation, Getting Started and Developer Guides

Please visit our
online documentation for
information on getting started using and developing with the fabric, SDK and chaincode:
- [v2.3](http://hyperledger-fabric.readthedocs.io/en/release-2.3/)
- [v2.2](http://hyperledger-fabric.readthedocs.io/en/release-2.2/)
- [v2.1](http://hyperledger-fabric.readthedocs.io/en/release-2.1/)
- [v2.0](http://hyperledger-fabric.readthedocs.io/en/release-2.0/)
- [v1.4](http://hyperledger-fabric.readthedocs.io/en/release-1.4/)
- [v1.3](http://hyperledger-fabric.readthedocs.io/en/release-1.3/)
- [v1.2](http://hyperledger-fabric.readthedocs.io/en/release-1.2/)
- [v1.1](http://hyperledger-fabric.readthedocs.io/en/release-1.1/)
- [main branch (development)](http://hyperledger-fabric.readthedocs.io/en/latest/)

It's recommended for first-time users to begin by going through the Getting Started section of the documentation in order to gain familiarity with the Hyperledger Fabric components and the basic transaction flow.

## Contributing

We welcome contributions to the Hyperledger Fabric project in many forms.
There’s always plenty to do! Check [the documentation on how to contribute to this project](http://hyperledger-fabric.readthedocs.io/en/latest/CONTRIBUTING.html)
for the full details.

## Community

[Hyperledger Community](https://www.hyperledger.org/community)

[Hyperledger mailing lists and archives](http://lists.hyperledger.org/)

[Hyperledger Chat](http://chat.hyperledger.org/channel/fabric)

[Hyperledger Fabric Issue Tracking (JIRA)](https://jira.hyperledger.org/secure/Dashboard.jspa?selectPageId=10104)

[Hyperledger Fabric Wiki](https://wiki.hyperledger.org/display/Fabric)

[Hyperledger Wiki](https://wiki.hyperledger.org/)

[Hyperledger Code of Conduct](https://wiki.hyperledger.org/display/HYP/Hyperledger+Code+of+Conduct)

[Community Calendar](https://wiki.hyperledger.org/display/HYP/Calendar+of+Public+Meetings)

## License <a name="license"></a>

Hyperledger Project source code files are made available under the Apache License, Version 2.0 (Apache-2.0), located in the [LICENSE](LICENSE) file. Hyperledger Project documentation files are made available under the Creative Commons Attribution 4.0 International License (CC-BY-4.0), available at http://creativecommons.org/licenses/by/4.0/.
