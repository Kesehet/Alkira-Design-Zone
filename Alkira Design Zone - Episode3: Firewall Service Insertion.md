**Title:** Firewall Service Insertion with Alkira Network Cloud

**Speakers:** Ken and Julian from Alkira's field sales team.

**Introduction:**
- The session focuses on firewall service insertion using the Alkira Network Cloud.
- The discussion revolves around the challenges of deploying firewalls in the cloud and how Alkira addresses these challenges.

**Use Cases for Firewall Service Insertion:**
1. **Cloud Firewall Consolidation:** Consolidating distributed firewalls across multiple cloud providers into Alkira.
2. **Regional Internet Security:** Using firewall capacity in the Alkira Cloud Exchange Points (CXPs) for secure internet breakout.
3. **WAN Firewall Consolidation:** Consolidating distributed firewalls from branches and data centers into a central location.
4. **Firewall Auto-Scaling:** Dynamically scaling firewall capacity based on demand.

**Challenges with Deploying Firewalls in the Cloud:**
- Complexity in integrating firewalls across different cloud providers.
- Inefficient resource usage due to overutilized and underutilized firewalls.
- Difficulty in managing state, especially across multiple cloud providers.
- Source IP obfuscation due to Source NAT, leading to loss of source IP information.
- Traffic redirection in cloud providers is often all-or-nothing, leading to inefficiencies.

**Alkira's Solution:**
- Alkira offers a global network with connectors for on-premises sites, cloud networks, and internet breakout.
- Alkira's platform allows for out-of-path firewall insertion, meaning traffic isn't redirected to the firewall until a network policy is applied.
- Alkira's network policy framework allows for transparent redirection of traffic to firewalls, ensuring source and destination IPs remain unchanged.
- The platform manages state and load balancing across multiple firewalls and can auto-scale firewall clusters based on demand.

**Demonstration:**
- Ken showcases the Alkira portal, emphasizing the firewall service insertion features.
- The portal displays connectors for on-premises sites, cloud networks, and internet breakout.
- Ken demonstrates how traffic is redirected to the firewall based on network policies and how certain traffic can bypass the firewall.
- The demonstration includes real-time traffic flow analysis, showing how traffic is inspected or bypassed based on policies.
- Ken also demonstrates the integration with the Checkpoint Security Management Server (SMS) to verify traffic inspection.

**Use Cases Demonstrated:**
1. **East-West Traffic Inspection:** Traffic between AWS and Azure is inspected by the Checkpoint firewall.
2. **Selective North-South Traffic Inspection:** Only web traffic from a branch to Azure is inspected, while other traffic types bypass the firewall.
3. **Internet Traffic Inspection:** All traffic from a data center to the internet is inspected by the firewall.

**Conclusion:**
- The video emphasizes the importance of firewall service insertion in the cloud and showcases how Alkira's platform simplifies and optimizes this process.
- Julian and Ken conclude by expressing their hope to cover more topics in future episodes.

---
