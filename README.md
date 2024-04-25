# User Entity Behavior Analytics (UEBA)

The following research was conducted in 2022, focusing on User Entity Behavior Analytics (UEBA) and its processes. The aim was to comprehend the fundamental concepts of this specific cybersecurity management process.

## UEBA Process
**Step One. Data Collection**
UEBA systems gather data from various sources within the organisation's IT infrastructure. These sources may include system logs, application logs, network devices, network traffic, user directories, and other relevant data repositories.

**Step Two. Data Normalisation**
The collected data undergoes normalisation, where it is standardised into a common format. 

**Step Three. Data Analysis**
The normalised data is then analysed using a combination of predefined rules, anomaly detection algorithms, and machine learning techniques.

**Step Four. Behaviour Profiling** 
UEBA systems build behavioral profiles for individual users and entities based on their historical activities.

**Step Five. Anomaly Detection** 
The system continuously monitors user activities and compares them against established behavioural profiles. Any deviations or anomalies that are identified are flagged for further investigation.

**Step Six. Alerting** 
When suspicious activities or anomalies are detected, the UEBA system generates alerts to notify security analysts or administrators. These alerts provide details about the detected anomalies, their severity, and any relevant contextual information.

**Step Seven.  Investigation and Response** 
Security analysts investigate the alerted anomalies to determine their nature and potential impact on the organisation's security.

**Step Eight. Risk Scoring** 
UEBA systems assign risk scores to users and entities based on the severity and frequency of detected anomalies.

**Step Nine. Continuous Improvement**
Over time, UEBA systems continuously learn from new data and feedback to improve their accuracy and effectiveness in detecting security threats.

## Research Materials

The typical objective of a Cyber Security Professional is to safeguard the organisation's network from external threats, for which various precautionary measures are implemented, such as firewalls, IDS, IPS, Proxy servers, and security gateways. However, there is often a lack of precautionary measures taken against insider attacks. Legitimate users frequently possess more rights and access control authorizations compared to non-legitimate users. This raises security concerns regarding the protection of confidential information if legitimate users are compromised. There is a necessity to shift the focus of the cybersecurity domain from system and network vulnerabilities to usage anomalies. The limitations of traditional cybersecurity products encompass:


    1. No Protection against Insider Attacks
    2. No Centralised Security Management
    3. No Users Activity and Role Management
    4. No Correlation between Users and Security Events
    5.Data Exfiltration not handled
    6. Security Patch management is tedious
    7. Incident forensics is not effective
    8. No Privileged Identity Management
    9. No Threat Intelligence or Incident Reporting
    

User and Entity Behavior Analytics (UEBA) represents a novel approach to identifying user activities and insider threats within an organisation. UEBA employs predefined rules, anomaly detection, and machine learning techniques in its pursuit of detecting insider attacks. The system detects anomalous user behaviors and assigns them a weight based on the severity and confidence level of the detection. These weighted anomalies contribute to computing a risk score for individual users, thereby facilitating the identification of compromised users (Khaliq et al., 2020).

## Referencing 
Khaliq, S., Tariq, Z. U. A., & Masood, A. (2020). Role of User and Entity Behavior Analytics in Detecting Insider Attacks.  https://doi.org/10.1109/iccws48432.2020.9292394


