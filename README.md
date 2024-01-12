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


<br/>


<h2>Amazon EBS: Your Cloud Storage Powerhouse</h2>

<p>
 Imagine your cloud storage as a trusty toolbox. You need different tools for different jobs, and sometimes you need to expand your kit. Amazon EBS is like that magic toolbox that grows with you and adapts to your needs, with lightning-fast performance, limitless scalability, and unwavering reliability.
</p>


<p>
 Supercharged Speed:

![image](https://github.com/Ham12-3/aws_cloud_developer_associate/assets/93613316/bad5e7d2-233b-46c9-a3f2-ba49ae2e70d6)


With EBS, data reads and writes happen in a blink, keeping your projects running smoothly like a well-oiled machine. Say goodbye to frustrating lag and hello to instant access!
</p>

<p>

Stretch Your Storage Legs:

![image](https://github.com/Ham12-3/aws_cloud_developer_associate/assets/93613316/3220ad73-d2b9-4aa4-a852-20b2c3cfc650)


No more worrying about running out of storage space! EBS expands effortlessly as your needs grow, ensuring you always have enough room for your ideas and data. Think of it as a bottomless storage bin for your digital treasures.
 
</p>


<p>
 Fort Knox for Your Data:

![image](https://github.com/Ham12-3/aws_cloud_developer_associate/assets/93613316/35ebee99-67c5-4511-b132-e69d0fe6bdcb)


EBS safeguards your data like a digital Fort Knox, with automatic backups and built-in redundancy that protect against unexpected bumps in the road. Rest assured, your information is always safe and sound.
</p>

<p>
Budget-Friendly Flexibility:

![image](https://github.com/Ham12-3/aws_cloud_developer_associate/assets/93613316/aa66e9bc-c1ae-44f3-934d-4a44730fa185)


EBS offers a variety of storage plans to fit any budget, from budget-conscious beginners to high-performance power users. Choose the perfect option for your needs and watch your digital dollars stretch further.
 
</p>





**Perfect for:**

* **Websites and Databases:** Keep your online projects humming with stable, fast storage that handles all your data without breaking a sweat.
* **Big Data Adventures:** Dive into the world of massive datasets with confidence, knowing EBS can handle the heavy lifting and keep your analysis flowing smoothly.
* **DevOps Dreams:** Build, test, and deploy applications in record time with EBS's flexible storage options and effortless scaling.

**Ready to ditch the clunky storage solutions and unlock the full potential of your cloud projects?** Dive into the world of EBS and experience the difference!

**Learn More:**

* **Official AWS EBS Documentation:** https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/AmazonEBS.html
* **Get Started with EBS:** [[link to AWS EBS getting started guide]](https://aws.amazon.com/ebs/)
* **EBS Pricing:** [[link to AWS EBS pricing page]](https://aws.amazon.com/ebs/pricing/)

Remember, EBS is like your partner in cloud crime, always there to support your projects and help you achieve your goals. So go forth, build, create, and innovate, knowing your data is in good hands!




## What is an AWS AMI?

**Imagine a blueprint for your ideal cloud server.** This blueprint includes the operating system, pre-installed software, and configurations you need to get your project running. That's what an **Amazon Machine Image (AMI)** is in the AWS cloud.

**Think of it this way:**

* **Traditional VM:** Like building a server from scratch, piece by piece, requiring time and effort.
* **AWS AMI:** Like using a prefabricated house – choose the design you like, move in quickly, and customize as needed.

**Here are the key aspects of an AWS AMI:**

* **Template:** It's a template containing the software and configuration of a server instance.
* **Fast Deployments:** Launch new server instances from the AMI in seconds, saving you time and effort.
* **Variety:** Choose from a massive library of pre-built AMIs for various operating systems and applications.
* **Customization:** Build and share your own custom AMIs with specific configurations tailored to your needs.
* **Cost-Effective:** Pay only for the resources you use with the chosen AMI instance type.
* **Security:** Leverage pre-baked security configurations and patch management for secure deployments.

**Next, let's explore the different types of AMIs:**

* **Amazon-provided AMIs:** Pre-built images for various OSes, software stacks, and applications.
* **Community AMIs:** Created and shared by other AWS users.
* **Your own custom AMIs:** Tailor-made images for specific needs and configurations.

**In essence, AMIs are the building blocks for quick, flexible, and cost-effective deployments in the AWS cloud.** 





<hr>


# AWS EFS


**Imagine a file storage system that:**

* **Scales on demand:** No need to pre-provision storage or worry about running out of space. It grows and shrinks automatically as your data needs change, just like magic!
* **Eliminates servers:** Ditch the clunky server racks and say goodbye to tedious server management. AWS EFS is fully serverless, letting you focus on your applications instead of the underlying infrastructure.
* **Shares files effortlessly:** Seamlessly share data across multiple Amazon Elastic Compute Cloud (EC2) instances, on-premises servers, and even containerized applications. Collaboration just got a whole lot easier!
* **Delivers high performance:** Get fast and consistent throughput for even the most demanding workloads, ensuring smooth operation and happy users.
* **Keeps your data safe:** Enjoy industry-leading security with features like encryption at rest and in transit, access control, and data durability that's practically unheard of (99.999999999%!).
* **Pays only for what you use:** No upfront costs or hidden fees. You only pay for the storage you actually use, making it a cost-effective solution for any budget.

That's AWS EFS in a nutshell! It's a revolutionary file storage service that simplifies data management in the cloud, making it ideal for a wide range of applications, from web and mobile apps to content management systems and big data processing.

Here's an image to help visualize what AWS EFS does:



Think of it as a bridge between your traditional on-premises storage and the limitless possibilities of the cloud. With AWS EFS, you can finally break free from the limitations of physical servers and embrace the agility, scalability, and cost-efficiency of cloud storage.

If you're interested in learning more, here are some helpful resources:

* **AWS EFS website:** [https://aws.amazon.com/efs/](https://aws.amazon.com/efs/)
* **AWS EFS documentation:** [https://docs.aws.amazon.com/efs/latest/ug/whatisefs.html](https://docs.aws.amazon.com/efs/latest/ug/whatisefs.html)
* **Blog post: 5 Reasons to Use AWS EFS for Your Cloud Applications:** [https://aws.amazon.com/efs/customers/](https://aws.amazon.com/efs/customers/)

![racks-of-servers](https://github.com/Ham12-3/aws_cloud_developer_associate/assets/93613316/f02ba35a-c97b-4052-bcba-6c94791c0a83)


# The Amazon Application Load Balancer (ALB) is a managed service offered by Amazon Web Services (AWS) that helps you distribute incoming traffic across multiple targets, such as Amazon EC2 instances, containers, or IP addresses. Think of it as a sophisticated traffic cop for your cloud applications, ensuring smooth flow and preventing bottlenecks.



Here's how the ALB works:

* **Distributes traffic:** When a user visits your website or uses your application, their request hits the ALB. The ALB then intelligently routes the request to one of your available targets, ensuring everyone gets served quickly and efficiently.
* **Scales on demand:** As your traffic fluctuates, the ALB automatically scales up or down its resources to handle the load. This means you avoid paying for idle capacity during low traffic periods, and your users never experience slowdowns during peak times.
* **Enhances security:** The ALB offers built-in DDoS protection and TLS encryption to safeguard your applications from malicious attacks and protect sensitive data.
* **Provides insights:** The ALB offers detailed monitoring and reporting tools, giving you visibility into your traffic patterns and application health. This information helps you identify and troubleshoot issues before they impact your users.

**Key benefits of using the ALB:**

* **Improved performance:** Reduces website loading times and enhances user experience.
* **Increased scalability:** Adapts to fluctuating traffic without manual intervention.
* **Enhanced security:** Protects your applications from attacks and data breaches.
* **Simplified management:** Provides a centralized platform for managing your application infrastructure.
* **Reduced costs:** Pay only for the resources you use, thanks to automatic scaling.

**Who can benefit from the ALB?**

* **Web developers:** Distribute traffic across web servers to ensure optimal performance.
* **App developers:** Scale mobile and web applications effortlessly.
* **DevOps engineers:** Streamline application management and automate scaling.
* **Anyone running cloud applications:** Improve performance, security, and scalability.

**In simple terms, the ALB is like having a highly trained traffic control center for your applications.** It keeps traffic flowing smoothly, protects your applications from harm, and gives you full visibility into what's happening. This makes it a valuable tool for any organization running applications in the cloud.

I hope this explanation clarifies what the Amazon ALB is and how it can benefit you. If you have any further questions, feel free to ask!


![3ga8w5y7gv9q4xukct62](https://github.com/Ham12-3/aws_cloud_developer_associate/assets/93613316/589bd94a-57c0-4ffa-98eb-fcb9d6d88c52)



## Imagine a group of friends... but for your cloud servers!

Think of an **Amazon Auto Scaling Group** as a team of virtual servers working together to handle your application's workload, just like a group of friends helping each other with a task. Each server is like a friend, and the group scales up or down automatically based on your needs.

Here's how it works:

**1. You set the desired number of servers in the group:** This is like deciding how many friends you need to help with the task.

**2. Servers automatically spin up or down:** If your website traffic suddenly increases, new servers are added to the group like more friends pitching in. Conversely, if things quiet down, some servers can take a break or even leave the group.

**3. Servers are always healthy and working:** Just like reliable friends, Amazon Auto Scaling continuously monitors the health of each server and replaces any unhealthy ones quickly, ensuring your application keeps running smoothly.

**4. You pay only for what you use:** This is like splitting the bill among your friends. You only pay for the servers that are actually working, not for the ones on standby.

**Benefits of using Amazon Auto Scaling Groups:**

* **Cost-effective:** No more overpaying for unused resources.
* **Highly available:** Your application stays up and running even during traffic spikes.
* **Scalable:** Easily handle changing demand without manual intervention.
* **Manageable:** Simplify your infrastructure management and focus on your application.

**Here's an analogy to help you visualize:**

* **Think of your website as a restaurant.** During peak hours, you need more waiters (servers) to handle the influx of customers. But during off-peak hours, you don't need as many. Amazon Auto Scaling is like having a team of waiters who automatically show up when needed and disappear when they're not, saving you money on labor costs.

**In short, Amazon Auto Scaling Groups take the guesswork out of server scaling, giving you a reliable and cost-effective way to handle fluctuating demand for your cloud resources.**

I hope this explanation helps! Feel free to ask if you have any further questions.


![as-basic-diagram](https://github.com/Ham12-3/aws_cloud_developer_associate/assets/93613316/d1237ba2-7aea-428d-adff-e6256260b0d7)











