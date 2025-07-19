#### Purpose ####

This template provides a standardized format for escalating cases to a client's security team. It can be adapted for any threat detection or incident response scenario.

>Feel free to expand upon this template based on the specifics of the incident you are investigating. However, avoid removing items unless they do not apply.

>**Use this template whenever you escalate a case to a customer for action.**

#### Applicable Job Roles : ####
> Security Analyst

Hello Team,
---
This is {{ analyst name }} with the {{ company name }} Security Team. We are reaching out today about {{ escalation reason }}.

</br>
## Escalation Summary

{{ Provide a high-level overview describing why you are escalating. Include 4-6 succinct sentences. }}

</br>
---
</br>
## Incident Details
</br>
| Field                     | Artifact                                                                  |
| ------------------------- | ------------------------------------------------------------------------- |
| **Detection Time (UTC)** | {{ detection time in UTC }} |
| **Hostname**              | {{ affected endpoint name }} |
| **Username**              | {{ affected user }} |
| **Operating System**      | {{ affected endpoint operating system }} |
| **IP Address(es)**        | {{ affected endpoint IP addresses; defang as needed (e.g., 192.168.1[.]1) }} |
| **Threat IP Address(es)** | {{ malicious IP addresses if present }} |
| **Threat File Path**      | |
| **Threat File Hash**      | |

**Threat Process Tree**: _display the process tree in ASCII art format below_

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
{{ Detail the steps taken to contain or eradicate the incident source. }}
</br>
---
## Initial Recommendations
</br>
* Provide instructions or recommendations to help facilitate containment or remediation.
* Provide any guidance the client needs to verify the legitimacy of the activity or to close the case.
</br>
---
</br>
## Root Cause Analysis
<br>
- _In tabular format_
        - Outline the timeline of events.
        - Identify the source: user generated, programmatic, interactive, social engineering, etc.
        - Note any vulnerabilities exploited.
        - Reference known campaigns if applicable.
</br>
---
</br>
## Impact
<br>
- _Describe why this presents risk and what the potential impact is._
</br>
---
</br>
## References
<br>
>For more information regarding this escalation, consult the links below.
<br>
* _In tabular format_ *

| Resources Link                   | Description |
| -------------------------------- | -------------------------------------------------------------- |
| {{title resource appropriately}} | _{{Provide relevant references or a link to the case in your platform.}}_ |
</br>
---
<br>
Thank you for your attention to this matter. If you need further assistance, please [email](mailto:<company support distro>) our support team. We are committed to ensuring the security of your environment.
