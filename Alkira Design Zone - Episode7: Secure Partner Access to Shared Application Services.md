**Title:** Building Your Google Cloud and Multi-Cloud Network with Alkira Network Cloud

**Speaker:** David Klebanov, leading product marketing for Alkira.

**Introduction:**
- David discusses securely connecting partners to a network and providing them access to shared application services in the cloud.
- He highlights the challenges faced by many enterprises that operate with partners requiring access to a common set of application resources.

**Challenges with Traditional Partner Connectivity:**
- Traditional methods involve point-to-point connectivity, leading to infrastructure strain and limited scalability.
- Controlling access and preventing partner-to-partner communication required next-generation firewalls and traffic segmentation.
- Centralized partner access led to significant traffic backhaul and sub-optimal application experience as applications moved to the cloud.

**Alkira's Solution:**
- Alkira offers distributed network access at different geographic locations for optimal application experience.
- It provides end-to-end segmentation with cross-segment routing and intelligent firewall service insertion.
- Network Address Translation (NAT) is used to mitigate IP address overlap for proper routing.

**Demonstration:**
1. **Login to Alkira CSX:** David logs into the Alkira CSX and selects two geographic locations.
2. **Create Segments:** Three network segments are created: one for suppliers, one for warehouses, and one for the corporate segment hosting the cloud inventory system.
3. **Add AWS Workloads:** The cloud inventory system residing in AWS is added.
4. **Add Partner Sites:** An IPsec connected site for suppliers and another for warehouses are added.
5. **Firewall Integration:** Palo Alto VM Series firewalls are integrated, managed by the Panorama tool. Auto-scaling is enabled for dynamic capacity based on real-time demand.
6. **Define Shared Resource:** The cloud inventory application in the corporate segment is defined as a shared resource.
7. **Resource Consumption:** Both suppliers and warehouses are allowed to consume the shared application. Traffic from both segments to the application is inspected by the firewall.
8. **Network Address Translation (NAT):** A NAT rule is created to resolve IP address overlap within the supplier segment.

**Conclusion:**
- David showcases the agility and efficiency of the Alkira Network Cloud in securely connecting partners to shared application services in the cloud.
- The entire process, from defining segments to integrating firewalls and defining NAT rules, is demonstrated in a streamlined manner.

---
