# caf_naming_vnet - cafrandom method

Deploys an Azure Virtual Network - cafrandom method

## Usage
To run this example, simply execute: 

```hcl
terraform init
terraform plan
terraform apply
```

Once you are done, just run 
```hcl
terraform destroy
```

## Outputs
| Name | Description |
| --   | -- |
| storage_name | Returns the name of the created storage account | 
| caf_name | Returns the name as given by the CAF module, before being sent to storage account creation |