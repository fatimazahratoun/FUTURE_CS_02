# FUTURE_CS_02
Future Interns SOC Internship - SECURITY ALERT MONITORING &amp; INCIDENT RESPONSE
# 🛡️ FUTURE_CS_02 - SOC Incident Response Analysis

## 🔍 Project Overview
**Future Interns Cybersecurity Internship**  
**Security Operations Center (SOC) Task 2**  
Security Alert Monitoring & Incident Response Simulation

### 📋 Incident Summary
- **ID**: IR-2025-007
- **Date**: July 3, 2025
- **Attack Type**: Coordinated Credential Stuffing
- **Affected Users**: 3 accounts (1 compromised)
- **Duration**: 4+ hours continuous activity

## 📁 Repository Contents

### **Main Files**
| File | Description |
|------|-------------|
| [📄 SECURITY_INCIDENT_REPORT.pdf](SECURITY_INCIDENT_REPORT.pdf) | Complete forensic investigation report (18 pages) |
| [📄 SOC_Task2_Sample_Logs.txt](SOC_Task2_Sample_Logs.txt) | Original log data provided for analysis |
### **📂 CSV Data Analysis**
| File | Analysis Type | Records |
|------|--------------|---------|
| [📄 csv_data/timeline_analysis.csv](csv_data/timeline_analysis.csv) | Chronological attack timeline | 13 events |
| [📄 csv_data/user_charlie_connection_attempts.csv](csv_data/user_charlie_connection_attempts.csv) | Charlie-specific attacks | 5 attempts |
| [📄 csv_data/all_users_connection_attempts.csv](csv_data/all_users_connection_attempts.csv) | All connection attempts | 21 attempts |

## 🎯 Key Investigation Findings

### 🔥 Critical Discoveries
1. **Early Malware** - Detected at 05:06:14 (43 minutes before main attack)
2. **Account Compromise** - User "charlie" breached via 172.16.0.3
3. **Coordinated Attack** - 4 IPs systematically targeting 3 users
4. **Lateral Movement** - Internal network pivoting detected

### 📊 Attack Statistics
| Metric | Value |
|--------|-------|
| Total Security Events | 13 |
| Attack Duration | 4h 2min |
| Compromised Accounts | 1 (charlie) |
| Targeted Accounts | 2 (david, bob) |
| Malicious IP Addresses | 6 |

## 🔧 Technical Analysis

### Attack Infrastructure
