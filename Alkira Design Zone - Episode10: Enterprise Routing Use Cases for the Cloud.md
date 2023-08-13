**Title:** NAT (Network Address Translation) in Cloud Networking with Alkira

**Speakers:** 
- Mrs. Varhaman, Senior Technical Marketing Engineer at Alkira.
- Ken, presenter for the Alkira Design Zone.

**Introduction:**
- The video delves into NAT (Network Address Translation) in cloud networking.
- Ken elaborates on the traditional use of NAT on edge devices and the context of NAT in cloud networking, especially addressing overlapping CIDRs or legacy devices with static IP addresses for migrated applications.

**NAT Use Cases with Alkira:**
- Alkira's NAT policies apply network-wide and can be applied to a single connector or a group of connectors or sites.
- NAT rules within a policy apply to traffic coming inbound from the Alkira CXP's perspective.
- Alkira supports various types of NATs, including dynamic IP and port, static IP, static IP and port, and static port.

**Demonstration:**
1. **Overlapping Prefixes:** Ken demonstrates a scenario with overlapping prefixes between a data center (DC1) and a branch (Branch1) with an AWS VPC. The overlapping subnet is 10.8.100.0/24.
2. **NAT Configuration:** Ken showcases the Alkira portal's NAT configuration. Branch1's traffic is source NATed to 20.20.20.0/24. For the AWS VPC, traffic going to Branch1's NATed subnet is source NATed to 30.3.3.0/24.
3. **Route Visualization:** Ken visualizes the routes in the Alkira dashboard, showing the advertised NATed prefixes for the overlapping VPC and Branch1.
4. **Policy Configuration:** Ken demonstrates how to configure policies in the Alkira portal, emphasizing the importance of setting the correct flags for NATed prefixes.

**Conclusion:**
- Ken wraps up the demonstration, emphasizing the flexibility and capabilities of Alkira's NAT policies in addressing complex cloud networking scenarios.
- The video showcases how Alkira handles overlapping prefixes and other NAT use cases in cloud networking efficiently.

---
