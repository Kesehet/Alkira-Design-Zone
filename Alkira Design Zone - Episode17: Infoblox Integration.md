**Title:** Simplifying the Deployment of Infoblox in Cloud with Alkira

**Speakers:** 
- Hasham Malik, Technical Marketing Engineer at Alkira.
- Ahmad, Product Manager at Alkira.

**Introduction:**
- The video highlights the partnership between Alkira and Infoblox to simplify networking and security services for multi-cloud, multi-region, and on-prem infrastructure.

**Challenges in Cloud DDI Deployment:**
- Deploying DDI (DHCP, DNS, IPAM) services in cloud environments is complex due to different constructs in each cloud service provider.
- Challenges include managing overlapping IP addresses, ensuring security and compliance, and handling anycast routing.
- Shared VPC and VNet designs increase complexity, especially when services need to be shared across different departments or segments.

**Alkira's Solution:**
- Alkira offers a cloud-native, agentless solution that simplifies DDI deployment.
- The Alkira Cloud Exchange Point (CXP) provides end-to-end connectivity.
- Alkira integrates seamlessly with Infoblox, allowing for easy deployment and scaling of DDI services.
- The solution supports segmentation, micro-segmentation, and anycast routing.

**Demonstration:**
1. **Alkira Portal Overview:** The portal shows the deployment of CXPs in different regions. The left panel allows for onboarding of on-prem sites, cloud constructs, and internet exits. The middle panel showcases the marketplace, including Infoblox services.
2. **Infoblox Deployment:** Infoblox services can be deployed in Alkira with minimal configuration. The service requires a global CIDR subnet block, segment selection, and anycast IP address configuration.
3. **Grid Configuration:** Customers can deploy a new Infoblox grid or integrate with an existing one. The grid master and grid members can be deployed in Alkira.
4. **Anycast Routing:** Alkira supports anycast routing between different regions. Customers only need to provide the anycast IP address.
5. **Traffic Inspection:** Alkira and Infoblox ensure secure DNS requests. The demonstration shows a DNS request from a host system connected via Alkira VPN. The request is sent to the Infoblox instance in the US West region, and the response is captured in the flowchart.
6. **Anycast IP Testing:** The same DNS request is sent to the anycast IP address, showcasing Alkira's capability to handle anycast routing.

**Conclusion:**
- Alkira and Infoblox's integration simplifies the deployment and management of DDI services in the cloud.
- The solution offers seamless connectivity, security, and redundancy for multi-cloud infrastructures.
- Viewers are encouraged to visit Alkira's website for more information and to reach out with any questions.

---
