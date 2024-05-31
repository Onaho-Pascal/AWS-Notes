# Mastering Identity and Access Management (IAM) Services on AWS
## What is the IAM?
AWS Identity and Access Management (IAM) is an important service that enables secure access to AWS resources. IAM helps manage access to AWS services and resources by creating and managing AWS users, groups, roles, and permissions. In this article, we will delve into the features, benefits, and best practices of IAM services on AWS.
## Features of IAM Services on AWS
IAM has several features, which are broadly categorized into **Access Management** and **Access Reports**.
## Features under Access Managements:
![1716320129810](https://github.com/Onaho-Pascal/AWS-Notes/assets/156159318/64507c05-40ff-4542-83f7-727e535233a0)
* **Users**: Users in AWS can be divided into Root user and IAM users. IAM users are entities that can access AWS resources. Users can be created and managed within IAM by the root user or through the root user's account, and each user has a unique set of credentials.
* **User groups**: IAM groups are collections of users that can be managed together. Groups simplify user management and permission assignment.
* **Roles**:  IAM roles are predefined permissions that can be assumed by users or services. Roles enable secure access to AWS resources without sharing credentials.
* **Policies**: IAM policies define permissions and access control for users, groups, and roles. Policies can be created and managed within IAM.
* **Identity Providers**: IAM Identity Providers enable users to access AWS resources using credentials from external identity systems. This allows users to utilize their existing identity management infrastructure, such as Microsoft Active Directory or Google Workspace, to authenticate and authorize access to AWS resources. There are three types of IAM Identity Providers: (1) AWS Directory Service which Integrates with Microsoft Active Directory, allowing users to access AWS resources using their existing Active Directory credentials, (2) AWS Single Sign-On (SSO) which enables users to access multiple AWS accounts and third-party applications using a single set of credentials, and (3) Custom Identity Providers which allows users to integrate their own identity management systems, such as Google Workspace or Okta, with AWS IAM.
* **Account Settings**: IAM Account Settings manage the global settings and configuration for an AWS account. These settings affect the entire account, rather than individual users or resources.
## Features under IAM Access Reports:
![1716320721542](https://github.com/Onaho-Pascal/AWS-Notes/assets/156159318/3fed17c5-ff40-4d5f-9e97-4477b3d4c072)

* **Access Analyzer**: Access Analyzer helps identify and report on access to AWS resources. It provides findings based on resource permissions, user and role access, and service-level access. This feature enables you to:
--- Identify unused or excessive access
--- Detect resource exposure
--- Simplify access management: 
* **Credential Report**: The Credential Report generates a report on all IAM user credentials, including: Access keys, Secret keys, Passwords, MFA devices. This report helps you:
--- Monitor credential usage
---Identify unused or compromised credentials
--- Rotate or remove unnecessary credentials
* **Organization Activity**: Organization Activity provides a centralized view of all AWS activity across your organization, including: Service events, Resource changes, User activity. This feature helps you:
- Monitor and audit activity
- Identify security threats
- Meet compliance requirements
* **Service Control Policies**: SCPs enable you to define and enforce controls across
your organization, including: Access restrictions, Service limitations, Resource constraints. SCPs help you:
- Enforce security and compliance standards
- Limit access to sensitive resources
- Ensure consistent configuration
## Conclusion
In conclusion, AWS IAM services offer a powerful toolset for managing access to one's AWS resources. With IAM, One can focus on driving innovation and growth, while keeping your resources safe and secure. Learning IAM and its services on AWS has given me a whole different persepective to account management and security processes.
![1716321440767](https://github.com/Onaho-Pascal/AWS-Notes/assets/156159318/fa3fe481-bda5-4b58-81f1-9d5ad13a3c67)


