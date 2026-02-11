# Project 4: Active Directory Group Policy Management

## Project Overview
This project demonstrates the creation and application of Group Policy Objects (GPOs) in an Active Directory environment to enforce user security restrictions. The goal is to centralize policy management and control user access to system settings.

## Tools Used
- Windows Server (Active Directory Domain Services)
- Group Policy Management Console (GPMC)
- Command Prompt

## What Was Configured
- Created a new GPO named **User Security Restrictions Policy**
- Enabled the policy **Prohibit access to Control Panel and PC settings** for domain users
- Linked the GPO to the domain
- Forced a policy update to confirm changes

## Screenshots
### Screenshot 1
![GPO Created and Linked](screenshots/01-gpo-created-linked.png)  
*Group Policy Object ‘User Security Restrictions Policy’ created and linked to the domain, ready to enforce user restrictions.*

### Screenshot 2
![Control Panel Policy Enabled](screenshots/02-disable-control-panel-gpo.png
)  
*Policy enabled to prohibit access to Control Panel and PC settings for domain users, demonstrating centralized user security restrictions.*

### Screenshot 3
![GPUpdate Command](screenshots/04-gpupdate-command.png)  
*Command prompt showing `gpupdate /force` success, confirming that the Group Policy Object has been applied to the domain environment.*

## What This Demonstrates
- Ability to create and link GPOs in an Active Directory environment  
- Enforcing security policies centrally for domain users  
- Testing and validating policy application using GPUpdate  
- Basic portfolio-ready screenshot documentation

