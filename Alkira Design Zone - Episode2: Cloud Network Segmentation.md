**Title:** Network Segmentation in the Cloud with Alkira CSX

**Speakers:** Ken and Julian from Alkira's field sales team.

**Introduction:**
- The session focuses on network segmentation in the cloud and how Alkira CSX can assist in achieving it.

**Why Network Segmentation?**
- **Line of Business Isolation:** Keeping different business entities separate for reasons like mergers, divestitures, or profit and loss isolation.
- **Compliance:** Industries have various compliance requirements, such as PCI DSS (for payment card information) and HIPAA.
- **Extranet Use Cases:** As workloads move to the cloud, businesses want to move their extranet environment to the cloud rather than keeping it on-premises.
- **Zero Trust & Lateral Isolation:** Dividing the network to reduce the risk area in case of a security breach.

**Alkira's Approach to Segmentation:**
- **Segments:** Layer 3 isolated routing spaces similar to VRF light or MPLS VPN. They can have overlapping address spaces.
- **Groups:** Used for micro-segmentation. They group like entities and apply policies between them. Resources (like IPsec sites, VPCs, VNets) are placed in groups, mapped to segments, and policies are applied across the infrastructure.

**Demonstration:**
- Ken showcases the Alkira portal, emphasizing the segmentation features.
- The portal displays connectors for on-prem sites, SD-WAN sites, remote users, and cloud networks.
- The demonstration includes filtering views by segments, showing how different segments can access or be restricted from accessing certain resources.
- Policies in Alkira are used to restrict or allow traffic flow. They can be applied globally, making them flexible and adaptable to changes in the network.
- The demonstration also highlights how Alkira's policies can be used for service insertion, where a third-party network service can be integrated into the flow.

**Practical Application:**
- Ken demonstrates how the policy works in real-time using VNC clients. He shows how a branch client can access the internet while a data center client cannot, based on the policies applied.

**Conclusion:**
- The video emphasizes the importance of network segmentation in the cloud and showcases how Alkira's platform makes it easy and efficient.
- Julian and Ken conclude by expressing their hope to cover more topics in future episodes.

---
