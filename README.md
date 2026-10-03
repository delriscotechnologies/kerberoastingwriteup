<h1 align="center">KERBEROASTING</h1>

<p align="center">
  An Active Directory lab exploring Kerberos service tickets, offline password recovery, and service-account protection.
</p>

<p align="center">
  <a href="https://delriscotechnologies.github.io/kerberoastingwriteup/">Full Write-Up</a>
</p>

---

This write-up follows a controlled Active Directory lab to explore how service-account passwords can be tested offline.

It looks at how authentication, password choices, and account permissions work together to protect an Active Directory environment, and how weaknesses in those areas can increase the impact of an attack.

## References

- [GhostPack: Rubeus](https://github.com/GhostPack/Rubeus)
- [NIST SP 800-63B-4](https://pages.nist.gov/800-63-4/sp800-63b.html)
- [HackTricks: Kerberoast](https://hacktricks.wiki/en/windows-hardening/active-directory-methodology/kerberoast.html)
- [Microsoft: Kerberoasting mitigation guidance](https://www.microsoft.com/en-us/security/blog/2024/10/11/microsofts-guidance-to-help-mitigate-kerberoasting/)
- [Microsoft: Authentication methods and phishing-resistant MFA](https://learn.microsoft.com/en-us/entra/identity/authentication/overview-authentication)
