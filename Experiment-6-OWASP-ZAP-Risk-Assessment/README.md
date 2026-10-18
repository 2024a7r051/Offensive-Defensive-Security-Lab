
# Experiment No. 6

## Website Risk Assessment Using OWASP ZAP

### Aim
To scan a web application using OWASP ZAP and identify vulnerabilities according to the OWASP Top 10 checklist.

### Requirements
- Kali Linux
- Metasploitable 2
- OWASP ZAP
- DVWA web application
- VirtualBox

### Theory
OWASP ZAP is a web application security testing tool used to detect vulnerabilities such as SQL Injection, Cross-Site Scripting (XSS), and security misconfigurations.

### Procedure

**Step 1: Configure Network**

Configure Kali Linux with NAT and Host-Only adapters. Connect Metasploitable 2 to the Host-Only network.

![Network Configuration](images/step1-network-configuration.png)

**Step 2: Find IP Addresses**

Run the following command:

ip addr

![IP Addresses](images/step2-ip-addresses.png)

**Step 3: Test Connectivity**

ping -c 4 192.168.56.101

![Connectivity Test](images/step3-connectivity-test.png)

**Step 4: Access DVWA**

Open the browser and visit:

http://192.168.56.101/dvwa/

![DVWA Login](images/step4-dvwa-login.png)

**Step 5: Install and Launch OWASP ZAP**

sudo apt update
sudo apt install zaproxy -y
zaproxy

![OWASP ZAP](images/step5-launch-zap.png)

**Step 6: Start Automated Scan**

In ZAP, select **Quick Start → Automated Scan**. Enter the DVWA URL and click **Attack**.

![Automated Scan](images/step6-automated-scan.png)

**Step 7: View Vulnerabilities**

Open the **Alerts** section to view detected vulnerabilities and their risk levels.

![Vulnerability Results](images/step7-vulnerability-results.png)

**Step 8: Document Vulnerabilities**

Record the vulnerability name, severity, URL, evidence, and OWASP Top 10 category.

![Vulnerability Evidence](images/step8-vulnerability-evidence.png)

**Step 9: Generate Report**

Select **Report → Generate Report** and save the report in HTML or PDF format.

![ZAP Report](images/step9-zap-report.png)

### Result
OWASP ZAP was used to scan the DVWA web application and identify potential security vulnerabilities.

### Conclusion
The experiment demonstrated how OWASP ZAP detects web application vulnerabilities and helps assess website security.

