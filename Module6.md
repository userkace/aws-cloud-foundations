# AWS Cloud Foundation Module 6 Answers

### Q1. Why is AWS more economical than traditional data centers for applications with varying compute workloads? (Select the best answer).
**Options:** <br/>
A. Amazon EC2 Costs are billed on a monthly basis. <br/>
B. Customers retain full administrative access to their Amazon EC2 instances. <br/>
C. Customers can permanently run enough instances to handle peak workloads. <br/>
D. Amazon EC2 instances can be launched on-demand when needed.

**Answer:**
- [D] Amazon EC2 instances can be launched on-demand when needed.

---

### Q2. If your project requires monthly reports that iterate through very large amounts of data, which Amazon Elastic Compute Cloud EC2 purchasing option should you consider? (Select the best answer).
**Options:** <br/>
A. Spot Instances. <br/>
B. Scheduled Reserved Instances. <br/>
C. Dedicated Hosts. <br/>
D. On-Demand Instances.

**Answer:**
- [B] Scheduled Reserved Instances.

---

### Q3. What is included in an Amazon Machine Image (AMI)? Select the best answer.
**Options:** <br/>
A. A template for the root volume for the instance. <br/>
B. Launch permissions that control which AWS accounts can use the AMI to launch instances. <br/>
C. A block device mapping that specifies the volumes to attach to the instance when it's launched. <br/>
D. All of the above.

**Answer:**
- [D] All of the above.

---

### Q4. Which Amazon Elastic Compute Cloud EC2 feature ensures your instances will not share a physical host with instances from any other AWS customer? (Select the best answer).
**Options:**
A. Amazon VPC. <br/>
B. Placement Groups. <br/>
C. Dedicated Instances. <br/>
D. Reserved Instances.

**Answer:**
- [C] Dedicated Instances.

---

### Q5. Which of the following services is a serverless compute service in AWS? (Select the best answer).
**Options:** <br/>
A. AWS Config. <br/>
B. AWS Lambda. <br/>
C. AWS OpsWork. <br/>
D. Amazon EC2.

**Answer:**
- [B] AWS Lambda.

---

### Q6. What is the service provided by AWS that enables developers to easily deploy and manage applications in the cloud? (Select the best answer).
**Options:** <br/>
A. Amazon Elastic Container Service. <br/>
B. AWS Elastic Beanstalk. <br/>
C. AWS OpsWork. <br/>
D. AWS CloudFormation.

**Answer:**
- [B] AWS Elastic Beanstalk.

*Elastic Beanstalk is an AWS compute service option. It is a Platform as a Service (or PaaS) that facilitates quick deployment, scaling, and managing of your web applications and services.*

---

### Q7. Your web application needs four instances to support steady traffic all of the time. On the last day of the month, the traffic triples. What is the most cost-effective way to handle this pattern? (Select the best answer).
**Options:** <br/>
A. Run 12 reserved instances all of the time. <br/>
B. Run four On-demand Instances constantly, then add eight more On-Demand on the last day of each month. <br/>
C. Run four Reserved Instances constantly, then add eight On-Demand Instances on the last day of each month. <br/>
D. Run four On-Demand Instances constantly, then add eight Reserved Instances on the last day of each month.

**Answer:**
- Run four Reserved Instances constantly, then add eight On-Demand Instances on the last day of each month.

*Reserved Instances provide cost savings when you can commit to running instances full-time, such as to handle the base traffic. On-Demand Instances provide the flexibility to handle traffic spikes.*

---

### Q8. True or false? Containers contain an entire operating system.
**Options:**
- True.
- False.

**Answer:**
- False.

*Containers are smaller than virtual machines, and do not contain an entire operating system.*

---

### Q9. Which Amazon EC2 option is best for long-term workload with predictable usage patterns? (Select the best answer).
**Options:** <br/>
A. Spot Instances. <br/>
B. On-Demand Instances. <br/>
C. Reserved Instances.

**Answer:**
- [C] Reserved Instances.

---

### Q10. Which of the following must be specified when launching a new Amazon Elastic Cloud Compute EC2 Windows instance? (Choose two).
**Options:** <br/>
A. Amazon EC2 instance type. <br/>
B. Amazon Machine Image (AMI). <br/>
C. The Amazon EC2 Instance ID. <br/>
D. Password for the administrator account.

**Answer:**
- [A] Amazon EC2 instance type.
- [B] Amazon Machine Image (AMI).