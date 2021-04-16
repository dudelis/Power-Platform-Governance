# Environment Strategy


## Overview
- How do you use your Default Environment?
- What other types of environments do you have?
- What is the purpose of each environment type?
- Do environments have database (for each type)?
- What can users do/create in each of the environment type?
- Who can create Trial and/or Production Environments?
- What are your environment drivers (per application, per team. per department, per geographic location etc.)?

## Environment Lifecycle
- Who can create environments?
- How can a user request an environment?
- How do you decide, if a user needs and environment?
- When should the environment be deleted?
- Who can delete environments?
- What is the process to delete the environment?
- How do you monitor existing environment?

## Envrionment Security (should be described for each type)
- Who can access environments?
- Who can administer the environments?
- Which Security Roles are granted for the users?
- Can Service Accounts be used within different environment types?
    - How can a user request a service account?
    - When should we license the service accounts?
    - How can a user work as a service account?
    - How should service account be used for connections?

## Data Loss Prevention Policy
- What is the default behavior for new connectors?
- What are common blocked connectors?
- Which global Data Loss Prevention Policies are created?
- What is the default Data Loss Prevention policy for newly created environments?
- How are different Data Loss Prevention Policies applied to each environment type?
- Which connectors are allowed for each environment types?
- How are the exceptions handled?
- What is the process to request a specific connector?
- How are custom connectors covered by the Data Loss Prevention Policies?
- What is the process to request and review a Custom connector?
- Are these processes automated?
- How often are the Policies reviewed?

## Dataverse for Teams
- Is Dataverse for teams enabled for the tenant?
- Which Data Loss Prevention policies apply to the newly created Teams Environments?
- Should the users provide justification about the necessity of the Teams environment?
- How are these environments are monitored?
- What are typical limitations for Dataverse for Teams environments?
- What are typical use cases for Dataverse for Teams environments?
- What is the process to review such Environments?
- What is the process to convert Dataverse for Teams to Production environments?
