# AWS Cloud Practitioner - Practice Exam 1

Click on the **Answer** button for the correct answer and its explanation.

## Domain: Cloud Concepts
**Q 1: According to AWS, what is the benefit of Elasticity?**

    A. Minimize storage requirements by reducing logging and auditing activities
    B. Create systems that scale to the required capacity based on changes in demand
    C. Enable AWS to automatically select the most cost-effective services.
    D. Accelerate the design process because recovery from failure is automated, reducing the need for testing


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>

<details markdown=1><summary markdown='span'>Explanation</summary>

The concept of Elasticity is the means of an application having the ability to scale up and scale down based on demand. An example of such a service is the Autoscaling service

For more information on AWS Autoscaling service, please refer to the below URL: https://aws.amazon.com/autoscaling/

A, C and D are incorrect. Elasticity will not have positive effects on storage, cost or design agility.
</details>

---

## Domain : Billing and Pricing
**Q2: Which tool can you use to forecast your AWS spending?**

    A. AWS Organizations
    B. Amazon Dev Pay
    C. AWS Trusted Advisor
    D. AWS Cost Explorer


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – D
</details>

---

## Domain : Technology
**Q3: A business analyst would like to move away from creating complex database queries and static spreadsheets when generating regular reports for high-level management. They would like to publish insightful, graphically appealing reports with interactive dashboards. Which service can they use to accomplish this?**

    A. Amazon QuickSight
    B. Business intelligence on Amazon Redshift
    C. Amazon CloudWatch dashboards
    D. Amazon Athena integrated with Amazon Glue

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>

---



---



---



---






## Domain: Cloud Concepts
**Q 1: According to AWS, what is the benefit of Elasticity?**

    A. Minimize storage requirements by reducing logging and auditing activities
    B. Create systems that scale to the required capacity based on changes in demand
    C. Enable AWS to automatically select the most cost-effective services.
    D. Accelerate the design process because recovery from failure is automated, reducing the need for testing


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>

<details markdown=1><summary markdown='span'>Explanation</summary>

The concept of Elasticity is the means of an application having the ability to scale up and scale down based on demand. An example of such a service is the Autoscaling service

For more information on AWS Autoscaling service, please refer to the below URL: https://aws.amazon.com/autoscaling/

A, C and D are incorrect. Elasticity will not have positive effects on storage, cost or design agility.
</details>



## Domain : Billing and Pricing

**Q2: Which tool can you use to forecast your AWS spending?**

    A. AWS Organizations  
    B. Amazon Dev Pay  
    C. AWS Trusted Advisor  
    D. AWS Cost Explorer

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – D
</details>

**Explanation :** 

The AWS Documentation mentions the following.

Cost Explorer is a free tool that you can use to view your costs. You can view data up to the last 12 months. You can forecast how much you are likely to spend for the next 12 months and get recommendations for what Reserved Instances to purchase. You can use Cost Explorer to see patterns in how much you spend on AWS resources over time, identify areas that need further inquiry, and see trends that you can use to understand your costs. You also can specify time ranges for the data and view time data by day or by month.

