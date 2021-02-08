# Randomation
A random collection of CloudFormation Templates built for various needs, _"Sharing is caring"_.

## What's in here?

You'll find a few scriptlets/templates addressing the following services:

- Amazon EBS
- Amazon S3
- AWS Config
- AWS Control Tower
- AWS Network Firewall
- AWS Service Catalog

Nothing major, just little templates I've written for automation reasons or to simplify usage of the services


| Name        | Description | Tested On/With |
| ----------- | ----------- | -------------- |
| `ConfigRule-RDSPublic` | RDS Public Instance Config Rule with Auto-Remediation | cfn-lint, cfn_nag, Stack, StackSets & Customizations for Control Tower |
| `ControlTower-EnrollPreReqs` | Control Tower Account Enrollment Pre-Req Implemenation | cfn-lint, cfn_nag, Stack, StackSets |
| `EBS-DefaultEncryption` | EBS Default Encryption Enable | cfn-lint, cfn_nag, Stack, StackSets & Customizations for Control Tower |
| `NetworkFirewall-SortedEndpoints.template` | Network Firewall with Sorted Endpoints | cfn-lint, cfn_nag, Stack, StackSets & Customizations for Control Tower |
| `S3-BlockAccountPublicAccess` | S3 Account-Level Block Public Access | cfn-lint, cfn_nag, Stack, StackSets & Customizations for Control Tower |
| `ServiceCatalog-OrgShare` | Service Catalog Share with AWS Organizations entities | cfn-lint, cfn_nag, Stack |
