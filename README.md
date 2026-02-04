# Fraud Alert Triage System

## Overview
This project demonstrates a structured fraud alert triage process designed to quickly identify high-risk transactions, reduce financial exposure, and minimize customer disruption. Each transaction is evaluated using multiple risk indicators and assigned an alert score from 0–100 to guide automated decisions and manual review workflows.

The system reflects real-world fraud operations practices, including alert prioritization, remediation documentation, and continuous feedback into fraud controls.

---

## Objectives
- Detect potentially fraudulent transactions efficiently
- Prioritize alerts by severity and financial risk
- Reduce false positives and unnecessary customer friction
- Apply proportionate remediation actions
- Improve fraud controls through feedback loops

---

## Risk Scoring Logic
Each transaction receives an **Alert Score (0–100)** based on factors such as:
- Transaction velocity and rapid repeat activity
- Sudden increases in spend
- Merchant risk level
- High-value or luxury purchases
- Uncharacteristic customer behavior
- New merchants or unfamiliar locations

---

## Alert Severity Tiers
| Risk Level | Score Range | Action |
|----------|-------------|--------|
| Low Risk | < 30 | Auto-approved |
| Medium Risk | 30–60 | Manual review and customer confirmation |
| High Risk | > 60 | Immediate block to prevent loss |

This tiered approach ensures critical threats are addressed immediately while maintaining a smooth experience for legitimate customers.

---

## Remediation Actions
For confirmed or high-confidence fraud cases, actions may include:
- Temporary account restrictions or freezes
- Customer identity and transaction verification
- Credential replacement
- Enhanced monitoring
- Account closure for severe or repeat fraud

Remediation is always proportional to the assessed risk to limit unnecessary disruption.

---

## Dataset
The project includes a simulated transaction dataset featuring:
- Transaction metadata (amount, merchant, channel, payment type)
- Fraud indicators and alert scores
- Final decisions (Approved, Review, Block)
- Documented company actions for flagged transactions

This mirrors how fraud analysts document investigations and response steps.

---

## Continuous Improvement
Patterns identified during triage are fed back into fraud controls to:
- Adjust alert thresholds
- Refine merchant-specific rules
- Reduce alert noise
- Improve detection accuracy over time

---

## Skills Demonstrated
- Fraud risk assessment
- Transaction monitoring and triage
- Risk scoring and severity classification
- False-positive reduction strategies
- Investigation documentation
- Operational decision-making

---

## Use Case
This project is designed for:
- Fraud Analyst
- Risk Analyst
- Financial Crimes Analyst
- Trust & Safety roles

It showcases practical fraud operations thinking rather than purely academic modeling.
