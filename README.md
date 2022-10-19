# AWS-Ansible-CloudFormation-CICD
## Project Summery:
This project aims to:
<br/>
1- Deploy S3 bucket and Cloudfront using CloudFormation to host frontend code.<br/>
2- Apply the blue-green strategy to replace the old s3 domain with a new domain.<br/>
3- Build, test, and scan the project code before pushing it to the EC2 instance.<br/>
4- Deploy an EC2 instance to deploy the backend code on it and install the required packages using Ansible.<br/>
5- Monitor an EC2 instance using Prometheus.<br/>
6- Run a smoke test on the newly created infrastructure and if the test fails, it will rollback the changes.<br/>
7- Clean up old infrastructure to prevent additional costs.<br/>

## Tools:

1- AWS            <br/>
2- Ansible  <br/>
3- CloudFormation        <br/>
4- Circle CI<br/>
5- Prometheus<br/>


