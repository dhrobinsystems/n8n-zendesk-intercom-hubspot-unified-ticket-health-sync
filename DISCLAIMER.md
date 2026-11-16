# ⚠️ Disclaimer & Liability Limitation

**Repository:** `n8n-zendesk-intercom-hubspot-unified-ticket-health-sync`
**Author:** DH Robin (dhRobin Systems)
**Last updated:** November 2026

Use at your own risk. The code, workflows, and scripts in this repository (`n8n-zendesk-intercom-hubspot-unified-ticket-health-sync`) are provided for educational and architectural demonstration purposes.

* **No Liability:** The author and dhRobin Systems accept no responsibility or liability for any direct, indirect, incidental, or consequential damages that result from using, misusing, or deploying these scripts. That includes, without limitation, missed, delayed, duplicated or misattributed tickets, tickets associated with the wrong contact or company, incorrect resolution times, CSAT, sentiment grades or health scores, account, renewal or staffing decisions made from them, API charges, and any record created or changed in a connected system.

* **No Warranty:** All software, n8n JSON blueprints and JavaScript modules are provided "AS IS", without warranty of any kind, express or implied. This includes, but is not limited to, warranties of merchantability, fitness for a particular purpose, and non-infringement. The status and priority maps, sentiment lexicon, health penalties, thresholds and redaction patterns are illustrative defaults and are not guaranteed to suit your support operation.

* **Production Testing Required:** Always test thoroughly in an isolated staging environment, such as a HubSpot developer test account or sandbox, a Zendesk sandbox and an Intercom test workspace, with `SANDBOX_MODE=true` and `DRY_RUN=true` enabled, before you connect live Zendesk, Intercom or HubSpot credentials. Treat every sentiment grade and health score as a signal that a person must review before acting on it.

* **Sentiment Is an Approximation:** Sentiment scores come from CSAT ratings, provider fields you configure, or a simple keyword match on ticket subjects. They are approximations, not an assessment of any person, and shouldn't be used to make decisions about individual customers or support staff.

* **Third-Party APIs & Compliance:** You alone are responsible for complying with the terms of service, rate limits, data privacy regulations (GDPR/CCPA and others), data-processing agreements, and security policies of Zendesk, Intercom, HubSpot, Slack and any connected services. That includes telling customers how their support data is shared between systems, confirming a lawful basis for that sharing, keeping conversation content and personal data out of the CRM and logs, honouring access and deletion requests in every connected system, restricting access to n8n executions, and reviewing every automatically created or updated record.

* **No Affiliation:** This project is independent. It is not affiliated with, endorsed by, or sponsored by Zendesk, Inc., Intercom, Inc., HubSpot, Inc., Slack Technologies, LLC, Salesforce, Inc., or n8n GmbH. All product names and trademarks belong to their respective owners and are used only to describe compatibility.

* **Fictional Sample Data:** All customer names, e-mail addresses, domains (under the reserved `.example` suffix), ticket and conversation IDs, subjects, message bodies, ratings, timings, record IDs and secrets in the pinned sample data and documentation are fictional and exist only for testing. Any resemblance to real people or organisations is coincidental. Placeholder values such as `YOUR_ZENDESK_SUBDOMAIN`, `YOUR_ZENDESK_AGENT_EMAIL`, `YOUR_ZENDESK_API_TOKEN`, `YOUR_ZENDESK_WEBHOOK_SIGNING_SECRET`, `YOUR_INTERCOM_ACCESS_TOKEN`, `YOUR_INTERCOM_CLIENT_SECRET`, `YOUR_HUBSPOT_PRIVATE_APP_TOKEN` and `YOUR_HUBSPOT_PORTAL_ID` must be replaced with your own values, which you keep in environment variables or n8n credentials.

* **Not Professional Advice:** Nothing in this repository is legal, privacy or compliance advice. Consult qualified professionals for decisions in those areas.

## Open-Source License Notice

This project is released under the MIT License. You may use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the software, subject to the conditions in [LICENSE](./LICENSE). The MIT License's own warranty disclaimer and limitation of liability apply in addition to this document. If the two conflict, the terms more protective of the author apply to the extent permitted by law.

---

Full text: DISCLAIMER.md · Licensed under the MIT License. License: MIT © 2026 DH Robin (dhRobin Systems) · Provided as-is, see the disclaimer.
