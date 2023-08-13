**Title:** Alkira's Integration with HashiCorp's Terraform

**Speaker:** 
- William Collins, Principal Cloud Architect at Alkira.

**Introduction:**
- William introduces Alkira's integration with HashiCorp's Terraform.
- The video focuses on provisioning cloud networking with CI/CD pipelines using Terraform.

**Terraform and Alkira:**
- Terraform providers are plugins that interface with external APIs. 
- Alkira's provider acts as a translation layer, enabling communication with various cloud or infrastructure providers.
- Terraform modules group common resources together, similar to functions in programming languages.

**Demonstration:**
1. **GitHub Repository:** William showcases his GitHub repository containing infrastructure-as-code files.
2. **GitHub Actions:** The workflow triggers on pull requests and runs checks for syntax, spacing errors, and other potential issues.
3. **Infrastructure Code:** The code defines the name of the VPC, CIDR range, subnets, Alkira segment, groups, and billing tags.
4. **Pull Request:** William opens a pull request, triggering GitHub Actions to validate the code.
5. **Terraform Cloud:** Once the code is merged, Terraform Cloud starts planning and provisioning the network infrastructure.
6. **Alkira Portal:** William validates the provisioned infrastructure in the Alkira portal. The common network across three major cloud providers is created with separation for different application environments.
7. **Segments and Groups:** William checks the segments and groups in the Alkira portal to ensure correct configuration.
8. **Tagging Scheme:** The desired tagging scheme is applied to the cloud networks.
9. **Policy Visualization:** Alkira's UI allows for easy visualization of policies. William ensures that non-production networks can communicate with each other and that production networks are isolated.

**Conclusion:**
- William emphasizes the flexibility and capabilities of Alkira's integration with Terraform.
- Alkira meets the current CI/CD pipeline setup and can be an additional step in the pipeline.
- Viewers are encouraged to reach out to Alkira for more information.

---
