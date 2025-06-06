# Phishing Email Triage Lab

> A beginner-friendly, real world email phishing investigation lab using free tools and basic SOC analyst techniques.

---

## 🧠 Lab Overview

In this case study, I investigate a real phishing email that was attempting to trick the recipient into clicking a fake email verification link. I follow the steps a SOC analyst might take to analyze the email header, inspect the body, identify indicators of compromise (IOCs), and document findings in a clear format.

This lab simulates real world email triage tasks and shows how I would respond to a potential phishing incident in a SOC environment.

---

## 🧰 Skills Demonstrated

- Email header analysis
- IP address reputation lookup
- Quoted-printable decoding
- Phishing link inspection
- IOC identification
- Markdown documentation
- Organized GitHub repo structure

---

## 🛠️ Tools Used

### 🛠️ Tools Used

- [MXToolbox](https://mxtoolbox.com/) – For email header analysis and blacklist checks  
- [URLScan.io](https://urlscan.io/) – To safely analyze the behavior and reputation of suspicious URLs  
- [CyberChef](https://gchq.github.io/CyberChef/) – For decoding email content  
- [malware-traffic-analysis.net](https://www.malware-traffic-analysis.net/) – Source of phishing email samples used in this lab
- GitHub for case documentation

---

## 📁 Folder Structure

- [`1_raw_email/`](./1_raw_email) – Original .eml, screenshots of rendered message  
- [`2_header_analysis/`](./2_header_analysis) – Screenshots of header + IP analysis  + IP Blacklisting
- [`3_link_analysis/`](./3_link_analysis) – Suspicious link and HTML analysis  
- [`4_findings/`](./4_findings) – IOCs and case summary  
- [`5_extras/`](./5_extras) – Optional bonus notes or screenshots  


---

## 🔎 How to Use This Repo

Each folder contains screenshots and files that walk through how the investigation was performed. This lab is meant to showcase my understanding of email-based attacks and how to analyze them using basic free tools just like an entry-level SOC analyst would.

