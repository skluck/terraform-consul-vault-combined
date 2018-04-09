# Terraform Consul/Vault (combined)

This repo is a convenience repo that combines two terraform Gruntwork repositories into one for easy cloning.
Consul and Vault modules are included as subtrees.

Original sources:
- [hashicorp/terraform-aws-consul](https://github.com/hashicorp/terraform-aws-consul)
- [hashicorp/terraform-aws-vault](https://github.com/hashicorp/terraform-aws-vault)

#### Updating Consul
```
git subtree pull --prefix terraform-aws-consul https://github.com/hashicorp/terraform-aws-consul $CONSUL_VERSION --squash
```

#### Updating Vault
```
git subtree pull --prefix terraform-aws-vault https://github.com/hashicorp/terraform-aws-vault $VAULT_VERSION --squash
```