![AWS cost explorer tool](data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20985%20495'%3E%3C/svg%3E "AWS cost explorer tool")

![AWS cost explorer tool](https://www.whizlabs.com/blog/wp-content/uploads/2022/01/aws-cost-explorer-tool.webp "AWS cost explorer tool")

**For more information on the AWS Cost Explorer, please refer to the below URL:**  [http://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/cost-explorer-what-is.html](http://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/cost-explorer-what-is.html)

**A, B and C are incorrect.** These services do not relate to billing and cost.

## Domain : Technology

**Q3: A business analyst would like to move away from creating complex database queries and static spreadsheets when generating regular reports for high-level management. They would like to publish insightful, graphically appealing reports with interactive dashboards. Which service can they use to accomplish this?**

    A. Amazon QuickSight  
    B. Business intelligence on Amazon Redshift  
    C. Amazon CloudWatch dashboards  
    D. Amazon Athena integrated with Amazon Glue  

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>

**Explanation :** 

Amazon QuickSight is the most appropriate service in the scenario. It is a fully-managed service that allows for insightful business intelligence reporting with creative data delivery methods, including graphical and interactive dashboards. QuickSight includes machine learning that allows users to discover inconspicuous trends and patterns on their datasets.

![AWS Quick Sight](data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%201052%20647'%3E%3C/svg%3E "AWS Quick Sight")

![AWS Quick Sight](https://www.whizlabs.com/blog/wp-content/uploads/2022/01/aws-quick-sight.webp "AWS Quick Sight")

AWS Quick Sight tool | Source: aws.amazon.com/quicksight

*   **Option B is INCORRECT.** Amazon Redshift service is a data warehouse and will not meet the requirements of interactive dashboards and dynamic means of delivering reports.
*   **Option C is INCORRECT.** Amazon CloudWatch dashboards will not accomplish the requirements of the scenario. They are used to monitor AWS system resources and infrastructure services, though they are customizable and present information graphically.
*   **Option D is INCORRECT.** Amazon Athena is a query service that allows for easy data analysis in Amazon S3 by using standard SQL. The service does not meet the requirements of the scenario. 

## Domain : Technology

**Q4. What is the AWS feature that enables fast, easy and secure transfers of files over long distances between your client and your Amazon S3 bucket?**

    A. File Transfer  
    B. HTTP Transfer  
    C. Amazon S3 Transfer Acceleration  
    D. S3 Acceleration

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>

**Explanation :** 

The AWS Documentation mentions the following.

Amazon S3 Transfer Acceleration enables fast, easy, and secure transfers of files over long distances between your client and an S3 bucket. Transfer Acceleration takes advantage of Amazon CloudFront’s globally distributed edge locations. As the data arrives at an edge location, data is routed to Amazon S3 over an optimized network path.

For more information on S3 transfer acceleration, please visit the Link:  [http://docs.aws.amazon.com/AmazonS3/latest/dev/transfer-acceleration.html](http://docs.aws.amazon.com/AmazonS3/latest/dev/transfer-acceleration.html)

**Options A, B and D are incorrect** . These features deal with transferring data but not between clients and an S3 bucket.

## Domain : Security

**Q5: What best describes the “Principle of Least Privilege ”? Choose the correct answer from the options given below.**

    A. All users should have the same baseline permissions granted to them to use basic AWS services.  
    B. Users should be granted permission to access only resources they need to do their assigned job.  
    C. Users should submit all access requests in written form so that there is a paper trail of who needs access to different AWS resources.  
    D. Users should always have a little more permission than they need.

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>

**Explanation :** 

The principle means giving a user account only those privileges which are essential to perform its intended function. For example, a user account for the sole purpose of creating backups does not need to install the software. Hence, it has rights only to run backup and backup-related applications. 

For more information on the principle of least privilege, please refer to the following link: [https://en.wikipedia.org/wiki/Principle\_of\_least\_privilege](https://en.wikipedia.org/wiki/Principle_of_least_privilege)

**Options A, C, and D are incorrect.** These actions would not adhere to the Principle of Least Privilege.

## Domain : Security

**Q6: A web administrator maintains several public and private web-based resources for an organisation. Which service can they use to keep track of the expiry dates of SSL/TLS certificates as well as updating and renewal?**

    A. AWS Data Lifecycle Manager  
    B. AWS License Manager  
    C. AWS Firewall Manager  
    D. AWS Certificate Manager

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – D
</details>

**Explanation :** 

The AWS Certificate Manager allows the web administrator to maintain one or several SSL/TLS certificates, both private and public certificates including their update and renewal so that the administrator does not worry about the imminent expiry of certificates.  [https://aws.amazon.com/certificate-manager/](https://aws.amazon.com/certificate-manager/)

*   **Option A is INCORRECT** . The AWS Lifecycle Manager creates life cycle policies for specified resources to automate operations. [https://docs.aws.amazon.com/dlm/?id=docs\_gateway](https://docs.aws.amazon.com/dlm/?id=docs_gateway)

*   **Option B is INCORRECT.** AWS License Manager serves the purpose of differentiating, maintaining third-party software provisioning vendor licenses. It also decreases the risk of license expirations and the penalties. [https://docs.aws.amazon.com/license-manager/?id=docs\_gateway](https://docs.aws.amazon.com/license-manager/?id=docs_gateway)

*   **Option C is INCORRECT.** AWS Firewall Manager aids in the administration of Web Application Firewall (WAF), by presenting a centralised point of setting firewall rules across different web resources. [https://docs.aws.amazon.com/firewall-manager/?id=docs\_gateway](https://docs.aws.amazon.com/firewall-manager/?id=docs_gateway)

## Domain : Security

**Q7: Which of the following is the responsibility of the customer to ensure the availability and backup of the EBS volumes?**

    A. Delete the data and create a new EBS volume.  
    B. Create EBS snapshots.  
    C. Attach new volumes to EC2 Instances.  
    D. Create copies of EBS Volumes.

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>

**Explanation :** 

Snapshots are _incremental_ backups, which means that only the blocks on the device that have changed after your most recent snapshot are saved. 

When you create an EBS volume based on a snapshot, the new volume begins as an exact replica of the original volume that was used to create the snapshot. The replicated volume loads data in the background so that you can begin using it immediately.

![Amazon EBS snapshots](data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20671%20589'%3E%3C/svg%3E "Amazon EBS snapshots")

![Amazon EBS snapshots](https://www.whizlabs.com/blog/wp-content/uploads/2022/01/aws-ebs-snapshots.webp "Amazon EBS snapshots")

Amazon EBS snapshots | Source: aws.amazon.com

**Option A is incorrect** because there is no need for backup of the volumes if data is already deleted.

**Option C is incorrect** because attaching more EBS volumes doesn ’t ensure availability, if there is no snapshot then the volume cannot be available to a different availability zone.

**Option D is incorrect** EBS volumes cannot be copied, they can only be replicated using snapshots.

For more information on EBS Snapshots, please refer to the below URL: [https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSSnapshots.html](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/EBSSnapshots.html)

## Domain : Security

**Q8: Which of the following services can be used as an application firewall in AWS?**

    A. AWS Snowball  
    B. AWS WAF  
    C. AWS Firewall  
    D. AWS Protection  

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>

**Explanation :** 

The AWS Documentation mentions the following:

AWS WAF is a web application firewall that lets you monitor the HTTP and HTTPS requests that are forwarded to Amazon CloudFront or an Application Load Balancer. AWS WAF also lets you control access to your content.

AWS Snowball, a part of the AWS Snow Family, is an edge computing, data migration, and edge storage device that comes in two options. Snowball Edge Storage Optimized devices provide both block storage and Amazon S3-compatible object storage, and 40 vCPUs.

For more information on AWS WAF, please refer to the below URL: [https://docs.aws.amazon.com/waf/latest/developerguide/waf-chapter.html](https://docs.aws.amazon.com/waf/latest/developerguide/waf-chapter.html)  
[https://aws.amazon.com/snowball/?whats-new-cards.sort-by=item.additionalFields.postDateTime &whats-new-cards.sort-order=desc](https://aws.amazon.com/snowball/?whats-new-cards.sort-by=item.additionalFields.postDateTime&whats-new-cards.sort-order=desc)

## Domain : Cloud Concepts

**Q9: Your design team is planning to design an application that will be hosted on the AWS Cloud. One of their main non-functional requirements is given below:**  
**Reduce inter-dependencies so failures do not impact other components.**  
**Which of the following concepts does this requirement relate to?**

    A. Integration  
    B. Decoupling  
    C. Aggregation  
    D. Segregation

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>

**Explanation :** 

The entire concept of decoupling components ensures that the different components of applications can be managed and maintained separately. If all components are tightly coupled, the entire application would go down when one component goes down. Hence it is always a better practice to decouple application components.

For more information on a decoupled architecture, please refer to the below URL:  [http://whatis.techtarget.com/definition/decoupled-architecture](http://whatis.techtarget.com/definition/decoupled-architecture)

## Domain : Billing and Pricing

**Q10: A manufacturing firm has recently migrated their application servers to the Amazon EC2 instance. The IT Manager is looking for the details of upcoming scheduled maintenance activities which AWS would be performing on AWS resources, that may impact the services on these EC2 instances.**

**Which of the following services can alert you about the changes that can affect resources in your account?** 

    A. AWS Organizations  
    B. AWS Personal Health Dashboard  
    C. AWS Trusted Advisor  
    D. AWS Service Health Dashboard

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>

**Explanation :** 

AWS Personal Health Dashboard provides alerts for AWS services availability &performance which may impact resources deployed in your account. Customers get emails &mobile notifications for scheduled maintenance activities which might impact services on these AWS resources. 

**Option A is incorrect** as AWS Organizations do not provide any notifications for scheduled maintenance activities.

**Option C is incorrect** as AWS Trusted Advisor will provide notification on AWS resources created within the account for cost optimization, security, fault tolerance, performance, and service limits. It will not provide notification for scheduled maintenance activities performed by AWS on its resources.  

**Option D is incorrect** as Service Health Dashboard displays the general status of all AWS services &will not display scheduled maintenance activities.

For more information on the AWS Organizations, please refer to the below URL:  [https://aws.amazon.com/premiumsupport/technology/personal-health-dashboard/](https://aws.amazon.com/premiumsupport/technology/personal-health-dashboard/)

## Domain : Security

**Q11: Which of the following AWS services can be used to retrieve configuration changes made to AWS resources causing operational issues?**

    A. Amazon Inspector  
    B. AWS CloudFormation  
    C. AWS Trusted Advisor  
    D. AWS Config

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – D
</details>

**Explanation :** 

AWS Config can be used to audit, evaluate configurations of AWS resources. If there are any operational issues, AWS config can be used to retrieve configurational changes made to AWS resources that may have caused these issues.

*   **Option A is incorrect** as Amazon Inspector can be used to analyze potential security threats for an Amazon EC2 instance against an assessment template with predefined rules. It does not provide historical data for configurational changes done to AWS resources.
*   **Option B is incorrect** as AWS CloudFormation provided templates to provision and configure resources in AWS.
*   **Option C is incorrect** as AWS Trusted Advisor can help optimize resources with AWS cloud with respect to cost, security, performance, fault tolerance, and service limits. It does not provide historical data for configurational changes done to AWS resources.

For more information on AWS Config, refer to the following URL:[https://docs.aws.amazon.com/config/latest/developerguide/WhatIsConfig.html](https://aws.amazon.com/config/faq/)

## Domain : Security

**Q12: An organization runs several EC2 instances inside a VPC using three subnets, one for Development, one for Test, and one for Production. The Security team has some concerns about the VPC configuration. It requires restricting communication across the EC2 instances using Security Groups.**

**Which of the following options is true for Security Groups related to the scenario?**

    A. You can change a Security Group associated with an instance if the instance is in the running state.  
    B. You can change a Security Group associated with an instance if the instance is in the hibernate state.  
    C. You can change a Security Group only if there are no instances associated to it.  
    D. The only Security Group you can change is the Default Security Group.

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>

**Explanation :** 

*   **Option A is CORRECT** because the AWS documentation mentions it in the section called “Changing an Instance’s Security Group” using the following sentence: “After you launch an instance into a VPC, you can change the security groups that are associated with the instance. You can change the security groups for an instance when the instance is in the running or stopped state.”
*   **Option B is incorrect** as You can change the security groups for an instance when the instance is in the running or stopped state, not hibernate state.
*   **Option C is incorrect** because there have to be some instances associated.
*   **Option D is incorrect** because other security groups can also be changed.

**Reference:** [https://docs.aws.amazon.com/en\_pv/vpc/latest/userguide/VPC\_SecurityGroups.html](https://docs.aws.amazon.com/en_pv/vpc/latest/userguide/VPC_SecurityGroups.html)

## Domain : Technology

**Q13: Which of the following features of Amazon RDS allows for better availability of databases? Choose the answer from the options given below.**

    A. VPC Peering  
    B. Multi-AZ  
    C. Read Replicas  
    D. Data encryption

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>

**Explanation :** 

The AWS Documentation mentions the following.

If you are looking to use replication to increase database availability while protecting your latest database updates against unplanned outages, consider running your DB instance as a Multi-AZ deployment.

For more information on AWS RDS, please visit the FAQ Link:[https://aws.amazon.com/rds/faqs/](https://aws.amazon.com/rds/faqs/)

## Domain : Technology

**Q14: Your company wants to move an existing Oracle database to the AWS Cloud. Which of the following services can help facilitate this move?**

    A. AWS Database Migration Service  
    B. AWS VM Migration Service  
    C. AWS Inspector  
    D. AWS Trusted Advisor

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>

**Explanation :** 

The AWS Documentation mentions the following.

AWS Database Migration Service helps you migrate databases to AWS quickly and securely. The source database remains fully operational during the migration, minimizing downtime to applications that rely on the database. The AWS Database Migration Service can migrate your data to and from the most widely used commercial and open-source databases.

For more information on AWS Database migration, please refer to the below URL:[https://aws.amazon.com/dms/](https://aws.amazon.com/dms/)

## Domain : Security

**Q15: Which of the following services allows you to analyze EC2 Instances against pre-defined security templates to check for vulnerabilities?**

    A. AWS Trusted Advisor  
    B. AWS Inspector  
    C. AWS WAF  
    D. AWS Shield

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>

**Explanation :** 

The AWS Documentation mentions the following.

Amazon Inspector enables you to analyze the behavior of your AWS resources and helps you to identify potential security issues. Using Amazon Inspector, you can define a collection of AWS resources that you want to include in an assessment target. You can then create an _assessment template_ and launch a security _assessment run_ of this target.

For more information on AWS Inspector, please refer to the below URL:[https://docs.aws.amazon.com/inspector/latest/userguide/inspector\_introduction.html](https://docs.aws.amazon.com/inspector/latest/userguide/inspector_introduction.html)

## Domain : Technology

**Q16: A website for an international sport governing body would like to serve its content to viewers from different parts of the world in their vernacular language. Which of the following services provide location-based web personalization using geolocation headers?**

    A. Amazon CloudFront  
    B. Amazon EC2 Instance  
    C. Amazon Lightsail  
    D. Amazon Route 53

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>

**Explanation :** 

Amazon CloudFront supports country-level location-based web content personalization with a feature called Geolocation Headers.

You can configure CloudFront to add additional geolocation headers that provide more granularity in your caching and origin request policies. The new headers give you more granular control of cache behavior and your origin access to the viewer’s country name, region, city, postal code, latitude, and longitude, all based on the viewer’s IP address.

![CloudFront Distribution](data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%20909%20544'%3E%3C/svg%3E "Amazon CloudFront with Geolocation Headers")

![CloudFront Distribution](https://www.whizlabs.com/blog/wp-content/uploads/2022/01/cc16.webp "Amazon CloudFront with Geolocation Headers")

*   **Option B is INCORRECT** because EC2 is just a distractor, not suitable for routing and delivery.
*   **Option C is INCORRECT** because Amazon Lightsail will primarily allow for developing, deploying, and hosting websites and web applications. The service will not meet the requirements of the scenario.
*   **Option D is INCORRECT** because the geolocation routing policy of Route53 allows different resources to serve content based on the origin of the request. Route 53 does not use geolocation headers.

**References:**

[https://aws.amazon.com/about-aws/whats-new/2020/07/cloudfront-geolocation-headers/](https://aws.amazon.com/about-aws/whats-new/2020/07/cloudfront-geolocation-headers/)  
[https://aws.amazon.com/blogs/networking-and-content-delivery/leverage-amazon-cloudfront-geolocation-headers-for-state-level-geo-targeting/](https://aws.amazon.com/blogs/networking-and-content-delivery/leverage-amazon-cloudfront-geolocation-headers-for-state-level-geo-targeting/)

## Domain : Security

**Q17: Which of the following can be used to protect against DDoS attacks? Choose 2 answers from the options given below.**

    A. AWS EC2  
    B. AWS RDS  
    C. AWS Shield  
    D. AWS Shield Advanced

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C AND D
</details>

**Explanation :** 

The AWS Documentation mentions the following:

AWS Shield –All AWS customers benefit from the automatic protections of AWS Shield Standard, at no additional charge. AWS Shield Standard defends against most common, frequently occurring network and transport layer DDoS attacks that target your web site or applications

AWS Shield Advanced –For higher levels of protection against attacks targeting your web applications running on Amazon EC2, Elastic Load Balancing (ELB), CloudFront, and Route 53 resources, you can subscribe to AWS Shield Advanced. AWS Shield Advanced provides expanded DDoS attack protection for these resources.

For more information on AWS Shield, please refer to the below URL:[https://docs.aws.amazon.com/waf/latest/developerguide/ddos-overview.html](https://docs.aws.amazon.com/waf/latest/developerguide/ddos-overview.html)

## Domain : Technology

**Q18: Which of the following are the recommended resources to be deployed in the  Amazon VPC private subnet?**

    A. NAT Gateways  
    B. Bastion Hosts  
    C. Database Servers  
    D. Internet Gateways

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>

**Explanation :** 

As Database servers contain confidential information, so for a security perspective, it should be deployed in a **Private Subnet** .

Amazon Virtual Private Cloud (Amazon VPC) enables the user to launch AWS resources into a virtual network that a user has defined.

**Option A is incorrect** because NAT devices (**NAT Gateway, Nat Instance** ) allow instances in private subnets to connect to the internet, other VPCs, or on-premises networks. It is deployed in a public subnet.

**Option B is incorrect** because **bastion host** is a server whose purpose is to provide access (SSH access) to a private network from an external network, such as the Internet. It is deployed in a public subnet.

**Option D is incorrect** because an **Internet Gateway** is a horizontally scaled, redundant, and highly available VPC component that allows communication between your VPC and the internet.

For more information on AWS VPC, please refer to the below URL:[https://docs.aws.amazon.com/vpc/latest/userguide/VPC\_Networking.html](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Networking.html)  
[https://docs.aws.amazon.com/vpc/latest/userguide/VPC\_Internet\_Gateway.html](https://docs.aws.amazon.com/vpc/latest/userguide/VPC_Internet_Gateway.html)  
[https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat.html](https://docs.aws.amazon.com/vpc/latest/userguide/vpc-nat.html)  
[https://aws.amazon.com/blogs/security/how-to-record-ssh-sessions-established-through-a-bastion-host/](https://aws.amazon.com/blogs/security/how-to-record-ssh-sessions-established-through-a-bastion-host/)

## Domain : Technology

**Q19: A company wants to utilize AWS storage. For them, low storage cost is paramount. The data is rarely retrieved and a data retrieval time of 13-14 hours is acceptable for them. What is the best storage option to use?**

    A. Amazon S3 Glacier  
    B. S3 Glacier Deep Archive  
    C. Amazon EBS volumes  
    D. AWS CloudFront

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>

**Explanation :** 

**S3 Glacier Deep Archive** offers the lowest cost storage in the cloud, at prices lower than storing and maintaining data in on-premises magnetic tape libraries or archiving data offsite.

It expands our data archiving offerings, enabling you to select the optimal storage class based on storage and retrieval costs, and retrieval times.

**Option B is correct** because S3 Glacier Deep Archive offers low-cost storage and retrieval time doesn ’t matter for the company. If the question asks for fast retrieval time then S3 Glacier would be correct.

**Option A is incorrect** because S3 Glacier is not cheaper than S3 Glacier Deep Archive.

**Options C and D are incorrect** because they are not suitable for data archive and faster retrieval. Also, the CloudFront is not for storage.

With **S3 Glacie** r, customers can store their data cost-effectively for months, years, or even decades. S3 Glacier enables customers to offload the administrative burdens of operating and scaling storage to AWS, so they don ’t have to worry about capacity planning, hardware provisioning, data replication, hardware failure detection, and recovery, or time-consuming hardware migrations.

*   **Amazon S3 Glacier** for archiving data that might infrequently need to be restored within a few hours
*   **S3 Glacier Deep Archive** for archiving long-term backup cycle data that might infrequently need to be restored within 12 hours

|     |     |     |     |
| --- | --- | --- | --- |
| **Storage class** | **Expedited** | **Standard** | **Bulk** |
| Amazon S3 Glacier | 1–5 minutes | 3–5 hours | 5–12 hours |
| S3 Glacier Deep Archive | Not available | Within 12 hours | Within 48 hours |

**Reference:**

[https://docs.aws.amazon.com/amazonglacier/latest/dev/introduction.html](https://aws.amazon.com/documentation/glacier/)  
[https://docs.aws.amazon.com/prescriptive-guidance/latest/backup-recovery/amazon-s3-glacier.html](https://docs.aws.amazon.com/prescriptive-guidance/latest/backup-recovery/amazon-s3-glacier.html)  
[https://aws.amazon.com/s3/storage-classes/](https://aws.amazon.com/s3/storage-classes/)

## Domain : Cloud Concepts

**Q20: Which AWS service provides a fully managed NoSQL database service that provides fast and predictable performance with seamless scalability?**

    A. AWS RDS  
    B. DynamoDB  
    C. Oracle RDS  
    D. Elastic Map Reduce

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>

**Explanation :** 

DynamoDB is a fully managed NoSQL offering provided by AWS. It is now available in most regions for users to consume.

For more information on AWS DynamoDB, please refer to the below URL:[http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html](http://docs.aws.amazon.com/amazondynamodb/latest/developerguide/Introduction.html)

## Domain : Cloud Concepts

**Q21: For which of the following AWS resources, the Customer is responsible for the infrastructure-related security configurations?**

    A. Amazon RDS  
    B. Amazon DynamoDB  
    C. Amazon EC2  
    D. AWS Fargate

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>

**Explanation :** 

Amazon EC2 is an Infrastructure as a Service (IaaS) for which customers are responsible for the security and the management of guest operating systems.

*   **Options A, B, and D are incorrect** as all these resources are part of abstracted services for which AWS is responsible for the security, &infrastructure layer. Customers are responsible for data that is saved on these resources.

For more information on the Shared responsibility model, refer to the following URL:[https://aws.amazon.com/compliance/shared-responsibility-model/](https://aws.amazon.com/compliance/shared-responsibility-model/)

## Domain : Cloud Concepts

**Q22: In the shared responsibility model for infrastructure services, such as Amazon Elastic Compute Cloud, which of the below two are customers responsibility?**

    A. Network infrastructure  
    B. Amazon Machine Images (AMIs)  
    C. Virtualization infrastructure  
    D. Physical security of hardware  
    E. Policies and configuration

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B AND E
</details>

**Explanation :** 

In the shared responsibility model, AWS is primarily responsible for “Security of the Cloud.” The customer is responsible for “Security in the Cloud.” In this scenario, the mentioned AWS product is IAAS (Amazon EC2) and AWS manages the security of the following assets:

–Facilities

–Physical security of hardware

–Network infrastructure

–Virtualization infrastructure

Customers are responsible for the security of the following assets:

–Amazon Machine Images (AMIs)

–Operating systems

–Applications

–Data in transit

–Data at rest

–Data stores

–Credentials

–Policies and configuration

*   **Option A is incorrect.** Refer to the explanation above and link in the references for more details.
*   **Option B is Correct.** Refer to the explanation above and link in the references for more details.
*   **Option C is incorrect.** Refer to the explanation above and link in the references for more details.
*   **Option D is incorrect.** Refer to the explanation above and link in the references for more details.
*   **Option E is correct.** Refer to the explanation above and link in the references for more details.

**References:**

[https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html](https://docs.aws.amazon.com/wellarchitected/latest/security-pillar/welcome.html)  
[https://aws.amazon.com/architecture/well-architected/?wa-lens-whitepapers.sort-by=item.additionalFields.sortDate &wa-lens-whitepapers.sort-order=desc](https://aws.amazon.com/architecture/well-architected/?wa-lens-whitepapers.sort-by=item.additionalFields.sortDate&wa-lens-whitepapers.sort-order=desc)

## Domain : Billing and Pricing

**Q23: AWS offers two savings plans to enable more savings and flexibility for its customers, namely, compute saving plans and EC2 Instance Savings plans.**

**Which of the below statement is FALSE regarding Saving Plans?**

    A. Capacity Reservations are not provided with Saving Plans.  
    B. Savings Plans are available for all the regions.  
    C. Savings plans will apply on ‘On-Demand Capacity Reservations’ that customers can allocate for their needs.  
    D. The prices for Savings Plans do not change based on the amount of hourly commitment.

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>

**Explanation :** 

*   **Option A** is **INCORRECT** . The given statement is True.
*   **Option B** is **CORRECT** . The given statement is False. For China Regions, savings plans are not available.
*   **Option C** is **INCORRECT** . The given statement is True.
*   **Option D** is **INCORRECT** . The given statement is True.

**Reference:**  [https://docs.aws.amazon.com/savingsplans/latest/userguide/what-is-savings-plans.html#sp-ris](https://docs.aws.amazon.com/savingsplans/latest/userguide/what-is-savings-plans.html#sp-ris)

## Domain : Technology

**Q24: Which of the below-listed services is a region-based AWS service?**

    A. AWS IAM  
    B. Amazon EFS  
    C. Amazon Route 53  
    D. Amazon CloudFront

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>

**Explanation :** 

*   **Option A** is **INCORRECT** . AWS IAM is a global service.
*   **Option B** is **CORRECT** . EFS is a regional service.
*   **Option C** is **INCORRECT** . Route 53 is a global service.
*   **Option D** is **INCORRECT** . Amazon Cloudfront is a global service.

**References:**

[https://aws.amazon.com/efs/](https://aws.amazon.com/efs/)  
[https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services/](https://aws.amazon.com/about-aws/global-infrastructure/regional-product-services/)

## Domain : Technology

**Q25: Which of the following LightSail Wizard allows the customers to “create a copy of the LightSail instance in EC2”?**

    A. LightSail Backup  
    B. LightSail Copy  
    C. Upgrade to EC2  
    D. LightSail-EC2 snapshot

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>

**Explanation :** 

*   **Option A** is **INCORRECT** . LightSail Backup is an invalid option.
*   **Option B** is **INCORRECT** . LightSail Copy is an invalid option.
*   **Option C** is **CORRECT** . “Upgrade to EC2” is the feature that allows customers to “create a copy of the LightSail instance in EC2”.  
    To get started, you need to export your Lightsail instance manual snapshot. You ’ll then use the Upgrade to EC2 wizard to create an instance in EC2.  
    Customers who are comfortable with EC2 can then use the EC2 creation wizard or API to create a new EC2 instance as they would from an existing EC2 AMI.
*   **Option D** is **INCORRECT** . A LightSail-EC2 snapshot is an invalid option.

![LightSail instance in EC2](data:image/svg+xml,%3Csvg%20xmlns='http://www.w3.org/2000/svg'%20viewBox='0%200%201146%20280'%3E%3C/svg%3E "Instance in EC2 Console")

![LightSail instance in EC2](https://www.whizlabs.com/blog/wp-content/uploads/2022/01/cc25.webp "Instance in EC2 Console")

**Reference:**

[https://lightsail.aws.amazon.com/ls/docs/en\_us/articles/amazon-lightsail-exporting-snapshots-to-amazon-ec2](https://lightsail.aws.amazon.com/ls/docs/en_us/articles/amazon-lightsail-exporting-snapshots-to-amazon-ec2)  
[https://aws.amazon.com/lightsail/features/upgrade-to-ec2/](https://aws.amazon.com/lightsail/features/upgrade-to-ec2/)

## Domain : Technology

**Q26 : Which of the following features of Amazon Connect helps better customer engagement on AWS Cloud ?**

    A. Push Notification  
    B. High Quality Audio  
    C. Mailbox Simulator  
    D. Reputation Dashboard

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>

Amazon Connect is an omnichannel cloud contact centre which can be setup easily &with low cost. It has following features which helps to provide customers a superior service ,

1.  Telephone as a service
2.  High quality Audio
3.  Omnichannel routing
4.  Web &Mobile Chat
5.  Task management
6.  Contact Centre automation
7.  Rules Engine.

**Option A is incorrect** as Push Notification is not a feature of Amazon Connect. It’s one of the features of Amazon Pinpoint.  
**Option C is incorrect** as Mailbox Simulator is not a feature of Amazon Connect. It’s one of the features of Amazon SES.  
**Option D is incorrect** as Reputation Dashboard is not a feature of Amazon Connect. It’s one of the features of Amazon SES.

For more information on Amazon Connect, refer to the following URL: [https://aws.amazon.com/connect/features/](https://aws.amazon.com/connect/features/)

## Domain : Technology

**Q27: A large IT company is looking to enable its large user base to remotely access Linux desktops from any location. Which service can be used for this purpose ?**

    A. Amazon Cognito  
    B. Amazon AppStream 2.0  
    C. Amazon WorkSpaces  
    D. Amazon WorkLink

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>

Amazon WorkSpaces provides a secure managed service for virtual desktops for remote users. It supports both Windows &Linux based virtual desktops for a large number of users.

**Option A is incorrect** as Amazon Cognito can be used to control access to AWS resources from an application.  
**Option B is incorrect** as Amazon AppStream 2.0 can be used to provide access to applications or a non-persistent desktop from any location.  
**Option D is incorrect** as Amazon WorkLink can be used by internal employees to securely access internal websites &applications using mobile phones.

For more information on Amazon WorkSpaces, refer to the following URL: [https://aws.amazon.com/workspaces/features/](https://aws.amazon.com/workspaces/features/?nc=sn&loc=2)

## Domain : Cloud Concepts

**Q28 : Users in the Developer Team need to deploy a multi-tier web application. Which service can be used to create a customized portfolio that will help users for quick deployment?**

    A. AWS Config  
    B. AWS Code Deploy  
    C. AWS Service Catalog  
    D. AWS Cloud Formation

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>

AWS Service Catalog can be used to create &deploy portfolio of products within AWS infrastructure. This helps to create consistent resources within AWS infrastructure with quick deployment. These catalogues can be used for deployment of single resource or a multi-tier web application consisting of web, application, &database layer resources.

**Option A is incorrect** as AWS config is used for evaluating configuration on the resources deployed in AWS cloud. It will not help for creating portfolios of resources for quick deployment.  
**Option B is incorrect** as AWS CodeDeploy is a managed service for automating software deployment on AWS resources &on-premise systems. It is not suitable for creating portfolios of resources for quick deployment.  
**Option D is incorrect** as AWS CloudFormation is a service for provisioning AWS resources using templates.

For more information on AWS Service Catalog, refer to the following URL: [https://aws.amazon.com/servicecatalog/features/](https://aws.amazon.com/servicecatalog/features/)

## Domain : Billing and Pricing

**Q29 : A large Oil &gas company is planning to deploy a high-volume application on multiple Amazon EC2 instances.  Which of the following can help to reduce operational expenses?**

    A. Deploy Amazon EC2 instance with Auto-scaling  
    B. Deploy Amazon EC2 instance in multiple AZ’s  
    C. Deploy Amazon EC2 instance with Amazon instance store-backed AMI  
    D. Deploy Amazon EC2 instance with Cluster placement group

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>

Using Amazon EC2 Auto-Scaling helps to match the workload on the application with the optimum number of the Amazon EC2 instance. Due to this, during low load on application, Amazon EC2 instances are terminated which reduces operational cost.

**Option B is incorrect** as deploying an Amazon EC2 instance in a multiple AZ might enhance application availability but will not reduce operational expenses.  
**Option C is incorrect** as deploying an Amazon EC2 instance with Amazon instance store-backed AMI incur charges for Amazon EC2 instance usage &storing AMI in Amazon S3. There will be no impact on operational expense using this AMI type.  
**Option D is incorrect** as deploying an Amazon EC2 instance in a cluster placement group will help to have low latency between instances but will not reduce operational expenses.

For more information on reducing cost using AWS cloud , refer to the following URL: [https://aws.amazon.com/economics/](https://aws.amazon.com/economics/)

## Domain : Cloud Concepts

**Q30 : Which of the following activities are within the scope of AWS Support?**

    A. Troubleshooting API issues  
    B. Code Development  
    C. Debugging custom software  
    D. Third-party application configuration on AWS resources  
    E. Database query tuning

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A AND D
</details>

As a part of AWS Support following activities are performed,

1.  Queries regarding all AWS Services &features.
2.  Best Practices to integrate, deploy &manage applications in the AWS cloud.
3.  Troubleshooting API &SDK issues.
4.  Troubleshooting operational issues.
5.  Issues related to any AWS Tools.
6.  Problems detected by EC2 health checks
7.  Third-Party application configuration on AWS resources &products.

AWS Support does not include:

*   Code development
*   Debugging custom software
*   Performing system administration tasks
*   Database query tuning
*   Cross-Account Support

**Option B is incorrect** as Code Development is not in the scope of AWS Support. This needs to be taken care of by the customer.  
**Option C is incorrect** as Debugging custom software is not in the scope of AWS Support. This needs to be taken care of by the customer.  
**Option E is incorrect** as Database query tuning is not in the scope of AWS Support. This needs to be taken care of by the customer.

For more information on AWS Support, refer to the following URL: [https://aws.amazon.com/premiumsupport/](https://aws.amazon.com/premiumsupport/)

### **Domain:** **Billing and Pricing**

**Q31: I have a huge amount of data (images, documents). I want to store them on AWS storage service S3 and know how S3 is priced to make informed decisions. Which of the following is accounted as a cost for S3 storage? Select TWO.** 

    A. While uploading data to an S3 bucket

    B. Lifecycle transition requests

    C. Outbound data transfer from S3 in US-West to an EC2 instance in US-West

    D. Outbound data transfer to Amazon CloudFront

    E. Outbound data transfer from S3 in US-East to an EC2 instance in US-West

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B and E
</details>

**Explanation:**

**Option A is incorrect.** Data transferred in from the internet to S3 does not incur any charges.

**Option B is CORRECT.** Lifecycle data transfers between the storage classes can be considered as GET/PUT operations from the source storage class to the target storage class which will incur cost.

**Option C is incorrect.** Outbound data transfers from S3 within the same Region (including a different AWS account) do not incur any charges.

**Option D is incorrect.** Data transferred out to Amazon CloudFront performed as a request by CloudFront to the Origin server (S3) for caching content does not incur any charges.

**Option E is CORRECT** since the Outbound data transfer is done out of the region where the S3 bucket resides.

**References:**

*   [https://aws.amazon.com/s3/pricing/](https://aws.amazon.com/s3/pricing/)
*   [http://pragmaticnotes.com/2020/04/22/s3-to-glacier-lifecycle-transition-see-if-its-worth-it/](http://pragmaticnotes.com/2020/04/22/s3-to-glacier-lifecycle-transition-see-if-its-worth-it/)

### **Domain:** **Technology**

**Q32: I am using the Amazon Simple Notification Service to send notifications to alert admins whenever the CPU utilization of an EC2 instance crosses 70%. Which of the following can be subscribers to an SNS Topic? (Select TWO)** 

    A. Email

    B. Amazon S3

    C. AWS Lambda

    D. Amazon CloudWatch

    E. Amazon DynamoDB streams

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A and C
</details>

**Explanation:**

SNS is extremely useful for the fan-out types of applications, i.e., multiple clients that push messages to an SNS topic &multiple listeners can be notified when a message arrives at the Topic.

**Option A is CORRECT.** SNS messages can be sent to registered addresses as Email (text-based or Object) who act as subscribers to the notification

**Option B is incorrect.** S3 acts as a publisher of SNS notifications. When a file is uploaded to S3, it can publish an event that can then be subscribed to &acted upon

**Option C is CORRECT.** A lambda function can subscribe to an SNS Topic and can act on any events that are published to that Topic. An S3 PUT or CREATE event for uploading documents can have a Lambda subscriber that can pull out metadata information contained within the documents &store it in a Dynamo DB database.

**Option D is incorrect.** CloudWatch will act as a publisher of events using alarms. Getting back to our scenario, we can set CloudWatch alarms on the CPU utilization metrics of the EC2 instance. The alarms can then be published to an SNS Topic for notifying users.

**Option E is incorrect.** Dynamo DB streams are events that are emitted when record modifications occur on a Dynamo DB table like INSERT, UPDATE, etc. They are extremely useful to create informative dashboards in real-time. Dynamo DB streams can trigger a lambda function that can publish a message to an SNS Topic. So we can see here that Dynamo DB stream acts as a publisher of events.

**References:**

*   [https://docs.aws.amazon.com/sns/latest/dg/welcome.html](https://docs.aws.amazon.com/sns/latest/dg/welcome.html)
*   [https://docs.aws.amazon.com/sns/latest/dg/sns-create-subscribe-endpoint-to-topic.html](https://youtu.be/PsJsP-7cydk)

### **Domain:** **Technology**

**Q 33: I require different levels of access for my application that is installed on an EC2 instance. I have configured an ENI for the same purpose. Which of the following statement is incorrect?** 

    A. I can detach the primary ENI of my EC2 instance and connect it to another instance for moving its Elastic IP

    B. I can configure a Security Group for my ENI and restrict traffic to the EC2 instance

    C. I can detach a secondary ENI containing a Private IP from one EC2 instance and attach it to another

    D. I can attach an Elastic IP to an EC2 instance in another subnet by releasing it from the ENI in the current subnet to which it is currently attached to

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>

**Explanation:**

**Option A is CORRECT.** The primary ENI of an instance cannot be detached from the instance. By default, the primary ENI is created with the creation of the EC2 instance &deleted when the instance is terminated

**Option B is incorrect** since an EC2 instance may require restricted access to certain IP addresses. This can be achieved by creating a new ENI &attaching a Public IP &Security Group restricting permissions.

**Option C is incorrect.** Secondary ENI’s that are created can be detached from the instance to which it is attached to &attached to another instance within the same subnet. The Private IP then gets allocated to the second instance to which it is attached currently

**Option D is incorrect.** ENI’s are subnet specific. So for attaching an Elastic IP to an instance in a different subnet, I need to first release it to the pool by dissociating it from an attached instance. This way, I can attach the Elastic IP to an instance in a different subnet.

**References:**

*   [https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-eni.html](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/using-eni.html)

### **Domain:** **Security**

**Q 34: To make programmatic calls to AWS, a user was provided an access key ID and secret access key. However, the user has now forgotten the shared credentials and cannot make the required programmatic calls.** 

How can an access key ID and secret access key be provided to the user?

    A. Use the “Forgot Password” Option

    B. Use “Create New Access Key” by logging in to AWS Management Console as the root user

    C. Credentials cannot be generated

    D. Raise a ticket with AWS Support

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>

**Explanation:**

**Option A** **is INCORRECT** . This is an invalid option.

**Option B** **is CORRECT** .

**Option C is** **INCORRECT** . This is an incorrect option. We can create a new access key by logging in to Management Console as a root user.

**Option D is INCORRECT** . This is an incorrect option. We can create a new access key by logging in to Management Console as a root user.

**Reference:**[](https://docs.aws.amazon.com/general/latest/gr/aws-sec-cred-types.html)

[https://docs.aws.amazon.com/general/latest/gr/aws-sec-cred-types.html](https://docs.aws.amazon.com/general/latest/gr/aws-sec-cred-types.html)

### **Domain:** **Security**

**Q 34: Which of the following statements accurately describe a function of AWS Secrets Manager? \[Select Two\]** 

    A. Encrypts authentication information in code, ensuring that it is unreadable, that is, not in plain-text.

    B. Replaces the need to hardcode authentication credentials in code.

    C. Makes it possible to include an API call in code that retrieves authentication information from a central repository.

    D. Automatically rotates and updates the code in the application build, ensuring that repositories are kept up to date.

    E. Facilitates the embedding of authentication information in code during runtime.

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B and C
</details>

**Explanation:**

AWS Secrets Manager allows users to replace authentication information in code with an API call to Secrets Manager. This API call then retrieves the secret programmatically. This safeguards the secret from being compromised since the secret is removed from the code. AWS Secrets Manager automatically rotates the secret in accordance with specified schedules which allows the implementation of more secure short-term secrets. These, in turn, reduce the risk of authentication information in code being compromised.

**Option A is INCORRECT** because AWS Secrets Manager does not encrypt authentication information whilst it is in the code.

**Option D is INCORRECT** because AWS Secrets Manager does not automatically rotate or update the application code. Rather, it automatically rotates the secret in accordance with specified schedules.

**Option E is INCORRECT** because AWS Secrets Manager does not facilitate embedding authentication information in code during runtime. Developers do not need to hard-code authentication information in code.

**Reference:**

[https://docs.aws.amazon.com/secretsmanager/latest/userguide/intro.html](https://docs.aws.amazon.com/secretsmanager/latest/userguide/intro.html)

### **Domain: Cloud Technology and Services**

**Q35. Which of the following statements accurately describes AWS IQ?**

    A. AWS IQ is an artificial intelligence service that predicts cloud infrastructure costs.

    B. AWS IQ is a service that offers free cloud computing resources to AWS customers.

    C. AWS IQ is a platform that connects AWS customers with certified freelancers, experts, and consulting firms for various AWS-related tasks.

    D. AWS IQ is a hardware appliance for secure data storage in AWS data centers.

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>

**Explanation:** AWS IQ is a platform that connects AWS customers with certified freelancers, experts, and consulting firms for various AWS-related tasks. This platform helps customers find and engage experts to assist with their specific AWS projects and tasks, making it a valuable resource for AWS customers looking for professional assistance.

**Option A is incorrect** because AWS IQ is not an artificial intelligence service for predicting cloud infrastructure costs. It is a platform for connecting customers with experts.

**Option B is incorrect** because AWS IQ does not offer free cloud computing resources. It is a marketplace for connecting customers with experts and involves payment for the services provided.

**Option D is incorrect** because AWS IQ is not a hardware appliance for data storage but rather a platform for connecting customers with AWS experts.

**Reference:** [https://docs.aws.amazon.com/aws-iq/latest/user-guide/what-is-aws-iq.html](https://docs.aws.amazon.com/aws-iq/latest/user-guide/what-is-aws-iq.html)

### **Domain: Cloud Technology and Services**

**Q36. You are developing a web application that requires real-time collaboration features and seamless integration with AWS services for the backend. Which AWS service should you consider for simplifying the development and implementation of these features?**

    A. AWS AppSync

    B. AWS Amplify

    C. Amazon RDS

    D. AWS Device Farm

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>

**Explanation:** AWS Amplify is a framework that simplifies the development of web and mobile applications by providing tools and services to streamline the process. It enables seamless integration with various AWS services for the backend, making it a suitable choice for simplifying the development and implementation of real-time collaboration features in web applications.

**Option A is incorrect** because AWS AppSync, while capable of handling real-time data synchronization, is primarily designed for applications using GraphQL APIs, and it may not be the most straightforward choice for the above scenario.

**Option C is incorrect** because Amazon RDS is a managed database service used to simplify the process of setting up, operating, and scaling relational databases in the cloud.

**Option D is incorrect** because AWS Device Farm is a testing service for mobile and web applications on real devices.

**Reference:** [https://docs.aws.amazon.com/amplify/latest/userguide/welcome.html](https://docs.aws.amazon.com/amplify/latest/userguide/welcome.html)

### **Domain: Cloud Technology and Services**

**Q37: You are working on a software development project that involves managing and distributing software packages and dependencies across your development team. You need a secure and scalable solution for storing and sharing these artifacts. Which AWS service should you consider for this purpose?**

    A. AWS CodeCommit

    B. AWS CodeStar

    C. AWS CodeBuild

    D. AWS CodeArtifact

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – D
</details>

**Explanation:** AWS CodeArtifact is designed for secure and scalable artifact management, making it an excellent choice for storing and sharing software packages and dependencies.

**Option A is incorrect** because AWS CodeCommit is a managed source code repository service, primarily used for version control and collaboration on source code. It ’s not designed for storing and managing software artifacts and dependencies.

**Option B is incorrect** because AWS CodeStar is a developer tool that simplifies the setup and management of development projects, including integration with AWS services like CodeCommit, CodeBuild, and CodeDeploy.

**Option C is incorrect** because AWS CodeBuild is designed to compile, build, and test code in a scalable and efficient manner, helping development teams automate and streamline their build and deployment processes.

**Reference:** [https://aws.amazon.com/codeartifact/](https://aws.amazon.com/codeartifact/)

### **Domain: Cloud Technology and Services**

**Q38: You are tasked with building and deploying a machine-learning model to predict customer preferences for an e-commerce platform. Which AWS service provides end-to-end machine learning capabilities?**

    A. Amazon SageMaker

    B. Amazon Lex

    C. Amazon Polly

    D. Amazon Kendra

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>

**Explanation:** Amazon SageMaker is the correct choice for building and deploying machine learning models with end-to-end capabilities. It covers the entire machine-learning workflow, including data preprocessing, and model training.

**Option B is incorrect** because Amazon Lex is a service for building conversational interfaces using chatbots and voice-enabled applications. It is not designed for building and deploying machine learning models for predicting customer preferences.

**Option C is incorrect** because Amazon Polly is a service that converts text into lifelike speech. It is not used for machine learning model development or predictive analytics.

**Option D is incorrect** because Amazon Kendra is a service for building intelligent search capabilities into applications. While it is valuable for search and retrieval tasks, it is not designed for building machine learning models for predictive analytics.

**Reference:** [https://docs.aws.amazon.com/sagemaker/latest/dg/whatis.html](https://docs.aws.amazon.com/sagemaker/latest/dg/whatis.html)

### **Domain: Cloud Technology and Services**

**Q39: In a customer support application, there is a need for a chatbot to assist users in finding quick answers to frequently asked questions. Which AWS service is suitable for building this chatbot with natural language understanding capabilities?**

    A. Amazon Rekognition

    B. Amazon Lex

    C. Amazon Polly

    D. Amazon Kendra

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>

**Explanation:** Amazon Lex is the correct choice for developing a chatbot with natural language understanding capabilities. It enables the creation of conversational interfaces and chatbots that can comprehend and respond to user queries in natural language.

**Option A is incorrect** because Amazon Rekognition is a service for image and video analysis, primarily used for tasks like object recognition and facial analysis. It is not intended for chatbot development or natural language understanding.

**Option C is incorrect** because Amazon Polly is a service that converts text into lifelike speech but does not provide natural language understanding capabilities or chatbot development features.

**Option D is incorrect** because Amazon Kendra is an intelligent search service designed to provide highly accurate and efficient search capabilities for documents and data. It does not focus on chatbot development or natural language understanding.

**Reference:** [https://docs.aws.amazon.com/lex/latest/dg/what-is.html](https://docs.aws.amazon.com/lex/latest/dg/what-is.html)

### **Domain: Cloud Technology and Services**

**Q40: What role does Amazon AppStream play in helping organizations?**

    A. It provides cloud-based virtual machines for running containerized applications.

    B. It automates and manages AWS resource provisioning.

    C. It delivers desktop applications securely to users via streaming.

    D. It hosts websites and web applications with high availability.

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>

**Explanation:** Amazon AppStream is designed to securely stream desktop applications to users over the internet. It allows you to deliver software applications to a variety of devices, making them accessible from anywhere while maintaining data security.

**Option A is incorrect** because the description aligns more with services like Amazon EC2 or AWS Fargate, which provide virtual machines or containerized application execution, rather than AppStream ’s focus on desktop application streaming.

**Option B is incorrect** because This aligns more with services like AWS CloudFormation or AWS Elastic Beanstalk, which are used for automating and managing AWS resource provisioning but are not related to desktop application streaming.

**Option D is incorrect** because High-availability hosting of websites and web applications is typically associated with services like AWS Elastic Load Balancing, AWS Auto Scaling, and Amazon S3 static website hosting, but it is not the primary purpose of Amazon AppStream. 

**Reference:** [https://docs.aws.amazon.com/appstream2/latest/developerguide/what-is-appstream.html](https://docs.aws.amazon.com/appstream2/latest/developerguide/what-is-appstream.html)

### **Domain: Cloud Technology and Services**

**Q41: You are developing a mobile application that requires real-time data synchronization and offline access to your backend data. Which AWS service should you consider for building the GraphQL API to meet these requirements?**  

    A. AWS Amplify

    B. AWS Device Farm

    C. Amazon AppStream

    D. AWS AppSync

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – D
</details>

**Explanation:** AWS AppSync is the correct choice for building a GraphQL API that provides real-time data synchronization and offline access capabilities for mobile and web applications. It allows you to connect to various data sources and enables offline access through data caching.

**Option A is incorrect** because AWS Amplify is a development framework and library for building web and mobile applications, including features for authentication and data access. 

**Option B is incorrect** because AWS Device Farm is a testing service for mobile and web applications on real devices. It is unrelated to building GraphQL APIs or providing real-time data synchronization and offline access.

**Option C is incorrect** because AWS AppStream is a service for securely streaming desktop applications to users over the internet.

**Reference:** [https://docs.aws.amazon.com/appsync/latest/devguide/what-is-appsync.html](https://docs.aws.amazon.com/appsync/latest/devguide/what-is-appsync.html)

### **Domain: Cloud Technology and Services**

**Q42: In a software development project, a team needs a service to automate the compilation and testing of code changes in a continuous integration (CI) environment. Which AWS service is suitable for this purpose?**

    A. AWS CodeBuild

    B. AWS CodeDeploy

    C. AWS CodePipeline

    D. AWS CodeCommit

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>

**Explanation:** AWS CodeBuild is the appropriate choice for automating the compilation and testing of code changes in a CI (continuous integration) environment. It is a fully managed build service that can compile your source code, run tests, and produce build artifacts.  

**Option B is incorrect** because AWS CodeDeploy is a service used for automating software deployments to various compute targets, such as EC2 instances, and Lambda functions. It is not designed for the compilation and testing of code changes.

**Option C is incorrect** because AWS CodePipeline is a CI/CD service used for orchestrating and automating the delivery of software changes. While it can include CodeBuild as a build step, its primary focus is on the entire CI/CD pipeline, not just the build process.

**Option D is incorrect** because AWS CodeCommit is a managed source code repository service for version control and collaboration on source code. It is not a build service like CodeBuild.

**Reference:** [https://docs.aws.amazon.com/codebuild/latest/userguide/welcome.html](https://docs.aws.amazon.com/codebuild/latest/userguide/welcome.html)

### **Domain: Cloud Technology and Services**

**Q43: In a production environment, there is a requirement to automate the entire process of managing and delivering changes, including building, testing, and deploying resources. Which AWS service should be considered to create an end-to-end continuous integration and continuous deployment (CI/CD) pipeline?**

    A.AWS CodeDeploy

    B. AWS CodeBuild

    C. AWS CodePipeline

    D. AWS CodeCommit

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>

**Explanation:** AWS CodePipeline is the appropriate choice for creating a streamlined, end-to-end CI/CD pipeline. It enables you to automate the entire process of managing and delivering changes, including building, testing, and deploying resources, facilitating a seamless and efficient CI/CD workflow.

**Option A is incorrect** because AWS CodeDeploy is a service used for automating software deployments to various compute targets, such as EC2 instances, Lambda functions. It is not designed to handle the complete CI/CD pipeline like CodePipeline.

**Option B is incorrect** because AWS CodeBuild is a managed build service used for compiling source code and running tests. While it is a crucial component of the CI/CD pipeline, it does not cover the entire CI/CD workflow as CodePipeline does.

**Option D is incorrect** because AWS CodeCommit is a managed source code repository service for version control and collaboration on source code.

**Reference:** [https://docs.aws.amazon.com/codepipeline/latest/userguide/welcome.html](https://docs.aws.amazon.com/codepipeline/latest/userguide/welcome.html)

### **Domain:** Cloud**Technology and Services**

**Q44: In a remote work scenario, your organization needs to provide a virtual desktop experience for employees, allowing them to access their desktop environments securely from anywhere. Which AWS service should you consider for this purpose?**

    A) Amazon WorkSpaces

    B) Amazon WorkSpaces Web

    C) Amazon AppStream 2.0

    D) AWS Device Farm

<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>

**Explanation:** Amazon WorkSpaces is a service that provides a virtual desktop experience to employees, enabling them to access their desktop environments securely from anywhere with an internet connection. It offers a fully managed, scalable, and secure solution for remote desktop access.

**Option B is incorrect** because Amazon WorkSpaces Web is an economical, comprehensively supervised, Linux-centric solution, crafted to streamline secure web-based entry to internal websites and software-as-a-service (SaaS) applications through web browsers. It does not have the capability to provide a virtual desktop experience to users.

**Option C is incorrect** because Amazon AppStream 2.0 is a service for streaming desktop applications to users, but it is not primarily focused on providing full virtual desktop environments like Amazon WorkSpaces. It ’s more suitable for streaming specific applications rather than complete desktops.

**Option D is incorrect** because AWS Device Farm is a testing service for mobile and web applications on real devices.

**Reference:** [https://docs.aws.amazon.com/workspaces/latest/adminguide/amazon-workspaces.html](https://docs.aws.amazon.com/workspaces/latest/adminguide/amazon-workspaces.html)

### Summary:

We hope the above list of questions on AWS Cloud Practitioner exams are helpful for you. AWS CCP (Certified Cloud Practitioner) is a foundational exam in which even a beginner interested to pursue their career in AWS cloud can attempt this exam.


---



---



---



---

# Practice Exam my own that I guessed wrong

**Q1: An organization runs several Amazon EC2 instances inside an Amazon VPC using three subnets - one for Development, one for Test, and one for Production. The Security team wants to restrict communication between the EC2 instances using Security Groups. Which of the following statements is true about changing Security Groups associated with the instances in this scenario?**


    A. You can change a Security Group only if there are no instances associated with it.
    B. You can change a Security Group associated with an instance if the instance is in the hibernate state.
    C. You can change only the Default Security Group.
    D. You can change a Security Group associated with an instance if the instance is in the running state.


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – D
</details>


---

**Q2: Which key cloud concept pertains to the ability to reuse components of an application or service?**


    A. Interoperability.
    B. Portability.
    C. Modularization
    D. Reusability


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>


---

**Q3: Amazon RDS provides Multi-AZ feature for better availability of databases. Which of the following options describes Multi-AZ?
Amazon RDS bietet die Multi-AZ-IFunktionur eine bessere Verfugbarkeit von Datenbanken. Welche der folgenden Optionen beschreibt Multi-AZ?**


    A. Multi-AZ encrypts RDS instance data.
    B. Multi-AZ allows read replicas of RDS im,tances across availability zones.
    C. Multi-AZ maintains standby replica.s of RDS instances in different availability zones
    D. Multi-AZ allows peening connections between VPCs


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>


---

**Q4: How does using cloud computing help companies focus on innovation rather than infrastructure??**


    A. There are no infrastructure costs.
    B. The cloud automates all processes.
    C. Resources can be provisioned on demand
    D. The cloud provider handles routine IT tasks


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – D
</details>


---

**Q5: Which concept will articullate the specific requirements between the cloud user and provider as far as promised performance, uptime, and responsiveness for services?
Welches Konzept bring! die spezifischen Anforderungen zwischen Cloud-Benutzer und -Anbieter hinsichtlich der versprochenen Leistung, Verfugbarkeit und Reaktionsfahigkeit der Dienst zum Ausdruck?**


    A. Auditability / Überprüfbarkeit
    B. Governance / Führung
    C. Service Level Agreement (SLA)
    D. Contract / Vertag


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>


---

**Q6: What are two best practices for managing access in AWS using IAM? Was sind die zwei Best Practices fur die Zugriffsverwaltung in AWS mithilfe von IAM?**


    A. Grant least privilege
    B. Account-level policies
    C. Customer-managed policies
    D. Use service accounts


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A and D
</details>


---

**Q7: In which two locations can Amazon EC2 Auto Scaling launch resources? An welchen zwei Standorten kann Amazon EC2 Auto Scaling Ressourcen starten?**


    A. Multiple availability zones within a region
    B. Only in one single availability zone
    C. Everywhere, there are no constraints
    D. Multiple availability zones across multiple regions


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A and D
</details>


---

**Q8: You are using Amazon Simple Notification Service to send notifications to alert admins when CPU usage of an Amazon EC2 instance is more than 70%. Which two of the following can subscribe to an Amazon SNS topic ?**


    A. AWS Lambda
    B. Email
    C. Amazon CloudWatch
    D. Amazon S3


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A and B
</details>


---

**Q9: A company migrated their application servers to Amazon EC2 instances. The IT Manager wants to know about upcoming AWS scheduled maintenance activities that could impact the EC2 instances. Which AWS service provides alerts about these activities ?**


    A. AWS Personal Health Dashboard
    B. AWS Service Health Dashboard
    C. AWS Trusted Advisor
    D. AWSOrganizations


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>


---

**Q10: How does using Infrastructure as a Service (laaS) help companies' ?**


    A. laaSis fully managed by the provider
    B. Eliminates infrastructure costs
    C. Provides rapid innovation capabilities
    D. Reduces need for data center space


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – D
</details>


---

**Q11: Which universal concept of cloud computing refers to the ability of a cloud environment to continue functioning while some portions are unavailable?**


    A. Performance / Leistung
    B. Resiliency / Belastbarkeit
    C. Availability / Verfügbarkeit
    D. Scalability / Skalierbarkeit


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>


---

**Q12: Which AWS services are global in nature versus based on regions like most AWS services?**


    A. EC2
    B. IAM
    C. CloudFront
    D. S3
    E. LightSail


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B and C
</details>


---

**Q13: If you have multiple users who need the same rights within your AWS account, which would be the easiest approach to implement and maintain the consistency of them?**


    A. Assign them to the same security group
    B. Make each their own AWS account and share access to the rn.ain account.
    C. Create each user in IAM and assign the proper roles.
    D. Assign them to the same IAM group that you create.


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – D
</details>


---

**Q14: Welches AWS Tool kann durch die Suche nach ungenutzten und nicht ausgelasteten Ressourcen bei der Ermittlung potenzieller Kosteneinsparungen helfen?**


    A. AWS Trusted Advisor
    B. AWS-Budgets
    C. AWSConfig
    D. AWS Cost Explorer


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – D
</details>


---

**Q15: Which Amazon EC2 purchasing option allows you to use your existing per-socket, per-core, or per-VM software licenses like Microsoft Windows Server?**


    A. Dedicated Instance
    B. Reserved Instance
    C. On-Demand Instance
    D. Dedicated Host


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – D
</details>


---

**Q16: What AWS services and resources are contained within an Amazon Virtual Private Cloud (VPC)?**


    A. Resources across multiple AWS regions and your on-premises networks
    B. Resources across multiple Avaikability Zones in a single region
    C. Resources across multiple regions
    D. Only resources in a single Availability Zone


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>


---

**Q17: Which of the following statements best explains AWS Service Quotas?**


    A. Service Quotas places limits on AWS.Services within an account but can always,be increased for a fee specific to tllat service
    B. Service Quotas only apply to rnmpute and storage instances across AWS
    C. Service Quotas is .specific to a region and will place default limits on the number of specific types of resources you can allocate
    D. Service Quotas sets limitations on the amount of AWS services that may be allocated across AWS for a specific account


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>


---

**Q18: Which Amazon Web Services resource requires customers to be responsible for security configurations rellated to the infrastructure?**


    A. Amazon DynamoDB
    B. AWS Fargate
    C. Amazon RDS
    D. Amazoni EC2


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – D
</details>


---

**Q19: Which Amazon Web Services tool can be used to monitor, store and access log files created by EC2 instances and on-premises servers?**


    A. AWS Organization
    B. Amazon CloudFront
    C. AWS Global Accelerator
    D. Amazon CloudWatch Logs


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – D
</details>


---

**Q20: Which type of AWS Reserved Instance offers the smalller cost savings?**


    A. Standard
    B. Flexible
    C. Convertible
    D. Limited


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>


---

**Q21: Which Amazon Web Services feature allows customers to ueate a copy of their Lightsail instance in EC2?**


    A. Upgrade to EC2
    B. LightSail-EC2 snapshot
    C. LightSail Copy
    D. LightSail Backup


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>


---

**Q22: Where in the architecture should firewalling be implemented for a web hosting design using AWS?**


    A. At the perimeter
    B. Al the core
    C. Al all layers
    D. For all access layer functions


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>


---

**Q23: Which Amazon Web Services tool allows you to check Amazon EC2 instances for security vulnerabilities by analyzing them against predefined security templates?**


    A. Amazon Guard Duty
    B. AWSConfig
    C. AWS Inspector
    D. AWS Trusted Advisor


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>


---

**Q24: What benefits does a database administrator get by using Amazon Relational Database Service (RDS)?**


    A. RDS provides extremely high reliability a11d durability
    B. RDS simplifies tasks related to managing relational databases.
    C. RDS databases automatically scale based on load.
    D. RDS enables users to dynamically adjust CPU .and RAM resources.


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>


---

**Q25: Which report, offered in CSV format, can be downloaded to audit your list of users, their access permissions, and other information about logins?**


    A. Credential report
    B. User Audit
    C. User Report
    D. IAM report


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>


---

**Q26: Which characteristic of the AWS Cloud enables companies to innovate faster?**


    A. Security
    B. Agility
    C. Cost Savings
    D. High Availability


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>


---

**Q27: Which AWS database service encrypts data at rest by default?**


    A. AmazornRedshift
    B. Amazon RDS
    C. Amazorn DynamoDB
    D. Amazorn Aurora


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>


---

**Q28: At what levell are security groups applied?**


    A. VPC
    B. Account
    C. Instance
    D. Subnet


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>


---

**Q29: Which AWS database service encrypts data at rest by default?**


    A. NAT Gateway
    B. Internet Gateway
    C. Network Access Control List (NaCl)


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>


---

**Q30: Which Amazon Web Services (AWS) service is designed for time series data analytics?**


    A. Amazon Kinesis
    B. Amazon DynamoDB
    C. Amazon ElasticSearch
    D. Amazon Timestream


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – D
</details>


---

**Q31: Which cloud characteristic involves delivering the same resources to a large pool of customers?**


    A. Agility
    B. Multitenancy
    C. Scalability
    D. Elasticity


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>


---

**Q32: Which Amazon EC2 pricing model allows customers to use existing server-bound software licenses?**


    A. Spot Instances
    B. On-Demarid Instances
    C. Dedicated Hosts
    D. Reserved Instances


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>


---

**Q33: What benefit does Elasticity provide according to .Amazon Web Services (AWS)?**


    A. It allows delivery of the same resour,ces to a large pool of customers in a scalable way.
    B. It provisions new servers to meet static demand growth.
    C. It allows systems to scale up or down based on changes in demand.
    D. It minimizes storage needs by reducin,g logging and auditing activities.


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>


---

**Q34: Which Amazon Web Services service is designed for time series data and operational analytics?**


    A. Amazon ElasticSearch
    B. Amazon Kinesis
    C. Amazon DynamoDB
    D. Amazon Timestream


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – D
</details>


---

**Q35: Which Amazon Web Services service can you use to create billing alarms?**


    A. AWS Systems Manager
    B. Amazon CloudFront
    C. Amazon CloudFormation
    D. Amazon CloudWatch


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – D
</details>


---

**Q36: Which of the following are true about security groups, but not ACLs? (Choose two)?**


    A. Rules are applied to only specify things allowed.
    B. Traffic is automatically allowed outbound to respond to an allowed inbound rule.
    C. Rule are applied at the subnet level.
    D. The VPC by default will allow all traffic for both inbound and outbol.lnd routes
    E. Each subnet must have a security group applied.


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B and D
</details>


---

**Q37: Where can a user find the policies and rules about prohibited actions when using AWS infrastructure and services?**


    A. AWS Billing Console
    B. AWS Identity and Access Management (1AM)
    C. AWS Acceptable Use Policy
    D. AWS Trusted Advisor


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>


---

**Q38: Which of the following AWS services under the Free Tier would have limitations for 750 hours of usage for the month?**


    A. EC2
    B. Lambda
    C. RDS Migration 5ervice
    D. CloudWatch


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>


---

**Q39: Which type of AWS offering provides discounts specifically for compute purchases of specific time/hours quantities??**


    A. Compute Packages
    B. Savings Plans
    C. EC2 Reservations
    D. Reserved Instances


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>


---

**Q40: Which AWS tool can be best used to track your usage of Reserved Instances?**


    A. Budgets
    B. Instance Tracker
    C. Cost Categories
    D. Cost Explorer


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>


---

**Q41: Which AWS service can be used as a p1·ivate Git repository?**


    A. CodeBuild
    B. CodePipeline
    C. CodeDeploy
    D. CodeCommit


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – D
</details>


---

**Q42: Which two components can be configured through the VPC console in AWS?**


    A. Security Group
    B. KeyPair
    C. Endpoint
    D. Subnet


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A and D
</details>


---

**Q43: Which AWS service can be used to host a static website?**


    A. Amazon Managed Blockchain
    B. Amazon S3
    C. Amazon Aurora
    D. AWS Lambda


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>


---

**Q44: Select two pillars in the AWS Well-Architected Framework**


    A. Elasticity and Scalability
    B. Operational Excellence
    C. Data Consistency
    D. Performance Efficiency


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B and D
</details>


---

**Q45: Which Amazon Web Services tool can notify users if they need to increase the service limit for an EC2 instance?**


    A. Service Catalog
    B. Personal Health Dashboard
    C. Systems Manager
    D. Trusted Advisor


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – D
</details>


---

**Q46: I have a large amount of data (images, documents) that I want to store in the AWS S3 storage service. I want to understand how S3 is priced to make informed decisions. Which two of the following are accounted as costs for S3 storage?**


    A. Data transfer from one AWS region to a11other
    B. Data tra11sfer to Amazon Cloud Front
    C. Lifecycle transitions between storage classes
    D. Data transfer within the same AWS region
    E. Uploading data to an S3 bucket


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A and C
</details>


---

**Q47: Which AWS service enables hybrid clloud storage between on-premises data cente1·s and the AWS Cloud?**


    A. AWS Fargate
    B. AWS Storage Gateway
    C. AWS Snow Family
    D. Amazon S3


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>


---

**Q48: Which two of the folllowing AWS services prohibit you from performing penetration testing without prior authorization?**


    A. AWS Shield (Standard)
    B. Amazon EC2 inslances
    C. AWS Shield (Advanced)
    D. Amazon RDS


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A and D
</details>


---

**Q49: What is the range of time that Cost Explorer will display historical usage and future projections?**


    A. 12 months back, 6, months forward
    B. 12 months back, 12 months forward
    C. 6 months back, 3 months forward
    D. 6 months back, 6 months forward


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>


---

**Q50: Why does using cloud computing typically provide more agility compared to on-premises data centers?**


    A. Unlimited on-demand resources
    B. No need for IT staff
    C. Faster time to market for new resources
    D. No infrastructure maintenance


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>


---

**Q51: Why would using AWS with an application that has cyclical load demands, such as a healthcare provider during open enrollment periods, be more cost-effective in AWS than a, traditional data center?**


    A. AWS resources can be spread across multiple regions
    B. AWS is continually expanding and adding faster compute resources
    C. AWS resources can be allocated when needed
    D. You can provision enough resources year-round to handle peak loads without buying more hardware


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>


---

**Q52: Which AWS service helps identify the resources that were modified and who made the changes?**


    A. AWSConfig
    B. AWS Trusted Advisor
    C. Amazon Inspector
    D. AWS CloudTrail


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>


---

**Q53: Which AWS service provides a history of the activities in your AWS account, including actions through the AWS Console, SDKs, CLI, and other AWS services?**


    A. AWS Config
    B. AWS Infrastructure Event Management
    C. AWS CloudTrail
    D. Amazon CloudWatch


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>


---

**Q54: Which concept focuses on replicating data across AZs and regions?**


    A. Durability
    B. Elasticity
    C. Automation
    D. Decoupling


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>


---

**Q55: When using federated authentication with SAML, what are the two key components involved with the workflow? (Choose two.)**


    A. System of record
    B. Identity provider
    C. LDAP
    D. Service providerDecoupling
    E. Application


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B and D
</details>


---

**Q56: What benefits are included with an Enterprise Support plan from Amazon Web Services?**


    A. Technical Account Manager
    B. AWS Support Analysts
    C. AWS Technical Support Manager
    D. AWS Cloud Architect


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A and B
</details>


---

**Q57: Which AWS service is a content delivery network (CDN)?**


    A. Lambda
    B. Elastic Beanstalk
    C. CloudFront
    D. Lightsail


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>


---

**Q58: Which statement about AWS Certificate Manager certificates is incorrect?**


    A. They are permanent certificates
    B. You can issue unlimited certificates
    C. They are free when used with Elastic Load Balancer
    D. They automate the prooess, of getting and renewing SSL/TLS certificales


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>


---

**Q59: Which AWS service protects your external-facing web applications from bot traffic and DDoS attacks?**


    A. AWS Shield Advanced
    B. AWS WAF
    C. AWS CloudTrail
    D. AWS EMR


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>


---

**Q60: Which AWS service provides instrumentation to monitor and troubleshoot applications in the AWS Cloud?**


    A. Amazon QLDB
    B. Amazon Batch
    C. AWS X-Ray
    D. AWS HSM


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>


---

**Q61: Which AWS service provides a unified interface to view operational data across multiple AWS services and automate tasks?**


    A. AWS Organizations
    B. AWS Trusted Advisor
    C. AWS Systems Manager
    D. AWS Service Catalog


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – C
</details>


---

**Q62: Which of the following is the correct URL for accessing the AWS Management Console?**


    A. https://console.aws.arnaz.on.com
    B. https://mgmt.aws.com
    C. https://console.aws.com
    D. https://console.amazon.com


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – A
</details>


---

**Q63: Which AWS service provides access to security and compliance reports?**


    A. AWS Systems Manager
    B. AWS Shield
    C. AWS Macie
    D. AWS Artifacts


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – D
</details>


---

**Q64: As part of your company's DR strategy, you have decided to use S3 Glacier to archive data files. When needed, you have a mandate that data must be accessible in less than six hours' tirne. Which S3 retrieval option will you need to utilize to meet this requirement while also realizing the most cost savings?**


    A. Basic
    B. Standard
    C. Bulk
    D. Expedited


<details markdown=1><summary markdown='span'>Answer</summary>
    Answer – B
</details>
