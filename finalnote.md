# Final
# Ch 1
  IT is crucial for solving business problems and maintaining daily tasks in the modern business environment.
  IT addresses issues like data overload, mobile and wireless usage, cloud computing, video hosting, AI, machine learning, and cybersecurity.
  Proficiency in IT is essential for effective navigation of computer systems and leveraging the benefits of cloud computing.
  "IT can provide the edge a company needs to outsmart, outpace, and out-deliver competitors" – Emphasizes how IT can drive business competitiveness through innovation and efficiency.
  "In order to understand how broad information technology is, you should first understand some of the varying roles. Each role has a specialized focus such as analysts, scientists, architects, programmers, and administrators" – Highlights the diverse roles and specializations within the field of information technology.
  The importance of information technology in addressing various challenges in modern business.
  The central role of information technology in improving and updating systems through close collaboration with other fields.
# ch 2
  Cloud computing concept originates from John McCarthy in 1961.
  Emerged in the 1990s with internet-based services like search engines and social media.
  Offers ubiquitous, on-demand access to configurable computing resources.
  Motivates organizations to adopt cloud technology.
  Capacity planning for IT resource fulfillment.
  Cost reduction and aligning IT costs with business performance.
  Organizational agility for adapting to changing market demands.
  Cloud is a non-physical IT environment with scalable resources.
  IT resources can be physical or virtual.
  On-Premise vs. Cloud deployment options.
  Horizontal and vertical scaling.
  Cloud service and cloud service consumer.
  Reduced investments and proportional costs with scalability.
  Increased security vulnerabilities in cloud.
  User-centric, task-centric, accessible, powerful, intelligent, and programmable features.
# ch 5
  Cloud Computing is not a physical workstation; it's a virtual infrastructure.
  AWS Regions allow users to choose a nearby location for hosting.
  Best practices for choosing AWS Regions include proximity, services, cost, SLA, and compliance considerations.
  AWS Availability Zones offer high availability and flexibility with 76 zones per region.
  Endpoints are specific URLs that minimize latency and act as entry points for web services.
  Availability Zones provide high availability, efficiency, fault tolerance, scalability, and data accessibility.
  When selecting a region, consider supported services, cost, latency, security, and service level agreements.
  Points of Presence ensure efficient global content delivery in AWS infrastructure.
  Local Zones bring AWS services closer to specific locations, benefiting from high-bandwidth and secure connectivity.
  It's important to remember the hierarchy: Edge Locations > Availability Zones > Regions.
# ch 6
  Cybersecurity is vital for safeguarding networks, data, and online activities to ensure confidentiality, integrity, and availability.
  Poor cybersecurity exposes various risks, including malware and unauthorized credit card use, mitigated by precautionary measures.
  AWS security responsibility involves AWS managing physical security, while customers oversee OS, applications, and access.
  AWS's "Security of the Cloud" encompasses safeguarding infrastructure like data centers and network components.
  AWS's "Security in the Cloud" requires customers to secure data and applications, the extent varying based on the AWS service.
  AWS Identity and Access Management (IAM) securely controls user access to AWS resources, promoting the avoidance of root user access.
  IAM authorization grants specific permissions globally through JSON policies, following the least privilege principle.
  IAM offers shared access, granular permissions, MFA, PCI DSS compliance, and integration with AWS services.
  IAM components, including IAM Users, Groups, Policies, and Roles, serve distinct roles in managing access to AWS resources.
  Data security in AWS involves encryption for data at rest and in transit, secure S3 bucket configurations following the principle of least privilege, and DevSecOps for proactive risk management in development processes.
# ch 7
  Cybersecurity is essential for protecting networks, data, and online activities with a focus on confidentiality, integrity, and availability.
  Poor cybersecurity leads to risks like malware and unauthorized credit card usage, which can be minimized through precautionary measures.
  AWS's security responsibility includes managing physical security, while customers are responsible for the OS, applications, and access.
  "Security of the Cloud" in AWS involves safeguarding infrastructure, including data centers and network components.
  "Security in the Cloud" in AWS requires customers to secure data and applications, with the level of responsibility varying based on the AWS service.
  AWS Identity and Access Management (IAM) is crucial for securely controlling user access to AWS resources and discouraging root user access.
  IAM authorization uses JSON policies to grant specific permissions globally, following the least privilege principle.
  IAM offers shared access, granular permissions, multi-factor authentication (MFA), PCI DSS compliance, and integration with AWS services.
  IAM components, such as IAM Users, Groups, Policies, and Roles, play distinct roles in managing access to AWS resources.
  Data security in AWS includes encryption for data at rest and in transit, secure S3 bucket configurations (least privilege principle), and implementing DevSecOps for proactive risk management in development processes
