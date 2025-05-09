# 🎯 Interview Questions - 2025

---

## General DevOps Questions

- **What's your organization's current CI/CD process and tools?**
- **What do you know about CyberArk and how are you consuming it in your pipeline?**
- **Which scripting languages are you aware of, and how confident are you with them?**
- **What AWS services have you used?**
- **If you want to design an infrastructure for high scalability, how would you do that?**
- **What are NACLs, Security Groups, and NAT Gateway?**
- **About Kubernetes architecture.**
- **Difference between ReplicaSet and Deployment.**
- **About Ansible and Terraform.**
- **About ConfigMaps, PV, PVCs.**
- **Write a Deployment file.**
- **Write a Dockerfile.**
- **About multistage Dockerfile.**
- **Which type of Jenkins file are you using? Can you please write a Jenkins file?**
- **What is the toughest situation you faced while implementing something, and what did you learn from that?**
- **Have you handled any debug/troubleshooting for Kubernetes?**
- **About Prometheus/Grafana.**
- **About Fargate.**
- **What are Lambda functions? Did you use any Lambda functions? What did you achieve from that?**

---

## **NatWest Group**

1. What is Maven release?
2. Explain the Maven lifecycle.
3. What is the purpose of the dependency management tag in Maven?
4. How did you manage Kubernetes pods, considering it's on Linux?
5. What happens when you run `mvn install`?
6. What types of branching strategies are you using?
7. Where is your `pom.xml` file located in your project?

---

## **Wikreate Media**

1. What is the use of Route53?
2. What is `git stash` used for?
3. What is the difference between S3 and EBS?
4. What is the difference between `git fetch` and `git pull`?
5. What is the difference between vertical and horizontal scaling?
6. What is the role of continuous integration?

---

## **AWS Cloud Engineer Role**

1. Explain the OSI model.
2. How did you perform cost optimization in AWS?
3. Explain AWS Lambda, CloudFormation, Data Storage, and S3.
4. How do you implement best security policies on AWS?
5. What factors motivate you for this role?
6. Explain your cloud migration process.

---

## **SRE Role**

1. What commands do you use for Kubernetes, Docker, and Ansible?
2. Explain Kubernetes structure, Config Map, and Scheduler.
3. How do you troubleshoot the `ImagePullBackOff` error?
4. Explain the installation process of Prometheus and Grafana.
5. How do you build a CI/CD pipeline?
6. How do you monitor CPU metrics in Grafana?
7. How do you grant access to users in a Kubernetes environment?

---

## **LinkedIn Post (08-02-2025 Interview Experience)**

1. Write Terraform code to create multiple S3 buckets.
2. How do you manage the state file in Terraform?
3. How do you handle state file conflicts in Terraform?
4. How do you integrate SonarQube with Jenkins?
5. How do you authenticate Jenkins to push Docker images to a registry?
6. What deployment strategy are you following in Kubernetes?
7. How do you implement Blue-Green deployment?
8. What is Horizontal Pod Autoscaler (HPA)?
9. How do you roll back a Kubernetes deployment to a specific version?
10. What is a StatefulSet in Kubernetes?
11. What are the different IAM policy types in AWS?
12. What is the difference between S3 bucket policies and ACLs?
13. What is dynamic auto-scaling in AWS?
14. What is the difference between Security Groups and NACLs?
15. How do you access tokens in one AWS account from an EC2 instance in another account?

---

## **Oracle (8 years experience)**

1. What is the purpose of using init containers in Kubernetes?
2. What is the difference between StatefulSet and Deployment in Kubernetes?
3. Explain ConfigMap vs Secrets in Kubernetes.
4. What is a Pod Distribution Budget in Kubernetes?
5. Explain the steps for building a multi-stage Docker image.
6. What layers are created when you build a Docker image?
7. How do you troubleshoot when deploying a Pod that throws an error?
8. How do you deploy a Pod to a specific node?
9. Explain the components of a `deployment.yaml` file in Kubernetes.
10. How do you fix a corrupted Terraform state file?
11. Explain Terraform lifecycle (create/after destroy).

---

## **TCS (9 years experience)**

