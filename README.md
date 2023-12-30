# Creating-a-scalable-app-with-AWS-EKS-using-the-AWS-Console

 # Task 1: Creating EKS Cluster Components

Title: Creating the Components Required for the EKS Cluster
Before creating the EKS Cluster, prepare the IAM Role that provides the necessary permissions for the EKS Cluster to interact with AWS services.
Before creating the EKS Cluster, prepare the dedicated VPC required for the Node Group.

# Task 2: Creating and Connecting EKS Cluster to CloudShell

Title: Creating the EKS Cluster and Connecting it to CloudShell
Create the EKS Cluster through the AWS Management Console with all its settings.
Learn how to connect to the EKS Cluster using CloudShell.
Explore the EKS Cluster using Kubectl commands.

# Task 3: Creating Node Group and its IAM Role

Title: Creating the Node Group and its IAM Role
Add two types of compute resources to the EKS Cluster: Node Group and Fargate.
Node Group requires an IAM Role to perform its functions.
Node Group does not automatically increase the number of nodes; it requires AutoScaler-Cluster.

# Task 5: Creating AutoScaler-Cluster for Node Group

Title: Creating AutoScaler-Cluster for Node Group
Before adding AutoScaler-Cluster, grant necessary permissions to the Node Group's Role.
AutoScaler-Cluster can dynamically adjust the number of nodes in the Node Group based on Cluster requirements.

# Task 6: Adding and Testing Application in EKS Cluster

Title: Adding the Application to the EKS Cluster and Testing
Create an application on the EKS Cluster and manage it using Kubectl commands.
Increasing the Replica Pod count increases the number of nodes in the Node Group.
Creating an Ingress within the EKS Cluster automatically generates an AWS Load Balancer.

