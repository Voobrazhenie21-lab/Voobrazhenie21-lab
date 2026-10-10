<div align="center">
  <h1>Hey there, I'm Aleksei Zharkou 👋</h1>
  <h3>🛡️ Junior Penetration Tester & Cybersecurity Specialist (SOC / DevSecOps)</h3>
  <p>
    <b>Offensive Security | Active Directory Attacks | SIEM & Incident Response | Security Tooling in Python</b>
  </p>

  <p align="center">
    <a href="https://www.linkedin.com/in/aleksei-zharkou/"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
    <a href="https://t.me/Voobrazhenie_20"><img src="https://img.shields.io/badge/Telegram-2CA5E0?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
    <a href="mailto:lyosha.zharkov.98@mail.ru"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
    <a href="https://github.com/Voobrazhenie21-lab"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub" /></a>
  </p>
</div>

---

### 👨‍💻 About Me

I am a hands-on cybersecurity specialist focused on **Blue Team / SOC Incident Response (DFIR)**, **Infrastructure Penetration Testing (Active Directory)**, and **DevSecOps Security Tooling**. 

- 📍 Located in **Minsk, Belarus** (open to remote, hybrid, or on-site roles).
- 🎓 **Graduated (100% completed, Final Blue Team DFIR Diploma Defended)** from the **Skillbox «Cybersecurity Specialist 2.0»** professional program.
- 🛠️ Author of a complete **"Purple Team + DevSecOps" portfolio**:
  - 👁️ **[Blue Team Incident Investigation (`acme.skb`)](https://github.com/Voobrazhenie21-lab/blue-team-incident-investigation)** — end-to-end Wazuh SIEM & host forensics report
  - 🌐 **[Enterprise AD Pentest Report](https://github.com/Voobrazhenie21-lab/enterprise-pentest-report)** — PTES / OWASP / MITRE ATT&CK assessment
  - 🛡️ **[PipeShield](https://github.com/Voobrazhenie21-lab/pipeshield)** — DevSecOps SAST/CI-CD scanner with OASIS SARIF 2.1.0 support
- 🧠 Prior 5-year background in **clinical psychology and university teaching**: brings a strong edge in **human factor analysis (social engineering, phishing)**, meticulous forensic documentation, and stress resilience during incident response.
- 🎯 Looking for: **Junior SOC Analyst (L1/L2)**, **Incident Responder (DFIR)**, **Junior Penetration Tester**, or **Junior DevSecOps Engineer** roles.

---

### 🚀 Featured Security Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>👁️ <a href="https://github.com/Voobrazhenie21-lab/blue-team-incident-investigation">Blue Team Incident Investigation (DFIR)</a></h3>
      <p><b>Enterprise AD & DMZ Compromise Forensics (<code>acme.skb</code>)</b> &bull; <a href="https://voobrazhenie21-lab.github.io/blue-team-incident-investigation/">[Live Report]</a></p>
      <ul>
        <li>Reconstructed a 12-tactic <b>MITRE ATT&CK</b> kill chain across Linux DMZ (<code>web-server</code>) and Windows AD (<code>ws01</code>, <code>dc01</code>) via <b>Wazuh SIEM 4.3.9</b>.</li>
        <li>Uncovered root compromise via <code>backdoor.php</code> on Apache 2.4.57 compiled with <code>-DBIG_SECURITY_HOLE</code>, <code>/etc/shadow</code> theft, and <code>sshd -R</code> pivoting.</li>
        <li>Proved execution of deleted Win32k LPE exploit (<code>CVE-2019-0623.exe</code>) via <b>WER AppCrash</b> forensics, <code>mimikatz.exe</code> execution over <code>\\tsclient</code> RDP share, <b>Pass-the-Hash</b> (Rule 92652) DC takeover, and exfiltration of <code>TOP SECRET!.txt</code>.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🌐 <a href="https://github.com/Voobrazhenie21-lab/enterprise-pentest-report">Active Directory Pentest & Threat Assessment</a></h3>
      <p><b>Enterprise AD Domain Exploitation & PTES Report</b> &bull; <a href="https://voobrazhenie21-lab.github.io/enterprise-pentest-report/">[Live Report]</a></p>
      <ul>
        <li>Mapped domain ACLs and privilege escalation paths using BloodHound CE & SharpHound.</li>
        <li>Executed Kerberoasting (RC4-HMAC), SMB NTLM Relay, Pass-the-Hash, and ACL abuse (<code>GenericAll</code>) to achieve Domain Admin.</li>
        <li>Full executive & technical audit report with CVSS v3.1 scoring and remediation roadmap (SMB signing, LAPS, gMSA).</li>
      </ul>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🛡️ <a href="https://github.com/Voobrazhenie21-lab/pipeshield">PipeShield</a></h3>
      <p><b>Next-Gen DevSecOps Pipeline Security Scanner</b> &bull; <a href="https://voobrazhenie21-lab.github.io/pipeshield/">[Live Demo]</a></p>
      <ul>
        <li>Static security analysis (SAST) auditing code, Dockerfiles, and CI/CD pipelines.</li>
        <li>Shannon entropy engine to eliminate false positives in secret detection.</li>
        <li>CIS Docker Benchmarks & CI/CD supply chain risk enforcement.</li>
        <li>Exports to <b>OASIS SARIF 2.1.0</b> (GitHub Code Scanning) & interactive HTML dashboard.</li>
        <li><i>Tech:</i> Python, Pytest, Click, Rich, GitHub Actions CI/CD.</li>
      </ul>
    </td>
    <td width="50%" valign="top">
      <h3>🔍 <a href="https://github.com/Voobrazhenie21-lab">Log Sentinel</a></h3>
      <p><b>Python Threat Detection & Incident Triage Tool</b></p>
      <ul>
        <li>Zero-dependency CLI tool parsing Linux <code>auth.log</code> & Windows Security Events (4625/4769).</li>
        <li>Detects SSH brute force, password spraying, and Kerberoasting (RC4 TGS <code>0x17</code>).</li>
        <li>Extracts structured forensic evidence with remediation guidance in JSON.</li>
        <li><i>Tech:</i> Python Standard Library, Regex, Windows Event Logging.</li>
      </ul>
    </td>
  </tr>
</table>

---

### 🧰 Tech Stack & Security Arsenal

<p align="center">
  <img src="https://img.shields.io/badge/Wazuh_SIEM-00599C?style=flat-square&logo=security&logoColor=white" />
  <img src="https://img.shields.io/badge/Kali_Linux-557C94?style=flat-square&logo=kali-linux&logoColor=white" />
  <img src="https://img.shields.io/badge/Ubuntu-E95420?style=flat-square&logo=ubuntu&logoColor=white" />
  <img src="https://img.shields.io/badge/Windows_Server-0078D6?style=flat-square&logo=windows&logoColor=white" />
  <img src="https://img.shields.io/badge/Active_Directory-00599C?style=flat-square&logo=microsoft&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white" />
  <img src="https://img.shields.io/badge/PowerShell-5391FE?style=flat-square&logo=powershell&logoColor=white" />
</p>

| Category | Tools & Technologies |
|:---|:---|
| **Blue Team, SOC & DFIR** | Wazuh SIEM (Rules 60204, 92652, 506), TheHive, Windows Event Logs (4624/4625/4769, Defender 1116/5001), WER Forensics, LNK/Recycle.Bin Artifacts, Linux `auditd`, FIM |
| **Offensive Security & AD** | Nmap (NSE), BloodHound CE, SharpHound, Mimikatz, Impacket (`ntlmrelayx`), Hashcat, Hydra, Kerberoasting, Pass-the-Hash, OWASP Top 10 |
| **DevSecOps & Tooling** | Static Analysis (SAST), Shannon Entropy, CIS Docker Benchmarks, GitHub Actions Security, OASIS SARIF 2.1.0, Pytest |
| **Infrastructure & Networking** | L2/L3 Protocols (STP 802.1D/w, 802.1Q VLAN, 802.1X, ARP), TCP/IP, DHCP (DORA), DNS, NAT, GRE/SSH Tunneling, Wireshark, WireGuard VPN |

---

### 📊 GitHub Activity & Stats

<p align="center">
  <img src="https://streak-stats.demolab.com/?user=Voobrazhenie21-lab&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</p>

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=Voobrazhenie21-lab&color=2563eb&style=flat-square&label=PROFILE+VIEWS" alt="Profile Views" />
  <img src="https://img.shields.io/badge/Security_Portfolio-DFIR_%7C_Pentest_%7C_PipeShield-blue?style=flat-square&logo=github" alt="Security Projects" />
  <img src="https://img.shields.io/badge/Status-Open_for_Opportunities-brightgreen?style=flat-square" alt="Status" />
</p>

---

<div align="center">
  <p><i>"Security is not a product, but a process." — Bruce Schneier</i></p>
  <p>Feel free to reach out via <a href="https://t.me/Voobrazhenie_20">Telegram (@Voobrazhenie_20)</a> or <a href="https://www.linkedin.com/in/aleksei-zharkou/">LinkedIn</a>!</p>
</div>
