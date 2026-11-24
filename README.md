# RabTech-Internship-Task-02
Description: Cybersecurity Internship - Legal Scope, Asset Inventory and Threat Model
# Legal Scope, Asset Inventory and Threat Model

## Cybersecurity Internship – Task 02

## 1. Project Overview

This project focuses on preparing a controlled cybersecurity
testing environment and documenting its security architecture.

The task includes legal scope definition, asset inventory,
trust boundary identification, data classification,
attack surface identification, STRIDE threat modelling,
Data Flow Diagram creation, and Rules of Engagement.

## 2. Objectives

- Define the testing scope and limitations.
- Identify assets in the lab environment.
- Identify trust boundaries and identities.
- Classify data based on sensitivity.
- Identify potential attack surfaces.
- Analyse potential threats using STRIDE.
- Create a Data Flow Diagram.
- Document Rules of Engagement.

## 3. Lab Environment

| Component | Details |
|---|---|
| Host OS | Windows 11 |
| Virtualization | Oracle VirtualBox |
| Testing OS | Kali Linux |
| Container Platform | Docker |
| Web Application | OWASP Juice Shop |
| Container | juice-shop |
| Local URL | http://127.0.0.1:3000 |
| Port | 3000 |

## 4. Tools Used

- Kali Linux
- Oracle VirtualBox
- Docker
- OWASP Juice Shop
- Firefox
- diagrams.net
- GitHub

## 5. Project Structure

- 01_Authorization
- 02_Asset_Inventory
- 03_Threat_Model
- 04_Data_Flow_Diagram
- 05_Rules_of_Engagement
- 06_Evidence

## 6. Asset Inventory

The asset inventory documents the host laptop, virtual
machine, Docker environment, browser, and local web application.

Refer to:
02_Asset_Inventory/asset-inventory.csv

## 7. Threat Modelling

The project uses the STRIDE methodology.

- Spoofing
- Tampering
- Repudiation
- Information Disclosure
- Denial of Service
- Elevation of Privilege

The threats documented are potential risks and are not
confirmed vulnerabilities.

## 8. Data Flow Diagram

The DFD represents communication between the tester,
browser, Docker port mapping, Juice Shop application,
and its logical data store.

Refer to:
04_Data_Flow_Diagram/

## 9. Rules of Engagement

Testing is restricted to the locally created OWASP Juice Shop
lab. Public websites, college networks, and third-party
systems are outside the scope.

Refer to:
05_Rules_of_Engagement/rules-of-engagement.txt

## 10. Evidence

Screenshots of the actual lab environment and project
documentation are stored in the 06_Evidence folder.

## 11. Learning Outcomes

Through this task, I learned:

- How to define a cybersecurity testing scope.
- How to identify and document assets.
- How to understand trust boundaries.
- How to classify application data.
- How to identify potential attack surfaces.
- How to use STRIDE for threat modelling.
- How to create a Data Flow Diagram.
- Why Rules of Engagement are important.

## 12. Conclusion

This task provided practical experience in preparing a
controlled cybersecurity lab and documenting its security
architecture.

It helped me understand the importance of scope definition,
asset identification, threat analysis, and ethical testing.

---

**Project Type:** Educational Cybersecurity Lab

**Internship Task:** Task 02
