# What's New

## Enhancements

- MITRE modules *Group*, *Tactic*, *Technique*, *Sub-Technique*, *Software*, and *Mitigation* are now correlated with an alert or incident on updating the alert or incident with a MITRE Technique ID
- A new dashboard **MITRE ATT&CK Matrices** displays MITRE matrices
- A new **Get MITRE ATT&CK Data** playbook gets MITRE ATT&CK data when executed

## Bug Fixes

- Changed *Group* and *Tactic* field type from *One To One* to *Many To Many* in **Alert** and **Incident** modules

## Deprecations

- Removed the role **MITRE Admin** as **Full App Permission** contains the necessary permissions for working with MITRE modules.

    > **NOTE**: After an upgrade, existing permissions in the **MITRE Admin** role remain unaffected.

- Removed *Hunt* module permissions from **Full App Permission** as **SOAR Framework** `v1.1.0` and later contains necessary permissions for the *Hunt* module.

    > **NOTE**: After an upgrade, existing permissions in the **Full App Permission** role remain unaffected.

## Known Issues

- When an alert or an incident is updated with another *Technique ID* new MITRE data is being overwritten in correlations.

### Workaround

To change the behavior to *Append* instead of *Overwrite* for both alerts and incidents, perform the following steps:

1. Navigate to **Automation** > **Playbooks**.

2. Click to open the **10 - SP - MITRE ATT&CK Enrichment Framework** playbook collection.

3. Perform the following steps to change the behavior in **Alerts**:

    1. Click to open the **Link ATT&CK Technique to Alert (On Update)** playbook.

    2. Double-click to open the **Link Technique to Alert** step.

    3. Under **Fields** click the **Correlations** tab.

    4. Toggle *Overwrite* and *Append* options.

    5. Click **Save** and **Save Playbook** to save the changes to the step and subsequently the playbook.

4. Perform the following steps to change the behavior in **Incidents**:

    1. Click to open the **Link ATT&CK Technique to Incident (On Update)** playbook.

    2. Double-click to open the **Link Technique to Incident** step.

    3. Under **Fields** click the **Correlations** tab.

    4. Toggle *Overwrite* and *Append* options.

    5. Click **Save** and **Save Playbook** to save the changes to the step and subsequently the playbook.