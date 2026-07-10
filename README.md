
# Basic Employee Onboarding (AD)(RBAC)

## Problem Statement
The problem statement in this project was related to a fictional company called GLNSP Medical Group. The company relied on a third-party Managed Service Provider (MSP) to manage its identity lifecycle workflows.The arrangement worked well in the beginning. As the company expanded across multiple departments, issues began to show. Because the organization had not established Role-Based Access Control (RBAC) policies, user access was assigned inconsistently, and there was NO Audit trails.These gaps increased compliance risks, and potential violations. 

## Solution Overview

The solution was to build out a basic employee onboarding pipeline in active directory. I set up the RBAC Mmatrix and ensured users were given access ONLY according to their role. I simulated a mock ticket where a user was provisioned the incorrect level of access.

## Video Walkthrough
[Add your video walkthrough link placeholder here. You will record this tomorrow and update this link so visitors can see a live demonstration of your lab environment.]

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built GLNSP.local domain from scratch
* Solved a mock ticket where a user was given incorrect access
* I fully documented my steps end-to-end
