---
layout: default
title: Home
---

# DSC180AB Modular Threat Model Privacy Dataflow 
Max Yuen Sum Wong
y6wong@ucsd.edu

Wally Zi Chen Yu
ziy015@ucsd.edu

Chris Yuen Kei Wong 
ykw001@ucsd.edu



## Section and Mentor
Section B09  
Mentor: Hao Jian Jin

---

## Introduction
Privacy design decisions in software development often follow an informal and unstructured process. Managers and engineers typically start with high-level privacy principles, such as avoiding the collection of user data without consent or minimizing data retention to reduce risk, but their translation into low-level design choices is frequently guided by intuition rather than systematic evaluation. This gap leads to inconsistencies and missed opportunities for optimizing user privacy.

To address this challenge, we propose PrivacyVerb, a new privacy design framework that helps practitioners systematically explore the privacy-related design space and make informed decisions. PrivacyVerb introduces a reusable, verb-centric approach to privacy threat modeling, shifting away from the conventional case-by-case, noun-centric design process. By abstracting privacy-relevant actions into structured verb-based units across data flows, stakeholder interactions, and individual design choices, PrivacyVerb enables practitioners to systematically compare and reuse privacy decisions. This approach improves efficiency, consistency, and accessibility, making privacy engineering more scalable and reducing the expertise needed to design privacy-sensitive data practices.

## Modular Nodes

### Data Action
A specific operation that developers perform on users' data.


Capture:
- Definition: Capture users' data or sensor inputs
- Example: Capture participant focuses from attention tracking mechanism
- Template: Capture “data type” from “types of device/ types of service”


Share:
- Definition: Share users’ data to different parties.
- Example: Share participant inactivity to Host
- Template: Share “data type” to “third-party/ somewhere” (with “methods”)

Store:
- Definition: Keep users' data in a persistent storage system
- Example: Store attendance data in cloud with encryption
- Template: Store “data type” in “persistent storage system” with/without encryption

Process:
- Definition: Process users’ data to derive new information
- Example: Process desktop info to inactivity status
- Template: Process “data type” to “certain extent of result” (with “techniques of data processing”)


### Stakeholder Interaction
Stakeholder: Any individual, group, or entity that is involved in or affected by data actions.
Stakeholder interaction: A specific way that stakeholders engage with or are affected by data actions.

Consent:
- Definition: A data subject gives permission for specific data actions
- Example: Consent to academic research
- Template: Consent to “purpose (noun)”

Influence:
- Definition: A data beneficiary/victim is impacted by a data practice
- Example: Influence user due to Advertisement 
- Template: Influence “stakeholder” due to “consequences that affect the subject”.

Request:
- Definition: A data subject asks to exercise their data rights
- Example: Request deletion on user’s inactivity status
- Template: Request “data retention” on “data type”.

Audit:
- Definition: An auditor examines data actions for compliance with policies or regulations
- Example: Audit user info for GDPR
- Template: Audit “data type” for “compliance policy”.

Notify:
- Definition: A data observer informs data subjects about specific aspects or status of data actions.
- Example: Notify Non-Consent Humans about data capturing
- Template: Notify “stakeholder” about “data action” (via “notification method”).

Access:
- Definition: A data observer accesses and uses user data or derived data for a specific purpose
- Example: Access user’s friend connection from GSR for advertisement
- Template: Access “data type” from “source” for “purpose”.

Control:
- Definition: A data subject controls settings that determine how their data is stored or processed 
- Example: Control opt-out option on attention tracking mechanism
- Template: Control “data retention/ data preferences” on “data type/service”

## Modular Combination
todo


## Thread Modeling Background
**What is Threat Modeling?**
Threat modeling is the process of identifying and assessing potential security threats, vulnerabilities, and risks within a system. It allows organizations to anticipate privacy and security risks and develop mitigation strategies accordingly.

**Purpose of Threat Modeling**
The primary goal of threat modeling is to provide a structured approach to analyzing privacy risks. This includes:
1. Identifying threats that could exploit vulnerabilities in a system.
2. Understanding how privacy risks impact individuals and organizations.
3. Establishing a privacy risk management framework to facilitate proactive risk mitigation

## Our Thread Modeling based on Modular Dataflow Diagram

## More Features

### Property Layer

### Canvas Layer

### Thread Table

### Simplified Graph







### Actual Page of the Application 

[PrivacyVerb Application](https://privacyio-web-n87a.vercel.app/)

---


### Todo in the future
1. Scientifically test privacy design choices through empirical evaluation rather than relying on intuition.
2. Iterate and refine these decisions based on structured feedback and evidence.
3. Dynamic Thread Modeling Result
4. Using Akinator to generate the data flow. 
