# VIAcode Incident Management System for Azure Release Notes

<!-- TOC -->
- [VIAcode Incident Management System for Azure 1.2.0](#viacode-incident-management-system-for-azure-120)
- [VIAcode Incident Management System for Azure initial release](#viacode-incident-management-system-for-azure-initial-release)  
<!-- TOC END -->

## VIAcode Incident Management System for Azure 1.2.0

### Features

- By default Admin user name is admin and password is admin.
- App Service Plan of VIAcode Incident Management System for Azure Web Application was changed to P1V2. It supports backups.
- A new Repeat Count property was added to every ticket, it displays the number of alert repeats.
- Azure Alert status changes to Acknowledged when an incident created in VIMS changes its state to Open.
- A new default group Incoming added, it replaces Users.
- A new designated customer Azure Monitor was added. It connects VIMS to Azure Monitor. All new tickets are created by the customer.
- By default VIMS has Customer and Default SRE Provider shared organizations.
- Added states Delegated and Pending Review for tickets. Customer can set ticket into Pending Review state in place of closing the ticket.
- A new role Connector was added. It has minimal set of privileges just to create and update tickets. Agent role has full access to Incoming group and it is an editor of Knowledge Base. Customer role has access to Incoming group.
- An avatar for Azure Monitor Connector was added.
- My Assigned Tickets overview now displays delegated and pending review tickets. My delegated Tickets overview was added.
- Name Prefix was removed from Settings page.
- Customer doesn't receive notifications.
- Azure Alert severity now affects ticket priority.
- A new [repository](https://github.com/VIAcode/VIAcode-Incident-Management-System) for VIMS.

### Bug-fixes

- Dates in tickets are in 12-hour with AM/PM indication.
- Installation wizard lists only the right locations.
- There are no duplicates and lost alerts anymore.
- Tickets can be created manually.
- A ticket can be created even if Threshold is decimal.
- Broken links are no longer displayed in tickets when an Azure Alert does not have a Resource Group or a resource.
- Minor bug-fixes.

## VIAcode Incident Management System for Azure initial release

VIAcode Incident Management System is a cloud-born ticketing system that combines a powerful incident management engine with out-of-the-box integration with Azure platform. It creates a process around alerts, recommendations and threats in order to foster individual and organizational accountability. It helps visualize operational maturity and compliance.

### Incident Management

- Ability to set SLA for incident types.
- Custom attributes.
- Full text search.
- Knowledge base of Azure best practices.

### Azure integrations

- Ability to escalate incidents to appropriate Azure DevOps projects.
- Ability to execute remediation actions using Azure Automation runbooks.
- Seamless platform integration with Azure portal, Azure Active Directory, Office365.

### Connectors

- Azure Monitor.
- Azure Advisor.
- Azure Sentinel.

### Plans and Pricing

- Core incident management functionality is available for free!
- Check the “Plans” tab to see premium features.
- All premium features are free with [VIAcode Managed Services](https://azuremarketplace.microsoft.com/en-us/marketplace/apps/viacode_consulting-1089577.viacodems?tab=Overview&flightCodes=viacode).

### Deployment Steps

- Follow [the deployment guide](https://github.com/VIAcode/VIAcode-Incident-Management-System-for-Azure/blob/master/VIAcode%20Incident%20Management%20System%20for%20Azure%20deployment%20and%20%D1%81onfiguration%20guide.md).
- Review available Premium Connectors and install it from Azure Marketplace.

**Visit [viacode.com](https://www.viacode.com) for more information.**