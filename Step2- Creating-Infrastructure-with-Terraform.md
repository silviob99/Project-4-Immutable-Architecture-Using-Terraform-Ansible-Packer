![Immutable Inftastructure (1)](https://github.com/silviob99/Project-4-Immutable-Architecture-Using-Terraform-Ansible-Packer/assets/107585020/5168ee23-eddb-4419-b758-0c0f861ed5c9)

### Step 2: Creating Infrastructure with Terrafom

In this step, we'll use Terraform to create the necessary infrastructure components, including VPC, subnets, route tables, route table rules, and associations.
If you're using Visual Studio Code as your preferred text editor, you can follow these steps to open and edit the "main.tf" file:

1. Launch Visual Studio Code.
 
2. Navigate to the directory where your "main.tf" file is located. You can do this by clicking on "File" in the top menu, then selecting "Open Folder" and choosing the folder containing your Terraform project.

3. Once inside the folder, locate the "main.tf" file.

4. Right-click on the "main.tf" file and select "Open with Code" from the context menu. This will open the file in Visual Studio Code.

5. You can now edit the "main.tf" file as needed using the features and capabilities of Visual Studio Code.

6. After making your changes, save the file by pressing Ctrl + S (or Cmd + S on macOS) or by selecting "Save" from the "File" menu.

It will look like this picture below:

![VS-UI-Terraform](https://github.com/silviob99/Project-4-Immutable-Architecture-Using-Terraform-Ansible-Packer/assets/107585020/00f2d1af-2d6e-4659-b5b5-81bbb6e6898c)

7. In the next step, we'll begin creating our infrastructure using Terraform. To get started, we'll visit the Terraform provider documentation for AWS, available at:
   
[Terraform Registry - Hashicorp](https://registry.terraform.io/providers/hashicorp/aws/latest/docs)
, where we'll find the necessary resources and configuration options provided by the AWS provider. We'll use this documentation as a reference to write our Terraform code for provisioning infrastructure components on AWS.

<img width="500" alt="registry-provider" src="https://github.com/silviob99/Project-4-Immutable-Architecture-Using-Terraform-Ansible-Packer/assets/107585020/2d073731-3c10-4de5-8c0b-cd9dc86ea424">

Once you have found the code you need, copy it to your Visual Studio Code editor and make any necessary changes, such as specifying the region or adjusting resource configurations according to your requirements. This step allows for customization and fine-tuning of the infrastructure setup to suit your project needs.

<img width="500" alt="provider-code" src="https://github.com/silviob99/Project-4-Immutable-Architecture-Using-Terraform-Ansible-Packer/assets/107585020/ae064029-ec85-4acd-a04f-1b2af8f62757">

Next step, we'll define the Virtual Private Cloud (VPC) and subnets for our infrastructure using Terraform. Following the same approach as before, we'll visit the Terraform provider documentation for AWS to find resources for VPC and subnets. We'll define attributes such as CIDR blocks, VPC name, tags, subnet tags, and any other necessary configurations to tailor the VPC and subnets according to our project requirements.

<img width="500" alt="vpc-subnet-code" src="https://github.com/silviob99/Project-4-Immutable-Architecture-Using-Terraform-Ansible-Packer/assets/107585020/a5cb1ae8-53c2-490c-9d92-cd9a9a3f91fb">

To enhance security and flexibility in our infrastructure setup, we'll transition from hardcoded values to using variables in our Terraform code. By doing so, we can easily adjust configuration settings across different environments and mitigate security risks associated with hardcoded values. We'll define variables for attributes such as CIDR blocks, VPC name, subnet tags, and any other configurable parameters, allowing us to customize our infrastructure setup based on specific requirements for each environment.
