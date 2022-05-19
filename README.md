# eks-cluster-deployment

## Step 01
 #### Create Cluster
 A Kubernetes cluster is a set of node machines for running containerized applications. If you’re running Kubernetes, you’re running a cluster.
   1) First create an IAM role with AmazonEKSClusterPolicy.
   2) Now move to Services -> EKS -> Clusters -> Create Cluster
   3) Type a name for the cluster.
   4) Select any Kubernetes version. I chose 1.21 (No specific reason).
   5) In the Service Role, select the IAM Role previously created.
   6) Next, select the VPC created in the previous step.
   7) Create Logging options based on the use case and then Review and create.
Wait until the the cluster state turns Active.
 #### create worker nodes
 #### configure kubectl to access cluster form local machine 

## Step 02
#### configure Service and workload
#### Configure ingress
#### Configure Cert-Manager
