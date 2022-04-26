# infrastructure


Name: Siva Dheeraj Reddy

NUID: 001524090

EMAIL: obulam.s@northeastern.edu


Create & Setup GitHub Repository for AWS Infrastructure
Create (Links to an external site.) a new private GitHub repository in the GitHub organization you created.
GitHub repository name must be infrastructure.
Grant TAs access to your GitHub repository.
Update README.md in your repository with instructions for setting up your infrastructure using CloudFormation.
Fork the GitHub repository in your namespace. You will do all development work on your fork.
All CloudFormation templates should be in this repository.
Add appropriate .gitignore to your repository. A collection of useful .gitignore templates can be found here (Links to an external site.).


execute the following code to import the ssl certificate into the aws 
 aws acm --profile=demo-admin import-certificate --debug  --certificate fileb:///Users/dheeraj/Repo/Git/SEM_2/NETWORKS/prod_dheerajreddy.me/prod_dheerajreddy_me.crt \
      --certificate-chain fileb:///Users/dheeraj/Repo/Git/SEM_2/NETWORKS/prod_dheerajreddy.me/prod_dheerajreddy_me.ca-bundle \
      --private-key fileb:///Users/dheeraj/Repo/Git/SEM_2/NETWORKS/aws_cred/dheerajreddy_me.pem