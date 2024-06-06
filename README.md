# Azure Terraform HTTP Trigger Example

This is an example Azure Function HTTP trigger, Terraform is used to deploy the infrastructure.

To deploy:

```bash
terraform init && terraform apply
```

To destroy:

```bash
terraform destroy
```

Note that this is a simple HTTP trigger, other examples (storage trigger) may require additional resources.
