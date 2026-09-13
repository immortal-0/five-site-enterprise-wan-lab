# Five-site-enterprise-wan-lab
Designed and configured a five-site enterprise network in Cisco Packet Tracer connecting NJ, NY, and three branch offices through routed WAN links, multilayer switching, VLAN-based networks, and centralized DNS/HTTP services.


The topology connects five locations, including primary New Jersey and New York sites and three remote branch offices.

The project focuses on enterprise routing, multilayer switching, subnetting, remote-site connectivity, network services, and end-to-end troubleshooting.

## Network Architecture

The environment consists of:

- New Jersey main site
- New York main site
- Three remote branch sites
- Multiple Cisco routers
- Multiple multilayer switches
- Client laptops across multiple networks
- DNS server
- HTTP/web servers
- Routed WAN links between locations

## Networking Concepts Demonstrated

- Enterprise WAN design
- IPv4 addressing and subnetting
- Point-to-point network links
- Layer 3 routing
- Multilayer switching
- VLAN-based network segmentation
- Inter-VLAN routing
- Static routing
- DNS services
- HTTP services
- Client-to-server communication
- Multi-site connectivity
- Network troubleshooting

## New Jersey Site

The New Jersey site acts as one of the primary enterprise locations and contains multiple client networks, multilayer switching, an HTTP server, and DNS services.

Local networks are connected through Layer 3 switching and routed toward remote enterprise locations.

## New York Site

The New York site contains multiple client networks, multilayer switching, and HTTP servers.

The NY router provides WAN connectivity between the local network and the other enterprise sites.

## Remote Branch Sites

Three additional branch networks were connected to the enterprise WAN.

Each branch includes:

- Cisco router
- Multilayer switch
- Multiple client devices
- Local subnet
- Routed connectivity to the main enterprise network

The branch-office design demonstrates how remote business locations can be integrated into an existing enterprise infrastructure.

## WAN Connectivity

Multiple routers were used to connect the five locations.

Routing was configured so that devices located on separate local and remote networks could communicate across the enterprise WAN.

Point-to-point addressing was used where appropriate for routed links between routers.

## Network Services

The environment includes centralized services such as:

- DNS
- HTTP/Web applications

Client devices across the network were configured to access enterprise services through the routed infrastructure.
