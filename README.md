# AI-Powered SOC Alert Enrichment Workflow

An automated Security Operations Center (SOC) alert enrichment and triage workflow built using n8n, OpenAI, VirusTotal, and Slack.

This project simulates a lightweight SOAR (Security Orchestration, Automation, and Response) pipeline that enriches suspicious IP alerts with threat intelligence data, generates AI-powered security analysis, and sends formatted incident notifications to Slack.

---

## Features

- Real-time webhook-based alert ingestion
- IP threat intelligence enrichment
- VirusTotal reputation analysis
- AI-generated SOC analyst summaries using OpenAI
- Automated Slack notifications
- Modular and extensible workflow design
- Event-driven security automation

---

## Workflow Architecture

```text
Incoming SOC Alert
        ↓
IP Reputation Enrichment
        ↓
VirusTotal Threat Analysis
        ↓
AI Security Triage
        ↓
Slack SOC Notification
```

---

## Technologies Used

- n8n
- OpenAI API
- VirusTotal API
- Slack API
- Webhooks
- REST APIs
- JSON Expressions

---

## Sample Workflow

### Incoming Alert

```json
{
  "ip": "1.1.1.1",
  "alert": "Suspicious outbound traffic"
}
```

### AI SOC Analysis

```text
Threat Level: Low

Security Summary:
IP 1.1.1.1 belongs to Cloudflare DNS infrastructure and shows no confirmed malicious activity.

Recommended Actions:
Continue monitoring traffic and investigate anomalies if suspicious behavior persists.
```

---

## Use Cases

- SOC alert enrichment
- Threat intelligence automation
- Security operations workflows
- AI-assisted incident triage
- SOAR pipeline simulations
- Cloud security monitoring

---

## Future Improvements

- AbuseIPDB integration
- WHOIS enrichment
- Automatic firewall/WAF blocking
- Severity scoring logic
- SIEM integrations
- Dashboard visualization
- Database logging
- Multi-channel alerting

---

## Learning Outcomes

This project demonstrates:

- Workflow automation
- API integrations
- Event-driven architecture
- Threat intelligence enrichment
- AI-powered security analysis
- Security orchestration concepts
- Cloud and SOC engineering fundamentals

---

## Author

Jiya Saini

AI security | Cloud Security | Security Automation
