
## Introduction

In modern business environments, secure access to systems and resources is critical. Organizations rely on authentication and authorization mechanisms to ensure that only approved users can access sensitive information and services. Without proper access control, unauthorized users can exploit company resources such as shared folders, intranets, printers, and internal systems.

This project explores **AWS Identity and Access Management (IAM)**, a core AWS service that enables secure control of access to AWS resources. Through this lab, I gained hands-on experience in managing users, groups, and policies while understanding how access permissions are enforced within the AWS environment.

---

## Understanding Aws Iam

AWS Identity and Access Management (IAM) is a global AWS service that allows administrators to securely manage access to AWS resources. IAM enables the creation of users, assignment of permissions, and enforcement of security policies without sharing root account credentials.

IAM operates based on the principle of least privilege, meaning users are granted only the permissions necessary to perform their tasks. This minimizes security risks and ensures tighter control over cloud resources.

--

**The primary goal of this lab was to understand how IAM controls authentication and authorization in AWS. After completing the lab, I was able to:**

- Create and apply an IAM password policy

- Explore pre-created IAM users and user groups

- Inspect IAM policies applied to user groups

- Add users to groups with specific permissions

- Locate and use the IAM sign-in URL

- Test how policies affect access to AWS services

--

## Creating and Applying an IAM Password Policy

The first task involved configuring an IAM password policy. This policy enforces password strength requirements for all IAM users within the account.

I configured the policy to:

- Require a minimum password length

- Include uppercase and lowercase characters

- Require numbers and special characters

- Enforce password expiration

This step reinforced the importance of strong authentication mechanisms in preventing unauthorized access.

<img width ="1000" height="500" alt="instance1" src=


