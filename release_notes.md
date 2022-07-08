# What's New

- The solution pack has been renamed from *MITRE ATT&CK* to *MITRE ATT&CK Enrichment Framework*
- Changes in *Techniques* and *Sub-techniques* Module
  - Added record uniqueness condition on ‘MITRE ID’ in Techniques and Sub-Technique Module
  - Configured the below fields as a ‘Default Grid Column’ in both Techniques and Sub-Technique Module
    - MITRE ID
    - Name
    - Description

- Removed the following Hunt Playbook collections from the solution pack
  - 13 - MITRE ATT&CK™ - Access Token Manipulation
  - 13 - MITRE ATT&CK™ - Boot or Logon Autostart Execution
  - 13 - MITRE ATT&CK™ - Credential Access
  - 13 - MITRE ATT&CK™ - Defence Evasion
  - 13 - MITRE ATT&CK™ - Event Triggered Execution
  - 13 - MITRE ATT&CK™ - Process Execution
  - 13 - MITRE ATT&CK™ - Signed Binary Proxy Execution
  - 13 - MITRE ATT&CK™ - System Services
  - 13 - MITRE ATT&CK™ - Modulars
  - 13 - MITRE ATT&CK™ - Link Techniques to Alerts and Incidents

- Added the following MITRE related modules in the Navigation view by default. Setting up the Navigation View manually for MITRE modules is no longer required
  - Groups
  - Mitigations
  - Software
  - Sub-techniques
  - Techniques
  - Tactics

- Bug Fix for MITRE ATT&CK Connector configuration
  - The Health Check of MITRE Connector used to remain disconnected after solution pack deployment, the error has been fixed in this release of SP and the connector health check show ‘Available’ post-deployment