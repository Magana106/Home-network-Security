# Home Network Security Assessment

## 🎯 Project Overview

**Objective:** 
I Conducted a thorough security assessment of my home network to identify vulnerabilities, misconfigurations, and security gaps using industry-standard reconnaissance tools and methodologies.

**Duration:** 8 hours over one weekend

**Environment:** Home network (192.168.1.0/24), Qatar

**Skill Level:** Entry-level SOC Analyst

## 🔧 Tools & Technologies

- **Nmap 7.95** - The tool itself and its a network reconnaissance used by security proffessionals
- **Service Detection** (`sV`) - Identifies the software that is running
- **NSE Scripts** (`sC`) - Automated vulnerability detection
- **SSL Certificate Analysis** - Certificate validation and expiration checking

## 📊 Key Findings

### Finding #1: Expired SSL/TLS Certificate (MEDIUM Severity)

**Discovery:**

- Router's HTTPS admin interface using certificate expired  365 days ago
- Detected via Nmap SSL certificate validation scripts
- Creates potential MITM vulnerability

**Risk Assessment:**

- **CVSS Score:** 5.3 (Medium)
- **Impact:** Medium (credential interception possible)
- **Likelihood:** Low (requires local network access + active MITM)
- **Overall Risk:** Medium

**Status:** Documented with compensating controls pending credential recovery

**Remediation Approach:**

- Professional risk management when immediate fix blocked by access constraints
- Implemented compensating controls (strong WiFi encryption, minimal access, monitoring)
- Escalation plan created for ISP support coordination
- Demonstrates real-world security operations beyond simple "find and fix"

## 💡 What This Project Demonstrates

### Technical Skills

✅ Network reconnaissance using Nmap

✅ Service version detection and enumeration

✅ SSL/TLS certificate validation

✅ Vulnerability identification through scripting

✅ Evidence collection and preservation

### Professional Skills

✅ Risk assessment (likelihood × impact)

✅ CVSS scoring methodology

✅ Professional security reporting

✅ Compensating control implementation

✅ Stakeholder communication

### Real-World Understanding

✅ Security operations involves constraints

✅ Risk management vs. risk elimination

✅ Cross-functional coordination requirements

✅ Documentation maintains accountability

✅ Not all findings = immediate fixes
