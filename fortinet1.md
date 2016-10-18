### COMPONENTS
Azure Load Balancer – Abstracted Azure resource, which is scalable and resilient. Dynamically splits traffic between the two FortiGate firewall appliances.

Virtual Network – 10.1.0.0/16, also known as VNET

Public Facing Network – 10.1.0.0/24

Protected Network – 10.1.1.0/24

Availability Set – Method of grouping resources within Azure to ensure that they are hosted on separate physical hardware so that at any given time

(even during upgrades and maintenance) at least one of the set will remain up.

FortiGate – Azure certified virtual appliance running the same OS that is used on our hardware appliances. These will be referenced as FortiGate-A and FortiGate-B.

FortiManager – Dedicated policy & configuration manager that is used to keep the configuration in sync between the two FortiGate appliances
