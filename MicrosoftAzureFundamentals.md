# Describe features and tools in Azure for governance and compliance
[Microsoft Purview](https://learn.microsoft.com/en-us/purview/governance-solutions-overview)
- Microsoft Purview's data governance solutions create one place for you to manage your on-premises, multicloud, and software-as-a-service (SaaS) data.
- Two main solution areas comprise Microsoft Purview: risk and compliance and unified data governance.
  - ![image](Purview_1.png)

[Azure Policy](https://learn.microsoft.com/en-us/azure/governance/policy/overview)
- Enables you to create, assign, and manage policies that control or audit your resources.
- Enables you to define both individual policies and groups of related policies, known as initiatives.
- Azure Policy evaluates your resources and highlights resources that aren't compliant with the policies you've created. 
- Azure Policy can also prevent noncompliant resources from being created.
- Azure Policies can be set at each level, enabling you to set policies on a [specific resource, resource group, subscription](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/overview), and so on. Additionally, Azure Policies are **inherited**.
- If you have a specific resource that you don’t want Azure Policy to automatically fix, you can flag that resource as an exception – and the policy won’t automatically fix that resource.
- An [Azure Policy initiative](https://techcommunity.microsoft.com/t5/itops-talk-blog/azure-policy-initiatives-vs-azure-policies-when-should-i-use-one/ba-p/1229167) is a way of grouping related policies together.

## Describe the purpose of [resource locks](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/lock-resources)
- A resource lock prevents resources from being accidentally deleted or changed.
- Resource locks can be applied to [individual resources, resource groups, or even an entire subscription](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/overview).
- Resource locks are inherited.
- **Types of Resource Locks:**
  - CanNotDelete
  - ReadOnly(CanNotChange)
- You can manage resource locks from the [Azure portal](https://learn.microsoft.com/en-us/azure/azure-portal/azure-portal-overview), [PowerShell](https://learn.microsoft.com/en-us/powershell/azure/what-is-azure-powershell?view=azps-11.6.0), the [Azure CLI](https://learn.microsoft.com/en-us/cli/azure/what-is-azure-cli), or from an [Azure Resource Manager](https://learn.microsoft.com/en-us/azure/azure-resource-manager/management/overview) template.
- Resource locks apply regardless of [RBAC](https://learn.microsoft.com/en-us/azure/role-based-access-control/overview) permissions.
- [Exercise - Configure a resource lock](https://learn.microsoft.com/en-us/training/modules/describe-features-tools-azure-for-governance-compliance/5-exercise-configure-resource-lock)

## Describe the purpose of the [Service Trust portal](https://learn.microsoft.com/en-us/purview/get-started-with-service-trust-portal)
- The Microsoft Service Trust Portal is a portal that provides access to various content, tools, and other resources about Microsoft security, privacy, and compliance practices. 
- The Service Trust Portal contains details about Microsoft's implementation of controls and processes that protect our cloud services and the customer data therein. 
- To access some of the resources on the Service Trust Portal, you must sign in as an authenticated user with your Microsoft cloud services account (Microsoft Entra organization account). You'll need to review and accept the Microsoft non-disclosure agreement for compliance materials.


# [Describe features and tools for managing and deploying Azure resources](https://learn.microsoft.com/en-us/training/modules/describe-features-tools-manage-deploy-azure-resources/)
## [Azure portal](https://learn.microsoft.com/en-us/azure/azure-portal/azure-portal-overview)
- The Azure portal is a web-based, unified console that provides an alternative to command-line tools. With the Azure portal, you can manage your Azure subscription by using a graphical user interface.

## [Azure Cloud Shell](https://learn.microsoft.com/en-us/azure/cloud-shell/overview)
- Azure Cloud Shell is a browser-based shell tool that allows you to create, configure, and manage Azure resources using a shell. 
- Azure Cloud Shell support both Azure PowerShell and the Azure Command Line Interface (CLI), which is a Bash shell.
