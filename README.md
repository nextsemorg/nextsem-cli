# nextsem-cli ⚡

> **Official Developer Environment & CLI Toolchain**  
> Curated by **NextSem Academy** for Full-Stack Web Engineering.

---

## 🧭 Overview
`nextsem-cli` provides verified dual-OS setup scripts, terminal configurations, and step-by-step verification commands across:
- **🪟 Windows 11 Pro**: Windows Terminal, PowerShell 7, VS Code 2026, Git CLI, and Node.js LTS.
- **🐧 Linux Mint 22 / Ubuntu LTS**: Bash terminal, essential POSIX packages, and developer workflows.

---

## 📁 Repository Structure
```text
nextsem-cli/
├── README.md                   # Complete dual-OS setup guide & verification commands
├── .gitignore                  # Standard Node.js & Windows/Linux gitignore
├── windows11/
│   ├── powershell-profile.ps1  # Custom developer prompt & aliases (PowerShell 7)
│   └── verification-checks.ps1 # Auto-tester for node, npm, git versions
├── linux-mint/
│   ├── .bashrc_additions       # Developer aliases & paths
│   └── verification-checks.sh  # Auto-tester for Linux tools
└── day1-first-commit/
    └── hello-world.js          # Minimal test script to verify environment
```

---

## 🚀 Quick Verification Commands

### 🪟 Windows 11 (PowerShell 7 / Windows Terminal)
```powershell
node -v
npm -v
git --version
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

### 🐧 Linux Mint 22 (Bash Terminal)
```bash
node -v
npm -v
git --version
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

---

## 📜 License
MIT License • NextSem Academy Open Curriculum
