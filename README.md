# deploy-to-eks-using-github-actions
1. Create an EKS Cluster using this command🧮 

eksctl create cluster --name testeks --region us-east-1 --nodegroup-name linux-nodes --node-type t3.micro --nodes 2

2. Then create .github folder and then create workflow inside .github folder
3. Create file with .yml extension and write the workflow code
4. Create a github repository
5. Create a secrets in github repo
        Go to settings of repo
        click on secrets and variables
6. Test application by getting the dns name and going to a web browser
7. Clean up: run eksctl delete cluster --name testeks