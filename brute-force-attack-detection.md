# Brute Force Attack Detection using Log Analysis

## Scenario
A server is experiencing multiple failed login attempts. As a SOC Analyst, the task is to investigate whether this is a brute force attack.

## Objective
Identify suspicious login attempts from logs.

## Log Sample
Failed password for admin from 192.168.1.15 port 22
Failed password for admin from 192.168.1.15 port 22
Failed password for admin from 192.168.1.15 port 22
Failed password for admin from 192.168.1.15 port 22

## Investigation Steps
1. Reviewed authentication logs.
2. Identified repeated login failures.
3. Checked the source IP address.
4. Counted number of failed attempts.

## Findings
Multiple login failures from the same IP address indicate a possible brute force attack.

## Recommended Actions
- Block the suspicious IP address
- Enable account lockout policy
- Monitor login attempts
- Implement multi-factor authentication

## Tools Used
Linux
Log analysis
Basic threat detection
