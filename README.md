Create the underlying infrastructure (VPC, subnets, route tables, internet gateway, nat gateway, security groups).
Create EKS cluster role with policies - AmazonEKSClusterPolicy, AmazonEKSVPCResourceController.
Create EKS node group role with policies - AmazonEKSWorkerNodePolicy, AmazonEC2ContainerRegistryReadOnly, AmazonEKS_CNI_Policy.
Create the EKS cluster.
Create the node group.
Apply the deployment.yaml kubectl config.