1. What is JFrog Artifactory?
2. What is Ansible Tower?
3. What is Nagios, and how do you integrate Jenkins with Nagios?
4. What are Ansible roles and Jinja2 templates?
5. What is JFrog Xray, and how is it used?
6. How do you find the mount point space in Linux?
7. What are the Ansible modules you have used?
8. What is the difference between GitHub repos and JFrog?
9. What branching strategies do you use?
10. What are the different types of repositories in JFrog?

---

## **HCL**

1. What is the difference between PV and PVC in Kubernetes?
2. Explain the Kubernetes architecture.
3. What is the difference between Deployment and StatefulSet?
4. What is Calico in Kubernetes?
5. What is etcd?
6. How do you take a backup of a Kubernetes cluster?
7. How do you upgrade an EKS cluster?
8. What is a rolling update in Kubernetes?
9. What deployment strategies are you using?
10. Can we run one container with two pods?
11. What is StatefulSet?
12. How do you upgrade an EKS cluster?
13. What are the steps to upgrade an EKS cluster?
14. What happens if the pod `mongo-0` dies in a StatefulSet?
15. Have you worked with Argo CD or Helm charts?
16. What is Docker multi-stage build, and why is it used?
17. Have you worked with Grafana?

---

## **CTS**

1. What are the common troubleshooting steps when a web app is down?
2. How do you troubleshoot service failures in Nginx/Apache?
3. How do you investigate failed Jenkins builds?
4. How do you secure an S3 bucket that was made public by mistake?
5. How do you troubleshoot a Jenkins failure to push a Docker image?

---

## **UK Company**

1. /var partition is 90% full. What’s your immediate action?
2. You’re locked out via SSH with no root access. How do you recover?
3. Add 50GB to /opt using LVM without any downtime. What are the steps?
4. Jenkins is failing to push a Docker image to the registry. How do you troubleshoot?
5. Ansible playbook times out on one host. What do you check?
6. EC2 instance is unreachable, and it’s not a security group issue. What’s your next step?
7. How do you secure and audit a publicly exposed S3 bucket?
8. How would you approach RDS migration with minimal downtime?
9. How would you implement rollback in a CI/CD pipeline?
10. Write a shell script to check if a service is running and restart it if not.
11. Write Terraform code to provision an EC2 instance with a custom security group and user data script.
12. Design a highly available backend on AWS. What services and architecture would you use?

---

## 🏢 Company: Techdome

1. Kubernetes Architecture
2. Deployment vs StatefulSet
3. Explain Docker Networking and types of network. What is the default network?
4. Terraform Provisioners
5. Terraform Statefile
6. Docker Image vs Container
7. Docker Bind Mount vs Volume

---

## 🏢 Company: LTIMindtree

- Can we install Docker inside a container?
- If we have created 3 instances using a Terraform script and the instance names are mentioned as a list:  
  - Suppose we remove the 2nd instance name from the list and apply the script again, what happens to the already created 3 instances?
- If we have 5 stages in a Jenkins pipeline, and the 5th stage has a syntax error, what happens when we run the pipeline?
- What are the main differences between Scripted and Declarative pipelines in Jenkins?
- Difference between Code Quality and Code Coverage.
- What is the default Quality Gate in SonarQube?
- How to run a Kubernetes YAML manifest if no manifest file is created?

---

## 🏢 Company: HCL (Experience: 4–5 years)

- What Git branching strategy is used in your organization?
- How is deployment done in different environments using a Git repository?
- How and from where do you clone the repo? Are you using any local repo and then transferring it to remote? (Clarify real-time exposure if possible.)
- What is a PAT (Personal Access Token)?
- How to configure SonarQube?
- How to integrate Azure Key Vault into Jenkins / Azure Pipelines?
- How to handle merge conflicts in Git?  
  (If two people work on the same file and get a conflict error — how many ways can it be resolved?)
- What is the output of SonarQube?  
  How to fix smell codes/vulnerabilities found?
- Where do you write the code/YAML file for pipelines?
- What is inside a Dockerfile?
- How to schedule a pipeline?  
  (Example: After validating some updates, how to schedule merging into stage/main branch?)

