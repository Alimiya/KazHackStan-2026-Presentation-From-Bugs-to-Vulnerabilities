# From Bugs to Vulnerabilities: One Skill Changes Everything

A comprehensive presentation on application security (AppSec) in the age of AI-driven development.

## Overview

This presentation explores the critical gap between code generation and security practices, highlighting how millions of developers use AI to write code without proper security checks. It covers real-world incidents from 2026, security frameworks, and a practical roadmap for developers to transition into AppSec roles.

**Event:** KazHackstan 2026  
**Speakers:** Zhaslan Yernazarov, Ali Orymbayev (Application Security Engineers)

---

## Key Topics

### 1. **The Problem: 6 Steps of Vulnerable Code**
- Vague prompts without context or constraints
- Code accepted without review or analysis
- Unverified dependencies and skipped security checks
- Exposed API keys in public repositories
- Server-side code execution without safeguards
- Production incidents at scale

### 2. **Real Incidents of 2026**
- **Moltbook:** 1.5M API tokens leaked due to exposed Supabase keys in client-side JavaScript
- **Lovable:** CVE-2025-48757 – BOLA vulnerability exposing user source code
- **Replit AI Agent:** Deletion of production databases across 1,196 companies
- **CrowdSec:** Supply chain compromise with 170 private GitHub repositories compromised

### 3. **Security Frameworks**

#### SSDLC (Secure Software Development Lifecycle)
Integrating security at every stage (Requirements → Design → Development → Testing → Deployment → Operations) reduces business risk by 70–90%.

#### OWASP Top 10 for AI Ecosystem
- **OWASP Top 10:** Classic web vulnerabilities (SQL injection, XSS, CSRF, broken auth)
- **OWASP LLM Top 10:** Model-specific risks (prompt injection, sensitive data disclosure, insecure output handling)
- **OWASP MCP Top 10:** Protocol layer vulnerabilities (token mismanagement, insecure tool descriptions)
- **OWASP Agentic Skills Top 10:** Execution vulnerabilities (malicious skills, supply chain compromise, over-privileged access)

### 4. **Why AppSec Matters**
- Errors are predictable and preventable via checklists
- Lower barrier to entry than assumed
- A learnable skill, not a career restart

### 5. **Career Roadmap**
Quick transition to AppSec specialization:
1. Master OWASP Top 10
2. Learn threat modeling (STRIDE)
3. Implement SAST and dependency scanners in CI/CD
4. Conduct security code reviews
5. Build a portfolio: CTFs, bug bounties, internal security reviews

### 6. **Market Opportunity in Kazakhstan**
- **14 AppSec positions nationwide** (vs. 1,403 developer roles)
- **Salary:** Not disclosed in public postings, but confidentially **higher than backend developers**
- **Competition:** 1 in 100 market vacancies is AppSec – extremely low supply vs. high demand

---

## Key Takeaways

1. **Security experience cannot be faked** – specific findings matter (SQL injection, IDOR, prompt injection)
2. **AppSec is a skill, not a separate profession** – developers can transition with structured learning
3. **High market value** – rare specialists command premium compensation
4. **Urgent need** – AI-generated code amplifies vulnerability at scale

---

## Who Should Watch This

- **Developers** using AI coding assistants (Copilot, Claude, etc.)
- **Security professionals** building defenses against AI-generated vulnerabilities
- **Career changers** interested in high-demand, well-compensated AppSec roles
- **Organizations** deploying AI-assisted development at scale
- **Students** considering security engineering specializations

---

## Resources Mentioned

- OWASP Top 10: https://owasp.org/www-project-top-ten/
- OWASP LLM Top 10: https://owasp.org/www-project-top-10-for-large-language-model-applications/
- STRIDE Threat Modeling: https://www.microsoft.com/en-us/securityengineering/sdl/threatmodeling
- SAST Tools: Bandit, Semgrep, Safety, Snyk
- Incident Sources: Moltbook, Lovable, Replit, CrowdSec public disclosures

---

## Presentation Structure

| Section | Topic | Focus |
|---------|-------|-------|
| 01 | 6 Steps of Vulnerable Code | From idea to deployment |
| 02 | Real Incidents 2026 | Moltbook, Lovable, Replit, CrowdSec |
| 03 | How to Fix It | Code review, threat modeling, SAST |
| 04 | Career Impact | Job market and practical roadmap |

---

## About the Speakers

- **Zhaslan Yernazarov** – Application Security Engineer
- **Ali Orymbayev** – Application Security Engineer (Freedom Telecom Operations)

---

## License

This presentation was delivered at KazHackstan 2026. Use for educational and community purposes.

---

*"One skill changes everything."* – Start with OWASP Top 10, master threat modeling, and build your AppSec portfolio today.
