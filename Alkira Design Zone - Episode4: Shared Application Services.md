**Title:** Resource Sharing with Alkira Network Cloud

**Speaker:** Julian from Alkira's field sales team.

**Introduction:**
- Julian introduces the concept of resource sharing in the Alkira Network Cloud.
- The video builds on concepts from previous videos on segmentation and network services insertion.

**Concept of Resource Sharing:**
- Alkira's network segmentation allows dividing the network into isolated segments or routing domains.
- Each segment enables communication within itself but restricts communication between different segments.
- Resource sharing allows restricted communication between these isolated segments for specific use cases.

**Use Cases for Resource Sharing:**
1. **Infrastructure Services Sharing:** For instance, if the corporate segment hosts infrastructure services like DNS and directory services, these can be shared with the PCI segment without replicating them.
2. **Bi-directional Communication:** For services that require two-way communication, resource sharing can be applied. For example, a service in the PCI segment that collects cardholder data might need to communicate with an external business partner in another segment.

**Demonstration:**
- Julian showcases the Alkira portal, emphasizing the resource sharing features.
- The portal displays connectors for on-premises sites and cloud networks.
- Julian demonstrates how to define segment resources, which determine the scope of resource sharing.
- He then creates a resource share policy, specifying the segments that will share resources and the direction of communication (unidirectional or bi-directional).
- Julian also integrates a Palo Alto firewall for additional security during resource sharing.
- The demonstration includes real-time traffic flow analysis, showing how traffic is inspected or bypassed based on policies.

**Validation:**
- Julian validates the resource sharing setup using a web browser session in the PCI segment to access a web server in the corporate segment.
- He demonstrates successful web browsing and curl requests, while ping requests are denied based on firewall policies.
- The Palo Alto firewall console is used to verify that traffic is being inspected as per the defined policies.

**Conclusion:**
- The video emphasizes the importance of resource sharing in the cloud and showcases how Alkira's platform simplifies and optimizes this process.
- Julian concludes by expressing his hope to cover more topics in future episodes.

---
