
### Shell - Real interview questions faced during interviews ###
1.	What is CRONTAB?
2.	How would you know the disk usage using the shell script commands?
3.	Give the purpose of the shebang line?
4.	Tell us about the ‘$#’ use in shell scripting?
5.	Write a script to check vowels in a string
6.	Differentiate between $@ and $*?
7.	How can you determine if a linux server is virtualized or bare-metal?
8.	Explain special variables in Shell

### Linux Interview Questions  ###
1. What is the difference between a process and a thread in Linux?
2. What is the difference between a hard link and a soft link in Linux?
3. How can you check the memory usage of a Linux system?
4. How do you find the IP address of a Linux system?
5.  What is the purpose of the "chmod" command in Linux?
6. What is the purpose of the "grep" command?
7. How do you change the password for a user in Linux?
8. What is the purpose of the "cron" daemon in Linux?
9. How do you schedule a cron job in Linux?
10. Diskspace full issue?
11. Running out of memory?
12. How do you troubleshoot high CPU usage on a Linux server?
13. Describe the boot process of a Linux system?
14. You need to transfer a large file securely between two Linux servers. What tools or protocols would you use, and why?
15. A user accidentally deleted an important file, and you need to recover it from the backup. Explain the steps you would take to restore the file.
16. A user reports that they are unable to connect to a remote Linux server using SSH. How would you troubleshoot and resolve this connectivity issue?
17. You need to find all files larger than 100MB in the /home directory and its subdirectories. How would you accomplish this task?
18. What is inode?
19. What is booting process in Linux?
20. How do you clear the server if you continuously get Space not available
21. What types of OS patching’s you have done
22. What are the Linux commands you use daily?
23. Linux file permissions types

### Ansible Interview Questions ###
1.	what are tags in ansible?
2.	what is ansible playbook?
3.	What are handlers in Ansible playbook?
4.	What are various modules you have used in Ansible?
5.	What is Ansible ad hoc command?
6.	How has Ansible helped your organization?
7.	What are register targets in Ansible?
8.	How to add multiple tasks in ansible playbook
9.	Ansible host ping is success but I am not able to execute playbooks why?
10.	What is Ansible Tower and what are its features
11.	How do you keep data secret in a playbook?

### Git Interview Questions ###
1.	Git conflict?
2.	Branching strategy?
3.	how to resolve merge conflicts?
4.	Merge vs rebase
5.	interactive rebase git
6.	squash in git
7.	fast-forward merge in Git?
8.	What is cherry pic
9.	what is gitignore?
10.	What is Git and why is it used?
11.	What is the difference between git fetch and git pull?
12.	How can you revert a commit that has already been pushed to a remote repository?
13.	How do you initialize a new Git repository?
14.	What is the purpose of the Git staging area?
15.	How do you commit changes in Git?

### Monitoring Interview Questions ###
1.	What are the different dashboards created in Grafana?
2.	What is the prometheus configuration file
3.	What is Prometheus, and how does it contribute to Kubernetes monitoring?
4.	Explain the architecture of Prometheus. What are the main components, and how do they interact?
5.	What is a Prometheus Exporter, and how does it enable the monitoring of third-party applications and services in Kubernetes?
6.	How do you create custom Prometheus alerts and alerting rules for Kubernetes monitoring? Provide an example alert rule and its configuration.
7.	What is Grafana, and how does it complement Prometheus for Kubernetes monitoring?
8.	Explain the concept of Grafana data sources and how they enable integration with various data providers, including Prometheus.

### AWS Interview Questions ###
1.	what is the diff b\w ALB and NLB
2.	How do you determine if a subnet is private or public?
3.	What is diff b\w EBS and EFS
4.	Can you attach a single EBS volume to the multiple EC2 instances at the same time?
5.	what is VPC endpoint
6.	What are the similarities between SSL and TLS?
7.	ami and snapshot difference
8.	What is s3?
9.	autoscaling in aws?
10.	How many many VPC can we create in one Region?
11.	How to access the S3 bucket privately
12.	What is VPC and its components?
13.	What is difference between NACL and Security groups?
14.	difference between Network and application load balancer
15.	Route 53 types and what is route 53
16.	What is a route table in Amazon VPC?
17.	Explain S3 lifecycle
18.	Can you increase the size of the root volume without shutting down the instance?
19.	You have 500GB data how you will store in S3 and what steps you will take to make sure you have time, cost and security implemented
20.	What is the network flow when you hit the www.google.com
21.	How you will get the list of Ips of EC2 from various regions that are exposed to internet
22.	What is DNS caching
23.	What is the NAT gateway and its rules
24.	Which AWS services have you worked on
25.	What is the difference between users and roles?
26.	How do you define policies in IAM?
27.	What is VPC? What is VPC peering?
28.	What is the storage facility present in EC2 instance?
29.	How to attach NAT, internet gateways
30.	Diff b/w on demand instance, spot instances, reserved instance

