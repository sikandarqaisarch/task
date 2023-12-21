<!-- BEGIN_TF_DOCS -->
## Requirements

No requirements.

## Providers

| Name | Version |
|------|---------|
| <a name="provider_aws"></a> [aws](#provider\_aws) | n/a |

## Modules

No modules.

## Resources

| Name | Type |
|------|------|
| [aws_iam_policy.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/resources/iam_policy) | resource |
| [aws_iam_policy_document.this](https://registry.terraform.io/providers/hashicorp/aws/latest/docs/data-sources/iam_policy_document) | data source |

## Inputs

| Name | Description | Type | Default | Required |
|------|-------------|------|---------|:--------:|
| <a name="input_DESCRIPTION"></a> [DESCRIPTION](#input\_DESCRIPTION) | n/a | `string` | `"IAM Policy"` | no |
| <a name="input_NAME"></a> [NAME](#input\_NAME) | n/a | `string` | `""` | no |
| <a name="input_PATH"></a> [PATH](#input\_PATH) | n/a | `string` | `"/"` | no |
| <a name="input_POLICY"></a> [POLICY](#input\_POLICY) | n/a | `string` | `""` | no |
| <a name="input_POLICY_JSON"></a> [POLICY\_JSON](#input\_POLICY\_JSON) | n/a | `bool` | `false` | no |
| <a name="input_STATEMENTS"></a> [STATEMENTS](#input\_STATEMENTS) | n/a | `any` | n/a | yes |
| <a name="input_VERSION"></a> [VERSION](#input\_VERSION) | n/a | `string` | `"2012-10-17"` | no |

## Outputs

| Name | Description |
|------|-------------|
| <a name="output_IAM_POLICY"></a> [IAM\_POLICY](#output\_IAM\_POLICY) | iam policy |
| <a name="output_IAM_POLICY_ARN"></a> [IAM\_POLICY\_ARN](#output\_IAM\_POLICY\_ARN) | iam policy arn |
| <a name="output_IAM_POLICY_NAME"></a> [IAM\_POLICY\_NAME](#output\_IAM\_POLICY\_NAME) | iam policy name |
<!-- END_TF_DOCS -->