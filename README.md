# Mohamed Amgad Khater

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://eg.linkedin.com/in/moh-amgad)
[![Twitter](https://img.shields.io/badge/Twitter-1DA1F2?style=for-the-badge&logo=twitter&logoColor=white)](https://twitter.com/moh_amgad)
[![GitHub](https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white)](https://github.com/mamgad)

## 👨‍💻 About Me

I build security products and I break them, which is why they work. These days that means AI-native application security tooling, agentic systems for offense and defense, and the model infrastructure and evaluation work underneath them. My background is offensive, years of penetration testing and secure code review before I started building the tooling that automates it, and that is still where the detection content comes from. Most of my engineering time goes into making AI-assisted security decisions auditable rather than opaque.

## 🔭 Current Role

**Security R&D Technical Lead @ Cyshield**
- Architected an application security platform that scans on the customer's own machine and sends only finding metadata to the cloud, so source never leaves their environment
- Designed the rule pipeline and the finding-identity model that keeps triage decisions attached to a finding across re-scans
- Built the verification layer that asks a model whether a finding is real, and the MCP server that surfaces findings inside developers' coding agents
- Led development of the agentic SOC systems our analysts use daily, and owned the security architecture for a commercially launched AI-powered WAF

## 🤖 AI & Model Infrastructure

- Deploy and tune open-weight models on **vLLM** and **llama.cpp** behind OpenAI-compatible gateways
- Build the agent harnesses and provider shims that let one security core run against a local or a hosted model without changes
- Run evaluation and security benchmarking against labeled corpora with deterministic graders, including the study that showed a security-tuned prompt on a locally served model recovering more real vulnerabilities than a frontier agent
- Measure cost alongside recall rather than after the fact, in that order: get it working, prove it finds what it claims, then bring down what it costs to run

## 🛡️ Security Research

[![HackerOne](https://img.shields.io/badge/HackerOne-494649?style=for-the-badge&logo=hackerone&logoColor=white)](https://hackerone.com/moh_amgad)
[![Bugcrowd](https://img.shields.io/badge/Bugcrowd-F26822?style=for-the-badge&logo=bugcrowd&logoColor=white)](https://bugcrowd.com/moh_amgad)

- Discovered and responsibly disclosed critical vulnerabilities in Fortune 500 companies
- Notable companies: Twitter, Sony, Adobe, TripAdvisor, Ford Motors, Pinterest, Dell
- Published CVEs: CVE-2017-1000058 (Stored XSS at Chevereto CMS), CVE-2018-5222

## 🎓 Certifications

### Advanced Security
- Offensive Security Web Expert (OSWE)
- Certified Cloud Native Security Expert (CCNSE)
- Certified Container Security Expert (CCSE)
- Certified DevSecOps Professional (CDP)

### Penetration Testing
- Web Application Penetration Tester Extreme v2 (eWPTXv2)
- Certified Professional Penetration Tester v2 (eCPPTv2)
- Mobile Application Penetration Tester (eMAPT)

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
