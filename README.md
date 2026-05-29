cd ~/Desktop/AlBochi 2>/dev/null || git clone https://github.com/AlBochi/AlBochi.git ~/Desktop/AlBochi
cd ~/Desktop/AlBochi

cat > README.md << 'ENDOFFILE'
<p align="center">
  <strong>Saillent</strong>
</p>

<h3 align="center">AI Governance Infrastructure for Financial Institutions</h3>

<p align="center">
  Regulated financial institutions. Canada & United States.
</p>

<p align="center">
  <a href="https://saillent.com">saillent.com</a> &nbsp;|&nbsp;
  <a href="mailto:info@saillent.com">info@saillent.com</a>
</p>

<p align="center">
  <a href="https://www.linkedin.com/company/saillent/"><img src="https://img.shields.io/badge/LinkedIn-Company-0A66C2?logo=linkedin&style=flat" alt="LinkedIn Company"></a>
  <a href="https://www.linkedin.com/in/albochi/"><img src="https://img.shields.io/badge/LinkedIn-Founder-0A66C2?logo=linkedin&style=flat" alt="LinkedIn Founder"></a>
  <a href="https://x.com/SaillentCanada"><img src="https://img.shields.io/badge/X-@SaillentCanada-000000?logo=x&style=flat" alt="X"></a>
  <a href="https://www.youtube.com/@SaillentCA"><img src="https://img.shields.io/badge/YouTube-@SaillentCA-FF0000?logo=youtube&style=flat" alt="YouTube"></a>
</p>

---

### What We Build

Enterprise AI governance infrastructure for regulated financial institutions — enabling AI visibility, risk classification, audit-ready control environments, and board-level governance operating models. Aligned to OSFI E-23, SR 11-7, and emerging regulatory expectations.

---

### Governance Operating System

**Enterprise AI Visibility** → **Risk Classification & Controls** → **Monitoring & Audit Evidence** → **Governance Operating Model** → **Organizational Enablement**

---

### Regulatory Alignment

`OSFI E-23` `SR 11-7` `NIST AI RMF` `OCC` `SEC` `FDIC` `CFPB` `FINRA` `NCUA` `FCAC` `PIPEDA`

---

### Open-Source Tools

[Model Inventory CLI](https://github.com/AlBochi/model-inventory-cli) · [Shadow AI Detector](https://github.com/AlBochi/shadow-ai-detector) · [OSFI E-23 Checklist](https://github.com/AlBochi/osfi-e23-checklist) · [SR 11-7 Readiness](https://github.com/AlBochi/sr11-7-readiness) · [Audit Trail Logger](https://github.com/AlBochi/audit-trail-logger) · [Governance Dashboard](https://github.com/AlBochi/governance-dashboard)

---

<p align="center">
  <em>We find what your AI hides — before regulators do.</em>
</p>
ENDOFFILE

git add .
git commit -m "Update GitHub profile to match enterprise governance infrastructure positioning"
git push
