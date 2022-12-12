##

Azure Private Link provides the following benefits:

- `_____`
- `_____`
- `_____`
- `_____`
- `_____`

%

- Privately access services on the Azure platform
- On-premises and peered networks
- Protection against data leakage
- Global reach
- Extend to your own services

##

Privately access services on the Azure platform: Connect your `_____` using private endpoints to all services that can be used as application components in Azure. Service providers can render their services in their own `_____` and consumers can access those services in their local `_____`. The Private Link platform will handle the connectivity between the consumer and services over the Azure backbone network.

%

Privately access services on the Azure platform: Connect your **virtual network** using private endpoints to all services that can be used as application components in Azure. Service providers can render their services in their own **virtual network** and consumers can access those services in their local **virtual network**. The Private Link platform will handle the connectivity between the consumer and services over the Azure backbone network.

##

On-premises and peered networks: Access services running in Azure from on-premises over ExpressRoute private peering, VPN tunnels, and peered virtual networks using private endpoints. There's no need to configure ExpressRoute Microsoft peering or traverse the internet to reach the service. Private Link provides a secure way to

%

migrate workloads to Azure

##

Protection against data leakage: A private endpoint is mapped to an instance of a PaaS resource instead of the entire service. Consumers can only connect to the specific resource. Access to any other resource in the service is blocked. This mechanism provides protection against

%

data leakage risks

##

Global reach: Connect privately to services running in other regions. The consumer's `_____` could be in region A and it can connect to services behind Private Link in region B.

%

Global reach: Connect privately to services running in other regions. The consumer's **virtual network** could be in region A and it can connect to services behind Private Link in region B.

##

Extend to your own services: Enable the same experience and functionality to render your service privately to consumers in Azure. By placing your service behind a standard Azure Load Balancer, you can enable it for Private Link. The consumer can then connect directly to your service using a private endpoint in their own virtual network. You can manage the connection requests using an approval call flow. Azure Private Link works for consumers and services belonging to different Azure

%

Active Directory tenants

##

Azure Private Link, along with Azure Virtual Network, span across Azure `_____` and are therefore zone resilient. To provide high availability for the Azure resource using a private endpoint, ensure that resource is zone resilient.

%

Azure Private Link, along with Azure Virtual Network, span across Azure **Availability Zones** and are therefore zone resilient. To provide high availability for the Azure resource using a private endpoint, ensure that resource is zone resilient.
