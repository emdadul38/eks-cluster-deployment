# eks-cluster-deployment

## Step 01
 #### Create Cluster
 A Kubernetes cluster is a set of node machines for running containerized applications. If you’re running Kubernetes, you’re running a cluster.
    • First create an IAM role with AmazonEKSClusterPolicy.
    • Now move to Services -> EKS -> Clusters -> Create Cluster
    • Type a name for the cluster.
    • Select any Kubernetes version. I chose 1.21 (No specific reason).
    • In the Service Role, select the IAM Role previously created.
    • Next, select the VPC created in the previous step.
    • Create Logging options based on the use case and then Review and create.
    • Wait until the the cluster state turns Active.
 #### create worker nodes
 #### configure kubectl to access cluster form local machine 

## Step 02
#### configure Service and workload
#### Configure ingress
#### Configure Cert-Manager
