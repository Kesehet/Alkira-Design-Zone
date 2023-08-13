**Title:** Resource Sharing with Alkira Network Cloud

**Speaker:** David Klebanov, leading product marketing for Alkira.

**Introduction:**
- David introduces the Alkira Network Cloud and its capabilities.
- The video aims to demonstrate building an AWS cloud network in under seven minutes using Alkira.

**Challenges with Traditional Cloud Networking:**
- Traditional methods are complex and lack a uniform approach for on-premises, cloud, and multi-cloud connectivity.
- They often require costly hardware investments, complex software configurations, and deep cloud and networking expertise.
- Traditional networks are not agile enough for the cloud era.

**Alkira Network Cloud Solution:**
- Powered by the Alkira Cloud Services Exchange (CSX).
- Provides agility in building secure and segmented networks for AWS and on-premises environments.
- Offers integrated auto-scaling firewalls and regional internet exit points for optimal SaaS application access.

**Demonstration:**
1. **Login to Alkira CSX:** David logs into the Alkira CSX and selects two locations (US East and US West) for the network.
2. **Add New Segment:** A custom segment named "finance" is created with a specific IP address block.
3. **Add AWS Workloads:** David authenticates to an AWS account and selects VPCs from different AWS regions (Ohio and Oregon) to onboard.
4. **Internet Exit Point:** An internet connector is defined for VPCs to access the internet.
5. **Firewall Integration:** A Palo Alto firewall is integrated for security. Alkira automates the provisioning and lifecycle of the firewall.
6. **Define Policies:** David defines intent-based policies for inter-region traffic between VPCs and internet traffic. Traffic is directed to the Palo Alto firewall based on these policies.
7. **On-Premises Connectivity:** An IPsec connector is defined for the San Jose site, which has two routers. BGP is used for dynamic route exchange between the San Jose site and the cloud network.
8. **Security for On-Premises Traffic:** A policy is defined to inspect traffic from the San Jose site to the cloud workloads in the US East and US West regions. Non-business relevant traffic is dropped, while other traffic is sent to the Palo Alto firewall.

**Conclusion:**
- David concludes the demonstration, highlighting the agility and efficiency of the Alkira Network Cloud in building and securing cloud networks.
- The entire process, from defining segments to integrating firewalls and defining policies, is showcased in a streamlined and user-friendly manner.

---
