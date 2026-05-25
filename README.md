# IOTGUARD

**Enterprise Network Device Vulnerability Scanner**

Defensive security assessment tool to identify, fingerprint, and mitigate risks in connected IoT devices across enterprise environments.

### Architecture
- **Backend**: Flask (Python)
- **Scanning Engine**: Nmap integration (custom fingerprinting & risk rules)
- **Frontend**: TailwindCSS

### Core Capabilities
- **Network Discovery**: Safely enumerates active devices via CIDR subnets.
- **Risk Assessment**: Automated heuristics mapping open ports and services to a local mitigation database.
- **Reporting Engine**: Generates JSON-based vulnerability reports for compliance teams.

### Setup
```bash
git clone https://github.com/Diode11-Alt/IoTGuard.git
cd IoTGuard
pip install -r requirements.txt
# Requires nmap installed locally
python3 app.py
```

---
*Developed by Sujal Mainali · [GitHub](https://github.com/Diode11-Alt)*
