# Deploy-PHP-app-using-Jenkins-to-AWS-EKS
1. Create an EKS Cluster using this command:
eksctl create cluster --name tbcommerce --region us-east-1 --nodegroup-name linux-nodes --node-type t2.micro --nodes 2



2. Test application by getting the dns name and going to a web browser

Clean up: Run: eksctl delete cluster --name tbcommerce