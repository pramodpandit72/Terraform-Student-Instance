## Steps Performed

1. Created a project folder named **Terraform-Student-Instance**

Created folder "Terraform-Student-Instance"

Created Terraform configuration files and Added code:


1. Created Terraform configuration files:

   * main.tf
   * outputs.tf
   * variables.tf

2. Added provider configuration for AWS with region `ap-south-1`

3. Defined an EC2 instance resource with:

   * Amazon Linux AMI
   * Instance type: t3.micro
   * Tag: Name = Terraform-Student-Instance

4. Configured AWS credentials using:
   aws configure

5. Initialized Terraform:
   terraform init

6. Checked execution plan:
   terraform plan

7. Applied the configuration to create resources:
   terraform apply

8. Verified EC2 instance in AWS Console

---

## Commands Used

terraform init
terraform plan
terraform apply

---

## Resources Created

* AWS EC2 Instance
* Instance Type: t3.micro