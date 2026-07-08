# Update IP Feed on FortiManager

## Refer to article:
https://community.fortinet.com/fortianalyzer-6/technical-tip-updating-a-fortimanager-local-external-resource-feed-from-a-fortianalyzer-playbook-228684

- Create Webhook connector in FortiAnalyzer (using FMG API).
- Download the Alert Handler *FortiGate_Login.json* and import in FortiAnalyzer -> Incidents & Alerts -> Alert Handler -> More -> Import.
- Download the Playbook *Update_IP_Feed_on_FortiManager_v8.json* for *FAZ v8.0* and import the file to FortiAnalzyer: FortiAnalyzer -> Incidents & Alerts -> Automation -> Playbook -> More -> Import.
- Edit the playbook and verify.
