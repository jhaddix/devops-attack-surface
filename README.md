# 🔐 Pentester's Cheatsheet Collection

Interactive, self-hosted HTML reference guides for penetration testing and security assessments.

## 📚 Available Cheatsheets

### 1. [Default Credentials Cheatsheet](default-credentials.html)
**52+ services with default usernames and passwords**
- Databases (PostgreSQL, MySQL, MongoDB, Redis, MSSQL, Oracle, etc.)
- Web Applications & CMS (WordPress, Jira, Jenkins, GitLab, etc.)
- Network Devices (Cisco, Juniper, Fortinet, Palo Alto, etc.)
- Cloud & Virtualization (VMware, Proxmox, Docker, etc.)
- IoT & Embedded Systems
- Application Servers
- Monitoring & Management Tools

**Features:**
- 🔍 Real-time search
- 📋 One-click copy to clipboard
- 🎨 Interactive, modern UI
- ⚡ Keyboard shortcuts

### 2. [Service Accounts Cheatsheet](service-accounts.html)
**30+ system and service accounts for Windows, Linux, and Cloud**

**Coverage:**
- **Windows:** SYSTEM, LocalService, NetworkService, IIS AppPools, Virtual Accounts, Domain Service Accounts, gMSA
- **Linux:** root, www-data, apache, nginx, mysql, postgres, redis, mongodb, docker, systemd accounts
- **Cloud:** AWS IAM Roles, GCP Service Accounts, Azure Managed Identities, Kubernetes Service Accounts
- **Containers:** Docker, Kubernetes pod security contexts

**For Each Account:**
- Privilege levels and permissions
- Attack techniques and vectors
- Exploitation commands (ready to copy)
- Security notes and risks
- OPSEC considerations

### 3. [DevOps Attack Surface Guide](devops-attack-surface.html)
**60+ DevOps tools and platforms with attack vectors**

Based on the open-source class by **Tom and Colbert from Accenture (formerly FusionX)**

**Categories:**
- 📚 Knowledge Bases (SharePoint, Confluence, Notion, Wiki.js, etc.)
- 📋 Dev & Project Management (Jira, Trello, Redmine)
- 🔀 Source Code Management (Git, GitHub, GitLab, Bitbucket, etc.)
- 📦 Repository Management (Artifactory, Nexus, etc.)
- 🏗️ Build Servers (Jenkins, CircleCI, GitHub Actions, etc.)
- 🚀 Deployment Platforms (Octopus Deploy, UrbanCode, etc.)
- ⚙️ Configuration Management (Ansible, Chef, Puppet, Salt, etc.)
- 📊 Operations & Monitoring (Splunk, ELK, Grafana, Nagios, etc.)
- 🏗️ Infrastructure as Code (Terraform, CloudFormation, ARM, etc.)
- 🔐 Secrets Managers (Vault, Key Vault, Secrets Manager, CyberArk, etc.)

**Includes:**
- Attack vectors and exploitation techniques
- Default credentials
- CVE references
- OPSEC considerations
- Complete 2-day course agenda and prerequisites

## 🚀 Quick Start

### Option 1: Local Hosting
```bash
# Clone the repository
git clone https://github.com/YOUR_USERNAME/pentest-cheatsheets.git
cd pentest-cheatsheets

# Start a local web server
python3 -m http.server 8080

# Open in browser
open http://localhost:8080
```

### Option 2: GitHub Pages
Visit: `https://YOUR_USERNAME.github.io/pentest-cheatsheets/`

## 📖 Usage

Each cheatsheet is a standalone HTML file that works completely offline. No external dependencies, no JavaScript frameworks - just pure HTML, CSS, and vanilla JavaScript.

**Features:**
- 🔍 **Search:** Find tools, credentials, or techniques instantly
- 📋 **Copy:** Click any credential or command to copy to clipboard
- 🎯 **Interactive:** Expand/collapse categories and tool details
- ⚡ **Keyboard Shortcuts:**
  - `Ctrl+F` - Focus search box
  - `Esc` - Clear search
- 📱 **Responsive:** Works on desktop and mobile

## ⚠️ Disclaimer

These tools are for **authorized security testing only**. Always obtain proper authorization before testing any systems. Unauthorized access is illegal and can cause significant damage.

**Use cases:**
- Authorized penetration testing
- Red team operations
- Security assessments
- CTF competitions
- Security research and education

## 🤝 Credits

- **DevOps Attack Surface:** Based on the open-source class by Tom and Colbert from Accenture (formerly FusionX)
- **Service Accounts:** Compiled from various penetration testing guides and field experience
- **Default Credentials:** Aggregated from vendor documentation, public databases, and security research

## 📝 Contributing

Contributions are welcome! If you have:
- Additional default credentials
- New service accounts to document
- More DevOps tools and attack vectors
- Corrections or improvements

Please open an issue or submit a pull request.

## 📄 License

MIT License - Free to use for educational and authorized security testing purposes.

## 🔗 Resources

- [OWASP Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)
- [CIDER Security - Top 10 CI/CD Security Risks](https://www.cidersecurity.io/top-10-ci-cd-security-risks/)
- [HackTricks](https://book.hacktricks.xyz/)
- [PayloadsAllTheThings](https://github.com/swisskyrepo/PayloadsAllTheThings)

---

**Last Updated:** 2024
