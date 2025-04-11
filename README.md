# CODTECH Internship - Task 4: Cloud Security

##  Objective
Implement cloud security features on AWS using IAM policies, S3 bucket configuration, and server-side encryption.

## Tools Used
- AWS S3 (Secure bucket + SSE-S3 encryption)
- AWS IAM (Custom policy and user)
- AWS CLI (for testing access)

##  Key Actions
- Created a private S3 bucket `secure-storage-usha`
- Enabled server-side encryption using SSE-S3
- Created IAM policy (`S3ReadOnlyPolicy`) with `s3:GetObject` and `s3:ListBucket`
- Created `readonly-user` and attached the policy
- Tested read and write access using AWS CLI

##  Report
See `Task4_Report.pdf` for screenshots and step-by-step documentation.

##  Outcome
IAM user can read but **cannot delete or upload**, proving the policy and encryption work as intended.
