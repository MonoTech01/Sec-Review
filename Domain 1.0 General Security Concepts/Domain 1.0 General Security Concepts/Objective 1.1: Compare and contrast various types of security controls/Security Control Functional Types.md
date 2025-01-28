# Security Control Functional Types

## Introduction
- Security controls can be classified by their *function* or *goal*.
- Understanding these functional types helps in designing a layered defense.

## Functional Types of Security Controls

1.  **Preventive Controls**
    -   Act to *eliminate or reduce* the likelihood of a successful attack.
    -   Operate *before* an attack takes place.
    -   Examples:
        -   `Access Control Lists (ACLs)` on firewalls.
        -   `Antimalware software`.
        -   File system access permissions.

2.  **Detective Controls**
    -   *Identify and record* attempted or successful intrusions.
    -   Operate *during* an attack.
    -   Examples:
        -   `Logs`.
        -   Intrusion Detection Systems (IDS).

3.  **Corrective Controls**
    -   *Eliminate or reduce* the impact of a security policy violation.
    -   Used *after* an attack.
    -   Examples:
        -   `Backup systems`.
        -   `Patch management systems`.
        -   Incident response procedures.

## Additional Control Types

1.  **Directive Controls**
    -   *Enforce a rule of behavior*.
    -   Examples:
        -   `Security policies`.
        -   `Employee contracts with disciplinary procedures`.
        -   Training and awareness programs.

2.  **Deterrent Controls**
    -   *Psychologically discourage* an attacker from attempting an intrusion.
    -   Examples:
        -   `Warning signs of legal penalties`.
        -   Security cameras with visible signage.

3.  **Compensating Controls**
    -   Substitute for a *primary control* when it cannot be implemented.
    -   Offer the same or better protection with a different methodology.
    -   Example:
        -   Using encryption to compensate for missing access control policies.

## Summary Table

| Control Type      | Function                      | Timing       | Examples                                                |
|-------------------|-------------------------------|--------------|---------------------------------------------------------|
| Preventive        | Eliminate/reduce attack likelihood | Before     | ACLs, Antimalware, File Permissions                |
| Detective         | Identify/record intrusions   | During     | Logs, Intrusion Detection Systems                     |
| Corrective        | Reduce impact of violations      | After      | Backups, Patch Management, Incident Response              |
| Directive         | Enforce rules of behavior    | Ongoing       | Policies, Employee Contracts, Training Programs      |
| Deterrent         | Discourage attacks          | Ongoing       | Warning signs, Visible security measures                |
| Compensating      | Substitute for primary control | Ongoing      | Alternative security measures                                |

## Layered Defense
-   Use a combination of different functional types for a robust security strategy.
-   A layered approach ensures that if one control fails, others can still protect the system.

## Actionable Items

1.  Think about the security controls in your personal or work life. Can you classify them into the functional types outlined?
2.  Imagine a situation where a specific control is not practical (e.g., a firewall isn't suitable). Can you propose a compensating control that would achieve similar security?
3.  Why is it important to have a mix of preventive, detective and corrective controls?
