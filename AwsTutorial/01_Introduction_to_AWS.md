# Introduction to AWS

- AWS stands for Amazon Web Services which is a cloud provider. It actually provides us the severs and sevices that you can use on demand and scale easily.

- AWS provides many sevices such as AWS Ec2, S3, EBS, RDS, DynamoDB, VPC, EFS and many more. Through these services it actually revolutionized the IT industry. It hosts biggest websites in the world such as Amazon and Netfilx.

## History of AWS

- AWS was actually launched in 2002 which is initially used to maintain the Amazon infrastructure only. Until 2003 Aws core strength is used to maintain the amazon infrastructure only. As time goes on they got an idea to provide the IT services to the market and with this idea they launched the AWS publicly with only one service called SQS in 2004.

- Later in 2006, they relaunched the AWS publicly by adding two more services such as S3 and EC2. Until 2007 they are providing IT services only in United States. But in early 2007 they launched AWS in Europe also.

- As years going on, they are adding more and more services to it and now become a leading cloud provider in the market by hosting many powerful applications such as Netflix, DropBox, Airbnb and even NASA also.

- AWS enables us to build sophisticated and scalable applications and it is applicate for diverse set of industires. It can be used for Enterprise IT, Backup & Storage, Big Data Applications, Website Hosting , even used to run entire gaming services (or applications) and social apps.

## AWS Global Infrastructure

- AWS is Global which means its services are available all over the world in the form of Regions. An <b>AWS Region</b> is a seperate geographic location in the world where AWS has a cluster of data centers which actually provides many of its services. Most of the AWS services are region scoped.

- So before choosing a region to host our application, we have to keep the following things in our mind. Those are :

  **Compliance with data governanace and legal requirements** : Most of the governaments wants to keep thier users data in their country itself and they don't want to store thier country peoples data outside of thier country. In these scenarios, developers has to choose a region in thier country itself to host their application.

  **Proximity to customers** : Before choosing a region, application developers has to know who and where the end users will leave. Because if you choose the region close to your end users then it would decrease the latency.

  **Available Services in a Region** : As we know most of the AWS services are region specific, so we have to choose a region where all the services required for our applications are available.

  **Pricing** : Pricing varies from region to region. So we have to choose a region where prices of the services are little bit low.

- Each region is divided into one or more <b>Availability Zones (AZ)</b>. An <b>Availability Zone</b> is one or more discrete data centers with redundant power, networking and connectivity. Each region has minimum 3 availability zones and maximum 6 availability zones. Each AZ are named with code such as ap-southeast-2a, ap-souteast-2b etc. These Availabilty zones are seperate from each other, so that they are isolted from disasters. They are connected with high bandwidth and ultra low latency.

- Amazon has 400+ <b>points of presence</b> (400+ edge locations and 10+ regional caches) in 90+ cites across 40+ countries. An <b>Edge location</b> is a smaller, specialized AWS data center used to deliver content and services to your users with the lowest possible latency. While Region is where we run our main infrastructure (such as databases and servers), an Edge location is the local point of presence that brings specific services closer to where you live. It is mainly used for caching and routing the content.

- We can think Region as massive central warehouse where everything gets manufactured, and the edge location is the local convinience shop on our street corner that stocks most popular items for quick pickup.