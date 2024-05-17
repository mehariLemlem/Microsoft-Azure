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
- 