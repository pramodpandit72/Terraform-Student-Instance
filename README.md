## Steps Performed


1. Created a project folder named **Terraform-Student-Instance**
=======
Created folder "Terraform-Student-Instance"

Created Terraform configuration files and Added code:

2. Created Terraform configuration files:

   * main.tf
   * outputs.tf
   * variables.tf

3. Added provider configuration for AWS with region `ap-south-1`

4. Defined an EC2 instance resource with:

   * Amazon Linux AMI
   * Instance type: t3.micro
   * Tag: Name = Terraform-Student-Instance

5. Configured AWS credentials using:
   aws configure

6. Initialized Terraform:
   terraform init

7. Checked execution plan:
   terraform plan

8. Applied the configuration to create resources:
   terraform apply

9. Verified EC2 instance in AWS Console

---

## Commands Used

terraform init
terraform plan
terraform apply

---

## Resources Created

* AWS EC2 Instance
* Instance Type: t3.micro
