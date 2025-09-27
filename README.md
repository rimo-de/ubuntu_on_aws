# Connect to AWS EC2 Instance using SSH

This guide walks through creating an AWS EC2 instance and connecting to it using SSH.

## Steps

### 1. Create an Instance on AWS
Launch an EC2 instance from the AWS Console.  
![Instance on AWS](./Instance%20on%20AWS.png)

### 2. Download the Key-Pair
Download the `.pem` key-pair file when creating the instance. This will be required for SSH access.
![Key-Pair from ECS instance](./Permissions%20on%20Key-Pair.png)

### 3. Connect to ECS instance
Change permissions so the key can be used securely and connect to ECS:  
![Connect to ECS](./Connect%20to%20ECS%20instance.png)

### 4. Connection scuccesful
![Connect to ECS](./Connect%20via%20SSH.png)
