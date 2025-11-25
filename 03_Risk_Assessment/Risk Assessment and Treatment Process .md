# Information Security Risk Assessment and Treatment Process  
**CypherRisk Ltd** – **Version 1.0 – 01 April 2025** – **Approved by: Managing Director & CISO**

This document fully satisfies **ISO/IEC 27001:2022 Clause 6.1.1, 6.1.2 and 6.1.3**.

### 1. Risk Assessment Methodology (Clause 6.1.2)

**Approach**  
Asset-based qualitative risk assessment using a 5×5 matrix (Likelihood × Impact).

**Likelihood Criteria**  
| Level | Description                  | Probability | Example for CypherRisk |
|-------|------------------------------|-------------|------------------------|
| 1     | Rare                         | <5 %        | State-level APT attack |
| 2     | Unlikely                     | 5–20 %      | Targeted spear-phishing |
| 3     | Possible                     | 20–50 %     | Consultant falls for phishing |
| 4     | Likely                       | 50–80 %     | Misconfigured SharePoint sharing |
| 5     | Almost Certain               | >80 %       | Unpatched laptop on public Wi-Fi |

**Impact Criteria** (worst-case realistic)  
| Level | Financial | Regulatory / Legal | Reputational | Operational |
|-------|-----------|--------------------|--------------|-------------|
| 1     | <£5k      | None               | Minor        | <1 hour downtime |
| 2     | £5–25k    | Warning only       | Local        | <1 day |
| 3     | £25–100k  | ICO/FCA investigation | Regional     | <1 week |
| 4     | £100–500k | Fine               | National     | >1 week |
| 5     | >£500k    | Major fine / licence loss | Industry-wide | Business-ending |

**Risk Level Matrix**  
| Likelihood \ Impact | 1 | 2 | 3 | 4 | 5 |
|---------------------|---|----|----|----|----|
| 5                   | 5 |10 |15 |20 |25 |
| 4                   | 4 | 8 |12 |16 |20 |
| 3                   | 3 | 6 | 9 |12 |15 |
| 2                   | 2 | 4 | 6 | 8 |10 |
| 1                   | 1 | 2 | 3 | 4 | 5 |

**Risk Acceptance Criteria**  
- **High (12–25)** – Must treat within 90 days  
- **Medium (6–10)** – Treat within 6 months or accept with justification  
- **Low (1–5)** – Accept and monitor annually

### 2. Risk Assessment Process Steps (repeated annually and after significant change)

1. Identify assets (see Asset Register)  
2. Identify threats & vulnerabilities (using NCSC threat catalogue + experience from client work)  
3. Identify existing controls  
4. Assess inherent risk (Likelihood × Impact)  
5. Select Annex A controls as treatment  
6. Re-assess residual risk  
7. Document in Risk Register and update SoA  
8. Obtain Managing Director sign-off

### 3. Risk Treatment Process (Clause 6.1.3)

| Option   | When Used                              | Example at CypherRisk                     |
|----------|----------------------------------------|-------------------------------------------|
| Treat    | Default – reduce risk with Annex A controls | Enforce BitLocker, sensitivity labels     |
| Avoid    | Discontinue activity                   | No longer store client data on laptops   |
| Transfer | Cyber insurance + Microsoft SLA        | £5m cyber liability policy in place       |
| Accept   | Residual risk ≤ Low and justified      | Accept risk of state-level APT            |

All treatments are tracked in the Risk Register with owner and due date.

### 4. Roles & Responsibilities
- **Managing Director & CISO** – Ultimate risk owner, approves all acceptances  
- **All consultants** – Report new risks immediately  
- **Annual risk workshop** – Full team (5 people) – March each year

### 5. Tools Used
- Microsoft Excel / CSV (this repo) – Risk Register  
- Microsoft Purview & Defender – Monitoring & measurement  
- NCSC Risk Management Guidance – Reference methodology

**Next full risk assessment**: March 2026  
**Last completed**: 28–29 March 2025 (2-day remote workshop)

Signed:  
/s/ Dr. Alex Harper  
Managing Director & Chief Information Security Officer  
01 April 2025
