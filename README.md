# terraform-AWS-VPC
# AWS VPC Launcing module

This Terraform module is used to create a VPC with certain options.

## Usage

### Inputs [arguments]

- `vpc_cidr_block` - (Required) VPC network name. ex: `10.0.0.0/16`
- `vpc_name` - (Optional) label the vpc with `Name` Key
- `subnet_cidr_block` - (Required) list of VPC subnet network name.
  ex: `[10.0.0.0/24, 10.0.1.0/24]`
- `subnet_names` - (Optional) label the subnet with `Name` Key as a list
  ex: `[subnet1, subnet2]`
- `gateway_name` - (Optional) label the interet gateway with `Name` Key
- `route_table_name` - (Optional) label the routing table with `Name` Key

