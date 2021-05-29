## terraform-ws

#### This repository contains terraform code for launching a virtual-private-network over AWS. It launches internet-gateway and connects it to the vpc. It also creates parametrized subnets. To increase the count or change CIDR address , make changes in variables file.

***

- ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) providers.tf : This file contains the information regarding the provider i.e Amazon WebServices
- ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) variables.tf : This file has the variables which are usedin the main file. 
                                                                                The variables can be accesed using : var.{variablename} wherever required.
-  ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) vpc.tf : This file contains the terraform code for launching virtual-private-network
                                                                            The file is made paramaterized by using terraform in-built function and variable names.


***

```diff
@@ Initialize the code using the following commands : terraform init @@
```
```diff
@@ Run the code using the following commands : terraform apply @@
```
```diff
@@ Destroy  the architecture using the following commands : terraform destroy @@
```
