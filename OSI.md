# OSI MODEL

The OSI model is an [ISO Standard](https://en.wikipedia.org/wiki/International_Organization_for_Standardization) [ISO 7498-1](https://www.iso.org/standard/20269.html) [ITU X.200](https://www.itu.int/rec/T-REC-X.200-199407-I) outlining an approach for how dissimilar systems can communicate with each other over a network. These systems may be built using similar networking standards, protocols, and architecture or they may use differing ones. So the goal was to define a means to allow a separation of duties(the layered/stacked approach) such that each layer would have a defined responsibility. Protocol or standard aside any could be used as long as they fulfill the goal of that layer.

In this model each layer of the stack is responsible for a different aspect of the overall networked communication. Specifically, each layer can be described as providing a "service" wherein it will rely on lower layers to provide certain "services" or "guarantees" to it, and equally higher layers will rely on "services" or "guarantees" provided by it.

Overall, the OSI model is in reality a conceptual/theoretical model for how this networked communication can be broken down. In practice the ruling mainstream model is TCP/IP which is a similar model that will be explored later.


### Layer 7 - Application Layer
### Layer 6 - Presentation Layer
### Layer 5 - Session Layer
### Layer 4 - Transport Layer
### Layer 3 - Network Layer
### Layer 2 - Data-Link Layer
### Layer 1 - Physical Layer


## References
* [Cloudflare - OSI Model](https://www.cloudflare.com/learning/ddos/glossary/open-systems-interconnection-model-osi/)
