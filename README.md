# Third-party Partnerships and Integrations

This is a directory of third-party Kubecost integrations and partnerships along with relevant links and documentation.

We do our best to keep this list up to date. If there is a Kubecost integration you'd like to see in this list, we'd love to hear from you on our [Slack](https://join.slack.com/t/kubecost/shared_invite/enQtNTA2MjQ1NDUyODE5LWFjYzIzNWE4MDkzMmUyZGU4NjkwMzMyMjIyM2E0NGNmYjExZjBiNjk1YzY5ZDI0ZTNhZDg4NjlkMGRkYzFlZTU) or in this repository's [Issues](https://github.com/kubecost/integrations/)!

## Developer Tools & Kubernetes Management Platforms

### AWS SSP

Customers can install Kubecost as an AddOn on their [Shared Services Platform built on EKS](https://aws-quickstart.github.io/ssp-amazon-eks/getting-started/) using the `ssp-amazon-eks` module.

[🧑‍💻 AWS CDK AddOn Docs](https://github.com/kubecost/kubecost-ssp-addon/)

_Terraform AddOn Documentation (coming soon)_

### Lens

Kubecost offers a simple extension for the [Lens K8s IDE](https://k8slens.dev/) that adds namespace cost data from the last 24 hours to the Namespaces view.

[🧑‍💻 Lens Extension](https://github.com/kubecost/kubecost-lens-extension)

### Rancher

[Rancher](https://rancher.com/docs/) users may install Kubecost as a partner Helm chart, leveraging their cloud native packaging system.

[🧑‍💻 Rancher/Istio Installation Docs](https://guide.kubecost.com/hc/en-us/articles/4408175613719-Installation-Kubecost-with-Istio-Rancher-)

## Rafay

[Rafay](https://docs.rafay.co/) users may install the Kubecost Helm chart as a CNCF best practices recipe.

[🧑‍💻 Rafay Installation Docs](https://github.com/kubecost/kubecost-lens-extension)

## Third-party Managed Services

### Amazon Managed Service for Prometheus (AMP)

[Amazon Managed Service for Prometheus (AMP)](https://docs.aws.amazon.com/prometheus/index.html) is a Prometheus-compatible monitoring service that makes it easy to monitor containerized applications at scale. Integrating AMP with Kubecost follows a workflow that is similar to integrating Kubecost with any [Custom Prometheus](https://docs.kubecost.com/custom-prom.html).

[📄 AMP Documentation](https://guide.kubecost.com/hc/en-us/articles/4409859798679--Amazon-Managed-Service-for-Prometheus)

## Cloud Service Provider Integrations

Kubecost integrates with Cloud Service Provider APIs to display out-of-cluster costs and improve accuracy by leveraging real billing data.

[📄 Full documentation](https://guide.kubecost.com/hc/en-us/articles/4407595968919-Setting-Up-Cloud-Integrations)

### AWS

[🏷️ AWS Docs](https://github.com/kubecost/docs/blob/master/aws-cloud-integrations.md)

### GCP

[🏷️ GCP Docs](https://cloud.google.com/billing/docs/how-to/export-data-bigquery)

### Microsoft Azure

[🏷️ Azure Docs](https://docs.microsoft.com/en-us/azure/cost-management-billing/costs/tutorial-export-acm-data?tabs=azure-portal) 

### Multi-Cloud

[🏷️ Multi-Cloud Docs](https://github.com/kubecost/docs/blob/master/multi-cloud.md)

## Marketplaces

Kubecost Business and Enterprise plans can be purchased via supported CSP Marketplaces, saving time and potential procurement approval hassle in your organization.

Please get in touch with us via [sales@kubecost.com](mailto:sales@kubecost.com) if you're looking for a custom Kubecost plan or quote.

### AWS Marketplace

[🛍️ AWS Marketplace](https://www.kubecost.com/aws)

### Microsoft Azure Marketplace

[🛍️ Azure Marketplace](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/stackwatchinc1625592579012.kubecost)
