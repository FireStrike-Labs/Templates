
#### Purpose ####

It is essential for the Managed Detection & Response team to have a standardized set of information for escalating cases to clients' internal teams.

>Analysts are encouraged to expand upon this template based on the specifics of the incident they are investigating. However, they should not remove any items unless the information is not relevant to the case. 

>**This template shall be used by all MDR analysts when escalating a case to a client for action.**

#### Applicable Job Roles : ####
> L1/L2/L3 MDR Analyst(s)

Hello Team, 
---
This is {{ analyst name }} with the {{ company name}}, Managed Detection & Response (MDR) Team. We are reaching out today in regards to {{ escalation reason }}.

</br>
## Escalation Summary

{{ Provide high-level overview of reason for reaching out. About 4-6 sentences }}

</br>
---
</br>
## Incident Details
</br>

| Field                     | Artifact                                                                                                           |
| ------------------------- | ------------------------------------------------------------------------------------------------------------------ |
| **Detection Time (UTC)**      | {{detection time in UTC}}                                                                                          |
| **Hostname**              | {{affected endpoint name}}                                                                                         |
| **Username**              | {{affected user}}                                                                                                  |
| **Operating System**      | {{affected endpoint operation system}}                                                                             |
| **IP Address(es)**        | {{affected endpoint IP address; ensure IP addresses are de-fanged (i.e, 92.168.1[.]1, hxxps://www.example[.]com)}} |
| **Threat IP Address(es)** | {{malicious IP addresses if present}}                                                                              |
| **Threat File Path**      |                                                                                                                    |
| **Threat File Hash**      |                                                                                                                    |

**Threat Process Tree**: _display process tree in the ascii art format below_

malicious.exe
|
+-- rundll32.exe
    |
    +-- powershell.exe (network connection to hxxp://malicious-site[.]com)

</br>
---
</br>
## Actions Taken
</br>
{{ Provide details about what has been done to contain and/or eradicate the source of the incident }}
</br>
---
## Initial Recommendations
</br>
* Provide instructions or recommendations to the client to either help facilitate the containment, eradication, or remediation of an incident.
* Provide instructions or recommendations to the client to help facilitate closing the case out (i.e, verification of legitimacy of activity).
</br>
---
</br>
## Root Cause Analysis
<br>

- _In tabular format_
	- Cover the timeline of events
	- Cover the source, was it user generated, programatic, interactive, social engineering, etc.
	- Were there vulnerabilities exploited? Which vulnerabilities?
	- Is this a tactic seen in a recent campaign? Which one?

</br>
---
</br>
## Impact
<br>
- _Provide insights for why this presents risk to the organization and what the impact of that risk is or would be_
</br>
---
</br>
## References
<br>
>For additional details regarding the subject of this escalation communication, please refer to the information provided below.
<br>
* _In tabular format_ * 

| Resources Link                   | Description                                                                                                                                                                                              |
| -------------------------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| {{title resource appropriately}} | _{{Search the web and provide contextually relevant references about the threat. If this isn't feasible, do not provide a reference. The link to the case in the source platform is also a reference.}}_ |
</br>
---
<br>
Thank you for your attention to this matter. Should you require any further details or assistance, please do not hesitate to [email](mailto:<company support distro>) our support team. We are committed to supporting you through the resolution process and ensuring the security of your environment.
