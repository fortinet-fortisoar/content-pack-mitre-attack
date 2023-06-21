# What's New

## Enhancement

- Upon **Alert** or **Incident** created or updated with an MITRE Technique ID, MITRE modules *Group*, *Tactic*, *Technique*, *Sub-Technique*, *Software*, and *Mitigation* gets correlated.
- Introduced new dashboard **MITRE ATT&CK Matrices** which display MITRE Matrices.
- Introduced new playbook **Get MITRE ATT&CK Data** to get MITRE ATT&CK data manually.

## Bug Fixes

- Changed *Group* and *Tactic* field type from *One To One* to *Many To Many* in **Alert** and **Incident**.

## Depricated

- Removed **MITRE Admin** role as **Full App Permission** contains required permission for MITRE modules.
- Removed *Hunt* module permission from **Full App Permission** as **SOAR Framework** solution pack contains required permission for *Hunt* module.