# ch 8
  An operating system manages computer resources and includes Windows, macOS, and Linux.
  AWS offers compute services like Virtual Machines, Containers, Serverless, and PaaS.
  To select compute resources, consider instances, containers, functions, and use metrics.
  Virtual machines are software-based computers within a host OS, and hypervisors enable them.
  Amazon EC2 rents virtual computers and offers various instance types and AMIs.
  EC2 pricing includes On-Demand, Savings Plans, Reserved Instances, Spot Instances, and Dedicated Hosts.
  Cost optimization involves the four pillars: Right Size, Increase Elasticity, Leverage Pricing Model, and Optimize Storage.
  Containers package applications and dependencies, with Docker containers being portable.
  Kubernetes simplifies containerized application management with automation and scalability.
  AWS Container Services include ECS, EKS, ECR, AWS Lambda (for serverless), and PaaS like AWS Elastic Beanstalk for simplified application management.
# ch 9 
  Operating systems like Windows, macOS, and Linux manage computer resources.
  AWS offers a range of compute services, including Virtual Machines, Containers, Serverless, and PaaS.
  When selecting compute resources, consider instances, containers, functions, and monitor relevant metrics.
  Virtual machines are software-based computers within a host OS, enabled by hypervisors.
  Amazon EC2 provides virtual computer rentals with various instance types and Amazon Machine Images (AMIs).
  EC2 pricing options include On-Demand, Savings Plans, Reserved Instances, Spot Instances, and Dedicated Hosts.
  Cost optimization focuses on four pillars: Right Size, Increase Elasticity, Leverage Pricing Model, and Optimize Storage.
  Containers package applications and their dependencies, with Docker containers offering portability.
  Kubernetes streamlines containerized application management through automation and scalability.
# ch 11
Reliability: In the AWS Well-Architected Framework, planning for failure means designing for reliability and availability.
What is Reliability : Reliability assesses a system's consistent performance, considering hardware, software, and the likelihood of failures, with metrics like MTBF, MTTF, and MTTR.
Availability: Availability in computing refers to the percentage of time a service is accessible for use, typically measured as "number of 9's" (e.g., "five nines" means 99.999% availability), with factors like fault tolerance, scalability, and recoverability influencing it.
High Availability: High availability (HA) ensures consistent, uninterrupted system operation by minimizing downtime and human intervention, functioning as a failure response mechanism in infrastructure, and allowing systems to automatically recover from failures.
AWS Well-Architected Tool: The AWS Well-Architected Tool is a free resource in the AWS Management Console that evaluates your workloads against AWS best practices, offering recommendations to enhance reliability, security, efficiency, and cost-effectiveness throughout the product lifecycle.
AWS Trusted Advisor: AWS Trusted Advisor is an online tool that offers real-time guidance for optimizing AWS resources in terms of cost, performance, security, fault tolerance, and service limits, helping users adhere to best practices and improve their AWS infrastructure.
# ch 12
  # Chapter 12; Notes 10: Automatic Scaling & Monitoring
## 12.01 - 12.07
  What is Load Balancing: Load balancing is the distribution of computational workloads among multiple computers to improve efficiency, enhance performance, and reduce latency, commonly used for internet servers.
  How does load balancing work: Load balancing is the distribution of incoming requests to servers, managed by a tool called a load balancer, which can be either hardware or software-based, and it uses algorithms to decide which server should handle each request.
  Static load balancing algorithms: Static load balancing distributes workloads based on a predetermined plan, ignoring the system's current performance, similar to a grocery store employee assigning customers to checkout lines without considering their speed, potentially leading to uneven server workloads and inefficiencies.
  Dynamic load balancing algorithms: Dynamic load balancing optimizes server performance by distributing traffic based on factors like server health and workload, analogous to a grocery store employee assigning customers to checkout lines for efficiency, with different load balancing algorithms available.
  Introduction to IT Monitoring: Monitoring IT infrastructure is vital because various complex forms of modern enterprise infrastructure exist, and any downtime or performance issues can lead to substantial revenue losses.
  What is IT monitoring: IT monitoring assesses the real-time performance of IT infrastructure to detect issues, support resource allocation, enhance security, and analyze usage patterns.
  What is Auto Scaling: Auto scaling is a cloud computing technique that automatically adjusts the number of active servers in a server farm or pool based on user needs and load balancing capacity.
  What is Auto Scaling in Cloud Computing: Autoscaling in cloud computing automatically adjusts server capacities or virtual machine instances based on defined conditions like traffic levels, offering cost-effective and reliable performance, while also eliminating the need for manual resource management in response to demand fluctuations.
  the Difference Between Auto Scaling and Load Balancing: Elastic load balancing and application autoscaling are related concepts that both optimize server management and traffic distribution, often used together, but they are distinct; elastic load balancing focuses on distributing traffic and ensuring healthy instances, while application autoscaling adjusts instance numbers based on predefined criteria to meet demand efficiently.
  Elastic Load Balancing: Elastic Load Balancing is a service that distributes incoming traffic across various targets while monitoring their health and automatically adjusting capacity to handle changes in traffic.
  Amazon CloudWatch: Amazon CloudWatch provides real-time monitoring for AWS resources and applications, allowing you to collect and track measurable metrics.
  
