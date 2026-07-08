# Update IP Feed on FortiManager

Refer to article: [Technical Tip: Updating a FortiManager local external resource feed from a FortiAnalyzer playbook.](https://community.fortinet.com/fortianalyzer-6/technical-tip-updating-a-fortimanager-local-external-resource-feed-from-a-fortianalyzer-playbook-228684)

## Steps
- Create Webhook connector in FortiAnalyzer (using FMG API).
- Download Alert/Event Handler **FortiGate_Login.json** and import in **FortiAnalyzer -> Incidents & Alerts -> Alert Handler -> More -> Import**.
- Download appropriate (v7.4/7.6/8.0) Playbook **Update_IP_Feed_on_FortiManager_vX.X.json** and import the file to **FortiAnalzyer: Incidents & Alerts -> Automation -> Playbook -> More -> Import**.
- Edit the playbook and verify.
