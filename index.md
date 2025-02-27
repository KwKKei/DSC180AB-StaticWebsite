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

### Data Action
A specific operation that developers perform on users' data.


- Capture: Capture users' data or sensor inputs
- Share: Share users’ data to different parties.
- Store: Keep users' data in a persistent storage system
- Process: Process users’ data to derive new information

### Stakeholder Interaction
Stakeholder: Any individual, group, or entity that is involved in or affected by data actions.
Stakeholder interaction: A specific way that stakeholders engage with or are affected by data actions.

- Consent: A data subject gives permission for specific data actions
- Influence:: A data beneficiary/victim is impacted by a data practice
- Request: A data subject asks to exercise their data rights
- Audit: An auditor examines data actions for compliance with policies or regulations
- Notify: A data observer informs data subjects about specific aspects or status of data actions.
- Access: A data observer accesses and uses user data or derived data for a specific purpose
- Control: A data subject controls settings that determine how their data is stored or processed 


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
