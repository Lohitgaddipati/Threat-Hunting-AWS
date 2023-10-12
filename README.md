# Threat-Hunting-AWS

Technologies: AWS CloudTrail Lake, AWS GaurdDuty, JasonQuery.

## Introduction to MITRE CLOUD MATRIX
Went through all 11 stages of Mitre Cloud Matrix which include:
  1. Initial Access
  2. Execution
  3. Persistence
  4. Privilege Escalation
  5. Defense Evasion
  6. Credential Access
  7. Discover
  8. Lateral Movement
  9. Collection
  10. Exfiltration and
  11. Impact

## Log Analysis in AWS using CloudTrail

Analyzed different types of visibilities in the cloud, which are the control plane and data plane, along with the Components that make up the CloudTrail logs. 
The CloudTrail logs include:
  1. S3 Bucket: storage logs
  2. Cloud-Watch: this allows us to trigger real-time notifications based on specific activities.
  3. Cloud-Watch logs: logs for advanced or deep analysis
  4. Insights: Visual representation of the data
  5. Encryption: AWS KMS keys to encrypt logs

Here, used JSON Query to go through the logs and analyze them. 
     
Discussed Enumeration (gathering of information about resources done by the bad actor to get a know the resource they have access) and enumeration calls like
  1. 'GET' API Calls -> to retrieve information
  2. 'LIST' API Calls ->to get the list of resources
  3. 'DESCRIBE' API Calls -> to get specific information

## AWS CloudTrail Lake

Used SQL Queries to analyze logs. Also, discussed about
  1. AMI Exfiltration
  2. AWS Access Key Leakage


For more: refer to "Introduction to AWS Threat Hunting" course in LinkedIn Learning by Day Johnson.
