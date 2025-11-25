# Risk Assessment and Risk Treatment Process – CZ Ltd  
**Version 1.1 | 18 March 2025 | Approved by: CTO & Compliance Officer**

This document satisfies **ISO 27001:2022 Clause 6.1 – Actions to address risks and opportunities** and **Clause 6.1.3 – Information security risk treatment**.

### Risk Assessment Methodology (Clause 6.1.2)
- **Approach**: Asset-based, qualitative 5×5 risk matrix (Likelihood × Impact)
- **Likelihood scale**  
  1=Rare, 2=Unlikely, 3=Possible, 4=Likely, 5=Almost Certain
- **Impact scale** (financial, regulatory, reputational, operational)  
  1=Negligible, 2=Minor, 3=Moderate, 4=Major, 5=Catastrophic
- **Risk acceptance criteria**  
  - High (15–25) → Must treat within 3 months  
  - Medium (8–12) → Treat within 6 months or accept with justification  
  - Low (1–6) → Accept and monitor
- **Risk owners**: Assigned to department heads (IT Director, Compliance Officer, etc.)
- **Review frequency**: Full re-assessment annually (March) + ad-hoc after major incidents or scope changes

### Risk Treatment Options (Clause 6.1.3)
1. **Treat** – Apply one or more Annex A controls (preferred)
2. **Avoid** – Discontinue the activity (e.g., decommissioning legacy on-prem server)
3. **Transfer** – Cyber insurance + Microsoft shared responsibility model
4. **Accept** – Documented sign-off by CTO where residual risk ≤ Low

### Process Steps
1. Identify information assets (see Asset Register)
2. Identify threats and vulnerabilities (NCSC threat catalogue + Azure-specific threats)
3. Assess existing controls
4. Calculate inherent risk
5. Select and implement Annex A controls as treatment
6. Re-assess residual risk
7. Document in Risk Register and update SoA

### Risk Assessment Schedule (Clause 8.2 – Operation)
| Activity                          | Owner               | Frequency       | Next Due    | Evidence Location                          |
|-----------------------------------|---------------------|-----------------|-------------|--------------------------------------------|
| Annual full risk assessment       | Compliance Officer  | Annually        | Mar 2026    | This folder – Risk Register v2            |
| Review after major incident       | CISO                | As required     | Ongoing     | Incident post-mortem reports              |
| Review after scope change         | CTO                 | As required     | Ongoing     | Change request + updated Scope Statement  |
| Quarterly risk treatment review   | Risk Committee      | Quarterly       | Jun 2025    | Management Review minutes                 |
| Annual SoA update                 | Compliance Officer  | Annually        | Mar 2026    | 04_Statement_of_Applicability/            |

This process was applied in March 2025 and resulted in 89/93 Annex A controls being selected (see SoA).

Signed:  
/s/ James Carter – Chief Technology Officer – 18 March 2025  
/s/ Sarah Patel – Compliance Officer – 18 March 2025
