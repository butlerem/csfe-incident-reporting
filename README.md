# SmartMeter Co. Incident Report

**Prepared by:** Emma Butler  
**Date:** November 10, 2024  

## Executive Summary

This report is a project created as part of the Cybersecurity for Energy program. The incident, findings, and recommendations do not represent an actual event or organization.

On December 14, 2023, SmartMeter Co. experienced a high-severity phishing attack targeting key employees. A deceptive email led victims to a malicious website where credentials were entered, granting attackers unauthorized access to the company's email server and file systems. Sensitive data, including intellectual property, was potentially exfiltrated. 


### Contributing Factors:
1. Lack of **email filtering**.
2. Absence of **multi-factor authentication (MFA)**.
3. Insufficient **phishing awareness training**.

### Key Recommendation:
Implementing **MFA** is the top priority to mitigate credential compromise risks.

---

## Incident Details

- **Attack Description:** Phishing email disguised as a trusted source led employees to a malicious site, capturing credentials.  
- **Date and Time:** December 14, 2023  
- **Severity:** High – Access to critical files and credentials exposed.

### Root Cause Analysis
1. **Log Observations:**  
   - Credentials entered on a malicious webpage.  
   - Critical files accessed and potentially exfiltrated.

2. **Interviews:**  
   - Employees, including senior staff, misled by urgency and design of the phishing email.  
   - Users failed to verify URLs or recognize poor-quality email graphics.

3. **Attack Vector:** Phishing email targeting credential input.  
4. **Intrusion Point:** Email server compromised through captured credentials.

---

## Failed Controls

1. Lack of **email filtering** to detect phishing attempts.  
2. Absence of **multi-factor authentication (MFA)** to prevent unauthorized access after credential theft.

---

## Recommendations

| **Recommendation**                          | **Priority** | **Purpose**                                                |
|---------------------------------------------|--------------|------------------------------------------------------------|
| Implement **Multi-Factor Authentication**   | Critical      | Prevent unauthorized access even if credentials are compromised. |
| Conduct **Phishing Awareness Training**     | High          | Educate employees to identify and avoid phishing attempts. |
| Enhance **Email Security Filters**          | High          | Detect and flag phishing emails with suspicious content.   |

---

## About the Project

This fictional project demonstrates skills in incident analysis, root cause identification, and cybersecurity recommendations. It was developed as part of the Cybersecurity for Energy program.

