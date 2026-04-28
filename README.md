# NULLTRACE PROJECT

> **Advanced Open Source Intelligence (OSINT) Framework**  
> A comprehensive Python-based intelligence gathering tool for professional investigators, security researchers, and OSINT enthusiasts.

[![License](https://img.shields.io/badge/License-MIT-red.svg)](LICENSE.md)
[![Python](https://img.shields.io/badge/Python-3.11+-red.svg)](https://www.python.org/)
[![Status](https://img.shields.io/badge/Status-Active-green.svg)](#)

---

## 🎯 Overview

**NullTrace** is a powerful, modular OSINT framework that consolidates multiple intelligence-gathering techniques into a single, intuitive interface. Designed for security professionals, investigators, and researchers, it provides comprehensive tools for:

- **Person Reconnaissance** - Email, username, and social media profiling
- **Network Intelligence** - IP geolocation, domain analysis, WHOIS lookups
- **Communication Analysis** - Phone number tracking and reverse lookups
- **Digital Forensics** - Metadata extraction and file analysis
- **Dark Web & Crypto** - Underground marketplace and cryptocurrency tracking
- **Data Breach Monitoring** - Compromised database searches

---

## 🚀 Core Features

### Intelligence Gathering Modules

| Category | Features |
|----------|----------|
| **Person** | Email OSINT, Username Search, Social Media Profiling, Face Recognition |
| **Network** | IP Lookup, Domain Analysis, Geolocation, WHOIS, Shodan |
| **Communication** | Phone Number Reverse Lookup, Area Code Analysis |
| **Digital Forensics** | Metadata Extraction, File Analysis, EXIF Data |
| **Dark Web** | Marketplace Monitoring, Threat Intelligence |
| **Cryptocurrency** | Wallet Tracking, Transaction Analysis, Address Lookup |
| **Data Breach** | Compromise Database Search, Password Leak Detection |

### Professional Tools

- **Interactive Tutorial System** - Comprehensive OSINT methodology training
- **Custom Configurations** - API key management and settings
- **Detailed Reports** - Structured output and result management
- **OPSEC Guidelines** - Security best practices
- **Advanced Filtering** - Refine and analyze results

---

## 📋 Requirements

### System Requirements
- **OS**: Windows 10+, macOS, Linux
- **Python**: 3.11 or higher
- **RAM**: 4GB minimum
- **Disk Space**: 500MB

### Dependencies
- Core Python packages (see `config/requirements.txt`)
- API Keys for enhanced functionality (optional)
- Node.js (optional, for JavaScript modules)

---

## 📦 Installation

### Option 1: Quick Setup (Windows)
```bash
# Clone or extract the repository
git clone https://github.com/yourusername/NullTrace.git
cd NullTrace

# Run automated setup
./setup.bat
```

### Option 2: Manual Setup
```bash
# Create virtual environment
python -m venv venv
source venv/Scripts/activate  # Windows: venv\Scripts\activate

# Install dependencies
pip install -r config/requirements.txt

# Run the application
python main.py
```

---

## 🔑 API Configuration

NullTrace supports multiple API providers for enhanced functionality. Configure your API keys in `config/10 ] Api setup/`:

### Supported APIs
- **Neutrino API** - Email validation and IP geolocation
- **Numverify** - Phone number validation
- **Numlookup** - Advanced phone number lookup
- **Abstract** - Email and IP intelligence
- **OsintDog** - Dark web monitoring
- **Telethon** - Telegram OSINT
- **Shodan** - Device and port scanning

---

## 💻 Usage

### Launch Application
```bash
python main.py
```

### Menu Structure
The application provides an interactive menu with the following sections:

1. **Information & Settings** (01-12)
   - About, Credits, Disclaimer, Support
   - Settings and Discord community

2. **Educational Content** (13-24)
   - OSINT methodology training
   - Security mindset & resources
   - Advanced tutorials

3. **OSINT Modules** (25+)
   - Phone number intelligence
   - Email analysis
   - Username searches
   - IP geolocation
   - Domain analysis
   - Social media profiling
   - Metadata extraction
   - Dark web monitoring

### Example Workflow
```
[>] Select an option: 28
[>] Enter target IP: 192.168.1.1
[Processing...]
[✓] Geolocation: United States, California
[✓] ISP: Example ISP
[✓] Organization: Example Corp
```

---

## 🔐 Security & Ethics

### OPSEC Guidelines
- Use VPN/Proxy for operational security
- Cover your digital footprint
- Respect privacy laws and regulations
- Review the OPSEC section before conducting investigations

### Legal Notice
⚠️ **NullTrace is designed for legitimate security research and authorized investigations only.** Users are responsible for:
- Complying with applicable laws and regulations
- Obtaining proper authorization before investigating individuals
- Respecting privacy and data protection laws (GDPR, CCPA, etc.)
- Using information ethically and responsibly

---

## 📊 Results

All investigation results are saved in the `results/` directory:
```
results/
├── ip/
│   ├── 149.87.215.41/
│   └── [investigation data]
├── email/
├── domain/
└── [other_categories]/
```

---

## 🤝 Community & Support

- **Discord Server** - Active community of OSINT professionals
- **GitHub Issues** - Report bugs and request features
- **Email Support** - Direct assistance for enterprise users
- **Contributing** - We welcome improvements and new modules

---

## 🎓 Learning Path

1. Start with **Tutorial Tools** (13) and **OSINT Fundamentals** (14)
2. Review **Methodology** (22) and **Mindset** (21)
3. Study **Resources** (23) and **Practice** (24)
4. Begin with simple modules (IP, Domain, Username)
5. Progress to advanced techniques (Dark Web, Crypto)

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

---

## ⚖️ Legal Disclaimer

This tool is provided for **educational and authorized security research purposes only**. Users assume all responsibility for their actions. The developers of NullTrace:

- Do **not** endorse illegal activities
- Are **not** responsible for misuse of this tool
- Require **explicit authorization** before investigating individuals
- Recommend compliance with **all applicable laws**

By using this tool, you agree to use it responsibly and ethically.

---

## 🙏 Credits & Attribution

NullTrace is built upon the knowledge and tools developed by the global OSINT community. Special thanks to:
- Security researchers and investigators
- Open source contributors
- API providers and data services
- OSINT methodology pioneers

---

<div align="center">

**NullTrace: Intelligence Without a Trace**

*Built for professionals. Designed for accuracy. Created for the curious.*

</div>
