# MITRE ATT&CK Enrichment Framework Solution Pack

## What's new in the MITRE ATT&CK Enrichment Framework Solution Pack v2.0.2

- The solution pack has been renamed from ‘MITRE ATT&CK Solution Pack’ to ‘MITRE ATT&CK Enrichment Framework Solution Pack’
- Changes in Techniques and Sub Techniques Module
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

## Setting up the MITRE ATT&CK Solution Pack

You can use the MITRE ATT&CK Enrichment Framework Solution Pack to map alerts, incidents, and indicators to MITRE Tactics and Threat Actors; and also hunt for specific tactics in your environment using pre-configured playbooks. You can setup the MITRE ATT&CK Enrichment Framework Solution Pack as follows:

- Ensure that SOAR Framework solution pack is deployed.
- Setup data ingestion for the MITRE database using the MITRE ATT&CK Connector.

## Setting up Data Ingestion

The MITRE ATT&CK Connector leverages the ingestion wizard for seamless ingestion of the MITRE ATT&CK Framework on a set schedule and also provide inputs that specify which MITRE ATT&CK matrix should be used for pulling the data. For more information on setting up data ingestion, see the [MITRE ATT&CK](https://docs.fortinet.com/document/fortisoar/2.0.1/mitre-att-ck/197/mitre-att-amp-ck-v2-0-1) connector document that is included in the [FortiSOAR Connectors](https://docs.fortinet.com/fortisoar/connectors) listing page.

**Important**: By default, data ingestion for MITRE is configured with sample data. To get complete MITRE data, please open the connector step from the data ingestion playbook and change the action from "Get MITRE Sample Data" to "Get MITRE Data".
