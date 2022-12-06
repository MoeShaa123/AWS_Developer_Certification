## AWS CLI and SDK

- The AWS Command Line Interface (AWS CLI) is a unified tool to manage your AWS services. With this command line you can interact with AWS from anywhere. You can list buckets, launch or stop intances, change security groups, create subnets ect. Switch between AWS accounts using --profile 

- AWS Software Development Kit (SDK) allows you to control multiple AWS services using popular programming languages. SDK is a set of tools and libraries that you can use to integrate AWS services into your applications.

## AWS Services

- AWS CloudShell is a browser-based shell that makes it easy to securely manage, explore, and interact with your AWS resources. CloudShell is pre-authenticated with your console credentials. Common development and operations tools are pre-installed, so no local installation or configuration is required.

- Amazon Relational Database Service (RDS) is a managed SQL database service provided by Amazon Web Services (AWS). Amazon RDS supports an array of database engines to store and organize data. It also helps with relational database management tasks, such as data migration, backup, recovery and patching.

## IAM Best practices

- Require workloads to use temporary credentials with IAM roles to access AWS
- Require multi-factor authentication (MFA)
- Rotate access keys regularly for use cases that require long-term credentials
- Safeguard your root user credentials and don't use them for everyday tasks
- Apply least-privilege permissions
- Regularly review and remove unused users, roles, permissions, policies, and credentials
- Use permissions boundaries to delegate permissions management within an account
