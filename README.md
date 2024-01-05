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


