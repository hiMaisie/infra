# infrastructure

infrastructure configuration for my personal projects and servers.

runs on terraform cloud.

# terraform

## project structure

modules live in the `modules/` directory.

`main.tf` is where providers and modules are called.

`mbell_dev.tf` represents DNS record configuration for the `mbell.dev` domain.

`bell_wtf.tf` represents DNS record configuration for the `mbell.dev` domain.

`variables.tf` are for infra-wide variables.

### modules

-   `minecraft` - small minecraft server for use with friends.
