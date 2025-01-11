# EC2 Instance Configuration for Amazon Linux using AWS

## Aim
To configure an EC2 instance for Amazon Linux using AWS.

## Steps to Configure

### Step 1: Select EC2
Navigate to the AWS Management Console and select **EC2**.

### Step 2: Launch an Instance
Click on the **Launch Instance** button.

### Step 3: Enter Instance Details
1. Enter a name for your instance, e.g., `mylinuxserver`.
2. Select **Amazon Linux** as the AMI.

### Step 4: Create a Key Pair
Create a key pair with a name like `06072024` to securely connect to your instance.

### Step 5: Configure Security Group and Storage
1. Allow **SSH traffic** by default.
2. Configure storage with a size of **8 GiB**.

### Step 6: Launch the Instance
Click on the **Launch Instance** button.

### Step 7: Wait for Status Check
Wait until the status check is completed.

### Step 8: Connect to the Instance
1. Select your instance (e.g., `mylinuxserver`).
2. Click on the **Connect** button.

### Step 9: Connect Using EC2 Instance Connect
Select the **EC2 Instance Connect** option.

### Step 10: Click Connect
Click the **Connect** button to access your instance.

### Step 11: Terminate the Instance
Once your work is completed, terminate the instance to avoid additional charges.

---

## Notes
- Ensure that you save your key pair securely as it is required to access your instance.
- Follow AWS best practices for security and cost management.

## Resources
For more information, refer to the [AWS EC2 Documentation](https://docs.aws.amazon.com/ec2/index.html).
