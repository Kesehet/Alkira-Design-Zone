**Title:** Troubleshooting in the Cloud using Alkira

**Speaker:** 
- Mrs. Bhararaman, Technical Marketing Engineer at Alkira.

**Introduction:**
- Mrs. Bhararaman discusses how Alkira can help troubleshoot cloud networking issues using a single pane of glass.
- The video focuses on addressing a specific issue where a user in the San Jose branch office cannot connect to a web server in Virginia, which is connected to the US East CXP.

**Troubleshooting Steps:**
1. **Topology Overview:** Mrs. Bhararaman logs into the Alkira portal and views the full network topology. She filters the topology to focus on the San Jose branch, the US East CXP, and the cloud app in AZ.
2. **Identifying the Issue:** A red mark on the US West branch indicates a potential issue. Using the diagnostic view, she finds that the BGP is down.
3. **Checking Debug Logs:** The logs reveal a "bad AS number" notification, pointing to a misconfiguration.
4. **Router Configuration:** Mrs. Bhararaman checks the router's BGP configuration and finds the incorrect AS number. She corrects it, and the BGP status becomes green.
5. **Flow Analysis:** Despite the BGP fix, the web page is still inaccessible. She analyzes the flow and finds that HTTP packets are being forwarded but not received back, suggesting a potential security group or data policy issue.
6. **Policy Inspection:** Using Alkira's policy inspector, she confirms that the policies on Alkira are correctly configured to allow traffic.
7. **Cloud Insight Tool:** Mrs. Bhararaman introduces Alkira's Cloud Insight tool, which provides an inventory of cloud resources and helps identify security loopholes and resource wastage.
8. **Security Group Check:** Using Cloud Insight, she identifies that the security group for the web server only allows ICMP and SSH traffic. HTTP traffic is blocked.
9. **Security Group Modification:** She accesses the AWS console directly from Alkira's portal and modifies the security group to allow HTTP traffic.
10. **Web Page Access:** After the security group modification, the web page becomes accessible from the San Jose branch.

**Conclusion:**
- Mrs. Bhararaman emphasizes the power and flexibility of Alkira in troubleshooting end-to-end cloud networking issues.
- Alkira provides tools and integrations that simplify the troubleshooting process, from connectivity and routing issues to policy and security group configurations.
- She encourages viewers to reach out to Alkira for more information.

---