---

## 🏢 Company: Blue Yonder

- How do you use Azure Key Vault secrets in AKS?
- How does the application (container/pod) fetch the latest (rotated) secrets from Azure Vault?
- How do you integrate SonarQube and Snyk into Azure Pipelines?
- How do you secure your AKS cluster?
- How do you make your AKS cluster highly available?
- How do you perform cost optimization in AKS?
- HPA triggers: What types of triggers have you used so far?
- Stateful vs Stateless applications
- How do you manage the data of a Stateless application?
- How do you integrate Entra ID (Azure AD) with AKS for authentication?

---

## 🏢 Company: Wipro

- What is your day-to-day activity?
- If a file is used by two customers and needs to be deployed both in a Kubernetes cluster and on-prem, how do you handle it?
- What is the issue with using a large-size image in Dockerfile?
- How to deploy an application to a Kubernetes cluster (explain only the CD part)?
- If a secret is stored in Vault inside a pod and that pod is down, how do you troubleshoot?
- How is Azure Key Vault integrated into CI/CD?
- What to do if an application is down?
- **Scenario-based questions:**
  - (a) If a service is down for more than 2 weeks and the customer is asking for an update, what will you tell the customer?
  - (b) How to troubleshoot the issue and what steps would you check during the process?
  - (c) What steps can be taken to ensure the issue doesn't happen in the future?
- What is written inside a Dockerfile?
- What contents are inside a Deployment.yaml or Helm Chart?

---

## 🧩 L1 Questions:

- In Git, explain the push and pull commands.
- What is the use of Git tags?
- What are the different types of branches in Git?
- How do you write an Ansible playbook, and what client requirements do you consider?
- In Python, what are lists and tuples, and how do they differ?
- In CloudWatch, what is the use of log groups and log trails?
- In Terraform, what is the purpose of `init`, `plan`, and `apply` commands?
- What happens if the Terraform state file is accidentally deleted?
- What is the purpose of creating S3 bucket policies?
- How do you maintain the lifecycle of an S3 bucket?
- In Airflow, if a job fails, how do you debug it?
- If you're facing performance issues on a server, how do you troubleshoot?

---

## 🧩 L2 Questions:

- What are Network ACLs and Security Groups, and how do they differ?
- Explain EC2 instances and handling multiple VPCs.
- How do you configure AWS RDS, and what factors do you consider (size, requirements, etc.)?
- How much data is stored in your RDS MySQL?
- How many masters and slaves are configured in RDS?
- How do you configure a Grafana dashboard?
- What kind of CI/CD pipelines are you familiar with?
- Explain Declarative vs. Scripted pipelines.
- In Kubernetes, if a pod is in a pending state, how do you troubleshoot?
- If Docker containers are consuming too much disk space, how do you fix it?
- In Linux, how do you attach and detach a filesystem?
- How do you print the last 15 lines of a file in Linux?
- How do you enable passwordless authentication between two servers?

---

# 🏢 Company-Specific Questions

---

## 🏢 Company: E&Y

- Introduction
- Explain current project
- Kubernetes: Deployments, Services, ConfigMaps
- How to integrate Grafana with Prometheus
- Terraform questions
- Service Mesh concepts
- Pod Disruption Budget
- Git: squash vs rebase
- Purpose of Docker

---

## 🏢 Company: Startup Company

- Explain your organization's current CI/CD process and tools.
- How comfortable are you with AWS? (Rate yourself out of 5)
- Questions on IAM, Fargate, EC2, Lambda
- Can you write a Lambda function?
- Kubernetes Architecture and workflow explanation
- Write Terraform file to provision an EC2 instance in a public subnet of a VPC
- Are you using a Dockerfile? Are you building it with CodeBuild?
- How many containers can run in a pod?
- Example of running 4-5 containers inside a pod in your project
- Prometheus and Grafana setup experience
- Security measures/tools used in CI/CD pipelines
- RBAC (Role-Based Access Control) explanation

---

## 🏢 Company: Infosys (Set 1)

