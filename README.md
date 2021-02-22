# DXdao Security Board

The goal with this [Kanban board](https://github.com/nicoelzer/dxdao-security/projects/1) is to coordinate & streamline the security operations of DXdao.

Workers responsible for the Security Operations are executing daily tasks such as:

 - Monitoring & screening new proposals
 - Executing a daily security audits of all open proposals
 - Communicate any noticeable issue with proposals to Governance leaders

## Kanban Board

Any proposal is assigned to one of the following stages:

 - **📥 ToDo**: Open proposals to be screened
 - **📋 Daily Security Audit**: History of all performed Security audits
 - **❌ Rejected**: Malicious proposals that need to be carefully monitored
 - **✅ Approved**: Proposals that are good to pass (Proposals at this stage won't be monitored)
 - **Closed Proposals**: Proposals that have been executed (Either passed or failed)


## Workflow

### New Proposals

 - New proposals are automatically pushed in a 5 minute frequency by the [Security Bot](https://github.com/nicoelzer/dxdao-security-bot) to the Kanban board with the stage "ToDo"
 - The card contains all of the necessary information to screen the proposal
 - Once you screened the proposal you assign (Shortkey "a") it to yourself to signal you performed the screening (shown as avatar icon).
 - Depending on your decision:
	 - If you decide the proposal looks malicious,  move it directly to "Rejected" and communicate it to the Keybase security group
	 - If you decide the proposal can pass you can move it to "Approved" as long as one other worker approved it before as well


### Security Audit

 - The daily Security Audit is pushed as task to the "ToDo" line every day
 - The steps to be performed can be found in the task itself
 - Once you performed all the steps you move the task to the top of the  "Daily Security Audit" line & assign it yourself to show you executed the security audit