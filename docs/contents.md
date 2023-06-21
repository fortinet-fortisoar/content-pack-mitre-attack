| [Home](../README.md) |
| -------------------- |

# Contents

## Connector

| Name              | Description                                                                                                                                              |
| :---------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------- |
| MITRE ATT&CK&reg; | Helps replicate knowledge base of adversary tactics and techniques based on real-world observations as described in the MITRE ATT&CK&reg; knowledge base |

>**WARNING:** After deployment, this solution pack installs or upgrades the connector to the latest version.

## Modules

| Name           | Description                                                                                                                                                                                                                                                                |
| :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Groups         | This module captures and displays information related to similar intrusion activities tracked by a common name in the security community.                                                                                                                                  |
| Mitigation     | This module creates records of security concepts and classes of technologies that can be used to prevent a technique or sub-technique from being successfully executed.                                                                                                    |
| Software       | This module creates records of custom or commercial code, operating system utilities, open-source software, or other tools used to conduct behavior modeled in ATT&CK.                                                                                                     |
| Techniques     | This module creates records that represent *how* an adversary achieves a tactical goal by performing an action. E.g. *Abuse Elevation Control Mechanism* is a set of circumventing mechanisms designed to control elevate privileges for gaining higher-level permissions. |
| Sub-techniques | Sub-techniques are smaller actions used by an adversary to achieve the larger result targeted by a particular technique. For example, *Abuse Elevation Control Mechanism* is technique that requires a sub-technique of bypassing User Account Control                     |
| Tactics        | Tactics represent the *why* of an ATT&CK technique or sub-technique. For example, in the tactic *Reconnaissance*, the adversary tries to gather information they can use to plan future operations.                                                                        |

## Role

| Role                 | Description                                                                       |
| :------------------- | :-------------------------------------------------------------------------------- |
| Full App Permissions | Create, Read, Update and Delete permissions for Scans and Vulnerabilities modules |
| Mitre Admin          | Create, Read, Update and Delete permissions for MITRE ATT&CK&reg; modules         |

## Dashbaord

| Name                  | Description            |
| :-------------------- | :--------------------- |
| MITRE ATT&CK Matrices | Display MITRE Matrices |

## Widget

| Name                               | Description                                                                |
| :--------------------------------- | :------------------------------------------------------------------------- |
| MITRE ATT&CK Alert Incident Spread | Detailed table view of Alerts and Incidents linked to MITRE ATT&CK records |

## View Template

- MITRE ATT&CK

## Playbook Collection

| 10 - SP - MITRE ATT&CK&reg; Enrichment Framework |
| :----------------------------------------------- |

| Playbook Name                                 | Description                                                                                      |
| :-------------------------------------------- | :----------------------------------------------------------------------------------------------- |
| Get MITRE ATT&CK Data<sup>New<sup>                         | Link MITRE ATT&CK data on the basis of Technique ID                                              |
| Link ATT&CK Technique to Alert (On Create)    | Links MITRE technique or sub-technique to an alert, when a Technique ID is added                 |
| Link ATT&CK Technique to Alert (On Update)    | Links MITRE technique or sub-technique to an alert, when a Technique ID is updated or changed    |
| Link ATT&CK Technique to Incident (On Create) | Links MITRE technique or sub-technique to an incident, when a Technique ID is added              |
| Link ATT&CK Technique to Incident (On Update) | Links MITRE technique or sub-technique to an incident, when a Technique ID is updated or changed |