1. Introduce yourself
2. Git commands used in day-to-day activities
3. Write a sample Dockerfile
4. Write a sample Terraform resource file
5. Difference between Git rebase and Git merge
6. Difference between CMD and ENTRYPOINT in Docker
7. Explain Prometheus and Grafana
8. Troubleshooting if a Pod YAML fails
9. Explain the Blue-Green deployment strategy
10. Kubernetes architecture explanation
11. Basic Kubernetes commands
12. Troubleshooting approach if a deployed Kubernetes app crashes and pod is inaccessible
13. Project pipeline explanation
14. Have you worked on production deployment activities?
15. Frequency of production deployments in your current project

---

## 🏢 Company: Infosys (Set 2)

- Introduction
- Current company project-related questions
- Daily task and activities
- What are Prometheus, Grafana, Loki
- What is Kibana
- How Prometheus collects metrics
- Prometheus setup details
- Kibana setup details
- What is a log rotate job and how does it work
- Jenkins, Ansible basics
- Terraform usage in your project, resources provisioned
- Kubernetes Deployments, DaemonSets, StatefulSets
- Basic Kubernetes commands
- Docker usage and Dockerfile writing
- Data sources in Grafana and Kibana
- Traffic routing inside Kubernetes clusters (ELB, Ingress)
- Receiving and setting up alerts in the project
- Pod basics
- Indices and Index in Kibana
- CronJobs
- PaaS-related questions
- Handling disk and CPU alerts
- Kubernetes issues you have solved
- Troubleshooting approach if Pod/Node goes down

---

## 🏢 Company: CTS

- What is connection drain?
- `backend.tf` file is shown in the repo but not visible in the storage account — what could be the issue?
- How to log in to a VM with only a private IP?
- Deployed a web app successfully but later it went down — networking is fine, ports are open — how do you troubleshoot?
- Types of Load Balancers
- What is Azure Application Gateway and how does it encrypt HTTP/HTTPS traffic?
- Application is down and showing a 503 error — what steps should you take?

---

# Interview Questions and Scenarios

---

## VPC & Networking Questions

1. **How many NAT Gateways are needed for two public & two private subnets in a single VPC? Min & Max?**

2. **Explain TTL in DNS - how does it work, and when do we use it? Explain the Flow.**

3. **How does weighted routing work in LB?**

4. **How does Docker operate on a Linux machine? Explain the Docker architecture components.**

5. **There are 1 Master & 3 Worker nodes- if the master fails, what happens? Will pods keep running or they will crash?**

6. **In K8s, as etcd is a key-value store db, can you write something manually on it?**

7. **How to roll back a failed deployment in Docker & K8s?**

