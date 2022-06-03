---
{"dg-publish":true,"permalink":"/62-encyclopedic/20220419105747-3-principles-of-information-security/","dgHomeLink":true,"dgPassFrontmatter":false}
---


# 3 Principles of Information Security

> [[62-Encyclopedic/20220419105949-information-security|!word]]
>
> ![[Pasted-image-20220419105822.png|300]]
>
> 1.  [[62-Encyclopedic/62.01-security-plus/20220602125634-confidentiality|Confidentiality]]
> 2.  Integrity
> 3.  Availability

The ultimate goal of [[62-Encyclopedic/20220419105949-information-security|Information Security]] is to maintain the above CIA triad within an organization.

## Confidentiality

> [!note] Confidentiality
> Ensuring that only the authorized users have access to information.

When confidentiality has been compromised when unauthorized parties gain access to individual's information.

### Security Controls to Maintain Confidentiality

- Encryption
- Strong [[62-Encyclopedic/20220319080333-passwords|Passwords]]
  - [[62-Encyclopedic/20220319080333-passwords|Passwords]]
  - [[62-Encyclopedic/20220319080913-password-requirements|Password Requirements]]
- [[62-Encyclopedic/20220318214141-multi-factor-authentication|Multi-factor Authentication]]
- [[62-Encyclopedic/20220419110907-identity-and-access-management|Identity and Access Management]]
- [[62-Encyclopedic/20220419111050-technical-controls|Technical Controls]]
- [[62-Encyclopedic/20220419111148-physical-security-measures|Physical Security Measures]]

## Integrity

> [!note] Integrity
> The trustworthiness and accuracy of information. Ensuring that information is not being modified by the unauthorized, else, it will be a violation of the information's integrity.

- You need to have a means of knowing whether or not a document has been modified without your knowledge so that you can trust that document's integrity.
- In the event data is lost, you need to **be able to recover all of that data** or at least most of it from **a trusted source**

> [!IDEA]
> So maybe encryption [[62-Encyclopedic/20220419121809-hash|hash]] and check digit or sth like that.

### Security Controls to Maintain Integrity

- [[62-Encyclopedic/20220419121809-hash|Hash]]
- [[62-Encyclopedic/20220419122102-secure-backup|Secure Backup]]
- [[62-Encyclopedic/20220419122243-user-access-control|User Access Control]]

## Availablility

> [!WORD] Availability
> Ensure that the information is accessible to authorized people when ever it is needed. Most companies want availability of at least 99.99%.

## Ensure High Uptime

- [[62-Encyclopedic/20220419173823-offsite-backup|Offsite backup]]
- [[62-Encyclopedic/20220419123704-disaster-recovery-plan|Disaster Recovery]] & [[62-Encyclopedic/20220419141321-business-continuity-plan|Business Continuity Plan]]
- [[62-Encyclopedic/20220421223107-redundancy|Redundancy]]
- [[62-Encyclopedic/20220421223232-failover|Failover]]
- [[62-Encyclopedic/20220421223322-virtualization|Virtualization]]
- Proper Monitoring of the environment
  - Can know asap when there is a problem with my environment
  - Can use tools such as [[62-Encyclopedic/20220421223630-security-information-and-event-management|SIEM]]