### Docker Interview Questions ###
1.	what is the difference between Virtualization and Containerization?
2.	How to do the port mapping to the container?
3.	How can you get the shell access of a running container?
4.	What is the difference between RUN and CMD?
5.	What is Dockerfile?
6.	How do you build Docker images?
7.	What is the difference between ADD vs COPY?
8.	What is the difference between CMD and ENTRYPOINT?
9.	What is the Difference between ARG and ENV?
10.	What are Docker Volumes?
11.	Tell is the best practices you implemented while creating docker images?
12.	What are multi stage builds?
13.	What is a Dockerfile?
14.	What is multi-stage in Docker?
15.	What is a Docker volume and how do you use it?
16.	How can we pass an argument to Dockerfile?
17.	Dockerfile runs as which user?
18.	How do you push the image to Docker Hub?
19.	Write a Dockerfile for a Java-based application.
20.	What is Docker Compose?
21.	How is Docker integrated in Jenkins?
22.	Please explain Docker networking.
23.	Can you use multiple FROM statements in a Dockerfile?
24.	What is the difference between RUN and CMD?
25.	Write a Dockerfile for an Nginx application.
26.	What is the difference between Docker images and Docker containers?
27.	What are the benefits and use cases of using multi-stage builds in Docker?
28.	How does Docker handle resource limitations and isolation, such as CPU, memory, and I/O?
29.	Docker command: COPY vs ADD.
30.	ENTRYPOINT vs CMD in Dockerfile.
31.	Tell us something about Docker Compose.

### Kubernetes Interview Questions ###
1.	Why do we need Kubernetes when you have Docker already?
2.	What is the namespace in Kubernetes?
3.	What is the difference between Pod and Container?
4.	How do you restrict Pods and Containers to use limited host resources?
5.	How can you restrict resources to Pod if the engineer forgets to mention them in Pod definition?
6.	How to configure a health check in Pod?
7.	What is the image pull policy in Pod?
8.	How can you provide env variables to the Pod in a better way?
9.	What are the secrets in Kubernetes?
10.	What is Service in Kubernetes? How many types are there?
11.	What is Replica Set in Kubernetes?
12.	What is Deployment in Kubernetes?
13.	What is a Daemon Set in Kubernetes?
14.	If I want to run a specific container in a pod in Kubernetes, how do I run it?
15.	ENTRYPOINT vs CMD.
16.	How are the pods communicating with each other?
17.	What will you do to make your application more secure?
18.	What is a namespace in Kubernetes?
19.	What is a pod security policy?
20.	How will you implement security for a running container if you find a vulnerability?
21.	What are the various things that can be done to increase Kubernetes security?
22.	What problems have you faced?
23.	How often do you release the product?
24.	What Kubernetes issues have you encountered in production?
25.	What is the architecture of Kubernetes?
26.	How is the pod health check done in Kubernetes?
27.	How do you use Helm charts?
28.	What is the Blue/Green Deployment Pattern?
29.	Can you explain the concept of auto-healing in Kubernetes and give examples of how it works?
30.	What is a label and selector in Kubernetes?
31.	What is the CrashLoopBackOff state in a pod?
32.	What is Kubernetes Ingress?
33.	What are Kubernetes ConfigMaps and Secrets?
34.	How do microservices work?
35.	How do you debug your existing container?
36.	What is a DaemonSet?
37.	How do you upgrade the database and cluster in Kubernetes?
38.	How do you design your pods to be highly available?
39.	What is the Kubernetes version you are using?
40.	What is the difference between StatefulSets and Deployments in Kubernetes?
41.	Have you done the backup of etcd

