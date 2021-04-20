# Terraform Provider Cortex

[![Latest release](https://img.shields.io/github/v/release/vishmit123/terraform-provider-cortex)](https://github.com/vishmit123/terraform-provider-cortex/releases)

This provider enables the provisioning of [cortex](https://cortexmetrics.io).

- [Documentation](https://registry.terraform.io/providers/vishmit123/cortex/latest/docs)

## Building the provider

Run the following command to build the provider

```shell
go build -o terraform-provider-cortex
```

## Test sample configuration

First, build and install the provider.

```shell
make install
```

Then, run the following command to initialize the workspace and apply the sample configuration.

```shell
terraform init && terraform apply
```
