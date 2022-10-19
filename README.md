# AWS-Ansible-CloudFormation-CICD
## Project Summery:
This project aim:
<br/>
1-	Deploy S3 bucket and Cloudfront using CloudFormation to host frontend code.
2-	Apply blue green strategy to replace the old s3 domain with new domain. <br/>
3-	Build, test and scan project code before pushing on the EC2 instance. <br/>
4-	Deploy EC2 instance to deploy backend code on it and install required packages using Ansible. <br/>
5-	Monitor EC2 instance using Prometheus. <br/>
6-	Run smoke test on newly created infrastructure and if test failed it will rollback the changes. <br/>
7-	Clean up old infrastructure to prevent additional cost. <br/>

## Tools:

1- AWS            <br/>
2- Ansible  <br/>
3- CloudFormation        <br/>
4- Circle CI<br/>
5- Prometheus<br/>


