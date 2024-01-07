# aws_cloud_developer_associate

<h2>My learning odyssey
 for preparing for my AWS associate cloud developer exams</h2>

 # AWS IAM
<h2>Identity and Access Management</h2>

AWS IAM is way of creating an identity or a user and grouping them into groups or leaving them, making sure they are on a premission policy on what service to use in AWS. What I meant was that with IAM, you can create groups and then
create users within such groups. Each user can be in multiple groups and each one of them have a permission policy on form of a JSON format. This JSON format states what service is AWS they have permission to use and how to use them.
Making use of an AWS IAM account is better than using your root user account as this is more secure to use.
But you cannot add groups in groups.
The root user sohuld be only used for creating an IAM user but not be used for any other thing or shared.

<img src="https://www.msp360.com/resources/wp-content/uploads/2018/10/image4-1-1024x504.png"/>

# Beginning of AWS
<h2>AWS history</h2>
<p>AWS dated back to amazon e-commerce company where they felt the strength of their server infratrusture in 2002 and started innternally, It was in 2003 they realized they could make things such as IT for other people. In 2004, the AWS came up with a plan to create Amazon SQS and then upgraded to S3, EC2 in 2006. Now back today as they have taken over 47% of the cloud industry and have generated over 38 billion dollars in revenue, with Microsoft Azure being behind them taking up over 22% of the market</p>

<img src="https://docs.aws.amazon.com/images/wellarchitected/latest/high-performance-computing-lens/images/image4.png"/>

<p>
  After controlling the market, they scattered a lot of regions and availability zones across the planet to ensure their services are worldwide and the issue of latency is a no no.
</p>


# AWS ACCESSIBILITY
<h2>To make use of AWS we need to be able to access it</h2>

<h3>Well we have three ways of accesing AWS, which are as follows</h3>
<ul>
  <li>Using the standard AWS console</li>
  <li>Using the AWS CLI(Command Line Interface) either on your device or the AWS CloudShell</li>
  <li>Using the AWS SDK </li>
</ul>

