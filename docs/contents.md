| [Home](../README.md) |
|----------------------|
# Contents

The **FortiRecon EASM** solution pack contains the following resources:

## Connectors

| Connector Name | Description |
| :-             | :-          |
| Fortinet FortiRecon EASM | Discovers certificate issue for the assets |
| ServiceNow | Creates ServiceNow Ticket |

## Global Variables

| Global Variable | Description                               |
|:----------------|:------------------------------------------|
| `Demo_mode`     | Enables playbook to execute a mock output |

## Record Sets
| Scenario          | Description |
| :-                | :-          |
| Certificate Issue Discovered | Demonstrates the scenario where FortiRecon EASM scan discovers certificate issue for the assets |

## Playbook Collection

| 02 - Use Case - FortiRecon EASM                                          |
|:-------------------------------------------------------------------------|


| Playbook Name                                           | Description                                                                                                  |
|:--------------------------------------------------------|:-------------------------------------------------------------------------------------------------------------|
| Scenario - Discover Certificate Issues                  | Fetches the list of certificate issues related to assets discovered in the most recent FortiRecon EASM scan. |
| > Scenario - Create Assets/Alerts for Certificate Issue | Create and link alert to the asset affected by the certificate issue                                         |
| Certificate Issue Response                              | Creates a ServiceNow incident for the asset with a certificate issue discovered in the FortiRecon EASM scan. |


>**Warning:** We recommend you clone these playbooks before customizing to avoid information loss while upgrading the solution pack.
