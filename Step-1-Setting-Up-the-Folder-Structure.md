![Immutable Inftastructure (1)](https://github.com/silviob99/Project-4-Immutable-Architecture-Using-Terraform-Ansible-Packer/assets/107585020/5168ee23-eddb-4419-b758-0c0f861ed5c9)



### Step 1: Setting up the folder tree with Linux commands

1. Create a root folder named Terraform-project with two subfolders: "Deployment" and "Module."
- Linux command: ```mkdir -p Terraform-project/{Deployment,Module}```

2. Navigate to the "Module" folder:
- Linux command: ```cd Terraform-project/Module```
  
3. Within the "Module" folder, create subfolders for different environments: "dev," "test," and "prod."
- Linux commands:
```
mkdir dev
mkdir test
mkdir prod
```

4. Navigate to the "dev" environment folder:
- Linux command: ```cd dev```
  
5. Within each environment subfolder, create three additional subfolders: "Database," "Load Balancer," and "VPC."
- Linux commands: 
```
mkdir Database
mkdir "Load Balancer"
mkdir VP
```

6. Navigate to the "VPC" folder:
- Linux command: ```cd VPC```
  
7. Create a new file named "main.tf" and another file named "variables.tf," both with the ".tf" extension.
- Linux commands:
```
touch main.tf
touch variables.tf
```

8. Navigate back to the root "Terraform project" folder:
- Linux command: ```cd ../../```
  
9. Create a folder named "packer" within the "Terraform project" directory:
- Linux command: ```mkdir "packer"```

  
- At the end you should have the structure like this one shown on the picture below:

![Terraform-tree1](https://github.com/silviob99/Project-4-Immutable-Architecture-Using-Terraform-Ansible-Packer/assets/107585020/71fdf9cd-46b5-40d0-8dad-43d379f63123)


