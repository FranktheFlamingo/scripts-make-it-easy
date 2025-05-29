# 🔐 Security Policy

## 📦 Supported Versions

The following versions of our software and systems are currently supported for **security updates**:

| Version  | Supported          | Notes                                         |
|----------|--------------------|-----------------------------------------------|
| `5.1.x`  | ✅ :white_check_mark: | Active development and security patches       |
| `5.0.x`  | ❌ :x:              | Deprecated; upgrade strongly recommended      |
| `4.0.x`  | ✅ :white_check_mark: | Maintenance-only support                      |
| `< 4.0`  | ❌ :x:              | No longer maintained                          |

---

## 🛠️ Reporting a Vulnerability

Security is at the core of everything we build. If you believe you have discovered a security vulnerability, please report it responsibly using the steps below.

### 📩 Submit a Report

Please send all vulnerability disclosures to our **dedicated security email**:  
**[security@pcwprops.com](mailto:security@pcwprops.com)**  
Alternatively, submit securely via [https://pcwprops.com/disclosure](https://pcwprops.com/disclosure) *(requires login)*.

**Do not publicly disclose issues** until we have responded with a resolution or timeline.

---

### 📅 Response Timeline

You can expect a reply within **72 hours**. We commit to the following response workflow:

1. 🔍 **Acknowledgement** of the report
2. 🧪 **Verification and triage**
3. 🛠️ **Fix planning and internal patching**
4. 📣 **Disclosure timeline and CVE assignment (if applicable)**

We believe in **coordinated disclosure** and will work with you to release any advisories responsibly.

---

### 🧰 Systems Covered

We actively monitor and maintain the security of all repositories and services related to:

- `Terraform` infrastructure modules
- `Cloudflare` firewall and DNS configurations
- `UniFi` Identity SSO, VPN, and Zone Firewall policies
- `Home Assistant` integrations and APIs
- `WordPress` plugin code, templates, and custom themes
- `QuickBooks` automation templates and app integrations
- All codebases hosted within the `PCWProps`, `PCWIntegrates`, and `dynamicmarching.com` organizations

---

### 🧪 Best Practices

All systems follow these security practices:

- ✅ Secrets management via 1Password Connect Server
- ✅ API tokens never stored in code or `.env` files
- ✅ CI/CD audit trails with permission reviews
- ✅ SSH key rotation and access revocation via GitHub SSO
- ✅ Zero Trust policies applied via Cloudflare Gateway & Access

---

> 📌 For developers: see our [CONTRIBUTING.md](./CONTRIBUTING.md) for secure coding practices, or reach out to the DevSecOps lead via Slack or email.

Stay secure,  
**The PCW Security & DevOps Team**
