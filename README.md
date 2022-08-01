# Cohesity vRA/vRO Plugin
=================

## Overview

The **Cohesity vRealize Orchestrator (vRO)** Plugin provides self-service workflows for **Cohesity DataPlatform**. The **vRO plugin** is developed on the **Vmware vRealize Orchestrator** component of the **VMware vRealize Automation**. This plugin uses REST APIs to interact with the **Cohesity DataPlatform**. Using this vRO plugin, you can execute many self service workflows such as Add VM to Protection Group, Restore a VM, Clone a VM and so on. See [Features](#features) for details.

## Table of contents: :scroll:

 - [Prerequisites](https://docs.cohesity.com/api/integrations/vra/software-requirements-vro.htm)
 - [Download](https://github.com/cohesity/cohesity-vra-blueprints/releases)
 - [Installation](https://docs.cohesity.com/api/integrations/vra/install-vro-plugin.htm)
 - [Documentation](https://docs.cohesity.com/api/integrations/vra/concept-vro-plugin-deployment-guide.htm)
 - [Features](#features)
 - [Suggestions and Feedback](#suggest)

## <a name="features"></a> Features: :bulb:
The vRO plugin provides an inventory of objects that you can access on the Inventory tab of the Orchestrator client, along with packages of workflows and actions that you can run on these objects in the inventory to automate the typical use cases of the integrated product.

- **Managing Cohesity Data Operations**: Allows vRO user to perform operations for backups, data protection, restore and clone on Cohesity sources such as Virtual Machines and vCenters.
- **Managing Data with Multiple ESXi Boxes**: Move protected VM/data within protection groups and also clone and restore over different ESXi boxes.
- **Multiple Platform Support**: Management of multiple Cohesity DataPlatform setups.

### vRA supported workflows

| XAAS Workflows                                   | Resource Actions                        |       
| :------------------------                        | :-----------------------------          |
| 1. Add a Protection Source                       | 1. CS - Add VM to protection group      |
| 2. Add Physical Source to Protection Group       | 2. CS - Change protection group         |
| 3. Add Unprotected VM to Protection Group        | 3. CS - Create Snapshot                 |
| 4. Clone Virtual Machine                         | 4. CS - Recover Files or Folders        |
| 5. Delete Protection Group                       | 5. CS - Remove VM from Protection Group |
| 6. Generate Report                               | 6. CS - Restore Virtual Disk            |
| 7. Move VM to new Protection Group               | 7. CS - Restore Virtual Machine         |
| 8. Recover Files or Folders                      |                                         |
| 9. Remove a Protection Source                    |                                         |
| 10. Remove Physical Server from Protection Group |                                         |
| 11. Remove VM from Protection Group              |                                         |
| 12. Restore Virtual Machine                      |                                         |
| 13. Restore Protection on Demand                 |                                         |
| 14. Upgrade Cohesity Agent                       |                                         |


## <a name ="suggest"></a> Questions or Feedback :raised_hand:

We would love to hear from you. Please send your questions and feedback to: *cohesity-api-sdks@cohesity.com*

