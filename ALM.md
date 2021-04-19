# Application Lifecycle Management

*Application is used here in a broader meaning and might include one or more Power Platform components, inlcuding but not limited to Canvas Apps, Model-Driven Apps, Cloud and Desktop Flows, PVA, AI Builder modules as well as external components.*

## General
- What is the preferred method of deployment (managed vs unmanaged solutions)?
- Which external Source Code Control systems do you use (Azure DevOps, GitHub etc.)?
- Which automated ALM do you use (Azure DevOps, GitHub etc.)?
- What internal process do you have to assess the application?
- When should the application be reviewed?
- How can users submit a request for the new application?
- Are applications divided into different types/categories:
    - Which criteria are used?
    - Who is making a decision?
    - How do you collect the data and maintain the list of such applications?
    - How does the applicaiton type define/affect the applicaiton lifecycle?
    - How do you monitor each application type?
- What is the process to delete/archive applications?
- What is the process to move the reference data between environments?


**Below you can find a list of questions you might need to ask, when working with the Application Lifecycle**

## Create New Application
- Who is the application owner?
- Who will maintain/administer the application?
- Who will use the application?
- Where should the application be built (type of environment)?
- Does the application need additional environments for testing?
- How should the application be maintained?
- What components does the application consist of?
- Does the application need a Dataverse database?
- What connectors does the application use?
- Does the application need on-prem data?
- Does the application depend on other Power Platform components?
- What are the security roles for the application?
- Does the application need any data to be migrated?
- How can the users report problems or enhancements?
- How often is the application planned to be updated?

## Change Existing Application
- All questions from the section above.
- Do we need to add new connectors?
- Do we need to update any reference data?
- Do we need to add new components to the application?
- Do we have changes in the Security Roles (eg. how users are assigned or permissions) ?
- Is the existing Dataverse data affected?
- Are new licenses and/or add-ons to be acquired and assigned?

## Delete/Archive Existing Application

