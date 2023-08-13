**Title:** Aruba's SD-WAN Integration with Alkira Network Cloud

**Speakers:** 
- Mrs. Varhaman, Senior Technical Marketing Engineer at Alkira.
- Pasqual, Solution Architect at Alkira, formerly with HPE Aruba with the Silver Peak Edge Connect product.

**Introduction:**
- The video discusses the integration of Aruba's SD-WAN (formerly known as Silver Peak) with Alkira's Network Cloud.
- The focus is on securely connecting partners to a network and providing access to shared application services in the cloud.

**Challenges with Traditional Partner Connectivity:**
- Traditional methods involve point-to-point connectivity, leading to infrastructure strain and limited scalability.
- Controlling access and preventing partner-to-partner communication required next-generation firewalls and traffic segmentation.
- Centralized partner access led to significant traffic backhaul and sub-optimal application experience.

**Alkira's Solution:**
- Alkira offers distributed network access at different geographic locations for optimal application experience.
- It provides end-to-end segmentation with cross-segment routing and intelligent firewall service insertion.
- Network Address Translation (NAT) is used to mitigate IP address overlap for proper routing.

**Demonstration:**
1. **Login to Alkira CSX:** The Alkira CSX portal is shown, highlighting the integration features.
2. **Create Segments:** Three network segments are created: one for suppliers, one for warehouses, and one for the corporate segment hosting the cloud inventory system.
3. **Add Partner Sites:** An IPsec connected site for suppliers and another for warehouses are added.
4. **Firewall Integration:** Palo Alto VM Series firewalls are integrated, managed by the Panorama tool. Auto-scaling is enabled for dynamic capacity based on real-time demand.
5. **Define Shared Resource:** The cloud inventory application in the corporate segment is defined as a shared resource.
6. **Resource Consumption:** Both suppliers and warehouses are allowed to consume the shared application. Traffic from both segments to the application is inspected by the firewall.
7. **Network Address Translation (NAT):** A NAT rule is created to resolve IP address overlap within the supplier segment.

**Conclusion:**
- The video showcases the agility and efficiency of the Alkira Network Cloud in securely connecting partners to shared application services in the cloud.
- The entire process, from defining segments to integrating firewalls and defining NAT rules, is demonstrated in a streamlined manner.
- The speakers encourage viewers to visit Alkira's website to schedule a live demo with a solutions architect.

---
