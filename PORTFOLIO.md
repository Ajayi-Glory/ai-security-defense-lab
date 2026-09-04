# AI Defense Lab — Portfolio

**Student:** [Ajayi Glory]

**GitHub:** https://github.com/Ajayi-Glory

**Hugging Face Space:** https://ai-security-defense-lab-glovis.streamlit.app/

**Completed:** [August 2026]

---

Fill in each section as you complete a level. Link directly to your commit diff so a recruiter can see exactly what you changed.

---

## Level 1 — MedVitals AI · Cloud Infrastructure Security

**Problem:** The medvitals AI environment had cloud security weaknesses that could allow an attacker to access sensitive resources ,escalate privileges, or expose secret.

**Method:** I reviewed the cloud infrastructure and security logs identifield excessive permissions and exposed secrets, traced the attack activity, and applied least priviledge security control to reduce the attack surface.

**Evidence:** https://github.com/Ajayi-Glory/hernetiq-fellowship-portfolio/commit/35559bff9d0b8c7e08c81bcd9605a304cd117d2e

**Outcome:** Reduced unnecessary access, improved protectionof sensitive credential, and documented the incident timeline and security findings.

**Skills:** CloudTrail Log Forensics · IAM Least Privilege · Secrets Management · Incident Timeline Reporting

**Others:**
- https://lnkd.in/p/gp4VArxe


---

## Level 2 — DataForge ML · AI Model Security

**Problem:**The Dataforge ML pipeline used unsafe python pickle deserialization to load an AI model.A malicious model could execute embedded code during loading and compromise the production environment.

**Method:**Inspected the model loading code and source model repository, ran picklescan against the vulnerable model,identified the malicious subprocess payload, and hardened the pipeline by replacing pickle loading with safe tensors and adding picklescan verification before model loading

**Evidence:** https://github.com/Ajayi-Glory/ai-security-defense-lab/commit/b350cb7475d6ed23dcba3e9455fbe26225f3aa0d

**Outcome:**Removed the unsafe pickle-based model loading path, adding a security scanning gate and switched the model format to safe tensor to reduce the risk of malicious model deserialization.

**Skills:** Model Supply Chain Verification · Pickle Exploit Detection · Safetensors · Automated Model Scanning

**Others:**
- [https://github.com/Ajayi-Glory/ai-security-defense-lab/blob/main/level2_model_threat_assessment.md]
- [https://www.linkedin.com/posts/ajayi-glory-8b3397420_ive-been-working-through-corpconnect-messenger-activity-7495461509217673216-Npqh?utm_source=share&utm_medium=member_ios&rcm=ACoAAGrX8UcBcXv7iOr5YSVFAsr-YFm0w9oX_04]

---

## Level 3 — CartBot AI · Application & API Security

**Problem:**

**Method:**

**Evidence:** [Link to commit]

**Outcome:**

**Skills:** AI API Hardening · Rate Limiting · Output Filtering · OWASP LLM Top 10 · Direct Prompt Injection Defence

**Others:**
- [Technical write-up link]
- [LinkedIn post link]

---

## Level 4 — PayGuard · Data Security in AI

**Problem:**

**Method:**

**Evidence:** [Link to commit]

**Outcome:**

**Skills:** STRIDE Threat Modeling · RAG Pipeline Security · Multi-Tenant Data Isolation · Indirect Prompt Injection Defence

**Others:**
- [Technical write-up link]
- [LinkedIn post link]

---

## Level 5 — LegalBot Municipal · Agentic AI Security

**Problem:**

**Method:**

**Evidence:** [Link to commit]

**Outcome:**

**Skills:** Excessive Agency Mitigation · Llama Guard Integration · Pydantic Schema Enforcement · Autonomous Agent Containment

**Others:**
- [Technical write-up link]
- [LinkedIn post link]
