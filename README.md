# TASK-15
Task 15: Vulnerability Assessment & Risk Prioritization
Overview

This project demonstrates the process of identifying, analyzing, and prioritizing security vulnerabilities using vulnerability scanning tools such as Nessus Essentials or OpenVAS. The objective is to improve system security by detecting weaknesses and recommending remediation steps.

Objective

Identify vulnerabilities in the target system

Analyze vulnerabilities using CVE and CVSS scores

Classify vulnerabilities based on severity

Prioritize vulnerabilities based on risk

Recommend remediation measures

Tools Used

Primary Tool:

Nessus Essentials

Alternative Tool:

OpenVAS

Target System:

Ubuntu Linux / Kali Linux

Reference Databases:

NVD (National Vulnerability Database)

CVSS Scoring System

Scope

Target:

Linux system running SSH and network services

Scan Type:

Basic Network Scan

Vulnerability Assessment Scan

Procedure
Step 1: Define Scope

Selected Linux system as target

Identified IP address of system

Step 2: Configure Scanner

Configured Nessus/OpenVAS scan profile

Enabled vulnerability detection plugins

Enabled CVE and CVSS mapping

Step 3: Run Vulnerability Scan

Started vulnerability scan

Waited for scan completion

Step 4: Analyze Results

Reviewed vulnerability severity levels:

Critical

High

Medium

Low

Step 5: Map CVE and CVSS

Identified CVE IDs

Reviewed CVSS scores

Step 6: Risk Prioritization

Prioritized vulnerabilities based on:

Severity

Exploitability

System impact

Risk Priority List
Priority	Vulnerability	Severity
1	Firewall Disabled	Critical
2	Outdated Packages	Critical
3	OpenSSH Vulnerability	High
4	Open Ports	Medium
5	Weak SSH Configuration	Medium
Remediation Steps

Enable firewall (UFW)

Update system packages

Secure SSH configuration

Close unused ports

Apply security patches

Outcome

Vulnerabilities successfully identified

Risk prioritized based on CVSS

Security improvements recommended

Skills Gained

Vulnerability scanning

Risk analysis

CVE and CVSS understanding

Security risk prioritization
