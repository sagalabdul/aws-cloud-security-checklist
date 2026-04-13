# ✅ AWS Cloud Security & GDPR Audit Checklist

> Use this checklist to audit your AWS environment for security best practices and GDPR compliance.

---

## 🔑 1. Identity & Access Management (IAM)

- [ ] MFA is enabled for all users including root account
- [ ] Root account is not used for day-to-day tasks
- [ ] IAM roles are used instead of long-term access keys
- [ ] Least privilege principle is applied to all policies
- [ ] IAM policies are reviewed and updated regularly
- [ ] Role-Based Access Control (RBAC) is implemented
- [ ] Unused IAM users and roles are removed
- [ ] AWS Cognito is used for end-user authentication

---

## 🔐 2. Data Encryption

- [ ] All data is encrypted at rest using AWS KMS
- [ ] All data is encrypted in transit using HTTPS/TLS
- [ ] S3 buckets have encryption enabled by default
- [ ] RDS databases are encrypted with KMS
- [ ] Encryption keys are rotated regularly
- [ ] AWS Secrets Manager is used for credentials and API keys
- [ ] No sensitive data is stored in plain text anywhere

---

## 🌐 3. Network Security

- [ ] VPC is configured with public and private subnets
- [ ] Databases are placed in private subnets only
- [ ] Security Groups follow least privilege port access
- [ ] Network ACLs are configured as an additional layer
- [ ] AWS WAF is deployed at the edge
- [ ] AWS Shield is enabled for DDoS protection
- [ ] NAT Gateway is used for outbound private subnet traffic
- [ ] No resources are publicly exposed unnecessarily

---

## 📡 4. Monitoring & Logging

- [ ] AWS CloudTrail is enabled across all regions
- [ ] AWS CloudWatch alarms are configured for security events
- [ ] AWS GuardDuty is enabled for threat detection
- [ ] AWS Security Hub is enabled for centralised alerts
- [ ] Logs are stored securely and retained for required period
- [ ] Alerts are set up for unauthorised access attempts
- [ ] Regular log reviews are conducted

---

## 📋 5. GDPR Compliance

- [ ] All PII data is identified and documented
- [ ] PII is encrypted, access controlled and logged
- [ ] Users can request deletion of their data
- [ ] Data retention policies are defined and enforced
- [ ] Data processing activities are documented
- [ ] A Data Protection Officer (DPO) is appointed if required
- [ ] An incident response plan is in place
- [ ] Staff are trained on GDPR and data handling
- [ ] Third party data processors are reviewed for compliance
- [ ] Privacy policy is up to date and accessible to users

---

## 🏗️ 6. AWS Architecture Best Practices

- [ ] AWS Well-Architected Framework has been reviewed
- [ ] Multi-AZ is enabled for high availability
- [ ] Auto Scaling is configured for resilience
- [ ] Regular backups are automated and tested
- [ ] Disaster recovery plan is documented and tested
- [ ] Cost and usage alerts are configured
- [ ] Infrastructure is documented and version controlled

---

## 📅 Audit Log

| Date | Auditor | Area Reviewed | Notes |
|---|---|---|---|
| | | | |
| | | | |

---

<div align="center">

*Use this checklist regularly to maintain a secure and compliant AWS environment*

</div>
