# Infrastructure as Code with Terraform

![Terraform](https://img.shields.io/badge/Terraform-7B42BC?style=flat&logo=terraform&logoColor=white)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=flat&logo=microsoftazure&logoColor=white)

In this project I use Terraform to write a script that deploys a **resource group**, a **virtual network** and a **subnet** in Azure automatically, replacing manual portal clicks with repeatable code.

## Why Infrastructure as Code

- **Repeatable:** the same code produces the same environment every time.
- **Reviewable:** infrastructure changes can be read and reviewed like any other code.
- **Disposable:** `terraform destroy` removes everything cleanly when the lab is done.

## Workflow

1. `terraform init` downloads the AzureRM provider.
2. `terraform plan` previews the resources to be created.
3. `terraform apply` deploys the resource group, VNet and subnet.
4. Verify the resources in the Azure portal.

The deployment is shown step by step in the videos below.

## Video walkthroughs (Loom)

- [Project introduction](https://www.loom.com/share/c115476a348441eea1759b8d888d91b6)
- [Infrastructure as Code deployments](https://www.loom.com/share/6fb1c88d359a41fc80dc14b62f7de4bc)
- [Project outro](https://www.loom.com/share/3c7398a0108b4479920f468eef04cb7a)

## Larger Terraform projects

My later projects use Terraform end to end, for example [Azure-AI-Inventory-Tracker](https://github.com/JeremiahBTech12/Azure-AI-Inventory-Tracker) and [Azure-Lift-Shift-Migration](https://github.com/JeremiahBTech12/Azure-Lift-Shift-Migration).
