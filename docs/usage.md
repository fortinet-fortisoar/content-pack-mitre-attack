| [Home](../README.md) | 
|----------------------|

# Usage

With MITRE ATT&CK&reg; Enrichment Framework, you can configure and schedule data ingestion using the MITRE ATT&CK&reg; connector. This connector fetches latest information about groups, mitigation, software, techniques and other information and places them in the appropriate modules.

1. Navigate to **MITRE ATT&CK** > **Groups** to view an exhaustive list of threat groups.
    - Click a *Group* to view more information about it
    - Under the tab **Related Records** you can check the following tabs
        - **Techniques** - Lists the techniques that the selected group uses
        - **Software** - Lists software that the selected group uses

2. Navigate to **MITRE ATT&CK** > **Mitigation** to view a list of mitigation measures in place.
    - Click a *Mitigation* measure to view more information about it
    - Under the tab **Related Records** you can check the following tabs
        - **Techniques** - Lists the techniques that the selected mitigation method addresses
        - **Sub-techniques** - Click a technique to view the sub-techniques that the selected mitigation method addresses
        - **Alerts** - Lists any alerts of type **MITRE ATT&CK** detected during data ingestion
        - **Incidents** - Lists MITRE ATT&CK&reg; alerts escalated to incidents

3. Navigate to **MITRE ATT&CK** > **Software** to view a list of malicious software used for a MITRE ATT&CK&reg;.
    - Click a *Software* to view more information about it
    - Under the tab **Related Records** you can check the following tabs
        - **Groups** - Lists the groups that use the selected malicious software
        - **Techniques** - Lists the techniques that the selected software uses
        - **Sub-techniques** - Lists the techniques that the selected software uses
        - **Alerts** - Lists any alerts of type **MITRE ATT&CK** detected during data ingestion
        - **Incidents** - Lists MITRE ATT&CK&reg; alerts escalated to incidents

4. Navigate to **MITRE ATT&CK** > **Techniques** to view a list of techniques used for a MITRE ATT&CK&reg;.
    - Click a *Technique* to view more information about it
    - Under the tab **Related Records** you can check the following tabs
        - **Alerts** - Lists any alerts of type **MITRE ATT&CK** detected during data ingestion
        - **Incidents** - Lists MITRE ATT&CK&reg; alerts escalated to incidents
        - **Sub-techniques** - Lists the sub-techniques that categorized under the selected technique

5. Navigate to **MITRE ATT&CK** > **Sub-techniques** to view a list of sub-techniques used for a MITRE ATT&CK&reg;.
    - Click a *Sub-technique* to view more information about it
    - Under the tab **Related Records** you can check the following tabs
        - **Software** - Lists software that exploit the selected sub-technique
        - **Alerts** - Lists any alerts of type **MITRE ATT&CK** detected during data ingestion
        - **Incidents** - Lists MITRE ATT&CK&reg; alerts escalated to incidents

6. Navigate to **MITRE ATT&CK** > **Tactics** to view a list of tactics used for a MITRE ATT&CK&reg;.
    - Click a *Tactic* to view more information about it
    - Under the tab **Techniques** you can check the techniques that the selected tactic uses

A scheduled data ingestion periodically fetches the latest information from the MITRE ATT&CK&reg; database.
