# Incident Response for Phishing Email

## 1. Incident Overview
- **Date of incident**: 21st March, 2025
- **Reported by**: Jane Doe
- **Description**: Employee received a phishing email from a person pretending to be the CEO. They have clicked the link and entered their password.

## 2. Containment Methods
### Step 1: Immediate Containment
- Instruct the employee to disconnect from the network immediately.
- Lock the employee's access to confidential information and systems until the investigation is complete.
- Change the employee's password immediately.

### Step 2: Assessing Scope
- Identify if other employees received same or similar email.
- For **each employee** who received the email:
  - Instruct them to disconnect fromt he network.
  - Lock the employee's access to confidential information and systems until the investigation is complete.
  - Change their passwords immediately.
- Check if any other accounts were compromised.

## 3. Investigation
### Step 1: Gather Evidence
- Collect the phishing email and other related communcations.
- Check the logs for suspicious activity tied to the employee's account.

### Step 2: Analyzing the Phishing Attempt
- Ascertain the source of the phishing email.
- Find out about malware or malicious links that are involved in the attenpt.

## 4. Actions for Compromised Accounts
### Step 1: Containment
- Lock the accounts that have been compromised to prevent unauthorized access.
- Require a password reset for all the compromised accounts.

### Step 2: Remediation
- Identify the vulnerabilities by conducting a security review.
- Additional security mesaures like Multi-Factor Authentication (MFA) needs to be enabled.
- Update the SPF (Sender Policy Framework) records to ensure that only authorized mail servers can send emails on behalf of the domain. 

## 5. Notification
### Internal Notifications
- Notify the affected user, provide them with detailed next steps on how to proceed.
- Alert the IT security team and ensure that they are aware of the incident so that they can proceed with the investigation and response.
- Executives and relevant management need to notified about this incident and need to be told about its potential impact.

### External Notifications
- Notify clients, customers or other third-parties if any kind of sensitive data was accessed, while adhering to compliance regulations. 

## 6. Long-Term Improvements
- Regularly review and update the incident response playbooks based on lessons learned from the incidents.
- Improve the email filtering systems to detect and block phishing emails effectively.
- MFA for all employee accounts should be mandatory.
- Security awareness training should be given to all employees on recognizing phishing attempts and also other security incidents. 