8. **How does SSL work (Certbot, Let's Encrypt, AWS)? Explain the Flow.**

9. **What are the top 5 infra attacks, and how do you mitigate them?**

10. **If the tfstate file is lost, what do you do? With & without backup?**

11. **In Linux systems, there is the term Load Average? What does that mean? How is it calculated? And in what format is the load average output?**

12. **One of your worker nodes is not joining the cluster. How would you debug the issue?**

---

## Security and AWS

- **How would you ensure the best possible security for high availability architectures for 3-tier applications?**
- **Difference between SGs and NACLs.**
- **What is VPC peering?**
- **How do you scan for vulnerabilities, especially for AWS instances?**
- **Difference between IAM Users and Roles.**
- **Can you avoid specific port traffic using SGs?**
- **How do you connect to private instances when the SSH connection is not working?**
- **Where do you use firewalls, SGs, and NACLs?**
- **What are the best password security practices used by your organization?**
- **What are the security parameters we must consider while creating an EC2 instance for production?**
- **How can you protect the data in an AWS instance?**
- **How can you connect from AWS to on-prem servers?**
- **Explain about the Transit Gateway and why do we use this?**
- **What are the provisioners available in Terraform and can you explain the use cases?**
- **I have created an EC2 instance named A, and I want to create another instance B. It should create an instance without deleting instance A. What can I do during this?**
- **I have created an EC2 instance through Terraform. I don't have a backup of the Terraform state file, it is not in the remote state and locally not available. Now when I do apply, what can I do?**
- **Suppose I have given one command in null resource, it should run every time. What is the behavior?**
- **What is the difference between a map of objects in Terraform and how can you write an example?**
- **Suppose in your DevOps team, new team members are added to your team. How can you provide AWS access to your new users, and what is the behavior of login to the console?**
- **What is the difference between an EBS-backed instance and a non-EBS-backed instance?**
- **I have 3 nodes (small, medium, and large), and I want only data load to go to the large node. How can I do that?**
- **When I deploy the pods, it should be deployed on large and medium nodes, except small. How can I configure that?**
- **I am getting the following error, how can I debug that and what does the error mean?**
    ```
    Pods fail to schedule
    0/5 nodes are available: insufficient memory.
    ```

---

## Kubernetes and Containers

- **What is the difference between scaling and autoscaling in Kubernetes?**
- **If I don't specify TargetPort in the service object, what is it going to do?**
- **What are the different types of secrets in Kubernetes?**
- **I have an Ingress object that is not routing the traffic to the Kubernetes cluster. What are the reasons and how do you troubleshoot that?**
- **I have created a service object that is not mapped to a deployment. What could be the reason and how do you debug it?**
- **What are the different ways to specify the probes in Kubernetes?**
- **What is the difference between `git push --force-with-lease` vs `--force`?**
- **If I select the restart policy as Never, what is it going to do?**
- **What is an init container and why do we need to use it?**
- **What is the difference between EKS vs ECS vs Fargate?**
- **How can you delete the last 2 git commits?**

---

## General Infrastructure & CI/CD

- **What will happen if the K8 master node and worker node firewall gets broken? Will the existing deployments work or impact on any new deployments? How will you communicate to people?**
- **How to use secrets in Kubernetes? What encryption methods do you use?**
- **How does the GSLB load balancer work?**
- **What is SLI, SLO, SLA?**
- **How can you create extensions in Grafana?**
- **How does the ELK setup work, and what type of agents have you collected?**
- **Can you tell one scenario where you have done the RCA with respect to Linux?**
- **You have JSON data, how would you ingest and collect the data in the keys format?**
- **Can you design the Istio setup for your K8 cluster?**
- **AWS EventBridge creation and setup via Terraform?**
- **What will be the command to add annotations and labels for the existing pod?**
- **Design the Kubernetes cluster with Ingress.**
- **A sudden surge in traffic causes a web application to become unresponsive. What will be the steps you will take to mitigate it?**
- **Design the deployment of the pod with a replica set set as 3 and having the Apache HTTPD image running as a container.**
- **How do you reduce the size of a Dockerfile?**
- **Write a shell script to find and delete all files in a directory that are older than 30 days.**
- **Create a script to monitor the disk usage of a server. If usage exceeds 80%, log the details to a file and send an alert email.**
- **Write a script that renames all .txt files in a directory by appending the current date to the filename.**

---

## Docker & Kubernetes File Questions

- **What is the difference between NSG and Firewall?**
- **What is the difference between COPY and ADD commands in Dockerfile?**
- **What is Taint/Toleration?**
- **What is a StatefulSet?**
- **Architecture of Kubernetes.**
- **Use case of Node-Port and ClusterIP service type in Kubernetes.**
- **Explain GitHub Action workflow file.**
- **Difference between ENTRYPOINT and CMD in Dockerfile.**
- **Can we connect two different VMs that are in different VNets?**
- **Private Endpoints.**
- **ExpressRoute in Azure Cloud.**
- **What is PDB in Kubernetes?**
- **Difference between PV/PVC in Kubernetes.**
- **What is a state file in Terraform?**
- **What is a lock file in Terraform?**
- **Why Kubelet and Kube-proxy are used in Kubernetes?**
- **How can you build an image and push it to ACR?**
- **How can you use the existing image in a YAML file to deploy a pod?**
- **What is a pod in Kubernetes?**
- **Types of services in Kubernetes.**
- **Namespaces in Kubernetes.**

---

## **Emphasis**

1. Explain the components in a 3-tier architecture.
2. Explain Kubernetes architecture.
3. How does a private subnet connect to the outside world?
4. What is the difference between NACLs and security groups in AWS?
5. What is the purpose of a NAT gateway?
6. How do you write a Dockerfile?
7. How is an image pulled when using `docker pull`?
8. How do you pull an image from a private Docker repository?
9. What is an ingress controller in Kubernetes?
10. Explain the stages in a CI/CD pipeline.

---

## **DevOps Interview Questions**

1. What is a Dockerfile, and what is inside it?
2. Why Kubernetes instead of Docker Swarm?
3. What is the architecture of Kubernetes?
4. What is Blue-Green deployment? Explain a project based on it.
5. Why do Blue-Green and Canary deployments differ?
6. What happens if etcd stops working in Kubernetes?
7. What are the types of services in Kubernetes?
8. Explain a project in which you used Docker, Kubernetes, and CI/CD.
9. What CI/CD tools do you use? Explain in detail.
10. What happens if a Docker image has port 8080 but the container/application uses a different port?
11. Why is a load balancer used?
12. What is your Git branching strategy?
13. How do you handle Terraform state file locking?
14. What is the difference between a service and a deployment in Kubernetes?
15. What are some Linux commands you frequently use?
16. How do you write an Ansible file?
17. How do you structure a CI/CD pipeline?
18. What are the stages in a Jenkinsfile?

---

## **Nisum Technologies**

1. Explain your experience with CI/CD pipelines.
2. What is a scraper?
3. Can you deploy services on a master node in Kubernetes?
4. What deployment strategy are you following?
5. What is the difference between `COPY` and `ADD` in Docker?
6. How do you fix security issues in Docker images?
7. What is the difference between content and tuple in Terraform?
8. Have you worked on Python or shell scripting? Can you explain one file?
9. Have you worked with Ansible?
10. Explain Fargate in AWS.
11. How do you troubleshoot when a Kubernetes pod is not running?
12. What is the difference between a list and a string in Terraform?
13. Have you worked with Helm charts?

---

## **Capgemini (6+ years experience)**

1. How do you assign memory to a pod and ensure that it doesn't encounter memory constraints?
2. How do you pass variables in an Azure pipeline and parameterize it?
3. What is an availability zone, and explain the layout on the ground level?
4. How does MySQL interact with Azure Key Vault securely?
5. What is the difference between `git fetch` and `git pull` in depth?
6. What happens behind the scenes when you run `git add`?

---

## **Commonwealth Bank (4-5 years experience)**

1. What is observability architecture? Can you explain it?
2. What is DNS? What happens when you type `google.com`?
3. What is the difference between observability and monitoring?
4. Why do we need traces if we have logs?
5. How do you set SLAs and SLOs in an application from a business perspective?
6. How do you decide SLIs for an application?
7. Explain metrics, logs, and traces, including the tools used.
8. How does observability help in maintaining reliability?

---

## **Rapidsoft (10.5 years experience)**

1. What are the things you have worked on? Explain your experience.
2. How do you investigate errors in Terraform provisioning?
3. How do you execute something as a root user in Ansible?
4. How do you investigate Jenkins CI/CD pipeline failures?
5. How do you store sensitive information like passwords in Jenkins?
6. How do you manage multi-cloud pipelines?
7. How would you structure disaster recovery for your application?
8. How would you perform a database migration for your application?
9. How would you fix a crashloopback error in Kubernetes?
10. What is the difference between Deployment and StatefulSet in Kubernetes?
11. Explain the terms in a `deployment.yml` file.
12. Have you worked with Docker Swarm?

---

# Interview Questions

## Company: Epam
**Experience:** 9 years (4 years in DevOps)

### Kubernetes:
1. How to Create and Use Custom Resources in Kubernetes?
2. What are namespaces in Kubernetes?
3. What is the difference between a Deployment and a StatefulSet?
4. What is Role-Based Access Control (RBAC)?
5. What is the Cluster Autoscaler and Horizontal Pod Autoscaling?

### Terraform:
1. What is a provider in Terraform?
2. How to manage state in Terraform?
3. Do you store the data in the state file locally or remotely? What is the block you use while storing the state file?
4. What is a Terraform module?
5. How to manage multiple environments in Terraform?
6. What are the use cases of CloudWatch?
7. What is ECS and EKS?
8. What is Fargate?
9. What are the limitations of Lambda?
10. How does Lambda work with containers?
11. What are EC2 instances?
12. What is Direct Connect in AWS?
13. What is the Storage Gateway in AWS?
14. What is VPC, NAT Gateway, S3, Route53, VPC Peering, Transit Gateway, Autoscaling Group?
15. Difference between Security Groups (SG) and Network ACL (NACL)?
16. What is the difference between `COPY` and `ADD` commands in Docker?
17. Difference between `CMD` and `ENTRYPOINT` in Docker?
18. What is the `RUN` and `EXEC` commands in Docker?
19. What does the `VAR` and `OPT` directories contain in Linux?
20. Write a script to search for the pattern "error" and "warning" in the `test.log` file. Store "error" patterns in one file and "warning" in another file.

---

## Company: NUOS INFO Systems
**Experience:** 4 years  
**Tech Stack:** Terraform, Azure, DevOps, Docker, Git

1. How do you scale a Terraform pipeline that takes 25+ minutes?
2. What happens to the Terraform state file if someone deletes resources from Azure?
3. If the pipeline fails due to existing resources, how do you handle RIP (Remove, Import, Plan)?
4. How do you export Azure resources into Terraform code?
5. How do you enforce Azure Policies (like tag or location restrictions) using Terraform at scale?
6. Best practices to structure repos and pipelines in a large DevOps project?
7. Pipeline fails only on Tuesdays, no code changes — how do you debug?
8. Logs are incomplete — how would you troubleshoot across AKS, Ingress, App, and Infra?
9. How to monitor Azure VM memory and alert if it crosses 80%?
10. How to write a multistage Dockerfile for a Node.js app — removing secrets and unnecessary layers?
11. Recommended tools for CI/CD, artifact storage, vulnerability scanning, and container registry in a hybrid (on-prem + Azure) setup?
12. How do you assess Azure DevOps migration readiness and plan the transition?
13. How do you manage AWS + Azure using a single DevOps process with focus on security & cost?
14. How would you use the Azure DevOps REST API to apply a security policy to all repos programmatically?
15. What’s the difference between Git Merge and Rebase?
16. If someone force-pushed and lost the main branch, how do you recover it?
17. How to push the recovered branch back to remote?

---

## Company: Netcracker
**Experience:** 7 years (DevOps role)

1. Difference between mount and directories in Linux.
2. How will you restart the HTTP service from a VM?
3. Disk I/O in Linux.
4. What is meant by CPU throttling?
5. What are custom resources in Kubernetes?
6. What is ingress in Kubernetes?
7. Application is configured with Ingress but the webpage is not loading. What are the steps you will check?
8. How will you monitor the cluster through Prometheus?
9. Upgrading the worker nodes in Kubernetes.
10. For a junior team member, what roles will be provided in Kubernetes?
11. Difference between Role and RoleBinding.
12. If I want to deploy my app on worker node 2, what should I do?
13. Difference between NodeSelector, NodeAffinity vs Taint, Toleration.
14. While updating your worker node, you're trying to drain the PODs, but some PODs are not removed from the node. What will you do?
15. What command will you give for view access for the cluster → READ in rolebinding.yaml file?
16. What are storage classes in Kubernetes?
17. What is NFS in Kubernetes?
18. What's the purpose of using a storage class in Kubernetes?
19. If I have two PODs in the same worker node, can they communicate with each other?
20. If I have two PODs in different worker nodes, can they communicate? How to restrict communication between them? (Network policy)
21. What component should be added in network policy YAML file?

---

## Company: Zensar
**Experience:** 6+ years

1. What is a service connection/connection string?
2. How to set alerts in Azure Monitor (explain steps and configuration)?
3. Types of VNet peering in Azure.
4. What is Disaster Recovery (DR)?
5. What types of pipelines do you use? How many types of pipelines are there?
6. What is a variable in a pipeline?
7. If we have to run multiple jobs in parallel using a single pipeline, can it be done? How?
8. What is an agent in Azure DevOps?
9. Difference between ReplicaSet and Deployment in Kubernetes.
10. Difference between stateless and stateful applications in Kubernetes.
11. How can ConfigMap and Secrets be used in Kubernetes?
12. If the control plane goes down, what will happen to the worker plane?
13. What is etcd and its use in Kubernetes?
14. How to create an app registration in Azure?
15. What is Docker networking?
16. Why do we need Kubernetes if Docker volumes are there?
17. If two pods are in different namespaces, how can we make them communicate with each other securely?
18. What is Ingress in Kubernetes?
19. In terms of cost optimization, which one should we use: Azure App Gateway or Network Gateway?

---

## Company: CTS
**Experience:** 7 years

1. What is connection drain in AWS?
2. The `backend.tf` file is showing in the repo but it is not showing in the storage account. What may be the issue?
3. How to log into a VM if the VM has a private IP?
4. You have deployed a web app and it was working fine but the application went down. All networking and related ports are open. How do you troubleshoot?
5. Types of load balancers in AWS.
6. What is Azure App Gateway and how does it encrypt HTTP/HTTPS traffic?
7. An app is down and throwing a 503 error code. What steps should be taken to troubleshoot?

---

## Company: Hexaware
**Experience:** 4-5 years

1. Write a YAML pipeline for CI/CD (overall structure).
2. What is the command for auto-approval in Terraform?
3. What is `deployment.yml`?
4. What is `service.yml`?
5. What is a ReplicaSet in Kubernetes?
6. What is the output of a Helm chart?
7. What is Azure Storage Explorer?
8. How do you set approval in a CD pipeline?
9. What branching strategies have you used in your DevOps pipeline?
10. Have you written any automation scripts in your daily tasks?
11. How do you move the code from one environment to another?
12. What is a variable group in Azure DevOps?
13. What is SonarQube and which purpose is it used for?
14. Write a sample Terraform code (overall skeleton).
15. What are the files available inside a Helm chart?

---

## Company: Arrise Solutions
**Experience:** 7 years

1. Explain a three-tier architecture.
2. Difference between ALB and NLB in-depth.
3. How to connect an AWS VPC to an IBM Cloud VPC?
4. Difference between a Public and Private subnet.
5. How to connect your private subnet with the Internet?
6. Does a NAT gateway run in a public or private subnet?
7. Kubernetes architecture overview.
8. What is CoreDNS in Kubernetes?
9. What’s the purpose of CNI in Kubernetes?
10. How does kube-proxy communicate with nodes in Kubernetes?
11. What is the purpose of the scheduler in Kubernetes?
12. Layers in Docker.
13. Difference between using VM vs Docker.
14. Types of storage drivers in Docker.
15. Types of networking in Docker and explain in detail.
16. Does Docker have a kernel in place?
17. CNAME and namespace in Docker.
18. Which network will be used to isolate communication between two containers?
19. How to check the Linux process?
20. How to check the load of a Linux machine?
21. While rebooting a Linux machine, what are the stages/layers that will be restarted?
22. Where are kernel logs stored in Linux?
23. How to kill a running process in Linux?
24. States of a Linux machine.
25. When you type google.com, what happens at the backend in the browser?
26. When you type `TOP` command, what components will be displayed?
27. What is AWS CloudFront?
28. How does SSL certificates work between a client and a remote machine?

---

## Company: CTS (Additional)
1. How do you manage Terraform state files?
2. How would you design an architecture for a 2-tier application?
3. Difference between subnet and NACL.
4. Difference between NAT gateway and internet gateway.
5. How would you trigger pipeline B in Jenkins automatically after pipeline A?
6. How will you know if a network policy is enabled or not in Kubernetes?
7. Difference between ClusterRole and ClusterRoleBinding.
8. What will happen when an IaC-managed resource is modified manually? How would you avoid it?
9. Difference between DaemonSet and StatefulSet in Kubernetes.
10. How would you set up networking in VPC?
11. How would you direct traffic to and from an instance in a private subnet?

---
