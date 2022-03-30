![](https://img.shields.io/badge/Build%20with%20%E2%9D%A4%EF%B8%8F-at%20Technologiesitftung%20Berlin-blue)

# giessdenkiez.de AWS S3 Terraform

Terraform files for setting up S3 for giessdenkiez.de

## Prerequisites

 - Terraform (install using [asdf](https://asdf-vm.com/#/))

 ## Setup

 Follow the [terraform AWS setup instructions](https://learn.hashicorp.com/tutorials/terraform/aws-build?in=terraform/aws-get-started) to get your credentials right.

 ```bash
 asdf install
 terraform init
 mv terraform.tfvars.example terraform.tfvars
 ```
 Fill in all the variables in `terraform.tfvars`.

 ## Usage

 ```bash
 cd terraform
 terraform apply
 ```

## Contributors ✨

Thanks goes to these wonderful people ([emoji key](https://allcontributors.org/docs/en/emoji-key)):

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->
<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->
<!-- ALL-CONTRIBUTORS-LIST:END -->

This project follows the [all-contributors](https://github.com/all-contributors/all-contributors) specification. Contributions of any kind welcome!