![aws_cloud_shell](https://github.com/Ham12-3/aws_cloud_developer_associate/assets/93613316/d2c556d0-ce9f-4902-a360-0ff44f93763a)

To use the amazon CLI you'll need to get your CLI installed from AWS website then after that, you'll configure your access keys.
Try to make sure your access keys secrets are not revealed to someone else.
then you type in the code below 
```
aws --version
```

This is to check if your CLI installed successfully

Then after that you'll configure AWS, using the following command:
```
aws configure
```

# Exploring AWS CloudShell and Security Groups
<h2>Hello Cloud Enthusiasts! 👋 Today, let's take a deep dive into the functionalities of AWS CloudShell and the critical role Security Groups play in fortifying your AWS cloud infrastructure.</h2>

<ol>
 

<li>
 <h3>  AWS CloudShell: Seamless Command Line Access</h3>


AWS CloudShell offers a convenient command line interface directly accessible from the AWS Management Console. No more dealing with installations or configurations – it's a hassle-free way to manage your AWS resources right from your browser.

How to Access AWS CloudShell:

Simply open CloudShell from the AWS Management Console.
Leverage the AWS CLI directly in your browser for efficient resource management.
</li>


<li>
 <h3> Understanding Security Groups: Virtual Firewalls</h3>


What are Security Groups?
Security Groups act as virtual firewalls, managing inbound and outbound traffic to your AWS instances. They serve as the first line of defense for your cloud resources.

Granular Control:
Define rules within Security Groups to control traffic based on sources, ports, and protocols. This granular control ensures that only authorized access is granted to your AWS resources.
</li> 

<li>
 <h3>
    Navigating AWS CloudShell for Security Configuration
 </h3>


Let's walk through the process of configuring Security Groups using AWS CloudShell:

Access AWS CloudShell from the console.
Utilize the AWS CLI in the CloudShell for efficient security configurations.
</li>

<li>
 <h3> Tips for Optimal Security Group Management</h3>

 Regular Review:
Frequently review and update your Security Group rules to align with your evolving security requirements.

</li>
 
</ol>


AWS CloudShell Benefits:
Leverage AWS CloudShell for seamless command line access, making your security configurations more efficient and accessible.


![aws_cloud_shell](https://github.com/Ham12-3/aws_cloud_developer_associate/assets/93613316/03ad054a-476e-4a52-8e19-f709bd96f9ea)

![aws_security_groups](https://github.com/Ham12-3/aws_cloud_developer_associate/assets/93613316/2f0553ff-b7d2-42ac-b811-780583b05065)




<h2>Secure Shell (SSH) plays a crucial role in Amazon Web Services (AWS) by providing secure and encrypted communication for various tasks. Here are some specific uses of SSH in AWS:</h2>


<h3>Secure Remote Access:</h3>

<ul>
 <li>Purpose: SSH allows users to securely access and manage their AWS instances remotely.</li>
 <li>Benefit: This is particularly important for system administrators and developers who need to connect to their instances without compromising security.</li>
</ul>

<h3>File Transfer:</h3>
<ul>
 <li>Purpose: SSH is used for secure file transfers between local machines and AWS instances.</li>
 <li>Benefit: Users can move files securely between their local environment and the cloud, ensuring the confidentiality and integrity of the transferred data.</li>
</ul>

<h3>Command Execution:</h3>

<ul>
 <li>
Purpose: SSH enables users to execute commands on AWS instances remotely.</li>
 <li>Benefit: This feature is essential for system administration, configuration management, and troubleshooting without requiring direct physical access to the servers.</li>
</ul>


<h3>
Tunneling:</h3>
<ul>
 <li>Purpose: SSH tunneling allows secure transmission of data between local machines and AWS instances.</li>
 <li>
Benefit: Users can establish encrypted tunnels to transmit data, enhancing security for various applications, databases, or other services running on AWS.</li>
</ul>

<h3>Key Pair Authentication:</h3>
<ul>
 <li>
  
Purpose: SSH supports key pair authentication, reducing reliance on passwords for accessing AWS instances.
 </li>
 <li>Benefit: Key pair authentication enhances security by using public and private key pairs, making it more resistant to unauthorized access compared to password-based authentication.</li>
</ul>

<h3>
Identity and Access Management (IAM) Access:</h3>

<ul>
 <li>
  Purpose: SSH can be used in conjunction with IAM roles to control access to AWS resources.
 </li>
 <li>
  
Benefit: This ensures that users and systems have the appropriate permissions to perform actions on AWS, following the principle of least privilege.
 </li>
</ul>

<h3>
 Bastion Hosts:
</h3>
<ul>
 <li>
Purpose: SSH is often used to access a bastion host (jump host), which serves as an intermediary for accessing other instances in a private subnet.</li>
 <li>Benefit: Bastion hosts add an additional layer of security by acting as a gateway for accessing resources in a secure manner.</li>
</ul>

<p>
 Understanding and leveraging SSH in these scenarios contribute to a more secure and efficient management of AWS resources, ensuring the confidentiality and integrity of data and resources in the cloud environment.
</p>

![ssh](https://github.com/Ham12-3/aws_cloud_developer_associate/assets/93613316/a8a121ab-3a60-4ce0-8c72-468e94a729fa)



<h2>EC2 Instance Connect (EIC) is a simple and secure method for connecting to your Amazon EC2 Linux instances using Secure Shell (SSH). It eliminates the need to manage SSH keys manually and offers enhanced security features.</h2>


<h3>Key Features:</h3>
<ul>
 <li>
  
No SSH Key Management: EIC generates one-time use SSH keys, eliminating the need to store and distribute permanent keys.
 </li>
 <li>
  
IAM-Based Access Control: You can control SSH access to instances using AWS Identity and Access Management (IAM) policies and principals, ensuring granular control over who can connect to which instances.
 </li>
 <li>
  Secure Logging: All connection attempts are logged to AWS CloudTrail, providing an audit trail for security and compliance.
 </li>
</ul>

<h3>How it Works:</h3>

<ol>
 <li>
  User Requests Connection:
User initiates a connection request through the EC2 console, AWS CLI, or AWS SDKs.
 </li>
 <li>
  IAM Authorization:
AWS verifies the user's IAM permissions to access the instance.
 </li>
 <li>
  One-Time SSH Key Generation:
EIC generates a one-time SSH key pair and pushes the public key to the instance metadata.
 </li>
 <li>
  SSH Connection:
The user's SSH client connects to the instance using the private key, and the instance validates the public key from the metadata.
 </li>
 <li>
  Session Establishment:
Upon successful authentication, the SSH session is established, allowing interaction with the instance.
 </li>
</ol>

![image](https://github.com/Ham12-3/aws_cloud_developer_associate/assets/93613316/d678d722-cdf4-41b8-afb0-b776eb70a208)


<h3>
Using EIC with the AWS CLI:</h3>

<ol>
 <li>
  <p>Enable EIC on the Instance: (if not already enabled)</p>

  
  ```bash
    aws ec2 enable-instance-profile-on-instance \
    --instance-id instance-id \
    --instance-profile-name EC2InstanceConnect
```

 </li>

 <li>
  <p> Connect to Instance:</p>
 
```bash
    aws ec2-instance-connect send-ssh-public-key \
    --instance-id instance-id \
    --availability-zone availability-zone \
    --instance-os-user ubuntu
  ```
 </li>
 <li>
  Additional Benefits:

Streamlined Access: Simplifies access for developers and administrators.
Improved Security: Reduces security risks associated with managing SSH keys.
Auditability: Provides clear records of SSH access for compliance and troubleshooting.
Remember:
</li>
<li>

EIC is currently available for Linux instances only.
It supports SSH connections for both interactive sessions and command execution.
You can also use EIC to connect to instances using a web-based terminal in the EC2 console.
 </li>

 
</ol>

<h3>
 SOURCE: <a href="https://medium.com/avmconsulting-blog/connect-to-aws-rds-instance-using-ssm-and-ssh-tunneling-8900424a5bf7">A medium blog</a>
</h3>




















