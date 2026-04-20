# Review Report — Folder 146078
**Session Topic:** SOC Operations, ELK Stack, and Splunk Introduction

---

## Part 1 — Factual Correctness

### Notes

| Location | Issue | Verdict |
|---|---|---|
| Tool Focus section | Labels Splunk as the primary tool covered in the session. In reality, the session spent the majority of time on ELK (Kibana setup, data views, log discovery). Splunk installation was initiated but the actual lab was explicitly deferred to a future session. | Misleading framing |
| SOC Workflow — Step 5 | Labeled "Improvement (L3)" with tasks: update detection rules, improve monitoring, prevent recurrence. The transcript's actual workflow after L3 investigation includes a distinct "Response" phase, then "Documentation," and then "Post-Incident Review" leading to improvement. The notes compress and re-label these steps, skipping documentation. | Minor inaccuracy — incomplete representation of the workflow |

**Overall:** No major factual errors in the notes. The content that is present is broadly accurate.

---

### Assignment (CSV)

| Question | Issue | Verdict |
|---|---|---|
| Q5 — MTTR | Answer options include both "Mean Time to Resolve" (Option 1) and "Mean Time to Remediate" (Option 3, marked correct). In the industry, "MTTR" is a standard abbreviation for both terms. Having two plausible expansions as options — one correct, one as a distractor — creates an ambiguous question. However, the transcript explicitly defines it as "Mean Time to Remediate," so the answer is consistent with what was taught. | Minor concern — could confuse students who have seen the other expansion elsewhere |
| All other questions | Factually accurate and consistent with the transcript content. | No issue |

---

## Part 2 — Alignment with Session

### Items in Notes Outside the Scope of the Session

| Section in Notes | Issue |
|---|---|
| **"Ethical Responsibility"** | This entire section — covering analyst responsibility to respect privacy, follow strict policies, and avoid misuse of information — has **no basis in the transcript**. The session contains no discussion of ethics or data privacy obligations of SOC analysts. |
| **"SOC Mindset"** | Framed as a standalone concept ("A SOC analyst does not just look at data. They investigate patterns, question anomalies…"). This framing was not presented as a dedicated topic in the session. |
| **"Questions to Think About Before the Session"** | Three reflective prompts at the end of the notes (e.g., "Why is it important to filter logs instead of reviewing everything?"). These were not posed or discussed in the session. |
| **"What You Will Do in This Workshop"** | Describes a Splunk-focused hands-on session. The session was primarily ELK-focused, and the Splunk lab was explicitly postponed. |

---

### Items in Assignment Outside the Scope of the Session

All 10 MCQ topics (SOC roles, MTTR, KPIs, ELK vs Wazuh, Splunk, docker-compose, Kibana, SOC workflow) are grounded in concepts taught or demonstrated in the session. No MCQ topic is completely absent from the transcript.

The subjective question scenario (ELK monitoring + Splunk evaluation + Docker issues) is well-aligned with session content.

---

### Significant Coverage Gaps — Topics Taught in Session but Missing from Notes

| Topic Covered in Transcript | Present in Notes? |
|---|---|
| KPIs in SOC — definition, examples (vulnerability fix targets, feedback rate), and why they matter | ❌ Not mentioned |
| MTTD (Mean Time to Detect) — explicitly defined with example of 15-minute detection target | ❌ Not mentioned |
| MTTR (Mean Time to Remediate) — explicitly defined with SLA context | ❌ Not mentioned |
| Incident priority levels P1–P4 (P1 = critical, P4 = lowest; different MTTD/MTTR per priority) | ❌ Not mentioned |
| ELK Stack walkthrough — Kibana UI, creating data views, log discovery, filtering by syslog host, expanding log entries | ❌ Not mentioned (notes only mention Splunk) |
| Wazuh vs ELK detailed comparison — ELK as log/SIEM tool vs Wazuh as full SOC tool with endpoint protection | ❌ Not mentioned |
| UEBA — User Entity Behavior Analytics, briefly introduced as an advanced SOC concept | ❌ Not mentioned |
| SOC career progression path — L1 → L2/L3 → SOC Manager → Security Architect → CSO/Security Director | ❌ Not mentioned |
| CDC (Cyber Defense Center) — real-world example of a SOC setup shared by the instructor | ❌ Not mentioned |
