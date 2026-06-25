# NIST Cybersecurity Framework (CSF) Report

## Incident Overview

The organization experienced a **Denial of Service (DoS)** attack caused by a large volume of ICMP packets directed at the internal network. The excessive traffic saturated network resources, causing critical network services to become unavailable for approximately two hours.

The investigation determined that the primary cause of the incident was an improperly configured firewall that failed to restrict malicious ICMP traffic.

---

# NIST CSF Analysis

## 1. Identify

### Incident

* Denial of Service (DoS)
* ICMP Flood attack

### Assets Affected

* Internal network
* Network services
* Business operations

### Vulnerability

* Firewall configuration allowed excessive ICMP traffic.
* Lack of preventive network filtering.

### Business Impact

* Network unavailable for approximately two hours.
* Employees unable to access network resources.
* Business operations interrupted.

---

## 2. Protect

The following controls were recommended to reduce the likelihood of similar incidents:

* Configure firewall rules to limit ICMP traffic.
* Implement ICMP rate limiting.
* Validate source IP addresses.
* Deploy IDS/IPS solutions.
* Maintain secure firewall configurations.

---

## 3. Detect

Detection capabilities should include:

* Continuous network monitoring.
* IDS/IPS alerts.
* Network traffic analysis.
* Log monitoring.
* Detection of abnormal ICMP traffic patterns.

---

## 4. Respond

During the incident, the organization performed the following actions:

* Blocked incoming ICMP traffic.
* Isolated affected network services.
* Restored critical services.
* Investigated the incident.
* Updated firewall security controls.

---

## 5. Recover

Recovery activities included:

* Restoring normal network operations.
* Verifying network stability.
* Monitoring for additional malicious activity.
* Implementing long-term security improvements.
* Documenting lessons learned.

---

# Lessons Learned

This incident demonstrated the importance of properly configured network security controls. Continuous monitoring, firewall maintenance, IDS/IPS deployment, and proactive security management significantly reduce the risk of future Denial of Service attacks.

---

# Key Takeaways

* Proper firewall configuration is critical.
* ICMP traffic should be monitored and controlled.
* Continuous monitoring enables faster detection.
* Incident response plans reduce downtime.
* Recovery should always include security improvements.