### K8 Interview Questions ###
1.	if I want to run a specific container in pod in Kubernetes how to run it?
2.	Entry point vs CMD
3.	How the pods are communicating with each other?
4.	What will you do to make you application more secure?
5.	Namespace in k8?
6.	what is pod security policy 7 How will you implement the security for a running container if you find an vulnerability?
7.	What are the various things that can be done to increase Kubernetes security? Problem faced?
8.	How often do you release the product?
9.	Kubernetes issues in production
10.	What is the architecture of Kubernetes?
11.	how the pod health check is done in Kubernetes?
12.	helm charts usage?
13.	What is the Blue/Green Deployment Pattern?
14.	Can you explain the concept of auto-healing in Kubernetes and give examples of how it works?
15.	What is the label & selector in k8s?
16.	What is crashloofbackoff state in a pod?
17.	What is Kubernetes Ingress?
18.	Kubernetes ConfigMaps and Secrets?
19.	how microservices will work?
20.	How do you debug your existed container?
21.	What is Deamon set
22.	How to upgrade the DB and cluster in k8
23.	How you design your pods to have highly available
24.	What is the k8 version you are using
25.	What is difference between stateful sets and deployments in k8
26.	Have you done the backup of etcd

### Jenkins CICD - Real interview questions faced during interviews ###
1.	What are pipeline stages in your organization?
2.	What is the architecture of your application CICD deployment in the current organization?
3.	What is the issue have you faced in Jenkins non-prod to prod while building the Jenkins job?
4.	Pipeline issues in Jenkins
5.	Production pipeline issues in Jenkins
6.	What are the build issues have you faced in your project?
7.	Deployment strategies
8.	What are various plugins in your Jenkins Pipeline?
9.	How do you create a multi-branch Jenkins pipeline?
10.	How do you upgrade Jenkins?
11.	What is a shared library?
12.	What is Jenkins and security tools?
13.	What is the Jenkinsfile, and how is it used in Jenkins pipelines?
14.	How to integrate SonarQube in a declarative pipeline?
15.	How to pass credentials in a pipeline?
16.	What are the features of Jenkins?
17.	What is Groovy in Jenkins?
18.	Which command is used to start Jenkins?
19.	What are Declarative Pipelines in Jenkins?
20.	How can you set up a Jenkins job?
21.	How to create a backup and copy files in Jenkins?
22.	How can you secure Jenkins?
23.	What is the use of Backup Plugin in Jenkins? How to use it?

### Terraform - Real interview questions faced during interviews  ###
1.	What is Terraform?
2.	What is the state in Terraform?
3.	What is the remote state in Terraform?
4.	Explain variables in terraform?
5.	What is TFVARS in terraform?
6.	What is count and count index in terraform?
7.	what is outputs in Terraform?
8.	What are data sources in terraform?
9.	What are Locals in Terraform?
10.	What are functions in terraform and name a few functions you used?
11.	How do you manage credentials in terraform?
12.	Explain the concept of a workspace?
13.	How does Terraform manage updates to existing resources?
14.	Give the terraform configuration for  creating a single EC2 instance on AWS?
15.	How to Store Sensitive Data in Terraform?
16.	Does Terraform support multi-provider deployments?
17.	If I lose the state file in terraform how can I recover that?
18.	What are the commands of terraform apart from init, apply, plan?
19.	Null resource in terraform?
20.	What are modules in terraform?
21.	IS there a tool that can look for security vulnerabilities in your terraform code?
22.	What is the difference between Ansible & Terraform?
23.	Terraform vs CloudFormation
24.	I Faced one question.. Once you created ec2 using terraform, after that you added one tag manually what will terraform do..
25.	How do you deploy your code in different environments?
26.	Remote state in terraform and state in terraform?
27.	terraform data block vs resource block?
28.	How do you mange credentials in terraform?
29.	Explain the concept of a workspace
30.	terraform modules?
31.	Provider in terraform
32.	Null resource in terraform
33.	How to Ignore the Error Duplicate Resource when applying Terraform
34.	What are the commands of terraform apart from init, apply, plan
35.	How you maintain the state file
36.	If I lose the state files in terraform how can I recover that
37.	Is there a tool that can look for security vulnerabilities in your terraform code?
38.	What is the difference between Ansible & Terraform?
39.	explain provisioners in terraform.
40.	variables vs locals
41.	Does Terraform support multi-provider deployments?
42.	How to Store Sensitive Data in Terraform?
43.	Give the terraform configuration for creating a single EC2 instance on AWS
44.	How does Terraform manage updates to existing resources?
45.	How can you manage versioning of Terraform configurations?

