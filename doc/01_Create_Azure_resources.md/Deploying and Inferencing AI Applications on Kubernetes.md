---
layout: default
parent: 'Lab summaries'
---

# Deploying and Inferencing AI Applications on Kubernetes

**ID** 191961  
**Number:** LAB345  
**Name:** Deploying and Inferencing AI Applications on Kubernetes
**CloudSubscriptionPoolName:** Microsoft Event Subscription (CSS)  
**AllowSave:** True  
**CloudCredentialPoolAssignments:** LAB345: Deploying and Inferencing AI v4, Feature, Remove Role assignments, Roles, Remove Policy, "LOD CSR Policy v6"
                                                   $scope = '/subscriptions/@lab.CloudSubscription.Id/resourceGroups/@lab.CloudResourceGroup(ResourceGroup1).Name'
                                                   
                                                   # Remove the Policy Assignment
                                                   Remove-AzPolicyAssignment -Name $policyAssignmentName -Scope $scope -Force  
**Additional licenses:** NA  

---

## Exercise Summary
### Exercise Summary
- **Overview:** Learn KAITO (Kubernetes AI Toolchain Operator) for AI/ML workloads.
- **Setup:** Log into VM, authenticate to Azure, connect to AKS cluster.
- **Install KAITO:** Deploy as AKS add-on via VS Code extension.
- **Deploy Workspace:** Choose model (e.g., Phi-3), customize workspace YAML, provision GPU nodes.
- **Test & Monitor:** Expose inference endpoints, test via REST API, monitor with Azure Managed Prometheus & Grafana.

