# Terraform Beginner Bootcamp 2023

## Semantic Versioning 

This project is going to utilize versioning for ist taging 
[semver.org](https://semver.org/)
Given a vesion number **MAJOR.MINOR.PATCH**, eg. `1.0.1`

- **MAJOR** version when you make incompatible API changes
- **MINOR** version when you add functionality in a backward compatible manner
- **PATCH** version when you make backward compatible bug fixes
- Additional labels for pre-release and build metadata are available as extensions to the MAJOR.MINOR.PATCH format.

## Install Terraform CLI 

### Considerations with the Terraform CLI changes
The Terraform CLI installation instructions have changed due to gpg keyring changes. So we needed to refer to the latest install CLI instructions via Terraform Documentation and change the scripting for install.

(https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli)

https://en.wikipedia.org/wiki/Shebang_(Unix)
https://www.redhat.com/sysadmin/linux-file-permissions-explained
https://developer.hashicorp.com/terraform/tutorials/aws-get-started/install-cli