# What's New

## Enhacement

- Upon **Alert** or **Incident** created or updated with an MITRE Technique ID, MITRE modules *Group*, *Tactic*, *Technqiue*, *Sub-Technqiue*, *Software*, and *Mitigation* gets correlated.
- Introduced new dashboard **MITRE ATT&CK Matrices** which display MITRE Matrices.

## Bug Fixes

- Changed *Group* and *Tactic* field type from *One To One* to *Many To Many* in **Alert** and **Incident**.
- Removed **MITRE Admin** role as **Full App Premission** contains required permission for MITRE moduels.
- Removed *Hunt* permission from **Full App Premission** as **SOAR Framework** solution pack contians required permission for *Hunt*.