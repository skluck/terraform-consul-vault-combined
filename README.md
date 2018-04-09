# Terraform Consul/Vault (combined)

This repo is a convenience repo that combines two terraform Gruntwork repositories into one for easy cloning.
Consul and Vault modules are included as subtrees.

Original sources:
- [hashicorp/terraform-aws-consul](https://github.com/hashicorp/terraform-aws-consul)
- [hashicorp/terraform-aws-vault](https://github.com/hashicorp/terraform-aws-vault)

Current versions:
- hashicorp/terraform-aws-consul `v0.3.1`
- hashicorp/terraform-aws-vault `v0.5.1`

#### Updating Consul
```
git subtree pull --prefix terraform-aws-consul https://github.com/hashicorp/terraform-aws-consul v0.3.1 --squash
```

#### Updating Vault
```
git subtree pull --prefix terraform-aws-vault https://github.com/hashicorp/terraform-aws-vault v0.5.1--squash
```
