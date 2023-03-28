| [Home](../README.md) |
|----------------------------------------------------------------------------------------------------------------------------|

# Installation 
1. To install a solution pack, click **Content Hub** > **Discover**.    
2. From the list of solution pack that appears, search for and select **MITRE ATT&CK&reg; Enrichment Framework**. 
3. Click the **MITRE ATT&CK&reg; Enrichment Framework** solution pack card.    
4. Click the **Install** button on the bottom to begin installation. 

## Prerequisites 
The **MITRE ATT&CK&reg; Enrichment Framework** solution pack depends on the following solution packs.

| Solution Pack Name | Version  | Purpose                                |
|:-------------------|:---------|:---------------------------------------|
| SOAR Framework     |  v2.1.0  | Required for Incident Response modules |
 
# Configuration

You can use the MITRE ATT&CK&reg; Enrichment Framework Solution Pack to map alerts, incidents, and indicators to MITRE tactics and threat actors; and also hunt for specific tactics in your environment using pre-configured playbooks. You can setup the MITRE ATT&CK&reg; Enrichment Framework Solution Pack by setting up data ingestion from the MITRE database using the MITRE ATT&CK&reg; Connector.

The following section contains information on setting up data ingestion.

## Setting up Data Ingestion

The MITRE ATT&CK&reg; Connector leverages the ingestion wizard for seamless ingestion of the MITRE ATT&CK&reg; Framework on a set schedule. The connector also specifies the MITRE ATT&CK&reg; matrix to use for pulling data.

For more information on setting up data ingestion, see the [Configuring MITRE ATT&CK&reg; Connector](https://docs.fortinet.com/document/fortisoar/2.0.1/mitre-att-ck/197/mitre-att-amp-ck-v2-0-1).

>**IMPORTANT**: By default, data ingestion for MITRE is configured with sample data. To get complete MITRE data, please open the connector step from the data ingestion playbook and change the action from "Get MITRE Sample Data" to "Get MITRE Data".