# Experiment 8: Network Scanning and Vulnerability Assessment

## Aim
To identify open ports and running services using Nmap and detect known vulnerabilities using Nessus.

## Requirements
- Kali Linux
- Metasploitable 2
- VirtualBox
- Nmap
- Nessus

## Theory
Nmap (Network Mapper) is a network reconnaissance tool used to identify active hosts, open ports and running services. Nessus is a vulnerability scanning tool used to detect known security weaknesses in a system. Together, these tools help identify possible security risks and improve network protection.

## Procedure
1. Set up Kali Linux and Metasploitable 2 as attacker and target machines in VirtualBox.
2. Start both virtual machines and connect them to the same lab network.
3. Find the IP address of the target machine.
4. Open the Kali Linux terminal and perform host discovery using Nmap.
5. Scan the target machine to identify open ports and services.
6. Open Nessus and create a new vulnerability scan.
7. Enter the target machine's IP address and start the scan.
8. Analyze the scan report and identify the vulnerabilities found.
9. Record the findings and suggest suitable security measures.

## Result
Successfully studied network scanning using Nmap and vulnerability detection using Nessus.

## Conclusion
The experiment demonstrated how Nmap and Nessus help identify open ports, running services and security vulnerabilities. Regular scanning and patching help improve network security.

---

# Experiment 9: Password Guessing Using Hydra

## Aim
To understand password guessing attacks using Hydra and test password security in a controlled lab environment.

## Requirements
- Kali Linux
- Metasploitable 2
- VirtualBox
- Hydra tool
- SSH or FTP service
- Password wordlist

## Theory
Hydra is a password-testing tool used to perform automated login attempts against different network services. It uses username and password combinations from wordlists to check whether weak credentials can be guessed. It supports services such as SSH and FTP. This experiment helps understand the importance of strong passwords and secure authentication.

## Procedure
1. Start Kali Linux and Metasploitable 2 in VirtualBox.
2. Connect both machines to the same isolated lab network.
3. Find the IP address of the target machine.
4. Check whether SSH or FTP service is running on the target.
5. Open the Kali Linux terminal and verify that Hydra is installed.
6. Prepare a small password wordlist for testing. Kali also provides wordlists such as `/usr/share/wordlists/rockyou.txt`.
7. Use Hydra only against the authorized lab target to perform controlled password testing.
8. Observe the output and identify weak test credentials, if any.
9. Record the findings and recommend strong passwords and account protection measures.

## Result
Successfully studied password guessing using Hydra in a controlled virtual lab environment.

## Conclusion
The experiment demonstrated the risks of weak passwords and highlighted the importance of strong passwords and secure authentication.

---

# Experiment 10: Phishing Simulation Using GoPhish

## Aim
To understand how phishing campaigns are designed and executed by creating and running a simulated phishing attack using GoPhish in a controlled lab environment.

## Requirements
- Computer or laptop
- GoPhish tool
- Web browser
- Internet connection
- Test email account
- Controlled lab environment

## Theory
GoPhish is an open-source phishing simulation tool used for security awareness training. It helps create simulated phishing campaigns to understand how attackers use fake emails and login pages to trick users. It allows security professionals to analyze user awareness and identify phishing-related risks. Phishing simulations help organizations improve email security and train users to recognize suspicious messages.

## Procedure
1. Download and set up the GoPhish tool on the computer.
2. Start GoPhish and open its administration interface in a web browser.
3. Log in to the GoPhish dashboard.
4. Create a test email template for the phishing awareness campaign.
5. Set up a landing page for the simulation without collecting real passwords or sensitive information.
6. Add authorized test recipients to the campaign.
7. Configure the campaign using the created email template and landing page.
8. Launch the simulation only for authorized test users in the controlled lab environment.
9. Observe the campaign results and analyze user responses.
10. Record the findings and suggest methods to improve phishing awareness.

## Result
Successfully studied the creation and execution of a simulated phishing campaign using GoPhish in a controlled environment.

## Conclusion
The experiment helped understand phishing techniques and the working of GoPhish. It also highlighted the importance of user awareness, email security and safe online practices.
