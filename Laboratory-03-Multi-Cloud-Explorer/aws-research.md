# Amazon Web Services (AWS) — Research Notes

## Brief Overview
Amazon Web Services (AWS) is the cloud computing platform launched by Amazon in 2006. It is widely regarded as the largest and most mature public cloud provider, offering over 200 fully featured services from data centers globally, ranging from compute and storage to machine learning and IoT.

## Global Infrastructure
AWS organizes its infrastructure into **Regions** (geographic areas, 30+ worldwide) and **Availability Zones** (isolated data centers within a region, usually 3+ per region). It also has **Edge Locations** for content delivery (CloudFront) to reduce latency for end users.

## Cloud Management Console
The **AWS Management Console** is a web-based interface for provisioning, monitoring, and managing AWS resources. It also offers the AWS CLI and SDKs for programmatic access, and AWS CloudShell for browser-based command-line access.

## Four (4) Core Services
1. **Amazon EC2 (Elastic Compute Cloud)** – resizable virtual servers for running applications.
2. **Amazon S3 (Simple Storage Service)** – scalable object storage for files, backups, and static content.
3. **Amazon RDS (Relational Database Service)** – managed relational databases (MySQL, PostgreSQL, SQL Server, etc.).
4. **AWS IAM (Identity and Access Management)** – controls authentication and authorization to AWS resources.

## Three (3) Advantages
1. Largest service catalog and most mature ecosystem, with the biggest partner/marketplace network.
2. Strong global infrastructure footprint, giving low-latency options in more regions than most competitors.
3. Deep enterprise adoption means abundant documentation, community support, and third-party tooling.

## Typical Enterprise Use Cases
- Hosting scalable web and mobile applications with unpredictable traffic (auto-scaling EC2/Lambda).
- Big data analytics and data lakes (S3 + Athena + Redshift).
- Startups needing pay-as-you-go infrastructure with room to scale rapidly.

> <img width="1906" height="926" alt="image" src="https://github.com/user-attachments/assets/4d79dd30-c11f-4cd6-b692-fb838ff9a67f" />

