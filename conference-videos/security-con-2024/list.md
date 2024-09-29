# Videos

_Schedule: https://cloudnativesecurityconna24.sched.com_

## Threat Modelling: How to Improve Your Kubernetes Security Posture with Threat Model? - Maxime Coquerel, Royal Bank of Canada (RBC)
*YouTube: https://www.youtube.com/watch?v=ouGmWEM5RmY*

- [OWASP Kubernetes Top Ten](https://owasp.org/www-project-kubernetes-top-ten/)
- Compromised nodes can inject kernel modules to compromise pods. Blacklist kernel modules that are not required.
    - [RedHat](https://access.redhat.com/solutions/41278)
    - [](https://nasniconsultants.com/how-to-secure-a-kubernetes-cluster-by-preventing-unwanted-modules-from-loading/open-source/2020/04/09/fikre/)

## CVE Context Matters, but Do All Vulnerabilities Really Matter? - Shubha Badve & Ross Tannenbaum

*YouTube: https://www.youtube.com/watch?v=5IEVNKa295g*

- Different vulnerability scanners give different results. Hard to decide which to trust.
- [Malicious Compliance](https://www.youtube.com/watch?v=9weGi0csBZM) covers how vulnerability scanners can be bypassed.
- CVSS score from NVD is important for compliance. CVSS v3.1 does not take into account context (where the software is running and who has access to it). CVSS v4.0 is trying to fix this.
- Prioritize Known External Vulnerabilities (KEV) from CISA.