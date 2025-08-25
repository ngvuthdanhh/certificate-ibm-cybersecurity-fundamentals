# 📋 Detection & Response Playbook  

## 🕵️ Detection  
- Centralize logging with a SIEM.  
- Define baseline of normal behavior.  
- Monitor for anomalies: failed logins, large file transfers, unusual IPs.  

## 🚨 Response Workflow  
1. **Identification**: Verify the incident (alerts, logs, user reports).  
2. **Containment**: Isolate compromised systems (short-term & long-term).  
3. **Eradication**: Remove malware, disable malicious accounts.  
4. **Recovery**: Restore from backups, monitor post-incident.  
5. **Lessons Learned**: Document findings, improve controls.  

## 🔄 Example Scenario  
- Suspicious login from foreign IP → Alert triggered → SOC triages → Contain account → Block IP → Reset password → Document in incident report.  
