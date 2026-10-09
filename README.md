# Mohamed Amgad Khater

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://eg.linkedin.com/in/moh-amgad)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/moh_amgad)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mamgad)

## 👨‍💻 About Me

I build security products and I break them, which is why they work. These days that means AI-native application security tooling, agentic systems for offense and defense, and the model infrastructure and evaluation work underneath them. My background is offensive, years of penetration testing and secure code review before I started building the tooling that automates it, now extended to AI systems themselves through OSAI, OffSec's AI red teaming certification. Most of my engineering time goes into making AI-assisted security decisions auditable rather than opaque.

## 🔭 Current Role

**Security R&D Technical Lead @ Cyshield**
- Architected an AI-native ASPM platform that scans on the customer's own machine and sends only finding metadata to the cloud, so source never leaves their environment
- Designed the rule pipeline and the finding-identity model that keeps triage decisions attached to a finding across re-scans
- Built the verification layer that asks a model whether a finding is real, and the MCP server that surfaces findings inside developers' coding agents
- Own the security architecture across the portfolio, including a commercially launched AI-powered WAF that sits inline on all customer traffic
- Led development of the agentic SOC systems our analysts use daily, where agents carry the investigation legwork and analysts stay accountable for disposition

## 🤖 AI & Model Infrastructure

- Deploy and tune open-weight models on **vLLM** and **llama.cpp** behind OpenAI-compatible gateways
- Build the agent harnesses and provider shims that let one security core run against a local or a hosted model without changes
- Run evaluation and security benchmarking against labeled corpora with deterministic graders, including the study that showed a security-tuned prompt on a locally served model recovering more real vulnerabilities than a frontier agent
- Measure cost alongside recall rather than after the fact, in that order: get it working, prove it finds what it claims, then bring down what it costs to run

## 🛡️ Security Research

[![HackerOne](https://img.shields.io/badge/HackerOne-494649?style=for-the-badge&logo=hackerone&logoColor=white)](https://hackerone.com/moh_amgad)
[![Bugcrowd](https://img.shields.io/badge/Bugcrowd-F26822?style=for-the-badge&logo=bugcrowd&logoColor=white)](https://bugcrowd.com/moh_amgad)
[![Patchstack](https://img.shields.io/badge/Patchstack-7B3FE4?style=for-the-badge)](https://patchstack.com/database/researchers/cbf755ce-0ada-4561-9cdf-890bc8458aed)
[![Wordfence](https://img.shields.io/badge/Wordfence-0068A0?style=for-the-badge)](https://www.wordfence.com/threat-intel/vulnerabilities/researchers/mohamed-khater)

- Discovered and responsibly disclosed critical vulnerabilities in Fortune 500 companies
- Notable companies: Twitter, Sony, Adobe, TripAdvisor, Ford Motors, Pinterest, Dell
- Published CVEs:
  - [CVE-2026-104803](https://www.wordfence.com/threat-intel/vulnerabilities/wordpress-plugins/wpcom-member/wpcom-member-1727-unauthenticated-authentication-bypass-via-uuid-and-code-parameters-on-social-login-callback) (Unauthenticated Authentication Bypass, WPCOM Member WordPress plugin ≤ 1.7.27)
  - [CVE-2026-105059](https://patchstack.com/database/wordpress/plugin/delete-all-comments-of-website/vulnerability/wordpress-delete-all-comments-of-wordpress-plugin-7-1-broken-access-control-vulnerability) (Broken Access Control, Delete All Comments WordPress plugin ≤ 7.1)
  - [CVE-2026-93620](https://patchstack.com/database/wordpress/plugin/payplus-payment-gateway/vulnerability/wordpress-payplus-payment-gateway-plugin-8-2-5-broken-access-control-vulnerability) (Broken Access Control, PayPlus Payment Gateway WordPress plugin ≤ 8.2.5)
  - [CVE-2017-1000058](https://www.cve.org/CVERecord?id=CVE-2017-1000058) (Stored XSS at Chevereto CMS), CVE-2018-5222

## 🎓 Certifications

### Advanced Security
- OffSec Advanced AI Red Teaming (OSAI) · [verify](https://credentials.offsec.com/0c6b7486-4764-435c-b0d8-78468179558c)
- Offensive Security Web Expert (OSWE) · [verify](https://www.credly.com/badges/71af9f0c-d411-4435-b31c-4d39c7ca4f8d/public_url)
- Certified Cloud Native Security Expert (CCNSE) · [verify](https://www.credly.com/badges/a9a9af47-0706-4d8d-821d-f44226fa2637/)
- Certified Container Security Expert (CCSE) · [verify](https://www.credly.com/badges/88f16ddd-de07-4bf2-bf16-4774af27dfe0)
- Certified DevSecOps Professional (CDP) · [verify](https://www.credly.com/badges/4047edd1-2177-4010-8bcf-1db578a8a636)

### Penetration Testing
- Web Application Penetration Tester Extreme v2 (eWPTXv2) · [verify](https://certs.ine.com/f5d67a16-2494-4d4a-b8e4-ef08432ab131)
- Certified Professional Penetration Tester v2 (eCPPTv2) · [verify](https://certs.ine.com/af5f8150-2eae-4ddd-8a37-468fc5e95858)
- Mobile Application Penetration Tester (eMAPT) · [verify](https://certs.ine.com/1735ba4d-0e48-4432-aa6e-dd47e255f9fd)

## 💻 Technical Skills

### Software Development
- Primary Languages: Python, Java, JavaScript, TypeScript
- Additional: Ruby on Rails, MySQL, PostgreSQL, Bash

### Application Security
- Security Testing: SAST, DAST, SCA, Penetration Testing, Secure Code Review
- Security Tools: BurpSuite Pro, OWASP ZAP, Nuclei, Subfinder, httpx, Nmap, Metasploit, Wireshark, SonarQube, Semgrep, OpenGrep, Trivy, Gitleaks, Checkov

### AI & Agentic Systems
- Model serving: vLLM, llama.cpp, OpenAI-compatible gateways
- Integration: Anthropic, OpenAI, AWS Bedrock, self-hosted endpoints, MCP
- Agent evaluation, grader design, security benchmarking

### Cloud & Infrastructure
- Cloud Security: AWS, Kubernetes, Docker
- DevSecOps: CI/CD Pipeline Security, IaC, Security Automation

## 🚀 Featured Project

### [DVBLab - Secure Banking Application Training](https://github.com/mamgad/DVBLab/)
A comprehensive training project demonstrating common security vulnerabilities in banking applications.
- Built with Python, Flask, SQLAlchemy, React, JWT Authentication
- Includes modules on secure code review, authentication vulnerabilities, and API security
- Implements real-world security scenarios and industry security standards
