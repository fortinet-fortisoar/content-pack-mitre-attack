| [Home](https://github.com/fortinet-fortisoar/solution-pack-mitre-attack-enrichment-framework/blob/develop/README.md) | 
|--------------------------------------------|

# Contents

## Connector

| Name         | Description                                                                                                                                         |
|:-------------|:----------------------------------------------------------------------------------------------------------------------------------------------------|
| MITRE ATT&CK | Helps replicate knowledge base of adversary tactics and techniques based on real-world observations as described in the MITRE ATT&CK knowledge base |

>**Warning:** After deployment, this Solution Pack installs or upgrades the connector to the latest version.

## Modules

| Name           | Description                                                                                                                                                                                                                                                                |
|:---------------|:---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| Groups         | This module captures and displays information related to similar intrusion activities tracked by a common name in the security community.                                                                                                                                  |
| Mitigations    | This module creates records of security concepts and classes of technologies that can be used to prevent a technique or sub-technique from being successfully executed.                                                                                                    |
| Software       | This module creates records of custom or commercial code, operating system utilities, open-source software, or other tools used to conduct behavior modeled in ATT&CK.                                                                                                     |
| Techniques     | This module creates records that represent *how* an adversary achieves a tactical goal by performing an action. E.g. *Abuse Elevation Control Mechanism* is a set of circumventing mechanisms designed to control elevate privileges for gaining higher-level permissions. |
| Sub-techniques | Sub-techniques are smaller actions used by an adversary to achieve the larger result targeted by a particular technique. For example, *Abuse Elevation Control Mechanism* is technique that requires a sub-technique of bypassing User Account Control                     |
| Tactics        | Tactics represent the *why* of an ATT&CK technique or sub-technique. For example, in the tactic *Reconnaissance*, the adversary tries to gather information they can use to plan future operations.                                                                        |

## Role

| Role                 | Description                                                                       |
|:---------------------|:----------------------------------------------------------------------------------|
| Full App Permissions | Create, Read, Update and Delete permissions for Scans and Vulnerabilities modules |
| Mitre Admin          | Create, Read, Update and Delete permissions for Mitre Att&ck modules              |

## View Template

- MITRE ATT&CK
