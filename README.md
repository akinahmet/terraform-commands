## Basic Terraform Commands

### terraform init
This command used to initialize a working directory containing Terraform configuration files.

```text
terraform init
```

### terraform plan
The terraform plan command is used to create an execution plan.

```text
terraform plan
```

### terraform apply
The terraform apply command is used to apply the changes required to reach the desired state of the configuration. Terraform apply will also write data to the terraform.tfstate file.

```text
terraform apply
```

```text
terraform apply -auto-approve
```

### terraform refresh
The terraform refresh command is used to reconcile the state Terraform knows about (via its state file) with the real-world infrastructure. This does not modify infrastructure but does modify the state file.

```text
terraform refresh
```

### terraform destroy
The terraform destroy command is used to destroy the Terraform-managed infrastructure.

```text
terraform destroy
```

```text
terraform destroy -auto-approve
```

### terraform fmt
The terraform fmt command automatically updates configurations in the current directory for easy readability and consistency.

```text
terraform fmt
```

### terraform output
Show terraform outputs

```text
terraform output
```
### terraform validate
If you are copying configuration snippets or just want to make sure your configuration is syntactically valid and internally consistent, the built in terraform validate command will check and report errors within modules, attribute names, and value types.

```text
terraform validate
```

### terraform state list
The terraform state list command is used to list resources within a Terraform state.

```text
terraform state list
```

### terraform import
Terraform is able to import existing infrastructure. This allows you to take resources that you've created by some other means and bring them under Terraform management.

```text
terraform import
```

### terraform graph
The terraform graph command is used to generate a visual representation of either a configuration or execution plan. The output is in the DOT format, which can be used by GraphViz to generate charts.

```text
terraform graph
```

### terraform providers
Show terraform providers

```text
terraform providers
```

### terraform show
Show terraform resources

```text
terraform show
```

### terraform workspace list
List terraform workspaces 

```text
terraform workspace list
```

### terraform taint
The terraform taint command manually marks a Terraform-managed resource as tainted, forcing it to be destroyed and recreated on the next apply.

```text
terraform taint
```

### terraform console
The terraform console command provides an interactive console for evaluating expressions.

```text
terraform console
```