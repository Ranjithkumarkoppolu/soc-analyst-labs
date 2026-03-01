# SOC Alert Investigation – Suspicious Login Activity

## Alert Details
Alert Name: Multiple Failed Login Attempts  
Severity: Medium  
Source IP: 192.168.1.20  
Target System: Linux Server  

## Objective
Investigate suspicious login attempts and determine if it is malicious activity.

## Investigation Process

### Step 1 – Review Alert
The monitoring system generated an alert after detecting multiple failed login attempts.

### Step 2 – Check Authentication Logs
Log entries showed repeated login failures from the same IP address.

### Step 3 – Analyze Source IP
The IP address attempted multiple logins within a short period of time.

### Step 4 – Identify Attack Pattern
This behavior is commonly seen in brute force attacks.

## Conclusion
The activity is suspicious and likely a brute force attempt.

## Recommended Actions
- Block the IP address
- Enable account lockout policy
- Monitor future login attempts
- Enable MFA

## Skills Demonstrated
Log analysis  
Threat detection  
Security investigation
