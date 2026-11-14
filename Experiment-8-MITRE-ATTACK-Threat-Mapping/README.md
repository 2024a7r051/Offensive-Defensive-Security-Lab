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

## Step 1:

Set up Kali Linux and Metasploitable 2 as attacker and target machines in VirtualBox.

![Screenshot 1](images/step1-ip-ping.png)

## Step 2:

Start both virtual machines and connect them to the same lab network.

![Screenshot 2](images/step2-metasploit-console.png)

## Step 3:

Find the IP address of the target machine.

![Screenshot 3](images/step3-nmap-scan.png)

## Step 4:

Open the Kali Linux terminal and perform host discovery using Nmap.

![Screenshot 4](images/step4-exploit-result.png)

## Step 5:

Scan the target machine to identify open ports and services.

![Screenshot 5](images/step5-exploit-options.png)

## Step 6:

Open Nessus and create a new vulnerability scan.

![Screenshot 6](images/step6-system-info.png)

## Step 7:

Enter the target machine's IP address and start the scan.

![Screenshot 7](images/step7-attack-matrix.png)

## Step 8:

Analyze the scan report and identify the vulnerabilities found.

![Screenshot 8](images/step8-attack-technique.png)

## Step 9:

Record the findings and suggest suitable security measures.

![Screenshot 9](images/step9-defense-impairment.png)

## Result
Successfully studied network scanning using Nmap and vulnerability detection using Nessus.

## Conclusion
The experiment demonstrated how Nmap and Nessus help identify open ports, running services and security vulnerabilities. Regular scanning and patching help improve network security.


