| [Home](../README.md) |
| -------------------- |

# Contents

## Connector

| Name              | Description                                                                                                                                                      |
| :---------------- | :--------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| MITRE ATT&CK&reg; | Facilitates replication of adversary tactics and techniques knowledge base on FortiSOAR&trade; with the MITRE ATT&CK&reg; knowledge base which details the real-world observations |

>**WARNING:** After deployment, this solution pack installs or upgrades the connector to the latest version.

## Modules

| Name           | Description                                                                                                                                                                                                                                                                |
| :------------- | :------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Groups         | Captures and displays information related to similar intrusion activities tracked by a common name in the security community                                                                                                                                   |
| Mitigation     | Creates records of security concepts and classes of technologies that can be used to prevent a technique or sub-technique from being successfully executed                                                                                                     |
| Software       | Creates records of custom or commercial code, operating system utilities, open-source software, or other tools used to conduct behavior modeled in ATT&CK                                                                                                     |
| Techniques     | Creates records that represent *how* an adversary achieves a tactical goal by performing an action. E.g. *Abuse Elevation Control Mechanism* is a set of circumventing mechanisms designed to control elevate privileges for gaining higher-level permissions. |
| Sub-techniques | Sub-techniques are smaller actions used by an adversary to achieve the larger result targeted by a particular technique. For example, *Abuse Elevation Control Mechanism* is technique that requires a sub-technique of *bypassing User Account Control*                   |
| Tactics        | Tactics represent the *why* of an ATT&CK technique or sub-technique. For example, in the tactic *Reconnaissance*, the adversary tries to gather information they can use to plan future operations                                                                         |

## Role

| Role                 | Description                                                    |
| :------------------- | :------------------------------------------------------------- |
| Full App Permissions | Create, Read, Update, and Delete permissions for MITRE modules. |

## Dashboard

| Name                  | Description            |
| :-------------------- | :--------------------- |
| MITRE ATT&CK Matrices | Displays MITRE Matrices which are visual representations to evaluate and compare tools, techniques, and Sub-techniques of adversaries |

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
| Correlate MITRE ATT&CK Data<sup>New</sup>      | Link MITRE ATT&CK data with Alert or Incident on the basis of Technique ID                       |
| Link ATT&CK Technique to Alert (On Create)    | Links MITRE technique or sub-technique to an alert, when a Technique ID is added                 |
| Link ATT&CK Technique to Alert (On Update)    | Links MITRE technique or sub-technique to an alert, when a Technique ID is updated or changed    |
| Link ATT&CK Technique to Incident (On Create) | Links MITRE technique or sub-technique to an incident, when a Technique ID is added              |
| Link ATT&CK Technique to Incident (On Update) | Links MITRE technique or sub-technique to an incident, when a Technique ID is updated or changed |

| [Installation](./setup.md#installation) | [Configuration](./setup.md#configuration) | [Usage](./usage.md) |
|-----------------------------------------|-------------------------------------------|---------------------|