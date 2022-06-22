# TerraformAWS
### Basic Terraform module for AWS

Set variables for your AWS credential.

	export AWS_ACCESS_KEY_ID=
	export AWS_SECRET_ACCESS_KEY=

Initialize the directory.

	terraform init

Format and validate the configuration.

	terraform fmt
	terraform validate

Apply configuration.

	terraform apply

Inspect current state.

	terraform show

List the resources in the project's state.

	terraform state list

Name the instance something useful.

	terraform apply -var "instance_name=RelevantName"

Tear it down.

	terraform destroy
